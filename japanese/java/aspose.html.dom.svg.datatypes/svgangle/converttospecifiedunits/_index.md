---
title: "SVGAngle.ConvertToSpecifiedUnits"
second_title: "Aspose.HTML for Java API リファレンス"
description: "SVGAngle メソッド。基になる格納値はそのままに、格納された単位識別子を指定された unitType にリセットします。このメソッドの結果として、オブジェクト属性の unitType、valueInSpecifiedUnits、valueAsString が変更される可能性があります。"
type: docs

url: /ja/java/com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

同じ基礎となる格納値を保持しつつ、格納された単位識別子を指定された unitType にリセットします。このメソッドの結果として、オブジェクトの属性 unitType、valueInSpecifiedUnits、valueAsString が変更される可能性があります。

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| unitType | UInt16 | 切り替える単位タイプ（例: SVG_ANGLETYPE_DEG）。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | コード[`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/)は、unitType が SVG_ANGLETYPE_UNKNOWN であるか、有効な単位タイプ定数でない場合に発生します（このインターフェイスで定義されている他の SVG_ANGLETYPE_* 定数のいずれか）。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | コード [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) は、角度が読み取り専用属性に対応している場合、またはオブジェクト自体が読み取り専用の場合に発生します。 |

### 関連項目

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
