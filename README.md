# RTL2GDSII-PROJECT

## 🔧 Project Title:
**RTL2GDSII Flow for 4-bit Full Adder-Subtractor**

## 📁 Repository Structure:
This repository contains all relevant design files and reports for implementing a 4-bit full adder-subtractor using a complete RTL-to-GDSII flow.

## 📌 Overview:
This project demonstrates the physical design flow of a 4-bit Full Adder-Subtractor using industry-grade tools including Synopsys Design Compiler (DC), ICC2, PrimeTime, and Verdi. It starts from RTL design and ends at timing closure after routing, following the ASIC digital design methodology.

## 📂 Directory Contents:

| File/Folder Name           | Description |
|----------------------------|-------------|
| `CONSTRAINTS.zip`          | SDC and other constraint files used for synthesis and implementation |
| `DC.zip`                   | Design Compiler scripts, reports, and netlists |
| `FULL_ADD_SUB_PROJECT_23BIT153.zip` | RTL source files (Verilog), testbench, and behavioral simulations |
| `PT.zip`                   | PrimeTime reports for timing analysis and final slack verification |
| `rtl_simulation.zip`       | VCS + Verdi simulation results including waveform and schematic |
| `README.md`                | Project description and documentation |

## ✅ Tools Used:
- **Synopsys Design Compiler (DC)** – RTL synthesis
- **Synopsys ICC2** – Physical design (floorplan to routing)
- **Synopsys PrimeTime (PT)** – Static timing analysis
- **Synopsys Verdi** – Simulation and waveform analysis
- **VCS** – Simulation and debugging

## 🧠 Project Steps:

1. **RTL Design:**
   - Verilog code written for a 4-bit full adder-subtractor
   - Testbench created and simulated in VCS
   - Functional verification performed via Verdi (waveform + schematic)

2. **Synthesis (DC):**
   - RTL synthesized using `run.dc.tcl`
   - Gate-level netlist generated and checked for positive slack

3. **Physical Design (ICC2):**
   - Floorplanning
   - Power Planning
   - Placement
   - Clock Tree Synthesis
   - Routing
   - Slack verified at each stage to maintain timing within 0–1 ns

4. **Timing Analysis (PrimeTime):**
   - Final slack report after routing
   - Design verified for setup/hold timing and power constraints

## 📸 Screenshots:
Include the following in your repo for better documentation:
- RTL waveform (VCS + Verdi)
- Schematic diagram
- DC synthesis report snapshot
- Floorplan, placement, and routing images
- Final PT slack report

## 🎯 Outcome:
The project successfully meets the timing and functional objectives of a 4-bit adder-subtractor, demonstrating complete RTL2GDSII flow from design to physical verification.

---

## 📫 Contact
For any queries, please reach out to:
- **Pushkar Kanjani** – [GitHub Profile](https://github.com/PushkarKanjani)

