# IFEM: Finite Element Method for Beam and Truss Elements

## Overview
The **IFEM** project provides a collection of **MATLAB scripts** implementing the **Finite Element Method (FEM)** for analyzing **beam and truss structures**. These scripts serve as an educational tool, helping users understand and apply FEM principles in structural engineering.

## Features
- **Beam Element Analysis**: Compute **deflections, rotations, bending moments, and shear forces** in beam structures under various loading conditions.
- **Truss Element Analysis**: Determine **axial forces, displacements, and reactions** in truss systems subjected to different loads.
- **Modular Code Structure**: Easily adapt and extend the code for **various structural analysis scenarios**.

## Requirements
- **MATLAB**: Ensure MATLAB is installed to run the scripts effectively.

## Getting Started
### 1. Clone the Repository
```bash
git clone https://github.com/ashvar97/IFEM.git
```

### 2. Navigate to the Directory
```bash
cd IFEM/src
```

### 3. Run the Scripts
- **Open MATLAB**
- **Navigate to the `src` directory**
- **Execute the desired script**:
  ```matlab
  run('beam_analysis.m')
  ```

## Repository Structure
```
📂 IFEM
 ├── 📂 src
 │    ├── beam_analysis.m      # Script for beam element analysis
 │    ├── truss_analysis.m     # Script for truss element analysis
 │    └── utils/
 │         ├── fem_solver.m    # Core FEM solver functions
 │         └── plot_results.m  # Functions for visualizing results
 ├── README.md                 # Project documentation
 ├── LICENSE                    # Licensing information
 └── .gitignore                  # Ignored files in version control
```

## Usage
### Beam Analysis
- **Define material properties, geometry, and loading conditions** in `beam_analysis.m`.
- **Run the script** to compute and visualize results.

### Truss Analysis
- **Specify node coordinates, connectivity, material properties, and loads** in `truss_analysis.m`.
- **Execute the script** to analyze truss behavior and display results.

## Contributing
Contributions are welcome! If you would like to improve the project:
- **Fork the repository**
- **Make enhancements**
- **Submit a pull request**

For major changes, please open an **issue** to discuss your ideas first.

## License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

**Author**: Ashwin Varkey  
**Contact**: [ashvar97@gmail.com](mailto:ashvar97@gmail.com) | [LinkedIn](https://www.linkedin.com/in/ashvar97/)

*Note: This project is intended for educational purposes and may require further validation for professional engineering applications.*
