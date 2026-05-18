---
title: "IXPathEvaluator.CreateExpression"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος IXPathEvaluator. Δημιουργεί μια αναλυμένη έκφραση XPath με επιλυμένα πακέτα. Αυτό είναι χρήσιμο όταν μια έκφραση θα επαναχρησιμοποιηθεί σε μια εφαρμογή, καθώς καθιστά δυνατό το μεταγλωττισμό της έκφρασης String σε πιο αποδοτική εσωτερική μορφή και την προεπίλυση όλων των προθεμάτων πακέτων που εμφανίζονται στην έκφραση."
type: docs

url: /el/java/com.aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Δημιουργεί μια αναλυμένη έκφραση XPath με επιλυμένα πακέτα. Αυτό είναι χρήσιμο όταν μια έκφραση θα επαναχρησιμοποιηθεί σε μια εφαρμογή, καθώς καθιστά δυνατή τη μεταγλώττιση της String της έκφρασης σε πιο αποδοτική εσωτερική μορφή και την προεπίλυση όλων των προθεμάτων πακέτων που εμφανίζονται στην έκφραση.

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| έκφραση | String | Η συμβολοσειρά έκφρασης XPath που θα αναλυθεί. |
| resolver | IXPathNSResolver | Ο `resolver` επιτρέπει τη μετάφραση όλων των προθεμάτων, συμπεριλαμβανομένου του προθέματος πακέτου `xml`, μέσα στην έκφραση XPath σε κατάλληλα URI πακέτων. Εάν αυτό οριστεί ως `null`, οποιοδήποτε πρόθεμα πακέτου μέσα στην έκφραση θα προκαλέσει την εξαίρεση [`DOMException`](../../../com.aspose.html.dom/domexception/) με κωδικό `NAMESPACE_ERR`. |

### Τιμή επιστροφής

Η μεταγλωττισμένη μορφή της έκφρασης XPath.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Εμφανίζεται εάν η έκφραση δεν είναι έγκυρη σύμφωνα με τους κανόνες του [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: Εμφανίζεται εάν η έκφραση περιέχει προθέματα πακέτου που δεν μπορούν να επιλυθούν από τον καθορισμένο [`IXPathNSResolver`](../../ixpathnsresolver/). |

### Δείτε επίσης

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
