# acceleration-game

A LabVIEW-based prototype for trial-by-trial acceleration feedback.

## Project history

The original prototype was developed during my earlier research / coursework period (2023–2024) while learning experimental measurement, DAQ-based acquisition, and real-time feedback design. The repository was organized and published on GitHub later, so the Git commit history reflects the publication / maintenance period rather than the original development period.

## Overview

This program monitors acceleration across repeated trials and compares the current trial with the previous one. It provides a simple success / failure judgment as immediate feedback.

## What this project demonstrates

- LabVIEW-based experimental programming
- DAQ / sensor-oriented acquisition logic
- trial-by-trial performance comparison
- real-time feedback design
- early experience building human-in-the-loop experimental tools

## Features

- **Acceleration comparison**: compares maximum or average acceleration across successive trials
- **Success / failure judgment**: provides feedback when the current trial improves on the previous trial
- **LabVIEW GUI**: supports monitoring sensor input and trial results

## Requirements

- NI LabVIEW 2019 or later
- compatible DAQ hardware or simulated acceleration input

## Usage

1. Open `LABVIEW1.vi`.
2. Configure the acceleration-sensor / DAQ input.
3. Run the VI.
4. Use the first trial as the baseline.
5. Compare subsequent trials with the previous performance.

## Research direction

The basic idea in this prototype—measure a movement variable, evaluate trial performance, and return feedback—later connects naturally to adaptive sensorimotor feedback and human-in-the-loop AI systems.
