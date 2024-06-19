# Tutorial for Workshop on Classical and Quantum Machine Learning for Condensed Matter Physics 2024

## Overview
This tutorial will teach you how to use Qiskit to implement quantum computations in the XX chain model. It will also guide you on using neural networks and supervised learning to predict phase transitions in spin systems and the SSH model using PyTorch.

## Installation
Before starting the first calculation, please install one of the following platforms to run Jupyter Notebook or Jupyter Lab: 

Follow these instructions: 
1. Download Anaconda from <https://www.anaconda.com/download> 
2. Download Miniconda from <https://docs.conda.io/en/latest/miniconda.html> and install the required packages
3. Download Visual Studio Code from <https://code.visualstudio.com/download>, then install Jupyter using the Extensions tab.

To avoid some package dependencies with Python 3.11 on certain systems, create a virtual environment as follows:

```
conda create -n qml-cmp python=3.9
conda activate qml-cmp
```

Install Qiskit with the following command:
```
pip install qiskit qiskit-ibm-runtime qiskit[visualization] qiskit-aer
```

Install ML packages with the following commands:
```
conda install pytorch torchvision torchaudio cpuonly -c pytorch
conda install matplotlib scipy
pip install scikit-learn
 
```
If you face resource issues on your PC or laptop, you can use [Google Colab](https://colab.research.google.com/) as an alternative. On Google Colab, you only need to install the Qiskit package as the ML packages are pre-installed. 

If you happen to encounter any issues with this tutorial, please do not hesitate to contact me at [muha207(at)brin.go.id]().

I look forward to seeing you at the tutorial :D

M. Y. Hanna
