# ME 401: H-Infinity Control for Aircraft Dynamics  

## Description  
This repository contains solutions for **ME 401 Exam 2**, focusing on **H-infinity control** applied to **longitudinal and lateral-directional aircraft dynamics**. The tasks involve designing **H-infinity state feedback controllers** to track specific flight commands and regulate stability parameters while optimizing performance using the gamma-iteration method.  

## Files Included  

### **Part 1: Longitudinal Dynamics Control**  
- **File:** ME 401 Exam 2_1.py  
- **Topics Covered:**  
  - Design of an **H-infinity state feedback controller** for maintaining a **constant speed** and **angle of attack**.  
  - Implementation of the **gamma-iteration method** for tuning the controller.  
  - Step response analysis for tracking performance evaluation.  

### **Part 2: Lateral-Directional Dynamics Control**  
- **File:** ME 401 Exam 2_2.py  
- **Topics Covered:**  
  - Development of an **H-infinity controller** for tracking a **constant roll rate** and regulating the **sideslip angle (β)**.  
  - Stability assessment using eigenvalue analysis and frequency-domain responses.  
  - Optimization of system robustness via **H-infinity norm calculations**.  

### **Exam Report**  
- **File:** ME 401 Exam 2.pdf  
- **Contents:**  
  - Problem statements with given **state-space representations (A, B, C, D)**.  
  - Controller design objectives and required performance constraints.  
  - Stability analysis and expected system behavior under H-infinity control.  

## Installation  
Ensure **Python** and the required libraries are installed before running the scripts.  

### Required Python Packages  
- numpy  
- matplotlib  
- scipy  
- control  

To install the necessary packages, run:  
`pip install numpy matplotlib scipy control`  

## Usage  
1. Open a terminal or Python environment.  
2. Run the longitudinal dynamics control script:  
   `python ME\_401\_Exam\_2\_1.py`  
3. Run the lateral-directional dynamics control script:  
   `python ME\_401\_Exam\_2\_2.py`  
4. Analyze the **step response plots** and **H-infinity performance metrics** displayed in the output.  

## Example Output  

- **Longitudinal Control (Part 1)**  
  - H-infinity norm γ = **700**  
  - Step response plots for **velocity (V)** and **angle of attack (α)** tracking  

- **Lateral-Directional Control (Part 2)**  
  - H-infinity norm γ = **2.6**  
  - Step response plots for **roll rate (p)** and **sideslip angle (β)** tracking  

## Contributions  
This repository is designed for educational and research purposes. Feel free to fork and modify the scripts.  

## License  
This project is open for academic and research use.  

---
**Author:** Alexander Dowell  
