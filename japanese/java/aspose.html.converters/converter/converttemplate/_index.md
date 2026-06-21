---
title: "Converter.ConvertTemplate"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Converter メソッド。HTMLDocument で提供されるテンプレートソースとテンプレートデータ（XML、JSON）をマージします。結果は出力ファイルパスで生成された HTML ファイルです。"
type: docs

url: /ja/java/com.aspose.html.converters/converter/converttemplate/
---
## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions, String) {#converttemplate_7}

[`HTMLDocument`](../../../com.aspose.html/htmldocument/) で提供されるテンプレートソースとテンプレートデータ（XML、JSON）をマージします。結果は出力ファイルパスで生成された HTML ファイルです。

```java
public static void ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| template | HTMLDocument | [`HTMLDocument`](../../../com.aspose.html/htmldocument/) で提供されるソーススケルトンをマージしています。 |
| データ | TemplateData | マージ用テンプレートデータ - 置換 (XML、JSON)。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) オブジェクト インスタンス。テンプレートとデータ項目の名前が大文字小文字を区別せずに一致するかどうかを判断するために使用されます（オプション）。 |
| outputPath | 文字列 | 出力変換結果としての完全な HTML ファイルパス。 |

## 備考

テンプレートマージャー

テンプレートマージの考え方は、HTML テンプレートに基づいて HTML ドキュメントを作成し、データ ソースから内容を埋め込むことです。Aspose.HTML は、XML や JSON などのさまざまなデータ ソースタイプとテンプレートで使用できるインライン式構文を提供します。テンプレートマージおよび ConvertTemplate() メソッドの使用に関する詳細情報は、[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) を参照してください。

変換（マージ）手順

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

テンプレート ソース。ファイル、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) オブジェクト インスタンス、またはインライン コンテンツで HTML テンプレート ソースを定義します。変換結果。メソッド署名に応じて、結果の HTMLDocument を直接取得するか、出力ファイル パスを指定できます。[`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) のインスタンスを作成します。Converter クラスの ConvertTemplate() メソッドを使用してテンプレートとデータをマージします。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォーム スケルトン HTML ソース ファイル パス
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // フォーム XML（JSON）テンプレート データ ファイル パス
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");
      
      // TemplateData オブジェクト インスタンスを定義する
      var templateData = new TemplateData(templateDataPath);

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // デフォルトの TemplateLoadOptions オブジェクトを定義する
      var options = new TemplateLoadOptions();

      // HTML ドキュメントを変換ソースとして設定する
      var document = new HTMLDocument(sourcePath, new Configuration());

      // 変換プロセスを開始する
      Converter.ConvertTemplate(document, templateData, options, resultPath);

      // リソースをクリアする
      document.Dispose();





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions, String) {#converttemplate_9}

[`URL`](../../../com.aspose.html/url/) で提示されたテンプレート HTML ソースをテンプレート データ（XML、JSON）とマージします。結果は出力ファイル パスで作成された HTML ファイルです。

```java
public static void ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options, 
    String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | Url | [`URL`](../../../com.aspose.html/url/) で提示された HTML ソース スケルトンをマージします。 |
| データ | TemplateData | マージ用テンプレートデータ - 置換 (XML、JSON)。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) オブジェクト インスタンス。テンプレートとデータ項目の名前が大文字小文字を区別せずに一致するかどうかを判断するために使用されます（オプション）。 |
| outputPath | 文字列 | 出力変換結果としての完全な HTML ファイルパス。 |

## 備考

テンプレートマージャー

テンプレートマージの考え方は、HTML テンプレートに基づいて HTML ドキュメントを作成し、データ ソースから内容を埋め込むことです。Aspose.HTML は、XML や JSON などのさまざまなデータ ソースタイプとテンプレートで使用できるインライン式構文を提供します。テンプレートマージおよび ConvertTemplate() メソッドの使用に関する詳細情報は、[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) を参照してください。

変換（マージ）手順

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

テンプレート ソース。ファイル、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) オブジェクト インスタンス、またはインライン コンテンツで HTML テンプレート ソースを定義します。変換結果。メソッド署名に応じて、結果の HTMLDocument を直接取得するか、出力ファイル パスを指定できます。[`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) のインスタンスを作成します。Converter クラスの ConvertTemplate() メソッドを使用してテンプレートとデータをマージします。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // スケルトン HTML ソース URL を設定する
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // フォーム XML（JSON）テンプレート データ ファイル パス
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData オブジェクト インスタンスを定義する
      var templateData = new TemplateData(templateDataPath);

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // デフォルトの TemplateLoadOptions オブジェクトを定義する
      var options = new TemplateLoadOptions();

      // 変換プロセスを開始する
      Converter.ConvertTemplate(sourceUrl, templateData, options, resultPath);





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_8}

