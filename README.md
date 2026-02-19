# acceleration-game

LabVIEW-based program for evaluating trial success based on acceleration trends.

## Overview

This program is designed to monitor and compare acceleration data between successive trials. It provides a visual or logical judgment on whether a trial was "successful" (i.e., achieved faster acceleration than the previous one).

## Features

- **Acceleration Comparison**: Tracks maximum or average acceleration across trials.
- **Success/Failure Judgment**: Real-time feedback based on performance improvement.
- **LabVIEW GUI**: Visual interface for monitoring sensor data and trial results.

## Requirements

- NI LabVIEW 2019 or later
- Compatible DAQ (Data Acquisition) hardware or simulated acceleration input

## Setup

1. Open `LABVIEW1.vi` in LabVIEW.
2. Configure your acceleration sensor input channels.
3. Run the VI.

## Usage

1. Start the first trial to establish a baseline.
2. Perform subsequent trials.
3. The program will indicate "Success" if the current trial's acceleration exceeds the previous one.
