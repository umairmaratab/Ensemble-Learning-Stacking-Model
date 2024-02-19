# Ensemble-Learning-Stacking-Model using scikit-learn
This project combine several machine learning models into a single and robust meta-classifier via model stacking (also known as stacking model).

## Project setup:
* Clone this repo.
* Create a virtual environment using `conda` or `pyhton3 venv` i.e `python3 -m venv venv`.
* Install dependencies with: `pip install -r requirements.txt`
* Open the `.ipynb` file in `jupyterlab` or use `vscode` jupyterlab extension.
* Execute the each cell where everything is explained in the markdown.

## Strcuture

## Models used
* K nearent Neighbors
* SVM
* Decision Tree Classifier
* Random Forest
* MLP Classifier

## Stacked Model
All of the model are stacked and their evaluation is exported into the `results.csv` file.

Results looks like this:

- 'knn': 0.9375976715114386,
- 'svm_rbf': 0.9876028806587153,
- 'dt': 1.0,
- 'rf': 1.0,
- 'mlp': 0.9754065040827025,
- 'stack': 0.9876028806587153
