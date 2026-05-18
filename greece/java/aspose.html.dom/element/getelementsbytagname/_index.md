---
title: "Element.GetElementsByTagName"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Element. Επιστρέφει ένα αντικείμενο HTMLCollection που περιέχει όλα τα στοιχεία με το δοσμένο όνομα ετικέτας με τη σειρά του εγγράφου"
type: docs

url: /el/java/com.aspose.html.dom/element/getelementsbytagname/
---
## Element.GetElementsByTagName method

Επιστρέφει το αντικείμενο [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) που περιέχει όλα τα [`elements`](../) με το δοσμένο όνομα ετικέτας, με τη σειρά του εγγράφου.

```java
public HTMLCollection GetElementsByTagName(String name)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| name | String | Το όνομα ετικέτας. Αναπαράσταση συμβολοσειράς του ονόματος ετικέτας. |

### Τιμή επιστροφής

Ένα αντικείμενο [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) είναι μια λίστα παρόμοια με πίνακα από [`elements`](../).

## Παρατηρήσεις

Ανατρέξτε στην επίσημη [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbytagname).

Μπορεί επίσης να σας ενδιαφέρει η [documentation](https://docs.aspose.com/html/net/).

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Παραδείγματα

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
	// Ο κώδικας χρήστη πηγαίνει εδώ

	HTMLCollection htmlCollection = document.GetElementsByTagName("p");
	Console.WriteLine($"Found: {htmlCollection.Length}" );
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}
         
	// Ο κώδικας χρήστη πηγαίνει εδώ
}
```

*inputHtmlPath - user input html file.

# Console output

Βρέθηκαν: 3

Το περιεχόμενο της παραγράφου με την κλάση pStyle...

Το περιεχόμενο της δεύτερης παραγράφου...

Το περιεχόμενο της τρίτης παραγράφου...

### Δείτε επίσης

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
