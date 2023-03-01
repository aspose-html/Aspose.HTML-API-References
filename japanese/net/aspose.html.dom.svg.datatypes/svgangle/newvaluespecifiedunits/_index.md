---
title: SVGAngle.NewValueSpecifiedUnits
second_title: Aspose.HTML for .NET API リファレンス
description: SVGAngle 方法. 関連付けられた unitType を持つ数値として値をリセットしオブジェクトのすべての属性の値を置き換えます
type: docs
weight: 60
url: /ja/net/aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

関連付けられた unitType を持つ数値として値をリセットし、オブジェクトのすべての属性の値を置き換えます。

```csharp
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| newUnitType | UInt16 | 値の単位タイプ (例: SVG_ANGLETYPE_DEG)。 |
| valueInSpecifiedUnits | Single | 角度の値。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | コード[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) unitType が SVG_ANGLETYPE_UNKNOWN であるか、有効なユニット タイプ定数 (このインターフェイスで定義されている他の SVG_ANGLETYPE_* 定数の 1 つ) でない場合に発生します。 |
| [DOMException](../../../aspose.html.dom/domexception/) | コード[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) 角度が読み取り専用属性に対応する場合、またはオブジェクト自体が読み取り専用の場合に発生します。 |

### 関連項目

* class [SVGAngle](../)
* 名前空間 [Aspose.Html.Dom.Svg.DataTypes](../../svgangle/)
* 組み立て [Aspose.HTML](../../../)


