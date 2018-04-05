你可以设置图片来用于 Python 海龟。 

海龟图片尺寸较小，50 x 50 像素会得到一张大幅的海龟图片。 

首先你需要在画面上注册图片。 

```python
screen = turtle.Screen()
screen.register_shape('happy.png') 
```

然后你可以设置形状：

```python
turtle.shape('happy.png')
```

海龟在开始时面朝右侧。你可以更改朝向，以使你的图片朝北：

```python
turtle.setheading(90) # face north
```

示例：
<iframe src="https://trinket.io/embed/python/5f68ef3fd7?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

