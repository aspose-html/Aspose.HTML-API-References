---
title: "Element.GetElementsByTagNameNS"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode de l'élément. Retourne un objet HTMLCollection contenant tous les éléments avec un nom local donné et une chaîne d'URI de package dans l'ordre du document"
type: docs

url: /fr/java/com.aspose.html.dom/element/getelementsbytagnamens/
---
## Element.GetElementsByTagNameNS method

Retourne l'objet [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) contenant tous les [`elements`](../) avec un nom local donné et une chaîne d'URI de package dans l'ordre du document.

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| packageURI | String | La représentation de la chaîne d'URI du package. |
| localName | String | Représentation en chaîne du nom local. |

### Valeur de retour

Un objet [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) est une liste de type tableau d'[`elements`](../).

## Remarques

Consultez la [spécification](https://dom.spec.whatwg.org/#dom-element-getelementsbytagnamens) officielle.

Vous pourriez également être intéressé par la [documentation](https://docs.aspose.com/html/net/).

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exemples

```java
# .xhtml input file content
<!DOCTYPE html>
<html lang="en"
   xmlns="http://www.w3.org/1999/xhtml"
   xmlns:custom="http://www.company.com">
<head>
	<meta charset="UTF-8"/>
	<link rel="stylesheet" href="/styles/main.css"/>
	<title>Title</title>
</head>
<body>
<custom:customtag>
	Custom package custom tag content goes here...
</custom:customtag>
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

	HTMLCollection htmlCollection = document.GetElementsByTagNameNS("http://www.company.com", "customtag");
	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// Le code utilisateur va ici
}
```

*inputHtmlPath - user input xhtml file path.

# Console output

Trouvé : 1

Le contenu de la balise personnalisée du package personnalisé va ici...

### Voir aussi

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
