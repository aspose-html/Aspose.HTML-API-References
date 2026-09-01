---
title: "HTMLDocument"
second_title: "Aspose.HTML for Java API 参考"
description: "HTMLDocument 构造函数。HTMLDocument 构造函数创建一个新的 HTML Document 对象，该对象是加载在浏览器中的网页，并作为页面内容的入口点。"
type: docs

url: /zh/java/com.aspose.html/htmldocument/htmldocument/
---
## HTMLDocument() {#constructor}

HTMLDocument 构造函数创建一个新的 HTML 文档对象，该对象是加载在浏览器中的网页，并作为页面内容的入口点。

```java
public HTMLDocument()
```

## 备注

注意：文档的 base-url 属性默认值为 'about:blank'。

参考：

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 示例

文档对象创建后，可以随后填充 HTML 元素。以下代码片段展示了使用默认的 HTMLDocument() 构造函数创建空 HTML 文档并将其保存到文件的用法。

```java
import (var document = new HTMLDocument())
{
	// 在此处理文档
	...	
	
	// 将文档保存到文件
	document.Save("document.html");
}
```

### 另请参见

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Configuration) {#constructor_1}

HTMLDocument 构造函数创建一个新的 HTML 文档对象，该对象是加载在浏览器中的网页，并作为页面内容的入口点。

```java
public HTMLDocument(Configuration configuration)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 配置 | 配置 | 环境配置，例如脚本策略、自定义用户样式表等。 |

## 备注

注意：文档的 base-url 属性默认值为 'about:blank'。

参考：

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 示例

以下示例演示如何使用配置对象禁用脚本：

```java
// 准备 HTML 代码并将其保存到文件。
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// 创建 Configuration 的实例
import (var configuration = new Configuration())
{
	// 将 'scripts' 标记为不受信任的资源
	configuration.Security |= Sandbox.Scripts;

	// 使用指定的配置初始化 HTML 文档
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// 将 HTML 转换为 PDF
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### 另请参见

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url) {#constructor_4}

从 URL 加载 HTML 文档。

注意：如果传入的 URL 错误且当前无法访问，库会抛出 [`DOMException`](../../../com.aspose.html.dom/domexception/) 并带有特定代码 ‘NetworkError’，以提示找不到所选资源。

```java
public HTMLDocument(Url url)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | 要打开的 HTML 文档 URL。 |

## 备注

参考：

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 示例

从网页 'https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html' 加载文档：

```java
import (var document = new HTMLDocument("https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html"))
{
	// 将文档内容写入输出流
	Console.WriteLine(document.DocumentElement.OuterHTML);
}
```

### 另请参见

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url, Configuration) {#constructor_5}

使用指定的环境配置设置，从 URL 加载 HTML 文档。

注意：如果传入的 URL 错误且当前无法访问，库会抛出 [DOMException](T:com.aspose.html.dom.DOMException) 并带有特定代码 ‘NetworkError’，以提示找不到所选资源。

```java
public HTMLDocument(Url url, Configuration configuration)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | Url | 要打开的 HTML 文档 URL。 |
| 配置 | 配置 | 环境配置，例如脚本策略、自定义用户样式表等。 |

## 备注

参考：

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 示例

```java
The following example demonstrates how to use the configuration object to disable scripts:

// 准备 HTML 代码并将其保存到文件。
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// 创建 Configuration 的实例
import (var configuration = new Configuration())
{
	// 将 'scripts' 标记为不受信任的资源
	configuration.Security |= Sandbox.Scripts;

	// 使用指定的配置初始化 HTML 文档
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// 将 HTML 转换为 PDF
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### 另请参见

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String) {#constructor_10}

从地址加载 HTML 文档。

注意：如果传入的 URL 错误且当前无法访问，库会抛出 [`DOMException`](../../../com.aspose.html.dom/domexception/) 并带有特定代码 ‘NetworkError’，以提示找不到所选资源。

```java
public HTMLDocument(String address)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 地址 | String | 要打开的 HTML 文档地址。 |

## 备注

参考：

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 示例

从地址初始化 HTML 文档。

```java
import (var document = new HTMLDocument("./my-folder/document.html")))
{
	...
}
```

### 另请参见

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Configuration) {#constructor_11}

使用指定的环境配置设置，从地址加载 HTML 文档。

注意：如果传入的 URL 错误且当前无法访问，库会抛出 [`DOMException`](../../../com.aspose.html.dom/domexception/) 并带有特定代码 ‘NetworkError’，以提示找不到所选资源。

```java
public HTMLDocument(String address, Configuration configuration)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 地址 | String | 要打开的 HTML 文档地址。 |
| 配置 | 配置 | 环境配置，例如脚本策略、自定义用户样式表等。 |

## 备注

参考：

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 示例

```java
// 创建 Configuration 的实例
import (var configuration = new Configuration())
{
	// 将 'scripts' 标记为不受信任的资源
	configuration.Security |= Sandbox.Scripts;
	
	using (var document = new HTMLDocument("./my-folder/document.html", configuration)))
	{
		...
	}
}
```

### 另请参见

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String) {#constructor_14}

使用指定的 base-uri，从字符串内容创建 HTML 文档。

```java
public HTMLDocument(String content, String baseUri)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 用于加载文档的 String 内容。 |
| baseUri | String | 文档的基础 URI。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 如果 base-uri 参数为 null 则抛出异常。 |

## 备注

参考：

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 示例

```java
// 准备 HTML 代码
var html_code = "<p>Hello World!</p>";

// 从 String 变量初始化文档
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### 另请参见

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String, Configuration) {#constructor_15}

使用指定的 base-uri 和环境配置设置，从字符串内容创建 HTML 文档。

```java
public HTMLDocument(String content, String baseUri, Configuration configuration)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 用于加载文档的 String 内容。 |
| baseUri | String | 文档的基础 URI。 |
| 配置 | 配置 | 环境配置，例如脚本策略、自定义用户样式表等。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 如果 base-uri 参数为 null 则抛出异常。 |

## 备注

参考：

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 示例

```java
// 准备 HTML 代码
var html_code = "<p>Hello World!</p>";

// 从 String 变量初始化文档
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### 另请参见

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url) {#constructor_12}

使用指定的 base-uri，从字符串内容创建 HTML 文档。

```java
public HTMLDocument(String content, Url baseUri)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 用于加载文档的 String 内容。 |
| baseUri | Url | 文档的基础 URI。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 如果 base-uri 参数为 null 则抛出异常。 |

## 备注

参考：

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 示例

```java
// 准备 HTML 代码
var html_code = "<p>Hello World!</p>";

// 从 String 变量初始化文档
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### 另请参见

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url, Configuration) {#constructor_13}

使用指定的 base-uri 和环境配置设置，从字符串内容创建 HTML 文档。

```java
public HTMLDocument(String content, Url baseUri, Configuration configuration)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 用于加载文档的 String 内容。 |
| baseUri | Url | 文档的基础 URI。 |
| 配置 | 配置 | 环境配置，例如脚本策略、自定义用户样式表等。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 如果 base-uri 参数为 null 则抛出异常。 |

## 备注

参考：

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 示例

```java
// 准备 HTML 代码
var html_code = "<p>Hello World!</p>";

// 从 String 变量初始化文档
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### 另请参见

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String) {#constructor_8}

从具有指定 base-uri 的 [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) 内容创建 HTML 文档，该 base-uri 用于解析相对资源的路径。

```java
public HTMLDocument(Stream content, String baseUri)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| content | Stream | 用于加载文档的 [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) 内容。 |
| baseUri | String | 文档的基础 URI。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 如果 base-uri 参数为 null 则抛出异常。 |

## 备注

参考：

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 示例

```java
// 创建内存流对象
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// 将 HTML 代码写入内存对象
	sw.Write("<p>Hello World! I love HTML!</p>");

	// 重要的是将位置设置为开头，因为 HTMLDocument 从流中的当前位置开始读取。
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// 从 String 变量初始化文档
	using (var document = new HTMLDocument(mem, "."))
	{
		// 将文档保存到磁盘
		document.Save("load-from-stream.html");
	}
}
```

### 另请参见

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String, Configuration) {#constructor_9}

从具有指定 base-uri 和环境配置设置的 [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) 内容创建 HTML 文档。

```java
public HTMLDocument(Stream content, String baseUri, Configuration configuration)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| content | Stream | 用于加载文档的 [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) 内容。 |
| baseUri | String | 文档的基础 URI。 |
| 配置 | 配置 | 环境配置，例如脚本策略、自定义用户样式表等。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 如果 base-uri 参数为 null 则抛出异常。 |

## 备注

参考：

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 示例

```java
// 创建内存流对象
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// 将 HTML 代码写入内存对象
	sw.Write("<p>Hello World! I love HTML!</p>");

	// 重要的是将位置设置为开头，因为 HTMLDocument 从流中的当前位置开始读取。
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// 从 String 变量初始化文档
	using (var document = new HTMLDocument(mem, "."))
	{
		// 将文档保存到磁盘
		document.Save("load-from-stream.html");
	}
}
```

### 另请参见

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url) {#constructor_6}

从具有指定 base-uri 的 [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) 内容创建 HTML 文档，该 base-uri 用于解析相对资源的路径。

```java
public HTMLDocument(Stream content, Url baseUri)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| content | Stream | 用于加载文档的 [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) 内容。 |
| baseUri | Url | 文档的基础 URI。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 如果 base-uri 参数为 null 则抛出异常。 |