[`URL`](../../../com.aspose.html/url/) で提示されたテンプレート HTML ソースをテンプレート データ（XML、JSON）とマージします。結果は出力ファイル パスで作成された HTML ファイルです。

```java
public static void ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | Url | [`URL`](../../../com.aspose.html/url/) で提示された HTML ソース スケルトンをマージします。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| データ | TemplateData | マージ用テンプレートデータ - 置換 (XML、JSON)。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) オブジェクト インスタンス。テンプレートとデータ項目の名前が大文字小文字を区別せずに一致するかどうかを判断するために使用されます（オプション）。 |
| outputPath | 文字列 | 出力変換結果としての完全な HTML ファイルパス。 |

## 備考

テンプレートマージャー

テンプレートマージの考え方は、HTML テンプレートに基づいて HTML ドキュメントを作成し、データ ソースから内容を埋め込むことです。Aspose.HTML は、XML や JSON などのさまざまなデータ ソースタイプとテンプレートで使用できるインライン式構文を提供します。テンプレートマージおよび ConvertTemplate() メソッドの使用に関する詳細情報は、[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) を参照してください。

変換（マージ）手順

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

テンプレート ソース。ファイル、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) オブジェクト インスタンス、またはインライン コンテンツで HTML テンプレート ソースを定義します。変換結果。メソッド署名に応じて、結果の HTMLDocument を直接取得するか、出力ファイル パスを指定できます。[`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) のインスタンスを作成します。Converter クラスの ConvertTemplate() メソッドを使用してテンプレートとデータをマージします。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // スケルトン HTML ソース URL を設定する
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // フォーム XML（JSON）テンプレート データ ファイル パス
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData オブジェクト インスタンスを定義する
      var templateData = new TemplateData(templateDataPath);

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // デフォルトの TemplateLoadOptions オブジェクトを定義する
      var options = new TemplateLoadOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions, String) {#converttemplate_11}

フルファイルパスで提示されたテンプレートHTMLソースをテンプレートデータ（XML、JSON）とマージします。結果は出力ファイルパスで作成されたhtmlファイルです。

```java
public static void ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | 完全なファイル パスで提示された HTML ソース スケルトンをマージします。 |
| データ | TemplateData | マージ用テンプレートデータ - 置換 (XML、JSON)。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) オブジェクト インスタンス。テンプレートとデータ項目の名前が大文字小文字を区別せずに一致するかどうかを判断するために使用されます（オプション）。 |
| outputPath | 文字列 | 出力変換結果としての完全な HTML ファイルパス。 |

## 備考

テンプレートマージャー

テンプレートマージの考え方は、HTML テンプレートに基づいて HTML ドキュメントを作成し、データ ソースから内容を埋め込むことです。Aspose.HTML は、XML や JSON などのさまざまなデータ ソースタイプとテンプレートで使用できるインライン式構文を提供します。テンプレートマージおよび ConvertTemplate() メソッドの使用に関する詳細情報は、[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) を参照してください。

変換（マージ）手順

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

テンプレート ソース。ファイル、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) オブジェクト インスタンス、またはインライン コンテンツで HTML テンプレート ソースを定義します。変換結果。メソッド署名に応じて、結果の HTMLDocument を直接取得するか、出力ファイル パスを指定できます。[`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) のインスタンスを作成します。Converter クラスの ConvertTemplate() メソッドを使用してテンプレートとデータをマージします。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォーム スケルトン HTML ソース ファイル パス
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // フォーム XML（JSON）テンプレート データ ファイル パス
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData オブジェクト インスタンスを定義する
      var templateData = new TemplateData(templateDataPath);

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // デフォルトの TemplateLoadOptions オブジェクトを定義する
      var options = new TemplateLoadOptions();

      // 変換プロセスを開始する
      Converter.ConvertTemplate(sourcePath, templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 関連項目

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_10}

フルファイルパスで提示されたテンプレートHTMLソースをテンプレートデータ（XML、JSON）とマージします。結果は出力ファイルパスで作成されたhtmlファイルです。

