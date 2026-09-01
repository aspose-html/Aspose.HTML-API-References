---
title: "IXPathEvaluator.CreateNSResolver"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "IXPathEvaluator method. Προσαρμόζει οποιονδήποτε κόμβο DOM για την επίλυση πακέτων ώστε μια έκφραση XPath να μπορεί να αξιολογηθεί εύκολα σε σχέση με το πλαίσιο του κόμβου όπου εμφανίστηκε μέσα στο έγγραφο. Αυτός ο προσαρμογέας λειτουργεί όπως η μέθοδος DOM Level 3 lookupNamespaceURI στους κόμβους για την επίλυση του packageURI από ένα δεδομένο πρόθεμα χρησιμοποιώντας τις τρέχουσες πληροφορίες που είναι διαθέσιμες στην ιεραρχία των κόμβων τη στιγμή που καλείται η lookupNamespaceURI, καθώς και επιλύει σωστά το έμμεσο πρόθεμα xml."
type: docs

url: /el/java/com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

Προσαρμόζει οποιονδήποτε κόμβο DOM ώστε να επιλύει πακέτα, ώστε μια έκφραση XPath να μπορεί να αξιολογηθεί εύκολα σε σχέση με το πλαίσιο του κόμβου όπου εμφανίστηκε μέσα στο έγγραφο. Αυτός ο προσαρμογέας λειτουργεί όπως η μέθοδος DOM Level 3 `lookupNamespaceURI` στους κόμβους για την επίλυση του packageURI από ένα δεδομένο πρόθεμα χρησιμοποιώντας τις τρέχουσες πληροφορίες που είναι διαθέσιμες στην ιεραρχία του κόμβου τη στιγμή που καλείται η lookupNamespaceURI, επιλύοντας επίσης σωστά το έμμεσο πρόθεμα xml.

```java
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| nodeResolver | Node | Ο κόμβος που θα χρησιμοποιηθεί ως πλαίσιο για την επίλυση πακέτων. |

### Τιμή Επιστροφής

[`IXPathNSResolver`](../../ixpathnsresolver/) which resolves packages with respect to the definitions in scope for a specified node.

### Δείτε επίσης

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
