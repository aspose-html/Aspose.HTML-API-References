---
title: "ICanvasPathMethods.Arc"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICanvasPathMethods メソッド。パスに弧を追加します。弧は x y 位置を中心とし、半径 r で、startAngle から始まり endAngle で終わります。方向はデフォルトで時計回りですが、反時計回りに指定することもできます。"
type: docs

url: /ja/java/com.aspose.html.dom.canvas/icanvaspathmethods/arc/
---
## Arc(double, double, double, double, double) {#arc}

パスに円弧を追加します。円弧は (x, y) を中心とし、半径 r で、startAngle から始まり endAngle で終わり、指定された方向（デフォルトは時計回りで、反時計回りを指定可能）に描かれます。

```java
public void Arc(double x, double y, double radius, double startAngle, double endAngle)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | Double | 円弧の中心の x 座標です。 |
| y | Double | 円弧の中心の y 座標です。 |
| 半径 | Double | 円弧の半径です。 |
| startAngle | Double | 円弧が開始する角度で、正の x 軸から時計回りに測定し、ラジアンで表されます。 |
| endAngle | Double | 円弧が終了する角度で、正の x 軸から時計回りに測定し、ラジアンで表されます。 |

### 関連項目

* interface [ICanvasPathMethods](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Arc(double, double, double, double, double, bool) {#arc_1}

パスに円弧を追加します。円弧は (x, y) を中心とし、半径 r で、startAngle から始まり endAngle で終わり、指定された方向（デフォルトは時計回りで、反時計回りを指定可能）に描かれます。

```java
public void Arc(double x, double y, double radius, double startAngle, double endAngle, 
    bool counterclockwise)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | Double | 円弧の中心の x 座標です。 |
| y | Double | 円弧の中心の y 座標です。 |
| 半径 | Double | 円弧の半径です。 |
| startAngle | Double | 円弧が開始する角度で、正の x 軸から時計回りに測定し、ラジアンで表されます。 |
| endAngle | Double | 円弧が終了する角度で、正の x 軸から時計回りに測定し、ラジアンで表されます。 |
| 反時計回り | Boolean | 2 つの角度間で円弧を反時計回りに描画します。デフォルトでは時計回りに描画されます。 |

### 関連項目

* interface [ICanvasPathMethods](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
