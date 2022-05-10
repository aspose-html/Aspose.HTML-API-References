---
title: HTMLDocument
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 3270
url: /net/aspose.html/htmldocument/
---
## HTMLDocument class

Represents an HTML document. All top level HTML objects are added to this object. This class represents the HTML page as what we see in browser. All forms, tables, scripts, ... are added to the HTML page via the interfaces of this class. [HTMLDocument](https://dom.spec.whatwg.org/#ref-for-dom-domimplementation-createhtmldocument) is html implementation of most general [Document](https://dom.spec.whatwg.org/#document) interface and both are core or root point of [DOM](https://dom.spec.whatwg.org/) - Document Object Model. These concepts are in full accordance with officical web development basis or standards. For the purposes of web development, you can generally think of HTMLDocument as an alias for Document, upon which HTMLDocument is based.

```csharp
public class HTMLDocument : Document, IDocumentCSS
```

## Constructors

| Name | Description |
| --- | --- |
| [HTMLDocument](htmldocument)() | The HTMLDocument constructor creates a new HTML Document object that is a web page loaded in the browser and serving as an entry point into the page's content. |
| [HTMLDocument](htmldocument)(Configuration) | The HTMLDocument constructor creates a new HTML Document object that is a web page loaded in the browser and serving as an entry point into the page's content. |
| [HTMLDocument](htmldocument)(RequestMessage) | Creates an HTML document from the [`RequestMessage`](../../aspose.html.net/requestmessage) object. |
| [HTMLDocument](htmldocument)(string) | Loads the HTML document from an address. |
| [HTMLDocument](htmldocument)(Url) | Loads the HTML document from a URL. |
| [HTMLDocument](htmldocument)(RequestMessage, Configuration) | Creates an HTML document from the [RequestMessage](T:Aspose.Html.Net.RequestMessage) object. |
| [HTMLDocument](htmldocument)(Stream, string) | Creates an HTML document from a [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) content with specified base-uri that is used to resolve the relative resources' path. |
| [HTMLDocument](htmldocument)(Stream, Url) | Creates an HTML document from a [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) content with specified base-uri that is used to resolve the relative resources' path. |
| [HTMLDocument](htmldocument)(string, Configuration) | Loads the HTML document from an address with specified environment configuration settings. |
| [HTMLDocument](htmldocument)(string, string) | Creates an HTML document from a String content with specified base-uri. |
| [HTMLDocument](htmldocument)(string, Url) | Creates an HTML document from a String content with specified base-uri. |
| [HTMLDocument](htmldocument)(Url, Configuration) | Loads the HTML document from a URL with specified environment configuration settings. |
| [HTMLDocument](htmldocument)(Stream, string, Configuration) | Creates an HTML document from a [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) content with specified base-uri and environment configuration settings. |
| [HTMLDocument](htmldocument)(Stream, Url, Configuration) | Creates an HTML document from a [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) content with specified base-uri and environment configuration settings. |
| [HTMLDocument](htmldocument)(string, string, Configuration) | Creates an HTML document from a String content with specified base-uri and environment configuration settings. |
| [HTMLDocument](htmldocument)(string, Url, Configuration) | Creates an HTML document from a String content with specified base-uri and environment configuration settings. |

## Properties

| Name | Description |
| --- | --- |
| [Anchors](anchors) { get; } | A collection of all the anchor (`A`) elements in a document with a value for the `name` attribute. For reasons of backward compatibility, the returned set of anchors only contains those anchors created with the `name` attribute, not those created with the `id` attribute. Note that in [[XHTML 1.0](http://www.w3.org/TR/2002/REC-xhtml1-20020801)], the `name` attribute (see section 4.10) has no semantics and is only present for legacy user agents: the `id` attribute is used instead. Users should prefer the iterator mechanisms provided by [[DOM Level 2 Traversal](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)] instead. |
| [Applets](applets) { get; } | A collection of all the `OBJECT` elements that include applets and `APPLET` (deprecated) elements in a document. |
| [Body](body) { get; set; } | The element that contains the content for the document. In documents with `BODY` contents, returns the `BODY`element. In frameset documents, this returns the outermost `FRAMESET` element. |
| [Domain](domain) { get; } | The domain name of the server that served the document, or `null` if the server cannot be identified by a domain name. |
| [Forms](forms) { get; } | A collection of all the forms of a document. |
| [Images](images) { get; } | A collection of all the `IMG` elements in a document. The behavior is limited to `IMG` elements for backwards compatibility. As suggested by [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)], to include images, authors may use the `OBJECT` element or the `IMG` element. Therefore, it is recommended not to use this attribute to find the images in the document but `getElementsByTagName` with HTML 4.01 or `getElementsByTagNameNS` with XHTML 1.0. |
| [Links](links) { get; } | A collection of all `AREA` elements and anchor (`A`) elements in a document with a value for the `href` attribute. |
| [Referrer](referrer) { get; } | Returns the URI [[IETF RFC 2396](http://www.ietf.org/rfc/rfc2396.txt)] of the page that linked to this page. The value is an empty string if the user navigated to the page directly (not through a link, but, for example, via a bookmark). |
| [Title](title) { get; set; } | The title of a document as specified by the `TITLE` element in the head of the document. |

## Methods

| Name | Description |
| --- | --- |
| [GetOverrideStyle](getoverridestyle)(Element, string) | This method is used to retrieve the override style declaration for a specified element and a specified pseudo-element. |
| override [RenderTo](renderto)(IDevice) | This method is used to print the contents of the current document to the specified device. |
| [Save](save)(IOutputStorage) | Saves the document content and resources to the output storage. |
| [Save](save)(string) | Saves the document to a local file specified by path. All resources used in this document will be saved into an adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](save)(Url) | Saves the document to a local file specified by url. All resources used in this document will be saved into an adjacent folder, whose name will be constructed as output_file_name + "_files". |
| [Save](save)(IOutputStorage, HTMLSaveFormat) | Saves the document content and resources to the output storage. |
| [Save](save)(IOutputStorage, HTMLSaveOptions) | Saves the document content and resources to the output storage. |
| [Save](save)(IOutputStorage, MarkdownSaveOptions) | Saves the document content and resources to the output storage. |
| [Save](save)(IOutputStorage, MHTMLSaveOptions) | Saves the document content and resources to the output storage. |
| [Save](save)(string, HTMLSaveFormat) | Saves the document to a local file specified by path. All resources used in this document will be saved into an adjacent folder, whose name will be constructed as output_file_name + "_files". |
| [Save](save)(string, HTMLSaveOptions) | Saves the document to a local file specified by path. All resources used in this document will be saved into an adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](save)(string, MarkdownSaveOptions) | Saves the document to a local file specified by path. All resources used in this document will be saved into an adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](save)(string, MHTMLSaveOptions) | Saves the document to a local file specified by path. All resources used in this document will be saved into an adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](save)(Url, HTMLSaveFormat) | Saves the document to a local file specified by url. All resources used in this document will be saved into an adjacent folder, whose name will be constructed as output_file_name + "_files". |
| [Save](save)(Url, HTMLSaveOptions) | Saves the document to a local file specified by url. All resources used in this document will be saved into an adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](save)(Url, MarkdownSaveOptions) | Saves the document to a local file specified by url. All resources used in this document will be saved into an adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](save)(Url, MHTMLSaveOptions) | Saves the document to a local file specified by url. All resources used in this document will be saved into an adjacent folder, whose name will be constructed as: output_file_name + "_files". |

