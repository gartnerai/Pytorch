# Pytorch
Testing Cuda Pytorch and run few examples

Create pytorchenv

virtualenv pytorchenv

Activate virtual environment

source pytorchenv/bin/activate

Before installing pytorch we must check the cuda version installed. We can do so by

nvcc --version

The suitable command to install pytorch could be found here https://pytorch.org/get-started/locally/
In my case with a Cuda version 9.1 the command is the following

Install pytorch   

pip3 install torch torchvision
