# Conditions

条件

在开始之前，你可以对一个动画值进行检查。通过条件进行设置。这或许是最难学习的部分。一旦你知道这是如何工作的，要搞清这个问题，只要指定一个动画进行分析。

You can give an animations values to check against, before starting. These are set with conditions. This is probably the steepest part of the learning curve. Once you understand how it works, it’s just a matter of figuring out what you need for your specific animation.

下面是一个例子,条件表达式和分解的部分：

Below is an example of a conditional expression and a breakdown of the parts:

```
(layer1.x >= 0 and layer1.cx < 113) or (layer2.opacity > 0 and layer2.y == 259)
```

## Layer ID

Layer ID

条件只会识别图层 id。id 直接联系到图层名字，图层名字改变时会进行更新。取一个简短的图层名字好处很大。

Conditions will only recognize the layer IDs. These are directly tied to the layer name and will update when the layer’s name is changed. Shorter layer names can make your life easier. 

> 技巧：从属性面板中复制粘贴图层 ID，而不是手动输入。

> Tip: copy and paste the layer ID  from the property pane instead of typing in manually.

```
(layer1.x >= 0 and layer1.cx < 113) or (layer2.opacity > 0 and layer2.y == 259)
```

## Property

属性

这决定了图层属性条件会进行检查。属性的当前值会对提供的值进行检查。

This defines which layer property the condition should be checking. The current value of the property will be checked against the provided value.

```
(layer1.x >= 0 and layer1.cx < 113) or (layer2.opacity > 0 and layer2.y == 259)
```

下面是图层的属性表：

Here’s a list of current layer properties:


| 属性 | 描述 |
|----------|-------------|
| `.x or .left` | 左边的位置 |
| `.cx` | 水平居中 |
| `.right` | 右边的位置 |
| `.y or .top` | 顶边的位置 |
| `.cy` | 垂直居中 |
| `.bottom` | 低边的位置 |
| `.width` | 图层的宽度 |
| `.height` | 图层的高度 |
| `.scale` | 图层的缩放比 |
| `.scaleX` | 水平缩放比|
| `.scaleY` | 垂直缩放比 |
| `.opacity` | 图层透明度 |
| `.rotation` | z 轴上的选择角度 |
| `.rotationX` | x 轴上的选择角度 |
| `.rotationY` | y 轴上的选择角度 |
| `.rotationZ` | z 轴上的选择角度 |
| `.contentX` | 水平滚动的偏移 |
| `.contentY` | 垂直滚动的偏移 |
| `.velocityX` | 水平滚动的偏移的速度 |
| `.velocityY` | 垂直滚动的偏移的速度 |

| Property | Description |
|----------|-------------|
| `.x or .left` | Position of the left side |
| `.cx` | Horizontal center |
| `.right` | Position of the right side |
| `.y or .top` | Position of the top |
| `.cy` | Vertical center |
| `.bottom` | Position of the bottom |
| `.width` | The width value of the layer |
| `.height` | The height value of the layer |
| `.scale` | Scale factor of the layer (1 is original size, 2 is twice that size, etc.) |
| `.scaleX` | Horizontal scale factor |
| `.scaleY` | Vertical scale factor |
| `.opacity` | Layer opacity (0 - 1, transparent - opaque) |
| `.rotation` | Rotation around the Z axis (Same as .rotationZ) |
| `.rotationX` | Rotation around X axis (Vertical flip) |
| `.rotationY` | Rotation around Y axis (Horizontal flip) |
| `.rotationZ` | Rotation around Z axis (Same as .rotation) |
| `.contentX` | Horizontal offset of scroll |
| `.contentY` | Vertical offset of scroll |
| `.velocityX` | Horizontal speed and direction of scroll (negative value, left gesture) |
| `.velocityY` | Vertical speed and direction of scroll (negative value, upward gesture) |

## Comparison operator

比较运算符

比较运算符用来比较图层属性当前的值和将要赋值的值。

Comparison operators are used to compare a layer's current and provided values. 

```
layer1.x >= 0 and layer1.cx < 113) or (layer2.opacity > 0 and layer2.y == 259)
```

可能比较运算符：

Operators available:

| 操作符 | 描述 |
|----------|-------------|
| `<` | 小于 |
| `<=` | 不大于 |
| `>` | 大于 |
| `>=` | 不小于 |
| `==` | 等于 |
| `!=` | 不等于 |

| Operator | Description |
|----------|-------------|
| `<` | Less than |
| `<=` | Less than or equal to |
| `>` | Greater than |
| `>=` | Greater than or equal to |
| `==` | Equal to |
| `!=` | Not equal to |

## Value

值

图层属性的当前值会检查将要赋值的值，是否满足条件。值包括算术表达式。

The value of the layer property is checked against this provided value, to see if the condition is met. Values can include basic arithmetic expressions.

```
(layer1.x >= 0 and layer1.cx < 113) or (layer2.opacity > 0 and layer2.y == 259)
```

请留意，十进制实数必须使用前导零。例如 **0.5** 是合法值，**.5** 是非法值。

Please note, a leading zero must be used for decimal values. For example, **0.5** is a valid value; **.5** is not a valid value.

## Logical operators

逻辑运算符

逻辑运算符

逻辑运算符用以复杂的条件判断。创建一个复杂的条件表达式用来检测各种各样的图层和属性。使用小括号对复杂的条件表达式进行切分。

Logical operators are used to link multiple conditions. These are used to create complex conditions that can check against multiple properties and multiple layers. Parenthesis should be used to group more complex conditions

```
(layer1.x >= 0 and layer1.cx < 113) or (layer2.opacity > 0 and layer2.y == 259)
```

下面是一些逻辑运算符：

Here is the list of arguments:

| 操作符 | 描述 |
|----------|-------------|
| `and` | 操作符两边表单式为真则为真 |
| `or` | 操作符某一边为真则为真 |
| `not` | 逻辑非 |

| Operator | Description |
|----------|-------------|
| `and` | Both the lefthand and righthand expressions must be true |
| `or` | Either the lefthand or righthand expressions must be true |
| `not` | Logical negation |
