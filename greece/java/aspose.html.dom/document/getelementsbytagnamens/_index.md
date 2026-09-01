---
title: "Document.GetElementsByTagNameNS"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Document μέθοδος. Επιστρέφει μια λίστα στοιχείων με το δεδομένο όνομα ετικέτας που ανήκουν στο δεδομένο πακέτο. Το πλήρες έγγραφο αναζητείται συμπεριλαμβανομένου του ριζικού κόμβου"
type: docs

url: /el/java/com.aspose.html.dom/document/getelementsbytagnamens/
---
## Document.GetElementsByTagNameNS method

Επιστρέφει μια λίστα στοιχείων με το δοσμένο όνομα ετικέτας που ανήκουν στο δοσμένο πακέτο. Αναζητείται ολόκληρο το έγγραφο, συμπεριλαμβανομένου του ριζικού κόμβου.

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| packageURI | String | Το URI του πακέτου των στοιχείων που πρέπει να αναζητηθούν. |
| localName | String | Είτε το τοπικό όνομα των στοιχείων προς αναζήτηση είτε η ειδική τιμή *, η οποία ταιριάζει με όλα τα στοιχεία. |

### Τιμή Επιστροφής

Μια ζωντανή [`NodeList`](../../../com.aspose.html.collections/nodelist/) (αλλά δείτε τη σημείωση παρακάτω) των ευρεθέντων στοιχείων με τη σειρά που εμφανίζονται στο δέντρο.

## Παρατηρήσεις

Ανατρέξτε στην επίσημη [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagnamens).

Το περιεχόμενο πρακτικής ανάπτυξης ιστού μπορεί να βρεθεί στο [w3schools](https://www.w3schools.com/xml/met_document_getelementsbytagnamens.asp).

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Παραδείγματα

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
    // Ο κώδικας χρήστη πηγαίνει εδώ
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
         
	// Ο κώδικας χρήστη πηγαίνει εδώ
}
```

# Console output

Βρέθηκαν: 3

Bob Dylan

Bonnie Tyler

Dolly Parton

*inputHtmlPath - user input xhtml file path

### Δείτε επίσης

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
