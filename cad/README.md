# STR15 AutoCAD Designs
This folder contains the official STL, gcode, and final `.dwg` CAD files for the 70mm EDF rotor and housing replacement.
# 📐 STR15 AutoCAD & Print Files

This directory contains the official design, mesh, and manufacturing files for the 70mm EDF rotor and housing replacement. 

## 📂 Folder Structure

* **[`/edit`](./edit):** Contains the master editable `.dwg` CAD files.
* **[`/mesh`](./mesh):** Contains the `.stl` meshes ready to be imported into your slicer.
* **[`/print`](./print):** Contains pre-configured, tested `.gcode` files for specific 3D printers.

---

## 🛠️ Recommended Print Settings
To ensure the STR15 rotor can withstand high-RPM EDF forces, we recommend the following slicer profiles:

| Parameter | Recommended Setting |
| :--- | :--- |
| **Material** | Polycarbonate (PC), Carbon Fiber Nylon (PA-CF), or high-temp PETG |
| **Infill** | 100% (Solid) for the rotor / 30%+ Gyroid for the housing |
| **Wall Loops** | 4 minimum |
| **Layer Height** | 0.15mm - 0.20mm (for optimal dynamic balance) |

> ⚠️ **Safety Warning:** High-RPM EDF rotors spin at extreme speeds. Always print in high-strength materials and inspect the rotor for micro-cracks before dynamic balancing and testing.
