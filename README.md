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

“*” denotes results reported by Kong, Y., Liu, L., Wang, J., & Tao, D. (2021). Adaptive curriculum learning. In Proceedings of the IEEE/CVF International Conference on Computer Vision (pp. 5067-5076).

## Citation
Cite as below if you find this repository is helpful to your project.
```sh
@inproceedings{li2023dynamic,
  title={Dynamic Curriculum Learning via In-Domain Uncertainty for Medical Image Classification},
  author={Li, Chaoyi and Li, Meng and Peng, Can and Lovell, Brian C},
  booktitle={International Conference on Medical Image Computing and Computer-Assisted Intervention},
  pages={747--757},
  year={2023},
  organization={Springer}
}
```
## Acknowledgement
* Many thanks to the amazing work [Evidential Deep Learning to Quantify Classification Uncertainty](https://github.com/muratsensoy/muratsensoy.github.io/blob/master/uncertainty.ipynb)
