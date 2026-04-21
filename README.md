<h1 align="center">Hazardous Waste Detection in Scrap Yard Environments</h1>

----------

<p align="center">
  <img src="assets/workflow.png"/>
</p>

---


### 🔎 Problem Statement

Scrap yards process **1000+ tons of mixed metal waste**, where hazardous objects such as pressurized cylinders, shock absorbers, sealed tanks, and electrical components are often difficult to identify during sorting operations.

Failure to detect such materials can result in **explosions, fires, equipment damage, and worker injuries**, especially during shredding or crushing processes, leading to **operational downtime and financial losses**.

Current inspection methods rely on **manual monitoring**, which is slow, inconsistent, and prone to human error. Factors such as **fatigue and high processing speed contribute to estimated miss rates of 15–25%**, making manual inspection unreliable for real-time industrial environments.

Additionally, certain components like motors may still have **residual value**, but are often misclassified as scrap, resulting in **loss of potential revenue**.

👉 Therefore, there is a need for an **automated, real-time hazard detection and decision-making system** that can:

* Accurately identify hazardous objects
* Trigger appropriate actions (alerts, isolation, safe handling)
* Improve workplace safety and reduce accidents
* Enhance operational efficiency and reduce downtime
* Enable intelligent decision-making
* Support value recovery from reusable components like motors

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


