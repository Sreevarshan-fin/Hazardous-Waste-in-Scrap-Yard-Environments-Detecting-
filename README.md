<h1 align="center" style="font-size:22px;">
  Hazardous Waste Detection in Scrap Yard Environments
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

-----------------

<h2 align="center" style="font-size:15px;">
  End-to-End System for Hazardous Waste Detection in Scrap Yard
</h2>
  
  
  <p align="center">
  <img src="assets/ml_final.png",width="100%"/>
</p>


<p align="center">
  <img src="assets/system_final.png",width="100%"/>
</p>



---

### 🎯 Targeted Classes

**The system focuses on detecting the following high-risk and value-critical objects:**

| Class                 | Why Hazardous ⚠️         | Risk 💥              | Action ⚙️                                    | Impact 💼                          |
| --------------------- | ------------------------ | -------------------- | -------------------------------------------- | ---------------------------------- |
| **Gas Cylinder**      | High-pressure gas        | Explosion            | Detect → Isolate → Release gas → Scrap       | Prevents major damage & injuries   |
| **Shock Absorber**    | Pressurized oil/gas      | Burst, debris        | Detect → Remove → Release pressure → Scrap   | Reduces accidents & downtime       |
| **Capacitor**         | Stored electrical energy | Sparks, fire         | Detect → Discharge → Process                 | Prevents electrical hazards        |
| **Motor**             | Electrical + heavy parts | Sparks, leakage      | Detect → Check → Reuse/Scrap                 | Increases value & reduces waste 💰 |
| **Sealed Tank**       | Unknown contents         | Explosion/toxic leak | Detect → Isolate → Inspect                   | Avoids unexpected failures         |
| **Fire Extinguisher** | Pressurized chemical     | Explosion/exposure   | Detect → Remove → Release pressure → Recycle | Improves safety & compliance       |

----
