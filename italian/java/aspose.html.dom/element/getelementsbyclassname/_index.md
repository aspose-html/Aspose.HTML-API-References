---
title: "Element.GetElementsByClassName"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo di Element. Restituisce un oggetto HTMLCollection contenente tutti gli elementi all'interno dell'elemento che possiedono tutte le classi specificate nell'argomento"
type: docs

url: /it/java/com.aspose.html.dom/element/getelementsbyclassname/
---
## Element.GetElementsByClassName method

Restituisce l'oggetto [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) contenente tutti gli elementi all'interno di [`element`](../) che possiedono tutte le classi specificate nell'argomento.

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| classNames | String | La String String che contiene un insieme non ordinato di token unici separati da spazi che rappresentano classi (nomi delle classi) |

### Valore di ritorno

Un oggetto [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) è un elenco simile a un array di [`elements`](../).

## Osservazioni

Fare riferimento alla [specifica](https://dom.spec.whatwg.org/#dom-element-getelementsbyclassname) ufficiale.

Potresti anche essere interessato alla [documentazione](https://docs.aspose.com/html/net/).

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Esempi

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
	// Il codice dell'utente va qui

	Element container = document.GetElementById("divElementContainerId");
	HTMLCollection htmlCollection = container.GetElementsByClassName("pStyle");

	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// Il codice dell'utente va qui
}
```

*inputHtmlPath - user input html file path.

# Console output

Trovato: 2

Il contenuto del paragrafo con classe pStyle...

L'elemento div con la classe pStyle stilizzata...

### Vedi anche

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
