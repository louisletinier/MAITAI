# MAI TAI

### Code samples for the MAI TAI study.
The code provided in this repository is derived from the code used in the study. As, for data privacy and confidential medical information reasons, we can not publish the dataset we simplified the part of the code related to data processing. This code is provided for didactic purposes and is not supposed to run properly as is. It can be seen as an illustration of the methods used for the MAI TAI study and a starting point for people who would like to conduct similar studies. 

## Install
```bash
pip install -r requirements.txt
```
If your can run computations on a GPU, consider using the GPU compatible version of tensorflow (tensorflow-gpu).

## Run Jupyter lab
```bash
jupyter lab
```

## Notebooks description:
* training-pipeline.ipynb: basic training pipeline example for classical models.
* lstm-pipeline.ipynb: training pipeline example for LSTM model.
* bootstrap-pipeline.ipynb: pipeline for evaluation metrics confidence intervals estimation through bootstrap simulations method.
* bootstrap-analysis.ipynb: code for bootstrap simulations output analysis (CI computation, curves...)