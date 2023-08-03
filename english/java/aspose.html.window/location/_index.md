---
title: Location Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Window.Location class. Location objects provide a representation of the address of the active document of their Documents browsing context and allow the current entry of the browsing contexts session history to be changed by adding or replacing entries in the history object
type: docs
weight: 5880
url: /net/com.aspose.html.window/location/
---
## Location class

Location objects provide a representation of the address of the active document of their Document's browsing context, and allow the current entry of the browsing context's session history to be changed, by adding or replacing entries in the history object.

```java
public sealed class Location : Url
```

## Properties

| Name | Description |
| --- | --- |
[getHash]
[setHash] Gets or sets a String representation for the specified URL hash segment. |
[getHost]
[setHost] Gets or sets a String representation for the specified URL host. |
[getHostname]
[setHostname] Gets or sets a String representation for the specified URL hostname. |
[getHref]
[setHref] Gets or sets a serialized representation for the specified URL instance. |
| [getOrigin](../../com.aspose.html/url/origin/) Gets a String representation for the specified URL origin. |
[getPassword]
[setPassword] Gets or sets a String representation for the specified URL password. |
[getPathname]
[setPathname] Gets or sets a String representation for the specified URL path. |
[getPort]
[setPort] Gets or sets a String representation for the specified URL port. |
[getProtocol]
[setProtocol] Gets or sets a String representation for the specified URL schema. |
[getSearch]
[setSearch] Gets or sets a String representation for the specified URL search segment. |
| [getSearchParams](../../com.aspose.html/url/searchparams/) Gets an associated [`IUrlSearchParams`](../../com.aspose.html/iurlsearchparams/) object. |
[getUsername]
[setUsername] Gets or sets a String representation for the specified URL username. |

## Methods

| Name | Description |
| --- | --- |
| [assign](../../com.aspose.html.window/location/assign/)(String) | Navigates to the given page. |
| [equals](../../com.aspose.html/url/equals/)(object) | Determines whether the specified Object, is equal to this instance. |
| [getHashCode](../../com.aspose.html/url/gethashcode/)() | Returns a hash code for this instance. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [reload](../../com.aspose.html.window/location/reload/)() | Reloads the current page. |
| [replace](../../com.aspose.html.window/location/replace/)(String) | Removes the current page from the session history and navigates to the given page. |
| [toJson](../../com.aspose.html/url/tojson/)() | Returns a String that represents this instance. |
| [toString](../../com.aspose.html/url/toString/)() | Returns a String that represents this instance. |

### See Also

* class [Url](../../com.aspose.html/url/)
* package [com.aspose.html.Window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
