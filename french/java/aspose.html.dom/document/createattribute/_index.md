---
title: "Document.CreateAttribute"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Document. La méthode Document.createAttribute crée un nouveau nœud d'attribut et le retourne. L'objet créé est un nœud implémentant l'interface Attr. Le DOM n'impose pas le type d'attributs qui peuvent être ajoutés à un élément particulier de cette manière."
type: docs

url: /fr/java/com.aspose.html.dom/document/createattribute/
---
## Document.CreateAttribute method

La méthode Document.createAttribute() crée un nouveau nœud d'attribut et le retourne. L'objet créé est un nœud implémentant l'interface [`Attr`](../../attr/). Le DOM n'impose pas le type d'attributs qui peuvent être ajoutés à un élément particulier de cette manière.

```java
public Attr CreateAttribute(String localName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | String | name est une chaîne contenant le nom de l'attribut. |

### Valeur de retour

Un nœud [`Attr`](../../attr/).

## Exemples

```java
var element = document.GetElementById("div");
var attr = document.CreateAttribute("my_attr");
attr.Value = "my_value";
element.SetAttributeNode(attr);
```

### Voir aussi

* class [Attr](../../attr/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