### Remarks

More info about HTMLDocument, Document and DOM can be obtained in popular web development resources:

[General Document interface](https://developer.mozilla.org/en-US/docs/Web/API/Document).[Html specific HTMLDocument interface](https://developer.mozilla.org/en-US/docs/Web/API/HTMLDocument).[What is the HTML DOM](https://www.w3schools.com/js/js_htmldom.asp).

Standards Reference:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Examples

```csharp
    // Create an instance of an HTML document
	using (var document = new HTMLDocument())
      {
        // Create a style element and assign the green color for all elements with class-name equals 'gr'.
        var style = document.CreateElement("style");
        style.TextContent = ".gr { color: green }";

        // Find the document header element and append style element to the header
        var head = document.GetElementsByTagName("head").First();
        head.AppendChild(style);

        // Create a paragraph element with class-name 'gr'.
        var p = (HTMLParagraphElement)document.CreateElement("p");
        p.ClassName = "gr";

        // Create a text node
        var text = document.CreateTextNode("Hello World!!");

        // Append the text node to the paragraph
        p.AppendChild(text);

        // Append the paragraph to the document body element
        document.Body.AppendChild(p);

        // Save the HTML document to a file 
        document.Save(Path.Combine(OutputDir, "using-dom.html"));

        // Create an instance of the PDF output device and render the document into this device
        using (var device = new PdfDevice(Path.Combine(OutputDir, "using-dom.pdf")))
        {
          // Render HTML to PDF
          document.RenderTo(device);
        }
      }       
```

### See Also

* class [Document](../../aspose.html.dom/document)
* interface [IDocumentCSS](../../aspose.html.dom.css/idocumentcss)
* namespace [Aspose.Html](../../aspose.html)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
