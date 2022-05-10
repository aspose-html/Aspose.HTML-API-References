---
title: SVGDocument
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 2120
url: /net/aspose.html.dom.svg/svgdocument/
---
## SVGDocument class

An `SVGDocument` is the root of the SVG hierarchy and holds the entire content. Besides providing access to the hierarchy, it also provides some convenience methods for accessing certain sets of information from the document. When an ‘svg’ element is embedded inline as a component of a document from another namespace, such as when an ‘svg’ element is embedded inline within an XHTML document [XHTML], then an SVGDocument object will not exist; instead, the root object in the document object hierarchy will be a Document object of a different type, such as an HTMLDocument object. However, an SVGDocument object will indeed exist when the root element of the XML document hierarchy is an ‘svg’ element, such as when viewing a stand-alone SVG file(i.e., a file with MIME type "image/svg+xml"). In this case, the SVGDocument object will be the root object of the document object model hierarchy.

```csharp
public class SVGDocument : Document, IDocumentCSS
```

## Constructors

| Name | Description |
| --- | --- |
| [SVGDocument](svgdocument)() | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. |
| [SVGDocument](svgdocument)(Configuration) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. |
| [SVGDocument](svgdocument)(RequestMessage) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [SVGDocument](svgdocument)(string) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [SVGDocument](svgdocument)(Url) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [SVGDocument](svgdocument)(RequestMessage, Configuration) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [SVGDocument](svgdocument)(Stream, string) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). Document loading starts from the current position in the stream. |
| [SVGDocument](svgdocument)(Stream, Url) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). Document loading starts from the current position in the stream. |
| [SVGDocument](svgdocument)(string, Configuration) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [SVGDocument](svgdocument)(string, string) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [SVGDocument](svgdocument)(string, Url) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [SVGDocument](svgdocument)(Url, Configuration) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [SVGDocument](svgdocument)(Stream, string, Configuration) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). Document loading starts from the current position in the stream. |
| [SVGDocument](svgdocument)(Stream, Url, Configuration) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). Document loading starts from the current position in the stream. |
| [SVGDocument](svgdocument)(string, string, Configuration) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |
| [SVGDocument](svgdocument)(string, Url, Configuration) | Initializes a new instance of the [`SVGDocument`](../svgdocument) class. Constructor works synchronously, it waits for loading of all the external resources (images, scripts, etc.). To load document asynchronously use method [`Navigate`](../../aspose.html.dom/document/navigate) or its overloads. Or you can disable loading of some external resources by setting appropriate flags in [`Security`](../../aspose.html.dom/ibrowsingcontext/security). |

## Properties

| Name | Description |
| --- | --- |
| [Domain](domain) { get; } | The domain name of the server that served the document, or a null string if the server cannot be identified by a domain name. |
| [Referrer](referrer) { get; } | Returns the URI of the page that linked to this page. The value is an empty string if the user navigated to the page directly (not through a link, but, for example, via a bookmark). |
| [RootElement](rootelement) { get; } | The root ‘svg’ in the document hierarchy. |
| [Title](title) { get; } | The title of a document as specified by the ‘title’ sub-element of the ‘svg’ root element (i.e., Here is the title...) |
| [URL](url) { get; } | The complete URI of the document. |

## Methods

| Name | Description |
| --- | --- |
| [GetOverrideStyle](getoverridestyle)(Element, string) | This method is used to retrieve the override style declaration for a specified element and a specified pseudo-element. |
| override [RenderTo](renderto)(IDevice) | This method is used to print the contents of the current document to the specified device. |
| [Save](save)(IOutputStorage) | Saves the document content and resources to the output storage. |
| [Save](save)(string) | Saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](save)(Url) | Saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](save)(IOutputStorage, SVGSaveFormat) | Saves the document content and resources to the output storage. |
| [Save](save)(IOutputStorage, SVGSaveOptions) | Saves the document content and resources to the output storage. |
| [Save](save)(string, SVGSaveFormat) | Saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](save)(string, SVGSaveOptions) | Saves the document to local file specified by `path`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](save)(Url, SVGSaveFormat) | Saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files". |
| [Save](save)(Url, SVGSaveOptions) | Saves the document to local file specified by `url`. All resources used in this document will be saved in to adjacent folder, whose name will be constructed as: output_file_name + "_files". |

### See Also

* class [Document](../../aspose.html.dom/document)
* interface [IDocumentEvent](../../aspose.html.dom.events/idocumentevent)
* interface [IDocumentCSS](../../aspose.html.dom.css/idocumentcss)
* namespace [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
