---
title: SVGLength.ConvertToSpecifiedUnits
second_title: Aspose.HTML for .NET API リファレンス
description: SVGLength 方法. 基礎となる保存された同じ値を保持しますが保存されたユニット識別子を指定された unitType にリセットしますオブジェクト属性 unitTypevalueInSpecifiedUnitsおよび valueAsString はこのメソッドの結果として変更される場合がありますたとえば元の値が0.5cmでミリメートルに変換するためにメソッドが呼び出された場合unitType は SVG_LENGTHTYPE_MM に変更されvalueInSpecifiedUnits は数値 5 に変更されvalueAsString は5mmに変更されます
type: docs
weight: 50
url: /ja/net/aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

基礎となる保存された同じ値を保持しますが、保存されたユニット識別子を指定された unitType にリセットします。オブジェクト属性 unitType、valueInSpecifiedUnits、および valueAsString は、このメソッドの結果として変更される場合があります。たとえば、元の値が「0.5cm」で、ミリメートルに変換するためにメソッドが呼び出された場合、unitType は SVG_LENGTHTYPE_MM に変更され、valueInSpecifiedUnits は数値 5 に変更され、valueAsString は「5mm」に変更されます。

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| unitType | UInt16 | 切り替える単位の種類 (例: SVG_LENGTHTYPE_MM)。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | コード[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) unitType が SVG_LENGTHTYPE_UNKNOWN であるか、有効なユニット タイプ定数 (このインターフェイスで定義されている他の SVG_LENGTHTYPE_* 定数の 1 つ) でない場合に発生します。 |
| [DOMException](../../../aspose.html.dom/domexception/) | コード[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) 長さが読み取り専用属性に対応する場合、またはオブジェクト自体が読み取り専用の場合に発生します。 |

### 関連項目

* class [SVGLength](../)
* 名前空間 [Aspose.Html.Dom.Svg.DataTypes](../../svglength/)
* 組み立て [Aspose.HTML](../../../)


