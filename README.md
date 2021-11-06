# How-to-Gather-and-Visualize-Performance-Stats-for-Akai-MPC-Live-X-and-One

## Overview
The `Akai MPC` (Live, X and One) runs Linux on the 32 bit ARM architecture. As such, we can basically treat it like a `Raspberry Pi` when it comes to collecting stats.

## Requirements
- Download the `armv7` bits for `telegraf agent` from the `influxdata` team at `https://influxdata.com` (or follow my document link below which goes through the steps). On the MPC, the `telegraf aganet` can run on any USB, SD, etc. on your MPC.

- Enable SSH if needed.  See the excellent article at https://github.com/TheKikGen/MPC-LiveXplore/wiki/Enabling-SSH-on-the-MPC-Live-X-one-Force

## `TICK` Stack Required
You need at least `InfluxDB` up and running someplace for stats to get sent to.

For details see the "Performance Metrics Collection and Data Visualization" section of my write-up:

  https://github.com/mikenizo808/Building-the-Ultimate-Ubuntu-Desktop-on-a-Pre-Made-Gaming-PC


*Note: I recommend installing the entire `TICK` stack, version 1.x using `apt-get` as shown in the link above*
