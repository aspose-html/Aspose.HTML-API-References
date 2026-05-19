---
title: "HTMLSaveOptions クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.saving.HTMLSaveOptions クラス。HTML保存オプションを表します。特定のプロパティを設定することで、最大処理深度などのリソース処理を管理できます。詳細はドキュメント記事をご覧ください。"
type: docs

url: /ja/java/com.aspose.html.saving/htmlsaveoptions/
---
## HTMLSaveOptions class

HTML 保存オプションを表します。特定のプロパティを設定することで、最大処理深度などのリソース処理を管理できます。詳細はドキュメントの [article](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) をご覧ください。

```java
public class HTMLSaveOptions : SaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [HTMLSaveOptions](htmlsaveoptions/)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
[getDocumentType]
[setDocumentType] Gets or sets the output document type. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) リソース処理の構成に使用される [`ResourceHandlingOptions`](../resourcehandlingoptions/) オブジェクトを取得します。 |
[getSerializeInputValue]
[setSerializeInputValue] This option controls whether to serialize the value of the [`HTMLInputElement`](../../com.aspose.html/htmlinputelement/)'s or the [`HTMLTextAreaElement`](../../com.aspose.html/htmltextareaelement/)'s "value" property into the "value" attribute. |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [AUTO](../../com.aspose.html.saving/htmlsaveoptions/auto/) | 出力ドキュメントのタイプは自動的に選択されます。 |
| const [HTML](../../com.aspose.html.saving/htmlsaveoptions/html/) | ドキュメントはHTMLとして保存されます。 |
| const [XHTML](../../com.aspose.html.saving/htmlsaveoptions/xhtml/) | ドキュメントはXHTMLとして保存されます。 |

## Remarks

完全なサンプルとデータファイルは[GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)からダウンロードできます。

## 例

```java
import Aspose.Html;
import com.aspose.html.dom.svg;
import com.aspose.html.saving;
import System;
...
     // HTMLドキュメントの出力パスを準備します。
      String documentPath = Path.Combine(OutputDir, "save-with-linked-file.html");

      // リンクされたドキュメントを含むシンプルなHTMLファイルを準備します。
      File.WriteAllText(documentPath, "<p>Hello World!</p>" +
                      "<a href='linked.html'>linked file</a>");

      // シンプルなリンクHTMLファイルを準備します。
      File.WriteAllText(Path.Combine(OutputDir, "linked.html"), "<p>Hello linked file!</p>");

      // "save-with-linked-file.html" をメモリにロードします。
      using (var document = new HTMLDocument(documentPath))
      {
        // 保存オプションのインスタンスを作成します。
        var options = new HTMLSaveOptions();

        // 値が '0' の以下の行は、このインスタンスを保存する際に他のすべてのリンクされた HTML ファイルを切り離します
        // この行を削除するか、値を '1' に変更すると、'linked.html' ファイルも出力フォルダーに保存されます
        options.ResourceHandlingOptions.MaxHandlingDepth = 1;

        // 保存オプションを使用してドキュメントを保存します
        document.Save(Path.Combine(OutputDir, "save-with-linked-file_out.html"), options);
      }
```

*OutputDir - user output folder.

### 関連項目

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
