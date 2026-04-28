<h1 align="center" style="font-size:25px;">
  Hazardous Waste Detection in Scrap Yard Environments
</h1>

<p align="center">

<img src="https://img.shields.io/badge/Colab-F57C00?style=flat-square&logo=googlecolab&logoColor=white"/>
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
  <img src="assets/workflow_6.png",width="100%"/>
</p>


<p align="center">
  <img src="assets/system_8.png",width="100%"/>
</p>



---

### 🎯 Targeted Classes

| Class                 | Why Hazardous ⚠️                              | What Can Happen 💥                                          | Action ⚙️                                                      | Why This Action Matters 💡                                  | Business Impact 💼                                      |
| --------------------- | --------------------------------------------- | ----------------------------------------------------------- | -------------------------------------------------------------- | ----------------------------------------------------------- | ------------------------------------------------------- |
| **Gas Cylinder**      | Contains high-pressure gas inside             | Can explode when crushed or heated during processing        | Detect → Isolate → Check pressure → Release gas safely → Scrap | Releasing pressure prevents explosions during shredding     | Avoids major machine damage and serious worker injuries |
| **Shock Absorber**    | Contains pressurized oil or gas               | Can burst suddenly and send debris flying                   | Detect → Remove → Release pressure → Scrap                     | Removing internal pressure prevents sudden breakage         | Reduces accidents and machine downtime                  |
| **Capacitor**         | Stores electrical energy even after use       | Can discharge suddenly, causing sparks or fire              | Detect → Discharge safely → Inspect → Process                  | Safe discharge removes electrical risk                      | Protects equipment and prevents fire hazards            |
| **Motor**             | Contains electrical and mechanical components | Can cause sparks, oil leakage, or injury due to heavy parts | Detect → Inspect → Test → Reuse or Scrap                       | Motors can still be reused, so checking helps recover value | Increases profit and reduces material waste 💰          |
| **Sealed Tank**       | May contain unknown gas or liquid             | Can explode or release toxic substances unexpectedly        | Detect → Isolate → Inspect → Handle with care                  | Unknown contents must be checked before processing          | Prevents unexpected failures and safety risks           |
| **Fire Extinguisher** | Contains pressurized chemical agents          | Can explode or expose workers to chemicals                  | Detect → Remove → Release pressure → Recycle safely            | Releasing pressure avoids explosion risk                    | Improves workplace safety and ensures compliance        |

---
