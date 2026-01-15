# Comparison of Free and Immobilized Enzyme Kinetics using Python

## Overview
This project analyzes and compares the kinetic behavior of **free** and **immobilized** enzymes using experimental laboratory data. The analysis is performed in a Jupyter Notebook using Python to visualize enzyme kinetics and interpret the effects of enzyme immobilization on catalytic performance.

The study focuses on:
- Reaction velocity as a function of substrate concentration
- Comparison of kinetic behavior between free and immobilized enzymes
- Linearized kinetic analysis using the Lineweaver–Burk method

---

## Experimental Background
Enzyme immobilization is widely used in bioprocessing due to advantages such as enzyme reusability, improved stability, and ease of separation. However, immobilization can alter enzyme kinetics due to diffusion limitations, steric hindrance, and reduced accessibility of active sites.

This project investigates these effects by comparing experimentally measured reaction rates for free and immobilized enzymes under varying substrate concentrations.


---

## Data Description
The experimental dataset includes:
- Substrate concentration (mg/ml)
- Reaction velocity (V)
- Measurements for both free and immobilized enzyme systems

The data is structured into a single, tidy dataframe to enable direct comparison between enzyme types.

---

## Kinetic Analysis

### Michaelis–Menten Behavior
Reaction velocity versus substrate concentration plots show classical saturation kinetics for both enzyme systems.

- The **free enzyme** exhibits a rapid increase in velocity at low substrate concentrations and reaches a higher maximum velocity, indicating efficient substrate binding and turnover.
- The **immobilized enzyme** shows significantly lower reaction velocities across all substrate concentrations and reaches saturation earlier.

This behavior suggests that immobilization reduces effective catalytic activity, primarily due to mass transfer resistance and limited substrate diffusion to the enzyme active sites.

---

### Lineweaver–Burk Analysis
To further compare kinetic parameters, the data is linearized using the Lineweaver–Burk transformation (1/V vs 1/S).

Key observations:
- The immobilized enzyme displays a higher y-intercept, indicating a lower apparent Vmax.
- The slope of the immobilized enzyme plot is steeper, suggesting an increased apparent Km and reduced substrate affinity.

These changes are consistent with diffusion-controlled kinetics and partial loss of enzyme efficiency due to immobilization.

---

## Interpretation and Key Findings
- Free enzymes demonstrate higher catalytic efficiency and substrate accessibility.
- Immobilization leads to reduced reaction rates and altered apparent kinetic parameters.
- The Lineweaver–Burk plot confirms that immobilization impacts both maximum velocity and substrate affinity.
- While immobilization offers operational advantages, it introduces kinetic limitations that must be considered in bioprocess design.

---

## Tools and Libraries Used
- Python
- pandas
- numpy
- matplotlib
- Jupyter Notebook

---

## Conclusion
This project demonstrates how experimental enzyme kinetics data can be analyzed and interpreted using Python. The comparison highlights the fundamental trade-off in enzyme immobilization: improved process stability at the cost of reduced catalytic efficiency.

The notebook serves as a compact case study in applied enzymology and bioprocess data analysis.
