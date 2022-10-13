# RootSIFT

## Background
为了更好的了解目前AOI系统，提高自身代码能力，选择RootSIFT方法进行初步开发，并尝试在现有基础上进行功能的完善。
待解决问题：在物件有无的基础上判断物件个数
## Install
所需环境： 
numpy==1.21.6
opencv-python==4.6.0.66

## Usage
RootSIFT.py包含了大部分业务逻辑方法，无需单独执行。其中的__init__()可以使其他程序在导入模块时很轻松的访问帮助程序。
main.py为主程序，想要得到“特征匹配”的结果只需要执行main.py即可。

## Change Log

## Planning
增加保存“特征信息”的功能，多次使用同一图片时无需重复构建模型，直接导入即可。
