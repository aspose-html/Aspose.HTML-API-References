---
title: "RGBColor クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.css.RGBColor クラス。RGBColor インターフェイスは任意の RGB カラー値を表すために使用されます。このインターフェイスは基礎となる style プロパティの値を反映します。そのため、CSSPrimitiveValue オブジェクトに対する変更は style プロパティを変更します。"
type: docs

url: /ja/java/com.aspose.html.dom.css/rgbcolor/
---
## RGBColor class

RGBColor インターフェイスは任意の RGB カラー値を表すために使用されます。このインターフェイスは基礎となるスタイルプロパティの値を反映します。そのため、CSSPrimitiveValue オブジェクトに対する変更はスタイルプロパティを変更します。

指定された RGB カラーはクリップされません（数値が 0-255 または 0%-100% の範囲外であっても）。計算された RGB カラーはデバイスに応じてクリップされます。

スタイルシートがカラー値として整数しか保持できなくても、その整数の内部保存は浮動小数点数であり、指定されたスタイルまたは計算されたスタイルで浮動小数点数として使用できます。

カラーのパーセンテージ値は常に数値に変換でき、逆も可能です。

```java
public class RGBColor : DOMObject
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getAlpha](../../com.aspose.html.dom.css/rgbcolor/alpha/) この Color 構造体のアルファ成分の値を取得します。 |
| [getBlue](../../com.aspose.html.dom.css/rgbcolor/blue/) この Color 構造体の青成分の値を取得します。 |
| [getGreen](../../com.aspose.html.dom.css/rgbcolor/green/) この Color 構造体の緑成分の値を取得します。 |
| [getRed](../../com.aspose.html.dom.css/rgbcolor/red/) この Color 構造体の赤成分の値を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [toNative](../../com.aspose.html.dom.css/rgbcolor/tonative/)() | ネイティブのカラーオブジェクトに変換します。 |

## 備考

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参照

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### 関連項目

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
