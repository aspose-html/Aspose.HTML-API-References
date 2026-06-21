---
title: "MarkdownSaveOptions クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.saving.MarkdownSaveOptions クラス。Markdown の保存オプションを表します。例えば、事前定義された GitLab Flavored Markdown 互換オプションを使用して Markdown の書式スタイルを設定したり、リソースの処理を構成したりできます。詳細は記事をご参照ください"
type: docs

url: /ja/java/com.aspose.html.saving/markdownsaveoptions/
---
## MarkdownSaveOptions class

Markdown 保存オプションを表します。たとえば、Markdown の書式スタイルを設定したり、事前定義された GitLab Flavored Markdown 互換オプションを使用したり、リソース処理を構成したりできます。詳細は [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options) を参照してください。

```java
public class MarkdownSaveOptions : SaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | `MarkdownSaveOptions` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [getDefault](../../com.aspose.html.saving/markdownsaveoptions/default/) は、デフォルトの Markdown ドキュメントと互換性のあるオプションセットを返します。 |
| static [getGit](../../com.aspose.html.saving/markdownsaveoptions/git/) は、GitLab Flavored Markdown と互換性のあるオプションセットを返します。 |
[getFeatures]
[setFeatures] Flag set that controls which elements are converted to markdown. |
[getFormatter]
[setFormatter] Gets or sets the markdown formatting style. |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) は、リソース処理の構成に使用される [`ResourceHandlingOptions`](../resourcehandlingoptions/) オブジェクトを取得します。 |

## 備考

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) で見つけられます。

## サンプル

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
import System.IO;
...
	 // 変換後のファイル保存用パスを準備する
      String savePath = Path.Combine(OutputDir, "options-output.md");

      // HTML コードを用意し、ファイルに保存します
      var code = "<h1>Header 1</h1>" +
            "<h2>Header 2</h2>" +
            "<p>Hello, World!!</p>" +
            "<a href='aspose.com'>aspose</a>";
      File.WriteAllText(Path.Combine(OutputDir, "options.html"), code);

      // SaveOptions のインスタンスを作成し、ルールを設定します: 
      // - <a> と <p> 要素のみが Markdown に変換されます
      var options = new MarkdownSaveOptions();
      options.Features = MarkdownFeatures.Link | MarkdownFeatures.AutomaticParagraph;

      // ConvertHTML メソッドを呼び出して、HTML を Markdown に変換します。
      Converter.ConvertHTML(Path.Combine(OutputDir, "options.html"), options, savePath);
```

### 関連項目

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
