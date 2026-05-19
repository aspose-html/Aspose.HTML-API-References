---
title: "Configuration クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.Configuration クラス。アプリケーションの環境設定を構成するために使用される構成コンテキストオブジェクトを表します。構成を管理することで、カスタムユーザースタイルシートを適用してドキュメントのスタイルを上書きしたり、アプリケーションからの Web リクエストを処理したり、スクリプトポリシーを設定したりできます。詳細は Environment Configuration ガイドにあります。"
type: docs

url: /ja/java/com.aspose.html/configuration/
---
## Configuration class

構成コンテキストオブジェクトは、アプリケーションの環境設定を設定するために使用されます。構成を管理することで、カスタムユーザースタイルシートを適用してドキュメントのスタイルを上書きしたり、アプリケーションからの Web リクエストを処理したり、スクリプトポリシーを設定したりできます。詳細は [Environment Configuration guide](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/) にあります。

```java
public class Configuration : IDisposable, IServiceProvider
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Configuration](configuration/)() | `class` の新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
[getSecurity]
[setSecurity] Gets or sets the sandboxing flag of the configuration. Refer to article about [sandboxing](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/#sandboxing). |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [Create](../../com.aspose.html/configuration/create/#create)() | Configuration オブジェクトのインスタンスを作成し、構成します。 |
| static [Create](../../com.aspose.html/configuration/create/#create_1)(Action&lt;IConfigurationBuilder&gt;) | Configuration オブジェクトのインスタンスを作成し、構成します。 |
| [dispose](../../com.aspose.html/configuration/dispose/)() | アンマネージドリソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| [getService](../../com.aspose.html/configuration/getservice/#getservice)(Type) | 要求されたサービスを取得します。 |
| [GetService&lt;T&gt;](../../com.aspose.html/configuration/getservice/#getservice_1)() | 要求されたサービスを取得します。 |

## Remarks

完全なサンプルとデータファイルは[GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)からダウンロードできます。

## 例

```java
import System;
import System.Diagnostics;
import System.IO;
import Aspose.Html;
import com.aspose.html.net;
import com.aspose.html.services;

    // このメッセージハンドラは、リクエストの開始と終了の処理に関するメッセージを出力します。
    public class LogMessageHandler : MessageHandler
    {
      // Invoke() メソッドをオーバーライドします
      public void Invoke(INetworkOperationContext context)
      {
        Debug.WriteLine("Start processing request: " + context.Request.RequestUri);

        // チェーン内の次のメッセージハンドラを呼び出します
        Next(context);

        Debug.WriteLine("Finish processing request: " + context.Request.RequestUri);
      }
    }
```

```java
    public void CreateACustomMessageHandlerTest()
    {
      // Configuration クラスのインスタンスを作成する
      using var configuration = new Configuration();

      // 既存のメッセージハンドラのチェーンに LogMessageHandler を追加する
      var service = configuration.GetService<INetworkService>();
      var handlers = service.MessageHandlers;
           
      handlers.Insert(0, new LogMessageHandler());

      // ソース文書ファイルへのパスを準備する
      String documentPath = Path.Combine(DataDir, "input.htm");

      // 指定された構成で HTML ドキュメントを初期化する
      using var document = new HTMLDocument(documentPath, configuration);
    }
```

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.net;
import com.aspose.html.saving;
import com.aspose.html.services;
import System;
import System.Collections.Generic;
import System.IO;
import System.Net;
import System.Text;

public void SandboxingSample()
    {
      // HTML コードを準備し、ファイルに保存します
      var code = "<span>Hello World!!</span> " +
            "<script>document.write('Have a nice day!');</script>";

      File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

      // Configuration のインスタンスを作成する
      using (var configuration = new Configuration())
      {
        // 'scripts' を信頼できないリソースとしてマークする
        configuration.Security |= Sandbox.Scripts;

        // 指定された構成で HTML ドキュメントを初期化する
        using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
        {
          // HTML を PDF に変換
          Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
        }
      }       
    }
```

*OutputDir - user output folder path.

### 関連項目

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
