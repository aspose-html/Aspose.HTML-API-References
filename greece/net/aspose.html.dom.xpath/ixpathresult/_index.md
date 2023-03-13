---
title: Interface IXPathResult
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Dom.XPath.IXPathResult διεπαφή. ΤοXPathResult Η διεπαφή αντιπροσωπεύει το αποτέλεσμα της αξιολόγησης μιας έκφρασης XPath 1.0 στο πλαίσιο ενός συγκεκριμένου κόμβου. Εφόσον η αξιολόγηση μιας έκφρασης XPath μπορεί να οδηγήσει σε διάφορους τύπους αποτελεσμάτων αυτό το αντικείμενο καθιστά δυνατό τον να ανακαλύψει και να χειριστεί τον τύπο και την τιμή του αποτελέσματος.
type: docs
weight: 2600
url: /el/net/aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

Το`XPathResult` Η διεπαφή αντιπροσωπεύει το αποτέλεσμα της αξιολόγησης μιας έκφρασης XPath 1.0 στο πλαίσιο ενός συγκεκριμένου κόμβου. Εφόσον η αξιολόγηση μιας έκφρασης XPath μπορεί να οδηγήσει σε διάφορους τύπους αποτελεσμάτων, αυτό το αντικείμενο καθιστά δυνατό τον να ανακαλύψει και να χειριστεί τον τύπο και την τιμή του αποτελέσματος.

```csharp
public interface IXPathResult
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [BooleanValue](../../aspose.html.dom.xpath/ixpathresult/booleanvalue/) { get; } | Η τιμή αυτού του δυαδικού αποτελέσματος. |
| [InvalidIteratorState](../../aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) { get; } | Σημαίνει ότι ο επαναλήπτης έχει καταστεί άκυρος. Αλήθεια αν`Τύπος αποτελεσμάτων` είναι`UnorderedNodeIterator` τύπος ή`OrderedNodeIterator` πληκτρολογήστε και το έγγραφο έχει τροποποιηθεί από τότε που επιστράφηκε αυτό το αποτέλεσμα. |
| [NumberValue](../../aspose.html.dom.xpath/ixpathresult/numbervalue/) { get; } | Η τιμή αυτού του αριθμού προκύπτει. |
| [ResultType](../../aspose.html.dom.xpath/ixpathresult/resulttype/) { get; } | Ένας κωδικός που αντιπροσωπεύει τον τύπο αυτού του αποτελέσματος, όπως ορίζεται από το http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult [`XPathResultType`](../xpathresulttype/) αριθ. |
| [SingleNodeValue](../../aspose.html.dom.xpath/ixpathresult/singlenodevalue/) { get; } | Η τιμή αυτού του αποτελέσματος μεμονωμένου κόμβου, που μπορεί να είναι`μηδενικό` . |
| [SnapshotLength](../../aspose.html.dom.xpath/ixpathresult/snapshotlength/) { get; } | Ο αριθμός των κόμβων στο στιγμιότυπο αποτελέσματος. Οι έγκυρες τιμές για τους δείκτες snapshotItem είναι`0` προς την`στιγμιότυπο Μήκος-1` συμπεριλαμβανομένου. |
| [StringValue](../../aspose.html.dom.xpath/ixpathresult/stringvalue/) { get; } | Η τιμή αυτού του αποτελέσματος συμβολοσειράς. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [IterateNext](../../aspose.html.dom.xpath/ixpathresult/iteratenext/)() | Επαναλαμβάνει και επιστρέφει τον επόμενο κόμβο από το σύνολο κόμβων ή`μηδενικό` αν δεν υπάρχουν άλλοι κόμβοι. |
| [SnapshotItem](../../aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | Επιστρέφει το`δείκτης` το στοιχείο της συλλογής στιγμιότυπων. Αν`δείκτης`είναι μεγαλύτερο από ή ίσο με τον αριθμό των κόμβων στη λίστα, αυτή η μέθοδος επιστρέφει`μηδενικό` . Σε αντίθεση με το αποτέλεσμα του επαναλήπτη , το στιγμιότυπο δεν καθίσταται άκυρο, αλλά ενδέχεται να μην αντιστοιχεί στο τρέχον έγγραφο εάν έχει μεταλλαχθεί. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* συνέλευση [Aspose.HTML](../../)


