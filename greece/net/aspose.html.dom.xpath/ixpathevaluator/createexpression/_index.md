---
title: IXPathEvaluator.CreateExpression
second_title: Aspose.HTML για Αναφορά API .NET
description: IXPathEvaluator μέθοδος. Δημιουργεί μια αναλυμένη έκφραση XPath με επιλυμένους χώρους ονομάτων. Αυτό είναι χρήσιμο όταν μια έκφραση θα επαναχρησιμοποιηθεί σε μια εφαρμογή καθώς καθιστά δυνατή την να μεταγλωττίσει τη συμβολοσειρά έκφρασης σε μια πιο αποτελεσματική εσωτερική μορφή και να επιλύσει εκ των προτέρων όλα τα προθέματα χώρου ονομάτων που εμφανίζονται μέσα στην έκφραση.
type: docs
weight: 10
url: /el/net/aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Δημιουργεί μια αναλυμένη έκφραση XPath με επιλυμένους χώρους ονομάτων. Αυτό είναι χρήσιμο όταν μια έκφραση θα επαναχρησιμοποιηθεί σε μια εφαρμογή, καθώς καθιστά δυνατή την να μεταγλωττίσει τη συμβολοσειρά έκφρασης σε μια πιο αποτελεσματική εσωτερική μορφή και να επιλύσει εκ των προτέρων όλα τα προθέματα χώρου ονομάτων που εμφανίζονται μέσα στην έκφραση.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| expression | String | Η συμβολοσειρά έκφρασης XPath προς ανάλυση. |
| resolver | IXPathNSResolver | ο`διαλύων` επιτρέπει τη μετάφραση όλων των προθεμάτων, συμπεριλαμβανομένου του`xml` πρόθεμα namespace, εντός της έκφρασης XPath σε κατάλληλα URI χώρου ονομάτων . Εάν αυτό προσδιορίζεται ως`μηδενικό` , οποιοδήποτε πρόθεμα χώρου ονομάτων εντός της έκφρασης θα έχει ως αποτέλεσμα[`DOMException`](../../../aspose.html.dom/domexception/) όντας ρίχνονται με τον κωδικό`NAMESPACE_ERR`. |

### Επιστρεφόμενη Αξία

Η μεταγλωττισμένη μορφή της έκφρασης XPath.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Έγινε αν η έκφραση δεν είναι νόμιμη σύμφωνα με τους κανόνες του[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NAMESPACE_ERR: Αυξάνεται εάν η έκφραση περιέχει προθέματα namespace τα οποία δεν μπορούν να επιλυθούν από το καθορισμένο[`IXPathNSResolver`](../../ixpathnsresolver/). |

### Δείτε επίσης

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* χώρος ονομάτων [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* συνέλευση [Aspose.HTML](../../../)


