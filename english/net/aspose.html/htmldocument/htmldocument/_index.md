---
title: HTMLDocument
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 10
url: /net/aspose.html/htmldocument/htmldocument/
---
## HTMLDocument constructor (1 of 16)

The HTMLDocument constructor creates a new HTML Document object that is a web page loaded in the browser and serving as an entry point into the page's content.

```csharp
public HTMLDocument()
```

### Remarks

Note: The document is created with a default value for the base-url property that is equal to 'about:blank'.

Reference:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Examples

Once the document object is created, it can be filled later with HTML elements. The following code snippet shows the usage of the default HTMLDocument() constructor to create an empty HTML document and save it to a file.

```csharp
using (var document = new HTMLDocument())
{
	// Work with the document here
	...	
	
	// Save the document to a file
	document.Save("document.html");
}
```

### See Also

* class [HTMLDocument](../../htmldocument)
* namespace [Aspose.Html](../../htmldocument)
* assembly [Aspose.HTML](../../../)

---

## HTMLDocument constructor (2 of 16)

The HTMLDocument constructor creates a new HTML Document object that is a web page loaded in the browser and serving as an entry point into the page's content.

```csharp
public HTMLDocument(Configuration configuration)
```

| Parameter | Type | Description |
| --- | --- | --- |
| configuration | Configuration | The environment configuration such as scripts policy, custom user stylesheet, etc. |

### Remarks

Note: The document is created with a default value for the base-url property that is equal to 'about:blank'.

Reference:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Examples

The following example demonstrates how to use the configuration object to disable scripts:

```csharp
// Prepare HTML code and save it to a file
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Create an instance of Configuration
using (var configuration = new Configuration())
{
	// Mark 'scripts' as an untrusted resource
	configuration.Security |= Sandbox.Scripts;

	// Initialize an HTML document with specified configuration
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// Convert HTML to PDF
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### See Also

* class [Configuration](../../configuration)
* class [HTMLDocument](../../htmldocument)
* namespace [Aspose.Html](../../htmldocument)
* assembly [Aspose.HTML](../../../)

---

## HTMLDocument constructor (3 of 16)

Loads the HTML document from a URL.

Note: In case if you pass a wrong URL that can’t be reached right at the moment, the library throws the [`DOMException`](../../../aspose.html.dom/domexception) with specialized code ‘NetworkError’ to inform you that the selected resource can not be found.

```csharp
public HTMLDocument(Url url)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | The HTML document URL to open. |

### Remarks

Reference:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Examples

Load a document from 'https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html' web page:

```csharp
using (var document = new HTMLDocument("https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html"))
{
	// Write the document content to the output stream
	Console.WriteLine(document.DocumentElement.OuterHTML);
}
```

### See Also

* class [Url](../../url)
* class [HTMLDocument](../../htmldocument)
* namespace [Aspose.Html](../../htmldocument)
* assembly [Aspose.HTML](../../../)

---

## HTMLDocument constructor (4 of 16)

Loads the HTML document from a URL with specified environment configuration settings.

Note: In case if you pass a wrong URL that can’t be reached right at the moment, the library throws the [DOMException](T:Aspose.Html.Dom.DOMException) with specialized code ‘NetworkError’ to inform you that the selected resource can not be found.

```csharp
public HTMLDocument(Url url, Configuration configuration)
```

| Parameter | Type | Description |
| --- | --- | --- |
| url | Url | The HTML document URL to open. |
| configuration | Configuration | The environment configuration such as scripts policy, custom user stylesheet, etc. |

### Remarks

Reference:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Examples

