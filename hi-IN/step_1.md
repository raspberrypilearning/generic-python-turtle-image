Python टर्टल के लिए उपयोग करने के लिए चित्र निर्धारित कर सकते हैं। 

टर्टल चित्रों का आकार छोटा होना चाहिए, 50 x 50 पिक्सल्स बड़ा टर्टल चित्र प्रदान करेंगे। 

सबसे पहले आपको चित्र को स्क्रीन के साथ पंजीकृत करना चाहिए। 

```python
screen = turtle.Screen()
screen.register_shape('happy.png') 
```

इसके बाद आप आकृति निर्धारित कर सकते हैं:

```python
turtle.shape('happy.png')
```

टर्टल शुरू करने के लिए मुख दाईं तरफ रखते हैं। आप अपने चित्र को उत्तर की ओर करने के लिए शीर्षक में परिवर्तन कर सकते हैं:

```python
turtle.setheading(90) # face north
```

उदाहरण:
<iframe src="https://trinket.io/embed/python/5f68ef3fd7?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

