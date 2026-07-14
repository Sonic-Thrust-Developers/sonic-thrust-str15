# 🌐 STR15 3D Printable Meshes (`/mesh`)

This folder contains the ready-to-slice 3D mesh files (`.stl` / `.obj` / `.3mf`) exported from our master AutoCAD models.

## 📂 File Inventory

*   `str15_rotor_v1.stl` - High-RPM balanced rotor mesh.
*   `str15_housing_v1.stl` - Outer stator housing mesh.

## 🖨️ Slicer Instructions

To prepare these files for 3D printing:
*   **Orientation:** 
    *   Rotor: Print flat on its base (hub down) with supports enabled for the overhanging blades.
    *   Housing: Print vertically (intake lip down) for clean stator vane geometry.
*   **Resolution:** Print at `0.15mm` layer height or finer. Rough layers will create aerodynamic turbulence and ruin the dynamic balance of the rotor.
