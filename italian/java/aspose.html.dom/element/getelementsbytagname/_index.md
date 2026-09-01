---
title: "Element.GetElementsByTagName"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo Element. Restituisce un oggetto HTMLCollection contenente tutti gli elementi con un dato nome di tag in ordine di documento"
type: docs

url: /it/java/com.aspose.html.dom/element/getelementsbytagname/
---
## Element.GetElementsByTagName method

Restituisce l'oggetto [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) contenente tutti i [`elements`](../) con un dato nome di tag, in ordine di documento.

```java
public HTMLCollection GetElementsByTagName(String name)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | String | Il nome del tag. Rappresentazione stringa del nome del tag. |

### Valore di ritorno

Un oggetto [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) è un elenco simile a un array di [`elements`](../).

## Osservazioni

Fare riferimento alla [specifica](https://dom.spec.whatwg.org/#dom-element-getelementsbytagname) ufficiale.

Potresti essere interessato anche alla [documentazione](https://docs.aspose.com/html/net/).

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Esempi

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
	// Il codice dell'utente va qui

	HTMLCollection htmlCollection = document.GetElementsByTagName("p");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// Il codice dell'utente va qui
}
```

*inputHtmlPath - user input html file.

# Console output

Trovati: 3

Il contenuto del paragrafo con classe pStyle stilizzata...

Il contenuto del secondo paragrafo...

Il contenuto del terzo paragrafo...

### Vedi anche

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
