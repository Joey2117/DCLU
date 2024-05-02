# DCLU---Demo
Chaoyi Li, Meng Li, Can Peng, Brian C. Lovell, "Dynamic Curriculum Learning via In-Domain Uncertainty for Medical Image Classification", MICCAI 2023 [[paper]](https://link.springer.com/chapter/10.1007/978-3-031-43904-9_72)

![image](./DCLU_framework.png)

In this repository, we provide the demo of DCLU to reproduce the experiments on CIFAR10 in the supplementary material.

## Requirements
```
pip install -r requirements.txt
```

## Results
### CIFAR 10

|**Method**|Vanilla*|SPL*|SPCL*|FCL*|Adaptive CL*|Ours(exp)|Ours(full)|
|----------|-------|---|----|---|-----------|---------|----------|
|**Accuracy**|$78.09(± 0.083)$|$77.95 (± 0.078)$|$76.48 (± 0.182)$|$78.51 (± 0.106)$|$79.74 (± 0.074)$|$81.16 (± 0.553)$|$81.58(± 0.064)$|
