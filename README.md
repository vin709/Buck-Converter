# ⚡ Buck-Converter
This project is a discrete and educational buck converter using popular low cost ICs and discrete components such as diodes, bjts, MOSFET, 555 timer, op-amps and comparators. It features a voltage-controlled duty cycle, an op-amp error amplifier and integrator (PI controller), discrete asynchronous high-side N-MOSFET driver and OCP/OVP protection circuit.

## Features
* Input voltage range: 6V - 40V
* Max Output power: 20 W (Design Target) 
* Topology: Asynchronous Buck Converter
* PWM Generation: 555 Timer Sawtooth + LM393 Comparator
* High-side N-MOSFET driver: BJT Totem Pole + Bootstrap Capacitor
* Voltage Regulation: LM358 Error Amplifier/Integrator
* OCP/OVP Protection (Work-in-Progress)

## How a buck converter works
A buck converter or a DC-DC stepdown converter uses **Pulse Width Modulation (PWM)** to step down the input voltage effieciently. By varying the duty cycle or the length of ON time of the square wave, the amount of power that goes into the output can be lowered. An LC low pass filter then smooths out the voltage and the high frequency signals from the switching which supplies low noise, uninterrupted voltage supply to whatever purpose it may serve.

## 🚧 Project Status & Roadmap

- [x] Discrete 555-based sawtooth generator
- [x] Comparator-based PWM generator (LM393)
- [x] High-side N-MOSFET gate drive stage
- [x] Closed-loop PI feedback control (LM358)
- [ ] Over-Current Protection (OCP) circuit
- [ ] Over-Voltage Protection (OVP) circuit
