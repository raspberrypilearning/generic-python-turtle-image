### Pythonのタートルのアイコンを変更する

いつも使っているタートル(かめ)の代わりに、Pythonのタートルのアイコンに違う画像を使うように指示することができます。 画像は小さくして、画面を覆い尽くさないようにする必要があります。50×50ピクセルで大きなアイコンが表示されます。

+ 最初に `screen` を使って画像を登録する必要があります：

```python
screen = turtle.Screen()
screen.register_shape('happy.png') 
```

+ 次に `shape`を設定することができます：

```python
turtle.shape('happy.png')
```

+ タートルのアイコンは最初、右を向いています。 向きを変更して、画像を上向きにすることができます：

```python
turtle.setheading(90) # 顔を上向きに
```

以下の例を参照してください。 
<iframe src="https://trinket.io/embed/python/6a36ff88db?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>