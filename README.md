Example code of using  `DataParallel` in PyTorch for debugging issue [31045](https://github.com/pytorch/pytorch/issues/31045):

After upgrading to CUDA 10.2 (10.2, V10.2.89), and nccl-2.5.6-1 (PyTorch 1.3.1), I have the following error when using `DataParallel`:

```
terminate called after throwing an instance of 'std::runtime_error'
  what():  NCCL Error 4: invalid argument
Aborted (core dumped)
```



**Solved in version 1.4 (`python-pytorch-cuda-1.4.0-4`)**