```java
public static void ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | 完全なファイル パスで提示された HTML ソース スケルトンをマージします。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| データ | TemplateData | マージ用テンプレートデータ - 置換 (XML、JSON)。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) オブジェクト インスタンス。テンプレートとデータ項目の名前が大文字小文字を区別せずに一致するかどうかを判断するために使用されます（オプション）。 |
| outputPath | 文字列 | 出力変換結果としての完全な HTML ファイルパス。 |

## 備考

テンプレートマージャー

テンプレートマージの考え方は、HTML テンプレートに基づいて HTML ドキュメントを作成し、データ ソースから内容を埋め込むことです。Aspose.HTML は、XML や JSON などのさまざまなデータ ソースタイプとテンプレートで使用できるインライン式構文を提供します。テンプレートマージおよび ConvertTemplate() メソッドの使用に関する詳細情報は、[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) を参照してください。

変換（マージ）手順

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

テンプレート ソース。ファイル、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) オブジェクト インスタンス、またはインライン コンテンツで HTML テンプレート ソースを定義します。変換結果。メソッド署名に応じて、結果の HTMLDocument を直接取得するか、出力ファイル パスを指定できます。[`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) のインスタンスを作成します。Converter クラスの ConvertTemplate() メソッドを使用してテンプレートとデータをマージします。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォーム スケルトン HTML ソース ファイル パス
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // フォーム XML（JSON）テンプレート データ ファイル パス
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData オブジェクト インスタンスを定義する
      var templateData = new TemplateData(templateDataPath);

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // デフォルトの TemplateLoadOptions オブジェクトを定義する
      var options = new TemplateLoadOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options, resultPath);
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions, String) {#converttemplate_13}

インラインコンテンツで提示されたテンプレートHTMLソースをテンプレートデータ（XML、JSON）とマージします。結果は出力ファイルパスで作成されたhtmlファイルです。

```java
public static void ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン文字列コンテンツで提示された HTML ソース スケルトンをマージします。 |
| baseUrl | 文字列 | HTML テンプレートのベース URI。現在のディレクトリ パスと結合され、絶対 URL が形成されます。 |
| データ | TemplateData | マージ用テンプレートデータ - 置換 (XML、JSON)。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) オブジェクト インスタンス。テンプレートとデータ項目の名前が大文字小文字を区別せずに一致するかどうかを判断するために使用されます（オプション）。 |
| outputPath | 文字列 | 出力変換結果としての完全な HTML ファイルパス。 |

## 備考

テンプレートマージャー

テンプレートマージの考え方は、HTML テンプレートに基づいて HTML ドキュメントを作成し、データ ソースから内容を埋め込むことです。Aspose.HTML は、XML や JSON などのさまざまなデータ ソースタイプとテンプレートで使用できるインライン式構文を提供します。テンプレートマージおよび ConvertTemplate() メソッドの使用に関する詳細情報は、[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) を参照してください。

変換（マージ）手順

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

テンプレート ソース。ファイル、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) オブジェクト インスタンス、またはインライン コンテンツで HTML テンプレート ソースを定義します。変換結果。メソッド署名に応じて、結果の HTMLDocument を直接取得するか、出力ファイル パスを指定できます。[`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) のインスタンスを作成します。Converter クラスの ConvertTemplate() メソッドを使用してテンプレートとデータをマージします。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
	  // インライン ソース コンテンツをテンプレートとして設定する
      String templateContent =
        "<html>" + 
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";
       
      // フォーム XML（JSON）テンプレート データ ファイル パス
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData オブジェクト インスタンスを定義する
      var templateData = new TemplateData(templateDataPath);

      // マージ結果として出力を設定する
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // デフォルトの TemplateLoadOptions オブジェクトを定義する
      var options = new TemplateLoadOptions();
	  
      // 変換プロセスを開始する
      Converter.ConvertTemplate(templateContent, String.Empty, templateData, options, resultFilePath);

*TemplateFolder - user template data folder.
*OutputFolder - user output file path.

Below is sample data file to merge with source

<?xml version="1.0" encoding="utf-8" ?>
<Data>
	<Person>
	<Title>Title 1</Title>
	<Name>John</Name>
	<Surname>Smith</Surname>
	<Address>
		<Number>200</Number>
		<Street>Austin rd.</Street>
		<City>Dallas</City>
	</Address>
	</Person>
	<Person>
	<Title>Title 2</Title>
	<Name>Mike</Name>
	<Surname>Milbert</Surname>
	<Address>
		<Number>126</Number>
		<Street>First Avenue</Street>
		<City>Chicago</City>
	</Address>
	</Person>
