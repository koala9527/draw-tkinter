# draw-tkinter
tkinter 抽奖程序，九宫格，粽子选择器抽奖

Python3自带Tkinter

需要安装
pillow
pyinstaller


打包教程：
```
pyinstaller -F -w app.py
```
-F ：生成单文件  
-w ：不使用命令行启动  

需要手动把静态文件夹`imgs`复制到编译完成后的`dist`文件夹下，与`app.exe`同级，才能正确启动

![11.gif](https://qn.tuwei.space/github%2F11.gif)
![1.png](https://qn.tuwei.space/github%2F1.png)
