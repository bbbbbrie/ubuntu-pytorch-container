# xenial-pytorch-container

## About
This is a Singularity recipe for a super cool container that is based on Ubuntu 16.04 and contains tools like:

  * Jupyter
  * Numpy and Scipy
  * Pandas
  * Python3
  * PyTorch

This container also collects all of the requirements for the PyTorch examples. 

## Construction
Build the container with something like ```singularity build pytorch-friends.img Singularity``` or use the included helper script called ```build```

## Invocation
Run ```singularity shell --nv pytorch-friends.img```
