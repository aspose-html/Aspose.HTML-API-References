---
title: "Document.CreateDocumentType"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Document. Η μέθοδος επιστρέφει ένα αντικείμενο DocumentType, το οποίο μπορεί είτε να χρησιμοποιηθεί με DOMImplementation.createDocument κατά τη δημιουργία του εγγράφου είτε να τοποθετηθεί στο έγγραφο μέσω μεθόδων όπως Node.insertBefore ή Node.replaceChild."
type: docs

url: /el/java/com.aspose.html.dom/document/createdocumenttype/
---
## Document.CreateDocumentType method

Η μέθοδος επιστρέφει ένα [`DocumentType`](../../documenttype/) αντικείμενο, το οποίο μπορεί είτε να χρησιμοποιηθεί με DOMImplementation.createDocument κατά τη δημιουργία του εγγράφου είτε να τοποθετηθεί στο έγγραφο μέσω μεθόδων όπως Node.insertBefore() ή Node.replaceChild().

```java
public DocumentType CreateDocumentType(String name, String publicId, String systemId, 
    String internalSubset)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | String | Είναι ένα DOMString που περιέχει το πλήρες όνομα, όπως svg:svg. |
| publicId | String | Είναι ένα DOMString που περιέχει το αναγνωριστικό PUBLIC. |
| systemId | String | Είναι ένα DOMString που περιέχει τα αναγνωριστικά SYSTEM. |
| internalSubset | String | Το εσωτερικό υποσύνολο. |

### Τιμή Επιστροφής

Το [`DocumentType`](../../documenttype/).

## Παραδείγματα

```java
var dt = document.CreateDocumentType("svg:svg", "-//W3C//DTD SVG 1.1//EN", "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd", "");
```

### Δείτε επίσης

* class [DocumentType](../../documenttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
