---
title: "HTMLDocument.Save"
second_title: "Aspose.HTML for Java API リファレンス"
description: "HTMLDocument メソッド。 ドキュメントを url で指定されたローカルファイルに保存します。このドキュメントで使用されるすべてのリソースは、output_file_name_files のように名前が付けられた隣接フォルダーに保存されます。"
type: docs

url: /ja/java/com.aspose.html/htmldocument/save/
---
## Save(Url) {#save_5}

ドキュメントを url で指定されたローカルファイルに保存します。このドキュメントで使用されたすべてのリソースは、隣接するフォルダーに保存され、その名前は output_file_name + "_files" として構築されます。

```java
public void Save(Url url)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | Url | 出力ファイルへのローカル [`URL`](../../url/) |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 指定された `url` が有効なローカルファイル URL でない場合に発生します。 |

## 備考

HTML を保存

ほとんどのタスクはドキュメントの保存が必要です。既存のファイルを読み込むか、HTML ドキュメントをゼロから作成したら、HTMLDocument.Save() メソッドのいずれかを使用して変更を保存できます。これらのメソッドは、パス、URL、または出力ストレージで指定されたローカルファイルに HTML を保存することを可能にします。保存に関する詳細は、[documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) を参照してください。

Save(Url) メソッド

HTML ドキュメントを保存するには、完全な Url パス（例：'outputFilePath'）を指定する必要があります。 `Url(url)` コンストラクタは、指定された url を持つ [`Url`](../../url/) クラスのインスタンスを作成します。そのインスタンスを Save(Url) メソッドに渡す必要があります。ドキュメントは url で指定されたローカルファイルに保存されます。このドキュメントで使用されるすべてのリソースは、output_file_name + "_files" のように名前が付けられた隣接フォルダーに保存されます。

ソースコード

完全なサンプルとデータファイルは[GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)からダウンロードできます。

## サンプル

```java
import System;
import System.IO;
import Aspose.Html;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
        
	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(new Url(outputFilePath));
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### 関連項目

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler) {#save}

[`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/) を使用してドキュメントの内容とリソースを保存します。

```java
public void Save(ResourceHandler resourceHandler)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | リソースハンドラ [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)。 |

### 関連項目

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String) {#save_10}

パスで指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されたすべてのリソースは、隣接するフォルダーに保存され、その名前は output_file_name + "_files" の形式で作成されます。

```java
public void Save(String path)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| パス | 文字列 | 出力ファイルへのローカルファイルシステムパス。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 指定された `path` が有効なローカルファイルパスでない場合に発生します。 |

## 備考

HTML を保存

ほとんどのタスクはドキュメントの保存が必要です。既存のファイルを読み込むか、HTML ドキュメントをゼロから作成したら、HTMLDocument.Save() メソッドのいずれかを使用して変更を保存できます。これらのメソッドは、パス、URL、または出力ストレージで指定されたローカルファイルに HTML を保存することを可能にします。保存に関する詳細は、[documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) を参照してください。

Save(String) メソッドは、パラメータとして出力ファイルへのローカルファイルシステムパスを受け取り、HTML ドキュメントをパスで指定されたローカルファイルに保存します。このドキュメントで使用されるすべてのリソースは、隣接フォルダーに保存されます。

ソースコード

完全なサンプルとデータファイルは[GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)からダウンロードできます。

## サンプル

```java
import System;
import System.IO;
import Aspose.Html;
...
 using (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (outputHtmlPath == null)
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(outputFilePath);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output directory path.

### 関連項目

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveFormat) {#save_11}

ドキュメントを path で指定されたローカルファイルに保存します。このドキュメントで使用されたすべてのリソースは、隣接するフォルダーに保存され、その名前は output_file_name + "_files" として構築されます。

```java
public void Save(String path, HTMLSaveFormat saveFormat)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| パス | 文字列 | 出力ファイルへのローカルファイルパス。 |
| saveFormat | HTMLSaveFormat | ドキュメントが保存される形式です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 指定された `path` が有効なローカルファイルパスでない場合に発生します。 |

## 備考

HTML を保存

ほとんどのタスクはドキュメントの保存が必要です。既存のファイルを読み込むか、HTML ドキュメントをゼロから作成したら、HTMLDocument.Save() メソッドのいずれかを使用して変更を保存できます。これらのメソッドは、パス、URL、または出力ストレージで指定されたローカルファイルに HTML を保存することを可能にします。保存に関する詳細は、[documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) を参照してください。

Save(String, HTMLSaveFormat) メソッド

Save(String, HTMLSaveFormat) メソッドは、出力ファイルへのローカルファイルシステムパスと saveFormat をパラメータとして受け取ります。[`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) 列挙体は、ドキュメントが保存される形式を指定し、HTML、MHTML、MD 形式のいずれかにできます。メソッドは、指定された形式で HTML ドキュメントをパスで指定されたローカルファイルに保存します。ドキュメントで使用されるすべてのリソースは隣接フォルダーに保存されます。

ソースコード

完全なサンプルとデータファイルは[GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)からダウンロードできます。

## サンプル

```java
# HTML input file content
<!DOCTYPE html>
<html lang="en"
   xmlns:xml="http://www.w3.org/XML/1998/package">
<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="styles/main.css">
  <title>Title</title>
</head>
<body>
<div id="uniqueIdentifier">Container with ID - identifier</div>
<div class="custom-class">Customized by css class container</div>

<div>
  <p class="pStyle">First styled by pStyle class paragraph</p>
  <p class="pStyle">Second styled by pStyle class paragraph</p>
  <p class="pStyle">Third styled by pStyle class paragraph</p>
  <span class="pStyle">Span styled by pStyle</span>
</div>

<math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>...</mrow>
</math>

<div id="smart class">
  <p id="p1" class="ddd kkk">Paragraph styled by class name =ddd kkk=</p>
  <p id="p2" class="ddd fff">Paragraph styled by class name =ddd fff=</p>
  <p id="p3" class="kkk fff">Paragraph styled by class name =kkk fff=</p>
</div>

</body>
</html>

# C# code
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}
	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtml");
	document.Save(outputFilePath, HTMLSaveFormat.MHTML);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

# Content of result file

MIME-Version: 1.0

Content-Type: Multipart/related; boundary="boundary";type=Text/HTML

--boundary

Content-Type: text/html;

Content-Location: result.mhtml

&lt;!DOCTYPE html&gt;&lt;html lang="en" xmlns:xml="http://www.w3.org/XML/1998/package"&gt;&lt;head&gt;

&lt;meta charset="UTF-8"&gt;

&lt;link rel="stylesheet" href="main.css"&gt;

&lt;title&gt;タイトル&lt;/title&gt;

&lt;/head&gt;

&lt;body&gt;

&lt;div id="uniqueIdentifier"&gt;ID が付いたコンテナ - identifier&lt;/div&gt;

&lt;div class="custom-class"&gt;CSS クラスコンテナによってカスタマイズされました&lt;/div&gt;

&lt;div&gt;

&lt;p class="pStyle"&gt;pStyle クラスでスタイルされた最初の段落&lt;/p&gt;

&lt;p class="pStyle"&gt;pStyle クラスでスタイルされた2番目の段落&lt;/p&gt;

&lt;p class="pStyle"&gt;pStyle クラスでスタイルされた3番目の段落&lt;/p&gt;

&lt;span class="pStyle"&gt;pStyle でスタイルされたスパン&lt;/span&gt;

&lt;/div&gt;

&lt;math xmlns="http://www.w3.org/1998/Math/MathML"&gt;

&lt;mrow&gt;...&lt;/mrow&gt;

&lt;/math&gt;

&lt;div id="smart class"&gt;

&lt;p id="p1" class="ddd kkk"&gt;クラス名 =ddd kkk= によってスタイル設定された段落&lt;/p&gt;

&lt;p id="p2" class="ddd fff"&gt;クラス名 =ddd fff= によってスタイル設定された段落&lt;/p&gt;

&lt;p id="p3" class="kkk fff"&gt;クラス名 =kkk fff= によってスタイル設定された段落&lt;/p&gt;

&lt;/div&gt;

&lt;div&gt;DIV 要素からの挨拶&lt;/div&gt;&lt;/body&gt;&lt;/html&gt;

--boundary

Content-Type: text/css;

Content-Location: main.css

.custom-class { color: yellow; background-color: blueviolet; margin-top: 10pt; margin-right: 10pt; margin-bottom: 10pt; margin-left: 10pt; }.pStyle { font-

--boundary--

### 関連項目

* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveFormat) {#save_6}

ドキュメントを url で指定されたローカルファイルに保存します。このドキュメントで使用されたすべてのリソースは、隣接するフォルダーに保存され、その名前は output_file_name + "_files" として構築されます。

```java
public void Save(Url url, HTMLSaveFormat saveFormat)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | Url | 出力ファイルへのローカル URL。 |
| saveFormat | HTMLSaveFormat | ドキュメントが保存される形式です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 指定された `url` が有効なローカルファイル URL でない場合に発生します。 |

## 備考

HTML を保存

ほとんどのタスクはドキュメントの保存が必要です。既存のファイルを読み込むか、HTML ドキュメントをゼロから作成したら、HTMLDocument.Save() メソッドのいずれかを使用して変更を保存できます。これらのメソッドは、パス、URL、または出力ストレージで指定されたローカルファイルに HTML を保存することを可能にします。保存に関する詳細は、[documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) を参照してください。

Save(Url, HTMLSaveFormat) メソッド

HTML ドキュメントを保存するには、完全な Url パス（'outputFilePath'）を指定する必要があります。Url(url) コンストラクタは、指定された url を持つ [`Url`](../../url/) クラスのインスタンスを作成します。[`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) 列挙体は、ドキュメントが保存される形式を指定し、HTML、MHTML、MD 形式のいずれかを選択できます。その後、Save(url, saveFormat) メソッドにパラメータを渡す必要があります。ドキュメントは、指定された形式で、url で指定されたローカルファイルに保存されます。

ソースコード

完全なサンプルとデータファイルは[GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)からダウンロードできます。

## サンプル

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtml");
	document.Save(new Url(outputFilePath), HTMLSaveFormat.MHTML);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output directory path.

### 関連項目

* class [Url](../../url/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveFormat) {#save_1}

[`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/) を使用してドキュメントの内容とリソースを保存します。

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveFormat saveFormat)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | リソースハンドラ [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)。 |
| saveFormat | HTMLSaveFormat | ドキュメントが保存される形式です。 |

### 関連項目

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveOptions) {#save_12}

パスで指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されたすべてのリソースは、隣接するフォルダーに保存され、その名前は output_file_name + "_files" の形式で作成されます。

```java
public void Save(String path, HTMLSaveOptions saveOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| パス | 文字列 | 出力ファイルへのローカルパス。 |
| saveOptions | HTMLSaveOptions | [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) オブジェクトはリソース処理プロセスの管理用です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 指定された `path` が有効なローカルファイルパスでない場合に発生します。 |

## 備考

HTML を保存

ほとんどのタスクはドキュメントの保存が必要です。既存のファイルを読み込むか、HTML ドキュメントをゼロから作成したら、HTMLDocument.Save() メソッドのいずれかを使用して変更を保存できます。これらのメソッドは、パス、URL、または出力ストレージで指定されたローカルファイルに HTML を保存することを可能にします。保存に関する詳細は、[documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) を参照してください。

Save(String, HTMLSaveOptions) メソッド

Save(String, HTMLSaveOptions) メソッドは、出力ファイルへのローカルファイルシステムパスと、[HTMLSaveOptions](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) クラスのインスタンスをパラメータとして受け取り、リソース付きの HTML ドキュメントを指定されたパスのローカルファイルに保存します。HTMLSaveOptions() コンストラクタは、リソース処理の構成に使用される [`ResourceHandlingOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) プロパティを持つ保存オプションのインスタンスを作成します。ドキュメントで使用されるすべてのリソースは、隣接するフォルダーに保存されます。

