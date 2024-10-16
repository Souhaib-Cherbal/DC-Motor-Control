# DC Motor Control Using a 4Q Reversible Chopper with IGBTs

## Project Overview

This project focuses on controlling the speed of a separately excited DC motor using a 4-quadrant (4Q) reversible chopper based on IGBTs (Insulated-Gate Bipolar Transistors). The goal is to simulate and implement a reliable speed control system for industrial applications that demand high-performance motor drives.

The project includes:

- **Simulink Modeling:** A detailed simulation of a 4Q chopper and its control over a DC motor.
- **Speed Control:** Implementation of both open-loop and closed-loop control systems for precise speed regulation.
- **Practical Validation:** Results from a practical setup that validate the theoretical models and simulations.

## Features

- **Hacheur 4Q Simulation:** Simulation of the motor control system using a reversible 4-quadrant chopper with IGBTs in Simulink.
- **Closed-Loop Speed Control:** Implementation of a PI controller to ensure stable speed even with variable loads.
- **Practical Experiments:** Validation of the simulation results with real hardware, comparing open-loop and closed-loop control performance.

## Files Included

- `MCC Souhaib Cherbal.slx`: Simulink model file for the 4Q reversible chopper and DC motor control system.
- `Rapport.pdf`: Detailed report documenting the project, including system modeling, simulation results, and practical experiments.

## System Overview

The system comprises:

1. **Power Supply:** A single-phase 220V, 50Hz AC supply converted to DC using a full-wave rectifier.
2. **Reversible Chopper:** A 4Q chopper using IGBTs to provide bidirectional control of current flow and voltage polarity.
3. **DC Motor:** A separately excited DC motor with parameters tuned for this control system.

### Control Strategy

- **Open-Loop Control:** The speed of the motor is varied by adjusting the chopper's output voltage, but it lacks feedback, so disturbances can affect performance.
- **Closed-Loop Control:** A PI controller compensates for load disturbances, ensuring consistent motor speed by adjusting the input voltage based on speed feedback.

## Results

### Simulation Results

- **Open-Loop:** Shows motor speed fluctuations with changes in load torque.
- **Closed-Loop:** Maintains a steady motor speed regardless of load variations, demonstrating the effectiveness of the feedback system.

### Practical Results

The practical implementation confirms the accuracy of the simulations. Speed control in both open and closed loops shows that the closed-loop system offers superior performance, especially in applications requiring precise speed regulation.

## Conclusion

This project demonstrates the successful simulation and implementation of a speed control system for a DC motor using a 4Q reversible chopper. The use of Simulink allowed for detailed analysis and validation, and practical experiments provided real-world confirmation of the system's performance.

## Usage

To use the Simulink model:

1. Download `MCC Souhaib Cherbal.slx`.
2. Open the model in Simulink.
3. Run the simulation to see the open-loop and closed-loop control results.
