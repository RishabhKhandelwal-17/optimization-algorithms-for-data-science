# Optimization Algorithms for Data Science   

## Torch implementation of Projected Gradient Descent and Frank-Wolfe algorithm for Optimization

This is a repository containing code for the Design Project - OPTIMIZATION ALGORITHMS FOR DATA SCIENCE, made by **RISHABH KHANDELWAL** under the supervision of Prof. Sravan Danda.   

Contained in the [optimizers](https://github.com/RishabhKhandelwal-17/optimization-algorithms-for-data-science/tree/main/optimizers) folder are 5 files.      

[pgd_optimizer.py](https://github.com/RishabhKhandelwal-17/optimization-algorithms-for-data-science/blob/main/optimizers/pgd_optimizer.py) and [frankwolfe_optimizer.py](https://github.com/RishabhKhandelwal-17/optimization-algorithms-for-data-science/blob/main/optimizers/frankwolfe_optimizer.py) are the Optimizer Classes for the two algorithms (Projected Gradient Descent and Frank-Wolfe Algorithm). These two classes have been designed taking inspiration from the [SGD class](https://github.com/pytorch/pytorch/blob/main/torch/optim/sgd.py) which already exists in the [torch library](https://pytorch.org/docs/stable/index.html). The code in our classes is written to mirror the structure and functionality of the SGD class as closely as possible.    

[optimizer.py](https://github.com/RishabhKhandelwal-17/optimization-algorithms-for-data-science/blob/main/optimizers/optimizer.py) is a base class for all optimizers. It serves as a Light-weight stand-in for [torch.optim.optimizer](https://github.com/pytorch/pytorch/blob/main/torch/optim/optimizer.py), and only the symbols required by pgd_optimizer.py and frankwolfe_optimizer.py are implemented.  

[pgd_unit_tests.py](https://github.com/RishabhKhandelwal-17/optimization-algorithms-for-data-science/blob/main/optimizers/pgd_unit_tests.py) and [fw_unit_tests.py](https://github.com/RishabhKhandelwal-17/optimization-algorithms-for-data-science/blob/main/optimizers/fw_unit_tests.py) contain the tests to check working and functionality of both modules that we have designed.   

To run these, simply download the whole Optimizers directory and run the two unit test files within it. 
