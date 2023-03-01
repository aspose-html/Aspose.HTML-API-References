---
title: SVGLength.NewValueSpecifiedUnits
second_title: Aspose.HTML for .NET API リファレンス
description: SVGLength 方法. 関連付けられた unitType を持つ数値として値をリセットしオブジェクトのすべての属性の値を置き換えます
type: docs
weight: 60
url: /ja/net/aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

関連付けられた unitType を持つ数値として値をリセットし、オブジェクトのすべての属性の値を置き換えます。

```csharp
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| unitType | UInt16 | 値の単位タイプ。 |
| valueInSpecifiedUnits | Single | 新しい価値.. |

### 例外

| 例外 | 調子 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | コード[`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) unitType が SVG_LENGTHTYPE_UNKNOWN であるか、有効なユニット タイプ定数 (このインターフェイスで定義されている他の SVG_LENGTHTYPE_* 定数の 1 つ) でない場合に発生します。 |
| [DOMException](../../../aspose.html.dom/domexception/) | コード[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) 長さが読み取り専用属性に対応する場合、またはオブジェクト自体が読み取り専用の場合に発生します。 |

### 関連項目

* class [SVGLength](../)
* 名前空間 [Aspose.Html.Dom.Svg.DataTypes](../../svglength/)
* 組み立て [Aspose.HTML](../../../)


