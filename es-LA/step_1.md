### Cambiar los íconos de Python Tortuga

En lugar de usar siempre una tortuga, puedes indicarle al ícono de Python Tortuga que use una imagen diferente. La imagen debe ser pequeña, de modo que no cubra demasiado de la pantalla: 50 × 50 píxeles te darán un ícono grande.

+ Primero necesitas registrar la imagen en la pantalla `(screen)`:

```python
turtlescreen = turtle.Screen ()
screen.register_shape('happy.png') #cara sonriente 
```

+ Luego puedes definir la `forma (shape)`:

```python
turtle.shape('happy.png')
```

+ Los íconos de la tortuga miran hacia a la derecha para empezar. Puedes cambiar el encabezado para que tu imagen mire hacia arriba:

```python
turtle.setheading(90) # mirar hacia arriba
```

Aquí tienes un ejemplo: 
<iframe src="https://trinket.io/embed/python/02f47312b3?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>