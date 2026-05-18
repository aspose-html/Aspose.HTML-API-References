---
title: "Path2D.Arc"
second_title: "Aspose.HTML for Java API 参考"
description: "Path2D 方法。向路径添加一个弧线，该弧线以 x y 位置为中心，半径为 r，从 startAngle 开始，在 endAngle 结束，按给定方向绘制，默认顺时针，若为 anticlockwise 则逆时针。"
type: docs

url: /zh/java/com.aspose.html.dom.canvas/path2d/arc/
---
## Arc(double, double, double, double, double) {#arc}

向路径添加一个弧，该弧以 (x, y) 为中心，半径为 r，从 startAngle 开始到 endAngle 结束，按给定方向逆时针绘制（默认顺时针）。

```java
public void Arc(double x, double y, double radius, double startAngle, double endAngle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | Double | 弧中心的 x 坐标。 |
| y | Double | 弧中心的 y 坐标。 |
| 半径 | Double | 弧的半径。 |
| startAngle | Double | 弧的起始角度，以正 x 轴为基准顺时针测量，以弧度表示。 |
| endAngle | Double | 弧的结束角度，以正 x 轴为基准顺时针测量，以弧度表示。 |

### 另请参阅

* class [Path2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Arc(double, double, double, double, double, bool) {#arc_1}

向路径添加一个弧，该弧以 (x, y) 为中心，半径为 r，从 startAngle 开始到 endAngle 结束，按给定方向逆时针绘制（默认顺时针）。

```java
public void Arc(double x, double y, double radius, double startAngle, double endAngle, 
    bool counterclockwise)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | Double | 弧中心的 x 坐标。 |
| y | Double | 弧中心的 y 坐标。 |
| 半径 | Double | 弧的半径。 |
| startAngle | Double | 弧的起始角度，以正 x 轴为基准顺时针测量，以弧度表示。 |
| endAngle | Double | 弧的结束角度，以正 x 轴为基准顺时针测量，以弧度表示。 |
| 逆时针 | Boolean | 使弧在两个角度之间逆时针绘制。默认情况下为顺时针绘制。 |

### 另请参阅

* class [Path2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
