---
title: "Element.GetElementsByTagNameNS"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Element. Επιστρέφει το αντικείμενο HTMLCollection που περιέχει όλα τα στοιχεία με το δοσμένο τοπικό όνομα και τη συμβολοσειρά URI του πακέτου με τη σειρά του εγγράφου."
type: docs

url: /el/java/com.aspose.html.dom/element/getelementsbytagnamens/
---
## Element.GetElementsByTagNameNS method

Επιστρέφει το αντικείμενο [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) που περιέχει όλα τα [`elements`](../) με το δοσμένο τοπικό όνομα και τη συμβολοσειρά URI του πακέτου με τη σειρά του εγγράφου.

```java
public HTMLCollection GetElementsByTagNameNS(String packageURI, String localName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| packageURI | String | Η αναπαράσταση της συμβολοσειράς URI του πακέτου. |
| localName | String | Αναπαράσταση συμβολοσειράς του τοπικού ονόματος. |

### Τιμή Επιστροφής

Ένα αντικείμενο [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) είναι μια λίστα τύπου πίνακα από [`elements`](../).

## Παρατηρήσεις

Ανατρέξτε στην επίσημη [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbytagnamens).

Μπορεί επίσης να σας ενδιαφέρει η [τεκμηρίωση](https://docs.aspose.com/html/net/).

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Παραδείγματα

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
	// Ο κώδικας χρήστη πηγαίνει εδώ

	HTMLCollection htmlCollection = document.GetElementsByTagNameNS("http://www.company.com", "customtag");
	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// Ο κώδικας χρήστη πηγαίνει εδώ
}
```

*inputHtmlPath - user input xhtml file path.

# Console output

Βρέθηκε: 1

Το προσαρμοσμένο περιεχόμενο ετικέτας του προσαρμοσμένου πακέτου πηγαίνει εδώ...

### Δείτε επίσης

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
