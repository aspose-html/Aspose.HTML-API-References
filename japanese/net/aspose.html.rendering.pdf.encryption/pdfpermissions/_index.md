---
title: Enum PdfPermissions
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Rendering.Pdf.Encryption.PdfPermissions 列挙. この列挙型はPDF に対するユーザーの権限を表します
type: docs
weight: 4420
url: /ja/net/aspose.html.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

この列挙型は、PDF に対するユーザーの権限を表します。

```csharp
[Flags]
public enum PdfPermissions
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| PrintDocument | `4` | (リビジョン 2 のセキュリティ ハンドラ) ドキュメントを印刷します。 (リビジョン 3 以上のセキュリティ ハンドラ) ドキュメントを印刷します (PrintingQuality も設定されているかどうかによっては、最高の品質レベルではない可能性があります)。 |
| ModifyContent | `8` | ModifyTextAnnotations、FillForm、および 11. によって制御される操作以外の操作によってドキュメントの内容を変更します。 |
| ExtractContent | `10` | リビジョン 2 のセキュリティ ハンドラ (障害のあるユーザーへのアクセシビリティをサポートするため、またはその他の目的で) テキストとグラフィックスの抽出を含む、ドキュメントからテキストとグラフィックスをコピーまたは抽出します。 (リビジョン 3 以降のセキュリティ ハンドラ) コピーまたは、 ExtractContentWithDisabilities. によって制御される操作以外の操作によって、ドキュメントからテキストとグラフィックを抽出します。 |
| ModifyTextAnnotations | `20` | テキスト注釈を追加または変更し、インタラクティブ フォーム フィールドに入力します。ModifyContent も設定されている場合は、インタラクティブ フォーム フィールド (署名フィールドを含む) を作成または変更します。 |
| FillForm | `100` | (リビジョン 3 以上のセキュリティ ハンドラー) ModifyTextAnnotations がクリアであっても、既存のインタラクティブ フォーム フィールド (署名フィールドを含む) に入力します。 |
| ExtractContentWithDisabilities | `200` | (リビジョン 3 以降のセキュリティ ハンドラー) テキストとグラフィックを抽出します (障害を持つユーザーのアクセシビリティをサポートするため、またはその他の目的で)。 |
| AssembleDocument | `400` | (リビジョン 3 以上のセキュリティ ハンドラー) ドキュメントを組み立てます (ページの挿入、回転、または削除、ブックマークまたはサムネイル イメージの作成)。 |
| PrintingQuality | `800` | (リビジョン 3 以上のセキュリティ ハンドラー) PDF コンテンツの忠実なデジタル コピーを生成できる表現でドキュメントを印刷します。 -外観のレベル表現、おそらく品質が低下しています. |

### 関連項目

* 名前空間 [Aspose.Html.Rendering.Pdf.Encryption](../../aspose.html.rendering.pdf.encryption/)
* 組み立て [Aspose.HTML](../../)


