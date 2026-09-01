---
title: "SVGPoint クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.svg.datatypes.SVGPoint クラス。多くの SVG DOM インターフェイスは SVGPoint クラスのオブジェクトを参照します。SVGPoint は x y 座標ペアです。行列演算で使用される場合、SVGPoint は x y 1 の形のベクトルとして扱われます。SVGRect オブジェクトが読み取り専用として指定されている場合、その属性のいずれかに代入しようとすると例外がスローされます。"
type: docs

url: /ja/java/com.aspose.html.dom.svg.datatypes/svgpoint/
---
## SVGPoint class

SVG DOM の多くのインターフェイスはクラス SVGPoint のオブジェクトを参照します。SVGPoint は (x, y) の座標ペアです。行列演算で使用される場合、SVGPoint は次の形のベクトルとして扱われます: [x] [y] [1]。SVGRect オブジェクトが読み取り専用に指定されている場合、その属性のいずれかに代入しようとすると例外がスローされます。

```java
public class SVGPoint : SVGValueType
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [X](../../com.aspose.html.dom.svg.datatypes/svgpoint/x/) { get; set; } | X 座標。 |
| [Y](../../com.aspose.html.dom.svg.datatypes/svgpoint/y/) { get; set; } | Y 座標。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | アンマネージドおよび（オプションで）マネージドリソースを解放します。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [matrixTransform](../../com.aspose.html.dom.svg.datatypes/svgpoint/matrixtransform/)(SVGMatrix) | この SVGPoint オブジェクトに 2x3 行列変換を適用し、新しい変換後の SVGPoint オブジェクトを返します: newpoint = matrix * thispoint |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgpoint/toString/)() | このインスタンスを表す文字列を返します。 |

### 関連項目

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
