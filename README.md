# Three-Gate Parking Lot

A digital logic parking lot management system with a priority-based gate selection mechanism, car counting, and 7-segment display simulation.

## Features

- Three gates with priority-based selection
- Gate 1 has the highest priority
- Gate 2 has medium priority
- Gate 3 has the lowest priority
- Car count displayed from 0 to 7
- Full indication using a red LED
- Priority-based input selection
- 7-segment display for car count
- Proteus circuit simulation

## Components Used

- AND Gates
- OR Gates
- NOT Gates
- Push Buttons
- 74LS93 4-bit Binary Counter
- 74LS47 BCD to 7-Segment Driver
- Common-Anode 7-Segment Display
- Red LED
- Resistors

## Logic Design

The gate priority system is implemented using Boolean logic:

- G1 = G1
- G2 = G1' · G2
- G3 = G1' · G2' · G3

The selected gate inputs are combined using an OR gate to provide the counter input.

## Tools

- Proteus
- Digital Logic Design

## Project Report

The project report is included in this repository and contains the design methodology, Boolean expressions, circuit implementation, testing, and results.

## Authors

**Maheen Furqan**  
**Bareerah Haroon**  
**Arisha Mohsin**

FAST-NUCES, Islamabad
