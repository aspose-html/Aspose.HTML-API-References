---
title: "Document.GetElementsByTagNameNS"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Document. Retourne une liste d'éléments avec le nom de balise donné appartenant au package donné. Le document complet est recherché, y compris le nœud racine."
type: docs

url: /fr/java/com.aspose.html.dom/document/getelementsbytagnamens/
---
## Document.GetElementsByTagNameNS method

Renvoie une liste d'éléments avec le nom de balise donné appartenant au package spécifié. Le document complet est parcouru, y compris le nœud racine.

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| packageURI | String | L'URI du package des éléments à rechercher. |
| localName | String | Soit le nom local des éléments à rechercher, soit la valeur spéciale *, qui correspond à tous les éléments. |

### Valeur de retour

Une [`NodeList`](../../../com.aspose.html.collections/nodelist/) en direct (mais voir la note ci-dessous) des éléments trouvés dans l'ordre où ils apparaissent dans l'arbre.

## Remarques

Consultez la [spécification](https://dom.spec.whatwg.org/#dom-document-getelementsbytagnamens) officielle.

Le contenu de pratique du développement web peut être trouvé sur [w3schools](https://www.w3schools.com/xml/met_document_getelementsbytagnamens.asp).

Vous pouvez télécharger les exemples complets et les fichiers de données depuis [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exemples

```java
var elements = document.GetElementsByTagNameNS(@package, name);
```

```java
# HTML content. File extension - xhtml
<!DOCTYPE html>
<html lang="en"
	xmlns="http://www.w3.org/1999/xhtml"
	xmlns:xml="http://www.w3.org/XML/1998/package">
...
<xml:uniquetag>
  xml package uniquetag content goes here...
</xml:uniquetag>
...
</html>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
    HTMLCollection htmlCollection = document.GetElementsByTagNameNS("http://www.w3.org/XML/1998/package","uniquetag");
    Console.WriteLine($"Found: {htmlCollection.Length}" );
    foreach (Element element in htmlCollection)
    {
      Console.WriteLine(element.InnerHTML);
    }  
    // Le code utilisateur va ici
}





# Console output

Found: 1

xml package uniquetag content goes here...




```

*inputHtmlPath - user input xhtml file path

```java
# HTML content. File extension - xhtml
<!DOCTYPE html>
<html lang="en"
   xmlns="http://www.w3.org/1999/xhtml"
   xmlns:custom="http://www.company.com"
   xmlns:xml="http://www.w3.org/XML/1998/package">
...
<xml:CATALOG>
	<xml:CD>
    <xml:TITLE>Empire Burlesque</xml:TITLE>
    <xml:ARTIST>Bob Dylan</xml:ARTIST>
    <xml:COUNTRY>USA</xml:COUNTRY>
    <xml:COMPANY>Columbia</xml:COMPANY>
    <xml:PRICE>10.90</xml:PRICE>
    <xml:YEAR>1985</xml:YEAR>
  </xml:CD>
...

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = 
          document.GetElementsByTagNameNS("http://www.w3.org/XML/1998/package", "ARTIST");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// Le code utilisateur va ici
}
```

# Console output

Trouvé: 3

Bob Dylan

Bonnie Tyler

Dolly Parton

*inputHtmlPath - user input xhtml file path

### Voir aussi

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
