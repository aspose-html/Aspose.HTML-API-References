---
title: HTMLDocument
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 3270
url: /net/aspose.html/htmldocument/
---
## HTMLDocument class

An `HTMLDocument` is the root of the HTML hierarchy and holds the entire content. Besides providing access to the hierarchy, it also provides some convenience methods for accessing certain sets of information from the document.

The following properties have been deprecated in favor of the corresponding ones for the `BODY` element. In DOM Level 2, the method `getElementById` is inherited from the `Document` interface where it was moved to.

See also the [Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109).

```csharp
public class HTMLDocument : Document, IDocumentCSS
```

## Constructors

| Name | Description |
| --- | --- |
| [HTMLDocument](htmldocument)() | Initializes a new instance of the [`HTMLDocument`](../htmldocument) class. |
| [HTMLDocument](htmldocument)(Configuration) | Initializes a new instance of the [`HTMLDocument`](../htmldocument) class. |
| [HTMLDocument](htmldocument)(RequestMessage) | Initializes a new instance of the [`HTMLDocument`](../htmldocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [HTMLDocument](htmldocument)(string) | Initializes a new instance of the [`HTMLDocument`](../htmldocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [HTMLDocument](htmldocument)(Url) | Initializes a new instance of the [`HTMLDocument`](../htmldocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [HTMLDocument](htmldocument)(RequestMessage, Configuration) | Initializes a new instance of the [`HTMLDocument`](../htmldocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [HTMLDocument](htmldocument)(Stream, string) | Initializes a new instance of the [`HTMLDocument`](../htmldocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). Document loading starts from the current position in the stream. |
| [HTMLDocument](htmldocument)(Stream, Url) | Initializes a new instance of the [`HTMLDocument`](../htmldocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). Document loading starts from the current position in the stream. |
| [HTMLDocument](htmldocument)(string, Configuration) | Initializes a new instance of the [`HTMLDocument`](../htmldocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [HTMLDocument](htmldocument)(string, string) | Initializes a new instance of the [`HTMLDocument`](../htmldocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [HTMLDocument](htmldocument)(string, Url) | Initializes a new instance of the [`HTMLDocument`](../htmldocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [HTMLDocument](htmldocument)(Url, Configuration) | Initializes a new instance of the [`HTMLDocument`](../htmldocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [HTMLDocument](htmldocument)(Stream, string, Configuration) | Initializes a new instance of the [`HTMLDocument`](../htmldocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). Document loading starts from the current position in the stream. |
| [HTMLDocument](htmldocument)(Stream, Url, Configuration) | Initializes a new instance of the [`HTMLDocument`](../htmldocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). Document loading starts from the current position in the stream. |
| [HTMLDocument](htmldocument)(string, string, Configuration) | Initializes a new instance of the [`HTMLDocument`](../htmldocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [HTMLDocument](htmldocument)(string, Url, Configuration) | Initializes a new instance of the [`HTMLDocument`](../htmldocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |

## Properties

| Name | Description |
| --- | --- |
| [Anchors](anchors) { get; } | A collection of all the anchor (`A`) elements in a document with a value for the `name` attribute. For reasons of backward compatibility, the returned set of anchors only contains those anchors created with the `name` attribute, not those created with the `id` attribute. Note that in [[XHTML 1.0](http://www.w3.org/TR/2002/REC-xhtml1-20020801)], the `name` attribute (see section 4.10) has no semantics and is only present for legacy user agents: the `id` attribute is used instead. Users should prefer the iterator mechanisms provided by [[DOM Level 2 Traversal](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)] instead. |
| [Applets](applets) { get; } | A collection of all the `OBJECT` elements that include applets and `APPLET` (deprecated) elements in a document. |
| [Body](body) { get; set; } | The element that contains the content for the document. In documents with `BODY` contents, returns the `BODY` element. In frameset documents, this returns the outermost `FRAMESET` element. |
| [Domain](domain) { get; } | The domain name of the server that served the document, or `null` if the server cannot be identified by a domain name. |
| [Forms](forms) { get; } | A collection of all the forms of a document. |
| [Images](images) { get; } | A collection of all the `IMG` elements in a document. The behavior is limited to `IMG` elements for backwards compatibility. As suggested by [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)], to include images, authors may use the `OBJECT` element or the `IMG` element. Therefore, it is recommended not to use this attribute to find the images in the document but `getElementsByTagName` with HTML 4.01 or `getElementsByTagNameNS` with XHTML 1.0. |
| [Links](links) { get; } | A collection of all `AREA` elements and anchor ( `A`) elements in a document with a value for the `href` attribute. |
| [Referrer](referrer) { get; } | Returns the URI [[IETF RFC 2396](http://www.ietf.org/rfc/rfc2396.txt)] of the page that linked to this page. The value is an empty string if the user navigated to the page directly (not through a link, but, for example, via a bookmark). |
| [Title](title) { get; set; } | The title of a document as specified by the `TITLE` element in the head of the document. |

## Methods

| Name | Description |
| --- | --- |
| [GetOverrideStyle](getoverridestyle)(Element, string) | This method is used to retrieve the override style declaration for a specified element and a specified pseudo-element. |
| override [RenderTo](renderto)(IDevice) | This method is used to print the contents of the current document to the specified device. |
| [Save](save)(IOutputStorage) | Saves the document content and resources to the output storage. |
| [Save](save)(string) | Saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](save)(Url) | Saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](save)(IOutputStorage, HTMLSaveFormat) | Saves the document content and resources to the output storage. |
| [Save](save)(IOutputStorage, HTMLSaveOptions) | Saves the document content and resources to the output storage. |
| [Save](save)(IOutputStorage, MarkdownSaveOptions) | Saves the document content and resources to the output storage. |
| [Save](save)(IOutputStorage, MHTMLSaveOptions) | Saves the document content and resources to the output storage. |
| [Save](save)(string, HTMLSaveFormat) | Saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](save)(string, HTMLSaveOptions) | Saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](save)(string, MarkdownSaveOptions) | Saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](save)(string, MHTMLSaveOptions) | Saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](save)(Url, HTMLSaveFormat) | Saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](save)(Url, HTMLSaveOptions) | Saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](save)(Url, MarkdownSaveOptions) | Saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](save)(Url, MHTMLSaveOptions) | Saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files". |

### See Also

* class [Document](../../aspose.html.dom/document)
* interface [IDocumentCSS](../../aspose.html.dom.css/idocumentcss)
* namespace [Aspose.Html](../../aspose.html)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
