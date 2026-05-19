---
title: "HTMLDocument"
second_title: "Aspose.HTML for Java API リファレンス"
description: "HTMLDocument コンストラクタ。HTMLDocument コンストラクタは、ブラウザで読み込まれたウェブページであり、ページのコンテンツへのエントリーポイントとなる新しい HTML Document オブジェクトを作成します。"
type: docs

url: /ja/java/com.aspose.html/htmldocument/htmldocument/
---
## HTMLDocument() {#constructor}

HTMLDocument コンストラクタは、ブラウザで読み込まれたウェブページであり、ページのコンテンツへのエントリーポイントとなる新しい HTML Document オブジェクトを作成します。

```java
public HTMLDocument()
```

## Remarks

注: ドキュメントは base-url プロパティのデフォルト値として 'about:blank' が設定された状態で作成されます。

参照:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 例

ドキュメントオブジェクトが作成されたら、後で HTML 要素で内容を埋めることができます。以下のコードスニペットは、デフォルトの HTMLDocument() コンストラクタを使用して空の HTML ドキュメントを作成し、ファイルに保存する方法を示しています。

```java
import (var document = new HTMLDocument())
{
	// ここでドキュメントを操作する
	...	
	
	// ドキュメントをファイルに保存する
	document.Save("document.html");
}
```

### 関連項目

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Configuration) {#constructor_1}

HTMLDocument コンストラクタは、ブラウザで読み込まれたウェブページであり、ページのコンテンツへのエントリーポイントとなる新しい HTML Document オブジェクトを作成します。

```java
public HTMLDocument(Configuration configuration)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| 構成 | 構成 | スクリプトポリシーやカスタムユーザースタイルシートなどの環境設定 |

## Remarks

注: ドキュメントは base-url プロパティのデフォルト値として 'about:blank' が設定された状態で作成されます。

参照:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 例

以下の例は、設定オブジェクトを使用してスクリプトを無効化する方法を示しています。

```java
// HTML コードを準備し、ファイルに保存します
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Configuration のインスタンスを作成する
import (var configuration = new Configuration())
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
```

### 関連項目

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url) {#constructor_4}

URL から HTML ドキュメントを読み込みます。

注: 現在到達できない誤った URL を渡した場合、ライブラリは [`DOMException`](../../../com.aspose.html.dom/domexception/) をスローし、特定のコード ‘NetworkError’ で選択されたリソースが見つからないことを通知します。

```java
public HTMLDocument(Url url)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | 開く HTML ドキュメントの URL。 |

## Remarks

参照:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 例

 'https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html' のウェブページからドキュメントを読み込む:

```java
import (var document = new HTMLDocument("https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html"))
{
	// ドキュメントの内容を出力ストリームに書き込む
	Console.WriteLine(document.DocumentElement.OuterHTML);
}
```

### 関連項目

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url, Configuration) {#constructor_5}

指定された環境構成設定を使用して、URL から HTML ドキュメントを読み込みます。

注: 現在到達できない誤った URL を渡した場合、ライブラリは [DOMException](T:com.aspose.html.dom.DOMException) をスローし、特定のコード ‘NetworkError’ で選択されたリソースが見つからないことを通知します。

```java
public HTMLDocument(Url url, Configuration configuration)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | 開く HTML ドキュメントの URL。 |
| 構成 | 構成 | スクリプトポリシーやカスタムユーザースタイルシートなどの環境設定 |

## Remarks

参照:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 例

```java
The following example demonstrates how to use the configuration object to disable scripts:

// HTML コードを準備し、ファイルに保存します
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Configuration のインスタンスを作成する
import (var configuration = new Configuration())
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
```

### 関連項目

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String) {#constructor_10}

アドレスから HTML ドキュメントを読み込みます。

注: 現在到達できない誤った URL を渡した場合、ライブラリは [`DOMException`](../../../com.aspose.html.dom/domexception/) をスローし、特定のコード ‘NetworkError’ で選択されたリソースが見つからないことを通知します。

```java
public HTMLDocument(String address)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| アドレス | 文字列 | 開く HTML ドキュメントのアドレス。 |

## Remarks

参照:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 例

アドレスから HTML ドキュメントを初期化する。

```java
import (var document = new HTMLDocument("./my-folder/document.html")))
{
	...
}
```

### 関連項目

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Configuration) {#constructor_11}

指定された環境構成設定を使用して、アドレスから HTML ドキュメントを読み込みます。

注: 現在到達できない誤った URL を渡した場合、ライブラリは [`DOMException`](../../../com.aspose.html.dom/domexception/) をスローし、特定のコード ‘NetworkError’ で選択されたリソースが見つからないことを通知します。

```java
public HTMLDocument(String address, Configuration configuration)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| アドレス | 文字列 | 開く HTML ドキュメントのアドレス。 |
| 構成 | 構成 | スクリプトポリシーやカスタムユーザースタイルシートなどの環境設定 |

## Remarks

参照:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 例

```java
// Configuration のインスタンスを作成する
import (var configuration = new Configuration())
{
	// 'scripts' を信頼できないリソースとしてマークする
	configuration.Security |= Sandbox.Scripts;
	
	using (var document = new HTMLDocument("./my-folder/document.html", configuration)))
	{
		...
	}
}
```

### 関連項目

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String) {#constructor_14}

指定された base-uri を使用して、文字列コンテンツから HTML ドキュメントを作成します。

```java
public HTMLDocument(String content, String baseUri)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | ドキュメントを読み込むための String コンテンツ。 |
| baseUri | 文字列 | ドキュメントのベース URI。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | base-uri パラメータが null の場合にスローされます。 |

