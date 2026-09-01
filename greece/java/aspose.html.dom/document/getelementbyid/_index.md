---
title: "Document.GetElementById"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Document. Η μέθοδος Document getElementById επιστρέφει ένα αντικείμενο Element που αντιπροσωπεύει το στοιχείο του οποίου η ιδιότητα id ταιριάζει με το καθορισμένο String. Δεδομένου ότι τα IDs των στοιχείων πρέπει να είναι μοναδικά εάν καθοριστούν, αποτελούν έναν χρήσιμο τρόπο γρήγορης πρόσβασης σε ένα συγκεκριμένο στοιχείο."
type: docs

url: /el/java/com.aspose.html.dom/document/getelementbyid/
---
## Document.GetElementById method

Η μέθοδος Document getElementById() επιστρέφει ένα αντικείμενο [`Element`](../../element/) που αντιπροσωπεύει το στοιχείο του οποίου η ιδιότητα id ταιριάζει με το καθορισμένο String. Δεδομένου ότι τα IDs των στοιχείων πρέπει να είναι μοναδικά εάν καθοριστούν, αποτελούν έναν χρήσιμο τρόπο γρήγορης πρόσβασης σε ένα συγκεκριμένο στοιχείο.

Εάν χρειάζεστε πρόσβαση σε ένα στοιχείο που δεν έχει ID, μπορείτε να χρησιμοποιήσετε τη querySelector() για να βρείτε το στοιχείο χρησιμοποιώντας οποιονδήποτε επιλογέα.

```java
public Element GetElementById(String elementId)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| elementId | String | Το ID του στοιχείου που πρέπει να εντοπιστεί. Το ID είναι μια ευαίσθητη σε πεζά-κεφαλαία String που είναι μοναδική μέσα στο έγγραφο· μόνο ένα στοιχείο μπορεί να έχει το συγκεκριμένο ID. |

### Τιμή Επιστροφής

Ένα αντικείμενο [`Element`](../../element/) που περιγράφει το αντικείμενο DOM element που ταιριάζει με το καθορισμένο ID, ή null εάν δεν βρέθηκε κανένα στοιχείο που να ταιριάζει στο έγγραφο.

## Παρατηρήσεις

Αναφερθείτε στην επίσημη [προδιαγραφή](https://dom.spec.whatwg.org/#dom-nonelementparentnode-getelementbyid).

Το περιεχόμενο πρακτικής ανάπτυξης ιστού μπορεί να βρεθεί στο [w3schools](https://www.w3schools.com/jsref/met_document_getelementbyid.asp).

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Παραδείγματα

```java
// Περιεχόμενο HTML
<div id="uniqueIdentifier">Container with ID - identifier</div>

// Κώδικας C#
import System;
import Aspose.Html;
import com.aspose.html.dom;
...
	using (var document = new HTMLDocument(inputHtmlPath))
		{
			Element element = document.GetElementById("uniqueIdentifier");
			HTMLDivElement divElement = (HTMLDivElement) element;
			Console.WriteLine(divElement.InnerHTML);

			// Ο κώδικας χρήστη πηγαίνει εδώ
   }
```

// Έξοδος κονσόλας

Δοχείο με ID - αναγνωριστικό

*inputHtmlPath - user input html file path

### Δείτε επίσης

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
