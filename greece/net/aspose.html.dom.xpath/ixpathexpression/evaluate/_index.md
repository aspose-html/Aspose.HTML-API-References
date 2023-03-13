---
title: IXPathExpression.Evaluate
second_title: Aspose.HTML για Αναφορά API .NET
description: IXPathExpression μέθοδος. Αξιολογεί αυτήν την έκφραση XPath και επιστρέφει ένα αποτέλεσμα.
type: docs
weight: 10
url: /el/net/aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

Αξιολογεί αυτήν την έκφραση XPath και επιστρέφει ένα αποτέλεσμα.

```csharp
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| contextNode | Node | ο`συμφραζόμενα` είναι ο κόμβος περιβάλλοντος για την αξιολόγηση αυτής της έκφρασης XPath. Αν το[`IXPathEvaluator`](../../ixpathevaluator/) αποκτήθηκε με χύτευση του[`Document`](../../../aspose.html.dom/document/) τότε αυτό πρέπει να είναι που ανήκει στο ίδιο έγγραφο και πρέπει να είναι α[`Document`](../../../aspose.html.dom/document/) ,[`Element`](../../../aspose.html.dom/element/) ,[`Attr`](../../../aspose.html.dom/attr/) , [`Text`](../../../aspose.html.dom/text/) ,[`CDATASection`](../../../aspose.html.dom/cdatasection/) ,[`Comment`](../../../aspose.html.dom/comment/) ,[`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction/) , ήXPathNamespace κόμβος. Εάν ο κόμβος περιβάλλοντος είναι α[`Text`](../../../aspose.html.dom/text/) ή α[`CDATASection`](../../../aspose.html.dom/cdatasection/), τότε το περιβάλλον ερμηνεύεται ως ολόκληρος ο κόμβος λογικού κειμένου όπως φαίνεται από το XPath, εκτός εάν ο κόμβος είναι κενός οπότε μπορεί να μην χρησιμεύει ως περιβάλλον XPath. |
| type | XPathResultType | Εάν ένα συγκεκριμένο`τύπος` καθορίζεται, τότε το αποτέλεσμα θα εξαναγκαστεί να επιστρέψει τον καθορισμένο τύπο που βασίζεται στις μετατροπές XPath και θα αποτύχει εάν ο επιθυμητός εξαναγκασμός δεν είναι δυνατός. Αυτό πρέπει να είναι μία από τις τιμές του[`XPathResultType`](../../xpathresulttype/). |
| result | Object | ο`αποτέλεσμα` καθορίζει ένα συγκεκριμένο αντικείμενο αποτελέσματος το οποίο μπορεί να επαναχρησιμοποιηθεί και να επιστραφεί με αυτήν τη μέθοδο. Εάν αυτό προσδιορίζεται ως`μηδενικό`Εάν η υλοποίηση δεν επαναχρησιμοποιήσει το καθορισμένο αποτέλεσμα , ένα νέο αντικείμενο αποτελέσματος θα κατασκευαστεί και θα επιστραφεί. Για αποτελέσματα XPath 1.0, αυτό το αντικείμενο θα είναι τύπου [`IXPathResult`](../../ixpathresult/). |

### Επιστρεφόμενη Αξία

Το αποτέλεσμα της αξιολόγησης της έκφρασης XPath. Για αποτελέσματα XPath 1.0, αυτό το αντικείμενο θα είναι τύπου [`IXPathResult`](../../ixpathresult/).

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: Αυξάνεται εάν το αποτέλεσμα δεν μπορεί να μετατραπεί για να επιστρέψει τον καθορισμένο τύπο. |
| [DOMException](../../../aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: Ο κόμβος προέρχεται από ένα έγγραφο που δεν υποστηρίζεται από το [`IXPathEvaluator`](../../ixpathevaluator/) που το δημιούργησε αυτό[`IXPathExpression`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Ο Κόμβος δεν είναι τύπος που επιτρέπεται ως κόμβος περιβάλλοντος XPath ή ο τύπος αιτήματος δεν επιτρέπεται από αυτό[`IXPathExpression`](../). |

### Δείτε επίσης

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* χώρος ονομάτων [Aspose.Html.Dom.XPath](../../ixpathexpression/)
* συνέλευση [Aspose.HTML](../../../)


