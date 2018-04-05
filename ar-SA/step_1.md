يمكنك تعيين الصورة التي تريد استخدامها لسلحفاة Python. 

يجب أن تكون صور السلحفاة صغيرة، فاستخدام 50 × 50 بكسل سيعطينا صورة سلحفاة كبيرة. 

ستحتاج أولًا إلى تسجيل الصورة باستخدام screen. 

python```
screen = turtle.Screen()
screen.register_shape('happy.png') 
```

ثم يمكنك تعيين الشكل:

python```
turtle.shape('happy.png')
```

يكون اتجاه صور السلحفاة نحو اليمين عندما تبدأ. لكن يمكنك تغيير قيمة heading ليكون اتجاه الصورة إلى أعلى:

python```
turtle.setheading(90) # face north
```

مثال:
<iframe src="https://trinket.io/embed/python/5f68ef3fd7?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