</Data>
```

### 関連項目

* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions, String) {#converttemplate_12}

インラインコンテンツで提示されたテンプレートHTMLソースをテンプレートデータ（XML、JSON）とマージします。結果は出力ファイルパスで作成されたhtmlファイルです。

```java
public static void ConvertTemplate(String content, String baseUrl, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン文字列コンテンツで提示された HTML ソース スケルトンをマージします。 |
| baseUrl | 文字列 | HTML テンプレートのベース URI。現在のディレクトリ パスと結合され、絶対 URL が形成されます。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| データ | TemplateData | マージ用テンプレートデータ - 置換 (XML、JSON)。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) オブジェクト インスタンス。テンプレートとデータ項目の名前が大文字小文字を区別せずに一致するかどうかを判断するために使用されます（オプション）。 |
| outputPath | 文字列 | 出力変換結果としての完全な HTML ファイルパス。 |

## 備考

テンプレートマージャー

テンプレートマージの考え方は、HTML テンプレートに基づいて HTML ドキュメントを作成し、データ ソースから内容を埋め込むことです。Aspose.HTML は、XML や JSON などのさまざまなデータ ソースタイプとテンプレートで使用できるインライン式構文を提供します。テンプレートマージおよび ConvertTemplate() メソッドの使用に関する詳細情報は、[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) を参照してください。

変換（マージ）手順

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

テンプレート ソース。ファイル、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) オブジェクト インスタンス、またはインライン コンテンツで HTML テンプレート ソースを定義します。変換結果。メソッド署名に応じて、結果の HTMLDocument を直接取得するか、出力ファイル パスを指定できます。[`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) のインスタンスを作成します。Converter クラスの ConvertTemplate() メソッドを使用してテンプレートとデータをマージします。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
   // インライン ソース コンテンツをテンプレートとして設定する
   String templateContent =
    "<html>" + 
    "<body>" +
    "<div data_merge=\"{{#foreach Person}}\">" +
    "<p>{{Title}}</p>" +
    "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
    "<p>Address:</p>" +
    "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
    "</div>" +
    "</body></html>";
    
   // フォーム XML（JSON）テンプレート データ ファイル パス
   var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

   // TemplateData オブジェクト インスタンスを定義する
   var templateData = new TemplateData(templateDataPath);

   // マージ結果として出力を設定する
   var resultFilePath = Path.Combine(OutputFolder, "result.html");

   // configuration オブジェクト インスタンスを定義する
   var configuration = new Configuration();

   // デフォルトの TemplateLoadOptions オブジェクトを定義する
   var options = new TemplateLoadOptions();

   // デフォルト構成で変換プロセスを開始する
   Converter.ConvertTemplate(templateContent, String.Empty,
        configuration, templateData, options, resultFilePath);
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

以下は、ソースをテンプレートとしてマージするためのデータファイルです

```java
<?xml version="1.0" encoding="utf-8" ?>
<Data>
	<Person>
	<Title>Title 1</Title>
	<Name>John</Name>
	<Surname>Smith</Surname>
	<Address>
		<Number>200</Number>
		<Street>Austin rd.</Street>
		<City>Dallas</City>
	</Address>
	</Person>
	<Person>
	<Title>Title 2</Title>
	<Name>Mike</Name>
	<Surname>Milbert</Surname>
	<Address>
		<Number>126</Number>
		<Street>First Avenue</Street>
		<City>Chicago</City>
	</Address>
	</Person>
</Data>
```

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(HTMLDocument, TemplateData, TemplateLoadOptions) {#converttemplate}

[`HTMLDocument`](../../../com.aspose.html/htmldocument/) で提示されたテンプレートソースをテンプレートデータ (XML、JSON) とマージします。結果は新しく作成された HTMLDocument で、ファイルとして保存できます。

```java
public static HTMLDocument ConvertTemplate(HTMLDocument template, TemplateData data, 
    TemplateLoadOptions options)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| template | HTMLDocument | [`HTMLDocument`](../../../com.aspose.html/htmldocument/) で提供されるソーススケルトンをマージしています。 |
| データ | TemplateData | マージ用テンプレートデータ - 置換 (XML、JSON)。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) オブジェクト インスタンス。テンプレートとデータ項目の名前が大文字小文字を区別せずに一致するかどうかを判断するために使用されます（オプション）。 |

