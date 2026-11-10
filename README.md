Servo Motor Driver Using 555 Timer Experiment

Practical electronics lab experiment to build a simple servo motor driver circuit using a 555 timer IC configured to generate pulse-width modulated (PWM) control signals for position or speed control.

Hardware components:
- 555 Timer IC (U1 / IC1)
- 50 kOhm Potentiometer (Rpot1 / R4) for pulse width adjustment
- Resistors: 1 kOhm (R2, R3), 47 kOhm (R4 / R3')
- Capacitors: 0.22 uF polarized capacitor (C1), 100 nF / 0.01 uF capacitor (C2 / C1)
- Diodes: 2x 1N4148 (D1, D2)
- Power Source: 6V battery pack (or 4x AAA 1.5V batteries)
- Continuous / Standard Micro Servo Motor
- Terminal block, switch, and connection wires / breadboard

Circuit wiring steps:
1. Power Connections: Connect the positive supply line (VCC) from the 6V battery to pin 8 and pin 4 of the 555 timer IC, and connect the negative/ground line to pin 1.
2. Timing Network: Connect the potentiometer, resistors (R1, R2, R3, R4), and diodes (D1, D2) around pins 2, 6, and 7 to set up the astable/PWM oscillation frequency.
3. Capacitor Setup: Place the 0.22 uF capacitor across pins 2/6 and ground, and the 0.01 uF decoupling capacitor on pin 5.
4. Servo Motor Interface: Connect the servo motor control line (White/Signal wire) to output pin 3 of the 555 timer, connect the power wire (Red) through the switch to the positive supply, and connect the ground wire (Black) to the common ground.

Verification:
Adjust the 50k potentiometer to vary the pulse width output from pin 3, and observe the resulting motion and response of the servo motor.