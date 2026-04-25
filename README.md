# OpenLane-Based-ASIC-Implementation-of-a-Low-Power-16-Bit-Vedic-Multiplier-Using-Full-Swing-GDI-Logic
Low-power 16-bit Vedic multiplier ASIC design using full-swing GDI logic, implemented through complete RTL-to-GDSII flow with OpenLane.

## 📌 Overview

This project presents the design and ASIC implementation of a **low-power 16-bit Vedic multiplier** using **full-swing Gate Diffusion Input (GDI) logic**.
The design is implemented using the OpenLane RTL-to-GDSII flow, covering the complete ASIC design cycle from synthesis to physical design.

---

## 🎯 Objectives

* Design a **power-efficient 16-bit Vedic multiplier**
* Utilize **full-swing GDI logic** to reduce power consumption
* Implement complete **RTL-to-GDSII ASIC flow using OpenLane**
* Achieve **timing closure and optimized area**

---

## 🧠 Design Methodology

### 🔹 Vedic Multiplication (Urdhva Tiryakbhyam)

* Uses parallel multiplication technique
* Reduces delay compared to conventional multipliers
* Improves computational speed

### 🔹 Full-Swing GDI Logic

* Minimizes transistor count
* Reduces dynamic power consumption
* Maintains full voltage swing for reliable operation

---

## ⚙️ ASIC Design Flow (OpenLane)

```text
RTL Design → Synthesis → Floorplanning → Placement → Clock Tree Synthesis → Routing → STA → GDSII
```

### 🔸 Steps:

1. **RTL Design**

   * Verilog implementation of 16-bit Vedic multiplier

2. **Synthesis**

   * Logic synthesis using OpenLane (Yosys)
   * Gate-level netlist generation

3. **Floorplanning**

   * Die area and core utilization setup
   * IO pin placement

4. **Placement**

   * Standard cell placement optimization

5. **Clock Tree Synthesis (CTS)**

   * Clock distribution network generation

6. **Routing**

   * Global and detailed routing

7. **Static Timing Analysis (STA)**

   * Timing verification across PVT corners

8. **GDSII Generation**

   * Final layout file for fabrication

## 🧪 Tools Used

* OpenLane
* Yosys (Synthesis)
* OpenROAD (Physical Design)
* Magic (Layout Visualization)
* Netgen (LVS)

## 📊 Key Features

* Low power consumption using GDI logic
* Reduced transistor count
* Faster computation using Vedic algorithm
* Fully automated ASIC flow
* Timing-aware optimized design

## 📈 Results

* Successful RTL-to-GDSII implementation
* Timing closure achieved
* Reduced power compared to conventional CMOS design
* Area-efficient layout generation

## 🖼️ Outputs

* Gate-level netlist
* Timing reports
* Power analysis reports
* Final GDSII layout

## 🚀 Future Improvements

* Extend to **32-bit / 64-bit multipliers**
* Compare with **Booth and Wallace tree multipliers**
* Implement **low-voltage design techniques**
* Explore **FinFET-based implementation**

## 📌 Conclusion

The project demonstrates an efficient approach to ASIC design by combining **Vedic multiplication** with **GDI logic**, achieving reduced power consumption and improved performance.
The use of **OpenLane** enables a complete open-source RTL-to-GDSII flow, making the design reproducible and scalable.

---
