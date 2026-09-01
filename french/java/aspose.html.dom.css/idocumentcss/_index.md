---
title: "Interface IDocumentCSS"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.dom.css.IDocumentCSS. Cette interface représente un document avec une vue CSS."
type: docs

url: /fr/java/com.aspose.html.dom.css/idocumentcss/
---
## IDocumentCSS interface

Cette interface représente un document avec une vue CSS.

La méthode getOverrideStyle fournit un mécanisme permettant à un auteur DOM d'apporter un changement immédiat au style d'un élément sans modifier les feuilles de style explicitement liées d'un document ou le style en ligne des éléments dans les feuilles de style. Cette feuille de style vient après la feuille de style de l'auteur dans l'algorithme de cascade et est appelée feuille de style de substitution. La feuille de style de substitution a la priorité sur les feuilles de style de l'auteur. Une déclaration "!important" conserve la priorité sur une déclaration normale. Les feuilles de style de substitution, de l'auteur et de l'utilisateur peuvent toutes contenir des déclarations "!important". Les règles "!important" de l'utilisateur ont la priorité sur les règles "!important" de substitution et de l'auteur, et les règles "!important" de substitution ont la priorité sur les règles "!important" de l'auteur.

On s'attend à ce qu'une instance de l'interface DocumentCSS puisse être obtenue en utilisant des méthodes de conversion spécifiques à la liaison sur une instance de l'interface Document.

Voir également la [Document Object Model (DOM) Level 2 Style Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113).

```java
public interface IDocumentCSS : IDocumentStyle
```

## Méthodes

| Nom | Description |
| --- | --- |
| [getOverrideStyle](../../com.aspose.html.dom.css/idocumentcss/getoverridestyle/)(Element, String) | Cette méthode est utilisée pour récupérer la déclaration de style de substitution pour un élément spécifié et un pseudo‑élément spécifié. |

### Voir aussi

* interface [IDocumentStyle](../idocumentstyle/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
