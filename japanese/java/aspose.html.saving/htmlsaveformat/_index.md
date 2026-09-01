---
title: "HTMLSaveFormat 列挙型"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.saving.HTMLSaveFormat 列挙型。ドキュメントが保存される形式を指定します。HTMLDocument の保存に関する詳細情報は記事で確認できます"
type: docs

url: /ja/java/com.aspose.html.saving/htmlsaveformat/
---
## HTMLSaveFormat enumeration

ドキュメントが保存される形式を指定します。[`HTMLDocument`](../../com.aspose.html/htmldocument/) の保存に関する詳細情報は[記事](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/)で確認できます。

```java
public enum HTMLSaveFormat
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Original | `0` | ドキュメントは元の形式で保存されます。 |
| Markdown | `1` | ドキュメントは Markdown として保存されます。 |
| MHTML | `2` | ドキュメントは MHTML として保存されます。 |

## 備考

完全なサンプルとデータファイルは[GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)からダウンロードできます。

## サンプル

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
  // ドキュメント保存のための出力パスを準備します
  String documentPath = Path.Combine(OutputDir, "save-to-MD.md");

  // HTML コードを準備します
  var html_code = "<H2>Hello World!</H2>";
   
  // String 変数からドキュメントを初期化します
  using (var document = new HTMLDocument(html_code, "."))
  {
    // ドキュメントを Markdown ファイルとして保存します
    document.Save(documentPath, HTMLSaveFormat.Markdown);
  }
```

*OutputDir - user output folder path.

### 関連項目

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
