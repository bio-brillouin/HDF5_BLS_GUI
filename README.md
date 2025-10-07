# HDF5_BLS_GUI

The HDF5_BLS_GUI is a graphical user interface (GUI) for the HDF5_BLS library. It allows users to interact with the HDF5_BLS library through a graphical interface, making it easier to:
- Create and manage HDF5 files with the HDF5_BLS convention
- Read and write data to HDF5 files
- Visualize data in HDF5 files
- Perform various operations on HDF5 files, among which:
  - Reorganizing data inside an HDF5 files
  - Exporting lines of code to access data in HDF5 files
  - Applying analysis on raw data in HDF5 files to obtain a doublet of Power Spectral Density (PSD) and Frequency array
  - Applying treatment on the doublet of PSD and Frequency array to extract Brillouin-relevant information (shift, line width, etc.)

## Installation

The package is under development but executables will be available soon.

If you want to test the package, you can run the following commands:

```bash
git clone https://github.com/bio-brillouin/HDF5_BLS_GUI.git
cd HDF5_BLS_GUI
pip install -e .
```

This will install the package in editable mode, allowing you to make changes to the code and see the effects immediately. You can then run the GUI by executing the following command:

```bash
python src/main.py
```

## Usage

To use the HDF5_BLS_GUI, you need to have the HDF5_BLS library installed.