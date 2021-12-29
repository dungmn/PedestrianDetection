# Pedestrian Detection Using Cross-modal
This source is re-implement the method proposed at [1]
slide: https://docs.google.com/presentation/d/1v1x1WHEYEU-ur9tLXsy23WQpsJCwTpGqUgWnGCwLnT4/edit#slide=id.g44ff61ff99_2_69
## System requirement
* Python: 3.6.8
* Pytorch: 1.1.0
* MatLab: R2014b
* Cuda: 8.0

## Addittional Sources
* Toolbox ACF[2] using to extract region proposal: [toolbox](https://github.com/pdollar/toolbox)
* Pretrained modal MSDN: [link](https://drive.google.com/file/d/1XHjmr1JzHueCwP0TG8r6tiWyzwjF7npY/view?usp=sharing)

## Install 
* Intsall pytorch: ```conda install pytorch torchvision cudatoolkit=9.0 -c pytorch```
* Install necessary libraries: ``` pip install -r requirements.txt```

## Citation
[1]. Dan Xu, Wanli Ouyang, Elisa Ricci, Xiaogang Wang, Nicu Sebe.Learning Cross-Modal Deep Representations for Robust Pedestrian Detection. InCVPR, 2017.

[2]. S.Belongie P. Dollár R. Appel and P. Perona.Fast feature pyramids for objectdetection. InTPAMI, 2014.
