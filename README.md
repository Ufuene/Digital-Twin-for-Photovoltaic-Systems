# Digital-Twin-for-Photovoltaic-Systems


# Digital Twin for Photovoltaic Systems

This repository provides an **experimental dataset** obtained from the characterization of a **60W monocrystalline PV panel**.  
The dataset can be used for **parameter extraction** of PV models (such as the single-diode model, SDM) and for validation of modeling methods against real experimental data.

---

## PV Panel Specifications

- **Nominal power (Pmax):** 60 W  
- **Voltage at maximum power point (Vmp):** 18.62 V  
- **Current at maximum power point (Imp):** 3.20 A  
- **Open-circuit voltage (Voc):** 21.7 V  
- **Short-circuit current (Isc):** 3.56 A  
- **Efficiency:** 17.89%  
- **Maximum system voltage:** 600 V  
- **Maximum fuse current:** 5 A  
- **Power temperature coefficient:** -0.51 %/K  
- **Voltage temperature coefficient:** -0.39 %/K  
- **Current temperature coefficient:** +0.08 %/K  
- **Number of cells:** 32 (monocrystalline silicon, PERC technology)  
- **Dimensions (L × W × H):** 742 × 452 × 25 mm  
- **Total module area:** 0.335 m²  
- **Weight:** 2.4 kg  
- **Protective enclosure IP code:** IP65  

---

## Dataset Description

- **Format:** CSV (comma-separated values)

### Columns
- **Time (s)** → Timestamp of measurement  
- **G (W/m²)** → Irradiance  
- **V (V)** → Voltage  
- **I (A)** → Current  
- **P (W)** → Power  

These measurements represent the **I–V** and **P–V** characteristics of the PV panel under experimental conditions.

---

## Usage and Research Context

Researchers interested in PV modeling (e.g., **single-diode model parameter extraction**) can use this dataset instead of relying solely on manufacturer datasheets, which often present deviations compared to measured data.  

By plotting the I–V or P–V curves from this dataset, researchers can validate their estimation methods and compare model-based curves against experimental data.

This is particularly valuable because **not all researchers have access to expensive solar simulators or STC-certified equipment**. In many cases, experiments are performed under light sources that do not accurately reproduce the solar spectrum.  

Thus, this dataset provides a **reliable, real-world reference** for parameter estimation and digital twin applications in photovoltaic systems.

---

## License
This dataset is released under the **MIT License**. Please cite this repository if you use it in your research.
