# Stepped Shaft – CAD & FEA Analysis

## 📌 Project Description  
This project focuses on the **design and analysis of a stepped shaft** to evaluate its structural performance under load. The shaft was modeled using **Autodesk Fusion 360** and analyzed in **ANSYS Workbench** with a **Static Structural + Fatigue assessment**.  

The objective was to study:  
- Stress distribution (Equivalent / von Mises Stress)  
- Fatigue Life prediction  
- Factor of Safety evaluation  

---

## 🛠 Tools Used  
- **Fusion 360** → 3D CAD Modeling  
- **ANSYS Workbench** → Finite Element Analysis (FEA)  

---

## ⚙️ Methodology  
1. Designed a stepped shaft in Fusion 360.  
2. Imported the geometry into ANSYS Workbench.  
3. Applied boundary conditions:  
   - Load: **1000 N applied in Y-direction**  
   - Appropriate fixtures at supports  
4. Generated mesh (refined near step region to capture stress concentration).  
5. Solved for:  
   - Equivalent (von Mises) Stress  
   - Fatigue Life  
   - Safety Factor  

---

## 📊 Results  
- **Stress Concentration:** High stresses observed near the step.  
- **Fatigue Life:** Estimated life indicates durability limits under cyclic loading.  
- **Safety Factor:** Critical regions identified where design may need optimization.  

📂 Detailed plots and reports are available in the `ANSYS_Results/` folder.  

### Sample Results  
![Stress Plot](ANSYS_Results/02_eqv_stress.png)  
![Fatigue Life]([ANSYS_Results/03_fatigue_life.png](https://github.com/gowtham-d-p/stepped-shaft-fea-fusion-ansys/blob/main/Stepped%20Shaft/Ansys%20Workbench/Life.jpg))  

---

## 🎯 Key Learnings  
- Even simple components like shafts can show complex stress patterns.  
- FEA helps predict failure regions before physical testing.  
- Hands-on experience gained in the **CAD → FEA workflow**.  

---

## 🚀 Future Work  
- Explore bending and torsional load conditions.  
- Compare FEA results with analytical hand calculations.  
- Optimize geometry for improved fatigue resistance.  

---

## 📂 Repository Structure  