ソースコード

完全なサンプルとデータファイルは[GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)からダウンロードできます。

## サンプル

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	// オプションクラスのインスタンスを定義する
	var options = new HTMLSaveOptions();
	// ページ処理の制限
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### 関連項目

* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveOptions) {#save_7}

ドキュメントを url で指定されたローカルファイルに保存します。このドキュメントで使用されたすべてのリソースは、隣接するフォルダーに保存され、その名前は次のように構築されます: output_file_name + "_files"。

```java
public void Save(Url url, HTMLSaveOptions saveOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | Url | 出力ファイルへのローカル [`URL`](../../url/) |
| saveOptions | HTMLSaveOptions | [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) オブジェクトはリソース処理プロセスの管理用です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 指定された `url` が有効なローカルファイル URL でない場合に発生します。 |

## 備考

HTML を保存

ほとんどのタスクはドキュメントの保存が必要です。既存のファイルを読み込むか、HTML ドキュメントをゼロから作成したら、HTMLDocument.Save() メソッドのいずれかを使用して変更を保存できます。これらのメソッドは、パス、URL、または出力ストレージで指定されたローカルファイルに HTML を保存することを可能にします。保存に関する詳細は、[documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) を参照してください。

Save(Url, HTMLSaveOptions) メソッド

HTML ドキュメントを保存するには、完全な Url パスを指定する必要があります。Url(url) コンストラクタは、指定された url を持つ [`Url`](../../url/) クラスのインスタンスを作成します。HTMLSaveOptions() コンストラクタは、リソース処理の構成に使用される ResourceHandlingOptions プロパティを持つ [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) クラスのインスタンスを作成します。Save(url, saveOptions) メソッドはパラメータを受け取り、リソース付きの HTML ドキュメントを url で指定されたローカルファイルに保存します。

ソースコード

完全なサンプルとデータファイルは[GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)からダウンロードできます。

## サンプル

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	// オプションクラスのインスタンスを定義する
	var options = new HTMLSaveOptions();
	// ページ処理の制限
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### 関連項目

* class [Url](../../url/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveOptions) {#save_2}

[`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/) を使用してドキュメントの内容とリソースを保存します。

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveOptions saveOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | リソースハンドラ [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)。 |
| saveOptions | HTMLSaveOptions | HTML 保存オプション。 |

