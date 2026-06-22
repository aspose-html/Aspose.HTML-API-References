---
title: "Document.CreateAttribute"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Document-methode. De Document.createAttribute-methode maakt een nieuw attribuutknooppunt aan en geeft het terug. Het object maakt een knooppunt dat de Attr-interface implementeert. De DOM handhaaft niet welke soorten attributen op deze manier aan een bepaald element kunnen worden toegevoegd."
type: docs

url: /nl/java/com.aspose.html.dom/document/createattribute/
---
## Document.CreateAttribute method

De Document.createAttribute() methode maakt een nieuw attribuutknooppunt aan en geeft het terug. Het object maakt een knooppunt dat de [`Attr`](../../attr/) interface implementeert. De DOM handhaaft niet welke soorten attributen op deze manier aan een bepaald element kunnen worden toegevoegd.

```java
public Attr CreateAttribute(String localName)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | String | name is een String die de naam van het attribuut bevat. |

### Retourwaarde

Een [`Attr`](../../attr/) knooppunt.

## Voorbeelden

```java
var element = document.GetElementById("div");
var attr = document.CreateAttribute("my_attr");
attr.Value = "my_value";
element.SetAttributeNode(attr);
```

### Zie ook

* class [Attr](../../attr/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
