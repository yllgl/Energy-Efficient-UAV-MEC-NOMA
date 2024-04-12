---

# Energy-Efficient Multi-UAV-Enabled MEC with NOMA

This repository contains the Python implementation of an optimization algorithm for energy-efficient multi-UAV-enabled multiaccess edge computing (MEC), incorporating NOMA (Non-Orthogonal Multiple Access). The algorithm optimizes the positioning and resource allocation of UAVs (Unmanned Aerial Vehicles) and ground users to improve the energy efficiency of the system.

## Prerequisites

Before you run this project, make sure you have the following installed:
- Python 3.8 or newer
- pip (Python package installer)
- numpy
- cvxpy
- matplotlib

## Installation

Clone the repository and install the required Python packages using pip:

```bash
git clone https://github.com/your-username/NOMA-MEC-with-Multi-UAV.git
cd NOMA-MEC-with-Multi-UAV
pip install numpy,cvxpy,matplotlib
```

## Usage

To use this notebook:

1. Ensure you have Jupyter Notebook or JupyterLab installed. If not, you can install it using pip:
    ```bash
    pip install notebook
    ```

2. Start Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

3. Navigate to the `main.ipynb` file in the directory where you cloned the repo.

4. Open `main.ipynb` by clicking on it.

5. Run the cells sequentially by pressing `Shift + Enter` on each cell or using the "Run All" feature in the toolbar.

This will execute the optimization algorithm and should plot the results within the notebook environment, illustrating the positions of UAVs and ground users as optimized by the algorithm.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.

## Acknowledgments

- Thanks to the authors of the CVXPY library for providing a powerful tool for convex optimization.
- Gratitude to the community members who have contributed suggestions and improvements.

---