## Remarks

参照:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 例

```java
// HTML コードを準備します
var html_code = "<p>Hello World!</p>";

// String 変数からドキュメントを初期化します
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### 関連項目

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String, Configuration) {#constructor_15}

指定された base-uri と環境構成設定を使用して、文字列コンテンツから HTML ドキュメントを作成します。

```java
public HTMLDocument(String content, String baseUri, Configuration configuration)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | ドキュメントを読み込むための String コンテンツ。 |
| baseUri | 文字列 | ドキュメントのベース URI。 |
| 構成 | 構成 | スクリプトポリシーやカスタムユーザースタイルシートなどの環境設定 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | base-uri パラメータが null の場合にスローされます。 |

## Remarks

参照:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 例

```java
// HTML コードを準備します
var html_code = "<p>Hello World!</p>";

// String 変数からドキュメントを初期化します
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### 関連項目

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url) {#constructor_12}

指定された base-uri を使用して、文字列コンテンツから HTML ドキュメントを作成します。

```java
public HTMLDocument(String content, Url baseUri)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | ドキュメントを読み込むための String コンテンツ。 |
| baseUri | Url | ドキュメントのベース URI。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | base-uri パラメータが null の場合にスローされます。 |

## Remarks

参照:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 例

```java
// HTML コードを準備します
var html_code = "<p>Hello World!</p>";

// String 変数からドキュメントを初期化します
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### 関連項目

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url, Configuration) {#constructor_13}

指定された base-uri と環境構成設定を使用して、文字列コンテンツから HTML ドキュメントを作成します。

```java
public HTMLDocument(String content, Url baseUri, Configuration configuration)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | ドキュメントを読み込むための String コンテンツ。 |
| baseUri | Url | ドキュメントのベース URI。 |
| 構成 | 構成 | スクリプトポリシーやカスタムユーザースタイルシートなどの環境設定 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | base-uri パラメータが null の場合にスローされます。 |

## Remarks

参照:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 例

```java
// HTML コードを準備します
var html_code = "<p>Hello World!</p>";

// String 変数からドキュメントを初期化します
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### 関連項目

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String) {#constructor_8}

指定された base-uri を使用して相対リソースのパスを解決するための、[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) コンテンツから HTML ドキュメントを作成します。

```java
public HTMLDocument(Stream content, String baseUri)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| content | Stream | ドキュメントを読み込むための [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) コンテンツ。 |
| baseUri | 文字列 | ドキュメントのベース URI。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | base-uri パラメータが null の場合にスローされます。 |

## Remarks

参照:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 例

```java
// メモリストリームオブジェクトを作成する
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// HTML コードをメモリオブジェクトに書き込む
	sw.Write("<p>Hello World! I love HTML!</p>");

	// It is important to set the position to the beginning since HTMLDocument starts the reading exactly from the current position within the stream
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// String 変数からドキュメントを初期化します
	using (var document = new HTMLDocument(mem, "."))
	{
		// Save the document to a disk
		document.Save("load-from-stream.html");
	}
}
```

