# CAD Source Files – Starship Project

This folder contains the **SolidWorks source files** for the Starship project
completed in AME 5193: Intro to Computer-Aided Design.

## Contents
- `Ship_Assembly.SLDASM` – full starship assembly
- `Saucer.SLDPRT` – saucer/command section
- `Engineering.SLDPRT` – engineering hull
- `Nacelle.SLDPRT` – propulsion nacelle
- Additional small parts that support the final build

## Usage
These files can be opened in **SolidWorks 2024** (or later) to view, modify, or
inspect the model. Subsystems are organized as separate part files and are fully
referenced in the main assembly.

## Notes
- These files are large binary formats and are best tracked with **Git LFS**
  (Large File Storage).  
- If you don’t have SolidWorks, check the [`exports/`](../exports/) folder for
neutral formats:
  - `.step` for use in other CAD tools
  - `.stl` for lightweight viewing or 3D printing

---

📌 *This project was originally completed as part of a team assignment. The CAD
content shown here reflects the components and assemblies I created and refined
personally.*
