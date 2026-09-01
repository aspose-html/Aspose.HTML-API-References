---
title: "ICSSStyleDeclaration.RemoveProperty"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode ICSSStyleDeclaration. L'interface de la méthode CSSStyleDeclaration.removeProperty supprime une propriété d'un objet de déclaration de style CSS."
type: docs

url: /fr/java/com.aspose.html.dom.css/icssstyledeclaration/removeproperty/
---
## ICSSStyleDeclaration.RemoveProperty method

L'interface de méthode CSSStyleDeclaration.removeProperty() supprime une propriété d'un objet de déclaration de style CSS.

```java
public String RemoveProperty(String propertyName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| propertyName | String | propertyName est une String représentant le nom de la propriété à supprimer. Notez que les noms de propriétés composés de plusieurs mots sont hyphénés et non en camelCase. |

### Valeur de retour

oldValue est un DOMString égal à la valeur de la propriété CSS avant qu'elle ne soit supprimée.

### Exceptions

| exception | condition |
| --- | --- |
| DOMException | NO_MODIFICATION_ALLOWED_ERR : si la propriété ou le bloc de déclaration est en lecture seule. |

### Voir aussi

* interface [ICSSStyleDeclaration](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