### 関連項目

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String, Configuration) {#constructor_9}

指定された base-uri と環境構成設定を使用して、[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) コンテンツから HTML ドキュメントを作成します。

```java
public HTMLDocument(Stream content, String baseUri, Configuration configuration)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| content | Stream | ドキュメントを読み込むための [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) コンテンツ。 |
| baseUri | 文字列 | ドキュメントのベース URI。 |
| 構成 | 構成 | スクリプトポリシーやカスタムユーザースタイルシートなどの環境設定 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | base-uri パラメータが null の場合にスローされます。 |

## Remarks

参照:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 例

```java
// メモリストリームオブジェクトを作成する
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// HTML コードをメモリオブジェクトに書き込む
	sw.Write("<p>Hello World! I love HTML!</p>");

	// It is important to set the position to the beginning since HTMLDocument starts the reading exactly from the current position within the stream
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// String 変数からドキュメントを初期化します
	using (var document = new HTMLDocument(mem, "."))
	{
		// Save the document to a disk
		document.Save("load-from-stream.html");
	}
}
```

### 関連項目

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url) {#constructor_6}

指定された base-uri を使用して相対リソースのパスを解決するための、[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) コンテンツから HTML ドキュメントを作成します。

```java
public HTMLDocument(Stream content, Url baseUri)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| content | Stream | ドキュメントを読み込むための [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) コンテンツ。 |
| baseUri | Url | ドキュメントのベース URI。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | base-uri パラメータが null の場合にスローされます。 |

## Remarks

参照:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 例

```java
// メモリストリームオブジェクトを作成する
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// HTML コードをメモリオブジェクトに書き込む
	sw.Write("<p>Hello World! I love HTML!</p>");

	// It is important to set the position to the beginning since HTMLDocument starts the reading exactly from the current position within the stream
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// String 変数からドキュメントを初期化します
	using (var document = new HTMLDocument(mem, "."))
	{
		// Save the document to a disk
		document.Save("load-from-stream.html");
	}
}
```

### 関連項目

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url, Configuration) {#constructor_7}

指定された base-uri と環境構成設定を使用して、[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) コンテンツから HTML ドキュメントを作成します。

```java
public HTMLDocument(Stream content, Url baseUri, Configuration configuration)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| content | Stream | ドキュメントを読み込むための [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) コンテンツ。 |
| baseUri | Url | ドキュメントのベース URI。 |
| 構成 | 構成 | スクリプトポリシーやカスタムユーザースタイルシートなどの環境設定 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | base-uri パラメータが null の場合にスローされます。 |

## Remarks

参照:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 例

```java
// メモリストリームオブジェクトを作成する
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// HTML コードをメモリオブジェクトに書き込む
	sw.Write("<p>Hello World! I love HTML!</p>");

	// It is important to set the position to the beginning since HTMLDocument starts the reading exactly from the current position within the stream
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// String 変数からドキュメントを初期化します
	using (var document = new HTMLDocument(mem, "."))
	{
		// Save the document to a disk
		document.Save("load-from-stream.html");
	}
}
```

### 関連項目

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage) {#constructor_2}

Creates an HTML document from the [`RequestMessage`](../../../com.aspose.html.net/requestmessage/) object.

```java
public HTMLDocument(RequestMessage request)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| request | RequestMessage | The request message that contains a [`body`](../../../com.aspose.html.net/requestmessage/content/) with document content. |

## Remarks

By definition, a message handler is a class that receives a Web request and returns a Web response. In other words, a message handler is used to process a Web service request during input and/or to process the response during output.

Please, visit our [docs site](https://docs.aspose.com/html/net/message-handlers/) to see more scenarios on how to use this constructor.

参照:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### 関連項目

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage, Configuration) {#constructor_3}

[RequestMessage](T:com.aspose.html.net.RequestMessage) オブジェクトから HTML ドキュメントを作成します。

```java
public HTMLDocument(RequestMessage request, Configuration configuration)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| request | RequestMessage | The request message that contains a [body](P:com.aspose.html.net.RequestMessage.Content) with document content. |
| 構成 | 構成 | スクリプトポリシーやカスタムユーザースタイルシートなどの環境設定 |

## Remarks

By definition, a message handler is a class that receives a Web request and returns a Web response. In other words, a message handler is used to process a Web service request during input and/or to process the response during output.

Please, visit our [docs site](https://docs.aspose.com/html/net/message-handlers/) to see more scenarios on how to use this constructor.

参照:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### 関連項目

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
