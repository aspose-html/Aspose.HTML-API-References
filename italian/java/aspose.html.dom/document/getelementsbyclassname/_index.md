---
title: "Document.GetElementsByClassName"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo Document. Il metodo getElementsByClassName dell'interfaccia Document restituisce un oggetto simile a un array di tutti gli elementi figli che possiedono tutti i nomi di classe forniti"
type: docs

url: /it/java/com.aspose.html.dom/document/getelementsbyclassname/
---
## Document.GetElementsByClassName method

Il metodo getElementsByClassName dell'interfaccia [`Document`](../) restituisce un oggetto simile a un array di tutti gli elementi figli che possiedono tutti i nomi di classe forniti.

Quando viene chiamato sull'oggetto document, viene cercato l'intero documento, compreso il nodo radice. È inoltre possibile chiamare getElementsByClassName() su qualsiasi elemento; restituirà solo gli elementi che sono discendenti dell'elemento radice specificato con i nomi di classe forniti.

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| classNames | String | La String String che contiene un insieme non ordinato di token unici separati da spazi che rappresentano classi (nomi delle classi) |

### Valore di ritorno

Una [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) live di elementi trovati.

## Osservazioni

Fare riferimento alla [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbyclassname).

Il contenuto pratico di sviluppo web può essere trovato su [w3schools](https://www.w3schools.com/jsref/met_element_getelementsbyclassname.asp).

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Esempi

```java
var elements = document.GetElementsByClassName("red test");
```

```java
// Contenuto HTML
<div class="custom-class">Customized by css class container</div>

// Codice C#
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = document.GetElementsByClassName("custom-class");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// Il codice dell'utente va qui
}
```

// Output della console

Trovato: 1

Personalizzato dalla classe css container

*inputHtmlPath - user input html file path

```java
// Stile CSS
.ddd{
	padding: 10pt;
}

.kkk{
	background-color: chartreuse;
}

// Contenuto HTML
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
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = document.GetElementsByClassName("ddd");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
		Console.WriteLine($"Element type: {element.GetType()}");
	}
         
	// Il codice dell'utente va qui
}
```

# Console output

Trovato: 2

Paragrafo stilizzato dal nome classe =ddd kkk=

Tipo di elemento: Aspose.Html.HTMLParagraphElement

Paragrafo stilizzato dal nome classe =ddd fff=

Tipo di elemento: Aspose.Html.HTMLParagraphElement

*inputHtmlPath - user input html file path

```java
// Stile CSS
.pStyle{
  font-
}

# HTML content
<div>
	<p class="pStyle">First styled by pStyle class paragraph</p>
	<p class="pStyle">Second styled by pStyle class paragraph</p>
	<p class="pStyle">Third styled by pStyle class paragraph</p>
	<span class="pStyle">Span styled by pStyle</span>
</div>

# C# code
import System;
import Aspose.Html;
import com.aspose.html.collections;
import com.aspose.html.dom;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLCollection htmlCollection = document.GetElementsByClassName("pStyle");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
		Console.WriteLine($"Element type: {element.GetType()}");
	}
         
	// Il codice dell'utente va qui
}
```

# Console output

Trovato: 4

Primo stilizzato dalla classe pStyle del paragrafo

Tipo di elemento: Aspose.Html.HTMLParagraphElement

Secondo stilizzato dalla classe pStyle del paragrafo

Tipo di elemento: Aspose.Html.HTMLParagraphElement

Terzo stilizzato dalla classe pStyle del paragrafo

Tipo di elemento: Aspose.Html.HTMLParagraphElement

Span stilizzato da pStyle

Tipo di elemento: Aspose.Html.HTMLElement

*inputHtmlPath - user input html file path

### Vedi anche

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
