### 如何改变 Python Turtle 图标

除了一直使用海龟（turtle）的图像之外，你可以让 Python Turtle icon 使用一个不一样的形象。 图片应该要小，所以才不会占据太多屏幕空间：50x50 像素会是一个很大的图像。

+ 首先你需要通过使用 `screen` 注册你要用的图片:

```python
screen = turtle.Screen()
screen.register_shape('happy.png') 
```

+ 然后你需要设置形状 `shape`:

```python
turtle.shape('happy.png')
```

+ Turtle（海龟）默认情况面向右边： 你可以改变它的朝向来让图像朝上

```python
turtle.setheading(90) # 朝上
```

举例来说： <iframe src="https://trinket.io/embed/python/5f68ef3fd7?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>