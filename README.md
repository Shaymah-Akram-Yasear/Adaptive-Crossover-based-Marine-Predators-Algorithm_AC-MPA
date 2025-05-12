# Adaptive Crossover-based Marine Predators Algorithm (AC-MPA)

This is the original implementation of the **Adaptive Crossover-based Marine Predators Algorithm (AC-MPA)**. The algorithm is archived in Zenodo with DOI: https://doi.org/10.5281/zenodo.1234567 

## 🔍 Overview

The AC-MPA algorithm introduces an adaptive crossover mechanism into the standard Marine Predators Algorithm (MPA) to enhance its exploration and exploitation capabilities. This version improves convergence performance and avoids premature convergence in solving global optimization problems.

## 📘 Reference Paper

The mathematical formulation and experimental results of AC-MPA are detailed in the following peer-reviewed publication:

> **Shaymah Akram Yasear**,  
> *Adaptive crossover-based marine predators algorithm for global optimization problems*,  
> **Journal of Computational Design and Engineering**, Volume 11, Issue 4, August 2024, Pages 124–150  
> [DOI: 10.1093/jcde/qwae060](https://doi.org/10.1093/jcde/qwae060)

## 📁 Repository Contents

- `ACMPA.m` – Main MATLAB implementation of AC-MPA  
- `Main_ACMPA.m` – Definitions of benchmark functions used in experiments
- `CEC2027/` – CEC2027 test suit
- `input_data_CEC17/` – Input data of CEC2017 benchmark funtions
- `adaptiveSamplingMaximinDistance.m` – Adaptive Sampling with Maximin Distance Criterion
- `levy.m` – Lévy flight


## 🛠️ Requirements

- MATLAB R2020b or later

## 📬 Contact

For questions, feedback, or collaboration opportunities, please contact:

📧 **shayma.akram.yasear@gmail.com**

## 📜 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
