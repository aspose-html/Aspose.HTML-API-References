---
title: "Document.CreateNSResolver"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Document. Προσαρμόζει οποιονδήποτε κόμβο DOM για την επίλυση πακέτων ώστε μια έκφραση XPath να μπορεί να αξιολογηθεί εύκολα σε σχέση με το πλαίσιο του κόμβου όπου εμφανίστηκε μέσα στο έγγραφο. Αυτός ο προσαρμογέας λειτουργεί όπως η μέθοδος DOM Level 3 lookupNamespaceURI στους κόμβους για την επίλυση του packageURI από ένα δεδομένο πρόθεμα, χρησιμοποιώντας τις τρέχουσες πληροφορίες που είναι διαθέσιμες στην ιεραρχία των κόμβων τη στιγμή που καλείται η lookupNamespaceURI, καθώς και επιλύει σωστά το έμμεσο πρόθεμα xml."
type: docs

url: /el/java/com.aspose.html.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

Προσαρμόζει οποιονδήποτε κόμβο DOM για την επίλυση πακέτων ώστε μια έκφραση XPath να μπορεί να αξιολογηθεί εύκολα σε σχέση με το πλαίσιο του κόμβου όπου εμφανίστηκε μέσα στο έγγραφο. Αυτός ο προσαρμογέας λειτουργεί όπως η μέθοδος DOM Level 3 `lookupNamespaceURI` στους κόμβους για την επίλυση του packageURI από ένα δεδομένο πρόθεμα χρησιμοποιώντας τις τρέχουσες πληροφορίες που είναι διαθέσιμες στην ιεραρχία του κόμβου τη στιγμή που καλείται η lookupNamespaceURI, επίσης επιλύοντας σωστά το ρητό πρόθεμα xml.

```java
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| nodeResolver | Node | Ο κόμβος που θα χρησιμοποιηθεί ως πλαίσιο για την επίλυση πακέτων. |

### Τιμή επιστροφής

[`IXPathNSResolver`](../../../com.aspose.html.dom.xpath/ixpathnsresolver/) which resolves packages with respect to the definitions in scope for a specified node.

### Δείτε επίσης

* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
