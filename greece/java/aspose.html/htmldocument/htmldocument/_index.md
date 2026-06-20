---
title: "HTMLDocument"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "HTMLDocument constructor. Ο κατασκευαστής HTMLDocument δημιουργεί ένα νέο αντικείμενο HTML Document που είναι μια ιστοσελίδα που φορτώνεται στο πρόγραμμα περιήγησης και λειτουργεί ως σημείο εισόδου στο περιεχόμενο των σελίδων."
type: docs

url: /el/java/com.aspose.html/htmldocument/htmldocument/
---
## HTMLDocument() {#constructor}

Ο κατασκευαστής HTMLDocument δημιουργεί ένα νέο αντικείμενο HTML Document που είναι μια ιστοσελίδα φορτωμένη στον περιηγητή και λειτουργεί ως σημείο εισόδου στο περιεχόμενο της σελίδας.

```java
public HTMLDocument()
```

## Παρατηρήσεις

Σημείωση: Το έγγραφο δημιουργείται με προεπιλεγμένη τιμή για την ιδιότητα base-url που είναι ίση με 'about:blank'.

Αναφορά:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Παραδείγματα

Μόλις δημιουργηθεί το αντικείμενο εγγράφου, μπορεί αργότερα να γεμίσει με στοιχεία HTML. Το παρακάτω απόσπασμα κώδικα δείχνει τη χρήση του προεπιλεγμένου κατασκευαστή HTMLDocument() για τη δημιουργία ενός κενού εγγράφου HTML και την αποθήκευσή του σε αρχείο.

```java
import (var document = new HTMLDocument())
{
	// Εργαστείτε με το έγγραφο εδώ
	...	
	
	// Αποθηκεύστε το έγγραφο σε αρχείο
	document.Save("document.html");
}
```

