# 🌀 Birth Time Radial Visualization

## Overview

This Jupyter Notebook focuses on visualizing birth data in the USA for the year **2022** using a **radial plot**. The goal is to create a stylized circular visualization of births per minute throughout the day — inspired by the **“Baby Spike”** chart from *Scientific American* and *Visual Cinnamon*.

![5d3d00b6-ced2-48ef-b0b6-a3a59c8425fe](https://github.com/user-attachments/assets/2c3763cd-e0aa-4dbd-8e9b-330089ab7dc1)

The assignment uses **`pandas`**, **`matplotlib`**, and optionally **`numpy`** and **`math`** to preprocess and plot the data.

---

## 🔍 Objective

Created a radial plot showing the **average number of babies born per minute** in 2022 using:

- Circular layout with **minute-level resolution** (1440 minutes per day)
- Yellow average line at ~**7 births/minute** (`#FFDE00`)
- Color gradients using `.fill_between()` to show deviations:
  - Blue gradient for values **below average**
  - Red gradient for values **above average**
- Gradient bins scaled in 25% steps (every 3 colors per ±25% change)
- Hour labels around the circular axis  
- Dashed circular reference lines for **6** and **9** births per minute

---

## 📁 Files Included

- `Assignment 5.ipynb` – Jupyter notebook with full code and visualization  
- `births.csv` – Raw dataset with birth times across 2022
- 
---

## 📊 Visualization Preview

The notebook produces a circular visualization where:
- The **highest spike occurs around 8:00 AM**
- The **average line** is clearly visible
- Color bands provide a gradient that reflects birth density relative to the mean
- All design elements are tuned for visual clarity and stylistic accuracy

---

## 🧪 Technologies Used

- Python  
- [pandas](https://pandas.pydata.org/)  
- [matplotlib](https://matplotlib.org/)  
- [seaborn](https://seaborn.pydata.org/) (optional)  
- [numpy](https://numpy.org/) (optional)  
- [math](https://docs.python.org/3/library/math.html)

---

## 📚 References

- [CDC – National Center for Health Statistics](https://www.cdc.gov/nchs/data_access/vitalstatsonline.htm)  
- [The Baby Spike – Nadieh Bremer](https://www.visualcinnamon.com/portfolio/baby-spike/)  
- [Why So Many Babies Are Born at 8AM – SciAm](https://blogs.scientificamerican.com/sa-visual/why-are-so-many-babies-born-around-8-00-a-m/)
