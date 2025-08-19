This custom option is to build the [NVIDIA Linux open GPU kernel modules](https://github.com/NVIDIA/open-gpu-kernel-modules) for the [NVIDIA RTX PRO 6000 Blackwell Workstation Edition GPU](https://www.nvidia.com/en-us/products/workstations/professional-desktop-gpus/rtx-pro-6000/). As of August 18, 2025, Conda's [TensorFlow](https://www.tensorflow.org/) 2.18.0 package did not support this new GPU's [compute capability](https://developer.nvidia.com/cuda-gpus) 12. See [this repository](https://github.com/HuidaeCho/tensorflow-rtx-50-series) to build TensorFlow 2.20.0 with support for compute capability 12.

[NVIDIA Transitions Fully Towards Open-Source GPU Kernel Modules](https://developer.nvidia.com/blog/nvidia-transitions-fully-towards-open-source-gpu-kernel-modules/)
> For cutting-edge platforms such as NVIDIA Grace Hopper or NVIDIA Blackwell, you must use the open-source GPU kernel modules. The proprietary drivers are unsupported on these platforms.
>
> For newer GPUs from the Turing, Ampere, Ada Lovelace, or Hopper architectures, NVIDIA recommends switching to the open-source GPU kernel modules.
>
> For older GPUs from the Maxwell, Pascal, or Volta architectures, the open-source GPU kernel modules are not compatible with your platform. Continue to use the NVIDIA proprietary driver.
>
> For mixed deployments with older and newer GPUs in the same system, continue to use the proprietary driver.
