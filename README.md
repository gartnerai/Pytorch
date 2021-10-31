# Pytorch
Testing Cuda Pytorch, add books and run few examples

# Installation

Create environement with conda, check python version (python --version)
```
conda create -n pytorchenv pip scikit-learn jupyter pandas python==3.7
```

Activate virtual environment

```
source activate pytorchenv
```

Install ipykernel 
```
conda install ipykernel
```

Create jupyter kernel

```
python -m ipykernel install --user --name pytorchenv --display-name "Python (myenv)"
```
Now that we have our custom kernel created, we can add all the packages we need =)

## Pytorch

Before installing pytorch we must check the cuda version installed. We can do so by (nvcc --version)

The suitable command to install pytorch could be found here https://pytorch.org/get-started/locally/
In my case with a Cuda version 9.1 the command is the following

```
conda install -n pytorchenv pytorch torchvision cudatoolkit=9.0 -c pytorch
```

-n pytorchenv refers the environement in which we install the packages. We can avoid this instruction if we are inside the conda environment. 


### Book

Deep Learning with Pytorch

```
