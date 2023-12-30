# GW_SegFormer

## 相关仓库
模型***********|路径
UNet| https://github.com/bubbliiiing/unet-pytorch
PSPNet | https://github.com/bubbliiiing/pspnet-pytorch
DeepLabv3+ | https://github.com/bubbliiiing/deeplabv3-plus-pytorch
HRNetV2 | https://github.com/bubbliiiing/hrnet-pytorch
SegFormer | https://github.com/bubbliiiing/segformer-pytorch

### 所需环境
torch==1.2.0

###文件下载
训练所需的权值可在百度网盘中下载
链接；https://pan.baidu.com/s/1plRC47TYTLp-G3pwR1mU-A
提取码：zfkd

引力波时频数据集百度网盘如下：
链接：https://pan.baidu.com/s/1NoHVJ4usLWLFnTf5O8GYLg
提取码：zfkk

引力波真实事件时频图如下：
链接：https://pan.baidu.com/s/1pQJF7l0EAa77vmlF3v4R7Q
提取码：zfkl

###训练步骤
1、将提供的引力波时频数据集放在VOCdevkit文件夹下
2、在train.py中设置对应参数，并修改backbone和model_path。
3、运行train.py 进行训练。

###预测步骤
下载权值，或使用自己训练好的权值，放入model_data,修改segformer.py的backbone和model_path之后再运行predict.py可完成预测。
