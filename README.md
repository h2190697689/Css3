# CSS 只展示自己不熟悉的

## box-shadow
- box-shadow: 水平阴影位置(必需)  垂直阴影位置(必需)  模糊距离  阴影的大小  阴影的颜色  inset(内侧阴影)

## background-position  (背景图片位置)
- left top(只指定一个关键字，其他值将是center)
- x% y% (只指定一个值,其他值将是50%)
- 10px 10px   仅指定了一个值，其他值将是50％。你可以混合使用％和positions

## background-origin (指定背景图片的位置区域)
- border-box   
- padding-box
- content-box

## background-clip  (指定背景颜色的绘制区域)
- border-box   
- padding-box
- content-box

## linear-gradient 
- to left ,color1 ,color2
- to right bottom  ,color1 ,color2
- 90deg  ,color1 ,color2

# 3d转换

## transform
- rotateX
- rotateY

## transform-origin
- transform-origin: x-axis y-axis z-axis;
- x-axis 视图被置于X轴的何处    left,center,right,length,%
- y-axis 视图被置于Y轴的何处    top,center,bottom,length,%
- z-axis 视图被置于Z轴的何处    length

## perspective 设置从何处查看一个元素的角度
- num 数值

## perspective-origin  查看3D元素的基数位置
- x-axis 视图被置于X轴的何处    left,center,right,length,%
- y-axis 视图被置于Y轴的何处    top,center,bottom,length,%

## transition   过渡效果
- transition-property	规定应用过渡的 CSS 属性的名称  none,all,property
- transition-duration	定义过渡效果花费的时间。默认是 0
- transition-timing-function	过渡效果的时间曲线,默认是 "ease"   linear,ease,ease-in,ease-out,ease-in-out
- transition-delay	规定过渡效果何时开始。默认是 0

## animation  动画
- @keyframes  规定动画
- animation-name   规定 @keyframes 动画的名称
- animation-duration    动画完成的周期
- animation-timing-function   过渡曲线  ease,linear,ease-in,ease-out,ease-in-out   
- animation-delay   动画延时
- animation-iteration-count   动画被播放次数，默认1  , num(数值), infinite
- animation-direction   规定动画是否在下一周期逆向播放,   normal,reverse,alternate,alternate-reverse
- animation-fill-mode   规定动画不播放时，应用到元素的样式, forwards,backwards,both
- animation-play-state  规定动画是否正在运行或暂停，默认running,paused



