You can set the image to use for a Python turtle. 

Turtle images should be small, 50 x 50 pixels will give a large turtle image. 

First you need to register the image with the screen. 

```python
screen = turtle.Screen()
screen.register_shape('happy.png') 
```

Then you can set the shape:

```python
turtle.shape('happy.png')
```

Turtles face right to start with. You can change the heading to get your image to face north:

```python
turtle.setheading(90) # face north
```

Example:
<iframe src="https://trinket.io/embed/python/5f68ef3fd7?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

