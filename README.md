js代码使用方法：    
1.安装篡改猴扩展（我使用的是pc端谷歌浏览器）    
2.添加两份脚本，分别把上面两份代码复制进去  
3.可能因为会检测是否为当前活动页面，需要一直挂在屏幕上。这份代码的作用只是用于自动播放视频，完成后点击下一个链接。  

py代码使用方法：  
1.打开开发者工具，然后开始播放视频  
2.找到service.php?开头的请求，将请求头的cookie、sesskey以及载荷的fsresourceid复制下来。  
3.将复制好的信息填入代码中对应位置。注释有标注。  
4.调用doIt函数  
不保证是安全的
