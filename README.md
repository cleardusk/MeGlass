# Face Synthesis for Eyeglass-Robust Face Recognition
[[ArXiv](https://arxiv.org/abs/1806.01196)]

## Intro
This repo releases the MeGlass dataset in original paper.
MeGlass is an eyeglass dataset originaly designed for eyeglass face recognition evaluation. All the face images are selected 
and cleaned from MegaFace. Each identity has at least two face images with eyeglass and two face images without eyeglass.
More details are presented in paper [*Face Synthesis for Eyeglass-Robust Face Recognition*](https://arxiv.org/abs/1806.01196).

|Name|Dataset type|Link|
|-|-|-|
|MeGlass_120x120.zip|Cropped|[Google Drive](https://drive.google.com/file/d/1V0c8p6MOlSFY5R-Hu9LxYZYLXd8B8j9q/view?usp=sharing) or [Baidu Yun](https://pan.baidu.com/s/1QPGi22RaNWJrV1w5wNbSkg), 335.8M|
|MeGlass_ori.zip|Origin|[Baidu Yun](https://pan.baidu.com/s/17EBZz3LkQzyn44VL45udTg), 13.3G|

## Dataset description
`meta.txt` contains the eyeglass labels of images. `1` means black-eyeglass, `0` means no-eyeglass.

`MeGlass_120x120.zip` consists of the cropped images of size 120x120.

`MeGlass_ori.zip` contains the original face images. 

`test` directory contains four lists corresponding to the four protocols in paper.

|Dataset|Identity|Images|No-eyeglass|Black-eyeglass|
|-|-|-|-|-|
|MeGlass|1,710|47,917|14,832|33,085|
|Testing set|1,710|6,840|3,420|3,420|

### Samples
<p align="center">
    <img src="samples/samples.jpg", width="800px">
</p>

### Dataset usages
To build this dataset, we use eyeglass classifier, powerful face recognition model and manual labor to keep right the person identity and black eyeglass attribute.
Therefore, MeGlass dataset can be used for face recognition (identification and verification), eyeglass detection, removal, generation tasks and so on.


## Identity parsing rule
Take one filename `10032527@N08_identity_4@2897031059_1.jpg` for example, the string before the second `@` makes one face image's identity.
The naming rule is corresponding to the original MegaFace dataset.

## Acknowledgement
The 3D face model fitting is based on [Xiangyu Zhu](http://www.cbsr.ia.ac.cn/users/xiangyuzhu/)'s work.

## Citation
If your research benefits from MeGlass, please cite it.
