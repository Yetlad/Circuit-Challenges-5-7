
Circuit Report: Ping Pong Flashers (Astable Multivibrator)

The final project moves from manual and sensor-based switching to automated oscillation. The "Ping Pong Flasher" is an astable multivibrator circuit designed to alternate power between two LEDs (Red and Green) automatically, creating a rhythmic flashing effect.

How the "Ping Pong" Effect Works
This circuit relies on the interaction between capacitors, resistors, and transistors to create a feedback loop that never settles into a steady state.

The Capacitors (100μF): These act as temporary energy reservoirs. They charge up through the resistors and then discharge into the base of the opposite transistor.

The Cross-Coupled Design: * The cathode (short leg) of the first capacitor is connected to the base of the second transistor.

The cathode of the second capacitor is connected to the base of the first transistor.

The Alternating Switch: When one capacitor discharges, it "turns on" the opposite transistor, which illuminates its LED and simultaneously begins charging the next capacitor. This "handoff" continues indefinitely as long as power is supplied.

Technical Observations
Timing Control (RC Time Constant): The speed of the "ping pong" flash is determined by the RC circuit (the 10kΩ resistors and the 100μF capacitors).

Higher resistance/capacitance = Slower flashes.

Lower resistance/capacitance = Faster flashes.

Component Safety: Each LED remains protected by a 200 Ω resistor connected to the collector of its respective NPN transistor, maintaining the high-brightness standard established in Challenge 1.