### Δείτε επίσης

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Configuration) {#constructor_1}

Ο κατασκευαστής HTMLDocument δημιουργεί ένα νέο αντικείμενο HTML Document που είναι μια ιστοσελίδα φορτωμένη στον περιηγητή και λειτουργεί ως σημείο εισόδου στο περιεχόμενο της σελίδας.

```java
public HTMLDocument(Configuration configuration)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| διαμόρφωση | Διαμόρφωση | Η διαμόρφωση του περιβάλλοντος όπως η πολιτική σεναρίων, το προσαρμοσμένο φύλλο στυλ χρήστη, κ.λπ. |

## Παρατηρήσεις

Σημείωση: Το έγγραφο δημιουργείται με προεπιλεγμένη τιμή για την ιδιότητα base-url που είναι ίση με 'about:blank'.

Αναφορά:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να χρησιμοποιήσετε το αντικείμενο διαμόρφωσης για να απενεργοποιήσετε τα σενάρια:

```java
// Προετοιμάστε κώδικα HTML και αποθηκεύστε τον σε ένα αρχείο
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Δημιουργήστε μια παρουσία της Configuration
import (var configuration = new Configuration())
{
	// Σημειώστε το 'scripts' ως μη αξιόπιστο πόρο
	configuration.Security |= Sandbox.Scripts;

	// Αρχικοποιήστε ένα έγγραφο HTML με την καθορισμένη διαμόρφωση
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// Μετατρέψτε HTML σε PDF
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### Δείτε επίσης

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url) {#constructor_4}

Φορτώνει το έγγραφο HTML από ένα URL.

Σημείωση: Σε περίπτωση που περάσετε ένα λανθασμένο URL που δεν μπορεί να προσεγγιστεί αυτή τη στιγμή, η βιβλιοθήκη ρίχνει το [`DOMException`](../../../com.aspose.html.dom/domexception/) με εξειδικευμένο κώδικα ‘NetworkError’ για να σας ενημερώσει ότι ο επιλεγμένος πόρος δεν μπορεί να βρεθεί.

```java
public HTMLDocument(Url url)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Το URL του εγγράφου HTML για άνοιγμα. |

## Παρατηρήσεις

Αναφορά:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Παραδείγματα

Φορτώστε ένα έγγραφο από τη σελίδα web 'https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html':

```java
import (var document = new HTMLDocument("https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html"))
{
	// Γράψτε το περιεχόμενο του εγγράφου στην έξοδο ροής
	Console.WriteLine(document.DocumentElement.OuterHTML);
}
```

### Δείτε επίσης

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url, Configuration) {#constructor_5}

Φορτώνει το έγγραφο HTML από ένα URL με καθορισμένες ρυθμίσεις διαμόρφωσης περιβάλλοντος.

Σημείωση: Σε περίπτωση που περάσετε ένα λανθασμένο URL που δεν μπορεί να προσεγγιστεί αυτή τη στιγμή, η βιβλιοθήκη ρίχνει το [DOMException](T:com.aspose.html.dom.DOMException) με εξειδικευμένο κώδικα ‘NetworkError’ για να σας ενημερώσει ότι ο επιλεγμένος πόρος δεν μπορεί να βρεθεί.

```java
public HTMLDocument(Url url, Configuration configuration)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Το URL του εγγράφου HTML για άνοιγμα. |
| διαμόρφωση | Διαμόρφωση | Η διαμόρφωση του περιβάλλοντος όπως η πολιτική σεναρίων, το προσαρμοσμένο φύλλο στυλ χρήστη, κ.λπ. |

## Παρατηρήσεις

Αναφορά:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Παραδείγματα

```java
The following example demonstrates how to use the configuration object to disable scripts:

// Προετοιμάστε κώδικα HTML και αποθηκεύστε τον σε ένα αρχείο
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Δημιουργήστε μια παρουσία της Configuration
import (var configuration = new Configuration())
{
	// Σημειώστε το 'scripts' ως μη αξιόπιστο πόρο
	configuration.Security |= Sandbox.Scripts;

	// Αρχικοποιήστε ένα έγγραφο HTML με την καθορισμένη διαμόρφωση
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// Μετατρέψτε HTML σε PDF
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### Δείτε επίσης

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String) {#constructor_10}

Φορτώνει το έγγραφο HTML από μια διεύθυνση.

Σημείωση: Σε περίπτωση που περάσετε ένα λανθασμένο URL που δεν μπορεί να προσεγγιστεί αυτή τη στιγμή, η βιβλιοθήκη ρίχνει το [`DOMException`](../../../com.aspose.html.dom/domexception/) με εξειδικευμένο κώδικα ‘NetworkError’ για να σας ενημερώσει ότι ο επιλεγμένος πόρος δεν μπορεί να βρεθεί.

```java
public HTMLDocument(String address)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| διεύθυνση | String | Η διεύθυνση του εγγράφου HTML για άνοιγμα. |

## Παρατηρήσεις

Αναφορά:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Παραδείγματα

Αρχικοποιήστε ένα έγγραφο HTML από μια διεύθυνση.

```java
import (var document = new HTMLDocument("./my-folder/document.html")))
{
	...
}
```

### Δείτε επίσης

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Configuration) {#constructor_11}

Φορτώνει το έγγραφο HTML από μια διεύθυνση με καθορισμένες ρυθμίσεις διαμόρφωσης περιβάλλοντος.

Σημείωση: Σε περίπτωση που περάσετε ένα λανθασμένο URL που δεν μπορεί να προσεγγιστεί αυτή τη στιγμή, η βιβλιοθήκη ρίχνει το [`DOMException`](../../../com.aspose.html.dom/domexception/) με εξειδικευμένο κώδικα ‘NetworkError’ για να σας ενημερώσει ότι ο επιλεγμένος πόρος δεν μπορεί να βρεθεί.

```java
public HTMLDocument(String address, Configuration configuration)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| διεύθυνση | String | Η διεύθυνση του εγγράφου HTML για άνοιγμα. |
| διαμόρφωση | Διαμόρφωση | Η διαμόρφωση του περιβάλλοντος όπως η πολιτική σεναρίων, το προσαρμοσμένο φύλλο στυλ χρήστη, κ.λπ. |

## Παρατηρήσεις

Αναφορά:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Παραδείγματα

```java
// Δημιουργήστε μια παρουσία της Configuration
import (var configuration = new Configuration())
{
	// Σημειώστε το 'scripts' ως μη αξιόπιστο πόρο
	configuration.Security |= Sandbox.Scripts;
	
	using (var document = new HTMLDocument("./my-folder/document.html", configuration)))
	{
		...
	}
}
```

### Δείτε επίσης

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String) {#constructor_14}

Δημιουργεί ένα έγγραφο HTML από περιεχόμενο τύπου String με καθορισμένο base-uri.

```java
public HTMLDocument(String content, String baseUri)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | Το περιεχόμενο String για τη φόρτωση του εγγράφου. |
| baseUri | String | Η βασική διεύθυνση URI του εγγράφου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκπέμπει εξαίρεση εάν η παράμετρος base-uri είναι null. |

## Παρατηρήσεις

Αναφορά:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Παραδείγματα

```java
// Προετοιμάστε κώδικα HTML
var html_code = "<p>Hello World!</p>";

// Αρχικοποιήστε ένα έγγραφο από τη μεταβλητή String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Δείτε επίσης

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String, Configuration) {#constructor_15}

Δημιουργεί ένα έγγραφο HTML από περιεχόμενο τύπου String με καθορισμένο base-uri και ρυθμίσεις διαμόρφωσης περιβάλλοντος.

```java
public HTMLDocument(String content, String baseUri, Configuration configuration)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | Το περιεχόμενο String για τη φόρτωση του εγγράφου. |
| baseUri | String | Η βασική διεύθυνση URI του εγγράφου. |
| διαμόρφωση | Διαμόρφωση | Η διαμόρφωση του περιβάλλοντος όπως η πολιτική σεναρίων, το προσαρμοσμένο φύλλο στυλ χρήστη, κ.λπ. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκπέμπει εξαίρεση εάν η παράμετρος base-uri είναι null. |

## Παρατηρήσεις

Αναφορά:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Παραδείγματα

```java
// Προετοιμάστε κώδικα HTML
var html_code = "<p>Hello World!</p>";

// Αρχικοποιήστε ένα έγγραφο από τη μεταβλητή String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Δείτε επίσης

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url) {#constructor_12}

Δημιουργεί ένα έγγραφο HTML από περιεχόμενο τύπου String με καθορισμένο base-uri.

```java
public HTMLDocument(String content, Url baseUri)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | Το περιεχόμενο String για τη φόρτωση του εγγράφου. |
| baseUri | Url | Η βασική διεύθυνση URI του εγγράφου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκπέμπει εξαίρεση εάν η παράμετρος base-uri είναι null. |

## Παρατηρήσεις

Αναφορά:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Παραδείγματα

```java
// Προετοιμάστε κώδικα HTML
var html_code = "<p>Hello World!</p>";

// Αρχικοποιήστε ένα έγγραφο από τη μεταβλητή String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Δείτε επίσης

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url, Configuration) {#constructor_13}

Δημιουργεί ένα έγγραφο HTML από περιεχόμενο τύπου String με καθορισμένο base-uri και ρυθμίσεις διαμόρφωσης περιβάλλοντος.

```java
public HTMLDocument(String content, Url baseUri, Configuration configuration)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | Το περιεχόμενο String για τη φόρτωση του εγγράφου. |
| baseUri | Url | Η βασική διεύθυνση URI του εγγράφου. |
| διαμόρφωση | Διαμόρφωση | Η διαμόρφωση του περιβάλλοντος όπως η πολιτική σεναρίων, το προσαρμοσμένο φύλλο στυλ χρήστη, κ.λπ. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκπέμπει εξαίρεση εάν η παράμετρος base-uri είναι null. |

## Παρατηρήσεις

Αναφορά:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Παραδείγματα

```java
// Προετοιμάστε κώδικα HTML
var html_code = "<p>Hello World!</p>";

// Αρχικοποιήστε ένα έγγραφο από τη μεταβλητή String
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### Δείτε επίσης

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String) {#constructor_8}

Δημιουργεί ένα έγγραφο HTML από περιεχόμενο [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) με καθορισμένο base-uri που χρησιμοποιείται για την επίλυση της διαδρομής των σχετικών πόρων.

```java
public HTMLDocument(Stream content, String baseUri)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| content | Stream | Το περιεχόμενο [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) για τη φόρτωση του εγγράφου. |
| baseUri | String | Η βασική διεύθυνση URI του εγγράφου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκπέμπει εξαίρεση εάν η παράμετρος base-uri είναι null. |

## Παρατηρήσεις

Αναφορά:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Παραδείγματα

```java
// Δημιουργήστε ένα αντικείμενο memory stream.
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Γράψτε τον κώδικα HTML στο αντικείμενο μνήμης
	sw.Write("<p>Hello World! I love HTML!</p>");

	// It is important to set the position to the beginning since HTMLDocument starts the reading exactly from the current position within the stream
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Αρχικοποιήστε ένα έγγραφο από τη μεταβλητή String
	using (var document = new HTMLDocument(mem, "."))
	{
		// Save the document to a disk
		document.Save("load-from-stream.html");
	}
}
```

### Δείτε επίσης

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String, Configuration) {#constructor_9}

Δημιουργεί ένα έγγραφο HTML από περιεχόμενο [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) με καθορισμένο base-uri και ρυθμίσεις διαμόρφωσης περιβάλλοντος.

```java
public HTMLDocument(Stream content, String baseUri, Configuration configuration)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| content | Stream | Το περιεχόμενο [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) για τη φόρτωση του εγγράφου. |
| baseUri | String | Η βασική διεύθυνση URI του εγγράφου. |
| διαμόρφωση | Διαμόρφωση | Η διαμόρφωση του περιβάλλοντος όπως η πολιτική σεναρίων, το προσαρμοσμένο φύλλο στυλ χρήστη, κ.λπ. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκπέμπει εξαίρεση εάν η παράμετρος base-uri είναι null. |

## Παρατηρήσεις

Αναφορά:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Παραδείγματα

```java
// Δημιουργήστε ένα αντικείμενο memory stream.
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Γράψτε τον κώδικα HTML στο αντικείμενο μνήμης
	sw.Write("<p>Hello World! I love HTML!</p>");

	// It is important to set the position to the beginning since HTMLDocument starts the reading exactly from the current position within the stream
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Αρχικοποιήστε ένα έγγραφο από τη μεταβλητή String
	using (var document = new HTMLDocument(mem, "."))
	{
		// Save the document to a disk
		document.Save("load-from-stream.html");
	}
}
```

### Δείτε επίσης

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url) {#constructor_6}

Δημιουργεί ένα έγγραφο HTML από περιεχόμενο [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) με καθορισμένο base-uri που χρησιμοποιείται για την επίλυση της διαδρομής των σχετικών πόρων.

```java
public HTMLDocument(Stream content, Url baseUri)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| content | Stream | Το περιεχόμενο [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) για τη φόρτωση του εγγράφου. |
| baseUri | Url | Η βασική διεύθυνση URI του εγγράφου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκπέμπει εξαίρεση εάν η παράμετρος base-uri είναι null. |

