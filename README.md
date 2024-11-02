# boostpfc

### Boost Power Factor Correction (Boost PFC)

**Overview**:  
Boost PFC is a commonly used circuit design in AC-DC converters to improve power quality by aligning the input current with the input voltage. It reduces reactive power, minimizes harmonics, and improves efficiency, making it suitable for power supplies, battery chargers, and industrial equipment.

**Operation**:  
1. **AC to DC Conversion**: An AC input is rectified to DC by a full-bridge rectifier, producing a pulsating DC.
2. **Boost Conversion**: A boost converter steps up the DC to a stable output, using an inductor, diode, and switch (typically a MOSFET).
3. **Current Shaping**: The controller adjusts the switch’s duty cycle to shape the input current waveform in sync with the input voltage, achieving a high power factor.

**Benefits**:
- **High Power Factor**: Near-unity power factor through controlled current shaping.
- **Efficient Step-Up**: Boosting allows a higher DC output than the AC peak voltage.
- **Harmonic Reduction**: Lower THD (Total Harmonic Distortion), complying with standards.

**Key Components**:
- **Inductor**: Manages energy storage and smooths current.
- **Switch (MOSFET/IGBT)**: Controls energy flow.
- **Controller**: Maintains high power factor and regulates output voltage.

In summary, Boost PFC is essential in high-efficiency applications where improved power quality and minimal reactive power are required.
