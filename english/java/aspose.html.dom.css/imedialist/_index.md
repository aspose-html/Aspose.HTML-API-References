---
title: IMediaList Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.css.IMediaList interface. The MediaList interface provides the abstraction of an ordered collection of media without defining or constraining how this collection is implemented. An empty list is the same as a list that contains the medium all
type: docs

url: /java/com.aspose.html.dom.css/imedialist/
---
## IMediaList interface

The MediaList interface provides the abstraction of an ordered collection of media, without defining or constraining how this collection is implemented. An empty list is the same as a list that contains the medium "all".

See also the [CSS Object Model (CSSOM) # ](https://www.w3.org/TR/cssom-1/#the-medialist-interface)[MediaList](https://www.w3.org/TR/cssom-1/#the-medialist-interface).

```java
public interface IMediaList : IEnumerable<String>
```

## Properties

| Name | Description |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/imedialist/item/) RetuThe item(index) method must return a serialization of the media query in the collection of media queries given by index, or null, if index is greater than or equal to the number of media queries in the collection of media queries. |
| [getLength](../../com.aspose.html.dom.css/imedialist/length/) The length attribute must return the number of media queries in the collection of media queries. The range of valid media is 0 to length-1 inclusive. |
| [getMediaText](../../com.aspose.html.dom.css/imedialist/mediatext/) A Stringifier that returns a DOMString representing the MediaList as text, and also allows you to set a new MediaList. |

## Methods

| Name | Description |
| --- | --- |
| [appendMedium](../../com.aspose.html.dom.css/imedialist/appendmedium/)(String) | Adds the medium newMedium to the end of the list. If the newMedium is already used, it is first removed. |
| [deleteMedium](../../com.aspose.html.dom.css/imedialist/deletemedium/)(String) | Deletes the medium indicated by oldMedium from the list. |

## Remarks

Note: MediaList is a live list; updating the list using properties or methods listed below will immediately update the behavior of the document.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Reference

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # medialist](https://drafts.csswg.org/cssom/#medialist) – The CSSOM definition.

## Examples

The following would log to the console a textual representation of the MediaList of the first stylesheet applied to the current document.

```java
var stylesheets = document.StyleSheets;
var stylesheet = stylesheets[0];
Console.Write(stylesheet.Media.MediaText);
```

### See Also

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
