### ಪೈಥಾನ್ ಆಮೆ ಐಕಾನ್ಗಳನ್ನು ಬದಲಾಯಿಸುವುದು

ಯಾವಾಗಲೂ ಆಮೆ ಬಳಸುವ ಬದಲು, ಬೇರೆ ಚಿತ್ರವನ್ನು ಬಳಸಲು ನೀವು ಪೈಥಾನ್ ಆಮೆ ಐಕಾನ್‌ಗೆ ಹೇಳಬಹುದು. ಚಿತ್ರವು ಚಿಕ್ಕದಾಗಿರಬೇಕು, ಇದರಿಂದ ಅದು ಪರದೆಯನ್ನು ಹೆಚ್ಚು ಮುಚ್ಚಿಕೊಳ್ಳುವುದಿಲ್ಲ: 50 × 50 ಪಿಕ್ಸೆಲ್‌ಗಳು ನಿಮಗೆ ದೊಡ್ಡ ಐಕಾನ್ ನೀಡುತ್ತದೆ.

+ ಮೊದಲು ನೀವು ` ಪರದೆಯೊಂದಿಗೆ ಚಿತ್ರವನ್ನು ನೋಂದಾಯಿಸಿಕೊಳ್ಳಬೇಕು `:

```python
screen = turtle.Screen ()
screen.register_shape ('happy.png') 
```

+ ನಂತರ ನೀವು ` ಆಕಾರವನ್ನು ಹೊಂದಿಸಬಹುದು `:

```python
turtle.shape ('happy.png')
```

+ ಆಮೆ ಐಕಾನ್‌ಗಳು ಪ್ರಾರಂಭವಾಗುವ ಹಕ್ಕನ್ನು ಎದುರಿಸುತ್ತವೆ. ನಿಮ್ಮ ಚಿತ್ರವನ್ನು ಮೇಲಕ್ಕೆ ಮುಖ ಮಾಡಲು ನೀವು ಶೀರ್ಷಿಕೆಯನ್ನು ಬದಲಾಯಿಸಬಹುದು:

```python
turtle.setheading (90) # ಮುಖ ಮೇಲಕ್ಕೆ
```

ಇಲ್ಲಿ ಒಂದು ಉದಾಹರಣೆ ನೋಡಿ: 

<iframe src="https://trinket.io/embed/python/5f68ef3fd7?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>