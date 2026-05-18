---
title: "Element.GetElementsByClassName"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Element μέθοδος. Επιστρέφει αντικείμενο HTMLCollection που περιέχει όλα τα στοιχεία εντός του στοιχείου που έχουν όλες τις κλάσεις που καθορίζονται στο όρισμα"
type: docs

url: /el/java/com.aspose.html.dom/element/getelementsbyclassname/
---
## Element.GetElementsByClassName method

Επιστρέφει το αντικείμενο [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) που περιέχει όλα τα στοιχεία εντός του [`element`](../) που έχουν όλες τις κλάσεις που καθορίζονται στο όρισμα.

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| classNames | String | Η String String που περιέχει ένα αταξινόμητο σύνολο μοναδικών διαχωρισμένων διαστήματος διακριτών που αντιπροσωπεύουν κλάσεις (ονόματα κλάσεων) |

### Τιμή επιστροφής

Ένα αντικείμενο [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) είναι μια λίστα παρόμοια με πίνακα από [`elements`](../).

## Παρατηρήσεις

Ανατρέξτε στην επίσημη [spec](https://dom.spec.whatwg.org/#dom-element-getelementsbyclassname).

Μπορεί επίσης να σας ενδιαφέρει η [documentation](https://docs.aspose.com/html/net/).

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Παραδείγματα

```java
# HTML source content
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

	Element container = document.GetElementById("divElementContainerId");
	HTMLCollection htmlCollection = container.GetElementsByClassName("pStyle");

	Console.WriteLine($"Found: {htmlCollection.Length}");
	foreach (Element element in htmlCollection)
	{
		Console.WriteLine(element.InnerHTML);
	}

	// Ο κώδικας χρήστη πηγαίνει εδώ
}
```

*inputHtmlPath - user input html file path.

# Console output

Βρέθηκε: 2

Το περιεχόμενο της παραγράφου με την κλάση pStyle...

Το στοιχείο div με την κλάση pStyle...

### Δείτε επίσης

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
