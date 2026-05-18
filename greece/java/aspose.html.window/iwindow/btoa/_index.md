---
title: "IWindow.Btoa"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος IWindow. Λαμβάνει τα δεδομένα εισόδου με τη μορφή μιας Unicode String που περιέχει μόνο χαρακτήρες στο εύρος U0000 έως U00FF, ο καθένας αντιπροσωπεύει ένα δυαδικό byte με τιμές 0x00 έως 0xFF αντίστοιχα, και τα μετατρέπει στην αναπαράσταση base64 της, την οποία επιστρέφει."
type: docs

url: /el/java/com.aspose.html.window/iwindow/btoa/
---
## IWindow.Btoa method

Δέχεται τα δεδομένα εισόδου, με τη μορφή Unicode String που περιέχει μόνο χαρακτήρες στο εύρος U+0000 έως U+00FF, ο καθένας αντιπροσωπεύει ένα δυαδικό byte με τιμές 0x00 έως 0xFF αντίστοιχα, και τα μετατρέπει στην αναπαράστασή τους σε base64, την οποία επιστρέφει.

```java
public String Btoa(String data)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| δεδομένα | String | Η Unicode String που περιέχει μόνο χαρακτήρες στο εύρος U+0000 έως U+00FF. |

### Τιμή επιστροφής

Η base64 String.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Ρίχνει μια εξαίρεση "InvalidCharacterError" DOMException εάν η είσοδος String περιέχει χαρακτήρες εκτός του επιτρεπτού εύρους. |

### Δείτε επίσης

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
