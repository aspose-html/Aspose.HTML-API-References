---
title: "Document.CreateExpression"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Document. Δημιουργεί μια αναλυμένη έκφραση XPath με επιλυμένα πακέτα. Αυτό είναι χρήσιμο όταν μια έκφραση θα επαναχρησιμοποιηθεί σε μια εφαρμογή, καθώς καθιστά δυνατό το μεταγλωττισμό της συμβολοσειράς έκφρασης σε πιο αποδοτική εσωτερική μορφή και προεπιλύει όλα τα προθέματα πακέτων που εμφανίζονται στην έκφραση."
type: docs

url: /el/java/com.aspose.html.dom/document/createexpression/
---
## Document.CreateExpression method

Δημιουργεί μια αναλυμένη έκφραση XPath με επιλυμένα πακέτα. Αυτό είναι χρήσιμο όταν μια έκφραση θα επαναχρησιμοποιηθεί σε μια εφαρμογή, καθώς καθιστά δυνατή τη μεταγλώττιση της String της έκφρασης σε πιο αποδοτική εσωτερική μορφή και την προεπίλυση όλων των προθεμάτων πακέτων που εμφανίζονται στην έκφραση.

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| έκφραση | String | Η συμβολοσειρά έκφρασης XPath που θα αναλυθεί. |
| resolver | IXPathNSResolver | Ο `resolver` επιτρέπει τη μετάφραση όλων των προθεμάτων, συμπεριλαμβανομένου του προθέματος πακέτου `xml`, μέσα στην έκφραση XPath σε κατάλληλα URIs πακέτων. Εάν αυτό οριστεί ως `null`, οποιοδήποτε πρόθεμα πακέτου στην έκφραση θα προκαλέσει την εξαίρεση [`DOMException`](../../domexception/) με τον κωδικό `NAMESPACE_ERR`. |

### Τιμή επιστροφής

Η μεταγλωττισμένη μορφή της έκφρασης XPath.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../domexception/) | INVALID_EXPRESSION_ERR: Εμφανίζεται εάν η έκφραση δεν είναι νόμιμη σύμφωνα με τους κανόνες του [`IXPathEvaluator`](../../../com.aspose.html.dom.xpath/ixpathevaluator/). |
| [dOMException](../../domexception/) | NAMESPACE_ERR: Εμφανίζεται εάν η έκφραση περιέχει προθέματα πακέτων που δεν μπορούν να επιλυθούν από τον καθορισμένο [`IXPathNSResolver`](../../../com.aspose.html.dom.xpath/ixpathnsresolver/). |

### Δείτε επίσης

* interface [IXPathExpression](../../../com.aspose.html.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
