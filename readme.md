win8-icon-click 
========
win8 metro 界面的图标点击动画效果
------------
###2014-10-31
仿着win8 metro 界面的图标点击动画效果<br/>
html方面 .content 的div 必须 
.content{
    position: absolute;
    box-sizing: border-box;
    -webkit-perspective: 320;
  }<br/>
  里层的div 有个-webkit-transform-style: preserve-3d;<br/>
  css3动画效果用到了 -webkit-transform: rotateY(0deg);<br/>
  和 -webkit-transform: scale<br/>
  其他就是JS加了个addClass removeClass 和时间格式化<br/>