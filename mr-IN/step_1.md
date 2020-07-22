### Python Turtle icons बदलने

नेहमी Turtle वापरण्याऐवजी तुम्ही Python Turtle icon ला वेगळी image वापरण्यास सांगू शकता. Image लहान असावी, जेणेकरून ती जास्त स्क्रीन कव्हर करणार नाही: 50 × 50 पिक्सेल तुम्हाला एक मोठे icon देईल.

+ प्रथम तुम्हाला `screen` सह image नोंदणी करणे आवश्यक आहे:

```python
screen = turtle.Screen()
screen.register_shape('happy.png') 
```

+ नंतर तुम्ही `shape` सेट करू शकता:

```python
turtle.shape('happy.png')
```

+ Turtle icons प्रारंभ होण्यास उजवीकडे असावे लागते. तुम्ही image वरच्या दिशेने येण्यासाठी आपण शीर्षक बदलू शकता:

```python
turtle.setheading(90) # face upwards
```

येथे एक उदाहरण पहा: <iframe src="https://trinket.io/embed/python/5f68ef3fd7?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>