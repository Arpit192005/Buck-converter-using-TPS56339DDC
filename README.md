# Buck-converter-using-TPS56339DDC
Purpose: Converts 12 V DC input into a regulated 5 V DC output.
IC: TPS56339DDC, a synchronous buck converter with integrated MOSFETs.
Input connector (J1): Accepts 12 V DC power.
Input capacitors (C1, C2): Reduce input-voltage fluctuations and high-frequency noise.
Inductor (L1 – 5.6 µH): Stores and transfers energy to maintain a stable output.
Output capacitors (C4, C5 – 22 µF each): Reduce output ripple and help maintain voltage stability.
Feedback resistors (R1, R2): Set the output voltage to approximately 5 V.
Bootstrap network (30 Ω resistor and 100 nF capacitor): Supports the high-side MOSFET gate driver.
Output connector (J2): Delivers 5 V at up to 2 A continuous current.
Output power: 5 V × 2 A = 10 W.
Target ripple: ≤200 mV peak-to-peak, subject to simulation and hardware verification.