### 戻り値

変換結果として新しく生成された [`HTMLDocument`](../../../com.aspose.html/htmldocument/) は、出力ファイルパスを通じて保存できます。

## 備考

テンプレートマージャー

テンプレートマージの考え方は、HTML テンプレートに基づいて HTML ドキュメントを作成し、データ ソースから内容を埋め込むことです。Aspose.HTML は、XML や JSON などのさまざまなデータ ソースタイプとテンプレートで使用できるインライン式構文を提供します。テンプレートマージおよび ConvertTemplate() メソッドの使用に関する詳細情報は、[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) を参照してください。

変換（マージ）手順

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

テンプレート ソース。ファイル、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) オブジェクト インスタンス、またはインライン コンテンツで HTML テンプレート ソースを定義します。変換結果。メソッド署名に応じて、結果の HTMLDocument を直接取得するか、出力ファイル パスを指定できます。[`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) のインスタンスを作成します。Converter クラスの ConvertTemplate() メソッドを使用してテンプレートとデータをマージします。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォーム スケルトン HTML ソース ファイル パス
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // フォーム XML（JSON）テンプレート データ ファイル パス
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData オブジェクト インスタンスを定義する
      var templateData = new TemplateData(templateDataPath);

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // デフォルトの TemplateLoadOptions オブジェクトを定義する
      var options = new TemplateLoadOptions();
      
      // HTML ドキュメントを変換ソースとして設定する
      using (var template = new HTMLDocument(sourcePath, new Configuration()))
      {
        // 変換プロセスを開始する
        var document = Converter.ConvertTemplate(template, templateData, options);
         
        // リンクされたリソースとともに結果を保存する
        document.Save(new Url(resultPath));
      }





*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

```

*OutputFolder - user output file path.

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, TemplateData, TemplateLoadOptions) {#converttemplate_2}

[`URL`](../../../com.aspose.html/url/) で提示されたテンプレート HTML ソースをテンプレートデータ (XML、JSON) とマージします。結果は新しく作成された [`HTMLDocument`](../../../com.aspose.html/htmldocument/) で、ファイルとして保存できます。

```java
public static HTMLDocument ConvertTemplate(Url url, TemplateData data, TemplateLoadOptions options)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | Url | [`URL`](../../../com.aspose.html/url/) で提示された HTML ソース スケルトンをマージします。 |
| データ | TemplateData | マージ用テンプレートデータ - 置換 (XML、JSON)。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) オブジェクト インスタンス。テンプレートとデータ項目の名前が大文字小文字を区別せずに一致するかどうかを判断するために使用されます（オプション）。 |

### 戻り値

変換結果として新しく生成された [`HTMLDocument`](../../../com.aspose.html/htmldocument/) は、出力ファイルパスを通じて保存できます。

## 備考

テンプレートマージャー

テンプレートマージの考え方は、HTML テンプレートに基づいて HTML ドキュメントを作成し、データ ソースから内容を埋め込むことです。Aspose.HTML は、XML や JSON などのさまざまなデータ ソースタイプとテンプレートで使用できるインライン式構文を提供します。テンプレートマージおよび ConvertTemplate() メソッドの使用に関する詳細情報は、[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) を参照してください。

変換（マージ）手順

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

テンプレート ソース。ファイル、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) オブジェクト インスタンス、またはインライン コンテンツで HTML テンプレート ソースを定義します。変換結果。メソッド署名に応じて、結果の HTMLDocument を直接取得するか、出力ファイル パスを指定できます。[`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) のインスタンスを作成します。Converter クラスの ConvertTemplate() メソッドを使用してテンプレートとデータをマージします。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL を骨格 HTML ソースファイルに変換する
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // フォーム XML（JSON）テンプレート データ ファイル パス
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData オブジェクト インスタンスを定義する
      var templateData = new TemplateData(templateDataPath);

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // デフォルトの TemplateLoadOptions オブジェクトを定義する
      var options = new TemplateLoadOptions();

      // 変換プロセスを開始する
      using (var document = Converter.ConvertTemplate(sourceUrl, templateData, options))
      {
        // リンクされたリソースとともに結果を保存する
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(Url, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_1}

[`URL`](../../../com.aspose.html/url/) で提示されたテンプレート HTML ソースをテンプレートデータ (XML、JSON) とマージします。結果は新しく作成された [`HTMLDocument`](../../../com.aspose.html/htmldocument/) で、ファイルとして保存できます。

```java
public static HTMLDocument ConvertTemplate(Url url, Configuration configuration, TemplateData data, 
    TemplateLoadOptions options)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | Url | [`URL`](../../../com.aspose.html/url/) で提示された HTML ソース スケルトンをマージします。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| データ | TemplateData | マージ用テンプレートデータ - 置換 (XML、JSON)。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) オブジェクト インスタンス。テンプレートとデータ項目の名前が大文字小文字を区別せずに一致するかどうかを判断するために使用されます（オプション）。 |

### 戻り値

変換結果として新しく生成された [`HTMLDocument`](../../../com.aspose.html/htmldocument/) は、出力ファイルパスを通じて保存できます。

## 備考

テンプレートマージャー

テンプレートマージの考え方は、HTML テンプレートに基づいて HTML ドキュメントを作成し、データ ソースから内容を埋め込むことです。Aspose.HTML は、XML や JSON などのさまざまなデータ ソースタイプとテンプレートで使用できるインライン式構文を提供します。テンプレートマージおよび ConvertTemplate() メソッドの使用に関する詳細情報は、[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) を参照してください。

変換（マージ）手順

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

テンプレート ソース。ファイル、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) オブジェクト インスタンス、またはインライン コンテンツで HTML テンプレート ソースを定義します。変換結果。メソッド署名に応じて、結果の HTMLDocument を直接取得するか、出力ファイル パスを指定できます。[`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) のインスタンスを作成します。Converter クラスの ConvertTemplate() メソッドを使用してテンプレートとデータをマージします。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // URL を骨格 HTML ソースファイルに変換する
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // フォーム XML（JSON）テンプレート データ ファイル パス
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData オブジェクト インスタンスを定義する
      var templateData = new TemplateData(templateDataPath);

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // デフォルトの TemplateLoadOptions オブジェクトを定義する
      var options = new TemplateLoadOptions();

      // デフォルト構成で変換プロセスを開始する
      using (var document = Converter.ConvertTemplate(sourceUrl, new Configuration(), templateData, options))
      {
        // リンクされたリソースとともに結果を保存する
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, TemplateData, TemplateLoadOptions) {#converttemplate_4}

完全なファイルパスで提示されたテンプレート HTML ソースをテンプレートデータ (XML、JSON) とマージします。結果は新しく作成された [`HTMLDocument`](../../../com.aspose.html/htmldocument/) で、ファイルとして保存できます。

```java
public static HTMLDocument ConvertTemplate(String sourcePath, TemplateData data, 
    TemplateLoadOptions options)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | 完全なファイル パスで提示された HTML ソース スケルトンをマージします。 |
| データ | TemplateData | マージ用テンプレートデータ - 置換 (XML、JSON)。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) オブジェクト インスタンス。テンプレートとデータ項目の名前が大文字小文字を区別せずに一致するかどうかを判断するために使用されます（オプション）。 |

### 戻り値

変換結果として新しく生成された [`HTMLDocument`](../../../com.aspose.html/htmldocument/) は、出力ファイルパスを通じて保存できます。

## 備考

テンプレートマージャー

テンプレートマージの考え方は、HTML テンプレートに基づいて HTML ドキュメントを作成し、データ ソースから内容を埋め込むことです。Aspose.HTML は、XML や JSON などのさまざまなデータ ソースタイプとテンプレートで使用できるインライン式構文を提供します。テンプレートマージおよび ConvertTemplate() メソッドの使用に関する詳細情報は、[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) を参照してください。

変換（マージ）手順

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

テンプレート ソース。ファイル、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) オブジェクト インスタンス、またはインライン コンテンツで HTML テンプレート ソースを定義します。変換結果。メソッド署名に応じて、結果の HTMLDocument を直接取得するか、出力ファイル パスを指定できます。[`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) のインスタンスを作成します。Converter クラスの ConvertTemplate() メソッドを使用してテンプレートとデータをマージします。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォーム スケルトン HTML ソース ファイル パス
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // フォーム XML（JSON）テンプレート データ ファイル パス
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData オブジェクト インスタンスを定義する
      var templateData = new TemplateData(templateDataPath);

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // デフォルトの TemplateLoadOptions オブジェクトを定義する
      var options = new TemplateLoadOptions();

      // 変換プロセスを開始する
      using (var document = Converter.ConvertTemplate(sourcePath, templateData, options))
      {
        // リンクされたリソースとともに結果を保存する
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_3}

