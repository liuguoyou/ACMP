# ACMP
## About
This repository contains the code for the paper [Planar Prior Assisted PatchMatch Multi-View Stereo](https://arxiv.org/abs/1912.11744), Qingshan Xu and Wenbing Tao, AAAI2020. If you find this project useful for your research, please cite:  
```
@article{Xu2020ACMP,  
  title={Planar Prior Assisted PatchMatch Multi-View Stereo}, 
  author={Xu, Qingshan and Tao, Wenbing}, 
  journal={AAAI Conference on Artificial Intelligence (AAAI)},
  year={2020}
}
@article{Xu2019ACMM,  
  title={Multi-Scale Geometric Consistency Guided Multi-View Stereo}, 
  author={Xu, Qingshan and Tao, Wenbing}, 
  journal={Computer Vision and Pattern Recognition (CVPR)},
  year={2019}
}
```
## Dependencies
* [Cuda](https://developer.nvidia.com/zh-cn/cuda-downloads) >= 6.0
* [OpenCV](https://opencv.org/) >= 2.4
* [cmake](https://cmake.org/)
## Usage
* Complie ACMP
```  
cmake .  
make
```
* Test 
``` 
Use script colmap2mvsnet_acm.py to convert COLMAP SfM result to ACMP input   
Run ./ACMP $data_folder to get reconstruction results
```
## Acknowledgemets
This code largely benefits from the following repositories: [Gipuma](https://github.com/kysucix/gipuma) and [COLMAP](https://colmap.github.io/). Thanks to their authors for opening source of their excellent works.

