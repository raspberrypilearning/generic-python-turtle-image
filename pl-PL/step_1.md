### Zmiana ikon żółwia Pythona

Zamiast zawsze używać żółwia, możesz powiedzieć ikonie żółwia Pythona, żeby użyć innego obrazka. Obraz powinien być mały, tak aby nie zasłaniał on zbyt dużej części ekranu: 50 × 50 pikseli daje dużą ikonę.

+ Najpierw musisz zarejestrować obrazek na `ekranie`:

```python
screen = turtle.Screen()
screen.register_shape('happy.png') 
```

+ Następnie możesz ustawić `kształt`:

```python
turtle.shape("happy.png")
```

+ Ikony żółwia są początkowo skierowane w prawo. Możesz zmienić nagłówek, aby obrazek był skierowany w górę:

```python
turtle.setheading(90) # twarzą do góry
```

Zobacz przykład tutaj: <iframe src="https://trinket.io/embed/python/5f68ef3fd7?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>