---
title: Interface ITrueTypeFont
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Drawing.ITrueTypeFont インターフェース. TrueType フォントを操作するためのメソッドを宣言します
type: docs
weight: 2760
url: /ja/net/aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

TrueType フォントを操作するためのメソッドを宣言します。

```csharp
public interface ITrueTypeFont
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DataSize](../../aspose.html.drawing/itruetypefont/datasize/) { get; } | フォント データのサイズをバイト単位で返します |
| [FamilyName](../../aspose.html.drawing/itruetypefont/familyname/) { get; } | フォント ファミリーの名前を取得します。 |
| [FullFontName](../../aspose.html.drawing/itruetypefont/fullfontname/) { get; } | これは、「FamilyName」と「SubFamilyName」の組み合わせである必要があります。例外: "SubFamilyName" で と示されているように、フォントが "Regular" の場合は、"FamilyName" に含まれる姓のみを使用してください。 上記の完全なフォント名の定義の例外は、CFF OpenType フォントの Microsoft プラットフォーム文字列 です。この場合、完全なフォント名の文字列は、CFF 名 INDEX. の PostScript FontName と同一である必要があります。 |
| [SubFamilyName](../../aspose.html.drawing/itruetypefont/subfamilyname/) { get; } | フォント サブファミリ名は、同じフォント ファミリ名を持つグループ内のフォントを区別します。 これは、スタイル (イタリック、斜体) と太さ (ライト、ボールド、黒など) に対応するものと見なされます。 太さやスタイルに特別な違いがないフォント (例: 太さが中程度、イタリックではなく、fsSelection ビット 6 が設定されている) は、この位置に文字列 "Regular" を格納する必要があります。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetAscent](../../aspose.html.drawing/itruetypefont/getascent/)(float) | 上昇をポイントで返します. |
| [GetData](../../aspose.html.drawing/itruetypefont/getdata/)() | フォント データでストリームを開きます。呼び出し元は、ストリームを破棄する責任があります. |
| [GetDescent](../../aspose.html.drawing/itruetypefont/getdescent/)(float) | 降下をポイントで返します. |

### 関連項目

* 名前空間 [Aspose.Html.Drawing](../../aspose.html.drawing/)
* 組み立て [Aspose.HTML](../../)


