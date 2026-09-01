---
title: "SVGLength.ConvertToSpecifiedUnits"
second_title: "Aspose.HTML for Java API リファレンス"
description: "SVGLength メソッド。基礎となる格納値は同じまま保持し、格納された単位識別子を指定された unitType にリセットします。このメソッドの結果として、オブジェクト属性の unitType、valueInSpecifiedUnits、valueAsString が変更される可能性があります。例えば、元の値が 0.5cm で、このメソッドをミリメートルに変換するために呼び出した場合、unitType は SVG_LENGTHTYPE_MM に変更され、valueInSpecifiedUnits は数値の 5 に、valueAsString は 5mm に変更されます。"
type: docs

url: /ja/java/com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

同じ基礎となる保存値を保持しつつ、保存された単位識別子を指定された unitType にリセットします。このメソッドの結果としてオブジェクト属性 unitType、valueInSpecifiedUnits、valueAsString が変更される可能性があります。例えば、元の値が \"0.5cm\" でメソッドがミリメートルに変換するために呼び出された場合、unitType は SVG_LENGTHTYPE_MM に変更され、valueInSpecifiedUnits は数値の 5 に、valueAsString は \"5mm\" に変更されます。

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| unitType | UInt16 | 切り替える単位タイプ (例: SVG_LENGTHTYPE_MM)。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | コード [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/)は、unitType が SVG_LENGTHTYPE_UNKNOWN または有効な単位タイプ定数でない場合に発生します（このインターフェイスで定義されている他の SVG_LENGTHTYPE_* 定数のいずれか）。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | コード [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) は、長さが読み取り専用属性に対応している場合、またはオブジェクト自体が読み取り専用の場合に発生します。 |

### 関連項目

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