## 备注

参考：

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 示例

```java
// 创建内存流对象
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// 将 HTML 代码写入内存对象
	sw.Write("<p>Hello World! I love HTML!</p>");

	// 重要的是将位置设置为开头，因为 HTMLDocument 从流中的当前位置开始读取。
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// 从 String 变量初始化文档
	using (var document = new HTMLDocument(mem, "."))
	{
		// 将文档保存到磁盘
		document.Save("load-from-stream.html");
	}
}
```

### 另请参见

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url, Configuration) {#constructor_7}

从具有指定 base-uri 和环境配置设置的 [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) 内容创建 HTML 文档。

```java
public HTMLDocument(Stream content, Url baseUri, Configuration configuration)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| content | Stream | 用于加载文档的 [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) 内容。 |
| baseUri | Url | 文档的基础 URI。 |
| 配置 | 配置 | 环境配置，例如脚本策略、自定义用户样式表等。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 如果 base-uri 参数为 null 则抛出异常。 |

## 备注

参考：

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## 示例

```java
// 创建内存流对象
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// 将 HTML 代码写入内存对象
	sw.Write("<p>Hello World! I love HTML!</p>");

	// 重要的是将位置设置为开头，因为 HTMLDocument 从流中的当前位置开始读取。
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// 从 String 变量初始化文档
	using (var document = new HTMLDocument(mem, "."))
	{
		// 将文档保存到磁盘
		document.Save("load-from-stream.html");
	}
}
```

### 另请参见

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage) {#constructor_2}

从 [`RequestMessage`](../../../com.aspose.html.net/requestmessage/) 对象创建 HTML 文档。

```java
public HTMLDocument(RequestMessage request)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| request | RequestMessage | 包含文档内容的 [`body`](../../../com.aspose.html.net/requestmessage/content/) 的请求消息。 |

## 备注

根据定义，消息处理程序是接收 Web 请求并返回 Web 响应的类。换句话说，消息处理程序用于在输入期间处理 Web 服务请求和/或在输出期间处理响应。

请访问我们的 [docs site](https://docs.aspose.com/html/net/message-handlers/) 以了解更多关于如何使用此构造函数的示例。

参考：

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### 另请参见

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage, Configuration) {#constructor_3}

从 [RequestMessage](T:com.aspose.html.net.RequestMessage) 对象创建 HTML 文档。

```java
public HTMLDocument(RequestMessage request, Configuration configuration)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| request | RequestMessage | 包含文档内容的 [body](P:com.aspose.html.net.RequestMessage.Content) 的请求消息。 |
| 配置 | 配置 | 环境配置，例如脚本策略、自定义用户样式表等。 |

## 备注

根据定义，消息处理程序是接收 Web 请求并返回 Web 响应的类。换句话说，消息处理程序用于在输入期间处理 Web 服务请求和/或在输出期间处理响应。

请访问我们的 [docs site](https://docs.aspose.com/html/net/message-handlers/) 以了解更多关于如何使用此构造函数的示例。

参考：

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### 另请参见

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
