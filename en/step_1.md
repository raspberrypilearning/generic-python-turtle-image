### Changing Python Turtle icons

Instead of always using a turtle, you can tell the Python Turtle icon to use a different image. The image should be small, so that it does not cover up too much of the screen: 50 × 50 pixels will give you a large icon. 

+ First you need to register the image with the `screen`:

```python
screen = turtle.Screen()
screen.register_shape('happy.png') 
```

+ Then you can set the `shape`:

```python
turtle.shape('happy.png')
```

+ Turtle icons face right to start with. You can change the heading to get your image to face upwards:

```python
turtle.setheading(90) # face upwards
```

See an example here:
<iframe src="https://trinket.io/embed/python/5f68ef3fd7?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

