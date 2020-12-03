# Game_Engine_5
工程文件和可执行文件都在master branch，其中可执行文件在built文件夹里

没有添加遮挡剔除时的性能数据如下：  

![image](https://github.com/ixianren/Game_Engine_5/blob/master/1.png)

添加遮挡剔除后的性能如下:

![image](https://github.com/ixianren/Game_Engine_5/blob/master/%E5%89%94%E9%99%A4%E5%90%8E.png)

可见batches从81降到了62，且渲染的vertices减少了

经过调参后，发现参数设置为smallest occluder=5,smallest hole=0.25时，occlusion data数据最小为17.2KB

![image](https://github.com/ixianren/Game_Engine_5/blob/master/17.3.png)
