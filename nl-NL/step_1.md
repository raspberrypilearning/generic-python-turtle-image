### Python Turtle Pictogrammen wijzigen

In plaats van altijd een turtle (schildpad) te gebruiken, kun je het Python Turtle pictogram vertellen om een ​​andere afbeelding te gebruiken. De afbeelding moet klein zijn, zodat deze niet te veel van het scherm bedekt: 50 × 50 pixels geeft je een groot pictogram.

+ Eerst moet je de afbeelding registreren met het `screen`:

```python
screen = turtle.Screen()
screen.register_shape('happy.png') 
```

+ Dan kun je de `shape`(vorm) bepalen:

```python
turtle.shape('happy.png')
```

+ Schildpad-iconen kijken bij het begin naar rechts. Je kunt de richting wijzigen om je afbeelding naar boven te te laten kijken:

```python
turtle.setheading(90) #Kijk omhoog
```

Bekijk hier een voorbeeld: 

<iframe src="https://trinket.io/embed/python/b99ba71a48?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>