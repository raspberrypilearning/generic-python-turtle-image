### Python Turtle simgelerini değiştirme

Her zaman bir turtle kullanmak yerine, Python Turtle simgesine farklı bir görüntü kullanmasını söyleyebilirsiniz. Görüntünün küçük olması gerekir, böylece ekranda fazla yer kaplamaz: 50 × 50 piksel size büyük bir simge verecektir.

+ Öncelikle, görüntüyü `screen` komutuyla kaydetmeniz gerekir:

```python
screen = turtle.Screen()
screen.register_shape('mutlu.png') 
```

+ Sonra `şeklini` ayarlayabilirsiniz:

```python
turtle.shape('mutlu.png')
```

+ Turtle simgeleri başlamak için sağa bakarlar. Resminizin yukarı bakmasını sağlamak için başlığı değiştirebilirsiniz:

```python
turtle.setheading(90) # yüzü yukarı doğru
```

Burada bir örneğe bakın: 

<iframe src="https://trinket.io/embed/python/2845a10a68?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>
