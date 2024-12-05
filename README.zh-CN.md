# 这是一个基于Yolov8与Yolov10部分算法个人瞎改的模型。

## yolov5700
实现了n规模下的： 

metrics/precision(B): 0.676	metrics/recall(B): 0.538	metrics/mAP50(B): 0.588 metrics/mAP50-95(B):0.427 

3420928 parameters,  3420912 gradients,   11.0 GFLOPs


## yolov5701
实现了n规模下的： 

metrics/precision(B): 0.688	metrics/recall(B): 0.539	metrics/mAP50(B): 0.592 metrics/mAP50-95(B):0.431 

624 layers,  3422016 parameters,  3422000 gradients,   11.2 GFLOPs

## yolov5703
实现了n规模下的： 

metrics/precision(B): 0.677	metrics/recall(B): 0.527	metrics/mAP50(B): 0.582 metrics/mAP50-95(B):0.421 

452 layers,  3302432 parameters,  3302416 gradients,   10.4 GFLOPs

该模型在pytorch里的推理速度，在我的测试环境下，逼近了yolov8n的速度。 
 
该模型被微软的Defender报毒？什么鬼？


## 由于个人精力和设备有限，其它的都搞不定...
ps: yolov5700的数据及训练结果是我从时间线里拉出来的，不保证完全找对了=。=
ps: pytorch里"yolov5700"、"yolov5701"的耗时好像没有优势？其它的环境我也没测过...

[百度云盘：yolov5700](https://pan.baidu.com/s/1wck-qsTw6zN33_96SYL-EQ?pwd=58qu)

[百度云盘：yolov5701](https://pan.baidu.com/s/1rxhNzdUMfetnCuJPEss9_A?pwd=i4tb)