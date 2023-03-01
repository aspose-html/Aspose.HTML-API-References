---
title: Class SVGLength
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Svg.DataTypes.SVGLength クラス. SVGLength インターフェイスは長さの基本データ型に対応します SVGLength オブジェクトは読み取り専用として指定できますつまりオブジェクトを変更しようとすると以下で説明するように例外がスローされます
type: docs
weight: 1200
url: /ja/net/aspose.html.dom.svg.datatypes/svglength/
---
## SVGLength class

SVGLength インターフェイスは長さの基本データ型に対応します。 SVGLength オブジェクトは読み取り専用として指定できます。つまり、オブジェクトを変更しようとすると、以下で説明するように例外がスローされます。

```csharp
public class SVGLength : SVGValueType
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [UnitType](../../aspose.html.dom.svg.datatypes/svglength/unittype/) { get; } | このインターフェイスで定義された SVG_LENGTHTYPE_* 定数の 1 つによって指定された値の型。 |
| [Value](../../aspose.html.dom.svg.datatypes/svglength/value/) { get; set; } | ユーザー単位の浮動小数点値としての値。この属性を設定すると、valueInSpecifiedUnits と valueAsString が自動的に更新され、この設定が反映されます。 |
| [ValueAsString](../../aspose.html.dom.svg.datatypes/svglength/valueasstring/) { get; set; } | unitType で表される単位の文字列値としての値。この属性を設定すると、値、valueInSpecifiedUnits、および unitType が自動的に更新され、この設定が反映されます。 |
| [ValueInSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/valueinspecifiedunits/) { get; set; } | unitType で表される単位の浮動小数点値としての値。この属性を設定すると、値と valueAsString が自動的に更新され、この設定が反映されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/)(ushort) | 基礎となる保存された同じ値を保持しますが、保存されたユニット識別子を指定された unitType にリセットします。オブジェクト属性 unitType、valueInSpecifiedUnits、および valueAsString は、このメソッドの結果として変更される場合があります。たとえば、元の値が「0.5cm」で、ミリメートルに変換するためにメソッドが呼び出された場合、unitType は SVG_LENGTHTYPE_MM に変更され、valueInSpecifiedUnits は数値 5 に変更され、valueAsString は「5mm」に変更されます。 |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 管理されていないリソースと、オプションで管理されているリソースを解放します。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | このメソッドは、ECMAScript オブジェクトを取得するために使用されますType. |
| [NewValueSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/)(ushort, float) | 関連付けられた unitType を持つ数値として値をリセットし、オブジェクトのすべての属性の値を置き換えます。 |
| override [ToString](../../aspose.html.dom.svg.datatypes/svglength/tostring/)() | を返しますStringこのインスタンスを表す. |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_cm/) | CSS2 で定義されている cm 単位を使用して値が指定されました。 |
| const [SVG_LENGTHTYPE_EMS](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_ems/) | CSS2 で定義されている em 単位を使用して値が指定されました。 |
| const [SVG_LENGTHTYPE_EXS](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_exs/) | CSS2 で定義されている ex 単位を使用して値が指定されました。 |
| const [SVG_LENGTHTYPE_IN](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_in/) | CSS2 で定義されている単位を使用して値が指定されました。 |
| const [SVG_LENGTHTYPE_MM](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_mm/) | CSS2 で定義されている mm 単位を使用して値が指定されました。 |
| const [SVG_LENGTHTYPE_NUMBER](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_number/) | 単位の種類が指定されていません (つまり、単位のない値が指定されました)。これは、ユーザー単位の値を示します。 |
| const [SVG_LENGTHTYPE_PC](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pc/) | CSS2 で定義されている pc 単位を使用して値が指定されました。 |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_percentage/) | パーセント値が指定されました。 |
| const [SVG_LENGTHTYPE_PT](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_pt/) | CSS2 で定義されている pt 単位を使用して値が指定されました。 |
| const [SVG_LENGTHTYPE_PX](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_px/) | CSS2 で定義されている px 単位を使用して値が指定されました。 |
| const [SVG_LENGTHTYPE_UNKNOWN](../../aspose.html.dom.svg.datatypes/svglength/svg_lengthtype_unknown/) | ユニット タイプは、定義済みのユニット タイプの 1 つではありません。この型の新しい値を定義しようとしたり、既存の値をこの型に切り替えようとしたりすることは無効です. |

### 関連項目

* class [SVGValueType](../svgvaluetype/)
* 名前空間 [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* 組み立て [Aspose.HTML](../../)


