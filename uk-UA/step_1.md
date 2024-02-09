### Зміна іконок Python Turtle

Замість того, щоб завжди використовувати зображення черепахи, ти можеш встановити щось інше як іконку Python Turtle. Зображення має бути невеликим, щоб не закривати надто велику частину екрану: 50 × 50 пікселів дасть тобі досить велику іконку.

+ Перш за все, необхідно зареєструвати зображення в `screen`:

```python
screen = turtle.Screen()
screen.register_shape('happy.png') 
```

+ Тоді ти зможеш встановити його через `shape`:

```python
turtle.shape('happy.png')
```

+ Спочатку іконка Turtle повернута вправо. Ти можеш змінити напрямок (heading), щоб направити зображення вгору:

```python
turtle.setheading(90) # повернути вгору
```

Ось приклад: <iframe src="https://trinket.io/embed/python/5f68ef3fd7?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>