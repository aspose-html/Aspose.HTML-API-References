---
title: "SVGException クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.svg.SVGException クラス。この例外は、特定の SVG 操作を実行できない場合にスローされます"
type: docs

url: /ja/java/com.aspose.html.dom.svg/svgexception/
---
## SVGException class

特定の SVG 操作を実行できない場合にこの例外が発生します。

```java
public class SVGException : PlatformException
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGException](svgexception/)(ushort) | `SVGException` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getCode](../../com.aspose.html.dom.svg/svgexception/code/) 要求された操作が実行できなかった理由を示すコードです。このメンバーの値は SVGException のコード グループに定義された定数のいずれかになります。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [SVG_INVALID_VALUE_ERR](../../com.aspose.html.dom.svg/svgexception/svg_invalid_value_err/) | 操作に無効な値が渡されたり属性に割り当てられたときにスローされます。 |
| const [SVG_MATRIX_NOT_INVERTABLE](../../com.aspose.html.dom.svg/svgexception/svg_matrix_not_invertable/) | 逆行列が存在しない行列を反転しようとしたときにスローされます。 |
| const [SVG_WRONG_TYPE_ERR](../../com.aspose.html.dom.svg/svgexception/svg_wrong_type_err/) | 操作に誤った型のオブジェクトが渡されたときにスローされます。 |

### 関連項目

* class [PlatformException](../../com.aspose.html/platformexception/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)
