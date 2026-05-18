---
title: "Document.GetElementsByClassName"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος εγγράφου. Η μέθοδος getElementsByClassName της διεπαφής Document επιστρέφει ένα αντικείμενο τύπου πίνακα με όλα τα παιδικά στοιχεία που έχουν όλα τα δοσμένα ονόματα κλάσης."
type: docs

url: /el/java/com.aspose.html.dom/document/getelementsbyclassname/
---
## Document.GetElementsByClassName method

Η μέθοδος getElementsByClassName της διεπαφής [`Document`](../) επιστρέφει ένα αντικείμενο τύπου πίνακα με όλα τα παιδικά στοιχεία που έχουν όλα τα δοσμένα ονόματα κλάσης.

Όταν κληθεί στο αντικείμενο εγγράφου, αναζητείται ολόκληρο το έγγραφο, συμπεριλαμβανομένου του ριζικού κόμβου. Μπορείτε επίσης να καλέσετε τη getElementsByClassName() σε οποιοδήποτε στοιχείο· θα επιστρέψει μόνο τα στοιχεία που είναι απόγονοι του καθορισμένου ριζικού στοιχείου με τα δοσμένα ονόματα κλάσης.

```java
public HTMLCollection GetElementsByClassName(String classNames)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| classNames | String | Η String String που περιέχει ένα αταξινόμητο σύνολο μοναδικών διαχωρισμένων διαστήματος διακριτών που αντιπροσωπεύουν κλάσεις (ονόματα κλάσεων) |

### Τιμή επιστροφής

Μια ζωντανή [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) των ευρεθέντων στοιχείων.

## Παρατηρήσεις

Ανατρέξτε στην επίσημη [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbyclassname).

Το περιεχόμενο πρακτικής ανάπτυξης ιστού μπορεί να βρεθεί στο [w3schools](https://www.w3schools.com/jsref/met_element_getelementsbyclassname.asp).

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Παραδείγματα

```java
var elements = document.GetElementsByClassName("red test");
```

```java
// Περιεχόμενο HTML
<div class="custom-class">Customized by css class container</div>

// Κώδικας C#
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
         
	// Ο κώδικας χρήστη πηγαίνει εδώ
}
```

// Έξοδος κονσόλας

Βρέθηκε: 1

Προσαρμοσμένο από την κλάση css container

*inputHtmlPath - user input html file path

```java
// Στυλ CSS
.ddd{
	padding: 10pt;
}

.kkk{
	background-color: chartreuse;
}

// Περιεχόμενο HTML
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
         
	// Ο κώδικας χρήστη πηγαίνει εδώ
}
```

# Console output

Βρέθηκε: 2

Παράγραφος μορφοποιημένη από το όνομα κλάσης =ddd kkk=

Τύπος στοιχείου: Aspose.Html.HTMLParagraphElement

Παράγραφος μορφοποιημένη από το όνομα κλάσης =ddd fff=

Τύπος στοιχείου: Aspose.Html.HTMLParagraphElement

*inputHtmlPath - user input html file path

```java
// Στυλ CSS
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
         
	// Ο κώδικας χρήστη πηγαίνει εδώ
}
```

# Console output

Βρέθηκε: 4

Πρώτο μορφοποιημένο από την παράγραφο κλάσης pStyle

Τύπος στοιχείου: Aspose.Html.HTMLParagraphElement

Δεύτερο μορφοποιημένο από την παράγραφο κλάσης pStyle

Τύπος στοιχείου: Aspose.Html.HTMLParagraphElement

Τρίτο μορφοποιημένο από την παράγραφο κλάσης pStyle

Τύπος στοιχείου: Aspose.Html.HTMLParagraphElement

Span μορφοποιημένο από το pStyle

Τύπος στοιχείου: Aspose.Html.HTMLElement

*inputHtmlPath - user input html file path

### Δείτε επίσης

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