完全なファイルパスで提示されたテンプレート HTML ソースをテンプレートデータ (XML、JSON) とマージします。結果は新しく作成された [`HTMLDocument`](../../../com.aspose.html/htmldocument/) で、ファイルとして保存できます。

```java
public static HTMLDocument ConvertTemplate(String sourcePath, Configuration configuration, 
    TemplateData data, TemplateLoadOptions options)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | 完全なファイル パスで提示された HTML ソース スケルトンをマージします。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| データ | TemplateData | マージ用テンプレートデータ - 置換 (XML、JSON)。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) オブジェクト インスタンス。テンプレートとデータ項目の名前が大文字小文字を区別せずに一致するかどうかを判断するために使用されます（オプション）。 |

### 戻り値

変換結果として新しく生成された [`HTMLDocument`](../../../com.aspose.html/htmldocument/) は、出力ファイルパスを通じて保存できます。

## 備考

テンプレートマージャー

テンプレートマージの考え方は、HTML テンプレートに基づいて HTML ドキュメントを作成し、データ ソースから内容を埋め込むことです。Aspose.HTML は、XML や JSON などのさまざまなデータ ソースタイプとテンプレートで使用できるインライン式構文を提供します。テンプレートマージおよび ConvertTemplate() メソッドの使用に関する詳細情報は、[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) を参照してください。

変換（マージ）手順

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

テンプレート ソース。ファイル、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) オブジェクト インスタンス、またはインライン コンテンツで HTML テンプレート ソースを定義します。変換結果。メソッド署名に応じて、結果の HTMLDocument を直接取得するか、出力ファイル パスを指定できます。[`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) のインスタンスを作成します。Converter クラスの ConvertTemplate() メソッドを使用してテンプレートとデータをマージします。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォーム スケルトン HTML ソース ファイル パス
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // フォーム XML（JSON）テンプレート データ ファイル パス
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData オブジェクト インスタンスを定義する
      var templateData = new TemplateData(templateDataPath);

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // デフォルトの TemplateLoadOptions オブジェクトを定義する
      var options = new TemplateLoadOptions();

      // デフォルト構成で変換プロセスを開始する
      using (var document = Converter.ConvertTemplate(sourcePath, new Configuration(), templateData, options))
      {
        // リンクされたリソースとともに結果を保存する
        document.Save(new Url(resultPath));
      }
