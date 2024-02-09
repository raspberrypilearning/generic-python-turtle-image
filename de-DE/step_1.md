### Python Turtle Icons ändern

Anstatt immer eine Schildkröte zu verwenden, kannst du das Python Turtle-Symbol anweisen, ein anderes Bild zu verwenden. Das Bild sollte klein sein, damit es nicht zu viel vom Bildschirm verdeckt: 50 × 50 Pixel ergeben ein großes Symbol.

+ Zuerst musst du das Bild mit dem Bildschirm `screen` registrieren:

```python
screen = turtle.Screen()
screen.register_shape('happy.png') 
```

+ Dann kannst du die Form (`shape`) festlegen:

```python
turtle.shape('happy.png')
```

+ Turtle-Symbole zeigen zu Beginn nach rechts. Du kannst die Ausrichtung ändern, damit dein Bild nach oben zeigt:

```python
turtle.setheading(90) #zeige nach oben
```

Sehe Dir hier ein Beispiel an: <iframe src="https://trinket.io/embed/python/5f68ef3fd7?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>