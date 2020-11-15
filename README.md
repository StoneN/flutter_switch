# flutter_Switch
一个滑动开关UI
效果预览
 ![image-w100](https://github.com/Luy7788/flutter_switch/blob/main/preview/icon1.png)

点击右滑动动画，同时下面的PageView页面也跟着画的
 ![image](https://github.com/Luy7788/flutter_switch/blob/main/preview/2020-11-1612.15.53.gif)
 
使用方法
```
SwitchButton(
    width: 120, //宽度
    height: 44, //高度
    controller: mPageController, //下面的PageView的controller
    tabs: ['推荐', '热门'], 
    selectColor: Colors.white,
    unSelectColor: Colors.grey[300],
  ),
```
