---
title: Location Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Window.Location class. Location objects provide a representation of the address of the active document of their Documents browsing context and allow the current entry of the browsing contexts session history to be changed by adding or replacing entries in the history object
type: docs
weight: 6150
url: /net/aspose.html.window/location/
---
## Location class

Location objects provide a representation of the address of the active document of their Document's browsing context, and allow the current entry of the browsing context's session history to be changed, by adding or replacing entries in the history object.

```csharp
public sealed class Location : DOMObject
```

## Properties

| Name | Description |
| --- | --- |
| [Hash](../../aspose.html.window/location/hash/) { get; set; } | Returns the Location object's URL's fragment (includes leading "#" if non-empty). Can be set, to navigate to the same URL with a changed fragment(ignores leading "#"). |
| [Host](../../aspose.html.window/location/host/) { get; set; } | Returns the Location object's URL's host and port (if different from the default port for the scheme). Can be set, to navigate to the same URL with a changed host and port. |
| [Hostname](../../aspose.html.window/location/hostname/) { get; set; } | Returns the Location object's URL's host. Can be set, to navigate to the same URL with a changed host. |
| [Href](../../aspose.html.window/location/href/) { get; set; } | Returns the Location object's URL. Can be set, to navigate to the given URL. |
| [Origin](../../aspose.html.window/location/origin/) { get; } | Returns the Location object's URL's origin. |
| [Pathname](../../aspose.html.window/location/pathname/) { get; set; } | Returns the Location object's URL's path. Can be set, to navigate to the same URL with a changed path. |
| [Port](../../aspose.html.window/location/port/) { get; set; } | Returns the Location object's URL's port. Can be set, to navigate to the same URL with a changed port. |
| [Protocol](../../aspose.html.window/location/protocol/) { get; set; } | Returns the Location object's URL's scheme. Can be set, to navigate to the same URL with a changed scheme. |
| [Search](../../aspose.html.window/location/search/) { get; set; } | Returns the Location object's URL's query (includes leading "?" if non-empty). Can be set, to navigate to the same URL with a changed query(ignores leading "?"). |

## Methods

| Name | Description |
| --- | --- |
| [Assign](../../aspose.html.window/location/assign/)(*string*) | Navigates to the given page. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object Type. |
| [Reload](../../aspose.html.window/location/reload/)() | Reloads the current page. |
| [Replace](../../aspose.html.window/location/replace/)(*string*) | Removes the current page from the session history and navigates to the given page. |
| override [ToString](../../aspose.html.window/location/tostring/)() | Returns the Location object's URL. |

### See Also

* class [DOMObject](../../aspose.html.dom/domobject/)
* namespace [Aspose.Html.Window](../../aspose.html.window/)
* assembly [Aspose.HTML](../../)
