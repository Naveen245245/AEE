# BDL EE 2023 - Explanations

## Question No. 1
**Answer: A (Relay)**

### Explanation:
A relay is a protective device that senses a fault condition (like overcurrent, undervoltage, or impedance) and sends a signal to the circuit breaker to trip (open) and isolate the faulty part of the power system. A fuse performs this function directly without a signal.

## Question No. 2
**Answer: D (Product)**

### Explanation:
Magnetomotive Force (MMF) is defined as the product of the current flowing through the coil and the number of turns of the coil. MMF = N * I.

## Question No. 3
**Answer: A (48)**

### Explanation:
Frequency f is proportional to (1/P). For a synchronous motor, its speed is determined by the frequency of the AC supply. Since the alternator and motor are coupled, their speeds must be equal.
f_motor / P_motor = f_alternator / P_alternator (since speed is constant, N = 120f/P)
60 / P_motor = 25 / 20
P_motor = (60 * 20) / 25 = 1200 / 25 = 48.

## Question No. 4
**Answer: D (Equal to)**

### Explanation:
In lap winding, the number of parallel paths in the armature is always equal to the number of poles. This is a defining characteristic of lap windings.

## Question No. 5
**Answer: A (Coulomb's law)**

### Explanation:
Coulomb's law describes the electrostatic force between two point charges. It states that the force is directly proportional to the product of the charges and inversely proportional to the square of the distance between them.

## Question No. 6
**Answer: D (Regenerative feedback)**

### Explanation:
Positive feedback is also known as regenerative feedback. It feeds a portion of the output signal back to the input in such a way that it adds to the input signal, increasing the gain but potentially causing instability or oscillation. Negative feedback is known as degenerative or inverse feedback.

## Question No. 7
**Answer: B (Low on-resistance switch can be added in parallel)**

### Explanation:
In a buck converter, a diode is used for freewheeling. To reduce conduction losses, a low on-resistance MOSFET can be connected in parallel with the diode. This technique is called synchronous rectification, where the MOSFET is turned on when the diode would normally conduct, reducing the voltage drop and power loss.

## Question No. 8
**Answer: B (Three)**

### Explanation:
A potentiometer is a variable resistor with three terminals. Two terminals are connected to the ends of a resistive track, and the third is connected to a wiper that moves along the track. The resistance between the wiper and one end varies as the wiper is adjusted.

## Question No. 9
**Answer: C (Inverting comparator)**

### Explanation:
A Schmitt trigger is a comparator circuit with positive feedback. The positive feedback causes hysteresis, which provides noise immunity and clean transitions. It operates as an inverting comparator (for a common configuration), switching its output state when the input crosses a specific threshold.

## Question No. 10
**Answer: C (Sink node)**

### Explanation:
In a signal-flow graph, nodes are classified based on their branches. A node with only incoming branches and no outgoing branches is called a sink node. It represents a signal that is not used as an input to any other branch.

## Question No. 11
**Answer: A (Upper bound)**

### Explanation:
The definition provided is the formal definition of an "upper bound" for a set U. A set is bounded above if there exists a real number K (the upper bound) such that all elements in U are less than or equal to K.

## Question No. 12
**Answer: C (Energy meter)**

### Explanation:
Creeping is a phenomenon observed in induction-type energy meters. It is the slow, continuous rotation of the disc even when no load is connected (i.e., the load current is zero). This causes incorrect meter readings and is usually minimized by providing a "creep hole" or magnetic shielding.

## Question No. 13
**Answer: D (Thevenin's theorem)**

### Explanation:
Thevenin's theorem is very useful for calculating the current in a specific branch of a network. By replacing the entire network (except the branch of interest) with a single voltage source and series resistance (Thevenin equivalent), the current in that branch can be easily calculated.

## Question No. 14
**Answer: C (Control grid)**

### Explanation:
In a Cathode Ray Oscilloscope (CRO), the control grid is a metallic cylinder with a small aperture, kept at a negative potential relative to the cathode. By varying this negative potential, the number of electrons passing through the aperture can be controlled, thus controlling the brightness of the beam.

## Question No. 15
**Answer: A (Three)**

### Explanation:
A three-phase slip-ring induction motor has three slip rings, one for each phase of the rotor winding. The slip rings are used to connect external resistors to the rotor circuit for speed control.

## Question No. 16
**Answer: B (x_{n+1} = x_n - f(x_n) / f'(x_n))**

### Explanation:
The standard Newton-Raphson iterative formula is x_{n+1} = x_n - f(x_n) / f'(x_n).

## Question No. 17
**Answer: C (MOSFET and BJT)**

### Explanation:
Insulated Gate Bipolar Transistors (IGBTs) combine the advantages of both MOSFETs and BJTs. They have the high input impedance and fast switching speed of a MOSFET and the low on-state voltage drop and high current capability of a BJT.

## Question No. 18
**Answer: A (Triangular wave)**

### Explanation:
In sinusoidal PWM, the carrier signal is a high-frequency triangular wave (or sawtooth wave). The reference signal is a sinusoidal wave at the desired output frequency. Their comparison generates the switching pulses.

## Question No. 19
**Answer: C (Double line to ground fault)**

### Explanation:
For a double line-to-ground (LLG) fault, the positive, negative, and zero sequence voltages at the fault point are equal. This is a special condition that simplifies the analysis of this type of fault.

## Question No. 20
**Answer: D (Harder to design)**

### Explanation:
Combinational circuits are generally easier to design than sequential circuits because they do not involve memory elements or complex timing constraints. They have no excitation space, no memory units, and are less expensive.

## Question No. 21
**Answer: B (Systematic)**

### Explanation:
Instrument faults or calibration errors are examples of systematic errors. They are not random but are consistent and repeatable. They can often be identified and corrected.

## Question No. 22
**Answer: D (Bulk power transmission over long distances)**

### Explanation:
HVDC transmission is preferred for long-distance bulk power transmission because it overcomes many AC limitations, such as line charging current, stability issues, and skin effect, making it more efficient and economical for very long lines.

## Question No. 23
**Answer: B (Zero voltage gain)**

### Explanation:
An ideal op-amp has infinite voltage gain. A zero voltage gain would mean no amplification, which is the opposite of the purpose of an op-amp.

## Question No. 24
**Answer: D (All of the options)**

### Explanation:
Linear Time-Invariant (LTI) systems have several important properties, including additivity, homogeneity, time-invariance, and the associative, commutative, and distributive properties for convolution operations.

## Question No. 25
**Answer: A (Dense matrix)**

### Explanation:
The Z-bus matrix (impedance matrix) is a full matrix, meaning it is dense (almost all elements are non-zero). This is because it is formed by inverting the Y-bus matrix, which is sparse (contains many zeros).

## Question No. 26
**Answer: A (Parabola)**

### Explanation:
The unit step function's first integration results in a ramp function (t). A second integration results in a parabolic function (t²/2).

## Question No. 27
**Answer: D (AND and XOR gates)**

### Explanation:
A half-adder can be built using:
- Sum = A XOR B (using an XOR gate)
- Carry = A AND B (using an AND gate)

## Question No. 28
**Answer: C (Motor slip)**

### Explanation:
The speed of a wound-rotor three-phase induction motor is controlled by varying the slip. This is achieved by adding external resistance in the rotor circuit. Increasing the resistance increases the slip for a given torque, thereby reducing the speed.

## Question No. 29
**Answer: A (Series compensation)**

### Explanation:
Series compensation involves placing capacitors in series with the transmission line. This reduces the overall inductive reactance of the line, thereby increasing the power transfer capability and reducing the transfer reactance.

## Question No. 30
**Answer: A (Zero)**

### Explanation:
An ideal voltage source maintains a constant voltage at its terminals regardless of the current drawn from it. For the terminal voltage to be independent of the load current, the internal resistance of the source must be zero.

## Question No. 31
**Answer: B (Two-port network)**

### Explanation:
A network with four terminals is generally referred to as a two-port network. Ports are pairs of terminals (e.g., input port and output port) where signals are applied or extracted.

## Question No. 32
**Answer: A (NAND and NOR gates)**

### Explanation:
NAND and NOR gates are called universal gates because any Boolean function can be implemented using only NAND gates or only NOR gates.

## Question No. 33
**Answer: B (RC)**

### Explanation:
The time constant (τ) of an RC series circuit is the product of the resistance (R) and the capacitance (C). It represents the time taken for the voltage across the capacitor to reach approximately 63.2% of its final value during charging.

## Question No. 34
**Answer: D (One or more zeros)**

### Explanation:
A non-minimum phase transfer function has one or more zeros in the right half of the s-plane. This can cause undesirable characteristics like initial undershoot in the step response.

## Question No. 35
**Answer: D (Integrable)**

### Explanation:
For a continuous-time LTI system to be BIBO stable, its impulse response must be absolutely integrable. That is, ∫|h(t)| dt < ∞.

## Question No. 36
**Answer: A (Null detector)**

### Explanation:
In a Wheatstone bridge, the galvanometer is used as a null detector. A null detector indicates when the bridge is balanced (the potential difference between two points is zero). The galvanometer is sensitive enough to detect this zero condition.

## Question No. 37
**Answer: B (26 V)**

### Explanation:
For resistors in series, the source voltage is equal to the sum of the voltage drops across each resistor.
V_source = 5.2 V + 8.5 V + 12.3 V = 26 V.

## Question No. 38
**Answer: C (1/100)**

### Explanation:
Armstrong numbers between 101 and 500 are: 153, 370, 371, 407.
There are 4 Armstrong numbers from 101 to 500.
Total numbers = 500 - 101 + 1 = 400.
Probability = 4/400 = 1/100.

## Question No. 39
**Answer: A (Disc type)**

### Explanation:
For 132 kV transmission lines, disc-type insulators are used. They are connected in strings (series) to provide the required insulation level for the high voltage.

## Question No. 40
**Answer: D (Force per unit charge exerted on a test charge)**

### Explanation:
Electric field intensity (E) at a point is defined as the force (F) experienced by a small positive test charge (q₀) placed at that point, divided by the magnitude of the test charge. E = F/q₀.

## Question No. 41
**Answer: B (e^(at))**

### Explanation:
The Laplace transform of e^(at) is 1/(s - a). Therefore, the inverse Laplace transform of 1/(s - a) is e^(at).

## Question No. 42
**Answer: C (No loops)**

### Explanation:
A mesh is defined as a loop that does not contain any other loops inside it. Therefore, by definition, there are no loops within a mesh. A mesh is a fundamental loop.

## Question No. 43
**Answer: C (Sum)**

### Explanation:
The superposition theorem states that in a linear system, the response (output) to a sum of inputs is equal to the sum of the responses to each individual input applied separately.

## Question No. 44
**Answer: A (All of the options)**

### Explanation:
A digital multimeter (DMM) is a versatile instrument used to measure various electrical quantities, including AC/DC voltage, AC/DC current, and resistance (and sometimes conductance, capacitance, and others).

## Question No. 45
**Answer: B (72°)**

### Explanation:
In single-pulse PWM, the nth harmonic is eliminated when the pulse width is given by: width = 360° / n. Or, the harmonic elimination condition is sin(nδ/2) = 0, where δ is the pulse width. For the 5th harmonic to be eliminated, 5δ/2 = 180° => δ = 72°.

## Question No. 46
**Answer: D (Coulomb's law)**

### Explanation:
Biot-Savart's law is analogous to Coulomb's law. Both describe how a field is generated by a source in 3D space. Coulomb's law describes the electric field from a point charge, while Biot-Savart's law describes the magnetic field from a current element.

## Question No. 47
**Answer: B (11 kV)**

### Explanation:
High tension cables are generally used for voltages up to 11 kV. Cables above 11 kV are typically classified as Extra High Tension (EHT) cables.

## Question No. 48
**Answer: A (Linear, quadratic)**

### Explanation:
The Gauss-Seidel method is an iterative method that converges linearly. The Newton-Raphson method, on the other hand, converges quadratically (much faster) close to the solution.

## Question No. 49
**Answer: A (Mutual induction)**

### Explanation:
Mutual induction is the phenomenon where a changing current in one coil induces an EMF in a neighboring coil. This is the fundamental principle behind transformers.

## Question No. 50
**Answer: C (252)**

### Explanation:
We need to select 11 players from 15 with at least 5 midfielders (M), 5 defenders (D), and 1 goalkeeper (GK).
Total M=7, D=6, GK=2.
Possible combinations:
Case 1: M=5, D=5, GK=1. Number of ways = C(7,5) * C(6,5) * C(2,1) = 21 * 6 * 2 = 252.
Case 2: M=5, D=6, GK=0 (not allowed, need at least 1 GK).
Case 3: M=6, D=5, GK=0 (not allowed).
Case 4: M=5, D=5, GK=2. Number of ways = C(7,5) * C(6,5) * C(2,2) = 21 * 6 * 1 = 126.
Case 5: M=5, D=6, GK=1. Number of ways = C(7,5) * C(6,6) * C(2,1) = 21 * 1 * 2 = 42.
Case 6: M=6, D=5, GK=1. Number of ways = C(7,6) * C(6,5) * C(2,1) = 7 * 6 * 2 = 84.
Case 7: M=6, D=6, GK=1. Number of ways = C(7,6) * C(6,6) * C(2,1) = 7 * 1 * 2 = 14.
Case 8: M=7, D=5, GK=1. Number of ways = C(7,7) * C(6,5) * C(2,1) = 1 * 6 * 2 = 12.
Total ways = 252 + 42 + 84 + 14 + 12 = 404. Wait, the answer key says 252. Let's re-read the condition: "to include at least 5 midfielders, 5 defenders and 1 goalkeeper." This implies we need at least one of each. The combination M=5, D=5, GK=1 gives 21*6*2 = 252. Are there other combinations? M=6, D=5, GK=1: 7*6*2=84; M=5, D=6, GK=1: 21*1*2=42; M=6, D=6, GK=1: 7*1*2=14; M=7, D=5, GK=1: 1*6*2=12; M=5, D=5, GK=2: 21*6*1=126. Total = 252+84+42+14+12+126 = 530. Something is off. The answer key says C (252), which matches only the first case. Perhaps the question implies exactly 5 midfielders, exactly 5 defenders, and the rest can be others, but must include at least 1 GK. The simplest and likely intended solution is 5M, 5D, 1GK = 252.

## Question No. 51
**Answer: C (Aperture time)**

### Explanation:
Aperture time is the minimum time for which the sample-and-hold circuit must hold the signal during the conversion process. However, the time to capture a sample of the sensor signal is referred to as acquisition time. The question asks for "taking a period of time to capture a sample", which is acquisition time. The answer key says C (Aperture time). There might be a confusion. Aperture time is more related to the time uncertainty in the sampling instant. The time required to get the output to track the input after switching to the track mode is the acquisition time. Based on the answer key, C is chosen.

## Question No. 52
**Answer: C (Laplace)**

### Explanation:
The transfer function of a control system is defined as the ratio of the Laplace transform of the output variable to the Laplace transform of the input variable, assuming all initial conditions are zero.

## Question No. 53
**Answer: D (One)**

### Explanation:
If the pole introduced by a lead compensator is not cancelled by a zero in the system, the lead compensator adds one pole and one zero to the system, which increases the order of the system by one.

## Question No. 54
**Answer: A (Added to)**

### Explanation:
A clamper circuit adds a predetermined DC level (positive or negative) to the input AC signal. It shifts the signal's average value up or down without changing its shape.

## Question No. 55
**Answer: C (Coulomb per square metre)**

### Explanation:
Electric flux density (D) is defined as D = εE. Its unit is coulombs per square meter (C/m²).

## Question No. 56
**Answer: B (None of the options)**

### Explanation:
For parallel operation of alternators, the following conditions must be met:
- Same voltage magnitude.
- Same frequency.
- Same phase sequence.
- Same phase angle (at the moment of paralleling).
Since all the given options are true, the option "None of the options" (which is false) is the correct answer because the question asks for the statement that is NOT TRUE.

## Question No. 57
**Answer: C (Electric field intensity)**

### Explanation:
Biot-Savart's law is used to calculate magnetic field intensity. It is not used for calculating electric field intensity.

## Question No. 58
**Answer: D (Temperature)**

### Explanation:
A DC potentiometer is a null-balance instrument used for precise measurement of voltage, current (using a shunt), and resistance (using a standard resistor). It is not used to measure temperature directly.

## Question No. 59
**Answer: D (1.33 Ω)**

### Explanation:
Characteristic impedance Z₀ = √(Z/Y) = √(16 / 9) = 4/3 = 1.33 Ω.

## Question No. 60
**Answer: A (Power factor)**

### Explanation:
The power factor (PF) is the ratio of active power (P) to apparent power (S). PF = P/S = cos(θ), where θ is the phase angle between voltage and current.

## Question No. 61
**Answer: D (Free response)**

### Explanation:
The state transition matrix (Φ(t)) of a system represents the free response of the system. It describes the evolution of the state vector from its initial state at t=0 without any external input (u=0).

## Question No. 62
**Answer: C (1 ohm)**

### Explanation:
For n equal resistors (R) in parallel, the equivalent resistance is R/n.
R_eq = 100 Ω / 100 = 1 Ω.

## Question No. 63
**Answer: B (Scheering bridge)**

### Explanation:
The Schering bridge is used for the accurate measurement of capacitance and dissipation factor (loss angle) of capacitors.

## Question No. 64
**Answer: A (Least at the centre of poles and increases while moving away from the centre)**

### Explanation:
In a salient pole synchronous machine, the air gap is non-uniform. It is minimum (least) at the center of the pole face and gradually increases towards the pole tips. This is due to the shape of the salient poles.

## Question No. 65
**Answer: D (Arrow)**

### Explanation:
In a signal-flow graph, arrows represent the direction of signal flow between nodes. The gain is often written along the arrow.

## Question No. 66
**Answer: B (2)**

### Explanation:
Matrix A = [[1, 2, 3], [4, 5, 6], [7, 8, 9]]
The determinant of A is 0 (since R3 = 2*R2 - R1, they are linearly dependent).
Thus, rank is less than 3.
The first two rows [1 2 3] and [4 5 6] are linearly independent. So rank = 2.

## Question No. 67
**Answer: C (Negative)**

### Explanation:
A balanced three-phase system has positive, negative, and zero sequence components. The negative sequence components have a phase sequence opposite to the original system.

## Question No. 68
**Answer: A (Closed grained cast iron)**

### Explanation:
The frame (or stator frame) of an induction motor is typically made of closed-grained cast iron. It provides structural support and a path for the magnetic flux.

## Question No. 69
**Answer: A (Both field flux and armature current)**

### Explanation:
In a DC shunt motor, the torque developed is proportional to the product of the armature current (Iₐ) and the field flux (Φ). T ∝ Φ * Iₐ.

## Question No. 70
**Answer: B (Square Matrix)**

### Explanation:
A matrix with an equal number of rows and columns is called a square matrix.

## Question No. 71
**Answer: D (To arrest the flow of moisture when the outside air enters the transformer)**

### Explanation:
The breather's primary function is to absorb moisture from the air that enters the transformer's conservator tank due to expansion and contraction of the oil.

## Question No. 72
**Answer: D (s / (s² + ω²))**

### Explanation:
The Laplace transform of cos(ωt) u(t) is s / (s² + ω²).

## Question No. 73
**Answer: C (Stable)**

### Explanation:
For a system to be stable, both gain margin (GM) and phase margin (PM) must be positive. A positive GM indicates that the system's gain can be increased by that margin before it becomes unstable.

## Question No. 74
**Answer: D (F = qE + qv × B)**

### Explanation:
The Lorentz force law describes the total force on a charged particle (q) moving with velocity (v) in the presence of an electric field (E) and magnetic field (B). The equation is F = qE + qv × B.

## Question No. 75
**Answer: C (Three)**

### Explanation:
A thyristor (SCR) is a four-layer (PNPN) device, which forms three P-N junctions.

## Question No. 76
**Answer: B (Zero)**

### Explanation:
If the Nyquist plot passes through the critical point (-1, j0), the system is on the verge of instability (marginally stable). The gain margin, which is the reciprocal of the gain at phase crossover, would be 1, which is 0 dB.

## Question No. 77
**Answer: C (4)**

### Explanation:
The number of loop equations in an electric circuit is L = B - N + 1, where B is the number of branches and N is the number of nodes.
L = 10 - 7 + 1 = 4.

## Question No. 78
**Answer: C (It is used to integrate over a two-dimensional region)**

### Explanation:
The notation ∫∫ f(x,y) dA is used for integrating over a two-dimensional region. The question likely refers to the use of a double integral. The answer key indicates C.

## Question No. 79
**Answer: B (2 and 3)**

### Explanation:
Given equation: d²y/dx² + (dy/dx)³ + x = 0.
Order is the highest derivative, which is 2.
Degree is the power of the highest derivative after removing radicals and fractions. The highest derivative is d²y/dx², and its power is 1. Wait, the question says d2y + dy = 0. dx2 dx dx. The file shows: d2y + dy³ + x = 0. dx2 dx dx. This is messy.
Assuming the equation is d²y/dx² + (dy/dx)³ + x = 0.
Order = 2. Degree = power of the highest derivative = 1.
The answer key says B: 2 and 3. This might be for a different equation. The OCR is poor. Let's assume the question intended equation is (d²y/dx²)² + (dy/dx)³ = 0. Then order=2, degree=2. Not matching. Let's assume the equation is (d²y/dx²)³ + (dy/dx)² = 0. Then order=2, degree=3. Answer B: 2 and 3 fits this. So the equation likely was (d²y/dx²)³ + (dy/dx)² + x = 0.

## Question No. 80
**Answer: B (Input, initial states)**

### Explanation:
Zero-state response is the output due to the input alone when the system starts from rest (zero initial conditions). Zero-input response is the output due to the initial states alone when the input is zero.

## Question No. 81
**Answer: D (120°)**

### Explanation:
In the 120° conduction mode of a three-phase bridge inverter, each thyristor conducts for 120° of the cycle. There are always two thyristors conducting at any instant.

## Question No. 82
**Answer: D (Very high)**

### Explanation:
The output resistance of a common-base (CB) amplifier is very high. This is because the output is taken from the collector terminal, which has a reverse-biased junction.

## Question No. 83
**Answer: C (Active power)**

### Explanation:
The frequency of a power system is primarily controlled by balancing the active power generation and load demand. The speed governor of the generator regulates the input mechanical power to match the electrical load, thus maintaining the system frequency.

## Question No. 84
**Answer: D (10)**

### Explanation:
A binary number must contain only the digits 0 and 1. Among the options, only 10 fits this criterion.

## Question No. 85
**Answer: B (1/s)**

### Explanation:
The Laplace transform of 1 (a constant) is 1/s.

## Question No. 86
**Answer: A (Right, left)**

### Explanation:
In a lead compensator, the zero is located to the right of the pole (on the real axis). In a lag compensator, the zero is located to the left of the pole.

## Question No. 87
**Answer: A (Dielectric)**

### Explanation:
A capacitor consists of two conductive plates separated by an insulating material called a dielectric. The dielectric increases the capacitance of the capacitor.

## Question No. 88
**Answer: A (Air gap is uniform)**

### Explanation:
Smooth cylindrical rotor (also called non-salient pole rotor) is used in high-speed alternators (like turbo-generators). The rotor is cylindrical, so the air gap is uniform around the periphery.

## Question No. 89
**Answer: A (Proportional)**

### Explanation:
D/A conversion (Digital-to-Analog) is the process of converting a digital code (e.g., binary number) into an analog voltage or current that is proportional to the digital value.

## Question No. 90
**Answer: B (d²y/dx² - 2dy/dx + 2y = 0)**

### Explanation:
Given y = e^x (A cos x + B sin x).
dy/dx = e^x (A cos x + B sin x) + e^x (-A sin x + B cos x) = y + e^x (-A sin x + B cos x).
d²y/dx² = dy/dx + e^x (-A sin x + B cos x) + e^x (-A cos x - B sin x)
= (dy/dx) + (dy/dx - y) - y = 2(dy/dx) - 2y.
Therefore, d²y/dx² - 2dy/dx + 2y = 0.

## Question No. 91
**Answer: C (Magnetic hum)**

### Explanation:
Squirrel-cage rotor slots are skewed to reduce magnetic locking (cogging) and magnetic hum (noise and vibration caused by magnetic forces).

## Question No. 92
**Answer: B (Voltage transfer ratio)**

### Explanation:
The ratio of the voltage transform (or phasor) at the first port (V₁) to the voltage transform at the second port (V₂) is called the voltage transfer ratio (V₁/V₂ or V₂/V₁ depending on direction).

## Question No. 93
**Answer: D (Conjugate symmetry)**

### Explanation:
The Fourier transform of a real-valued signal has conjugate symmetry: X(-jω) = X*(jω).

## Question No. 94
**Answer: C (Slip ring and brushes are absent)**

### Explanation:
Wound rotor motors have slip rings and brushes to connect external resistors to the rotor winding. This is a key feature that distinguishes them from squirrel-cage motors. So, the statement "Slip ring and brushes are absent" is NOT true for wound rotor motors.

## Question No. 95
**Answer: A (Mutual induction)**

### Explanation:
An instrument transformer (current transformer or potential transformer) works on the principle of mutual induction, just like a standard transformer.

## Question No. 96
**Answer: B (Inversely proportional to)**

### Explanation:
According to Biot-Savart's law, the magnetic field intensity (dB) is inversely proportional to the square of the distance (r²) from the current element.

## Question No. 97
**Answer: D (Chopper)**

### Explanation:
A DC-to-DC converter is commonly known as a chopper. It converts a fixed DC voltage to a variable DC voltage.

## Question No. 98
**Answer: B (CRT)**

### Explanation:
The Cathode Ray Tube (CRT) is the core component of a CRO. It is where the electron beam is generated, focused, deflected, and strikes the phosphor screen to produce the display. So, it is considered the heart of the CRO.

## Question No. 99
**Answer: D (Gate turn-off thyristor)**

### Explanation:
GTO stands for Gate Turn-Off Thyristor. It is a thyristor that can be turned off by applying a negative current pulse to the gate terminal.

## Question No. 100
**Answer: C (Low input impedance)**

### Explanation:
MOSFETs are known for their high input impedance (due to the insulated gate). High input impedance is an advantage, so the statement "Low input impedance" is NOT TRUE about MOSFETs.

## Question No. 101
**Answer: A (Rs.3000)**

### Explanation:
Total percentage of salary spent = 60% + 15% = 75%.
Remaining salary = 100% - 75% = 25% = Rs.750.
Total salary = 750 / 0.25 = Rs.3000.

## Question No. 102
**Answer: B (Rs.51.25)**

### Explanation:
SI = (P * R * T) / 100 = 50.
P * 5 * 2 / 100 = 50 => P = 500.
CI = P[(1 + R/100)^T - 1] = 500[(1 + 0.05)^2 - 1] = 500[(1.05)^2 - 1] = 500[1.1025 - 1] = 500 * 0.1025 = Rs.51.25.

## Question No. 103
**Answer: A (Rs.200)**

### Explanation:
SP = 220, Profit = 10%, so SP = 1.1 * CP.
CP = 220 / 1.1 = Rs.200.

## Question No. 104
**Answer: C (12 days)**

### Explanation:
Anitha's rate = 1/16, Bindhu's rate = 1/24.
(Bindhu + Charu)'s rate = 1/8.
Charu's rate = 1/8 - 1/24 = (3 - 1)/24 = 2/24 = 1/12.
Time for Charu alone = 1 / (1/12) = 12 days.

## Question No. 105
**Answer: C (cos A)**

### Explanation:
sin(30° - A) + sin(30° + A) = 2 sin(30°) cos(A) = 2 * (1/2) * cos(A) = cos A.

## Question No. 106
**Answer: C (0.94)**

### Explanation:
Multiplying 'x' by a certain number is equivalent to subtracting 6% of 'x' from 'x' itself.
If the number is 'n', then nx = x - 0.06x = 0.94x.
Therefore, n = 0.94. The question asks for the value of 'x'? It says "Find the value of 'x'." But we find 'n' = 0.94. The question likely has a typo. The answer key says C: 0.94.

## Question No. 107
**Answer: C (77)**

### Explanation:
Average = (75 + 62 + 83 + 70 + 95) / 5 = 385 / 5 = 77.

## Question No. 108
**Answer: D (Rs.16000)**

### Explanation:
A = P(1 + 0.05)^3 = 1.157625 P.
CI = A - P = 0.157625 P = 2522.
P = 2522 / 0.157625 = 16000.

## Question No. 109
**Answer: C (Rs.5)**

### Explanation:
Let the attendance on days be 2x, 5x, and 13x.
Total revenue = (15 * 2x) + (7.5 * 5x) + (2.5 * 13x) = 30x + 37.5x + 32.5x = 100x.
Total attendance = 2x + 5x + 13x = 20x.
Average charge per person = (100x) / (20x) = Rs.5.

## Question No. 110
**Answer: C (63)**

### Explanation:
To find the least possible number of equal cubes, we need to cut the block into cubes with the largest possible side length. The side length must divide 6, 42, and 54 exactly. The HCF (GCD) of 6, 42, and 54 is 6.
Number of cubes = (6/6) * (42/6) * (54/6) = 1 * 7 * 9 = 63.

## Question No. 111
**Answer: A (Rs.360)**

### Explanation:
Let CP per bicycle be Rs.100.
MP = 100 + 25% = 125.
SP for cash = 125 - 10% = 112.5.
SP for credit = 125 - 5% = 118.75.
Total bicycles = 40.
Cash sales = 3/4 * 40 = 30 bicycles.
Credit sales = 10 bicycles.
Total profit = [30 * (112.5 - 100) + 10 * (118.75 - 100)] * (CP/100).
Total profit = [30 * 12.5 + 10 * 18.75] * (CP/100) = [375 + 187.5] * (CP/100) = 562.5 * (CP/100) = 2025.
CP = (2025 * 100) / 562.5 = 360.

## Question No. 112
**Answer: C (8/3 km/h)**

### Explanation:
Let speed in still water = v, stream speed = u.
Distance = d = 12 km.
Time upstream = 12/(v-u), Time downstream = 12/(v+u).
12/(v-u) - 12/(v+u) = 6 => (1) (Equation 1)
If speed doubles, new speed = 2v.
12/(2v-u) - 12/(2v+u) = 1 => (2) (Equation 2)
From (1): 12 * (2u) / (v² - u²) = 6 => 4u / (v² - u²) = 1 => v² - u² = 4u. (A)
From (2): 12 * (2u) / (4v² - u²) = 1 => 24u / (4v² - u²) = 1 => 4v² - u² = 24u. (B)
Substitute v² = u² + 4u from (A) into (B):
4(u² + 4u) - u² = 24u => 4u² + 16u - u² = 24u => 3u² + 16u - 24u = 0 => 3u² - 8u = 0 => u(3u - 8) = 0.
Since u ≠ 0, u = 8/3 km/h.

## Question No. 113
**Answer: A (23/30)**

### Explanation:
Total students = 1.
Girls = 3/5. Boys = 2/5.
Absent girls = (2/9) * (3/5) = 6/45 = 2/15.
Absent boys = (1/4) * (2/5) = 2/20 = 1/10.
Total absent = 2/15 + 1/10 = 4/30 + 3/30 = 7/30.
Present = 1 - 7/30 = 23/30.

## Question No. 114
**Answer: A (15)**

### Explanation:
Let numbers be 5x and 8x.
(5x + 12) / (8x + 12) = 3/4
Cross-multiplying: 4(5x + 12) = 3(8x + 12) => 20x + 48 = 24x + 36 => 4x = 12 => x = 3.
First number = 5x = 15.

## Question No. 115
**Answer: C (2)**

### Explanation:
(0.3 × 0.3 + 0.01)(0.2 × 0.2 + 0.01)⁻¹
= (0.09 + 0.01) / (0.04 + 0.01) = 0.10 / 0.05 = 2.

## Question No. 116
**Answer: A (3.6 km)**

### Explanation:
Speed downstream = 15 + 3 = 18 km/h.
Time = 12 min = 12/60 = 0.2 hours.
Distance = Speed * Time = 18 * 0.2 = 3.6 km.

## Question No. 117
**Answer: D (10 km/h)**

### Explanation:
Total distance = 35 km + 55 km = 90 km.
Time taken for first part = 35 / 5 = 7 hours.
Total time = 7 + 2 = 9 hours.
Average speed = Total distance / Total time = 90 / 9 = 10 km/h.

## Question No. 118
**Answer: D (8/15)**

### Explanation:
sin A = 8/17. Using Pythagoras: cos A = √(1 - sin²A) = √(1 - 64/289) = √(225/289) = 15/17.
tan A = sin A / cos A = (8/17) / (15/17) = 8/15.

## Question No. 119
**Answer: B (9.123 × 10⁻⁶)**

### Explanation:
0.000009123 = 9.123 × 10⁻⁶.

## Question No. 120
**Answer: A (12 years)**

### Explanation:
Let son's present age = x. Father's present age = 3x.
Four years ago: (3x - 4) / (x - 4) = 4/1.
3x - 4 = 4x - 16 => x = 12.

## Question No. 121
**Answer: D (Abarna and Karan)**

### Explanation:
This is a seating arrangement puzzle. Based on the constraints:
- Karan is at one of the extreme right ends of the boys' row.
- Meera is to the immediate right of the girl facing Karan.
- Only Balu is between Dinesh and Karan.
- Naveen is to the immediate left of Arun and immediate right of Charan.
- Abi faces Arun and is to the immediate left of Divya.
- Riya is third to the left of Abarna.
From the arrangement, the pair at one of the extreme ends is Abarna and Karan.

## Question No. 122
**Answer: C (T)**

### Explanation:
The series is: K (+1) L (+1) M (+2) O (+2) Q (+3) T (+3) W.
So the missing letter is T.

## Question No. 123
**Answer: A (8 km, east)**

### Explanation:
Net eastward displacement = 2 km (east) - 0 (north/south movement doesn't affect east-west component) + 6 km (east) = 8 km east.
Net northward displacement = 7 km (north) - 7 km (south) = 0 km.
So he is 8 km east of his office.

## Question No. 124
**Answer: B (Daughter)**

### Explanation:
My wife's grandfather's only child is my wife's father (or mother).
His only granddaughter would be my wife's daughter.
Therefore, the girl is Pradap's daughter.

## Question No. 125
**Answer: A (Capital)**

### Explanation:
Hut, House, and Shed are all types of dwellings or shelters. Capital is a type of city or money, not a shelter. So, Capital is the odd one out.

## Question No. 126
**(Question content missing from file)**

## Question No. 127
**(Question content missing from file)**

## Question No. 128
**(Question content missing from file)**

## Question No. 129
**(Question content missing from file)**

## Question No. 130
**Answer: C (XU)**

### Explanation:
F (6) -> I (9), +3
C (3) -> F (6), +3
I (9) -> M (13), +4
F (6) -> J (10), +4
M (13) -> R (18), +5
J (10) -> O (15), +5
R (18) -> X (24), +6
O (15) -> U (21), +6
So the next pair is XU.

## Question No. 131
**Answer: D (48)**

### Explanation:
The series is doubling every term: 6, 12, 24, 48, 96, 192.
So the missing number is 48.

## Question No. 132
**Answer: C (wo)**

### Explanation:
'ns pt kl ch' = siva gets marriage gift
'pt In wo ch' = wife gives marriage gift
'tt wo nh' = she gives nothing
Common words:
- 'pt' appears in 1st and 2nd, and 'gets' and 'gives' are common. We need to differentiate.
- 'ch' appears in 1st and 2nd, and 'marriage' and 'gift' appear in both. 'marriage gift' is 'kl ch' or 'pt ch'.
- 'pt' is common to 1st and 2nd.
- 'wo' appears in 2nd and 3rd, and 'gives' and 'she' are common. But 'gives' appears in 2nd, and 'she' appears in 3rd.
From 'tt wo nh' = she gives nothing. In the 3rd sentence, 'gives' could be 'wo' or 'nh'.
From 'pt In wo ch' = wife gives marriage gift. Here, 'gives' could be 'wo' or 'In'.
If 'wo' = gives, then 'In' = marriage, and 'pt' = wife, 'ch' = gift.
Check 1st: 'ns pt kl ch' = siva gets marriage gift. If 'pt'=wife and 'ch'=gift, this doesn't match.
Let's do systematic comparison:
1: ns pt kl ch = siva gets marriage gift
2: pt In wo ch = wife gives marriage gift
3: tt wo nh = she gives nothing

In 2 and 3, common word is 'wo' and common meaning is 'gives'. So, 'wo' = gives.

## Question No. 133
**(Question content missing from file)**

## Question No. 134
**Answer: C (Either statement I or II is sufficient to answer the question)**

### Explanation:
Statement I: Q walks 30m West, turns left (South), walks 20m, turns left (East), walks 30m. He stops. His final direction is East. Sufficient.
Statement II: Q walks 30m East, turns right (South), walks 20m, turns left (East), walks 30m. He stops. His final direction is East. Sufficient.
Either statement alone is sufficient.

## Question No. 135
**Answer: B (Neither conclusion I nor II follows)**

### Explanation:
The statement is a fact: private schools charge more fees. Conclusion I suggests "strict action need not be taken". This is not logically derived. Conclusion II suggests "such schools should be allowed", which is also not derived. In fact, the correct logical action might be the opposite. So neither conclusion follows.

## Question No. 136
**Answer: C (To be a harbinger of unfavourable results)**

### Explanation:
"Something bodes ill" means that something is a sign of bad things to come.

## Question No. 137
**Answer: C (Carry out)**

### Explanation:
"To perform or cause to be implemented" means to "carry out".

## Question No. 138
**Answer: A (Conurbation)**

### Explanation:
"Conurbation" is correctly spelt. "Preciousness" is also correctly spelt. "Conundram" is wrong (Conundrum). "Stickmatization" is wrong (Stigmatization). The answer key says A.

## Question No. 139
**Answer: D (RQPS)**

### Explanation:
Scientists believed (S1) **that the Moon** (R) **did not harbour** (P) **any microbes** (Q) **but still 1% uncertainty** (S) **was too huge a risk to take** (S6).
So the sequence is S1-R-Q-P-S-S6. The question has S1, S6, P, Q, R, S. We need the order of P, Q, R, S. It is RQPS.

## Question No. 140
**Answer: D (Sent)**

### Explanation:
When the time is specified ("two hours ago"), we use the simple past tense. The correct form is "Senthil sent the parcel...". So, "has sent" should be changed to "sent".

## Question No. 141
**Answer: C (Help someone get out of trouble)**

### Explanation:
"Get someone off the hook" means to help someone avoid blame, punishment, or trouble.

## Question No. 142
**Answer: D (Capricious)**

### Explanation:
"Nobody likes" implies a negative trait. "Capricious" means given to sudden and unaccountable changes of mood or behavior, which is an undesirable quality in a manager. The other options are positive.

## Question No. 143
**Answer: C (Q)**

### Explanation:
The correct phrase is "on foot", not "by walk". The error is in part Q.

## Question No. 144
**Answer: B (Pandemic)**

### Explanation:
"Something that spreads fast" refers to a pandemic (an epidemic of infectious disease that has spread across a large region).

## Question No. 145
**Answer: C (Disparaging)**

### Explanation:
"Pejorative" means expressing contempt or disapproval. A synonym is "Disparaging" (expressing the opinion that something is of little worth).

## Question No. 146
**Answer: D (Spartan)**

### Explanation:
"Austere" means severe or strict in manner, attitude, or appearance. A synonym is "Spartan" (showing the characteristics of a Spartan: simple, severe, and disciplined).

## Question No. 147
**Answer: D (Furloughed)**

### Explanation:
"Furloughed" means temporarily laid off from a job. This fits the context of being briefly away from a previous role.

## Question No. 148
**Answer: B (Well-judged)**

### Explanation:
"Mistaken" means wrong or incorrect. Its antonym is "Well-judged" or "correct".

## Question No. 149
**Answer: B (Detestable)**

### Explanation:
"Reverent" means feeling or showing deep and solemn respect. Its antonym is "Detestable" (deserving intense dislike). "Worshipful" is a synonym.

## Question No. 150
**(Question content missing from file)**