---
title: "Element.GetElementsByTagNameNS"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo Element. Restituisce un oggetto HTMLCollection contenente tutti gli elementi con un determinato nome locale e stringa URI del pacchetto, in ordine di documento"
type: docs

url: /it/java/com.aspose.html.dom/element/getelementsbytagnamens/
---
## Element.GetElementsByTagNameNS method

Restituisce l'oggetto [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) contenente tutti i [`elements`](../) con un determinato nome locale e stringa URI del pacchetto, in ordine di documento.

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| packageURI | String | La rappresentazione della stringa URI del pacchetto. |
| localName | String | Rappresentazione stringa del nome locale. |

### Valore di ritorno

Un oggetto [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) è un elenco simile a un array di [`elements`](../).

## Osservazioni

Fare riferimento alla [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbytagnamens) ufficiale.

Potresti anche essere interessato alla [documentazione](https://docs.aspose.com/html/net/).

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Esempi

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
	// Il codice dell'utente va qui

	HTMLCollection htmlCollection = document.GetElementsByTagNameNS("http://www.company.com", "customtag");
	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// Il codice dell'utente va qui
}
```

*inputHtmlPath - user input xhtml file path.

# Console output

Trovato: 1

Il contenuto personalizzato del tag del pacchetto personalizzato va qui...

### Vedi anche

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
