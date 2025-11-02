# Combined Schematic – Op-Amp Controlled VCCS

### Objective
Simulate the full Voltage-Controlled Current Source circuit integrating:
1. PWM to DC filter (Butterworth LPF)
2. Op-Amp buffer
3. Op-Amp + NMOS current sink

### Files
| File | Description |
|------|--------------|
| VCCS_Final.asc | LTspice schematic |
| VCCS_Final.net | Netlist for analysis |
| Transient_Output.png | PWM → DC conversion result |
| FFT_Current.png | FFT of I(Rsense) |
| Compliance_Curve.png | Load sweep plot |

### Observations
- Output current: 0–5 mA for 0–5 V input  
- Ripple < 1%  
- Compliance limit ≈ 10 kΩ load  
- FFT confirms DC dominance and harmonic suppression

---

[Back to Main Repo](../README.md)
