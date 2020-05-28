### पाइथन टर्टल चित्र का उपयोग करना

हमेशा turtle का उपयोग करने के बजाय, आप एक अलग छवि का उपयोग करने के लिए Python turtle के आइकॉन को बता सकते हैं। छवि छोटी होनी चाहिए, ताकि यह स्क्रीन के बहुत हिस्से को न ढके: 50 × 50 पिक्सेल आपको एक बड़ा आइकन देगा।

+ सबसे पहले आपको `स्क्रीन` से छवि को रजिस्टर करना होगा:

```python
screen = turtle.Screen()
screen.register_shape('happy.png') 
```

+ फिर आप `shape` को सेट कर सकते हैं:

```python
turtle.shape('happy.png')
```

+ शुरू करने के लिए Turtle आइकॉन का मुख दाहिने ओर रखें। आप अपनी छवि का मुख ऊपर की ओर करने के लिए शीर्षक बदल सकते हैं:

```python
turtle.setheading(90) # ऊपर की तरफ मुख
```

एक उदाहरण यहाँ देखें: <iframe src="https://trinket.io/embed/python/5f68ef3fd7?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>