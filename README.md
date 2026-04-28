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


<p align="center">

<img src="https://img.shields.io/badge/Colab-ffffff?style=flat&logo=googlecolab&logoColor=F57C00"/>
<img src="https://img.shields.io/badge/YOLO-ffffff?style=flat&logo=yolo&logoColor=00ACC1"/>
<img src="https://img.shields.io/badge/Ultralytics-ffffff?style=flat&logo=ultralytics&logoColor=5E35B1"/>
<img src="https://img.shields.io/badge/Docker-ffffff?style=flat&logo=docker&logoColor=1E88E5"/>
<img src="https://img.shields.io/badge/FastAPI-ffffff?style=flat&logo=fastapi&logoColor=00897B"/>
<img src="https://img.shields.io/badge/OpenCV-ffffff?style=flat&logo=opencv&logoColor=E53935"/>
<img src="https://img.shields.io/badge/Pillow-ffffff?style=flat&logo=python&logoColor=FDD835"/>
<img src="https://img.shields.io/badge/AWS%20EC2-ffffff?style=flat&logo=amazonaws&logoColor=F4511E"/>
<img src="https://img.shields.io/badge/Streamlit-ffffff?style=flat&logo=streamlit&logoColor=D32F2F"/>

</p>

---

# 🔎 Problem Statement

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

| Class                 | Why Hazardous ⚠️                   | What Happens 💥                        | Action ⚙️                                                | Why This Action Matters 💡                               | Business Impact 💼                          |
| --------------------- | ---------------------------------- | -------------------------------------- | -------------------------------------------------------- | -------------------------------------------------------- | ------------------------------------------- |
| **Gas_Cylinder**      | High-pressure gas stored inside    | Explosion when crushed/heated          | Detect → Isolate → Check pressure → Depressurize → Scrap | Pressure release prevents blast during shredding         | Avoids catastrophic damage & worker injury  |
| **Shock_Absorber**    | Contains pressurized oil/gas       | Sudden rupture → flying debris         | Detect → Remove → Depressurize → Scrap                   | Removing internal pressure prevents rupture              | Reduces accidents & machine downtime        |
| **Capacitor**         | Stores electrical charge           | Sudden discharge → sparks/fire         | Detect → Discharge → Inspect → Process                   | Safe discharge eliminates electrical hazard              | Protects equipment & prevents fire risk     |
| **Motor**             | Electrical + mechanical components | Sparks, oil leakage, heavy part injury | Detect → Inspect → Test → Reuse / Resell or Scrap        | Motors may still work → recover value instead of wasting | Increases profit & reduces material loss 💰 |
| **Sealed_Tank**       | Unknown contents (gas/liquid)      | Unexpected explosion or toxic leak     | Detect → Isolate → Inspect → Controlled handling         | Unknown risk must be verified before processing          | Prevents unpredictable failures & hazards   |
| **Fire_Extinguisher** | Pressurized chemical container     | Explosion or chemical exposure         | Detect → Remove → Depressurize → Safe recycle            | Releasing pressure avoids blast risk                     | Ensures safety & regulatory compliance      |


---

