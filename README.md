# -
使用voc2007数据集，地址http://host.robots.ox.ac.uk/pascal/VOC/voc2007/VOCtrainval_06-Nov-2007.tar

# 数据集详解

├── Annotations 标签文件，xml格式
├── ImageSets 存放数据集的分割文件
├── JPEGImages 图片文件，jpg格式
├── SegmentationClass 存放按照class类别分割的图片
└── SegmentationObject 存放按照object目标分割的图片
-----------------------------------------------------------------------------------------------------------------------
VOCdevkit
    └── VOC2012
         ├── Annotations               所有的图像标注信息(XML文件)
         ├── ImageSets    
         │   ├── Action                人的行为动作图像信息
         │   ├── Layout                人的各个部位图像信息
         │   │
         │   ├── Main                  目标检测分类图像信息
         │   │     ├── train.txt       训练集(5717)
         │   │     ├── val.txt         验证集(5823)
         │   │     └── trainval.txt    训练集+验证集(11540)
         │   │
         │   └── Segmentation          目标分割图像信息
         │         ├── train.txt       训练集(1464)
         │         ├── val.txt         验证集(1449)
         │         └── trainval.txt    训练集+验证集(2913)
         │ 
         ├── JPEGImages                所有图像文件
         ├── SegmentationClass         语义分割png图（基于类别）
         └── SegmentationObject        实例分割png图（基于目标）
