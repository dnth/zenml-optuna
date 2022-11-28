# zenml-optuna

A primitive example of how to use ZenML for Hyperparameter Tuning with Optuna.

The pipeline consist of 3 steps:
* Load the FashionMNIST data.
* Optimize hyperparameter with Optuna.
* Train a evaluate a model with the best hyperparameters.

Vizualization of the pipeline

![pipeline](./pipeline_viz.png)

## Get Started

Run 

`pip install zenml[server] optuna`

Run the `pytorch_hpo_fmnist.ipynb`.

