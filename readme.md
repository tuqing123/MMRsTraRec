# 🚗 MMRsTraRec: Denoising and Reconstruction of Vehicle Trajectories Using Millimeter Wave Radars Group

## 📌 Overview

Reconstructing vehicle trajectories is critical for traffic analysis and intelligent transportation systems. However, roadside millimeter-wave radar (MMR) data often suffer from noise, outliers, and missing values—especially across multiple dimensions like position and speed.

This project presents an optimization-based trajectory reconstruction method tailored for wide-area MMR deployments. It handles complex data anomalies while ensuring internal consistency across different dimensions (e.g., position and velocity). A prior-guided mechanism, which includes a masking strategy and adaptive scaling, is used to tackle data missing due to MMR blind areas.

We provide:
- A complete implementation of the proposed joint optimization framework
- Two representative case studies with real or simulated data
- Environment setup for quick start

---

## ⚙️ Environment Setup

You can set up the environment using either `pip` or `conda`.

### Option 1: pip (recommended if using virtualenv)

```bash
git clone https://github.com/tuqing123/MMRsTraRec.git
cd MMRsTraRec
pip install -r requirements.txt
```

### Option 2: conda

```
conda env create -f environment.yml
conda activate mmr-traj
```

------

## 🚀 How to Run

All visualization cases have been integrated into `case.ipynb` for easier review and execution. Simply open the notebook to explore the following two scenarios:

### 🔹 Case 1: The Proposed Joint Optimization Framework (No Mask)

- Description: A complete scenario without missing zones, showcasing the full performance of the proposed optimization.

### 🔹 Case 2: Scenario with Missing Zones

- Description: A challenging case with observation gaps, demonstrating the model's performance in handling blind areas and data imputation.

> 📘 You do not need to run individual Python scripts. Please execute the corresponding cells in `case.ipynb`.

------

## 📚 Method Highlights

- **Joint optimization framework** that integrates position and speed reconstruction
- **Prior-guided missing data handling**, using dynamic masking and scaling
- **Robust to radar blind zones**, noise, and large missing segments
- Validated through **field experiments**

------

## 📜 License

This project is licensed under the MIT License. See the LICENSE file for details.

------

## 📬 Contact

Feel free to reach out for questions, feedback, or collaboration opportunities:

**Your Name**
 Email: lchengmin9@gmail.com
 GitHub: [tuqing123](https://github.com/tuqing123)

------

> ⭐ If you find this project helpful, feel free to give it a star and share it with others!