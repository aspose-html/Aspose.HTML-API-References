---
title: "MHTMLSaveOptions クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.saving.MHTMLSaveOptions クラス。MHTML の保存オプションを表します。特定のプロパティを設定することで、最大処理深度などのリソース処理を管理できます。詳細はドキュメント記事をご覧ください。"
type: docs

url: /ja/java/com.aspose.html.saving/mhtmlsaveoptions/
---
## MHTMLSaveOptions class

MHTML 保存オプションを表します。特定のプロパティを設定することで、最大処理深度などのリソース処理を管理できます。詳細はドキュメントの [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options) をご覧ください。

```java
public class MHTMLSaveOptions : SaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MHTMLSaveOptions](mhtmlsaveoptions/)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getResourceHandlingOptions](../../com.aspose.html.saving/saveoptions/resourcehandlingoptions/) リソース処理の構成に使用される [`ResourceHandlingOptions`](../resourcehandlingoptions/) オブジェクトを取得します。 |

## Remarks

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) で見つけることができます。

## 例

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
import System.IO;
...
	 // 別のファイルへのリンクを含む HTML コードを作成し、'document.html' としてファイルに保存します
      var code = "<span>Hello, World!!</span> " +
            "<a href='document2.html'>click</a>";
      File.WriteAllText("document.html", code);

      // HTML コードを作成し、'document2.html' としてファイルに保存します
      code = @"<span>Hello, World!!</span>";
      File.WriteAllText("document2.html", code);
       
      String savePath = Path.Combine(OutputDir, "output-options.mht");

      // 直接リンクされたリソースを持つドキュメントを変換するために、リソースリンク深度の値を 1 に変更します
      var options = new MHTMLSaveOptions()
      {
        ResourceHandlingOptions =
        {
          MaxHandlingDepth = 1
        }
      };

      // HTML を MHTML に変換
      Converter.ConvertHTML("document.html", options, savePath);  
```

### 関連項目

* class [SaveOptions](../saveoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
