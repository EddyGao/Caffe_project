此处代码来自http://blog.csdn.net/10km/article/details/68926498博主，对此表示感谢！！！
faster rcnn 的demo.py运行时，对于同一个图像，每个类别显示一个窗口，看起来不太方便，顺便小改一下，让一幅图像中检测到的所有类别物体都在一个窗口下标注，就方便多了。 代码改动也不复杂，就是把vis_detections函数中for循环前后三行代码移动到demo函数的for循环前后。
