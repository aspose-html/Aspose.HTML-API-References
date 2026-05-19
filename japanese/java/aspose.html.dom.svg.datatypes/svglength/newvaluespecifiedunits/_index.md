---
title: "SVGLength.NewValueSpecifiedUnits"
second_title: "Aspose.HTML for Java API リファレンス"
description: "SVGLength メソッド。単位タイプを関連付けた数値として値をリセットし、オブジェクト上のすべての属性の値を置き換えます。"
type: docs

url: /ja/java/com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

unitType が関連付けられた数値として値をリセットし、これによりオブジェクト上のすべての属性の値が置き換えられます。

```java
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| unitType | UInt16 | 値の単位タイプです。 |
| valueInSpecifiedUnits | Single | 新しい値です.. |

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | コード [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/)は、unitType が SVG_LENGTHTYPE_UNKNOWN であるか、有効な単位タイプ定数でない場合に発生します（このインターフェイスで定義されている他の SVG_LENGTHTYPE_* 定数のいずれか）。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | コード [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) は、長さが読み取り専用属性に対応している場合、またはオブジェクト自体が読み取り専用である場合に発生します。 |

### 関連項目

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
