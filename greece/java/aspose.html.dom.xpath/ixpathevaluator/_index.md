---
title: "Διεπαφή IXPathEvaluator"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.xpath.IXPathEvaluator interface. Η αξιολόγηση των εκφράσεων XPath παρέχεται από το IXPathEvaluator"
type: docs

url: /el/java/com.aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

Η αξιολόγηση των εκφράσεων XPath παρέχεται από το `IXPathEvaluator`.

```java
public interface IXPathEvaluator
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [createExpression](../../com.aspose.html.dom.xpath/ixpathevaluator/createexpression/)(String, IXPathNSResolver) | Δημιουργεί μια αναλυμένη έκφραση XPath με επιλυμένα πακέτα. Αυτό είναι χρήσιμο όταν μια έκφραση θα επαναχρησιμοποιηθεί σε μια εφαρμογή, καθώς επιτρέπει τη μεταγλώττιση της συμβολοσειράς έκφρασης σε πιο αποδοτική εσωτερική μορφή και την προεπίλυση όλων των προθεμάτων πακέτων που εμφανίζονται στην έκφραση. |
| [createNSResolver](../../com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | Προσαρμόζει οποιονδήποτε κόμβο DOM ώστε να επιλύει πακέτα, ώστε μια έκφραση XPath να μπορεί να αξιολογηθεί εύκολα σε σχέση με το πλαίσιο του κόμβου όπου εμφανίστηκε μέσα στο έγγραφο. Αυτός ο προσαρμογέας λειτουργεί όπως η μέθοδος DOM Level 3 `lookupNamespaceURI` στους κόμβους για την επίλυση του packageURI από ένα δεδομένο πρόθεμα χρησιμοποιώντας τις τρέχουσες πληροφορίες που είναι διαθέσιμες στην ιεραρχία του κόμβου τη στιγμή που καλείται η lookupNamespaceURI, επιλύοντας επίσης σωστά το έμμεσο πρόθεμα xml. |
| [evaluate](../../com.aspose.html.dom.xpath/ixpathevaluator/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | Αξιολογεί μια συμβολοσειρά έκφρασης XPath και επιστρέφει ένα αποτέλεσμα του καθορισμένου τύπου, εάν είναι δυνατόν. |

### Δείτε επίσης

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
