---
title: "Resource.Save"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Resource. Αποθηκεύει τον πόρο στη δοθείσα ροή."
type: docs

url: /el/java/com.aspose.html.saving/resource/save/
---
## Resource.Save method

Αποθηκεύει τον πόρο στη δοθείσα ροή.

```java
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Η ροή στην οποία θα αποθηκευτεί ο πόρος. |
| πλαίσιο | ResourceHandlingContext | Πλαίσιο διαχείρισης πόρων. |

### Τιμή Επιστροφής

Αυτός ο πόρος ώστε να μπορείτε να αλυσίδετε κλήσεις.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| InvalidOperationException | Εγείρεται εάν το [`OutputUrl`](../outputurl/) είναι `null`. Το [`OutputUrl`](../outputurl/) πρέπει να καθοριστεί πριν από την αποθήκευση του πόρου, επειδή διαφορετικά είναι αδύνατο να καθοριστεί η σωστή αναφορά στους πόρους που αναφέρονται σε αυτόν. |

### Δείτε επίσης

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