```

*InputFolder - user source template folder.

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, TemplateData, TemplateLoadOptions) {#converttemplate_6}

インラインコンテンツで提示されたテンプレート HTMLソースをテンプレートデータ (XML、JSON) とマージします。結果は新しく作成された [`HTMLDocument`](../../../com.aspose.html/htmldocument/) で、ファイルとして保存できます。

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, TemplateData data, 
    TemplateLoadOptions options)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン文字列コンテンツで提示された HTML ソース スケルトンをマージします。 |
| baseUrl | 文字列 | HTML テンプレートのベース URI。現在のディレクトリ パスと結合され、絶対 URL が形成されます。 |
| データ | TemplateData | マージ用テンプレートデータ - 置換 (XML、JSON)。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) オブジェクト インスタンス。テンプレートとデータ項目の名前が大文字小文字を区別せずに一致するかどうかを判断するために使用されます（オプション）。 |

### 戻り値

変換結果として新しく生成された [`HTMLDocument`](../../../com.aspose.html/htmldocument/) は、出力ファイルパスを通じて保存できます。

## 備考

テンプレートマージャー

テンプレートマージの考え方は、HTML テンプレートに基づいて HTML ドキュメントを作成し、データ ソースから内容を埋め込むことです。Aspose.HTML は、XML や JSON などのさまざまなデータ ソースタイプとテンプレートで使用できるインライン式構文を提供します。テンプレートマージおよび ConvertTemplate() メソッドの使用に関する詳細情報は、[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) を参照してください。

変換（マージ）手順

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

テンプレート ソース。ファイル、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) オブジェクト インスタンス、またはインライン コンテンツで HTML テンプレート ソースを定義します。変換結果。メソッド署名に応じて、結果の HTMLDocument を直接取得するか、出力ファイル パスを指定できます。[`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) のインスタンスを作成します。Converter クラスの ConvertTemplate() メソッドを使用してテンプレートとデータをマージします。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // インライン ソース コンテンツをテンプレートとして設定する
      String templateContent =
        "<html>" +
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";

      // フォーム XML（JSON）テンプレート データ ファイル パス
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData オブジェクト インスタンスを定義する
      var templateData = new TemplateData(templateDataPath);

      // マージ結果として出力を設定する
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // デフォルトの TemplateLoadOptions オブジェクトを定義する
      var options = new TemplateLoadOptions();

      // 変換プロセスを開始し、結果を保存する
      using (var document = Converter.ConvertTemplate(
        templateContent, String.Empty,
        templateData,
        options))
      {
        document.Save(new Url(resultFilePath));
      }
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertTemplate(String, String, Configuration, TemplateData, TemplateLoadOptions) {#converttemplate_5}

インラインコンテンツで提示されたテンプレート HTMLソースをテンプレートデータ (XML、JSON) とマージします。結果は新しく作成された [`HTMLDocument`](../../../com.aspose.html/htmldocument/) で、ファイルとして保存できます。

```java
public static HTMLDocument ConvertTemplate(String content, String baseUrl, 
    Configuration configuration, TemplateData data, TemplateLoadOptions options)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン文字列コンテンツで提示された HTML ソース スケルトンをマージします。 |
| baseUrl | 文字列 | HTML テンプレートのベース URI。現在のディレクトリ パスと結合され、絶対 URL が形成されます。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| データ | TemplateData | マージ用テンプレートデータ - 置換 (XML、JSON)。 |
| options | TemplateLoadOptions | [`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) オブジェクト インスタンス。テンプレートとデータ項目の名前が大文字小文字を区別せずに一致するかどうかを判断するために使用されます（オプション）。 |

