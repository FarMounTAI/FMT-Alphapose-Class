# FMT-Alphapose-class
hongyaohongyao大佬的智慧教室  
https://github.com/hongyaohongyao/smart_classroom_demo  
让我第一次接触到深度学习  
但是这两年hongyao大佬并没有对这个项目进行过更新，而且新版Alphapose的性能也有所提升，40系显卡也开始上市售卖。并不能满足现阶段的使用需求  
所以基于最新版Alphapose的课堂行为检测工具——FMT-Alphapose-class诞生了  
Alphapose 项目地址https://github.com/MVIG-SJTU/AlphaPose  
由于在刚开始学习的时候吃尽了苦头，所以我为广大想使用该项目的初学者提供保姆级环境配置方案，免去长时间配置的烦恼，后续会提供简单的图形用户界面，适配希沃、鸿合、创维的高分辨率屏幕，方便喜欢计算机的老师们使用。

推荐使用Miniconda  
官网https://docs.conda.io/en/latest/miniconda.html  
完整版Anaconda https://www.anaconda.com/  
清华镜像https://repo.anaconda.com/archive/  

默认使用halpe136_fast_res50_256x192.pth数据集  
https://github.com/Fang-Haoshu/Halpe-FullBody  
更多数据集  
https://github.com/MVIG-SJTU/AlphaPose/blob/master/docs/MODEL_ZOO.md

请将文件放置到C盘的根目录，以便操作，如果想要改到其他位置，可手动更改脚本中的地址

警告：  
如果使用英伟达GPU进行运行实时监测，由于CUDAtoolkit的缘故，请确保有15G以上的存储空间。如果进行视频图片的导入，请确保您的GPU至少有6G的独立显存  
CPU运行会很慢，非常慢，没有英伟达独立显卡的用户请确保您的CPU有足够的的算力（第十代移动版酷睿i7勉强能跑起来，锐龙没有试过），并且拥有至少8GB的运行内存

关于如何使用，请转至官方文档  
https://github.com/MVIG-SJTU/AlphaPose/blob/master/docs/GETTING_STARTED.md  


## 🔗 Onedrive
https://jixuaa-my.sharepoint.com/:f:/g/personal/farmountai_jixuaa_onmicrosoft_com/Ekc7MtyLpNNAtOSEgceCAWsBzA1KGqOs4jMnYwU8KKrvXw?e=rat8Mc  
下载里面的文件夹，并将内部的文件放置到Alphapose-master下




## 参考项目
https://github.com/cs-giung/face-detection-pytorch  
https://github.com/MVIG-SJTU/AlphaPose  
https://github.com/yinguobing/head-pose-estimation
