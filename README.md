# 🌊 Oceanographic Measurement Boat Trip — Toulon Bay, France

> A field-based oceanography project measuring **temperature, salinity, oxygen, density, and surface currents** in the Mediterranean Sea using **CTD sensors** and **drifters**.  
> Conducted as part of the *Introduction to Oceanography* course at Université de Toulon.

---

## 📍 Overview

On **October 18, 2024**, our team conducted an oceanographic survey in **Toulon Bay** (Mediterranean Sea, France) to investigate both **vertical water-column properties** and **horizontal surface current dynamics**.

The experiment was divided into two major components:
1. **CTD Deployment** – Measuring Conductivity, Temperature, Depth (CTD), salinity, density, and oxygen across different depths.
2. **Drifter Deployment** – Tracking surface drifter movement to study current velocity and wind influence.

Three locations were chosen for sampling. The weather was clear (15–21 °C), with moderate wind but high waves due to recent storms.

---

## ⚙️ Repository Structure

.
├── Code_for_CTD/
│ └── Code/ # Python scripts for CTD data processing & plotting
│
├── drifters/ # Position, trajectory, and velocity calculations
│
├── Marine_boat_trip_report.pdf # Full project report (14 pages)
│
└── README.md


---

## 🧪 Methodology

### 🔹 **1. CTD Measurements**
- Two CTD deployments were made at **338 m** and **205 m** depth.
- Data collected: Temperature, Salinity, Density, and Oxygen.
- Python (`gsw`, `matplotlib`, `pandas`) used to compute depth from pressure and visualize vertical profiles.

#### Key Observations:
| Parameter | Finding |
|------------|----------|
| **Temperature** | Typical thermocline structure — surface ≈ 20 °C, rapid cooling below 50 m |
| **Salinity** | Surface ≈ 38.3 PSU → deep ≈ 38.6 PSU |
| **Density** | Stable stratification with strong pycnocline (50–150 m) |
| **Oxygen** | Decrease from 220 µmol/kg (surface) → 170 µmol/kg (deep) |

---

### 🔹 **2. Drifter Experiment**
Three drifters (different shapes and anchoring conditions) were deployed for ~90 min each:

| Drifter | Type | Anchor | Distance (km) | Avg. Velocity (m/s) |
|----------|------|---------|----------------|----------------------|
| Yellow   | Cylindrical | ✅ Anchored | 0.30 | 0.06 |
| White A  | Donut | ✅ Anchored | 0.46 | 0.10 |
| White B  | Donut | ❌ Unanchored | 0.85 | 0.15 |

#### Findings:
- Anchored drifters reflected **subsurface currents**, showing slower, steadier motion.  
- Unanchored drifters drifted farther and faster under **surface wind influence**.  
- Comparison between **October 16** and **October 18** showed higher velocities on windier days.

---

## 📊 Visualization Highlights

- **CTD Profiles:** Temperature, Salinity, and Density vs. Depth  
- **TS Diagram:** Identifying water masses by potential temperature–salinity relationship  
- **Drifter Paths:** Geographic trajectories and velocity variation  
- **Wind Analysis:** Data from Copernicus Marine Service showing day-to-day differences

---

## 🧩 Tools & Technologies
- **Python:** `pandas`, `numpy`, `matplotlib`, `gsw`, `geopy`
- **Copernicus Marine Data Portal:** wind and wave data
- **Haversine formula:** used for drifter distance computation
- **GPS data logging:** for drifter tracking

---

## 🧠 Key Learning Outcomes
- Hands-on experience with **CTD profiling and drifter deployment**
- Practical understanding of **stratification, thermocline, halocline, and pycnocline**
- Quantitative analysis of **wind–current relationships**
- Integration of **Python-based analysis** with real-world field measurements

---

## 👩‍🔬 Team
**Hyejoo Kwon**, Ahmed Borchani, Sahil Abdullayev, Anastasiia Frolova,  
Mukesh Sadhasivam, Akira Techapattaraporn, Godsfavour Ugwu-Gabriel,  
Seyed Amirhesaan Mirabolghasemi  

📍 *Université de Toulon – Erasmus Mundus MIR Program*  
🧑‍🏫 *Instructor: Prof. Anne Molcard*  

---

## 🔗 Repository
➡️ [GitHub: Oceanographic_Measurement_Boat_Trip](https://github.com/S1194789/Oceanographic_Measurement_Boat_Trip)
