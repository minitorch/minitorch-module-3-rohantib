# MiniTorch Module 3

<img src="https://minitorch.github.io/minitorch.svg" width="50%">

* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module3.html


You will need to modify `tensor_functions.py` slightly in this assignment.

* Tests:

```
python run_tests.py
```

* Note:

Several of the tests for this assignment will only run if you are on a GPU machine and will not
run on github's test infrastructure. Please follow the instructions to setup up a colab machine
to run these tests.

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/tensor_data.py minitorch/tensor_functions.py minitorch/tensor_ops.py minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/module.py project/run_manual.py project/run_scalar.py project/run_tensor.py

### CPU - map, zip, reduce parallelized and JIT
NOTE: Times are recorded after a startup run to compile the functions, locally as opposed to colab

Simple dataset, 50 points \
Size of hidden layer: 2, Time per epoch: 0.074 \
Size of hidden layer: 10, Time per epoch: 0.079 \
Size of hidden layer: 15, Time per epoch: 0.080

XOR dataset, 75 points \
Size of hidden layer: 15, Time per epoch: 0.112 \
Size of hidden layer: 30, Time per epoch: 0.133

Spiral dataset, 75 points \
Size of hidden layer: 50, Time per epoch: 0.183 \
Size of hidden layer: 100, Time per epoch: 0.380 \
