---
title: "ITrueTypeFont インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.drawing.ITrueTypeFont インターフェイス。TrueType フォントを操作するメソッドを宣言します。"
type: docs

url: /ja/java/com.aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

TrueType フォントを扱うためのメソッドを宣言します。

```java
public interface ITrueTypeFont
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getDataSize](../../com.aspose.html.drawing/itruetypefont/datasize/) フォントデータのサイズをバイト単位で返します。 |
| [getFamilyName](../../com.aspose.html.drawing/itruetypefont/familyname/) フォントファミリーの名前を取得します。 |
| [getFullFontName](../../com.aspose.html.drawing/itruetypefont/fullfontname/) これは "FamilyName" と "SubFamilyName" の組み合わせである必要があります。例外として、"SubFamilyName" に "Regular" と示されている場合は、"FamilyName" に含まれるファミリ名のみを使用します。上記の Full フォント名の定義に対する例外は、Microsoft プラットフォームの CFF OpenType フォント用文字列です。この場合、Full フォント名文字列は CFF Name INDEX の PostScript FontName と同一でなければなりません。 |
| [getSubFamilyName](../../com.aspose.html.drawing/itruetypefont/subfamilyname/) フォントサブファミリ名は、同じフォントファミリ名を持つグループ内でフォントを区別します。これはスタイル（イタリック、オブリーク）やウェイト（ライト、ボールド、ブラックなど）を示すものと想定されます。ウェイトやスタイルに特別な違いがないフォント（例：中程度のウェイトでイタリックではなく、fsSelection ビット 6 が設定されている場合）は、この位置に文字列 "Regular" が格納されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getAscent](../../com.aspose.html.drawing/itruetypefont/getascent/)(float) | 上昇部（ascent）をポイント単位で返します。 |
| [getData](../../com.aspose.html.drawing/itruetypefont/getdata/)() | フォントデータのストリームを開きます。呼び出し側がストリームの破棄を担当します。 |
| [getDescent](../../com.aspose.html.drawing/itruetypefont/getdescent/)(float) | 下降部（descent）をポイント単位で返します。 |

### 関連項目

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
