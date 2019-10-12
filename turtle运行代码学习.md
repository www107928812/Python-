# 用turtle在屏幕上绘制图形
## turtle运行代码大全
- jupyter不好运行turtle 复制到Python界面运行
```
import turtle
#或者 from turtle import *  
```
```
turtle.pensize(4)
#括号中填需要笔的宽度width  
```
```
turtle.pendown()
turtle.penup()
turtle.pendown()
turtle.forward(50)
turtle.backward(100)
```
```
turtle.right(60)
#括号中填需要转的角度angle
```
```
turtle.left(105)
turtle.goto(1,10)
#括号中填坐标 
```
```
turtle.setx(2)

#改变x坐标值 sety同理  
```
```
turtle.sety(5)
turtle.setheading(180)
#使角度发生变化到某值  
```
```
turtle.home()
#回到坐标原点
```
```
turtle.circle(2,60,steps=3)
#第一个参数是半径r 第二个参数是角度extent控制画圆的哪一部分 第三个参数是画一个此圆的多边形step（3/4/5.....）  
```
```
turtle.dot(4,blue)
#1：直径diameter 2:color  
```
```
turtle.undo()
#撤销上一步  
```
```
turtle.speed(5)
#设置速度1到10  
```
```
turtle.color("blue")
turtle.fillcolor("blue")
#选择填充色  
```
```
turtle.begin_fill()
#开始填充  
```
```
turtle.filling()
#判断是否涂色  
```
```
turtle.end_fill()
#结束填充  
```
```
turtle.clear()
turtle.reset()
#清空轨迹  
```
```
turtle.screensize(10,5)
#设置画布的大小（width，height）  
```
```
turtle.hideturtle()
#隐藏turtle  
```
```
turtle.showturtle()
#显示turtle  
```
```
turtle.isbisible()
#返回可见的turtle  
```
```
turtle.write("我爱你",font=("Arial",8,"normal"))
#1：需要写的字符串 2：font字体 括号里依次是 字体名字，字体大小，字体类型    
```
```
turtle.done()
```
- 结束
