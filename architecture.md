# Architecture

## Overview

The system cools a 4S5P battery pack (20 cells) by combining passive heat absorption (PCM) with active heat removal (liquid-cooled cold plate).

## Heat path

```
Battery cells (4S5P)
        |  heat
        v
PCM layer: paraffin wax + 10% expanded graphite
        |  heat
        v
Aluminium cold plate (grooved)
        |  heat
        v
Copper tube in the grooves, with coolant flowing through it
        |
        v
Heat carried out of the pack by the coolant
```

## Components

**Battery pack.** 4S5P arrangement, 20 cells. This is the heat source during fast charging and high loads.

**PCM layer.** Paraffin wax is used because it absorbs a lot of heat while melting. Pure paraffin has low thermal conductivity, so 10% expanded graphite is added to improve heat spreading inside the PCM.

**Aluminium cold plate.** Aluminium conducts heat well. Grooves are made in the plate to hold the copper tube.

**Copper tube with coolant.** The tube sits in the grooves of the plate, so heat from the plate passes into the coolant and is carried away.

## Why both PCM and cold plate

- The PCM handles peak heat by absorbing it as it melts.
- The cold plate and coolant give continuous heat removal.
- Using both together is the main idea of this project.

## Design tool

CAD was used for the design.
