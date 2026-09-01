---
title: "CanvasFillRule 列挙型"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.canvas.CanvasFillRule 列挙型。 この列挙は、点がパスの内部にあるか外部にあるかを判定する塗りつぶし規則アルゴリズムを選択するために使用されます。"
type: docs

url: /ja/java/com.aspose.html.dom.canvas/canvasfillrule/
---
## CanvasFillRule enumeration

この列挙は、点がパスの内部にあるか外部にあるかを判定する塗りつぶしルールアルゴリズムを選択するために使用されます。

```java
public enum CanvasFillRule
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| NonZero | `0` | 「nonzero」 値は非ゼロ winding ルールを示します。このルールでは、点から半無限直線を引いたとき、その線が形状のパスをある方向に交差する回数と逆方向に交差する回数が等しい場合、点は形状の外側とみなされます。 |
| EvenOdd | `1` | 「evenodd」 値は偶数-奇数ルールを示します。このルールでは、点から半無限直線を引いたとき、その線が形状のパスと交差する回数が偶数であれば、点は形状の外側とみなされます。 |

### 関連項目

* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
