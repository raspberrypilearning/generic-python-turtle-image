### Endre Python Skilpadde-ikoner

I stedet for å alltid bruke en skilpadde, kan du fortelle Python Skilpadde-ikonet at det skal bruke et annet bilde. Bildet bør være lite, slik at det ikke dekker for mye av skjermen: 50 × 50 piksler gir deg et stort ikon.

+ Først må du registrere bildet med `screen`:

```python
skjerm = turtle.Screen()
skjerm.register_shape('happy.png') 
```

+ Deretter kan du sette formen med `shape`:

```python
turtle.shape('happy.png')
```

+ Skilpadde-ikoner peker til høyre til å begynne med. Du kan endre retningen for å få bildet ditt til å peke oppover:

```python
turtle.setheading (90) # vend oppover
```

Se et eksempel her: <iframe src="https://trinket.io/embed/python/5f68ef3fd7?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>