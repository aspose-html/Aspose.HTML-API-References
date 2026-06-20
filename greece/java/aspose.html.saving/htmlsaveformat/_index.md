---
title: "Απαρίθμηση HTMLSaveFormat"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Απαρίθμηση com.aspose.html.saving.HTMLSaveFormat. Καθορίζει τη μορφή στην οποία αποθηκεύεται το έγγραφο. Μπορείτε να βρείτε περισσότερες πληροφορίες για την αποθήκευση του HTMLDocument στο άρθρο"
type: docs

url: /el/java/com.aspose.html.saving/htmlsaveformat/
---
## HTMLSaveFormat enumeration

Καθορίζει τη μορφή στην οποία αποθηκεύεται το έγγραφο. Μπορείτε να βρείτε περισσότερες πληροφορίες για την αποθήκευση του [`HTMLDocument`](../../com.aspose.html/htmldocument/) στο [άρθρο](https://docs.aspose.com/html/net/working-with-documents/saving-a-document/).

```java
public enum HTMLSaveFormat
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Original | `0` | Το έγγραφο θα αποθηκευτεί στην αρχική του μορφή. |
| Markdown | `1` | Το έγγραφο θα αποθηκευτεί ως Markdown. |
| MHTML | `2` | Το έγγραφο θα αποθηκευτεί ως MHTML. |

## Παρατηρήσεις

Μπορείτε να κατεβάσετε τα πλήρη παραδείγματα και τα αρχεία δεδομένων από το [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Παραδείγματα

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.saving;
...
  // Προετοιμάστε μια διαδρομή εξόδου για την αποθήκευση του εγγράφου
  String documentPath = Path.Combine(OutputDir, "save-to-MD.md");

  // Προετοιμάστε κώδικα HTML
  var html_code = "<H2>Hello World!</H2>";
   
  // Αρχικοποιήστε ένα έγγραφο από τη μεταβλητή String
  using (var document = new HTMLDocument(html_code, "."))
  {
    // Αποθηκεύστε το έγγραφο ως αρχείο Markdown
    document.Save(documentPath, HTMLSaveFormat.Markdown);
  }
```

*OutputDir - user output folder path.

### Δείτε επίσης

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
