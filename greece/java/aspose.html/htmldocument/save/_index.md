---
title: "HTMLDocument.Save"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "HTMLDocument μέθοδος. Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από url. Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν σε έναν γειτονικό φάκελο του οποίου το όνομα θα κατασκευαστεί ως output_file_name _files."
type: docs

url: /el/java/com.aspose.html/htmldocument/save/
---
## Save(Url) {#save_5}

Αποθηκεύει το έγγραφο σε ένα τοπικό αρχείο που καθορίζεται από το url. Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν σε έναν διπλανό φάκελο, του οποίου το όνομα θα κατασκευαστεί ως output_file_name + \"_files\".

```java
public void Save(Url url)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Τοπικό [`URL`](../../url/) στο αρχείο εξόδου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εγείρεται εάν το καθορισμένο `url` δεν είναι έγκυρη τοπική URL αρχείου. |

## Παρατηρήσεις

Αποθήκευση HTML

Οι περισσότερες εργασίες που πρέπει να εκτελέσετε απαιτούν την αποθήκευση ενός εγγράφου. Μόλις φορτώσετε το υπάρχον αρχείο ή δημιουργήσετε ένα έγγραφο HTML από το μηδέν, μπορείτε να αποθηκεύσετε τις αλλαγές σας χρησιμοποιώντας μία από τις μεθόδους HTMLDocument.Save(). Οι μέθοδοι επιτρέπουν την αποθήκευση HTML σε τοπικό αρχείο που καθορίζεται από διαδρομή, URL ή αποθήκευση εξόδου. Ανατρέξτε στην [τεκμηρίωση](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) για να μάθετε περισσότερα σχετικά με την αποθήκευση.

Save(Url) Μέθοδος

Απαιτείται να καθοριστεί μια πλήρης διαδρομή Url - 'outputFilePath' για την αποθήκευση εγγράφου HTML. Ο κατασκευαστής Url(url) δημιουργεί μια παρουσία της κλάσης [`Url`](../../url/) με το καθορισμένο url. Στη συνέχεια πρέπει να περάσετε την παρουσία στη μέθοδο Save(Url). Το έγγραφο θα αποθηκευτεί στο τοπικό αρχείο που καθορίζεται από url. Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν σε έναν γειτονικό φάκελο, του οποίου το όνομα θα κατασκευαστεί ως output_file_name + \"_files\".

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Παραδείγματα

```java
import System;
import System.IO;
import Aspose.Html;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
        
	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(new Url(outputFilePath));
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### Δείτε επίσης

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler) {#save}

Αποθηκεύει το περιεχόμενο του εγγράφου και τους πόρους χρησιμοποιώντας το [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Ο διαχειριστής πόρων [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |

### Δείτε επίσης

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String) {#save_10}

Αποθηκεύει το έγγραφο σε ένα τοπικό αρχείο που καθορίζεται από τη διαδρομή. Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν σε έναν γειτονικό φάκελο, του οποίου το όνομα θα κατασκευαστεί ως: output_file_name + "_files".

```java
public void Save(String path)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| διαδρομή | String | Διαδρομή συστήματος αρχείων τοπικού υπολογιστή στο αρχείο εξόδου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εγείρεται εάν η καθορισμένη `path` δεν είναι έγκυρη τοπική διαδρομή αρχείου. |

## Παρατηρήσεις

Αποθήκευση HTML

Οι περισσότερες εργασίες που πρέπει να εκτελέσετε απαιτούν την αποθήκευση ενός εγγράφου. Μόλις φορτώσετε το υπάρχον αρχείο ή δημιουργήσετε ένα έγγραφο HTML από το μηδέν, μπορείτε να αποθηκεύσετε τις αλλαγές σας χρησιμοποιώντας μία από τις μεθόδους HTMLDocument.Save(). Οι μέθοδοι επιτρέπουν την αποθήκευση HTML σε τοπικό αρχείο που καθορίζεται από διαδρομή, URL ή αποθήκευση εξόδου. Ανατρέξτε στην [τεκμηρίωση](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) για να μάθετε περισσότερα σχετικά με την αποθήκευση.

Η μέθοδος Save(String) λαμβάνει ως παράμετρο μια διαδρομή συστήματος αρχείων τοπικού υπολογιστή σε αρχείο εξόδου και αποθηκεύει ένα έγγραφο HTML στο τοπικό αρχείο που καθορίζεται από τη διαδρομή. Όλοι οι πόροι που χρησιμοποιούνται στο έγγραφο θα αποθηκευτούν σε έναν γειτονικό φάκελο.

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Παραδείγματα

```java
import System;
import System.IO;
import Aspose.Html;
...
 using (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (outputHtmlPath == null)
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(outputFilePath);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output directory path.

### Δείτε επίσης

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveFormat) {#save_11}

Αποθηκεύει το έγγραφο σε ένα τοπικό αρχείο που καθορίζεται από τη διαδρομή. Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν σε έναν διπλανό φάκελο, του οποίου το όνομα θα κατασκευαστεί ως output_file_name + \"_files\".

```java
public void Save(String path, HTMLSaveFormat saveFormat)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| διαδρομή | String | Τοπική διαδρομή αρχείου στο αρχείο εξόδου. |
| saveFormat | HTMLSaveFormat | Μορφή στην οποία αποθηκεύεται το έγγραφο. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εγείρεται εάν η καθορισμένη `path` δεν είναι έγκυρη τοπική διαδρομή αρχείου. |

## Παρατηρήσεις

Αποθήκευση HTML

Οι περισσότερες εργασίες που πρέπει να εκτελέσετε απαιτούν την αποθήκευση ενός εγγράφου. Μόλις φορτώσετε το υπάρχον αρχείο ή δημιουργήσετε ένα έγγραφο HTML από το μηδέν, μπορείτε να αποθηκεύσετε τις αλλαγές σας χρησιμοποιώντας μία από τις μεθόδους HTMLDocument.Save(). Οι μέθοδοι επιτρέπουν την αποθήκευση HTML σε τοπικό αρχείο που καθορίζεται από διαδρομή, URL ή αποθήκευση εξόδου. Ανατρέξτε στην [τεκμηρίωση](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) για να μάθετε περισσότερα σχετικά με την αποθήκευση.

Save(String, HTMLSaveFormat) Μέθοδος

Η μέθοδος Save(String, HTMLSaveFormat) λαμβάνει ως παραμέτρους μια διαδρομή του τοπικού συστήματος αρχείων προς το αρχείο εξόδου και το saveFormat. Η [`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) Απαρίθμηση καθορίζει τη μορφή στην οποία αποθηκεύεται το έγγραφο, μπορεί να είναι μορφές HTML, MHTML και MD. Η μέθοδος αποθηκεύει το έγγραφο HTML στην καθορισμένη μορφή στο τοπικό αρχείο που ορίζεται από τη διαδρομή. Όλοι οι πόροι που χρησιμοποιούνται στο έγγραφο θα αποθηκευτούν σε έναν γειτονικό φάκελο.

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Παραδείγματα

```java
# HTML input file content
<!DOCTYPE html>
<html lang="en"
   xmlns:xml="http://www.w3.org/XML/1998/package">
<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="styles/main.css">
  <title>Title</title>
</head>
<body>
<div id="uniqueIdentifier">Container with ID - identifier</div>
<div class="custom-class">Customized by css class container</div>

<div>
  <p class="pStyle">First styled by pStyle class paragraph</p>
  <p class="pStyle">Second styled by pStyle class paragraph</p>
  <p class="pStyle">Third styled by pStyle class paragraph</p>
  <span class="pStyle">Span styled by pStyle</span>
</div>

<math xmlns="http://www.w3.org/1998/Math/MathML">
  <mrow>...</mrow>
</math>

<div id="smart class">
  <p id="p1" class="ddd kkk">Paragraph styled by class name =ddd kkk=</p>
  <p id="p2" class="ddd fff">Paragraph styled by class name =ddd fff=</p>
  <p id="p3" class="kkk fff">Paragraph styled by class name =kkk fff=</p>
</div>

</body>
</html>

# C# code
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}
	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtml");
	document.Save(outputFilePath, HTMLSaveFormat.MHTML);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

# Content of result file

MIME-Version: 1.0

Content-Type: Multipart/related; boundary="boundary";type=Text/HTML

--boundary

Content-Type: text/html;

Content-Location: result.mhtml

&lt;!DOCTYPE html&gt;&lt;html lang="el" xmlns:xml="http://www.w3.org/XML/1998/package"&gt;&lt;head&gt;

&lt;meta charset="UTF-8"&gt;

&lt;link rel="stylesheet" href="main.css"&gt;

&lt;title&gt;Τίτλος&lt;/title&gt;

&lt;/head&gt;

&lt;body&gt;

&lt;div id="uniqueIdentifier"&gt;Κοντέινερ με ID - identifier&lt;/div&gt;

&lt;div class="custom-class"&gt;Προσαρμοσμένο από το κοντέινερ της κλάσης css&lt;/div&gt;

&lt;div&gt;

&lt;p class="pStyle"&gt;Πρώτο μορφοποιημένο από την κλάση pStyle παράγραφος&lt;/p&gt;

&lt;p class="pStyle"&gt;Δεύτερο μορφοποιημένο από την κλάση pStyle παράγραφος&lt;/p&gt;

&lt;p class="pStyle"&gt;Τρίτο μορφοποιημένο από την κλάση pStyle παράγραφος&lt;/p&gt;

&lt;span class="pStyle"&gt;Span μορφοποιημένο από pStyle&lt;/span&gt;

&lt;/div&gt;

&lt;math xmlns="http://www.w3.org/1998/Math/MathML"&gt;

&lt;mrow&gt;...&lt;/mrow&gt;

&lt;/math&gt;

&lt;div id="smart class"&gt;

&lt;p id="p1" class="ddd kkk"&gt;Παράγραφος με στυλ από το όνομα κλάσης =ddd kkk=&lt;/p&gt;

&lt;p id="p2" class="ddd fff"&gt;Παράγραφος με στυλ από το όνομα κλάσης =ddd fff=&lt;/p&gt;

&lt;p id="p3" class="kkk fff"&gt;Παράγραφος με στυλ από το όνομα κλάσης =kkk fff=&lt;/p&gt;

&lt;/div&gt;

&lt;div&gt;Γειά σας από το στοιχείο DIV&lt;/div&gt;&lt;/body&gt;&lt;/html&gt;

--boundary

Content-Type: text/css;

Content-Location: main.css

.custom-class { color: yellow; background-color: blueviolet; margin-top: 10pt; margin-right: 10pt; margin-bottom: 10pt; margin-left: 10pt; }.pStyle { font-

--boundary--

### Δείτε επίσης

* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveFormat) {#save_6}

Αποθηκεύει το έγγραφο σε ένα τοπικό αρχείο που καθορίζεται από το url. Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν σε έναν διπλανό φάκελο, του οποίου το όνομα θα κατασκευαστεί ως output_file_name + \"_files\".

```java
public void Save(Url url, HTMLSaveFormat saveFormat)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Τοπική URL για το αρχείο εξόδου. |
| saveFormat | HTMLSaveFormat | Μορφή στην οποία αποθηκεύεται το έγγραφο. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εγείρεται εάν το καθορισμένο `url` δεν είναι έγκυρη τοπική URL αρχείου. |

## Παρατηρήσεις

Αποθήκευση HTML

Οι περισσότερες εργασίες που πρέπει να εκτελέσετε απαιτούν την αποθήκευση ενός εγγράφου. Μόλις φορτώσετε το υπάρχον αρχείο ή δημιουργήσετε ένα έγγραφο HTML από το μηδέν, μπορείτε να αποθηκεύσετε τις αλλαγές σας χρησιμοποιώντας μία από τις μεθόδους HTMLDocument.Save(). Οι μέθοδοι επιτρέπουν την αποθήκευση HTML σε τοπικό αρχείο που καθορίζεται από διαδρομή, URL ή αποθήκευση εξόδου. Ανατρέξτε στην [τεκμηρίωση](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) για να μάθετε περισσότερα σχετικά με την αποθήκευση.

Save(Url, HTMLSaveFormat) Μέθοδος

Απαιτείται να καθοριστεί πλήρης διαδρομή Url - 'outputFilePath' για την αποθήκευση εγγράφου HTML. Ο κατασκευαστής Url(url) δημιουργεί μια παρουσία της κλάσης [`Url`](../../url/) με το καθορισμένο url. Η Καταγραφή [`HTMLSaveFormat`](../../../com.aspose.html.saving/htmlsaveformat/) καθορίζει τη μορφή στην οποία αποθηκεύεται το έγγραφο, μπορεί να είναι μορφές HTML, MHTML και MD. Στη συνέχεια πρέπει να περάσετε τις παραμέτρους στη μέθοδο Save(url, saveFormat). Το έγγραφο θα αποθηκευτεί στην καθορισμένη μορφή στο τοπικό αρχείο που καθορίζεται από το url.

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Παραδείγματα

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtml");
	document.Save(new Url(outputFilePath), HTMLSaveFormat.MHTML);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output directory path.

### Δείτε επίσης

* class [Url](../../url/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveFormat) {#save_1}

Αποθηκεύει το περιεχόμενο του εγγράφου και τους πόρους χρησιμοποιώντας το [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveFormat saveFormat)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Ο διαχειριστής πόρων [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveFormat | HTMLSaveFormat | Μορφή στην οποία αποθηκεύεται το έγγραφο. |

### Δείτε επίσης

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [HTMLSaveFormat](../../../com.aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, HTMLSaveOptions) {#save_12}

Αποθηκεύει το έγγραφο σε ένα τοπικό αρχείο που καθορίζεται από τη διαδρομή. Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν σε έναν γειτονικό φάκελο, του οποίου το όνομα θα κατασκευαστεί ως: output_file_name + "_files".

```java
public void Save(String path, HTMLSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| διαδρομή | String | Τοπική διαδρομή για το αρχείο εξόδου. |
| saveOptions | HTMLSaveOptions | Το αντικείμενο [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) είναι για τη διαχείριση της διαδικασίας διαχείρισης πόρων. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εγείρεται εάν η καθορισμένη `path` δεν είναι έγκυρη τοπική διαδρομή αρχείου. |

## Παρατηρήσεις

Αποθήκευση HTML

Οι περισσότερες εργασίες που πρέπει να εκτελέσετε απαιτούν την αποθήκευση ενός εγγράφου. Μόλις φορτώσετε το υπάρχον αρχείο ή δημιουργήσετε ένα έγγραφο HTML από το μηδέν, μπορείτε να αποθηκεύσετε τις αλλαγές σας χρησιμοποιώντας μία από τις μεθόδους HTMLDocument.Save(). Οι μέθοδοι επιτρέπουν την αποθήκευση HTML σε τοπικό αρχείο που καθορίζεται από διαδρομή, URL ή αποθήκευση εξόδου. Ανατρέξτε στην [τεκμηρίωση](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) για να μάθετε περισσότερα σχετικά με την αποθήκευση.

Save(String, HTMLSaveOptions) Μέθοδος

Η μέθοδος Save(String, HTMLSaveOptions) λαμβάνει ως παραμέτρους μια διαδρομή τοπικού συστήματος αρχείων για το αρχείο εξόδου, μια παρουσία της κλάσης [HTMLSaveOptions](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) και αποθηκεύει ένα έγγραφο HTML με πόρους στο τοπικό αρχείο που καθορίζεται από τη διαδρομή. Ο κατασκευαστής HTMLSaveOptions() δημιουργεί μια παρουσία επιλογών αποθήκευσης που περιέχει ιδιότητες [`ResourceHandlingOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) που χρησιμοποιούνται για τη διαμόρφωση της διαχείρισης πόρων. Όλοι οι πόροι που χρησιμοποιούνται στο έγγραφο θα αποθηκευτούν σε έναν γειτονικό φάκελο.

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Παραδείγματα

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	// Ορίστε την παρουσία κλάσης επιλογών
	var options = new HTMLSaveOptions();
	// Περιορισμός διαχείρισης σελίδων
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Δείτε επίσης

* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveOptions) {#save_7}

Αποθηκεύει το έγγραφο σε ένα τοπικό αρχείο που καθορίζεται από το url. Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν σε έναν διπλανό φάκελο, του οποίου το όνομα θα κατασκευαστεί ως: output_file_name + \"_files\".

```java
public void Save(Url url, HTMLSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Τοπικό [`URL`](../../url/) στο αρχείο εξόδου. |
| saveOptions | HTMLSaveOptions | Το αντικείμενο [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) είναι για τη διαχείριση της διαδικασίας διαχείρισης πόρων. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εγείρεται εάν το καθορισμένο `url` δεν είναι έγκυρη τοπική URL αρχείου. |

## Παρατηρήσεις

Αποθήκευση HTML

Οι περισσότερες εργασίες που πρέπει να εκτελέσετε απαιτούν την αποθήκευση ενός εγγράφου. Μόλις φορτώσετε το υπάρχον αρχείο ή δημιουργήσετε ένα έγγραφο HTML από το μηδέν, μπορείτε να αποθηκεύσετε τις αλλαγές σας χρησιμοποιώντας μία από τις μεθόδους HTMLDocument.Save(). Οι μέθοδοι επιτρέπουν την αποθήκευση HTML σε τοπικό αρχείο που καθορίζεται από διαδρομή, URL ή αποθήκευση εξόδου. Ανατρέξτε στην [τεκμηρίωση](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) για να μάθετε περισσότερα σχετικά με την αποθήκευση.

Save(Url, HTMLSaveOptions) Μέθοδος

Απαιτείται να καθοριστεί πλήρης διαδρομή Url για την αποθήκευση εγγράφου HTML. Ο κατασκευαστής Url(url) δημιουργεί μια παρουσία της κλάσης [`Url`](../../url/) με το καθορισμένο url. Ο κατασκευαστής HTMLSaveOptions() δημιουργεί μια παρουσία της κλάσης [`HTMLSaveOptions`](../../../com.aspose.html.saving/htmlsaveoptions/) που διαθέτει ιδιότητες ResourceHandlingOptions που χρησιμοποιούνται για τη διαμόρφωση της διαχείρισης πόρων. Η μέθοδος Save(url, saveOptions) λαμβάνει παραμέτρους και αποθηκεύει το έγγραφο HTML με πόρους στο τοπικό αρχείο που καθορίζεται από το url.

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Παραδείγματα

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	// Ορίστε την παρουσία κλάσης επιλογών
	var options = new HTMLSaveOptions();
	// Περιορισμός διαχείρισης σελίδων
	options.ResourceHandlingOptions.MaxHandlingDepth = 1;
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Δείτε επίσης

* class [Url](../../url/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, HTMLSaveOptions) {#save_2}

Αποθηκεύει το περιεχόμενο του εγγράφου και τους πόρους χρησιμοποιώντας το [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, HTMLSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Ο διαχειριστής πόρων [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | HTMLSaveOptions | Επιλογές αποθήκευσης HTML. |

### Δείτε επίσης

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [HTMLSaveOptions](../../../com.aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MarkdownSaveOptions) {#save_13}

Αποθηκεύει το έγγραφο σε ένα τοπικό αρχείο που καθορίζεται από τη διαδρομή. Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν σε έναν γειτονικό φάκελο, του οποίου το όνομα θα κατασκευαστεί ως: output_file_name + "_files".

```java
public void Save(String path, MarkdownSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| διαδρομή | String | Τοπική διαδρομή για το αρχείο εξόδου. |
| saveOptions | MarkdownSaveOptions | Η χρήση του αντικειμένου [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε την [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options). |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εγείρεται εάν η καθορισμένη `path` δεν είναι έγκυρη τοπική διαδρομή αρχείου. |

## Παρατηρήσεις

Αποθήκευση HTML

Οι περισσότερες εργασίες που πρέπει να εκτελέσετε απαιτούν την αποθήκευση ενός εγγράφου. Μόλις φορτώσετε το υπάρχον αρχείο ή δημιουργήσετε ένα έγγραφο HTML από το μηδέν, μπορείτε να αποθηκεύσετε τις αλλαγές σας χρησιμοποιώντας μία από τις μεθόδους HTMLDocument.Save(). Οι μέθοδοι επιτρέπουν την αποθήκευση HTML σε τοπικό αρχείο που καθορίζεται από διαδρομή, URL ή αποθήκευση εξόδου. Ανατρέξτε στην [τεκμηρίωση](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) για να μάθετε περισσότερα σχετικά με την αποθήκευση.

Save(String, MarkdownSaveOptions) Μέθοδος

Απαιτείται να καθοριστεί διαδρομή τοπικού συστήματος αρχείων για το αρχείο εξόδου για την αποθήκευση του εγγράφου. Ο κατασκευαστής MarkdownSaveOptions() δημιουργεί μια παρουσία της κλάσης [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) που διαθέτει ένα σύνολο ιδιοτήτων. Για παράδειγμα, μπορείτε να ορίσετε το στυλ μορφοποίησης markdown, να χρησιμοποιήσετε προεπιλεγμένες επιλογές συμβατές με το GitLab Flavored Markdown και να διαμορφώσετε τη διαχείριση πόρων. Η μέθοδος Save(path, saveOptions) λαμβάνει τη διαδρομή τοπικού συστήματος αρχείων για το αρχείο εξόδου και την παρουσία επιλογών ως παραμέτρους και αποθηκεύει το HTML ως έγγραφο Markdown με πόρους στο τοπικό αρχείο που καθορίζεται από τη διαδρομή.

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Παραδείγματα

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
     
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.md");
	// Ορίστε την παρουσία κλάσης επιλογών
	var options = new MarkdownSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file.

*outputHtmlPath - user output folder path.

### Δείτε επίσης

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MarkdownSaveOptions) {#save_8}

Αποθηκεύει το έγγραφο σε ένα τοπικό αρχείο που καθορίζεται από το url. Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν σε έναν διπλανό φάκελο, του οποίου το όνομα θα κατασκευαστεί ως: output_file_name + \"_files\".

```java
public void Save(Url url, MarkdownSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Τοπικό [`URL`](../../url/) στο αρχείο εξόδου. |
| saveOptions | MarkdownSaveOptions | Η χρήση του αντικειμένου [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε την [documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#save-options). |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εγείρεται εάν το καθορισμένο `url` δεν είναι έγκυρη τοπική URL αρχείου. |

## Παρατηρήσεις

Αποθήκευση HTML

Οι περισσότερες εργασίες που πρέπει να εκτελέσετε απαιτούν την αποθήκευση ενός εγγράφου. Μόλις φορτώσετε το υπάρχον αρχείο ή δημιουργήσετε ένα έγγραφο HTML από το μηδέν, μπορείτε να αποθηκεύσετε τις αλλαγές σας χρησιμοποιώντας μία από τις μεθόδους HTMLDocument.Save(). Οι μέθοδοι επιτρέπουν την αποθήκευση HTML σε τοπικό αρχείο που καθορίζεται από διαδρομή, URL ή αποθήκευση εξόδου. Ανατρέξτε στην [τεκμηρίωση](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) για να μάθετε περισσότερα σχετικά με την αποθήκευση.

Save(Url, MarkdownSaveOptions) Μέθοδος

Απαιτείται να καθοριστεί πλήρης διαδρομή Url για την αποθήκευση του εγγράφου. Ο κατασκευαστής Url(url) δημιουργεί μια παρουσία της κλάσης [`Url`](../../url/) με το καθορισμένο url. Ο κατασκευαστής MarkdownSaveOptions() δημιουργεί μια παρουσία της κλάσης [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) που διαθέτει ένα σύνολο ιδιοτήτων. Για παράδειγμα, μπορείτε να ορίσετε το στυλ μορφοποίησης Markdown, να χρησιμοποιήσετε προεπιλεγμένες επιλογές συμβατές με το GitLab Flavored Markdown και να διαμορφώσετε τη διαχείριση πόρων. Η μέθοδος Save(url, saveOptions) λαμβάνει ως παραμέτρους το url και τις παρουσίες επιλογών αποθήκευσης και αποθηκεύει το έγγραφο με πόρους στο τοπικό αρχείο που καθορίζεται από το url.

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Παραδείγματα

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.md");
	// Ορίστε την παρουσία κλάσης επιλογών
	var options = new MarkdownSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Δείτε επίσης

* class [Url](../../url/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MarkdownSaveOptions) {#save_3}

Αποθηκεύει το περιεχόμενο του εγγράφου και τους πόρους χρησιμοποιώντας το [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, MarkdownSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Ο διαχειριστής πόρων [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | MarkdownSaveOptions | Επιλογές αποθήκευσης Markdown. |

### Δείτε επίσης

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(String, MHTMLSaveOptions) {#save_14}

Αποθηκεύει το έγγραφο σε ένα τοπικό αρχείο που καθορίζεται από τη διαδρομή. Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν σε έναν γειτονικό φάκελο, του οποίου το όνομα θα κατασκευαστεί ως: output_file_name + "_files".

```java
public void Save(String path, MHTMLSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| διαδρομή | String | Τοπική διαδρομή για το αρχείο εξόδου. |
| saveOptions | MHTMLSaveOptions | Η χρήση του αντικειμένου [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε την [documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options). |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εγείρεται εάν η καθορισμένη `path` δεν είναι έγκυρη τοπική διαδρομή αρχείου. |

## Παρατηρήσεις

Αποθήκευση HTML

Οι περισσότερες εργασίες που πρέπει να εκτελέσετε απαιτούν την αποθήκευση ενός εγγράφου. Μόλις φορτώσετε το υπάρχον αρχείο ή δημιουργήσετε ένα έγγραφο HTML από το μηδέν, μπορείτε να αποθηκεύσετε τις αλλαγές σας χρησιμοποιώντας μία από τις μεθόδους HTMLDocument.Save(). Οι μέθοδοι επιτρέπουν την αποθήκευση HTML σε τοπικό αρχείο που καθορίζεται από διαδρομή, URL ή αποθήκευση εξόδου. Ανατρέξτε στην [τεκμηρίωση](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) για να μάθετε περισσότερα σχετικά με την αποθήκευση.

Save(String, MHTMLSaveOptions) Μέθοδος

Απαιτείται να καθοριστεί μια διαδρομή τοπικού συστήματος αρχείων για το αρχείο εξόδου κατά την αποθήκευση του εγγράφου. Ο κατασκευαστής MHTMLSaveOptions() αρχικοποιεί μια παρουσία της κλάσης [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) που διαθέτει την ιδιότητα ResourceHandlingOptions η οποία χρησιμοποιείται για τη διαμόρφωση του χειρισμού πόρων. Η μέθοδος Save(path, saveOptions) λαμβάνει μια διαδρομή τοπικού συστήματος αρχείων για το αρχείο εξόδου και μια παρουσία επιλογών αποθήκευσης ως παραμέτρους και αποθηκεύει το HTML ως έγγραφο MHTML στο τοπικό αρχείο που καθορίζεται από τη διαδρομή.

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Παραδείγματα

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtm");
	// Ορίστε την παρουσία κλάσης επιλογών
	var options = new MHTMLSaveOptions();
	document.Save(outputFilePath, options);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### Δείτε επίσης

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(Url, MHTMLSaveOptions) {#save_9}

Αποθηκεύει το έγγραφο σε ένα τοπικό αρχείο που καθορίζεται από το url. Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν σε έναν διπλανό φάκελο, του οποίου το όνομα θα κατασκευαστεί ως: output_file_name + \"_files\".

```java
public void Save(Url url, MHTMLSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Τοπική URL για το αρχείο εξόδου. |
| saveOptions | MHTMLSaveOptions | Η χρήση του αντικειμένου [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) σας επιτρέπει να ρυθμίσετε τη διαδικασία απόδοσης. Για περισσότερες πληροφορίες δείτε την [documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#save-options). |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εγείρεται εάν το καθορισμένο `url` δεν είναι έγκυρη τοπική URL αρχείου. |

## Παρατηρήσεις

Αποθήκευση HTML

Οι περισσότερες εργασίες που πρέπει να εκτελέσετε απαιτούν την αποθήκευση ενός εγγράφου. Μόλις φορτώσετε το υπάρχον αρχείο ή δημιουργήσετε ένα έγγραφο HTML από το μηδέν, μπορείτε να αποθηκεύσετε τις αλλαγές σας χρησιμοποιώντας μία από τις μεθόδους HTMLDocument.Save(). Οι μέθοδοι επιτρέπουν την αποθήκευση HTML σε τοπικό αρχείο που καθορίζεται από διαδρομή, URL ή αποθήκευση εξόδου. Ανατρέξτε στην [τεκμηρίωση](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/) για να μάθετε περισσότερα σχετικά με την αποθήκευση.

Save(Url, MHTMLSaveOptions) Μέθοδος

Απαιτείται να καθοριστεί μια πλήρης διαδρομή Url για την αποθήκευση του εγγράφου. Ο κατασκευαστής Url(url) δημιουργεί μια παρουσία της κλάσης [`Url`](../../url/) με το καθορισμένο url. Ο κατασκευαστής MHTMLSaveOptions() αρχικοποιεί μια παρουσία της κλάσης [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) που διαθέτει την ιδιότητα ResourceHandlingOptions η οποία χρησιμοποιείται για τη διαμόρφωση του χειρισμού πόρων. Η μέθοδος Save(url, saveOptions) λαμβάνει το url και τις επιλογές ως παραμέτρους και αποθηκεύει το HTML ως έγγραφο MHTML στο τοπικό αρχείο που καθορίζεται από το url.

Πηγαίος κώδικας

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Παραδείγματα

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLDivElement element = (HTMLDivElement) document.CreateElement("div");
	element.InnerHTML = "Hello from DIV element";
	document.Body.AppendChild(element);
         
	if (String.IsNullOrEmpty(outputHtmlPath))
	{
		throw new ArgumentException("Non valid path to output result");
	}

	var outputFilePath = Path.Combine(outputHtmlPath, "result.mhtm");
	// Ορίστε την παρουσία κλάσης επιλογών
	var options = new MHTMLSaveOptions();
	document.Save(new Url(outputFilePath), options);
}
```

*inputHtmlPath - user input file path.

*outputHtmlPath - user output folder path.

### Δείτε επίσης

* class [Url](../../url/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, MHTMLSaveOptions) {#save_4}

Αποθηκεύει το περιεχόμενο του εγγράφου και τους πόρους χρησιμοποιώντας το [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, MHTMLSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Ο διαχειριστής πόρων [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | MHTMLSaveOptions | Επιλογές αποθήκευσης MHTML. |

### Δείτε επίσης

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
