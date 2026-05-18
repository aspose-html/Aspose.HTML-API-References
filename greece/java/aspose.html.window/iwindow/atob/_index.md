---
title: "IWindow.Atob"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος IWindow. Λαμβάνει τα δεδομένα εισόδου με τη μορφή μιας Unicode String που περιέχει κωδικοποιημένα σε base64 δυαδικά δεδομένα, τα αποκωδικοποιεί και επιστρέφει μια String που αποτελείται από χαρακτήρες στο εύρος U0000 έως U00FF, ο καθένας αντιπροσωπεύει ένα δυαδικό byte με τιμές 0x00 έως 0xFF αντίστοιχα, που αντιστοιχούν σε αυτά τα δυαδικά δεδομένα."
type: docs

url: /el/java/com.aspose.html.window/iwindow/atob/
---
## IWindow.Atob method

Δέχεται τα δεδομένα εισόδου, με τη μορφή Unicode String που περιέχει δυαδικά δεδομένα κωδικοποιημένα σε base64, τα αποκωδικοποιεί και επιστρέφει ένα String που αποτελείται από χαρακτήρες στο εύρος U+0000 έως U+00FF, ο καθένας αντιπροσωπεύει ένα δυαδικό byte με τιμές 0x00 έως 0xFF αντίστοιχα, που αντιστοιχούν σε αυτά τα δυαδικά δεδομένα.

```java
public String Atob(String data)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| δεδομένα | String | Η Unicode String που περιέχει κωδικοποιημένα σε base64 δυαδικά δεδομένα |

### Τιμή επιστροφής

Η String που αποτελείται από χαρακτήρες στο εύρος U+0000 έως U+00FF

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Ρίχνει μια εξαίρεση "InvalidCharacterError" DOMException εάν η είσοδος String δεν είναι έγκυρα δεδομένα base64. |

### Δείτε επίσης

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
