---
title: "SVGLength クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.svg.datatypes.SVGLength クラス。SVGLength インターフェイスは長さの基本データ型に対応します。SVGLength オブジェクトは読み取り専用に指定でき、オブジェクトの変更を試みると、以下に記載された例外がスローされます"
type: docs

url: /ja/java/com.aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

SVGLength インターフェイスは length 基本データ型に対応します。SVGLength オブジェクトは読み取り専用に指定でき、オブジェクトの変更を試みると例外がスローされます（以下参照）。

```java
public class SVGLength : SVGValueType
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getUnitType](../../com.aspose.html.dom.svg.datatypes/svglength/unittype/) 値の型は、このインターフェイスで定義された SVG_LENGTHTYPE_* 定数のいずれかで指定されます。 |
[getValue]
[setValue] The value as a floating point value, in user units. Setting this attribute will cause valueInSpecifiedUnits and valueAsString to be updated automatically to reflect this setting. |
[getValueAsString]
[setValueAsString] The value as a String value, in the units expressed by unitType. Setting this attribute will cause value, valueInSpecifiedUnits and unitType to be updated automatically to reflect this setting. |
[getValueInSpecifiedUnits]
[setValueInSpecifiedUnits] The value as a floating point value, in the units expressed by unitType. Setting this attribute will cause value and valueAsString to be updated automatically to reflect this setting. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [convertToSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/)(ushort) | 同じ基礎となる格納値を保持しつつ、格納された単位識別子を指定された unitType にリセットします。このメソッドの結果として、オブジェクト属性 unitType、valueInSpecifiedUnits、valueAsString が変更される可能性があります。例えば、元の値が "0.5cm" で、メソッドがミリメートルに変換するために呼び出された場合、unitType は SVG_LENGTHTYPE_MM に変更され、valueInSpecifiedUnits は数値の 5 に変更され、valueAsString は "5mm" に変更されます。 |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | アンマネージドおよび（オプションで）マネージド リソースを解放します。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [newValueSpecifiedUnits](../../com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/)(ushort, float) | unitType が関連付けられた数値として値をリセットし、これによりオブジェクト上のすべての属性の値が置き換えられます。 |
| [toString](../../com.aspose.html.dom.svg.datatypes/svglength/toString/)() | このインスタンスを表す文字列を返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm/) | CSS2 で定義された cm 単位を使用して値が指定されました。 |
| const [SVG_LENGTHTYPE_EMS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems/) | CSS2 で定義された em 単位を使用して値が指定されました。 |
| const [SVG_LENGTHTYPE_EXS](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs/) | CSS2 で定義された ex 単位を使用して値が指定されました。 |
| const [SVG_LENGTHTYPE_IN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in/) | CSS2 で定義された in 単位を使用して値が指定されました。 |
| const [SVG_LENGTHTYPE_MM](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm/) | CSS2 で定義された mm 単位を使用して値が指定されました。 |
| const [SVG_LENGTHTYPE_NUMBER](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number/) | 単位タイプが提供されませんでした（つまり、単位なしの値が指定され）、これはユーザー単位の値を示します。 |
| const [SVG_LENGTHTYPE_PC](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc/) | CSS2 で定義された pc 単位を使用して値が指定されました。 |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage/) | パーセンテージ値が指定されました。 |
| const [SVG_LENGTHTYPE_PT](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt/) | CSS2 で定義された pt 単位を使用して値が指定されました。 |
| const [SVG_LENGTHTYPE_PX](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px/) | CSS2 で定義された px 単位を使用して値が指定されました。 |
| const [SVG_LENGTHTYPE_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown/) | 単位タイプは事前定義された単位タイプのいずれでもありません。このタイプの新しい値を定義しようとしたり、既存の値をこのタイプに切り替えようとすることは無効です。 |

### 関連項目

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
