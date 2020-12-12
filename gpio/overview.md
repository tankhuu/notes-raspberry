# Pi GPIO

## Wires:

red:positive
black: negative
yellow: ground

## Relay

NO: Normally Open
COM: Common
NC: Normally Close

## Connect Device & Power wire with relay

- Connect 2 Positive wires, 1 to NO and the other to COM terminals
- Connect 2 ground wires of power supply and device together.

- Connect ground wire to ground pin
- Connect 5V to VCC
- Signal wire to IN

> To activate relay: bring the signal pin down to ground. To deactivate relay: we leave it unconnected or 5V

## Connect Raspberry Pi with Relay

JD-VCC : 5V (Pi)
VCC: 3.3V (Pi)
GND: Ground
