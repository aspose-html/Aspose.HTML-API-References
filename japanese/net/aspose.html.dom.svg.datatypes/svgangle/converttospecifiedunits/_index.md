---
title: SVGAngle.ConvertToSpecifiedUnits
second_title: Aspose.HTML for .NET API リファレンス
description: SVGAngle 方法. 基礎となる保存された同じ値を保持しますが保存されたユニット識別子を指定された unitType にリセットしますオブジェクト属性 unitTypevalueInSpecifiedUnitsおよび valueAsString はこのメソッドの結果として変更される可能性があります.
type: docs
weight: 50
url: /ja/net/aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

基礎となる保存された同じ値を保持しますが、保存されたユニット識別子を指定された unitType にリセットします。オブジェクト属性 unitType、valueInSpecifiedUnits、および valueAsString は、このメソッドの結果として変更される可能性があります.

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| unitType | UInt16 | 切り替える単位の種類 (例: SVG_ANGLETYPE_DEG)。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | コード[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) unitType が SVG_ANGLETYPE_UNKNOWN であるか、有効なユニット タイプ定数 (このインターフェイスで定義されている他の SVG_ANGLETYPE_* 定数の 1 つ) でない場合に発生します。 |
| [DOMException](../../../aspose.html.dom/domexception/) | コード[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) 角度が読み取り専用属性に対応する場合、またはオブジェクト自体が読み取り専用の場合に発生します。 |

### 関連項目

* class [SVGAngle](../)
* 名前空間 [Aspose.Html.Dom.Svg.DataTypes](../../svgangle/)
* 組み立て [Aspose.HTML](../../../)


