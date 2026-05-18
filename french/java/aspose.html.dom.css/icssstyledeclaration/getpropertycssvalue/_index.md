---
title: "ICSSStyleDeclaration.GetPropertyCSSValue"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode ICSSStyleDeclaration. Utilisée pour récupérer la représentation objet de la valeur d'une propriété CSS si elle a été explicitement définie dans ce bloc de déclaration. Cette méthode renvoie null si la propriété est une propriété raccourcie. Les valeurs des propriétés raccourcies ne peuvent être accédées et modifiées que sous forme de chaînes en utilisant les méthodes getPropertyValue et setProperty."
type: docs

url: /fr/java/com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/
---
## ICSSStyleDeclaration.GetPropertyCSSValue method

Utilisé pour récupérer la représentation objet de la valeur d'une propriété CSS si elle a été explicitement définie dans ce bloc de déclaration. Cette méthode renvoie null si la propriété est une propriété raccourcie. Les valeurs des propriétés raccourcies ne peuvent être accédées et modifiées que sous forme de chaînes, en utilisant les méthodes getPropertyValue et setProperty.

```java
public CSSValue GetPropertyCSSValue(String propertyName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| propertyName | String | propertyName est une String représentant le nom de la propriété à récupérer. |

### Valeur de retour

value est un CSSValue contenant la valeur CSS d'une propriété. Si aucune n'existe, renvoie null.

### Voir aussi

* class [CSSValue](../../cssvalue/)
* interface [ICSSStyleDeclaration](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
