---
title: Document.CreateNSResolver
second_title: Aspose.HTML για Αναφορά API .NET
description: Document μέθοδος. Προσαρμόζει οποιονδήποτε κόμβο DOM για την επίλυση χώρων ονομάτων έτσι ώστε μια έκφραση XPath να μπορεί εύκολα να αξιολογηθεί σε σχέση με το περιβάλλον του κόμβου όπου εμφανίστηκε στο έγγραφο. Αυτός ο προσαρμογέας λειτουργεί όπως η μέθοδος DOM Level 3lookupNamespaceURI σε κόμβους για την επίλυση του namespaceURI από ένα δεδομένο πρόθεμα χρησιμοποιώντας τις τρέχουσες πληροφορίες που είναι διαθέσιμες στην ιεραρχία του κόμβου στο time lookupNamespaceURI καλείται επιλύοντας επίσης σωστά το σιωπηρό πρόθεμα xml.
type: docs
weight: 910
url: /el/net/aspose.html.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

Προσαρμόζει οποιονδήποτε κόμβο DOM για την επίλυση χώρων ονομάτων, έτσι ώστε μια έκφραση XPath να μπορεί εύκολα να αξιολογηθεί σε σχέση με το περιβάλλον του κόμβου όπου εμφανίστηκε στο έγγραφο. Αυτός ο προσαρμογέας λειτουργεί όπως η μέθοδος DOM Level 3`lookupNamespaceURI` σε κόμβους για την επίλυση του namespaceURI από ένα δεδομένο πρόθεμα χρησιμοποιώντας τις τρέχουσες πληροφορίες που είναι διαθέσιμες στην ιεραρχία του κόμβου στο time lookupNamespaceURI καλείται, επιλύοντας επίσης σωστά το σιωπηρό πρόθεμα xml.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| nodeResolver | Node | Ο κόμβος που θα χρησιμοποιηθεί ως πλαίσιο για την ανάλυση χώρου ονομάτων. |

### Επιστρεφόμενη Αξία

[`IXPathNSResolver`](../../../aspose.html.dom.xpath/ixpathnsresolver/) το οποίο επιλύει τους χώρους ονομάτων σε σχέση με τους ορισμούς του πεδίου για έναν καθορισμένο κόμβο.

### Δείτε επίσης

* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* χώρος ονομάτων [Aspose.Html.Dom](../../document/)
* συνέλευση [Aspose.HTML](../../../)


