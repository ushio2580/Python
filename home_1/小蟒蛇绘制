#绘制一条Python小蟒蛇
import turtle  #turtle是用于绘制图像的库

def drawSnake(rad,angle,len,neckrad):
    for i in range(len):
        turtle.circle(rad,angle) #rad描述圆形轨迹半径的位置
        turtle.circle(-rad,angle)#angle表示小乌龟沿着圆形爬行的弧度值，rad为负值，半径在小乌龟运行的右侧
    turtle.circle(rad,angle/2)
    turtle.fd(rad)#表示小乌龟沿着直线爬行移动，它有一个参数表示爬行的距离
    turtle.circle(neckrad+1,180)
    turtle,fd(rad*2/3)

def main():
    turtle.setup(1300,800,0,0) #长 宽  起始点
    pythonsize=30  #小乌龟运行轨迹的宽度
    turtle.pensize(pythonsize)
    turtle.pencolor("blue") #轨迹的颜色
    turtle.seth(-40)#小乌龟的运行方向
    drawSnake(40,80,5,pythonsize/2)

main()
