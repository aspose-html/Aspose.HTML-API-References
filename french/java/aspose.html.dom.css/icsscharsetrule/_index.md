---
title: "Interface ICSSCharsetRule"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.dom.css.ICSSCharsetRule. L'interface CSSCharsetRule représente une règle de jeu de caractères dans une feuille de style CSS. La valeur de l'attribut encoding n'affecte pas l'encodage des données textuelles dans les objets DOM ; cet encodage est toujours UTF-16. Après le chargement d'une feuille de style, la valeur de l'attribut encoding correspond à celle trouvée dans la règle charset. S'il n'y avait pas de charset dans le document original, aucune CSSCharsetRule n'est créée. La valeur de l'attribut encoding peut également être utilisée comme indication pour l'encodage utilisé lors de la sérialisation de la feuille de style."
type: docs

url: /fr/java/com.aspose.html.dom.css/icsscharsetrule/
---
## ICSSCharsetRule interface

L'interface CSSCharsetRule représente une règle @charset dans une feuille de style CSS. La valeur de l'attribut encoding n'affecte pas l'encodage des données texte dans les objets DOM ; cet encodage est toujours UTF-16. Après le chargement d'une feuille de style, la valeur de l'attribut encoding correspond à la valeur trouvée dans la règle @charset. S'il n'y avait pas de @charset dans le document original, aucune CSSCharsetRule n'est créée. La valeur de l'attribut encoding peut également être utilisée comme indication pour l'encodage utilisé lors de la sérialisation de la feuille de style.

```java
public interface ICSSCharsetRule : ICSSRule
```

## Propriétés

| Nom | Description |
| --- | --- |
[getEncoding]
[setEncoding] The encoding information associated with the current stylesheet used in this @charset rule. |

### Voir aussi

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
