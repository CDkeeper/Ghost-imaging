# Ghost-imaging
最近一直在做鬼成像（单像素成像）方面的科研工作，发现这方面的代码很多是不开源的，这就导致了极大的不方便，于是打算自己编写一下这方面的代码。  
可以供人参考，同时也会不断的完善这方面的工作，目前还是一个最简单版本。  
  
目前需要改动的地方目前就4处：
1.第4行设定源图片路径  
2.第5行设置灰度图或彩图  
3.第7行设定成像帧数，也就是多少张图片，这和鬼成像的采样率有关，也即 帧数/像素值为采样率  
4.第36行设定图片导出路径

注意：代码编写环境为pycharm环境，使用了pytorch框架。
11
