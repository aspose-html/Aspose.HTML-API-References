---
title: "Element.GetElementsByTagName"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Element. Renvoie un objet HTMLCollection contenant tous les éléments avec un nom de balise donné dans l'ordre du document"
type: docs

url: /fr/java/com.aspose.html.dom/element/getelementsbytagname/
---
## Element.GetElementsByTagName method

Renvoie l'objet [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) contenant tous les [`elements`](../) avec un nom de balise donné, dans l'ordre du document.

```java
public HTMLCollection GetElementsByTagName(String name)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nom | String | Le nom de la balise. Représentation sous forme de chaîne du nom de la balise. |

### Valeur de retour

Un objet [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) est une liste de type tableau d'[`elements`](../).

## Remarques

Consultez la [spécification](https://dom.spec.whatwg.org/#dom-element-getelementsbytagname) officielle.

Vous pourriez également être intéressé par la [documentation](https://docs.aspose.com/html/net/).

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exemples

```java
# Html input content
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

	HTMLCollection htmlCollection = document.GetElementsByTagName("p");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// Le code utilisateur va ici
}
```

*inputHtmlPath - user input html file.

# Console output

Trouvé : 3

Le contenu du paragraphe stylé avec la classe pStyle...

Le contenu du deuxième paragraphe...

Le contenu du troisième paragraphe...

### Voir aussi

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
