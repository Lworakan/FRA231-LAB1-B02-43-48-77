# FRA231-LAB1-B02-43-48-77

## Assignment Lab 1 - Sensor Characteristics

This repository contains the code and resources for Lab 1, focusing on characterizing various sensors using the Nucleo G474RE board. The experiments covered include the Load Cell, Hall Sensor, Potentiometer, and Incremental Encoder. Each sensor is examined for its unique characteristics, response, and application in real-world scenarios.

### Table of Contents
1. [Overview](#overview)
2. [Sensors](#sensors)
    - [Load Cell](#load-cell)
    - [Hall Sensor](#hall-sensor)
    - [Potentiometer](#potentiometer)
    - [Incremental Encoder](#incremental-encoder)
3. [Installation](#installation)
4. [Usage](#usage)
5. [License](#license)

---

### Overview
In this lab, we explore the working principles and characteristics of four sensors:
1. **Load Cell**: For measuring weight/force.
2. **Hall Sensor**: For detecting magnetic fields.
3. **Potentiometer**: For measuring and adjusting electrical potential.
4. **Incremental Encoder**: For measuring rotational position, direction, and speed.

### Sensors

#### Load Cell
- **Description**: A load cell measures the force or weight applied to it and outputs a voltage signal proportional to the applied force.
- **Setup**: The Nucleo G474RE board reads the output from the Load Cell through an INA125 instrumentation amplifier.
- **Objective**: To analyze the relationship between applied force and output voltage, exploring calibration and signal conditioning.

#### Hall Sensor
- **Description**: A Hall sensor detects the presence and magnitude of a magnetic field.
- **Setup**: The Nucleo G474RE board captures the sensor’s response to changes in magnetic flux density.
- **Objective**: To observe the sensor’s output response to magnetic field variations and compare it with theoretical data.

#### Potentiometer
- **Description**: A potentiometer is used to measure or adjust voltage by varying its resistance.
- **Setup**: The Nucleo G474RE board reads the output voltage from the potentiometer as its position is varied.
- **Objective**: To study the relationship between the rotation angle of the potentiometer and its output voltage, converting analog to digital signals.

#### Incremental Encoder
- **Description**: An Incremental Encoder measures rotational position, direction, and speed by generating pulses as it rotates.
- **Setup**: The encoder is connected to the Nucleo G474RE board, where the pulses are read using either the Quadrature Encoder Interface (QEI) or Polling method.
- **Objective**: To analyze the encoder’s characteristics by reading pulses, calculating angular position, and deriving angular velocity. This includes studying the effects of resolution (x1, x2, x4) and implementing signal processing to convert raw pulse data to meaningful measurements.

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Lworakan/FRA231-LAB1-B02-43-48-77.git
