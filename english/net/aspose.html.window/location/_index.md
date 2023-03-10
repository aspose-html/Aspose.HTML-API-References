---
title: Location Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Window.Location class. Location objects provide a representation of the address of the active document of their Documents browsing context and allow the current entry of the browsing contexts session history to be changed by adding or replacing entries in the history object
type: docs
weight: 5890
url: /net/aspose.html.window/location/
---
## Location class

Location objects provide a representation of the address of the active document of their Document's browsing context, and allow the current entry of the browsing context's session history to be changed, by adding or replacing entries in the history object.

```csharp
public sealed class Location : Url
```

## Properties

| Name | Description |
| --- | --- |
| [Hash](../../aspose.html/url/hash/) { get; set; } | Gets or sets a string representation for the specified URL hash segment. |
| [Host](../../aspose.html/url/host/) { get; set; } | Gets or sets a string representation for the specified URL host. |
| [Hostname](../../aspose.html/url/hostname/) { get; set; } | Gets or sets a string representation for the specified URL hostname. |
| [Href](../../aspose.html/url/href/) { get; set; } | Gets or sets a serialized representation for the specified URL instance. |
| [Origin](../../aspose.html/url/origin/) { get; } | Gets a string representation for the specified URL origin. |
| [Password](../../aspose.html/url/password/) { get; set; } | Gets or sets a string representation for the specified URL password. |
| [Pathname](../../aspose.html/url/pathname/) { get; set; } | Gets or sets a string representation for the specified URL path. |
| [Port](../../aspose.html/url/port/) { get; set; } | Gets or sets a string representation for the specified URL port. |
| [Protocol](../../aspose.html/url/protocol/) { get; set; } | Gets or sets a string representation for the specified URL schema. |
| [Search](../../aspose.html/url/search/) { get; set; } | Gets or sets a string representation for the specified URL search segment. |
| [SearchParams](../../aspose.html/url/searchparams/) { get; } | Gets an associated [`IUrlSearchParams`](../../aspose.html/iurlsearchparams/) object. |
| [Username](../../aspose.html/url/username/) { get; set; } | Gets or sets a string representation for the specified URL username. |

## Methods

| Name | Description |
| --- | --- |
| [Assign](../../aspose.html.window/location/assign/)(string) | Navigates to the given page. |
| override [Equals](../../aspose.html/url/equals/)(object) | Determines whether the specified Object, is equal to this instance. |
| override [GetHashCode](../../aspose.html/url/gethashcode/)() | Returns a hash code for this instance. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [Reload](../../aspose.html.window/location/reload/)() | Reloads the current page. |
| [Replace](../../aspose.html.window/location/replace/)(string) | Removes the current page from the session history and navigates to the given page. |
| [ToJson](../../aspose.html/url/tojson/)() | Returns a String that represents this instance. |
| override [ToString](../../aspose.html/url/tostring/)() | Returns a String that represents this instance. |

### See Also

* class [Url](../../aspose.html/url/)
* namespace [Aspose.Html.Window](../../aspose.html.window/)
* assembly [Aspose.HTML](../../)
