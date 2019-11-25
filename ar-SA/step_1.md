### تغيير أيقونات سلحفاة الـ(Python)

بدلاً من استخدام أيقونة السلحفاة بشكل دائمًا، يمكنك أن تخبر الـ Python بإستخدام صورة مختلفة. يجب أن تكون الصورة صغيرة، بحيث لا تغطي الكثير من مساحة الشاشة: 50×50 بكسل ستعطيك أيقونة كبيرة الحجم.

+ تحتاج أولاً إلى تسجيل الصورة باستخدام `screen`:

```python
screen = turtle.Screen()
screen.register_shape('happy.png') 
```

+ ثم يمكنك ضبط `الشكل(shape)`:

```python
turtle.shape('happy.png')
```

+ يكون اتجاه وجه ايقونة السلحفاة نحو اليمين عند البدء. لكن يمكنك تغيير اتجاه الصورة إلى أعلى:

```python
turtle.setheading(90) #الوجه للأعلى
```

انظر على سبيل المثال هنا: <iframe src="https://trinket.io/embed/python/f0d1b53583?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>