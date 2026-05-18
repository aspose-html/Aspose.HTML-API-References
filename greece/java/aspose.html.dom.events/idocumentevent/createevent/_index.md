---
title: "IDocumentEvent.CreateEvent"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "IDocumentEvent method. Η μέθοδος createEvent χρησιμοποιείται για τη δημιουργία Events όταν είναι είτε άβολη είτε περιττή η δημιουργία ενός Event από τον χρήστη."
type: docs

url: /el/java/com.aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

Η μέθοδος createEvent χρησιμοποιείται για τη δημιουργία Events όταν είναι είτε άβολη είτε περιττή η δημιουργία Event από τον χρήστη.

```java
public Event CreateEvent(String eventType)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| eventType | String | Η παράμετρος eventType καθορίζει τον τύπο της διεπαφής που θα δημιουργηθεί. Εάν η καθορισμένη διεπαφή υποστηρίζεται από την υλοποίηση, αυτή η μέθοδος θα επιστρέψει ένα νέο αντικείμενο του ζητούμενου τύπου διεπαφής. Εάν το is θα αποσταλεί μέσω της μεθόδου, η κατάλληλη μέθοδος πρέπει να κληθεί μετά τη δημιουργία για την αρχικοποίηση των τιμών. Η μέθοδος χρησιμοποιείται για τη δημιουργία s όταν είναι είτε άβολη είτε περιττή η δημιουργία τους από τον χρήστη. Σε περιπτώσεις όπου η παρεχόμενη υλοποίηση είναι ανεπαρκής, οι χρήστες μπορούν να παρέχουν τις δικές τους υλοποιήσεις για χρήση με τη μέθοδο. |

### Τιμή επιστροφής

Επιστρέφει το νεοδημιουργημένο συμβάν του καθορισμένου τύπου συμβάντος.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Εγείρεται εάν η υλοποίηση δεν υποστηρίζει τον τύπο της ζητούμενης διεπαφής. |

### Δείτε επίσης

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
