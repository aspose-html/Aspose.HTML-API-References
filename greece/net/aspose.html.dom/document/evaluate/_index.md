---
title: Document.Evaluate
second_title: Aspose.HTML για Αναφορά API .NET
description: Document μέθοδος. Αξιολογεί μια συμβολοσειρά έκφρασης XPath και επιστρέφει ένα αποτέλεσμα του καθορισμένου τύπου εάν είναι δυνατόν.
type: docs
weight: 950
url: /el/net/aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

Αξιολογεί μια συμβολοσειρά έκφρασης XPath και επιστρέφει ένα αποτέλεσμα του καθορισμένου τύπου εάν είναι δυνατόν.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| expression | String | Η συμβολοσειρά έκφρασης XPath προς ανάλυση και αξιολόγηση. |
| contextNode | Node | Το πλαίσιο είναι ο κόμβος περιβάλλοντος για την αξιολόγηση αυτής της έκφρασης XPath. |
| resolver | IXPathNSResolver | Ο αναλυτής επιτρέπει τη μετάφραση όλων των προθεμάτων, συμπεριλαμβανομένου του προθέματος χώρου ονομάτων xml , εντός της έκφρασης XPath σε κατάλληλα URI χώρου ονομάτων. |
| type | XPathResultType | Εάν έχει καθοριστεί ένας συγκεκριμένος τύπος, τότε το αποτέλεσμα θα επιστραφεί ως ο αντίστοιχος τύπος. |
| result | Object | Το αποτέλεσμα καθορίζει ένα συγκεκριμένο αντικείμενο αποτελέσματος το οποίο μπορεί να επαναχρησιμοποιηθεί και να επιστραφεί με αυτήν τη μέθοδο. |

### Επιστρεφόμενη Αξία

Το αποτέλεσμα της αξιολόγησης της έκφρασης XPath.

### Δείτε επίσης

* interface [IXPathResult](../../../aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* χώρος ονομάτων [Aspose.Html.Dom](../../document/)
* συνέλευση [Aspose.HTML](../../../)