### 戻り値

変換結果として新しく生成された [`HTMLDocument`](../../../com.aspose.html/htmldocument/) は、出力ファイルパスを通じて保存できます。

## 備考

テンプレートマージャー

テンプレートマージの考え方は、HTML テンプレートに基づいて HTML ドキュメントを作成し、データ ソースから内容を埋め込むことです。Aspose.HTML は、XML や JSON などのさまざまなデータ ソースタイプとテンプレートで使用できるインライン式構文を提供します。テンプレートマージおよび ConvertTemplate() メソッドの使用に関する詳細情報は、[article](https://docs.aspose.com/html/net/converting-between-formats/html-template/) を参照してください。

変換（マージ）手順

[`Converter`](../) class offers few ways to merge html source with template data wherein you should follow one of simple scenarios consists of few steps:

テンプレート ソース。ファイル、[`URL`](../../../com.aspose.html/url/)、[`HTMLDocument`](../../../com.aspose.html/htmldocument/) オブジェクト インスタンス、またはインライン コンテンツで HTML テンプレート ソースを定義します。変換結果。メソッド署名に応じて、結果の HTMLDocument を直接取得するか、出力ファイル パスを指定できます。[`TemplateLoadOptions`](../../../com.aspose.html.loading/templateloadoptions/) のインスタンスを作成します。Converter クラスの ConvertTemplate() メソッドを使用してテンプレートとデータをマージします。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // インライン ソース コンテンツをテンプレートとして設定する
      String templateContent =
        "<html>" + 
        "<body>" +
        "<div data_merge=\"{{#foreach Person}}\">" +
        "<p>{{Title}}</p>" +
        "<p>Name: {{Name}} Surname: {{Surname}}</p>" +
        "<p>Address:</p>" +
        "<p>{{Address.Number}}, {{Address.Street}} {{Address.City}}</p>" +
        "</div>" +
        "</body></html>";
       
      // フォーム XML（JSON）テンプレート データ ファイル パス
      var templateDataPath = Path.Combine(TemplateFolder, "templateData.xml");

      // TemplateData オブジェクト インスタンスを定義する
      var templateData = new TemplateData(templateDataPath);

      // マージ結果として出力を設定する
      var resultFilePath = Path.Combine(OutputFolder, "result.html");

      // configuration オブジェクト インスタンスを定義する
      var configuration = new Configuration();

      // デフォルトの TemplateLoadOptions オブジェクトを定義する
      var options = new TemplateLoadOptions();

      // 変換プロセスを開始し、結果を保存する
      using (var document = Converter.ConvertTemplate(
        templateContent, String.Empty,
        configuration,
        templateData,
        options))
      {
        document.Save(new Url(resultFilePath));
      }
```

*TemplateFolder - user template data folder.

*OutputFolder - user output file path.

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TemplateData](../../templatedata/)
* class [TemplateLoadOptions](../../../com.aspose.html.loading/templateloadoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
