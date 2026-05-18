---
title: "Document.GetElementsByTagName"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Document. Η μέθοδος getElementsByTagName της διεπαφής Document επιστρέφει μια HTMLCollection από στοιχεία με το συγκεκριμένο όνομα ετικέτας."
type: docs

url: /el/java/com.aspose.html.dom/document/getelementsbytagname/
---
## Document.GetElementsByTagName method

Η μέθοδος getElementsByTagName της διεπαφής [`Document`](../) επιστρέφει μια [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) από στοιχεία με το συγκεκριμένο όνομα ετικέτας.

Το πλήρες έγγραφο αναζητείται, συμπεριλαμβανομένου του ριζικού κόμβου. Η επιστρεφόμενη [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) είναι ζωντανή, πράγμα που σημαίνει ότι ενημερώνεται αυτόματα ώστε να παραμένει συγχρονισμένη με το δέντρο DOM χωρίς να χρειάζεται να κληθεί ξανά το document.getElementsByTagName().

```java
public HTMLCollection GetElementsByTagName(String tagname)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| όνομα ετικέτας | String | Μια Συμβολοσειρά που αντιπροσωπεύει το όνομα των στοιχείων. Η ειδική Συμβολοσειρά "*" αντιπροσωπεύει όλα τα στοιχεία. |

### Τιμή επιστροφής

Μια ζωντανή [`HTMLCollection`](../../../com.aspose.html.collections/htmlcollection/) από τα ευρεθέντα στοιχεία με τη σειρά που εμφανίζονται στο δέντρο.

## Παρατηρήσεις

Αναφερθείτε στην επίσημη [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname).

Πρακτικό περιεχόμενο ανάπτυξης ιστού μπορεί να βρεθεί στο [w3schools](https://www.w3schools.com/jsref/met_document_getelementsbytagname.asp).

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Παραδείγματα

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

    // Ο κώδικας χρήστη πηγαίνει εδώ
}
```

# Console output

Βρέθηκαν: 6

Πρώτο μορφοποιημένο από την παράγραφο κλάσης pStyle

Δεύτερο μορφοποιημένο από την παράγραφο κλάσης pStyle

Τρίτο μορφοποιημένο από την παράγραφο κλάσης pStyle

Παράγραφος μορφοποιημένη από το όνομα κλάσης =ddd kkk=

Παράγραφος μορφοποιημένη από το όνομα κλάσης =ddd fff=

Παράγραφος μορφοποιημένη από το όνομα κλάσης =kkk fff=

*inputHtmlPath - user input html file path

### Δείτε επίσης

* class [HTMLCollection](../../../com.aspose.html.collections/htmlcollection/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
