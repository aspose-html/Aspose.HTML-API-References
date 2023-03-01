---
title: Document.CreateExpression
second_title: Aspose.HTML για Αναφορά API .NET
description: Document μέθοδος. Δημιουργεί μια αναλυμένη έκφραση XPath με επιλυμένους χώρους ονομάτων. Αυτό είναι χρήσιμο όταν μια έκφραση θα επαναχρησιμοποιηθεί σε μια εφαρμογή καθώς καθιστά δυνατή την να μεταγλωττίσει τη συμβολοσειρά έκφρασης σε μια πιο αποτελεσματική εσωτερική μορφή και να επιλύσει εκ των προτέρων όλα τα προθέματα χώρου ονομάτων που εμφανίζονται μέσα στην έκφραση.
type: docs
weight: 890
url: /el/net/aspose.html.dom/document/createexpression/
---
## Document.CreateExpression method

Δημιουργεί μια αναλυμένη έκφραση XPath με επιλυμένους χώρους ονομάτων. Αυτό είναι χρήσιμο όταν μια έκφραση θα επαναχρησιμοποιηθεί σε μια εφαρμογή, καθώς καθιστά δυνατή την να μεταγλωττίσει τη συμβολοσειρά έκφρασης σε μια πιο αποτελεσματική εσωτερική μορφή και να επιλύσει εκ των προτέρων όλα τα προθέματα χώρου ονομάτων που εμφανίζονται μέσα στην έκφραση.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| expression | String | Η συμβολοσειρά έκφρασης XPath προς ανάλυση. |
| resolver | IXPathNSResolver | ο`διαλύων` επιτρέπει τη μετάφραση όλων των προθεμάτων, συμπεριλαμβανομένου του`xml` πρόθεμα namespace, εντός της έκφρασης XPath σε κατάλληλα URI χώρου ονομάτων . Εάν αυτό προσδιορίζεται ως`μηδενικό` , οποιοδήποτε πρόθεμα χώρου ονομάτων εντός της έκφρασης θα έχει ως αποτέλεσμα[`DOMException`](../../domexception/) όντας ρίχνονται με τον κωδικό`NAMESPACE_ERR`. |

### Επιστρεφόμενη Αξία

Η μεταγλωττισμένη μορφή της έκφρασης XPath.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../domexception/) | INVALID_EXPRESSION_ERR: Έγινε αν η έκφραση δεν είναι νόμιμη σύμφωνα με τους κανόνες του[`IXPathEvaluator`](../../../aspose.html.dom.xpath/ixpathevaluator/). |
| [DOMException](../../domexception/) | NAMESPACE_ERR: Αυξάνεται εάν η έκφραση περιέχει προθέματα namespace τα οποία δεν μπορούν να επιλυθούν από το καθορισμένο[`IXPathNSResolver`](../../../aspose.html.dom.xpath/ixpathnsresolver/). |

### Δείτε επίσης

* interface [IXPathExpression](../../../aspose.html.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* χώρος ονομάτων [Aspose.Html.Dom](../../document/)
* συνέλευση [Aspose.HTML](../../../)


