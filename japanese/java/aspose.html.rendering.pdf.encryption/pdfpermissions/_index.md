---
title: "PdfPermissions 列挙型"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.rendering.pdf.encryption.PdfPermissions 列挙型。この列挙型は PDF のユーザー権限を表します"
type: docs

url: /ja/java/com.aspose.html.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

この列挙型は PDF に対するユーザーの権限を表します。

```java
[Flags]
public enum PdfPermissions
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| PrintDocument | `4` | (リビジョン 2 のセキュリティハンドラ) ドキュメントを印刷します。(リビジョン 3 以上のセキュリティハンドラ) ドキュメントを印刷します（PrintingQuality が設定されているかどうかに応じて、最高品質でない場合があります）。 |
| ModifyContent | `8` | ModifyTextAnnotations、FillForm、および 11 によって制御される操作以外の操作でドキュメントの内容を変更します。 |
| ExtractContent | `10` | (リビジョン 2 のセキュリティハンドラ) 文書からテキストや画像をコピーまたは抽出します。テキストや画像の抽出を含みます（障害を持つユーザーへのアクセシビリティ支援やその他の目的のため）。(リビジョン 3 以上のセキュリティハンドラ) ExtractContentWithDisabilities によって制御される操作以外で文書からテキストや画像をコピーまたは抽出します。 |
| ModifyTextAnnotations | `20` | テキスト注釈を追加または変更し、インタラクティブなフォームフィールドに入力し、さらに ModifyContent が設定されている場合はインタラクティブなフォームフィールド（署名フィールドを含む）を作成または変更します。 |
| FillForm | `100` | (リビジョン 3 以上のセキュリティハンドラ) ModifyTextAnnotations がクリアされていても、既存のインタラクティブなフォームフィールド（署名フィールドを含む）に入力します。 |
| ExtractContentWithDisabilities | `200` | (リビジョン 3 以上のセキュリティハンドラ) テキストや画像を抽出します（障害を持つユーザーへのアクセシビリティ支援やその他の目的のため）。 |
| AssembleDocument | `400` | (リビジョン 3 以上のセキュリティハンドラ) ModifyContent がクリアされていても、文書を組み立てます（ページの挿入、回転、削除、ブックマークやサムネイル画像の作成）。 |
| PrintingQuality | `800` | (リビジョン 3 以上のセキュリティハンドラ) PDF コンテンツの忠実なデジタルコピーを生成できる表現に文書を印刷します。このビットがクリアされ（かつビット 3 が設定されている）場合、印刷は外観の低レベル表現に制限され、品質が低下する可能性があります。 |

### 関連項目

* package [com.aspose.html.rendering.pdf.encryption](../../com.aspose.html.rendering.pdf.encryption/)
* package [Aspose.HTML](../../)
