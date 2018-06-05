## Intro
MeGlass is an eyeglass dataset for eyeglass face recognition evaluation. All the face images are selected and cleaned from MegaFace.

|Name|Dataset type|Link|
|-|-|-|
|MeGlass_120x120.zip|Cropped|[Google Drive](https://drive.google.com/file/d/1V0c8p6MOlSFY5R-Hu9LxYZYLXd8B8j9q/view?usp=sharing) or [Baidu Yun](https://pan.baidu.com/s/1QPGi22RaNWJrV1w5wNbSkg), 335.8M|
|MeGlass_ori.zip|Origin|[Baidu Yun](https://pan.baidu.com/s/17EBZz3LkQzyn44VL45udTg), 13.3G|

## Dataset description
`meta.txt` contains the eyeglass labels of images. `1` means black-eyeglass, `0` means no-eyeglass.

`MeGlass_120x120.zip` consists of the cropped images of size 120x120.

`MeGlass_ori.zip` contains the original face images. 

`test` directory contains four lists corresponding to the four protocols in paper.

|Dataset|Identity|Images|No-glass|Black-glass|
|-|-|-|-|-|
|MeGlass|1,710|47,917|14,832|33,085|
|Testing set|1,710|6,840|3,420|3,420|

## Identity parsing rule
Take one filename `10032527@N08_identity_4@2897031059_1.jpg` for example, the string before the second `@` makes one face image's identity.
The naming rule is corresponding to the original MegaFace dataset.

## Acknowledgement
The 3D face model fitting is based on [Xiangyu Zhu](http://www.cbsr.ia.ac.cn/users/xiangyuzhu/)'s work.

## Future Plans
More 3D face related works will be published.
