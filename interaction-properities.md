# 交互属性

交互分为简短的，和连续的。简短交互由一个简单手势动作组成，例如点击。连续的交互允许用户连续触摸屏幕，例如拖拽。

本章节会温习持续交互的可用属性。在 **Pixate** 中短暂交互没有任何的属性，因为交互执行过程是瞬时的。

## 拖拽

当用户拖拽图层时，在连续触摸屏幕的情况下，可以移动图层。

一般地，拖拽模式设置为 **Free**。意思是图层可以向任意方向拖动。

![](images/interaction-properities1.png)

切换到 **Vertical** 或者 **Horizontal** 模式，将会限制图层拖动的方向。

![](images/interaction-properities2.png)

### REFERENCE EDGE

用来定义图层中用于参考的边，可以设置最大值和最小值。

**垂直参数**：

Top, Vertical Center, Bottom

**水平参数**：

Left, Horizontal Center, Right

### MIN AND MAX POSITION

在区域范围内，会对拖拽进行限制，确保图层不越界。

**垂直**：

Min - how far up 

Max - how far down

**水平**：

Min - how far left 

Max - how far right

### STRETCH PAST MINIMUM AND MAXIMUM

设置允许用户拖动的最大和最小范围。数值越小，对图层限制越大。

## 旋转

可以使用两个手指旋转图层。为了启动交互，两根手指必须同时触摸图层。

![](images/interaction-properities3.png)

### MIN AND MAX ANGLE

设置这些值可以限制用户旋转的角度大小。最小角度是逆时针，最大角度是顺时针。

### STRETCH PAST MINIMUM AND MAXIMUM

设置了用户可以旋转图层比例的极限值。值越小，限制越大。

## Resize with Pinch

捏拉改变大小

允许用户使用两根手指捏图层，进行缩放。为了启动交互，两根手指必须同时触摸图层。

![](images/interaction-properities4.png)

### MIN AND MAX SCALE

设置了用户缩放图层比例的极限值。比例值越小，缩放越小，反之亦然。

### STRETCH PAST MINIMUM AND MAXIMUM

设置了用户缩放图层比例的极限值。比例值越小，限制越大。

## 拖拽滚动

滚动界面允许用户使用手指轻弹或者拖拽内容。当滚动界面超出边界时，就会 over-scroll 反弹，这是IOS 的特色。

![](images/interaction-properities5.png)

### PAGING MODE

设置此分页将提前存储多个内容层,用户在滚动界面时，就可看到内容层。

![](images/interaction-properities6.gif)
