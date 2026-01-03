# QST-Assignment-1
A single-qubit quantum state tomography pipeline built from scratch using Python.

## Overview
This repository contains a full implementation of Single Qubit Tomography. The project simulates quantum measurements, generates noisy data, and reconstructs density matrices using Linear Inversion.

## Contents
* **Assignment_1.ipynb:** The main Jupyter Notebook containing all code for simulation, reconstruction, and validation.
* **qst_data/:** Folder containing the generated .npy datasets.
* **validation_plot.png:** Visualization of the reconstructed density matrices.
* **requirements.txt:** Python dependencies required to run the code.

## Results
* **Fidelity:** Achieved F=1.0 for eigenstates and F~0.87 for random states.
* **Method:** Pauli Projective Measurements + Linear Inversion.
