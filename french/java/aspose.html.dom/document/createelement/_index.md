---
title: "Document.CreateElement"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Document. Dans un document HTML, la méthode document.createElement crée l'élément HTML spécifié par tagName ou un HTMLUnknownElement si tagName n'est pas reconnu"
type: docs

url: /fr/java/com.aspose.html.dom/document/createelement/
---
## Document.CreateElement method

Dans un document HTML, la méthode document.createElement() crée l'élément HTML spécifié par tagName, ou un [`HTMLUnknownElement`](../../../com.aspose.html/htmlunknownelement/) si tagName n'est pas reconnu.

```java
public Element CreateElement(String localName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | String | Une chaîne qui spécifie le type d'élément à créer. Le nodeName de l'élément créé est initialisé avec la valeur de tagName. N'utilisez pas de noms qualifiés (comme "html:a") avec cette méthode. Lorsqu'elle est appelée sur un document HTML, createElement() convertit tagName en minuscules avant de créer l'élément. |

### Valeur de retour

Le nouveau [`Element`](../../element/).

## Exemples

```java
var element = document.CreateElement(tagName);
```

### Voir aussi

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
