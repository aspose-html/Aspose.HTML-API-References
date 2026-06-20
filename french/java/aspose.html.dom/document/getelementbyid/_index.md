---
title: "Document.GetElementById"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode du Document. La méthode getElementById du Document renvoie un objet Element représentant l'élément dont la propriété id correspond à la String spécifiée. Étant donné que les ID d'éléments doivent être uniques lorsqu'ils sont spécifiés, ils constituent un moyen pratique d'accéder rapidement à un élément spécifique."
type: docs

url: /fr/java/com.aspose.html.dom/document/getelementbyid/
---
## Document.GetElementById method

La méthode getElementById() du Document renvoie un objet [`Element`](../../element/) représentant l'élément dont la propriété id correspond à la String spécifiée. Étant donné que les ID d'éléments doivent être uniques lorsqu'ils sont spécifiés, ils constituent un moyen pratique d'accéder rapidement à un élément spécifique.

Si vous devez accéder à un élément qui n'a pas d'ID, vous pouvez utiliser querySelector() pour trouver l'élément à l'aide de n'importe quel sélecteur.

```java
public Element GetElementById(String elementId)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| elementId | String | L'ID de l'élément à localiser. L'ID est une String sensible à la casse qui est unique dans le document ; un seul élément peut posséder un ID donné. |

### Valeur de retour

Un objet [`Element`](../../element/) décrivant l'objet d'élément DOM correspondant à l'ID spécifié, ou null si aucun élément correspondant n'a été trouvé dans le document.

## Remarques

Reportez-vous à la [spécification](https://dom.spec.whatwg.org/#dom-nonelementparentnode-getelementbyid) officielle.

Le contenu pratique de développement web peut être trouvé sur [w3schools](https://www.w3schools.com/jsref/met_document_getelementbyid.asp).

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exemples

```java
// Contenu HTML
<div id="uniqueIdentifier">Container with ID - identifier</div>

// Code C#
import System;
import Aspose.Html;
import com.aspose.html.dom;
...
	using (var document = new HTMLDocument(inputHtmlPath))
		{
			Element element = document.GetElementById("uniqueIdentifier");
			HTMLDivElement divElement = (HTMLDivElement) element;
			Console.WriteLine(divElement.InnerHTML);

			// Le code utilisateur va ici
   }
```

// Sortie console

Conteneur avec ID - identifiant

*inputHtmlPath - user input html file path

### Voir aussi

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
