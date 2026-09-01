---
title: "SVGAngle クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.svg.datatypes.SVGAngle クラス。SVGAngle インターフェイスは angle 基本データ型に対応します。"
type: docs

url: /ja/java/com.aspose.html.dom.svg.datatypes/svgangle/
---
## SVGAngle class

SVGAngle インターフェイスは、角度の基本データ型に対応します。

```java
public class SVGAngle : SVGValueType
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svgangle/unittype/) このインターフェイスで定義された SVG_ANGLETYPE_* 定数のいずれかによって指定された値の型です。 |
[getValue]
[setValue] The angle value as a floating point value, in degrees. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The angle value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The angle value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | 同じ基礎となる格納値を保持しつつ、格納された単位識別子を指定された unitType にリセットします。このメソッドの結果として、オブジェクトの属性 unitType、valueInSpecifiedUnits、valueAsString が変更される可能性があります。 |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | アンマネージドおよび（オプションで）マネージドリソースを解放します。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | 単位タイプが関連付けられた数値として値をリセットし、オブジェクト上のすべての属性の値を置き換えます。 |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgangle/toString/)() | このインスタンスを表す文字列を返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_deg/) | 単位タイプは明示的に degrees に設定されました。 |
| const [SVG_ANGLETYPE_GRAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_grad/) | 単位タイプは radians です。 |
| const [SVG_ANGLETYPE_RAD](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_rad/) | 単位タイプは radians です。 |
| const [SVG_ANGLETYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unknown/) | 単位タイプは事前定義された単位タイプのいずれでもありません。このタイプの新しい値を定義しようとしたり、既存の値をこのタイプに切り替えようとすることは無効です。 |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../com.aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unspecified/) | 単位タイプが提供されませんでした（つまり、単位なしの値が指定されました）。角度の場合、単位なしの値は degrees が指定された場合と同様に扱われます。 |

### 関連項目

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
