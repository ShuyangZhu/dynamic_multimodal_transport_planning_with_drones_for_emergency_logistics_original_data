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
  - `No-G` – Results excluding the greedy-related operators
  - `No-R` – Results excluding the random-related operators  
  - `No-M` – Results excluding the multimodal-specific operators  

- **Stability analysis of ALNS**  
  Provides 10 runs of ALNS under identical settings to test its stability and robustness.

- **Comparison of approaches with and without drones**  
  Comparative results between multimodal approaches:  
  - `without drones` – only cargo aircraft, trains, and trucks  
  - `with drones` – intergrated drones into the cargo aircraft-train-truck multimodal system

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
  - `0-100` – 0% emergency orders, 100% normal orders  
  - `20-80` – 20% emergency orders, 80% type normal orders 
  - `50-50` – 50% emergency orders, 50% type normal orders  

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