### 関連項目

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MarkdownSaveOptions) {#save_13}

パスで指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されたすべてのリソースは、隣接するフォルダーに保存され、その名前は output_file_name + "_files" の形式で作成されます。

```java
public void Save(String path, MarkdownSaveOptions saveOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| パス | 文字列 | 出力ファイルへのローカルパス。 |
| saveOptions | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options) を参照してください。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 指定された `path` が有効なローカルファイルパスでない場合に発生します。 |

## 備考

HTML を保存

ほとんどのタスクはドキュメントの保存が必要です。既存のファイルを読み込むか、HTML ドキュメントをゼロから作成したら、HTMLDocument.Save() メソッドのいずれかを使用して変更を保存できます。これらのメソッドは、パス、URL、または出力ストレージで指定されたローカルファイルに HTML を保存することを可能にします。保存に関する詳細は、[documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) を参照してください。

Save(String, MarkdownSaveOptions) メソッド

ドキュメントを保存するには、出力ファイルへのローカルファイルシステムパスを指定する必要があります。MarkdownSaveOptions() コンストラクタは、[`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) クラスのインスタンスを作成し、さまざまなプロパティを持ちます。たとえば、Markdown の書式スタイルを設定したり、事前定義された GitLab Flavored Markdown 互換オプションを使用したり、リソース処理を構成したりできます。Save(path, saveOptions) メソッドは、出力ファイルへのローカルパスとオプションインスタンスをパラメータとして受け取り、HTML をリソース付きの Markdown ドキュメントとして、指定されたパスのローカルファイルに保存します。

