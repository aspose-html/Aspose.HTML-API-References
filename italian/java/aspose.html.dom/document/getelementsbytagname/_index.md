---
title: "Document.GetElementsByTagName"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo Document. Il metodo getElementsByTagName dell'interfaccia Document restituisce una HTMLCollection di elementi con il nome di tag specificato"
type: docs

url: /it/java/com.aspose.html.dom/document/getelementsbytagname/
---
## Document.GetElementsByTagName method

Il metodo getElementsByTagName dell'interfaccia [`Document`](../) restituisce una [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) di elementi con il nome di tag specificato.

Viene cercato l'intero documento, incluso il nodo radice. La [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) restituita è live, il che significa che si aggiorna automaticamente per rimanere sincronizzata con l'albero DOM senza dover chiamare nuovamente document.getElementsByTagName().

```java
public HTMLCollection GetElementsByTagName(String tagname)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tagname | String | Una Stringa che rappresenta il nome degli elementi. La Stringa speciale "*" rappresenta tutti gli elementi. |

### Valore di ritorno

Una [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) live degli elementi trovati nell'ordine in cui appaiono nell'albero.

## Osservazioni

Fare riferimento alla [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname) ufficiale.

Il contenuto pratico di sviluppo web può essere trovato su [w3schools](https://www.w3schools.com/jsref/met_document_getelementsbytagname.asp).

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Esempi

```java
var elements = document.GetElementsByTagName(name);
```

```java
#HTML content
<div>
	<p class="pStyle">First styled by pStyle class paragraph</p>
	<p class="pStyle">Second styled by pStyle class paragraph</p>
	<p class="pStyle">Third styled by pStyle class paragraph</p>
	<span class="pStyle">Span styled by pStyle</span>
</div>
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

import (var document = new HTMLDocument(inputHtmlPath))
{
    HTMLCollection htmlCollection = document.GetElementsByTagName("p");
    Console.WriteLine($"Found: {htmlCollection.Length}" );
    foreach (Element element in htmlCollection)
    {
      Console.WriteLine(element.InnerHTML);
    }

    // Il codice dell'utente va qui
}
```

# Console output

Trovati: 6

Primo stilizzato dalla classe pStyle paragraph

Secondo stilizzato dalla classe pStyle paragraph

Terzo stilizzato dalla classe pStyle paragraph

Paragrafo stilizzato dal nome classe =ddd kkk=

Paragrafo stilizzato dal nome classe =ddd fff=

Paragrafo stilizzato dal nome classe =kkk fff=

*inputHtmlPath - user input html file path

### Vedi anche

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
