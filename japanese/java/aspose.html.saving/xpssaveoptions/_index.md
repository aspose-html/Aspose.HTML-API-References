---
title: "XpsSaveOptions クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.saving.XpsSaveOptions クラス。特定のオプションデータクラスで、変換結果を管理するためのいくつかのプロパティを提供します。例えば PageSetup はページの特性を指定します。ドキュメント記事を参照してください"
type: docs

url: /ja/java/com.aspose.html.saving/xpssaveoptions/
---
## XpsSaveOptions class

特定のオプションデータクラスは、変換結果を管理するためのいくつかのプロパティを提供します。例えば [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) はページの特性を指定します。ドキュメントの [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#save-options) を参照してください。

```java
public class XpsSaveOptions : XpsRenderingOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions/)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) は、css プロパティ処理の構成に使用される [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) オブジェクトを取得します。 |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | 内部画像（フィルタ処理中に使用される）の水平解像度を設定または取得します。単位はインチあたりピクセルです。デフォルトではこのプロパティは 300 dpi です。 |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) は、出力ページ設定の構成に使用されるページ設定オブジェクトを取得します。 |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | 内部画像（フィルタ処理中に使用される）の垂直解像度を設定または取得します。単位はインチあたりピクセルです。デフォルトではこのプロパティは 300 dpi です。 |

## Remarks

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) で見つけることができます。

## 例

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
...
	  String documentPath = Path.Combine(OutputDir, "save-options.html");
      String savePath = Path.Combine(OutputDir, "save-options-output.xps");

      // HTML コードを準備し、ファイルに保存します
      var code = "<h1> XpsSaveOptions Class</h1>\r\n" +
            "<p>Using XpsSaveOptions Class, you can programmatically apply a wide range of conversion parameters such as BackgroundColor, PageSetup, etc.</p>\r\n";

      File.WriteAllText(documentPath, code);

      // HTML ファイルから HTML ドキュメントを初期化します
      using var document = new HTMLDocument(documentPath);
       
      // ページサイズと余白を設定し、背景色を AntiqueWhite に変更します
      var options = new XpsSaveOptions()
      {
        BackgroundColor = Color.AntiqueWhite
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(Length.FromInches(4.9f), Length.FromInches(3.5f)), new Margin(30, 20, 10, 10));

      // HTML を XPS に変換する
      Converter.ConvertHTML(document, options, savePath); 
```

### 関連項目

* class [XpsRenderingOptions](../../com.aspose.html.rendering.xps/xpsrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
