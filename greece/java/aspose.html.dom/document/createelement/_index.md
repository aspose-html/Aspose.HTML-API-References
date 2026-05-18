---
title: "Document.CreateElement"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Document. Σε ένα έγγραφο HTML, η μέθοδος document.createElement δημιουργεί το στοιχείο HTML που καθορίζεται από το tagName ή ένα HTMLUnknownElement εάν το tagName δεν αναγνωρίζεται"
type: docs

url: /el/java/com.aspose.html.dom/document/createelement/
---
## Document.CreateElement method

Σε ένα έγγραφο HTML, η μέθοδος document.createElement() δημιουργεί το στοιχείο HTML που καθορίζεται από το tagName, ή ένα [`HTMLUnknownElement`](../../../com.aspose.html/htmlunknownelement/) εάν το tagName δεν αναγνωρίζεται.

```java
public Element CreateElement(String localName)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| localName | String | Μια συμβολοσειρά που καθορίζει τον τύπο του στοιχείου που θα δημιουργηθεί. Το nodeName του δημιουργημένου στοιχείου αρχικοποιείται με την τιμή του tagName. Μην χρησιμοποιείτε προσδιορισμένα ονόματα (π.χ. "html:a") με αυτή τη μέθοδο. Όταν κληθεί σε ένα έγγραφο HTML, η createElement() μετατρέπει το tagName σε πεζά πριν δημιουργήσει το στοιχείο. |

### Τιμή επιστροφής

Το νέο [`Element`](../../element/).

## Παραδείγματα

```java
var element = document.CreateElement(tagName);
```

### Δείτε επίσης

* class [Element](../../element/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
