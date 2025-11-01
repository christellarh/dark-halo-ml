# Dark Halo ML: N-body Simulation & Machine Learning Analysis

## Project Overview
This project simulates the formation of dark matter halos using an N-body gravitational simulation and analyzes their density profiles and structural properties with machine learning techniques.

---

## 1. Requirements & Setup
### Install Python (recommended: Python 3.9+)
- Download from: https://www.python.org/downloads/

### Install Required Libraries:
You will need (minimum):
- numpy
- scipy
- matplotlib
- scikit-learn

For optional deep learning:
- torch (PyTorch) or tensorflow

**Install everything:**
```bash
pip install numpy scipy matplotlib scikit-learn torch
```

---

## 2. Project Structure
- `simulation/` — N-body simulation code and scripts
- `analysis/` — Density and structural analysis scripts
- `ml/` — Machine learning scripts (feature extraction, model training, etc.)
- `notebooks/` — For interactive exploration and visualization
- `requirements.txt` — List of dependencies
- `README.md` — Project information

---

## 3. Major Tasks / Milestones
1. **Set up project structure and environment**
2. **Develop the N-body simulation code**
    - Choose integration method (e.g., leapfrog, Runge-Kutta)
    - Set initial conditions (random, Plummer, etc.)
    - Implement gravitational force calculation
    - Run and visualize test simulations
3. **Analyze simulation outputs**
    - Compute density and structural profiles of halos
    - Save data for later use
    - Visualize results using plots
4. **Build dataset for ML**
    - Extract features and structural properties
    - Optionally label types or properties of halos
5. **Apply Machine Learning**
    - Clustering (find typical halo types)
    - Regression/prediction (e.g., predict density profile parameters)
    - Classification (optional)
6. **Visualize and interpret results**
7. **Document process and findings**

---

## 4. References & Resources
- [Python documentation](https://docs.python.org/3/)
- [NumPy User Guide](https://numpy.org/doc/stable/user/)
- [Astrophysical N-body Simulations](https://ui.adsabs.harvard.edu/abs/2012NewA...17..682D/abstract)
- [Machine Learning in Astronomy - Review](https://arxiv.org/abs/1904.07362)
