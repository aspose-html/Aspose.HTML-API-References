---
title: "Document.GetElementsByTagNameNS"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Document method. Retourneert een lijst van elementen met de opgegeven tagnaam die tot het opgegeven pakket behoren. Het volledige document wordt doorzocht, inclusief het root-knooppunt."
type: docs

url: /nl/java/com.aspose.html.dom/document/getelementsbytagnamens/
---
## Document.GetElementsByTagNameNS method

Retourneert een lijst van elementen met de opgegeven tagnaam die tot het opgegeven pakket behoren. Het volledige document wordt doorzocht, inclusief het root‑knooppunt.

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| packageURI | String | De pakket-URI van de te zoeken elementen. |
| localName | String | Ofwel de lokale naam van elementen om naar te zoeken of de speciale waarde *, die overeenkomt met alle elementen. |

### Retourwaarde

Een live [`NodeList`](../../../com.aspose.html.collections/nodelist/) (maar zie de onderstaande opmerking) van gevonden elementen in de volgorde waarin ze in de boom verschijnen.

## Opmerkingen

Raadpleeg de officiële [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagnamens).

Praktische webontwikkelingsinhoud is te vinden op [w3schools](https://www.w3schools.com/xml/met_document_getelementsbytagnamens.asp).

U kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Voorbeelden

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
    // Gebruikerscode komt hier
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
         
	// Gebruikerscode komt hier
}
```

# Console output

Gevonden: 3

Bob Dylan

Bonnie Tyler

Dolly Parton

*inputHtmlPath - user input xhtml file path

### Zie ook

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
