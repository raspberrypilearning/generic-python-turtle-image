### Alterando os ícones da Tartaruga Python

Em vez de estar sempre a usar uma tartaruga, podes dizer ao ícone da Tartaruga Python para usar uma imagem diferente. A imagem deve ser pequena, para que não cubra muito o ecrã: 50 × 50 pixels resulta na criação de um ícone grande.

+ Primeiro precisas registar a imagem no `ecrã`:

```python
screen = turtle.Screen()
screen.register_shape('happy.png') 
```

+ Então podes definir a `forma`:

```python
turtle.shape('happy.png')
```

+ No início os ícones da tartaruga estão voltados para a direita. Podes alterar o cabeçalho para fazer com que a tua imagem fique virada para cima:

```python
turtle.setheading(90) # face para cima
```

Vê um exemplo aqui: <iframe src="https://trinket.io/embed/python/5f68ef3fd7?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>