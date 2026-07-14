# 💾 STR15 Machine-Ready Print Files (`/print`)

This folder contains tested, pre-configured machine G-code (`.gcode` / `.gcode.gz`) and slicer project files (`.3mf`) optimized for specific 3D printers.

## 📂 Active Profiles

*   `/prusa-Core One+/` - G-code tuned for Prusa Core One+ (optimized for PC-CF / Polycarbonate Carbon Fiber).
*   `/bambu-lab-p1s/` - Bambu Studio project files (`.3mf`) with dialed-in speed, cooling, and retraction settings.

## ⚠️ Important Calibration Notes

*   **Z-Offset:** Ensure your first-layer calibration is flawless. Any warping at the base of the rotor or housing will cause catastrophic rubbing during high-speed spinning.
*   **Scale Calibration:** Ensure your printer's X/Y step calibration is highly accurate so the press-fit motor shaft sleeve fits securely without slipping.
