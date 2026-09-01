---
title: "Document.GetElementsByTagNameNS"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Document-Methode. Gibt eine Liste von Elementen mit dem angegebenen Tag-Namen zurück, die zum angegebenen Paket gehören. Das gesamte Dokument wird einschließlich des Wurzelknotens durchsucht."
type: docs

url: /de/java/com.aspose.html.dom/document/getelementsbytagnamens/
---
## Document.GetElementsByTagNameNS method

Gibt eine Liste von Elementen mit dem angegebenen Tag‑Namen zurück, die zum angegebenen Paket gehören. Das gesamte Dokument wird durchsucht, einschließlich des Wurzelknotens.

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| packageURI | String | Der Paket-URI der zu suchenden Elemente. |
| localName | String | Entweder der lokale Name der zu suchenden Elemente oder der Sonderwert *, der alle Elemente entspricht. |

### Rückgabewert

Eine Live-[`NodeList`](../../../com.aspose.html.collections/nodelist/) (siehe jedoch die Anmerkung unten) der gefundenen Elemente in der Reihenfolge, in der sie im Baum erscheinen.

## Hinweise

Siehe die offizielle [Spezifikation](https://dom.spec.whatwg.org/#dom-document-getelementsbytagnamens).

Praxis-Webentwicklungsinhalte können bei [w3schools](https://www.w3schools.com/xml/met_document_getelementsbytagnamens.asp) gefunden werden.

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) herunterladen.

## Beispiele

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
    // Benutzercode kommt hierher
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
         
	// Benutzercode kommt hierher
}
```

# Console output

Gefunden: 3

Bob Dylan

Bonnie Tyler

Dolly Parton

*inputHtmlPath - user input xhtml file path

### Siehe auch

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
