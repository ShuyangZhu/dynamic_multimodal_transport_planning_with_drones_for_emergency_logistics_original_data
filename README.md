# Dynamic Multimodal Transport Planning with Drones for Emergency Logistics: Data and Results

This repository provides the original benchmark instances, parameter settings, and experimental results used in the paper:

**Dynamic Multimodal Transport Planning with Drones for Emergency Logistics: Mathematical Model and Heuristic Algorithm**

All data and results are organized into thematic folders as follows:

## Repository Structure

- **Comparison with the exact approach**  
  Contains results comparing the proposed heuristic algorithm with the exact solution approach.

- **The impact of different operator designs**  
  Contains experiments evaluating the influence of different operator designs in the ALNS heuristic:  
  - `All` – Results using all operators  
  - `No-G` – Results excluding the "G" operator  
  - `No-R` – Results excluding the "R" operator  
  - `No-M` – Results excluding the "M" operator  

- **Stability analysis of ALNS**  
  Provides multiple runs of ALNS under identical settings to test its stability and robustness.

- **Comparison of approaches with and without drones**  
  Comparative results between multimodal approaches:  
  - `without drones` – Ground-only transport  
  - `with drones` – Coordinated ground–air transport  

- **Comparison of static and dynamic models**  
  Analysis of planning under static and dynamic models:  
  - `static` – Static optimization model results  
  - `dynamic` – Dynamic rolling-horizon model results  

- **Performance under numerous sudden events**  
  Evaluates the system under different frequencies of sudden disruptions:  
  - `Low frequency` – Few sudden events  
  - `High frequency` – Frequent sudden events  

- **Results under heterogeneous cargoes**  
  Results with varying proportions of heterogeneous cargo:  
  - `0-100` – 0% type A cargo, 100% type B cargo  
  - `20-80` – 20% type A, 80% type B  
  - `50-50` – Equal split of cargo types  

- **Sensitivity analysis of key parameters**  
  Sensitivity tests with respect to major parameters:  
  - `benchmark` – Baseline experiments  
  - `the speed of vehicles` – Variations in vehicle speed  
  - `the unit transit cost of vehicles` – Variations in transport costs  
  - `the delay penalty coefficient` – Variations in delay penalty settings  
  - `drones` – Variations in drone-related parameters  

---

## Usage
All benchmark data and results are made publicly available to support **transparency and reproducibility**.  
Researchers can use these files to replicate or extend our experiments.  

## Citation
If you use this repository in your research, please cite our paper:

