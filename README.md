<h1 align="center" style="font-size:22px;">
  Hazardous Metal Waste Detection in Scrap Yard Environments
</h1>

<p align="center">

<img src="https://img.shields.io/badge/Colab-T4%20GPU-F57C00?style=flat-square&logo=googlecolab&logoColor=white"/>
<img src="https://img.shields.io/badge/YOLO-00ACC1?style=flat-square&logo=yolo&logoColor=white"/>
<img src="https://img.shields.io/badge/Ultralytics-5E35B1?style=flat-square&logo=ultralytics&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-1E88E5?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/FastAPI-00897B?style=flat-square&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenCV-E53935?style=flat-square&logo=opencv&logoColor=white"/>
<img src="https://img.shields.io/badge/Pillow-FDD835?style=flat-square&logo=python&logoColor=black"/>
<img src="https://img.shields.io/badge/AWS%20EC2-F4511E?style=flat-square&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Streamlit-D32F2F?style=flat-square&logo=streamlit&logoColor=white"/>
<img src="https://img.shields.io/badge/Augmentation-43A047?style=flat-square&logo=tensorflow&logoColor=white"/>

</p>




---
### 🔎 Project Overview

An industrial hazardous waste detection system developed using **YOLOv8 segmentation** to identify high-risk objects in complex scrap yard environments. The project includes a custom dataset of **250+** self-annotated images across **6 hazardous object classes**, along with **imbalance-aware training**, **segmentation modeling**, and **deployment engineering**. The system focuses on improving **high-recall detection** and **Mask mAP** performance for safety-critical monitoring through optimized training strategies and cloud-based real-time deployment.

-----------------

<h2 align="center" style="font-size: 9 px;">
  End-to-End System for Hazardous Waste Detection in Scrap Yard
</h2>
  
  
  <p align="center">
  <img src="assets/ml_final.png",width="100%"/>
</p>


<p align="center">
  <img src="assets/system_final.png",width="100%"/>
</p>



---

### 🔎 Problem Statement

Scrap yards process **1000+ tons of mixed metal waste**, where **hazardous objects** such as **pressurized cylinders, shock absorbers, sealed tanks, and capacitors** are **difficult to identify** during sorting.

Failure to detect these materials can cause **explosions, fires, equipment damage, and serious worker injuries**, especially during **shredding or crushing**, leading to **safety risks, operational downtime, and financial losses**.

Current inspection relies on **manual monitoring**, which is **slow, inconsistent, and error-prone**, with miss rates of **15–25%** due to **fatigue, high speed, and limited visibility**, making it **unreliable for real-time environments**.

Additionally, valuable components like **motors** are often **misclassified as scrap**, resulting in **inefficient resource use and lost revenue**.


👉 These challenges have a direct impact on **overall business performance**:

* **Financial Loss** – medical costs, machine damage, higher insurance
* **Operational Downtime** – production stops, reduced efficiency
* **Legal & Compliance Risks** – penalties, compensation claims
* **Reputation & Workforce Impact** – loss of trust, low morale, reduced productivity

---

## 📊 Dataset Information

- 250+ self-annotated industrial scrap images
- Polygon annotations for YOLOv8 segmentation
- 6 hazardous industrial object classes
- Imbalance-aware dataset preparation using oversampling
- Images collected from cluttered scrap-yard-like environments
- Designed for safety-critical industrial monitoring scenarios

**The system target classes to focuses on detecting the following high-risk and value-critical objects:**

| Class | Why Hazardous | Risk | Action | Impact |
|---|---|---|---|---|
| **Gas Cylinder** | High-pressure gas | Explosion | Detect → Isolate → Release gas → Scrap | Prevents major damage & injuries |
| **Shock Absorber** | Pressurized oil/gas | Burst and flying debris | Detect → Remove → Release pressure → Scrap | Reduces accidents & downtime |
| **Capacitor** | Stored electrical energy | Sparks or fire | Detect → Discharge → Process | Prevents electrical hazards |
| **Motor** | Electrical + heavy components | Sparks, leakage | Detect → Inspect → Reuse / Scrap | Increases value & reduces waste 💰 |
| **Sealed Tank** | Unknown contents | Explosion or toxic leak | Detect → Isolate → Inspect | Avoids unexpected failures |
| **Fire Extinguisher** | Pressurized chemical | Explosion or exposure | Detect → Remove → Release pressure → Recycle | Improves safety & compliance |

-------

## 🛠 Solution Approach

- Prepared a dataset with **250+ self-annotated industrial scrap images** across **6 hazardous object classes** for segmentation-based detection.

- Performed **polygon annotations** for **YOLOv8 segmentation** to enable accurate object boundary localization in cluttered industrial environments.

- Conducted **dataset quality checks** including **annotation quality verification, missing label inspection, duplicate analysis, label consistency validation, and class distribution analysis** to improve training reliability.

- Applied **preprocessing techniques** such as **image resizing** and **label validation** for consistent data preparation.

- Addressed severe **class imbalance** using **oversampling techniques** along with **controlled augmentation** to improve minority-class diversity and **high-recall detection performance**.

- Trained a **YOLOv8 segmentation model** using **transfer learning** and optimized the pipeline for **Recall** and **Mask mAP** performance in safety-critical scenarios.

- Evaluated both **detection** and **segmentation** performance using **Precision, Recall, mAP@0.5, mAP@0.5–0.95, and Mask mAP metrics**.

- Deployed the complete system using **Docker, Streamlit, and AWS EC2**, and simulated a **real-time industrial hazardous-object monitoring workflow**.
