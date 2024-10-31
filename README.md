# FRA231-LAB1-B02-43-48-77

## Assignment Lab 1 - Sensor Characteristics

This repository contains the code and resources for Lab 1, focusing on characterizing various sensors using the Nucleo G474RE board. The experiments covered include the Load Cell, Hall Sensor, and Potentiometer. Each sensor is examined for its unique characteristics, response, and application in real-world scenarios.

### Table of Contents
1. [Overview](#overview)
2. [Sensors](#sensors)
    - [Load Cell](#load-cell)
    - [Hall Sensor](#hall-sensor)
    - [Potentiometer](#potentiometer)
3. [Installation](#installation)
4. [Usage](#usage)
5. [License](#license)

---

### Overview
In this lab, we explore the working principles and characteristics of three sensors:
1. **Load Cell**: For measuring weight/force.
2. **Hall Sensor**: For detecting magnetic fields.
3. **Potentiometer**: For measuring and adjusting electrical potential.

### Sensors

#### Load Cell
- **Description**: A load cell measures the force or weight applied to it and outputs a voltage signal proportional to the applied force.
- **Setup**: The Nucleo G474RE board is used to read the output from the Load Cell through an INA125 instrumentation amplifier.
- **Objective**: To analyze the relationship between applied force and output voltage, exploring calibration and signal conditioning.

#### Hall Sensor
- **Description**: A Hall sensor detects the presence and magnitude of a magnetic field.
- **Setup**: The Nucleo G474RE board captures the sensor’s response to changes in magnetic flux density.
- **Objective**: To observe the sensor’s output response to magnetic field variations and compare it with theoretical data.

#### Potentiometer
- **Description**: A potentiometer is used to measure or adjust voltage by varying its resistance.
- **Setup**: The Nucleo G474RE board reads the output voltage from the potentiometer as its position is varied.
- **Objective**: To study the relationship between the rotation angle of the potentiometer and its output voltage, converting analog to digital signals.

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Lworakan/FRA231-LAB1-B02-43-48-77.git