## Παρατηρήσεις

Αναφορά:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Παραδείγματα

```java
// Δημιουργήστε ένα αντικείμενο memory stream.
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Γράψτε τον κώδικα HTML στο αντικείμενο μνήμης
	sw.Write("<p>Hello World! I love HTML!</p>");

	// It is important to set the position to the beginning since HTMLDocument starts the reading exactly from the current position within the stream
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Αρχικοποιήστε ένα έγγραφο από τη μεταβλητή String
	using (var document = new HTMLDocument(mem, "."))
	{
		// Save the document to a disk
		document.Save("load-from-stream.html");
	}
}
```

### Δείτε επίσης

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url, Configuration) {#constructor_7}

Δημιουργεί ένα έγγραφο HTML από περιεχόμενο [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) με καθορισμένο base-uri και ρυθμίσεις διαμόρφωσης περιβάλλοντος.

```java
public HTMLDocument(Stream content, Url baseUri, Configuration configuration)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| content | Stream | Το περιεχόμενο [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) για τη φόρτωση του εγγράφου. |
| baseUri | Url | Η βασική διεύθυνση URI του εγγράφου. |
| διαμόρφωση | Διαμόρφωση | Η διαμόρφωση του περιβάλλοντος όπως η πολιτική σεναρίων, το προσαρμοσμένο φύλλο στυλ χρήστη, κ.λπ. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | Εκπέμπει εξαίρεση εάν η παράμετρος base-uri είναι null. |

## Παρατηρήσεις

Αναφορά:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## Παραδείγματα

```java
// Δημιουργήστε ένα αντικείμενο memory stream.
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// Γράψτε τον κώδικα HTML στο αντικείμενο μνήμης
	sw.Write("<p>Hello World! I love HTML!</p>");

	// It is important to set the position to the beginning since HTMLDocument starts the reading exactly from the current position within the stream
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// Αρχικοποιήστε ένα έγγραφο από τη μεταβλητή String
	using (var document = new HTMLDocument(mem, "."))
	{
		// Save the document to a disk
		document.Save("load-from-stream.html");
	}
}
```

### Δείτε επίσης

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage) {#constructor_2}

Creates an HTML document from the [`RequestMessage`](../../../com.aspose.html.net/requestmessage/) object.

```java
public HTMLDocument(RequestMessage request)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| request | RequestMessage | The request message that contains a [`body`](../../../com.aspose.html.net/requestmessage/content/) with document content. |

