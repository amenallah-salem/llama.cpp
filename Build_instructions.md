# Linux

```bash 
$ nvidia-smi

+-----------------------------------------------------------------------------------------+
| NVIDIA-SMI 550.107.02             Driver Version: 550.107.02     CUDA Version: 12.4     |
|-----------------------------------------+------------------------+----------------------+
|   0  NVIDIA GeForce MX330
+-----------------------------------------------------------------------------------------+

```


```nvcc --version ```

```bash 
nvcc: NVIDIA (R) Cuda compiler driver
Copyright (c) 2005-2021 NVIDIA Corporation
Built on Thu_Nov_18_09:45:30_PST_2021
Cuda compilation tools, release 11.5, V11.5.119
Build cuda_11.5.r11.5/compiler.30672275_0
```



```export BUILD_TAG=llamacpp_30oct2024_amen```

```export CUDA_DOCKER_ARCH=compute_75```

```make clean && GGML_CUDA=1 make -j``` add build tag and build forlder 