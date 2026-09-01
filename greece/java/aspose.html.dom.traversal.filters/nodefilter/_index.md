---
title: "Κλάση NodeFilter"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Κλάση com.aspose.html.dom.traversal.filters.NodeFilter. Τα φίλτρα είναι αντικείμενα που ξέρουν πώς να φιλτράρουν κόμβους"
type: docs

url: /el/java/com.aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

Τα φίλτρα είναι αντικείμενα που ξέρουν πώς να "φιλτράρουν" κόμβους.

```java
public abstract class NodeFilter : DOMObject, INodeFilter
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| abstract [AcceptNode](../../com.aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | Δοκιμάστε εάν ένας καθορισμένος κόμβος είναι ορατός στην λογική προβολή ενός TreeWalker ή NodeIterator. Αυτή η λειτουργία θα κληθεί από την υλοποίηση του TreeWalker και του NodeIterator· συνήθως δεν καλείται άμεσα από κώδικα χρήστη. (Ωστόσο, μπορείτε να το κάνετε εάν θέλετε να χρησιμοποιήσετε το ίδιο φίλτρο για να καθοδηγήσετε τη λογική της εφαρμογής σας.) |
| [getPlatformType](../../com.aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου αντικειμένου ECMAScript. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [FILTER_ACCEPT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | Αποδοχή του κόμβου. Οι μέθοδοι πλοήγησης που ορίζονται για NodeIterator ή TreeWalker θα επιστρέψουν αυτόν τον κόμβο. |
| const [FILTER_REJECT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | Απόρριψη του κόμβου. Οι μέθοδοι πλοήγησης που ορίζονται για NodeIterator ή TreeWalker δεν θα επιστρέψουν αυτόν τον κόμβο. Για το TreeWalker, τα παιδιά αυτού του κόμβου θα απορριφθούν επίσης. Οι NodeIterators θεωρούν αυτό ως συνώνυμο του FILTER_SKIP. |
| const [FILTER_SKIP](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | Παράλειψη αυτού του μοναδικού κόμβου. Οι μέθοδοι πλοήγησης που ορίζονται για NodeIterator ή TreeWalker δεν θα επιστρέψουν αυτόν τον κόμβο. Για τόσο το NodeIterator όσο και το TreeWalker, τα παιδιά αυτού του κόμβου θα εξακολουθούν να λαμβάνονται υπόψη. |
| const [SHOW_ALL](../../com.aspose.html.dom.traversal.filters/nodefilter/show_all/) | Εμφάνιση όλων των κόμβων. |
| const [SHOW_ATTRIBUTE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | Εμφάνιση κόμβων Attr. Αυτό έχει νόημα μόνο όταν δημιουργείται ένας επαναλήπτης ή tree-walker με έναν κόμβο χαρακτηριστικού ως ρίζα· σε αυτήν την περίπτωση, σημαίνει ότι ο κόμβος χαρακτηριστικού θα εμφανιστεί στην πρώτη θέση της επανάληψης ή της διαδρομής. Δεδομένου ότι τα χαρακτηριστικά δεν είναι ποτέ παιδιά άλλων κόμβων, δεν εμφανίζονται κατά την περιήγηση του δένδρου του εγγράφου. |
| const [SHOW_CDATA_SECTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | Εμφάνιση κόμβων CDATASection. |
| const [SHOW_COMMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_comment/) | Εμφάνιση κόμβων Comment. |
| const [SHOW_DOCUMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document/) | Εμφάνιση κόμβων Document. |
| const [SHOW_DOCUMENT_FRAGMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | Εμφάνιση κόμβων DocumentFragment. |
| const [SHOW_DOCUMENT_TYPE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | Εμφάνιση κόμβων DocumentType. |
| const [SHOW_ELEMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_element/) | Εμφάνιση κόμβων Element. |
| const [SHOW_ENTITY](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity/) | Εμφάνιση κόμβων Entity. Αυτό έχει νόημα μόνο όταν δημιουργείται ένας επαναλήπτης ή tree-walker με έναν κόμβο Entity ως ρίζα· σε αυτήν την περίπτωση, σημαίνει ότι ο κόμβος Entity θα εμφανιστεί στην πρώτη θέση της διαδρομής. Δεδομένου ότι οι οντότητες δεν αποτελούν μέρος του δένδρου του εγγράφου, δεν εμφανίζονται κατά την περιήγηση του δένδρου του εγγράφου. |
| const [SHOW_ENTITY_REFERENCE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | Εμφάνιση κόμβων EntityReference. |
| const [SHOW_NOTATION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_notation/) | Εμφάνιση κόμβων Notation. Αυτό είναι σημαντικό μόνο όταν δημιουργείται ένας iterator ή tree-walker με έναν κόμβο Notation ως ρίζα· σε αυτήν την περίπτωση, σημαίνει ότι ο κόμβος Notation θα εμφανιστεί στην πρώτη θέση της διαδρομής. Δεδομένου ότι οι σημειώσεις δεν αποτελούν μέρος του δένδρου εγγράφου, δεν εμφανίζονται κατά την περιήγηση του δένδρου εγγράφου. |
| const [SHOW_PROCESSING_INSTRUCTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | Εμφάνιση κόμβων ProcessingInstruction. |
| const [SHOW_TEXT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_text/) | Εμφάνιση κόμβων Text. |

### Δείτε επίσης

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [INodeFilter](../../com.aspose.html.dom.traversal/inodefilter/)
* package [com.aspose.html.dom.traversal.filters](../../com.aspose.html.dom.traversal.filters/)
* package [Aspose.HTML](../../)
