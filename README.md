# PiML Toolbox

PiML (Python Interpretable Machine Learning) is a new Python toolbox for IML model development and validation. Through low-code automation and high-code programming, PiML supports various machine learning models in the following two categories:

- **Inherently interpretable models**: 
  1. EBM: Explainable Boosting Machine (Nori, et al. 2019; Lou, et al. 2013)
  2. GAMI-Net: Generalized Additive Model with Struatured Interactions (Yang, Zhang and Sudjianto, 2021)
  3. ReLU-DNN: Deep ReLU Networks using Aletheia Unwrapper (Sudjianto, et al. 2020)

- **Arbitrary black-box models**，e.g.
  1. LightGBM or XGBoost of varying depth
  2. RandomForest of varying depth
  3. Residual Deep Neural Networks

## Installation 

```python
!pip install wget
import wget
url = "https://github.com/SelfExplainML/PiML-Toolbox/releases/download/V0.1.0/PiML-0.1.0-cp37-cp37m-linux_x86_64.whl"
wget.download(url, 'PiML-0.1.0-cp37-cp37m-linux_x86_64.whl')
!pip install PiML-0.1.0-cp37-cp37m-linux_x86_64.whl
```
