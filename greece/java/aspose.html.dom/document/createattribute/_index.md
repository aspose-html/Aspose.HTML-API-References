---
title: "Document.CreateAttribute"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Document. Η μέθοδος Document.createAttribute δημιουργεί έναν νέο κόμβο χαρακτηριστικού και τον επιστρέφει. Το αντικείμενο δημιουργεί έναν κόμβο που υλοποιεί τη διεπαφή Attr. Το DOM δεν επιβάλλει ποιοι τύποι χαρακτηριστικών μπορούν να προστεθούν σε ένα συγκεκριμένο στοιχείο με αυτόν τον τρόπο."
type: docs

url: /el/java/com.aspose.html.dom/document/createattribute/
---
## Document.CreateAttribute method

Η μέθοδος Document.createAttribute() δημιουργεί έναν νέο κόμβο χαρακτηριστικού και τον επιστρέφει. Το αντικείμενο δημιουργεί έναν κόμβο που υλοποιεί τη διεπαφή [`Attr`](../../attr/). Το DOM δεν επιβάλλει ποιοι τύποι χαρακτηριστικών μπορούν να προστεθούν σε ένα συγκεκριμένο στοιχείο με αυτόν τον τρόπο.

```java
public Attr CreateAttribute(String localName)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| localName | String | Το name είναι μια String που περιέχει το όνομα του χαρακτηριστικού. |

### Τιμή επιστροφής

Ένας κόμβος [`Attr`](../../attr/).

## Παραδείγματα

```java
var element = document.GetElementById("div");
var attr = document.CreateAttribute("my_attr");
attr.Value = "my_value";
element.SetAttributeNode(attr);
```

### Δείτε επίσης

* class [Attr](../../attr/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
