### 更改Python烏龜圖像

除了一直使用烏龜的圖標，你可以讓 Python Turtle icon使用一個不一樣的圖像 圖像應該要很小，這樣它才不會遮擋太多屏幕畫面：50×50像素會給你一個很大的圖標。

+ 首先你需要使用屏幕 `screen`來註冊要用的圖像：

```python
screen = turtle.Screen()
screen.register_shape('happy.png') 
```

+ 接著你可以設置形狀`shape`：

```python
turtle.shape('happy.png')
```

+ 烏龜圖標面朝右開始。 你可以更改方向來讓你的圖像朝上：

```python
turtle.setheading(90)＃朝上
```

這裡可以看到實例：
<iframe src="https://trinket.io/embed/python/ff7e4cceb6?start=result" width="100%" height="300" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen mark="crwd-mark"></iframe>