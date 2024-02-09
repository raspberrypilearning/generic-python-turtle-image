### Python Turtle आइकन बदलना

हमेशा turtle का उपयोग करने के बजाय, आप एक अलग चित्र का उपयोग करने के लिए Python Turtle के आइकॉन को कह सकते हैं। चित्र छोटा होना चाहिए, ताकि यह स्क्रीन के बहुत हिस्से को न ढके: 50 × 50 पिक्सल (pixel) आपको एक बड़ा आइकन देगा।

+ सबसे पहले आपको `screen` के साथ चित्र को रजिस्टर करना होगा:

```python
screen = turtle.Screen()
screen.register_shape('happy.png') 
```

+ फिर आप `shape` को सेट कर सकते हैं:

```python
turtle.shape('happy.png')
```

+ शुरू करने के लिए Turtle आइकॉन का मुख दाहिने ओर होता है। आप अपने चित्र का मुख ऊपर की ओर करने के लिए शीर्षक बदल सकते हैं:

```python
turtle.setheading(90) # ऊपर की तरफ मुख
```

एक उदाहरण यहाँ देखें: <iframe src="https://trinket.io/embed/python/5f68ef3fd7?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>