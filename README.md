### Intro
MeGlass is an eyeglass dataset for eyeglass face recognition evaluation. ALl the face images are selected and cleaned from MegaFace.

|Name|Dataset Type|Link|
|-|-|-|
|MeGlass_120x120.zip|120x120 Cropped|[Google Drive](https://drive.google.com/open?id=1T15qNvU5FHg3Xte_aOTFSwP66_x6gfxZ) or [Baidu Yun](https://pan.baidu.com/s/1QPGi22RaNWJrV1w5wNbSkg), 335.8M|
|MeGlass_ori.zip|Origin|[Baidu Yun](), 13.3G|

### Dataset description
`meta.txt` contains the glass labels of images. `1` means black-eyeglass, `0` means no-eyeglass.

`MeGlass_120x120.zip` consists of the cropped images of size 120x120.

`MeGlass_ori.zip` contains the original face images. 

`test` directory contains four lists corresponding to the four protocols in paper.


### Identity parsing rule
Take one filename `10032527@N08_identity_4@2897031059_1.jpg` for example, the string before the second `@` makes one face image's identity.
The naming rule is corresponding to the original MegaFace dataset.