## Παρατηρήσεις

By definition, a message handler is a class that receives a Web request and returns a Web response. In other words, a message handler is used to process a Web service request during input and/or to process the response during output.

Please, visit our [docs site](https://docs.aspose.com/html/net/message-handlers/) to see more scenarios on how to use this constructor.

Αναφορά:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Δείτε επίσης

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage, Configuration) {#constructor_3}

Δημιουργεί ένα έγγραφο HTML από ένα αντικείμενο [RequestMessage](T:com.aspose.html.net.RequestMessage).

```java
public HTMLDocument(RequestMessage request, Configuration configuration)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| request | RequestMessage | The request message that contains a [body](P:com.aspose.html.net.RequestMessage.Content) with document content. |
| διαμόρφωση | Διαμόρφωση | Η διαμόρφωση του περιβάλλοντος όπως η πολιτική σεναρίων, το προσαρμοσμένο φύλλο στυλ χρήστη, κ.λπ. |

## Παρατηρήσεις

By definition, a message handler is a class that receives a Web request and returns a Web response. In other words, a message handler is used to process a Web service request during input and/or to process the response during output.

Please, visit our [docs site](https://docs.aspose.com/html/net/message-handlers/) to see more scenarios on how to use this constructor.

Αναφορά:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Δείτε επίσης

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
