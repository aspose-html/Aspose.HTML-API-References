---
title: "Document.GetElementById"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo del documento. Il metodo Document getElementById restituisce un oggetto Element che rappresenta l'elemento la cui proprietà id corrisponde alla Stringa specificata. Poiché gli ID degli elementi devono essere unici se specificati, sono un modo utile per accedere rapidamente a un elemento specifico."
type: docs

url: /it/java/com.aspose.html.dom/document/getelementbyid/
---
## Document.GetElementById method

Il metodo Document getElementById() restituisce un oggetto [`Element`](../../element/) che rappresenta l'elemento la cui proprietà id corrisponde alla Stringa specificata. Poiché gli ID degli elementi devono essere unici se specificati, sono un modo utile per accedere rapidamente a un elemento specifico.

Se hai bisogno di accedere a un elemento che non ha un ID, puoi usare querySelector() per trovare l'elemento usando qualsiasi selettore.

```java
public Element GetElementById(String elementId)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| elementId | String | L'ID dell'elemento da individuare. L'ID è una Stringa sensibile al maiuscolo/minuscolo che è unica all'interno del documento; solo un elemento può avere un determinato ID. |

### Valore di ritorno

Un oggetto [`Element`](../../element/) che descrive l'oggetto DOM dell'elemento corrispondente all'ID specificato, o null se non è stato trovato alcun elemento corrispondente nel documento.

## Osservazioni

Fai riferimento alla [spec](https://dom.spec.whatwg.org/#dom-nonelementparentnode-getelementbyid) ufficiale.

Il contenuto pratico di sviluppo web può essere trovato su [w3schools](https://www.w3schools.com/jsref/met_document_getelementbyid.asp).

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Esempi

```java
// Contenuto HTML
<div id="uniqueIdentifier">Container with ID - identifier</div>

// Codice C#
import System;
import Aspose.Html;
import com.aspose.html.dom;
...
	using (var document = new HTMLDocument(inputHtmlPath))
		{
			Element element = document.GetElementById("uniqueIdentifier");
			HTMLDivElement divElement = (HTMLDivElement) element;
			Console.WriteLine(divElement.InnerHTML);

			// Il codice dell'utente va qui
   }
```

// Output della console

Contenitore con ID - identificatore

*inputHtmlPath - user input html file path

### Vedi anche

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
