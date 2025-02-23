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
- **Commissioned By:** TBC
- **Website Used In:** [Shane Smith Grab Hire Aggregates Calculator](https://www.shanesmithgrabhire.uk/aggregates-calculator/)

---

## 🔩 Technical Information

---

## 🏠 1. Square Slabs & Footings  
### **📏 Formula:**
    V = Length × Width × Depth

### **📥 Inputs:**  
- **Length (m):** Total length of the slab or footing.  
- **Width (m):** Total width of the slab or footing.  
- **Depth (m):** Thickness of the slab.  

### **📊 Example Calculation:**  
- Length: **4m**, Width: **3m**, Depth: **0.2m**  
    V = 4 × 3 × 0.2 = 2.4m³

---

## 🏛️ 2. Round Slabs & Columns  
### **📏 Formula:**  
    V = π × (Diameter / 2)² × Depth

### **📥 Inputs:**  
- **Diameter (m):** Full width of the round slab or column.  
- **Depth (m):** Thickness or height of the round slab.  

### **📊 Example Calculation:**  
- Diameter: **12m**, Depth: **6m**  
    V = π × (12 / 2)² × 6 V = π × (6)² × 6 V = 678.58m³

---

## 🏗️ 3. Stairs  
This follows the **Omni Calculator** approach for stair volume estimation.  

### **📥 Inputs:**  
- **Platform Depth (m):** Depth of the landing area.  
- **Rise Height (m):** Vertical height of each step.  
- **Run Depth (m):** Horizontal length of each step.  
- **Throat Depth (m):** Thickness of the stair slab.  
- **Width (m):** Total width of the stairs.  
- **Number of Steps:** Total number of steps.  

### **🔢 Calculation Steps:**  
1. **📏 Step Area:**  
    A_s = (Run Depth × Rise Height) / 2

2. **🛠️ Carriage Portion Area:**  
    A_c = Diagonal Length × Throat Depth

(where diagonal length is calculated using **Pythagoras' theorem**)  
3. **📦 Total End Area:**  
    A_t = Number of Steps × (A_s + A_c)

4. **🏗️ Final Volume:**  
    V = A_t × Width

### **📊 Example Calculation:**  
- Platform Depth: **10m**, Rise Height: **10m**, Run Depth: **10m**, Throat Depth: **10m**, Width: **10m**, Steps: **5**  
- **Final Volume:**  

---

## 🔩 4. Fence Post Holes  
### **📏 Formula:**  
    V = π × r² × Depth × Number of Posts

### **📥 Inputs:**  
- **Radius (m):** Half of the diameter of each fence post hole.  
- **Depth (m):** Depth of each hole.  
- **Number of Posts:** Total number of fence posts.  

### **📊 Example Calculation:**  
- Radius: **0.2m**, Depth: **0.5m**, Number of Posts: **5**  
    V = π × (0.2)² × 0.5 × 5 = 0.314m³

---

## ⚖️ Weight Calculation  
The estimated **weight of the concrete** is calculated using the **standard density of concrete**:  
    Weight = Volume × 2.4

Where **2.4** represents the **approximate density of concrete in tons per cubic meter**.  

---
