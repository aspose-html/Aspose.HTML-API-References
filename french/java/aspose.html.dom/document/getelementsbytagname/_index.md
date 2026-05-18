---
title: "Document.GetElementsByTagName"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode du document. La méthode getElementsByTagName de l'interface Document renvoie une HTMLCollection d'éléments portant le nom de balise indiqué."
type: docs

url: /fr/java/com.aspose.html.dom/document/getelementsbytagname/
---
## Document.GetElementsByTagName method

La méthode getElementsByTagName de l'interface [`Document`](../) renvoie une [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) d'éléments portant le nom de balise indiqué.

Le document complet est parcouru, y compris le nœud racine. La [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) retournée est dynamique, ce qui signifie qu'elle se met à jour automatiquement pour rester synchronisée avec l'arbre DOM sans avoir besoin d'appeler à nouveau document.getElementsByTagName().

```java
public HTMLCollection GetElementsByTagName(String tagname)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| tagname | String | Une String représentant le nom des éléments. La String spéciale "*" représente tous les éléments. |

### Valeur de retour

Une [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) dynamique des éléments trouvés dans l'ordre où ils apparaissent dans l'arbre.

## Remarques

Consultez la [spécification](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname) officielle.

Le contenu pratique de développement web peut être trouvé sur [w3schools](https://www.w3schools.com/jsref/met_document_getelementsbytagname.asp).

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exemples

```java
var elements = document.GetElementsByTagName(name);
```

```java
#HTML content
<div>
	<p class="pStyle">First styled by pStyle class paragraph</p>
	<p class="pStyle">Second styled by pStyle class paragraph</p>
	<p class="pStyle">Third styled by pStyle class paragraph</p>
	<span class="pStyle">Span styled by pStyle</span>
</div>
<div id="smart class">
	<p id="p1" class="ddd kkk">Paragraph styled by class name =ddd kkk=</p>
	<p id="p2" class="ddd fff">Paragraph styled by class name =ddd fff=</p>
	<p id="p3" class="kkk fff">Paragraph styled by class name =kkk fff=</p>
</div>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;

import (var document = new HTMLDocument(inputHtmlPath))
{
    HTMLCollection htmlCollection = document.GetElementsByTagName("p");
    Console.WriteLine($"Found: {htmlCollection.Length}" );
    foreach (Element element in htmlCollection)
    {
      Console.WriteLine(element.InnerHTML);
    }

    // Le code utilisateur va ici
}
```

# Console output

Trouvé : 6

Premier stylisé par la classe de paragraphe pStyle

Deuxième stylisé par la classe de paragraphe pStyle

Troisième stylisé par la classe de paragraphe pStyle

Paragraphe stylisé par le nom de classe =ddd kkk=

Paragraphe stylisé par le nom de classe =ddd fff=

Paragraphe stylisé par le nom de classe =kkk fff=

*inputHtmlPath - user input html file path

### Voir aussi

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
