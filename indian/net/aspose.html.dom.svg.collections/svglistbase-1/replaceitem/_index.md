---
title: SVGListBase1.ReplaceItem
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: SVGListBase तरक. सूच में मजूद आइटम क नए आइटम से बदलत है.
type: docs
weight: 110
url: /hi/net/aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

सूची में मौजूदा आइटम को नए आइटम से बदलता है.

```csharp
public T ReplaceItem(T newItem, ulong index)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newItem | T | आइटम जो सूची में डाला जाना है। |
| index | UInt64 | उस वस्तु का सूचकांक जिसे बदला जाना है। पहला आइटम नंबर 0 है। |

### प्रतिलाभ की मात्रा

डाली गई वस्तु।

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | कोड[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). उठाया गया जब सूची को संशोधित नहीं किया जा सकता। |
| [DOMException](../../../aspose.html.dom/domexception/) | कोड[`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). उठाया जाता है अगर इंडेक्स संख्या संख्याऑफइटम्स से अधिक या उसके बराबर है। |

### यह सभी देखें

* class [SVGListBase&lt;T&gt;](../)
* नाम स्थान [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* सभा [Aspose.HTML](../../../)