ソースコード

完全なサンプルとデータファイルは[GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)からダウンロードできます。

## サンプル

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
     
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.md");
	// オプションクラスのインスタンスを定義する
	var options = new MarkdownSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### 関連項目

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MarkdownSaveOptions) {#save_8}

ドキュメントを url で指定されたローカルファイルに保存します。このドキュメントで使用されたすべてのリソースは、隣接するフォルダーに保存され、その名前は次のように構築されます: output_file_name + "_files"。

```java
public void Save(Url url, MarkdownSaveOptions saveOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | Url | 出力ファイルへのローカル [`URL`](../../url/) |
| saveOptions | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options) を参照してください。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 指定された `url` が有効なローカルファイル URL でない場合に発生します。 |

## 備考

HTML を保存

ほとんどのタスクはドキュメントの保存が必要です。既存のファイルを読み込むか、HTML ドキュメントをゼロから作成したら、HTMLDocument.Save() メソッドのいずれかを使用して変更を保存できます。これらのメソッドは、パス、URL、または出力ストレージで指定されたローカルファイルに HTML を保存することを可能にします。保存に関する詳細は、[documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) を参照してください。

Save(Url, MarkdownSaveOptions) メソッド

ドキュメントを保存するには、完全な Url パスを指定する必要があります。Url(url) コンストラクタは、指定された url を持つ [`Url`](../../url/) クラスのインスタンスを作成します。MarkdownSaveOptions() コンストラクタは、[`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) クラスのインスタンスを作成し、さまざまなプロパティを持ちます。たとえば、Markdown の書式スタイルを設定したり、事前定義された GitLab Flavored Markdown 互換オプションを使用したり、リソース処理を構成したりできます。Save(url, saveOptions) メソッドは、url と保存オプションのインスタンスをパラメータとして受け取り、リソース付きのドキュメントを url で指定されたローカルファイルに保存します。

