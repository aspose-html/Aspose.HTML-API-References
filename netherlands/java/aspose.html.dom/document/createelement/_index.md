---
title: "Document.CreateElement"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Documentmethode. In een HTML‑document maakt de document.createElement‑methode het HTML‑element aan dat wordt opgegeven door tagName of een HTMLUnknownElement als tagName niet wordt herkend."
type: docs

url: /nl/java/com.aspose.html.dom/document/createelement/
---
## Document.CreateElement method

In een HTML‑document maakt de document.createElement()‑methode het HTML‑element aan dat wordt opgegeven door tagName, of een [`HTMLUnknownElement`](../../../com.aspose.html/htmlunknownelement/) als tagName niet wordt herkend.

```java
public Element CreateElement(String localName)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| localName | String | Een string die het type element specificeert dat moet worden aangemaakt. De nodeName van het aangemaakte element wordt geïnitialiseerd met de waarde van tagName. Gebruik geen gekwalificeerde namen (zoals \"html:a\") met deze methode. Wanneer aangeroepen op een HTML‑document, zet createElement() tagName om naar kleine letters voordat het element wordt aangemaakt. |

### Retourwaarde

Het nieuwe [`Element`](../../element/).

## Voorbeelden

```java
var element = document.CreateElement(tagName);
```

### Zie ook

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
