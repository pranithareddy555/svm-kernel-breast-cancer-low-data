# Low-Data Breast Cancer Classification (SVM)

This project trains SVM classifiers on limited training data (5% and 10%) and compares kernels:
- Polynomial kernel (poly)
- RBF kernel (rbf)

## Files
- `SVM-p5.py`  : polynomial kernel, 5% training
- `SVM-p10.py` : polynomial kernel, 10% training
- `SVM-e5.py`  : RBF kernel, 5% training
- `SVM-e10.py` : RBF kernel, 10% training
- `documentation_project3.pdf` : results summary

## Results (Accuracy)
- Poly 5%  : 0.9561
- Poly 10% : 0.9596
- RBF 5%   : 0.9332
- RBF 10%  : 0.9473

## Setup
```bash
pip install -r requirements.txt
