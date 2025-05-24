

### 1. Attenuation (Signal Loss)
Reduction in signal strength as it travels through a medium.  
Cause: Resistance of wire, Long distances  
Solution:Use amplifiers (analog signal) or repeaters (digital signal)  
Use optical fibers for long-distance, low-loss transmission

Attenuation is measured in decibels (dB) using:
```math
\text{Attenuation (dB)} = 10 \log_{10} \left(\frac{P_{in}}{P_{out}}\right)
]
```

---
### 2. Distortion (Signal Shape Changes)
Change in signal form or shape as it travels.  
Cause: Different components of the signal (frequencies) travel at different speeds  
Common in composite signals (which include multiple frequencies)  
Solution: Equalization, Use of modulation and filtering techniques

Affects composite signals more than pure sine waves.

---
### 3. Noise (Unwanted Signals)
📌 Definition:
Random electrical signals that interfere with the transmitted signal.

| Type of Noise       | Description                                  |
| ------------------- | -------------------------------------------- |
| **Thermal Noise**   | Random electron motion due to heat           |
| **Intermodulation** | Mixing of different signal frequencies       |
| **Crosstalk**       | Signal leakage from one wire to another      |
| **Impulse Noise**   | Sudden spikes (e.g., lightning, power surge) |

Solution: Shielded cables, Proper grounding, Error detection and correction codes  
Thermal noise is also called white noise and is present in all devices.