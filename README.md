#关于setBar
平常班里经常会有一些截图打卡活动，所以写了一个脚本，这个脚本可以把你自己的手机截图的状态栏和其他截图合起来成为一张可用的截图
#setBar怎么用？
setBar是一个小脚本，在setBar.py里写了一个函数：
change_statusBar(base , yourself , out)
这个函数接受三个字符串参数,base是别人的截图文件名，yoursel是你自己的截图文件名，out是输出图片文件名
###下载代码：
#####直接点击下载setBar.py或者将代码到处黏贴
#####git@github.com:maoyuqing/setBar.git 就可以将脚本整个clone到本地啦（linux用户）
#####pip install setBar 就可以在你的python脚本里调用这个函数了：from setBar import change_statusBar 

###举个例子：
到群里找个截图a.jpg过来，放在脚本同文件夹内，找一张自己手机的截图mypicture.jpg过来，放在脚本同文件夹内，生成out.jpg   :
change_statusBar('a.jpg' , 'mypicture.jpg' , 'out.jpg')
#关于setBar
本脚本兼容python2/3 ， 对于手机分辨率720p , 或者1080p ， 或者都不是的截图，均有良好的兼容性