---
title: "Document.GetElementsByClassName"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Document. La méthode getElementsByClassName de l'interface Document renvoie un objet de type tableau contenant tous les éléments enfants qui possèdent toutes les classes spécifiées."
type: docs

url: /fr/java/com.aspose.html.dom/document/getelementsbyclassname/
---
## Document.GetElementsByClassName method

La méthode getElementsByClassName de l'interface [`Document`](../) renvoie un objet de type tableau contenant tous les éléments enfants qui possèdent toutes les classes spécifiées.

Lorsqu'elle est appelée sur l'objet document, le document complet est parcouru, y compris le nœud racine. Vous pouvez également appeler getElementsByClassName() sur n'importe quel élément ; elle ne renverra que les éléments qui sont des descendants de l'élément racine spécifié avec les classes indiquées.

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| classNames | String | La String String qui contient un ensemble non ordonné de jetons uniques séparés par des espaces représentant des classes (noms de classe) |

### Valeur de retour

Une [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) en direct des éléments trouvés.

## Remarques

Consultez la [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbyclassname) officielle.

Le contenu de pratique du développement web peut être trouvé sur [w3schools](https://www.w3schools.com/jsref/met_element_getelementsbyclassname.asp).

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exemples

```java
var elements = document.GetElementsByClassName("red test");
```

```java
// Contenu HTML
<div class="custom-class">Customized by css class container</div>

// Code C#
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = document.GetElementsByClassName("custom-class");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// Le code utilisateur va ici
}
```

// Sortie console

Trouvé : 1

Personnalisé par la classe css container

*inputHtmlPath - user input html file path

```java
// Style CSS
.ddd{
	padding: 10pt;
}

.kkk{
	background-color: chartreuse;
}

// Contenu HTML
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
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = document.GetElementsByClassName("ddd");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
		Console.WriteLine($"Element type: {element.GetType()}");
	}
         
	// Le code utilisateur va ici
}
```

# Console output

Trouvé : 2

Paragraphe stylisé par le nom de classe =ddd kkk=

Type d'élément : Aspose.Html.HTMLParagraphElement

Paragraphe stylisé par le nom de classe =ddd fff=

Type d'élément : Aspose.Html.HTMLParagraphElement

*inputHtmlPath - user input html file path

```java
// Style CSS
.pStyle{
  font-
}

# HTML content
<div>
	<p class="pStyle">First styled by pStyle class paragraph</p>
	<p class="pStyle">Second styled by pStyle class paragraph</p>
	<p class="pStyle">Third styled by pStyle class paragraph</p>
	<span class="pStyle">Span styled by pStyle</span>
</div>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = document.GetElementsByClassName("pStyle");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
		Console.WriteLine($"Element type: {element.GetType()}");
	}
         
	// Le code utilisateur va ici
}
```

# Console output

Trouvé : 4

Premier stylisé par la classe de paragraphe pStyle

Type d'élément : Aspose.Html.HTMLParagraphElement

Deuxième stylisé par la classe de paragraphe pStyle

Type d'élément : Aspose.Html.HTMLParagraphElement

Troisième stylisé par la classe de paragraphe pStyle

Type d'élément : Aspose.Html.HTMLParagraphElement

Span stylisé par pStyle

Type d'élément : Aspose.Html.HTMLElement

*inputHtmlPath - user input html file path

### Voir aussi

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
