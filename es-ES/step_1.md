### Cambiar el icono de la tortuga de Python

En lugar de usar siempre una tortuga, puedes decirle a Python que use una imagen diferente para el icono de Python Turtle. La imagen debe ser pequeña para que no ocupe demasiado de la pantalla: 50 × 50 píxels te dará un icono grande.

+ Primero necesitas registrar la imagen en la pantalla `(screen)`:

```python
screen = turtle.Screen ()
screen.register_shape('happy.png') #cara sonriente 
```

+ Luego puedes definir la `forma (shape)`:

```python
turtle.shape('happy.png')
```

+ Al principio, los iconos de tortuga miran hacia la derecha. Puedes cambiar el encabezado para que tu imagen mire hacia arriba:

```python
turtle.setheading(90) # mirando hacia arriba
```

Aquí tienes un ejemplo: 

<iframe src="https://trinket.io/embed/python/5f68ef3fd7?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>
