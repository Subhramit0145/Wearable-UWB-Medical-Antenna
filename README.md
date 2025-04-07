
# Compact Wearable Antenna with Band-Notch Features for Medical Applications

A compact ultra-wideband (UWB) wearable antenna designed for integration into a physician's chest badge. This antenna features **five selective notch bands** to mitigate interference from 4G, 5G, WLAN, and satellite communications while maintaining flexibility and safety for medical applications.

---

## Key Features
- **Five Notch Bands**: Filters interference at 2.58–3.21 GHz, 4.05–4.29 GHz, 5.00–5.64 GHz, 8.60–9.05 GHz, and 9.20–10.32 GHz.
- **Compact Design**: Dimensions of **30 × 25 × 0.508 mm³** using Rogers 5880 substrate.
- **Flexible & Wearable**: Slim profile (0.508 mm thickness) enables bending for integration into badges or clothing.
- **Hygienic Medical Application**: Reduces manual card swiping in hospitals, lowering bacterial contamination risks.
- **SAR-Compliant**: Meets safety standards (SAR < 1.6 W/kg per 1 g of tissue).

---

## Specifications
| Parameter               | Details                                                                 |
|-------------------------|-------------------------------------------------------------------------|
| Substrate               | Rogers 5880 (ε<sub>r</sub> = 2.2, tanδ = 0.0009)                       |
| Frequency Range         | 2.56–12.7 GHz (UWB) excluding notch bands                              |
| Notch Bands             | 2.58–3.21 GHz, 4.05–4.29 GHz, 5.00–5.64 GHz, 8.60–9.05 GHz, 9.20–10.32 GHz |
| Feed Type               | 50 Ω microstrip line                                                   |
| Peak Gain               | 4.76 dBi                                                               |
| Flexibility Tested      | Bending radii: 20 mm, 40 mm, 60 mm, 80 mm                              |

---

## Design Overview
### Structure
- **Top Layer**: Rectangular radiating patch with an S-shaped strip and circular rings for the first notch band.
- **Feed Line**: Symmetrical spiral strips for two additional notch bands.
- **Bottom Layer**: Ground plane with rectangular and sector-shaped slots for impedance matching. Spiral strips generate remaining notch bands.
- **Side-Mounted Strips**: Connect radiating patch to bottom layer, enabling efficient current flow and isolation between notch structures.

### Notch Band Implementation
- **Dual Notch from Single Structure**: Enhanced spiral strips and side-mounted metal strips optimize space.
- **Current Distribution**: Targeted current concentration at specific frequencies (e.g., 2.67 GHz, 4.13 GHz) suppresses interference.

### Flexibility
- Tested under bending conditions (radii 20–80 mm) to simulate real-world wearable use.

---

## Simulation and Results
- **Software**: CST Studio Suite 2020.
- **Reflection Coefficient (S<sub>11</sub>)**: Achieved <-10 dB across UWB range (2.56–12.7 GHz) with five notch bands (Fig. 4, 5).
- **Radiation Pattern**: Omnidirectional with stable gain.
- **SAR Compliance**: Simulated SAR values at 6 GHz, 8 GHz, and 11 GHz meet U.S. and European safety standards.

---

## Application in Medical Settings
- Integrated into a **doctor's chest badge** (Fig. 6) for hands-free access control.
- Positioned on the badge's internal backside to protect against friction and maintain aesthetics.
- Reduces contact with contaminated surfaces, enhancing hospital hygiene.

---

## Comparison with Existing Work
- **More Notch Bands**: Five notches vs. 1–3 in prior designs.
- **Space Efficiency**: Dual-notch structures minimize interference in compact layouts.
- **Medical Focus**: Tailored for wearable WBAN applications with SAR compliance.

---

## References
1. Kumar et al., "Ultrawideband (UWB) planar antenna..." *IEEE Antennas Wireless Propag. Lett.*, 2017.  
2. Awan et al., "Stub loaded, low profile UWB antenna..." *Microw. Opt. Technol. Lett.*, 2019.  
3. Arif et al., "A compact, low-profile fractal antenna..." *IEEE Antennas Wireless Propag. Lett.*, 2019.  

*Full references available in the [paper](Subhramit_Paper.pdf).*

---

## Citation
```bibtex
@article{kumar2023compact,
  title={Compact Wearable Antenna with Band-Notch Features for Medical Applications},
  author={Kumar, Somesh and Dwivedi, Yadvendra Prasad and Bera, Subhramit},
  journal={ABV-IIITM, Gwalior},
  year={2023}
}
