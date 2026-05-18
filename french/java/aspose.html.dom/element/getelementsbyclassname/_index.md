---
title: "Element.GetElementsByClassName"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Element. Retourne un objet HTMLCollection contenant tous les éléments à l'intérieur de l'élément qui possèdent toutes les classes spécifiées dans l'argument"
type: docs

url: /fr/java/com.aspose.html.dom/element/getelementsbyclassname/
---
## Element.GetElementsByClassName method

Retourne l'objet [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) contenant tous les éléments à l'intérieur de [`element`](../) qui possèdent toutes les classes spécifiées dans l'argument.

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| classNames | String | La String String qui contient un ensemble non ordonné de jetons uniques séparés par des espaces représentant des classes (noms de classe) |

### Valeur de retour

Un objet [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) est une liste de type tableau d'[`elements`](../).

## Remarques

Reportez-vous à la [spécification](https://dom.spec.whatwg.org/#dom-element-getelementsbyclassname) officielle.

Vous pourriez également être intéressé par la [documentation](https://docs.aspose.com/html/net/).

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exemples

```java
# HTML source content
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Title</title>
</head>
<body>
<div id="divElementContainerId">
	<p class="pStyle">The paragraph styled pStyle class content...</p>
	<p>The second paragraph content...</p>
	<p>The third paragraph content...</p>
	<div class="pStyle">The div element styled pStyle class...</div>
</div>
</body>
</html>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	// Le code utilisateur va ici

	Element container = document.GetElementById("divElementContainerId");
	HTMLCollection htmlCollection = container.GetElementsByClassName("pStyle");

	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// Le code utilisateur va ici
}
```

*inputHtmlPath - user input html file path.

# Console output

Trouvé : 2

Le contenu du paragraphe stylisé avec la classe pStyle...

L'élément div stylisé avec la classe pStyle...

### Voir aussi

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