```csharp
The following example demonstrates how to use the configuration object to disable scripts:

// Prepare HTML code and save it to a file
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Create an instance of Configuration
using (var configuration = new Configuration())
{
	// Mark 'scripts' as an untrusted resource
	configuration.Security |= Sandbox.Scripts;

	// Initialize an HTML document with specified configuration
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// Convert HTML to PDF
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### See Also

* class [Url](../../url)
* class [Configuration](../../configuration)
* class [HTMLDocument](../../htmldocument)
* namespace [Aspose.Html](../../htmldocument)
* assembly [Aspose.HTML](../../../)

---

## HTMLDocument constructor (5 of 16)

Loads the HTML document from an address.

Note: In case if you pass a wrong URL that can’t be reached right at the moment, the library throws the [`DOMException`](../../../aspose.html.dom/domexception) with specialized code ‘NetworkError’ to inform you that the selected resource can not be found.

```csharp
public HTMLDocument(string address)
```

| Parameter | Type | Description |
| --- | --- | --- |
| address | String | The HTML document address to open. |

### Remarks

Reference:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Examples

Initialize an HTML document from an address.

```csharp
using (var document = new HTMLDocument("./my-folder/document.html")))
{
	...
}
```

### See Also

* class [HTMLDocument](../../htmldocument)
* namespace [Aspose.Html](../../htmldocument)
* assembly [Aspose.HTML](../../../)

---

## HTMLDocument constructor (6 of 16)

Loads the HTML document from an address with specified environment configuration settings.

Note: In case if you pass a wrong URL that can’t be reached right at the moment, the library throws the [`DOMException`](../../../aspose.html.dom/domexception) with specialized code ‘NetworkError’ to inform you that the selected resource can not be found.

```csharp
public HTMLDocument(string address, Configuration configuration)
```

| Parameter | Type | Description |
| --- | --- | --- |
| address | String | The HTML document address to open. |
| configuration | Configuration | The environment configuration such as scripts policy, custom user stylesheet, etc. |

### Remarks

Reference:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Examples

```csharp
// Create an instance of Configuration
using (var configuration = new Configuration())
{
	// Mark 'scripts' as an untrusted resource
	configuration.Security |= Sandbox.Scripts;
	
	using (var document = new HTMLDocument("./my-folder/document.html", configuration)))
	{
		...
	}
}
```

### See Also

* class [Configuration](../../configuration)
* class [HTMLDocument](../../htmldocument)
* namespace [Aspose.Html](../../htmldocument)
* assembly [Aspose.HTML](../../../)

---

## HTMLDocument constructor (7 of 16)

Creates an HTML document from a String content with specified base-uri.

```csharp
public HTMLDocument(string content, string baseUri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | The string content to load the document with. |
| baseUri | String | The base URI of the document. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Throws if the base-uri parament is null. |

### Remarks

Reference:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Examples

```csharp
// Prepare HTML code
var html_code = "<p>Hello World!</p>";

// Initialize a document from the string variable
using (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### See Also

* class [HTMLDocument](../../htmldocument)
* namespace [Aspose.Html](../../htmldocument)
* assembly [Aspose.HTML](../../../)

---

## HTMLDocument constructor (8 of 16)

Creates an HTML document from a String content with specified base-uri and environment configuration settings.

```csharp
public HTMLDocument(string content, string baseUri, Configuration configuration)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | The string content to load the document with. |
| baseUri | String | The base URI of the document. |
| configuration | Configuration | The environment configuration such as scripts policy, custom user stylesheet, etc. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Throws if the base-uri parament is null. |

### Remarks

Reference:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Examples

```csharp
// Prepare HTML code
var html_code = "<p>Hello World!</p>";

// Initialize a document from the string variable
using (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### See Also

* class [Configuration](../../configuration)
* class [HTMLDocument](../../htmldocument)
* namespace [Aspose.Html](../../htmldocument)
* assembly [Aspose.HTML](../../../)

---

## HTMLDocument constructor (9 of 16)

Creates an HTML document from a String content with specified base-uri.

```csharp
public HTMLDocument(string content, Url baseUri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | The string content to load the document with. |
| baseUri | Url | The base URI of the document. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Throws if the base-uri parament is null. |

### Remarks

Reference:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Examples

```csharp
// Prepare HTML code
var html_code = "<p>Hello World!</p>";

// Initialize a document from the string variable
using (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### See Also

* class [Url](../../url)
* class [HTMLDocument](../../htmldocument)
* namespace [Aspose.Html](../../htmldocument)
* assembly [Aspose.HTML](../../../)

---

## HTMLDocument constructor (10 of 16)

Creates an HTML document from a String content with specified base-uri and environment configuration settings.

```csharp
public HTMLDocument(string content, Url baseUri, Configuration configuration)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | String | The string content to load the document with. |
| baseUri | Url | The base URI of the document. |
| configuration | Configuration | The environment configuration such as scripts policy, custom user stylesheet, etc. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Throws if the base-uri parament is null. |

### Remarks

Reference:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Examples

```csharp
// Prepare HTML code
var html_code = "<p>Hello World!</p>";

// Initialize a document from the string variable
using (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### See Also

* class [Url](../../url)
* class [Configuration](../../configuration)
* class [HTMLDocument](../../htmldocument)
* namespace [Aspose.Html](../../htmldocument)
* assembly [Aspose.HTML](../../../)

---

## HTMLDocument constructor (11 of 16)

Creates an HTML document from a [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) content with specified base-uri that is used to resolve the relative resources' path.

```csharp
public HTMLDocument(Stream content, string baseUri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | Stream | The [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) content to load the document with. |
| baseUri | String | The base URI of the document. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Throws if the base-uri parament is null. |

### Remarks

Reference:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Examples

```csharp
// Create a memory stream object
using (var mem = new MemoryStream())
using (var sw = new StreamWriter(mem))
{
	// Write the HTML code into memory object
	sw.Write("<p>Hello World! I love HTML!</p>");

	// It is important to set the position to the beginning since HTMLDocument starts the reading exactly from the current position within the stream
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Initialize a document from the string variable
	using (var document = new HTMLDocument(mem, "."))
	{
		// Save the document to a disk
		document.Save("load-from-stream.html");
	}
}
```

### See Also

* class [HTMLDocument](../../htmldocument)
* namespace [Aspose.Html](../../htmldocument)
* assembly [Aspose.HTML](../../../)

---

## HTMLDocument constructor (12 of 16)

Creates an HTML document from a [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) content with specified base-uri and environment configuration settings.

```csharp
public HTMLDocument(Stream content, string baseUri, Configuration configuration)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | Stream | The [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) content to load the document with. |
| baseUri | String | The base URI of the document. |
| configuration | Configuration | The environment configuration such as scripts policy, custom user stylesheet, etc. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Throws if the base-uri parament is null. |

### Remarks

Reference:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Examples

```csharp
// Create a memory stream object
using (var mem = new MemoryStream())
using (var sw = new StreamWriter(mem))
{
	// Write the HTML code into memory object
	sw.Write("<p>Hello World! I love HTML!</p>");

	// It is important to set the position to the beginning since HTMLDocument starts the reading exactly from the current position within the stream
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Initialize a document from the string variable
	using (var document = new HTMLDocument(mem, "."))
	{
		// Save the document to a disk
		document.Save("load-from-stream.html");
	}
}
```

### See Also

* class [Configuration](../../configuration)
* class [HTMLDocument](../../htmldocument)
* namespace [Aspose.Html](../../htmldocument)
* assembly [Aspose.HTML](../../../)

---

## HTMLDocument constructor (13 of 16)

Creates an HTML document from a [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) content with specified base-uri that is used to resolve the relative resources' path.

```csharp
public HTMLDocument(Stream content, Url baseUri)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | Stream | The [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) content to load the document with. |
| baseUri | Url | The base URI of the document. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Throws if the base-uri parament is null. |

### Remarks

Reference:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Examples

```csharp
// Create a memory stream object
using (var mem = new MemoryStream())
using (var sw = new StreamWriter(mem))
{
	// Write the HTML code into memory object
	sw.Write("<p>Hello World! I love HTML!</p>");

	// It is important to set the position to the beginning since HTMLDocument starts the reading exactly from the current position within the stream
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Initialize a document from the string variable
	using (var document = new HTMLDocument(mem, "."))
	{
		// Save the document to a disk
		document.Save("load-from-stream.html");
	}
}
```

### See Also

* class [Url](../../url)
* class [HTMLDocument](../../htmldocument)
* namespace [Aspose.Html](../../htmldocument)
* assembly [Aspose.HTML](../../../)

---

## HTMLDocument constructor (14 of 16)

Creates an HTML document from a [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) content with specified base-uri and environment configuration settings.

```csharp
public HTMLDocument(Stream content, Url baseUri, Configuration configuration)
```

| Parameter | Type | Description |
| --- | --- | --- |
| content | Stream | The [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) content to load the document with. |
| baseUri | Url | The base URI of the document. |
| configuration | Configuration | The environment configuration such as scripts policy, custom user stylesheet, etc. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Throws if the base-uri parament is null. |

### Remarks

Reference:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Examples

```csharp
// Create a memory stream object
using (var mem = new MemoryStream())
using (var sw = new StreamWriter(mem))
{
	// Write the HTML code into memory object
	sw.Write("<p>Hello World! I love HTML!</p>");

	// It is important to set the position to the beginning since HTMLDocument starts the reading exactly from the current position within the stream
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Initialize a document from the string variable
	using (var document = new HTMLDocument(mem, "."))
	{
		// Save the document to a disk
		document.Save("load-from-stream.html");
	}
}
```

### See Also

* class [Url](../../url)
* class [Configuration](../../configuration)
* class [HTMLDocument](../../htmldocument)
* namespace [Aspose.Html](../../htmldocument)
* assembly [Aspose.HTML](../../../)

---

## HTMLDocument constructor (15 of 16)

Creates an HTML document from the [`RequestMessage`](../../../aspose.html.net/requestmessage) object.

```csharp
public HTMLDocument(RequestMessage request)
```

| Parameter | Type | Description |
| --- | --- | --- |
| request | RequestMessage | The request message that contains a [`body`](../../../aspose.html.net/requestmessage/content) with document content. |

### Remarks

By definition, a message handler is a class that receives a Web request and returns a Web response. In other words, a message handler is used to process a Web service request during input and/or to process the response during output.

Please, visit our [docs site](https://docs.aspose.com/html/net/message-handlers/) to see more scenarios on how to use this constructor.

Reference:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### See Also

* class [RequestMessage](../../../aspose.html.net/requestmessage)
* class [HTMLDocument](../../htmldocument)
* namespace [Aspose.Html](../../htmldocument)
* assembly [Aspose.HTML](../../../)

---

## HTMLDocument constructor (16 of 16)

Creates an HTML document from the [RequestMessage](T:Aspose.Html.Net.RequestMessage) object.

```csharp
public HTMLDocument(RequestMessage request, Configuration configuration)
```

| Parameter | Type | Description |
| --- | --- | --- |
| request | RequestMessage | The request message that contains a [body](P:Aspose.Html.Net.RequestMessage.Content) with document content. |
| configuration | Configuration | The environment configuration such as scripts policy, custom user stylesheet, etc. |

### Remarks

By definition, a message handler is a class that receives a Web request and returns a Web response. In other words, a message handler is used to process a Web service request during input and/or to process the response during output.

Please, visit our [docs site](https://docs.aspose.com/html/net/message-handlers/) to see more scenarios on how to use this constructor.

Reference:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### See Also

* class [RequestMessage](../../../aspose.html.net/requestmessage)
* class [Configuration](../../configuration)
* class [HTMLDocument](../../htmldocument)
* namespace [Aspose.Html](../../htmldocument)
* assembly [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->