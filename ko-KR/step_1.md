### 파이썬 거북 아이콘 변경하기

거북이를 항상 사용하는 대신 파이썬 거북 아이콘에 다른 이미지를 사용하도록 알릴 수 있습니다. 이미지가 너무 작아서 화면이 너무 많이 가려지지 않아야합니다. 50 × 50 픽셀은 커다란 아이콘을 줄 것입니다.

+ 먼저 이미지를 `screen`에 아래와 같이 등록합니다:

```python
screen = turtle.Screen()
screen.register_shape('happy.png') 
```

+ 그런 다음 `모양`을 설정할 수 있습니다:

```python
turtle.shape('happy.png')
```

+ 거북이 아이콘은 바로 시작합니다. 제목을 변경하여 이미지가 위를 향하도록 할 수 있습니다.

```python
turtle.setheading(90) # 얼굴을 위쪽으로
```

아래 예제를 참조하십시오: 
<iframe src="https://trinket.io/embed/python/9dbdb00d08?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>