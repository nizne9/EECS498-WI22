# Assignments for EECS 498.008 / 598.008: Deep Learning for Computer Vision Winter 2022
The completed assignments from the "Deep Learning for Computer Vision" course offered by the University of Michigan in the Winter of 2022.

Please note that the solutions provided are **unofficial**.

All code that needs to be edited has been formatted using `ruff`.

## A1

## A2

## A3

### Q1

* It will take some time to implement the `FullyConnectedNet` class.
* Don't forget to update the `config["t"]` when you implement `adam` optimizer.

### Q2

* If you find the implementation of `Conv` and `MaxPool` challenging, please don't worry too much about efficiency; simply use straightforward loops.
* When working on `DeepConvNet`, take it one step at a time and proceed with caution.
* Implement `create_convolutional_solver_instance` may be a bit challenging; take your time, and avoid striving for an excessive number of layers. You can refer to the parameter settings of VGGNet for guidance.
* [The essay](https://arxiv.org/abs/1502.03167) can be quite helpful when implementing the `BatchNorm` class.
* The gradients of biases in "Convolutional nets with batch normalization" may appear unusual; however, there's no need to be concerned about it.

## A4

### Q1

* The repo [mAP](https://github.com/Cartucho/mAP) used in this homework may have [some issues](https://github.com/Cartucho/mAP/issues/170) due to [a deprecated API](https://matplotlib.org/stable/api/prev_api_changes/api_changes_3.4.0.html#backend-deprecations) in Matplotlib since version 3.4.0. You may need to either modify the code yourself or install a version of Matplotlib older than 3.4.0 to resolve the problem.
* The `nms` (Non-Maximum Suppression) function in `common.py` could be implemented in a clearer way, but I'm too lazy to do it.:)
