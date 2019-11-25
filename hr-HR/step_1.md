### Promjena Python Turtle ikona

Umjesto da uvijek koristiš kornjaču, možeš reći Pythonovoj Turtle grafici da upotrijebi neku drugu sliku. Slika bi trebala biti mala, tako da ne pokriva previše zaslona: 50 × 50 piksela će ti dati veliku ikonu.

+ Prvo moraš registrirati sliku s metodom `screen`:

```python
screen = turtle.Screen()
screen.register_shape('happy.png') 
```

+ Zatim možeš postaviti `oblik`:

```python
turtle.shape('happy.png')
```

+ Kornjače na početku gledaju nadesno. Možeš promijeniti smjer (heading) tako da tvoja slika gleda prema gore:

```python
turtle.setheading(90) # gleda prema gore
```

Pogledaj primjer: 

<iframe src="https://trinket.io/embed/python/5f68ef3fd7?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>
