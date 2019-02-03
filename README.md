# Bikesharing Prediction Project

* [Description](#description)
* [Dependencies](#dependencies)
* [Installation](#installation)
* [Contributing](#contributing)

## Description

The goal of this project is to implement a neural network to predict bike sharing. Basic neural network concepts such as feedforward and backpropagation are implemented from scratch with raw `numpy`.

Bike sharing systems are new generation of traditional bike rentals where whole process from membership, rental and return back has become automatic. Through these systems, user is able to easily rent a bike from a particular position and return back at another position. Currently, there are about over 500 bike-sharing programs around the world which is composed of over 500 thousands bicycles. Today, there exists great interest in these systems due to their important role in traffic, environmental and health issues.

The data comes from the [UCI Machine Learning Database](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset).

## Dependencies

You need Python 3, Anaconda, and Jupyter to run this project locally.

## Installation

Create a new conda environment:

```shell
conda create --name bikesharing python=3
```

Enter your new environment:

* Mac/Linux:

```shell
source activate bikesharing
```

* Windows:

```shell
activate bikesharing
```

Ensure you have `numpy`, `matplotlib`, `pandas`, and `jupyter notebook` installed:

```shell
conda install numpy matplotlib pandas jupyter notebook
```

Run the notebook server:

```shell
jupyter notebook
```

In your browser, open `Predicting_bike_sharing_data.ipynb`.

## Contributing

I appreciate contributions. For guidelines please check [CONTRIBUTING.md](CONTRIBUTING.md).
