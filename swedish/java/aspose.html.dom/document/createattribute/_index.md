---
title: "Document.CreateAttribute"
second_title: "Aspose.HTML för Java API-referens"
description: "Document-metod. Document.createAttribute‑metoden skapar en ny attributnod och returnerar den. Objektet skapar en nod som implementerar Attr‑gränssnittet. DOM‑en påtvingar inte vilken typ av attribut som kan läggas till ett specifikt element på detta sätt."
type: docs

url: /sv/java/com.aspose.html.dom/document/createattribute/
---
## Document.CreateAttribute method

Document.createAttribute()-metoden skapar en ny attributnod och returnerar den. Objektet skapar en nod som implementerar [`Attr`](../../attr/)‑gränssnittet. DOM‑en påtvingar inte vilken typ av attribut som kan läggas till ett specifikt element på detta sätt.

```java
public Attr CreateAttribute(String localName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| localName | String | name är en String som innehåller attributets namn. |

### Returvärde

En [`Attr`](../../attr/)‑nod.

## Exempel

```java
var element = document.GetElementById("div");
var attr = document.CreateAttribute("my_attr");
attr.Value = "my_value";
element.SetAttributeNode(attr);
```

### Se även

* class [Attr](../../attr/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
