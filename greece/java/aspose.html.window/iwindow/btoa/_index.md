---
title: "IWindow.Btoa"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος IWindow. Λαμβάνει τα δεδομένα εισόδου με τη μορφή μιας Unicode String που περιέχει μόνο χαρακτήρες στην περιοχή U0000 έως U00FF, ο καθένας αντιπροσωπεύει ένα δυαδικό byte με τιμές 0x00 έως 0xFF αντίστοιχα, και τα μετατρέπει στην αναπαράσταση base64 που επιστρέφει."
type: docs

url: /el/java/com.aspose.html.window/iwindow/btoa/
---
## IWindow.Btoa method

Δέχεται τα δεδομένα εισόδου, με τη μορφή μιας Unicode String που περιέχει μόνο χαρακτήρες στο εύρος U+0000 έως U+00FF, ο καθένας από τους οποίους αντιπροσωπεύει ένα δυαδικό byte με τιμές 0x00 έως 0xFF αντίστοιχα, και τα μετατρέπει στην αναπαράστασή τους σε base64, την οποία επιστρέφει.

```java
public String Btoa(String data)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δεδομένα | String | Η Unicode String που περιέχει μόνο χαρακτήρες στην περιοχή U+0000 έως U+00FF. |

### Τιμή Επιστροφής

Η base64 String.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Εκρίει μια εξαίρεση "InvalidCharacterError" DOMException εάν η String εισόδου περιέχει χαρακτήρες εκτός της περιοχής. |

### Δείτε επίσης

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