ソースコード

完全なサンプルとデータファイルは[GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)からダウンロードできます。

## サンプル

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.md");
	// オプションクラスのインスタンスを定義する
	var options = new MarkdownSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### 関連項目

* class [Url](../../url/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MarkdownSaveOptions) {#save_3}

[`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/) を使用してドキュメントの内容とリソースを保存します。

```java
public void Save(ResourceHandler resourceHandler, MarkdownSaveOptions saveOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | リソースハンドラ [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)。 |
| saveOptions | MarkdownSaveOptions | Markdown 保存オプション。 |

### 関連項目

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MHTMLSaveOptions) {#save_14}

パスで指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されたすべてのリソースは、隣接するフォルダーに保存され、その名前は output_file_name + "_files" の形式で作成されます。

```java
public void Save(String path, MHTMLSaveOptions saveOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| パス | 文字列 | 出力ファイルへのローカルパス。 |
| saveOptions | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options) を参照してください。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 指定された `path` が有効なローカルファイルパスでない場合に発生します。 |

## 備考

HTML を保存

ほとんどのタスクはドキュメントの保存が必要です。既存のファイルを読み込むか、HTML ドキュメントをゼロから作成したら、HTMLDocument.Save() メソッドのいずれかを使用して変更を保存できます。これらのメソッドは、パス、URL、または出力ストレージで指定されたローカルファイルに HTML を保存することを可能にします。保存に関する詳細は、[documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) を参照してください。

Save(String, MHTMLSaveOptions) メソッド

ドキュメントを保存するには、出力ファイルのローカルファイルシステムパスを指定する必要があります。`MHTMLSaveOptions()` コンストラクタは、リソース処理の構成に使用される `ResourceHandlingOptions` プロパティを持つ [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) クラスのインスタンスを初期化します。`Save(path, saveOptions)` メソッドは、出力ファイルへのローカルパスと保存オプションのインスタンスをパラメータとして受け取り、HTML を MHTML ドキュメントとして指定されたパスのローカルファイルに保存します。

ソースコード

完全なサンプルとデータファイルは[GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)からダウンロードできます。

## サンプル

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtm");
	// オプションクラスのインスタンスを定義する
	var options = new MHTMLSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### 関連項目

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MHTMLSaveOptions) {#save_9}

ドキュメントを url で指定されたローカルファイルに保存します。このドキュメントで使用されたすべてのリソースは、隣接するフォルダーに保存され、その名前は次のように構築されます: output_file_name + "_files"。

```java
public void Save(Url url, MHTMLSaveOptions saveOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | Url | 出力ファイルへのローカル URL。 |
| saveOptions | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options) を参照してください。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 指定された `url` が有効なローカルファイル URL でない場合に発生します。 |

## 備考

HTML を保存

ほとんどのタスクはドキュメントの保存が必要です。既存のファイルを読み込むか、HTML ドキュメントをゼロから作成したら、HTMLDocument.Save() メソッドのいずれかを使用して変更を保存できます。これらのメソッドは、パス、URL、または出力ストレージで指定されたローカルファイルに HTML を保存することを可能にします。保存に関する詳細は、[documentation](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) を参照してください。

Save(Url, MHTMLSaveOptions) メソッド

ドキュメントを保存するには、完全な Url パスを指定する必要があります。`Url(url)` コンストラクタは、指定された URL を使用して [`Url`](../../url/) クラスのインスタンスを作成します。`MHTMLSaveOptions()` コンストラクタは、リソース処理の構成に使用される `ResourceHandlingOptions` プロパティを持つ [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) クラスのインスタンスを初期化します。`Save(url, saveOptions)` メソッドは、url とオプションをパラメータとして受け取り、HTML を MHTML ドキュメントとして url で指定されたローカルファイルに保存します。

ソースコード

完全なサンプルとデータファイルは[GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation)からダウンロードできます。

## サンプル

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtm");
	// オプションクラスのインスタンスを定義する
	var options = new MHTMLSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input file path.

*outputHtmlPath - user output folder path.

### 関連項目

* class [Url](../../url/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MHTMLSaveOptions) {#save_4}

[`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/) を使用してドキュメントの内容とリソースを保存します。

```java
public void Save(ResourceHandler resourceHandler, MHTMLSaveOptions saveOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | リソースハンドラ [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)。 |
| saveOptions | MHTMLSaveOptions | MHTML 保存オプション。 |

### 関連項目

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
