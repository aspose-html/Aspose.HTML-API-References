---
title: "Document.CreateAttribute"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Document-Methode. Die Document.createAttribute-Methode erstellt einen neuen Attributknoten und gibt ihn zurück. Das erstellte Objekt ist ein Knoten, der das Attr-Interface implementiert. Das DOM erzwingt nicht, welche Art von Attributen auf diese Weise zu einem bestimmten Element hinzugefügt werden können."
type: docs

url: /de/java/com.aspose.html.dom/document/createattribute/
---
## Document.CreateAttribute method

Die Document.createAttribute()-Methode erstellt einen neuen Attributknoten und gibt ihn zurück. Das erstellte Objekt ist ein Knoten, der das [`Attr`](../../attr/) Interface implementiert. Das DOM erzwingt nicht, welche Art von Attributen auf diese Weise zu einem bestimmten Element hinzugefügt werden können.

```java
public Attr CreateAttribute(String localName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | String | name ist ein String, der den Namen des Attributs enthält. |

### Rückgabewert

Ein [`Attr`](../../attr/) Knoten.

## Beispiele

```java
var element = document.GetElementById("div");
var attr = document.CreateAttribute("my_attr");
attr.Value = "my_value";
element.SetAttributeNode(attr);
```

### Siehe auch

* class [Attr](../../attr/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
