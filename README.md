# ZenML + Optuna + PyTorch

A primitive example of how to use ZenML for Hyperparameter Tuning with [Optuna](https://github.com/optuna/optuna) and PyTorch.

The pipeline consist of 3 steps:
* Load the FashionMNIST data.
* Optimize hyperparameter with Optuna.
* Train and evaluate a model with the best hyperparameters.

Vizualization of the pipeline on the local ZenML Dashboard:

![pipeline](./pipeline_viz.png)

## Get Started
 
`pip install zenml[server] optuna optuna-dashboard plotly`

Run the `pytorch_hpo_fmnist.ipynb` in Colab [here](https://colab.research.google.com/github/dnth/zenml-optuna/blob/master/pytorch_hpo_fmnist.ipynb).

To view the Optuna dashboard run `optuna-dashboard sqlite:///zenml-optuna.db`

Here are some plots that you will see on the dashboard

Optimization History
![pipeline](./history.png)

Parallel Coordinate Plot
![pipeline](./parallel.png)

Slice Plot
![pipeline](./slice.png)

Hyperparameter Importance
![pipeline](./importance.png)

Empirical Distribution
![pipeline](./edf.png)