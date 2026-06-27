<h1 align="center">⚙️ separately excited dc motor simulation using matlab simulink</h1>

<h3 align="center">DC Motor Performance Analysis Project ⚡</h3>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=00F7FF&center=true&vCenter=true&lines=DC+Motor+Simulation+Using+MATLAB;Separately+Excited+DC+Motor;Armature+Resistance+Analysis;Speed+Torque+Characteristics;Series+RLC+Branch+Simulation" />
</p>

---

# 📌 project overview

This project investigates the effect of varying armature circuit resistance on the performance of a separately-excited DC motor using MATLAB/Simulink.

The simulation uses a **Series RLC Branch** configured as a pure resistor to introduce controlled resistance into the armature circuit. Different resistance values are tested to analyze their effect on:

* Motor Speed
* Electromagnetic Torque
* Field Current
* Power Factor

The results confirm that decreasing armature resistance reduces motor speed and torque while slightly increasing field current.

---

# 📖 description

The Simulink model consists of a separately-excited DC motor driven by a constant torque input. The armature circuit is connected to a Series RLC Branch block acting as a variable resistor.

Multiple simulations were performed using different resistance values:

| S2 Value      | Resistance (Ω) |
| ------------- | -------------- |
| Base          | 30 Ω           |
| 50            | 20 Ω           |
| 100           | 10 Ω           |
| 150           | 4.7 Ω          |
| Alternate 150 | 3.19 Ω         |

As resistance decreases:

* Armature current increases
* Motor speed decreases
* Torque reduces gradually
* Field current rises slightly
* Power factor remains near unity

The project demonstrates the practical relationship between armature resistance and DC motor speed-torque characteristics.

---

# 🛠 technologies used

* MATLAB
* Simulink
* Series RLC Branch
* DC Machine Block
* Powergui
* Electrical Machine Simulation
* Speed-Torque Analysis

---

# 📊 simulation results

✔ Base Speed = 1422 RPM
✔ Lowest Speed = 1282 RPM
✔ Maximum Torque = 1.383 p.u.
✔ Stable Field Excitation
✔ Power Factor Near Unity
✔ Multiple Resistance Analysis

---

# 📂 repository files

| File Name                 | Description                 |
| ------------------------- | --------------------------- |
| `README.md`               | Project documentation       |
| `DC_Motor_Report.docx`    | Detailed simulation report  |
| `simulation_results.docx` | Output and analysis results |

---

# 🚀 applications

* DC Motor Analysis
* Industrial Drive Systems
* Electrical Machine Studies
* Speed Control Systems
* Power Electronics Education

---

# 👩‍💻 author

## Zainab Bilal

Electrical Engineering Student ⚡

---

# ⭐ conclusion

The simulation successfully demonstrates the effect of armature resistance variation on the performance of a separately-excited DC motor. Results closely follow theoretical speed-torque characteristics while maintaining stable operation and near-unity power factor across all test cases.

---

<p align="center">
  ⭐ Thanks for visiting this repository ⭐
</p>
