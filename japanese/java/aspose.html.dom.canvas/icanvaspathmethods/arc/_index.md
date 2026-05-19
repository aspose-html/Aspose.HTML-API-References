---
title: "ICanvasPathMethods.Arc"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICanvasPathMethods メソッド。パスに円弧を追加します。円弧は x y 位置を中心とし、半径 r、開始角度 startAngle、終了角度 endAngle で、指定された方向で描かれます。デフォルトは clockwise で、anticlockwise に設定することもできます。"
type: docs

url: /ja/java/com.aspose.html.dom.canvas/icanvaspathmethods/arc/
---
## Arc(double, double, double, double, double) {#arc}

パスに弧を追加します。弧は (x, y) を中心とし、半径 r で、startAngle から始まり endAngle で終わり、指定された方向（デフォルトは時計回りで、反時計回りを指定可能）に描かれます。

```java
public void Arc(double x, double y, double radius, double startAngle, double endAngle)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| x | Double | 円弧の中心の x 座標です。 |
| y | Double | 円弧の中心の y 座標です。 |
| 半径 | Double | 円弧の半径です。 |
| startAngle | Double | 円弧が開始する角度で、正の x 軸から時計回りに測定し、ラジアンで表します。 |
| endAngle | Double | 円弧が終了する角度で、正の x 軸から時計回りに測定し、ラジアンで表します。 |

### 関連項目

* interface [ICanvasPathMethods](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Arc(double, double, double, double, double, bool) {#arc_1}

パスに弧を追加します。弧は (x, y) を中心とし、半径 r で、startAngle から始まり endAngle で終わり、指定された方向（デフォルトは時計回りで、反時計回りを指定可能）に描かれます。

```java
public void Arc(double x, double y, double radius, double startAngle, double endAngle, 
    bool counterclockwise)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| x | Double | 円弧の中心の x 座標です。 |
| y | Double | 円弧の中心の y 座標です。 |
| 半径 | Double | 円弧の半径です。 |
| startAngle | Double | 円弧が開始する角度で、正の x 軸から時計回りに測定し、ラジアンで表します。 |
| endAngle | Double | 円弧が終了する角度で、正の x 軸から時計回りに測定し、ラジアンで表します。 |
| counterclockwise | Boolean | 円弧が2つの角度間を反時計回りに描かれるようにします。デフォルトでは時計回りで描画されます。 |

### 関連項目

* interface [ICanvasPathMethods](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
