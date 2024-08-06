- 👋 Hi, I’m @ShenZi-Ast
- 👀 I’m interested in Machine Learning & Chemistry
- 🌱 I’m currently learning Python-R
- 💞️ Collaborate Data science
- 📫 : Sinaastian@Gmail.com  

<!---
ShenZi-Ast/ShenZi-Ast is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

#Compound DFT Calculation with PubChem and PySCF
This repository contains a Python script for calculating the Density Functional Theory (DFT) energy of chemical compounds using PubChem data and the PySCF library. The script retrieves 3D coordinates of a compound from PubChem and performs DFT calculations on it.

Overview
Retrieve Compound Data: Fetches the Chemical ID (CID) of a compound from PubChem using its common name.
Fetch 3D Coordinates: Obtains 3D conformer coordinates from PubChem using the CID.
Perform DFT Calculation: Uses the PySCF library to compute the DFT energy of the compound based on the retrieved coordinates.
Requirements
Python 3.x
requests library for HTTP requests
pyscf library for quantum chemistry calculations
