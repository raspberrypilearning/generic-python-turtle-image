### Modifier les icônes de Python Turtle

Au lieu de toujours utiliser une tortue, tu peux indiquer à l'icône Python Turtle d'utiliser une image différente. L'image doit être petite pour ne pas trop recouvrir l'écran : 50 × 50 pixels te donnera une grande icône.

+ Tu dois d'abord enregistrer l'image avec la fonction `ecran` :

```python
ecran = turtle.Screen()
ecran.register_shape('happy.png') 
```

+ Ensuite, tu peux définir la `forme` :

```python
turtle.shape('happy.png')
```

+ Les icônes Turtle sont en face pour commencer. Tu peux changer le titre pour que ton image soit orientée vers le haut :

```python
turtle.setheading(90) # faire face vers le haut
```

Voir un exemple ici : 

<iframe src="https://trinket.io/embed/python/79c0501385?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>
