---
title: "Resource.Save"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Resource. Αποθηκεύει τον πόρο στο παρεχόμενο ρεύμα"
type: docs

url: /el/java/com.aspose.html.saving/resource/save/
---
## Resource.Save method

Αποθηκεύει τον πόρο στη δοθείσα ροή.

```java
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Το ρεύμα στο οποίο θα αποθηκευτεί ο πόρος. |
| πλαίσιο | ResourceHandlingContext | Πλαίσιο διαχείρισης πόρων. |

### Τιμή επιστροφής

Αυτός ο πόρος ώστε να μπορείτε να αλυσίδετε κλήσεις.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Εγείρεται εάν το [`OutputUrl`](../outputurl/) είναι `null`. Το [`OutputUrl`](../outputurl/) πρέπει να καθοριστεί πριν από την αποθήκευση του πόρου, διότι διαφορετικά είναι αδύνατο να καθοριστεί η σωστή αναφορά στους πόρους που αναφέρονται σε αυτόν. |

### Δείτε επίσης

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
