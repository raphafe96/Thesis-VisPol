# GruPol - A Suite for Predicting Optoelectronic Properties of Proteins and Molecular Crystals

**A suite of tools for biomolecular and crystal polarizability calculations**

---

## ⚠️ IMPORTANT NOTICE — GFF Module

The GFF module is an independent molecular dynamics simulation **written and maintained by a single developer - me**. This module is currently **under active development, testing, and validation**. While it appears to function very well in previous tests, **users should exercise caution** when interpreting results and report any unexpected behavior.

**This is the new graphical interface version.** The GUI has undergone significant changes from previous releases.

---

## 📥 Download & Installation

### Latest Version

The newest version of GruPol is available here:

🔗 **[Download GruPol (dist.zip)](https://github.com/raphafe96/Thesis-VisPol/blob/VisPol_new3/dist.zip)**

Extract the contents and locate the executable:
- **Executable:** `test.exe` (found in the `test` folder)

### Setup Instructions

1. Download and extract `dist.zip`
2. Navigate to the `test` folder
3. Run `test.exe`
4. **Important:** DO NOT use spaces or special characters in any folder names (neither where the executable is located nor in your working directory)
5. No installation is required - keep test.exe and _internal in the same directory.

---

## 📚 Documentation

Due to the extensive GUI changes, the previous manual has been **temporarily replaced by the developer's thesis**. The thesis contains examples of outputs and inputs (serving as the old manual) in its final sections.

📖 **Thesis & Documentation:** Available in the `.../_internal/Main_files` folder - or downloaded/accessed directly via GUI.

---

## 🧩 Modules

The GruPol suite includes the following modules:

* **GruPol** — Database containing the polarizabilities and dipole moments of the building blocks of the 20 most common amino acids, heme B, water, and Na⁺/Cl⁻ ions.
* **GFF** — Independent molecular dynamics simulation module for proteins in isolation or in an explicit solvent medium, supporting different protonation states and ion inclusion (see notice above).
* **CrysPol** — Crystal polarizability calculation module that can incorporate PolaBer results (PolaBer is third-party software also included in the distribution).

---

The main branch contains the examples.zip (test folders 1 and 2). For validation folders consult the old interface with thesis results _old_thesis_all_files.zip.

### Examples

| Folder | Description |
|--------|-------------|
| **TEST FOLDER 1** | Contains a PDB file for running GruPol (atom labels must follow CHARMM force field). Examples of modified PDB files for devmode available upon request. |
| **TEST FOLDER 2** | Contains a PolaBer output file for running CrysPol. The given CIF file provides necessary crystal symmetry information for testing. |

### Data used for validation
| **PROTEINS VALIDATION COORDINATES** | Coordinates of molecules used to benchmark GruPol. |
| **DYNAMICS COORDINATES** | Coordinates for HH and SW myoglobins, as well as Alanine oligomers obtained via molecular dynamics. |
| **TEST CHARGE COORDINATES** | Coordinates of three peptides used for testing the charged model in three different protonation states. |

---

## 📜 Citing GruPol

If GruPol proves useful in your research, please cite the following publications:

### Core GruPol Reference
- **GruPol Main:** *J. Phys. Chem. B* **2024**, 128, 33, 7954–7965

### ADIM Model
- Ligório, R. F., Dos Santos, L. H., Krawczuk, A. "Iterative Implementation of the Dipole Interaction Model for Atomic Polarizabilities." *J. Comput. Chem.*, 46, e70158, **2025**

### Ion Effects
- Ligório, R. F., Gehle, R. H. M., Dos Santos, L. H., Krawczuk, A. "Electric Charge and Salting In/Out Effects on Glucagon's Dipole Moments and Polarizabilities Using the GruPol Database." *Acta Cryst. B*, 81-2, **2025**

### Development & Validation
- Ligório, R. F., Rodrigues, J. L., Zuev, A., Dos Santos, L. H., Krawczuk, A. "Benchmarking a Dipole Moment and Distributed Polarizability Database for Biomolecules." *Phys. Chem. Chem. Phys.*, 24, 29495–29504, **2022**
- Ligório, R. F., Rodrigues, J. L., Krawczuk, A., dos Santos, L. H. R. "A Building-Block Database of Distributed Polarizabilities and Dipole Moments to Estimate Optical Properties of Biomacromolecules in Isolation or in an Explicitly Solvated Medium." *J. Comput. Chem.*, 44, 745–754, **2022**

### Crystal Polarizabilities
- Ligório, R. F., Krawczuk, A., dos Santos, L. H. R. "Accurate Atom–Dipole Interaction Model for Prediction of Electro-Optical Properties: From van der Waals Aggregates to Covalently Bonded Clusters." *J. Phys. Chem. A*, 125, 4152–4159, **2021**
- Ligório, R. F., Krawczuk, A., dos Santos, L. H. R. "Crystal Field Effects on Atomic and Functional-Group Distributed Polarizabilities of Molecular Materials." *J. Phys. Chem. A*, 124, 10008–10018, **2020**

### PolaBer (Third-Party Software)
If you use the CrysPol module with PolaBer, please also cite:
- Krawczuk A., Pérez D., Macchi P. "PolaBer: a Program to Calculate and Visualize Distributed Atomic Polarizabilities Based on Electron Density Partitioning." *J. Appl. Cryst.*, 47, 1452-1458, **2014**
- Learn more at: [https://www.polaber.eu/](https://www.polaber.eu/)

---

## 📋 Requirements

- No installation required for core GruPol functionality

---

## 📧 Contact

For further information, questions, or to report issues:

✉️ **raphafe96@gmail.com**

---

## 📝 Notes

- GruPol was developed in Göttingen, Germany (Georg-August-Universität) and Belo Horizonte, Brazil (UFMG)
- The old version remains available for compatibility with published papers
- This software is **free** and provided as-is under active development

---

*Please save GruPol's folder in a directory that contains no spaces or special characters in its name. This also applies to folders containing input files.*
