### Schimbarea pictogramelor Turtle în Python

În loc să folosești întotdeauna o broască țestoasă, poți schimba pictograma Turtle în Python într-o altă imagine. Imaginea ar trebui să fie mică, astfel încât să nu acopere prea mult ecran: 50 × 50 pixeli îți va oferi o pictogramă mare.

+ Mai întâi trebuie să înregistrezi imaginea cu `ecranul`:

```python
ecran = turtle.Screen()
ecran.register_shape('happy.png') 
```

+ Apoi, poți seta `forma`:

```python
turtle.shape('happy.png')
```

+ Pictogramele țestoaselor încep orientate spre dreapta. Poți schimba poziția pentru a obține imaginea cu fața în sus:

```python
turtle.setheading(90) # cu fața în sus
```

Vezi un exemplu aici: <iframe src="https://trinket.io/embed/python/5f68ef3fd7?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>