canvas-Test
===========
###drawing.js
封装的一个简单基础画图库，用了单例方法实现，把1000*1000的屏幕所有像素点存在了一个二维数组中
###getPointArrayMy.js
自己写的返回流程图中间拐点的一个算法
###canvas.html,主要用到drawing.js和getPointArrayMy.js
一个canvas绘制流程图的测试，主要测试直角拐点的生成问题，后续可能还会涉及智能躲避障碍。
###clock.js
使用canvas画的一个时钟