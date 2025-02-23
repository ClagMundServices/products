# 🏗️ Aggregates Calculator

---

## Overview
The Aggregates Calculator is a live, user-friendly tool designed to accurately estimate the volume of aggregates needed for construction projects. It has been successfully integrated into the [Shane Smith Grab Hire website](https://www.shanesmithgrabhire.uk/aggregates-calculator/).

---

## Features
- **Accurate Estimations:** 
    Quickly computes the required volume of aggregates.
- **User-Friendly Interface:** 
    Simplifies the process for both professionals and DIY enthusiasts.
- **Responsive Design:** 
    Ensures a seamless experience across all devices.

---

## Details
- **Date Created:** 2024-10-15  
- **Commissioned By:** The Domain Directory
- **Website Used In:** [Shane Smith Grab Hire Aggregates Calculator](https://www.shanesmithgrabhire.uk/aggregates-calculator/)

---

## 🔩 Technical Information

---

## 🏗️ 1. Aggregates Volume Calculation  
### **📏 Formula:**  
    V = Length × Width × (Depth / 1000)  

### **📥 Inputs:**  
- **Length (m):** Total length of the area where aggregates are required.  
- **Width (m):** Total width of the area where aggregates are required.  
- **Depth (mm):** Depth of the aggregate layer in millimeters.  

### **📊 Example Calculation:**  
- Length: **5m**, Width: **4m**, Depth: **100mm**  
    V = 5 × 4 × (100 / 1000)  
    V = 5 × 4 × 0.1  
    V = **2m³**  

---

## ⚖️ 2. Approximate Tonnage Calculation  
Once the **volume (m³)** is determined, the **tonnage** is calculated using the density of the selected material.

### **📏 Formula:**  
    Tonnage = Volume × Density  

### **📥 Inputs:**  
- **Volume (m³):** The calculated volume of the aggregate required.  
- **Density (t/m³):** The approximate density of the selected aggregate material.  

| **Material Type**    | **Density (t/m³)** |
|----------------------|-------------------|
| Type 1 MOT          | 2.4               |
| Top Soil            | 1.4               |
| Compost             | 0.8               |
| Sharp Sand          | 1.8               |
| Fill Sand           | 1.6               |

### **📊 Example Calculation:**  
- **Aggregate Type:** Sharp Sand  
- **Volume:** **2m³**  
- **Density:** **1.8 t/m³**  

    Tonnage = 2 × 1.8  
    Tonnage = **3.6 tonnes**  

---

## 🔄 3. Conversion Notes  
- **Depth is entered in millimeters (mm), but the calculation converts it to meters (m) by dividing by 1000.**  
- **Densities used are approximate and may vary based on supplier and compaction factors.**  
- **Final tonnage is rounded to the nearest whole number for estimation purposes.**  

---

