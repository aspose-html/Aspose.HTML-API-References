---
title: "ICanvasPathMethods.Ellipse"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICanvasPathMethods メソッド。パスに楕円を追加します。楕円は x y 位置を中心とし、半径 radiusX と radiusY、開始角度 startAngle、終了角度 endAngle で、指定された方向で描かれます。デフォルトは clockwise で、anticlockwise に設定することもできます。"
type: docs

url: /ja/java/com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/
---
## Ellipse(double, double, double, double, double, double, double) {#ellipse}

パスに楕円を追加します。楕円は (x, y) を中心とし、半径 radiusX と radiusY を持ち、startAngle から始まり endAngle で終わり、指定された方向（デフォルトは時計回りで、反時計回りを指定可能）に描かれます。

```java
public void Ellipse(double x, double y, double radiusX, double radiusY, double rotation, 
    double startAngle, double endAngle)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| x | Double | 楕円の中心の座標の x 軸。 |
| y | Double | 楕円の中心の座標の y 軸。 |
| radiusX | Double | 楕円の長軸半径。 |
| radiusY | Double | 楕円の短軸半径。 |
| rotation | Double | この楕円の回転（ラジアンで表現）。 |
| startAngle | Double | 描画開始点（x 軸から測定し、ラジアンで表現）。 |
| endAngle | Double | 描画終了角度（楕円の終点、ラジアンで表現）。 |

### 関連項目

* interface [ICanvasPathMethods](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## Ellipse(double, double, double, double, double, double, double, bool) {#ellipse_1}

パスに楕円を追加します。楕円は (x, y) を中心とし、半径 radiusX と radiusY を持ち、startAngle から始まり endAngle で終わり、指定された方向（デフォルトは時計回りで、反時計回りを指定可能）に描かれます。

```java
public void Ellipse(double x, double y, double radiusX, double radiusY, double rotation, 
    double startAngle, double endAngle, bool anticlockwise)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| x | Double | 楕円の中心の座標の x 軸。 |
| y | Double | 楕円の中心の座標の y 軸。 |
| radiusX | Double | 楕円の長軸半径。 |
| radiusY | Double | 楕円の短軸半径。 |
| rotation | Double | この楕円の回転（ラジアンで表現）。 |
| startAngle | Double | 描画開始点（x 軸から測定し、ラジアンで表現）。 |
| endAngle | Double | 描画終了角度（楕円の終点、ラジアンで表現）。 |
| anticlockwise | Boolean | オプションのブール値で、true の場合は楕円を反時計回り（counter-clockwise）で描画し、false の場合は時計回りで描画します。 |

### 関連項目

* interface [ICanvasPathMethods](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
