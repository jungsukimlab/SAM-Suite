# S.A.M. - Spatial Analysis from Masks

[![S.A.M. Hero Preview](https://github.com/jungsukimlab/SAM-Suite/blob/main/SAM_Hero_Image.gif?raw=true)](https://jungsukimlab.github.io/SAM-Suite/SAM_Hero_Image.gif)

This is an interactive hero image created with HTML Canvas. **Click the image above to see the live version.**

# S.A.M. - Spatial Analysis from Masks
A suite of tools designed to streamline common image analysis tasks in scientific research.

[![DOI: 10.5281/zenodo.15851666](https://img.shields.io/badge/DOI-10.5281/zenodo.15851666-blue.svg)](https://doi.org/10.5281/zenodo.15851666)
[![Latest Release](https://img.shields.io/github/v/release/jungsukimlab/SAM-Suite?label=Latest%20Release&color=brightgreen)](https://github.com/jungsukimlab/SAM-Suite/releases)
[![Issues](https://img.shields.io/github/issues/jungsukimlab/SAM-Suite)](https://github.com/jungsukimlab/SAM-Suite/issues)
[![License: MIT](https://img.shields.io/badge/Docs%20License-MIT-purple.svg)](https://github.com/jungsukimlab/SAM-Suite/blob/main/LICENSE)

---

## ⏬ Downloads
You can download the latest compiled, ready-to-use versions of all applications for macOS and Windows from the **[Releases Page](https://github.com/jungsukimlab/SAM-Suite/releases)**.

---

## 🔬 Live Simulation
Gain intuition about the biological meaning of a key readout from the SAM tool.
* **[Interactive Ripley's L-Function Simulation](https://jungsukimlab.github.io/SAM-Suite/ripley-simulation.html)**: A tool to visualize how different glial spatial patterns (clustering, random dispersion, inhibition) produce unique `L(d) - d` curves.

---

## 🛠️ Tools Included
This suite currently includes the following tools, divided into preprocessing and analysis workflows.

### Preprocessing Tools
* **Mask Accuracy Verifier:** Analyzes masks of predicted signal against raw images to flag potentially inaccurate segmentations based on intensity ratios and coverage.
* **File Renamer:** A powerful batch-renaming tool to clean up filenames by removing specified parts or adding prefixes/suffixes.
* **ROI Extractor:** Extracts embedded ImageJ ROIs from `.tif` files and saves them as separate `.zip` files.

### Analysis Tools
* **SAM:** Interrogates colocalization, spatial organization, and spatial expanse of objects around amyloid-beta plaques.
* **Stats Tool:** Using columns in an Excel file, this tool identifies outliers using ROUT (Q=1%), determines normality, runs the correct statistical tests, calculates effect sizes, and optionally generates graphs.

---

## 📖 How to Cite
If you use these tools in your research, please cite them as:
> Walsh, SP. (2025). SAM - Spatial Analysis from Masks (Version 1.0) [Computer software]. https://doi.org/10.5281/zenodo.15851666

---

## 🐛 Bug Reports & Feature Requests
If you encounter a bug or have an idea for a new feature, please **[open a new issue](https://github.com/jungsukimlab/SAM-Suite/issues)**. We appreciate the feedback!

---

## ⚖️ License
The documentation in this repository is available under the **MIT License**.

**Please Note:** The S.A.M. software applications themselves are distributed under a separate, more restrictive license that is included in the download packages.
