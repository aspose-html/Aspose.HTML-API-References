---
title: "Document.GetElementsByTagNameNS"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo Document. Restituisce un elenco di elementi con il nome di tag fornito appartenenti al pacchetto specificato. Il documento completo viene cercato includendo il nodo radice"
type: docs

url: /it/java/com.aspose.html.dom/document/getelementsbytagnamens/
---
## Document.GetElementsByTagNameNS method

Restituisce un elenco di elementi con il nome di tag fornito appartenenti al pacchetto specificato. Viene cercato l'intero documento, inclusa la radice.

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| packageURI | String | L'URI del pacchetto degli elementi da cercare. |
| localName | String | Sia il nome locale degli elementi da cercare sia il valore speciale *, che corrisponde a tutti gli elementi. |

### Valore di ritorno

Una [`NodeList`](../../../com.aspose.html.collections/nodelist/) live (ma vedi la nota qui sotto) degli elementi trovati nell'ordine in cui appaiono nell'albero.

## Osservazioni

Fai riferimento alla [specifica](https://dom.spec.whatwg.org/#dom-document-getelementsbytagnamens) ufficiale.

Il contenuto pratico di sviluppo web può essere trovato su [w3schools](https://www.w3schools.com/xml/met_document_getelementsbytagnamens.asp).

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Esempi

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
    // Il codice dell'utente va qui
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
         
	// Il codice dell'utente va qui
}
```

# Console output

Trovati: 3

Bob Dylan

Bonnie Tyler

Dolly Parton

*inputHtmlPath - user input xhtml file path

### Vedi anche

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
