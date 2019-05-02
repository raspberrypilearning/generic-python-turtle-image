### Alterando os ícones da tartaruga do Python

Em vez de usar sempre uma tartaruga, podemos dizer ao ícone de tartaruga do Python para usar uma imagem diferente. A imagem deve ser pequena, para que não cubra muito a tela: 50 × 50 pixels lhe dará um grande ícone.

+ Primeiro é preciso registrar a imagem na `tela`:

```python
screen = turtle.Screen() 
screen.register_shape('happy.png') 
```

+ Em seguida podemos definir o `formato (shape)`:

```python
turtle.shape('happy.png')
```

+ Os ícones da tartaruga irão começar virados para a direita. Podemos alterar o cabeçalho para que a imagem fique voltada para cima:

```python
turtle.setheading(90) # Apontar para cima
```

Veja um exemplo aqui: <iframe src="https://trinket.io/embed/python/5f68ef3fd7?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>