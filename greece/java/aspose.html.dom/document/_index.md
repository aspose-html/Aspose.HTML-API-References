---
title: "Κλάση Document"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.Document κλάση. Το Document αντιπροσωπεύει ολόκληρο το έγγραφο HTML, XML ή SVG. Συγκεκριμένα, είναι η ρίζα του δέντρου του εγγράφου και παρέχει την κύρια πρόσβαση στα δεδομένα του εγγράφου."
type: docs

url: /el/java/com.aspose.html.dom/document/
---
## Document class

Το Document αντιπροσωπεύει ολόκληρο το έγγραφο HTML, XML ή SVG. Συγκεκριμένα, είναι η ρίζα του δέντρου εγγράφου και παρέχει την κύρια πρόσβαση στα δεδομένα του εγγράφου.

```java
public class Document : Node, IDocumentEvent, IDocumentStyle, IDocumentTraversal, 
    IGlobalEventHandlers, INonElementParentNode, IParentNode, IXPathEvaluator
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/document/baseuri/) Το απόλυτο βασικό URI αυτού του κόμβου ή null εάν η υλοποίηση δεν μπόρεσε να αποκτήσει ένα απόλυτο URI. |
| [getCharacterSet](../../com.aspose.html.dom/document/characterset/) Λαμβάνει την κωδικοποίηση του εγγράφου. |
| [getCharset](../../com.aspose.html.dom/document/charset/) Λαμβάνει την κωδικοποίηση του εγγράφου. |
| [getChildElementCount](../../com.aspose.html.dom/document/childelementcount/) Επιστρέφει τον τρέχοντα αριθμό των κόμβων στοιχείων που είναι παιδιά αυτού του στοιχείου. 0 εάν αυτό το στοιχείο δεν έχει παιδικούς κόμβους τύπου nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Η ιδιότητα μόνο για ανάγνωση childNodes της διεπαφής Node επιστρέφει μια ζωντανή λίστα [`NodeList`](../../com.aspose.html.collections/nodelist/) των κόμβων-παιδιών του δεδομένου στοιχείου, όπου ο πρώτος κόμβος παιδί έχει δείκτη 0. Οι κόμβοι-παιδιά περιλαμβάνουν στοιχεία, κείμενο και σχόλια. |
| [getChildren](../../com.aspose.html.dom/document/children/) Επιστρέφει τα θυγατρικά στοιχεία. |
| [getContentType](../../com.aspose.html.dom/document/contenttype/) Αποκτά τον τύπο περιεχομένου του εγγράφου. |
| [getContext](../../com.aspose.html.dom/document/context/) Αποκτά το τρέχον περιβάλλον περιήγησης. |
| [getDefaultView](../../com.aspose.html.dom/document/defaultview/) Το χαρακτηριστικό IDL defaultView της διεπαφής Document, κατά την ανάκτηση, πρέπει να επιστρέφει το αντικείμενο WindowProxy του περιβάλλοντος περιήγησης αυτού του Εγγράφου, εάν το Έγγραφο έχει συσχετισμένο περιβάλλον περιήγησης, ή null διαφορετικά. |
| [getDoctype](../../com.aspose.html.dom/document/doctype/) Η Δήλωση Τύπου Εγγράφου (Document Type Declaration) που σχετίζεται με αυτό το έγγραφο. |
| [getDocumentElement](../../com.aspose.html.dom/document/documentelement/) Αυτό είναι ένα βολικό χαρακτηριστικό που επιτρέπει άμεση πρόσβαση στον κόμβο-παιδί που είναι το στοιχείο εγγράφου του εγγράφου. |
| [getDocumentURI](../../com.aspose.html.dom/document/documenturi/) Η θέση του εγγράφου ή null εάν δεν ορίζεται ή εάν το Έγγραφο δημιουργήθηκε χρησιμοποιώντας τη μέθοδο DOMImplementation.createDocument. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Η ιδιότητα μόνο για ανάγνωση firstChild της διεπαφής [`Node`](../node/) επιστρέφει το πρώτο παιδί του κόμβου στο δέντρο, ή null εάν ο κόμβος δεν έχει παιδιά. |
| [getFirstElementChild](../../com.aspose.html.dom/document/firstelementchild/) Επιστρέφει τον πρώτο κόμβο στοιχείου-παιδί αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει παιδικά στοιχεία. |
| [getImplementation](../../com.aspose.html.dom/document/implementation/) Το αντικείμενο DOMImplementation που διαχειρίζεται αυτό το έγγραφο. |
| [getInputEncoding](../../com.aspose.html.dom/document/inputencoding/) Αποκτά την κωδικοποίηση του εγγράφου. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Η ιδιότητα μόνο για ανάγνωση lastChild της διεπαφής [`Node`](../node/) επιστρέφει το τελευταίο παιδί του κόμβου. Εάν ο γονέας του είναι ένα στοιχείο, τότε το παιδί είναι γενικά ένας κόμβος στοιχείου, ένας κόμβος κειμένου ή ένας κόμβος σχολίου. Επιστρέφει null εάν δεν υπάρχουν παιδικά στοιχεία. |
| [getLastElementChild](../../com.aspose.html.dom/document/lastelementchild/) Επιστρέφει τον τελευταίο κόμβο στοιχείου-παιδί αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει παιδικά στοιχεία. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Επιστρέφει το τοπικό μέρος του πλήρους ονόματος αυτού του κόμβου. Για κόμβους οποιουδήποτε τύπου εκτός από [`ELEMENT_NODE`](../node/element_node/) και [`ATTRIBUTE_NODE`](../node/attribute_node/) και κόμβους που δημιουργήθηκαν με μέθοδο DOM Level 1, όπως [`Document.createElement()`](./createelement/), αυτό είναι πάντα null. |
| [getLocation](../../com.aspose.html.dom/document/location/) Η θέση του εγγράφου. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Η ιδιότητα μόνο για ανάγνωση Element.packageURI επιστρέφει το URI του πακέτου του στοιχείου, ή null εάν το στοιχείο δεν βρίσκεται σε πακέτο. |
| [getNextElementSibling](../../com.aspose.html.dom/document/nextelementsibling/) Επιστρέφει τον επόμενο αδερφό κόμβο στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει αδερφούς κόμβους στοιχείου που έρχονται μετά από αυτό στο δέντρο του εγγράφου. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Η ιδιότητα μόνο για ανάγνωση nextSibling της διεπαφής [`Node`](../node/) επιστρέφει τον κόμβο που ακολουθεί αμέσως τον καθορισμένο στον γονέα του [`childNodes`](../node/childnodes/), ή επιστρέφει null εάν ο καθορισμένος κόμβος είναι το τελευταίο παιδί στο γονικό στοιχείο. |
| [getNodeName](../../com.aspose.html.dom/document/nodename/) Το όνομα αυτού του κόμβου, ανάλογα με τον τύπο του. |
| [getNodeType](../../com.aspose.html.dom/document/nodetype/) Ένας κώδικας που αντιπροσωπεύει τον τύπο του υποκείμενου αντικειμένου. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | Η ιδιότητα nodeValue του interface [`Node `](../node/) επιστρέφει ή ορίζει την τιμή του τρέχοντος κόμβου. |
| [getOrigin](../../com.aspose.html.dom/document/origin/) Αποκτά την προέλευση του εγγράφου. |
| [getOwnerDocument](../../com.aspose.html.dom/document/ownerdocument/) Αποκτά το έγγραφο ιδιοκτήτη. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Η ιδιότητα μόνο για ανάγνωση parentElement της διεπαφής [`Node`](../node/) επιστρέφει τον γονικό [`Element`](../element/) του κόμβου DOM, ή null εάν ο κόμβος δεν έχει γονέα ή ο γονέας του δεν είναι στοιχείο DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Η μόνο-ανάγνωση ιδιότητα parentNode του interface Node επιστρέφει τον γονέα του καθορισμένου κόμβου στο δέντρο DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | Η ιδιότητα μόνο για ανάγνωση prefix επιστρέφει το πρόθεμα πακέτου του συγκεκριμένου στοιχείου, ή null εάν δεν έχει καθοριστεί πρόθεμα. |
| [getPreviousElementSibling](../../com.aspose.html.dom/document/previouselementsibling/) Επιστρέφει τον προηγούμενο αδερφό κόμβο στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει αδερφούς κόμβους στοιχείου που έρχονται πριν από αυτό στο δέντρο του εγγράφου. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Η ιδιότητα μόνο για ανάγνωση previousSibling της διεπαφής [`Node`](../node/) επιστρέφει τον κόμβο που προηγείται αμέσως του καθορισμένου στη λίστα των [`childNodes`](../node/firstchild/) του γονέα του, ή null εάν ο καθορισμένος κόμβος είναι ο πρώτος σε αυτή τη λίστα. |
| [getReadyState](../../com.aspose.html.dom/document/readystate/) Επιστρέφει την κατάσταση ετοιμότητας του εγγράφου. Το "loading" ενώ το Έγγραφο φορτώνεται, το "interactive" όταν ολοκληρωθεί η ανάλυση αλλά εξακολουθούν να φορτώνονται υπο-πόροι, και το "complete" όταν έχει φορτωθεί πλήρως. |
[getStrictErrorChecking]
[setStrictErrorChecking] An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [getStyleSheets](../../com.aspose.html.dom/document/stylesheets/) Μια λίστα που περιέχει όλα τα φύλλα στυλ που συνδέονται ρητά ή ενσωματώνονται σε ένα έγγραφο. Για έγγραφα HTML, αυτό περιλαμβάνει εξωτερικά φύλλα στυλ, που περιλαμβάνονται μέσω του στοιχείου HTML LINK, και ενσωματωμένα στοιχεία STYLE. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | Η ιδιότητα textContent του interface [`Node`](../node/) αντιπροσωπεύει το κείμενο του κόμβου και των απογόνων του. |
[getXmlStandalone]
[setXmlStandalone] An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
[getXmlVersion]
[setXmlVersion] An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Η μέθοδος addEventListener() της διεπαφής [`EventTarget `](../eventtarget/) ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Η μέθοδος addEventListener() του interface [EventTarget ](T:com.aspose.html.dom.EventTarget) ορίζει μια συνάρτηση που θα κληθεί κάθε φορά που το καθορισμένο συμβάν παραδίδεται στον στόχο. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Η μέθοδος addEventListener() του interface [EventTarget ](T:com.aspose.html.dom.EventTarget) ορίζει μια συνάρτηση που θα κληθεί κάθε φορά που το καθορισμένο συμβάν παραδίδεται στον στόχο. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Η μέθοδος appendChild() του interface Node προσθέτει έναν κόμβο στο τέλος της λίστας των παιδιών ενός καθορισμένου γονικού κόμβου. Εάν το δοσμένο παιδί είναι αναφορά σε έναν υπάρχοντα κόμβο στο έγγραφο, η appendChild() τον μετακινεί από την τρέχουσα θέση του στη νέα θέση (δεν απαιτείται η αφαίρεση του κόμβου από τον γονικό του πριν την προσθήκη του σε κάποιον άλλο κόμβο). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Η μέθοδος cloneNode() του interface Node επιστρέφει ένα αντίγραφο του κόμβου στον οποίο κλήθηκε αυτή η μέθοδος. Η παράμετρός της ελέγχει αν το υποδέντρο που περιέχεται σε έναν κόμβο θα κλωνοποιηθεί επίσης ή όχι. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Η μέθοδος cloneNode() του interface Node επιστρέφει ένα αντίγραφο του κόμβου στον οποίο κλήθηκε αυτή η μέθοδος. Η παράμετρός της ελέγχει αν το υποδέντρο που περιέχεται σε έναν κόμβο θα κλωνοποιηθεί επίσης ή όχι. |
| [createAttribute](../../com.aspose.html.dom/document/createattribute/)(String) | Η μέθοδος Document.createAttribute() δημιουργεί έναν νέο κόμβο χαρακτηριστικού και τον επιστρέφει. Το αντικείμενο δημιουργεί έναν κόμβο που υλοποιεί τη διεπαφή [`Attr`](../attr/). Το DOM δεν επιβάλλει ποιοι τύποι χαρακτηριστικών μπορούν να προστεθούν σε ένα συγκεκριμένο στοιχείο με αυτόν τον τρόπο. |
| [createAttributeNS](../../com.aspose.html.dom/document/createattributens/)(String, String) | Η μέθοδος Document.createAttribute() δημιουργεί έναν νέο κόμβο χαρακτηριστικού και τον επιστρέφει. Το αντικείμενο δημιουργεί έναν κόμβο που υλοποιεί το interface [Attr](T:com.aspose.html.dom.Attr). Το DOM δεν επιβάλλει ποιο είδος χαρακτηριστικών μπορεί να προστεθεί σε ένα συγκεκριμένο στοιχείο με αυτόν τον τρόπο. |
| [createCDATASection](../../com.aspose.html.dom/document/createcdatasection/)(String) | Δημιουργεί έναν κόμβο [`CDATASection`](../cdatasection/) του οποίου η τιμή είναι η καθορισμένη συμβολοσειρά. |
| [createComment](../../com.aspose.html.dom/document/createcomment/)(String) | Δημιουργεί έναν κόμβο [`Comment`](../comment/) με την καθορισμένη συμβολοσειρά. |
| [createDocumentFragment](../../com.aspose.html.dom/document/createdocumentfragment/)() | Δημιουργεί ένα νέο κενό [`DocumentFragment`](../documentfragment/) στο οποίο μπορούν να προστεθούν κόμβοι DOM για την κατασκευή ενός εκτός οθόνης δέντρου DOM. |
| [createDocumentType](../../com.aspose.html.dom/document/createdocumenttype/)(String, String, String, String) | Η μέθοδος επιστρέφει ένα αντικείμενο [`DocumentType`](../documenttype/) που μπορεί είτε να χρησιμοποιηθεί με το DOMImplementation.createDocument κατά τη δημιουργία του εγγράφου είτε να ενσωματωθεί στο έγγραφο μέσω μεθόδων όπως Node.insertBefore() ή Node.replaceChild(). |
| [createElement](../../com.aspose.html.dom/document/createelement/)(String) | Σε ένα έγγραφο HTML, η μέθοδος document.createElement() δημιουργεί το στοιχείο HTML που καθορίζεται από το tagName, ή ένα [`HTMLUnknownElement`](../../com.aspose.html/htmlunknownelement/) εάν το tagName δεν αναγνωρίζεται. |
| [createElementNS](../../com.aspose.html.dom/document/createelementns/)(String, String) | Δημιουργεί ένα στοιχείο με το δεδομένο πλήρες όνομα και το URI του πακέτου. |
| [createEntityReference](../../com.aspose.html.dom/document/createentityreference/)(String) | Δημιουργεί ένα αντικείμενο EntityReference. Επιπλέον, εάν η αναφερόμενη οντότητα είναι γνωστή, η λίστα παιδιών του κόμβου EntityReference γίνεται ίδια με αυτή του αντίστοιχου κόμβου Entity. |
| [createEvent](../../com.aspose.html.dom/document/createevent/)(String) | Δημιουργεί ένα [`Event`](../../com.aspose.html.dom.events/event/) τύπου που υποστηρίζεται από την υλοποίηση. |
| [createExpression](../../com.aspose.html.dom/document/createexpression/)(String, IXPathNSResolver) | Δημιουργεί μια αναλυμένη έκφραση XPath με επιλυμένα πακέτα. Αυτό είναι χρήσιμο όταν μια έκφραση θα επαναχρησιμοποιηθεί σε μια εφαρμογή, καθώς καθιστά δυνατή τη μεταγλώττιση της String της έκφρασης σε πιο αποδοτική εσωτερική μορφή και την προεπίλυση όλων των προθεμάτων πακέτων που εμφανίζονται στην έκφραση. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator)(Node) | Δημιουργήστε έναν νέο NodeIterator πάνω στο υποδέντρο που έχει ρίζα τον καθορισμένο κόμβο. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator_1)(Node, long) | Δημιουργήστε έναν νέο NodeIterator πάνω στο υποδέντρο που έχει ρίζα τον καθορισμένο κόμβο. |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | Δημιουργήστε έναν νέο NodeIterator πάνω στο υποδέντρο που έχει ρίζα τον καθορισμένο κόμβο. |
| [createNSResolver](../../com.aspose.html.dom/document/creatensresolver/)(Node) | Προσαρμόζει οποιονδήποτε κόμβο DOM για την επίλυση πακέτων ώστε μια έκφραση XPath να μπορεί να αξιολογηθεί εύκολα σε σχέση με το πλαίσιο του κόμβου όπου εμφανίστηκε μέσα στο έγγραφο. Αυτός ο προσαρμογέας λειτουργεί όπως η μέθοδος DOM Level 3 `lookupNamespaceURI` στους κόμβους για την επίλυση του packageURI από ένα δεδομένο πρόθεμα χρησιμοποιώντας τις τρέχουσες πληροφορίες που είναι διαθέσιμες στην ιεραρχία του κόμβου τη στιγμή που καλείται η lookupNamespaceURI, επίσης επιλύοντας σωστά το ρητό πρόθεμα xml. |
| [createProcessingInstruction](../../com.aspose.html.dom/document/createprocessinginstruction/)(String, String) | Δημιουργεί έναν κόμβο ProcessingInstruction με το καθορισμένο όνομα και τις δεδομένες Strings δεδομένων. |
| [createTextNode](../../com.aspose.html.dom/document/createtextnode/)(String) | Δημιουργεί έναν κόμβο Text με τη δοσμένη String. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker)(Node) | Δημιουργήστε έναν νέο TreeWalker πάνω στο υποδέντρο που έχει ρίζα τον καθορισμένο κόμβο. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker_1)(Node, long) | Δημιουργήστε έναν νέο TreeWalker πάνω στο υποδέντρο που έχει ρίζα τον καθορισμένο κόμβο. |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | Δημιουργήστε έναν νέο TreeWalker πάνω στο υποδέντρο που έχει ρίζα τον καθορισμένο κόμβο. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Αποστέλλει ένα Event στο καθορισμένο [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (συγχρονισμένα) ενεργοποιώντας τους επηρεαζόμενους EventListeners με τη σωστή σειρά. Οι κανονικοί κανόνες επεξεργασίας συμβάντων (συμπεριλαμβανομένου του πλαισίου σύλληψης και του προαιρετικού φάσης φουσκώματος) ισχύουν επίσης για συμβάντα που αποστέλλονται χειροκίνητα με την [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Εκτελεί εργασίες που ορίζονται από την εφαρμογή και σχετίζονται με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| [evaluate](../../com.aspose.html.dom/document/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | Αξιολογεί μια String έκφρασης XPath και επιστρέφει ένα αποτέλεσμα του καθορισμένου τύπου, εάν είναι δυνατόν. |
| [getElementById](../../com.aspose.html.dom/document/getelementbyid/)(String) | Η μέθοδος Document getElementById() επιστρέφει ένα αντικείμενο [`Element`](../element/) που αντιπροσωπεύει το στοιχείο του οποίου η ιδιότητα id ταιριάζει με την καθορισμένη συμβολοσειρά. Δεδομένου ότι τα IDs των στοιχείων πρέπει να είναι μοναδικά εάν καθοριστούν, αποτελούν έναν χρήσιμο τρόπο γρήγορης πρόσβασης σε ένα συγκεκριμένο στοιχείο. |
| [getElementsByClassName](../../com.aspose.html.dom/document/getelementsbyclassname/)(String) | Η μέθοδος getElementsByClassName της διεπαφής `Document` επιστρέφει ένα αντικείμενο τύπου πίνακα με όλα τα θυγατρικά στοιχεία που έχουν όλα τα δοθέντα ονόματα κλάσης. |
| [getElementsByTagName](../../com.aspose.html.dom/document/getelementsbytagname/)(String) | Η μέθοδος getElementsByTagName της διεπαφής `Document` επιστρέφει μια [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) στοιχείων με το δοθέν όνομα ετικέτας. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/document/getelementsbytagnamens/)(String, String) | Επιστρέφει μια λίστα στοιχείων με το δοσμένο όνομα ετικέτας που ανήκουν στο δοσμένο πακέτο. Αναζητείται ολόκληρο το έγγραφο, συμπεριλαμβανομένου του ριζικού κόμβου. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του αντικειμένου ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Η μέθοδος hasChildNodes() της διεπαφής Node επιστρέφει μια λογική τιμή που υποδεικνύει εάν το δεδομένο [`Node`](../node/) έχει παιδικούς κόμβους ή όχι. |
| [importNode](../../com.aspose.html.dom/document/importnode/)(Node, bool) | Εισάγει έναν κόμβο από άλλο έγγραφο σε αυτό το έγγραφο, χωρίς να τροποποιήσει ή να αφαιρέσει τον πηγαίο κόμβο από το αρχικό έγγραφο· αυτή η μέθοδος δημιουργεί ένα νέο αντίγραφο του πηγαίου κόμβου. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Η μέθοδος insertBefore() του interface Node εισάγει έναν κόμβο πριν από έναν κόμβο αναφοράς ως παιδί ενός καθορισμένου γονικού κόμβου. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Η μέθοδος isDefaultNamespace() του interface Node δέχεται ένα URI πακέτου ως όρισμα. Επιστρέφει μια Boolean τιμή που είναι true εάν το πακέτο είναι το προεπιλεγμένο πακέτο στον δεδομένο κόμβο και false εάν όχι. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Η μέθοδος isEqualNode() της διεπαφής [`Node`](../node/) ελέγχει εάν δύο κόμβοι είναι ίσοι. Δύο κόμβοι είναι ίσοι όταν έχουν τον ίδιο τύπο, χαρακτηριστικά ορισμού (για στοιχεία, αυτό θα ήταν το ID τους, ο αριθμός των παιδιών κ.λπ.), τα χαρακτηριστικά τους ταιριάζουν, κ.ά. Το συγκεκριμένο σύνολο δεδομένων που πρέπει να ταιριάζει διαφέρει ανάλογα με τους τύπους των κόμβων. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Η μέθοδος isSameNode() του interface Node είναι ένα παλαιότερο ψευδώνυμο για τον τελεστή αυστηρής ισότητας ===. Δηλαδή, ελέγχει αν δύο κόμβοι είναι οι ίδιοι (δηλαδή, αν αναφέρονται στο ίδιο αντικείμενο). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Η μέθοδος lookupNamespaceURI() του interface Node λαμβάνει ένα πρόθεμα ως παράμετρο και επιστρέφει το URI του πακέτου που σχετίζεται με αυτό στον δεδομένο κόμβο, εάν βρεθεί (και null εάν όχι). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Η μέθοδος lookupPrefix() του interface Node επιστρέφει μια Συμβολοσειρά που περιέχει το πρόθεμα για ένα δεδομένο URI πακέτου, εάν υπάρχει, και null εάν όχι. Όταν είναι δυνατές πολλαπλές προθέματα, επιστρέφεται το πρώτο πρόθεμα. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate)(RequestMessage) | Φορτώνει το έγγραφο βάσει του καθορισμένου αντικειμένου αίτησης, αντικαθιστώντας το προηγούμενο περιεχόμενο. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_4)(String) | Φορτώνει το έγγραφο στη συγκεκριμένη Uniform Resource Locator (URL) στην τρέχουσα παρουσία, αντικαθιστώντας το προηγούμενο περιεχόμενο. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_1)(Url) | Φορτώνει το έγγραφο στη συγκεκριμένη Uniform Resource Locator (URL) στην τρέχουσα παρουσία, αντικαθιστώντας το προηγούμενο περιεχόμενο. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_3)(Stream, String) | Φορτώνει το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο. Η φόρτωση του εγγράφου ξεκινά από την τρέχουσα θέση στη ροή. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_2)(Stream, Url) | Φορτώνει το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο. Η φόρτωση του εγγράφου ξεκινά από την τρέχουσα θέση στη ροή. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_6)(String, String) | Φορτώνει το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο. |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_5)(String, Url) | Φορτώνει το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Τοποθετεί όλους τους κόμβους [`Text`](../text/) σε όλο το βάθος του υποδέντρου κάτω από αυτόν τον Node, συμπεριλαμβανομένων των κόμβων χαρακτηριστικών, σε μια "κανονική" μορφή όπου μόνο η δομή (π.χ., [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), και [`entity references`](../entityreference/)) χωρίζει τους κόμβους [`Text`](../text/), δηλαδή δεν υπάρχουν ούτε γειτονικοί κόμβοι Text ούτε κενά κόμβοι Text. Αυτό μπορεί να χρησιμοποιηθεί για να διασφαλιστεί ότι η προβολή DOM ενός εγγράφου είναι η ίδια όπως αν αποθηκευόταν και φορτωνόταν ξανά, και είναι χρήσιμο όταν λειτουργίες (όπως αναζητήσεις XPointer [XPointer]) που εξαρτώνται από μια συγκεκριμένη δομή δέντρου εγγράφου πρέπει να χρησιμοποιηθούν. Εάν η παράμετρος "normalize-characters" του αντικειμένου [`DOMConfiguration`](../../com.aspose.html/configuration/) που είναι συνδεδεμένο με το [`Node.ownerDocument`](../node/ownerdocument/) είναι true, αυτή η μέθοδος θα κανονικοποιήσει επίσης πλήρως τους χαρακτήρες των κόμβων Text. |
| [querySelector](../../com.aspose.html.dom/document/queryselector/)(String) | Επιστρέφει το πρώτο Element στο έγγραφο, που ταιριάζει με τον selector |
| [querySelectorAll](../../com.aspose.html.dom/document/queryselectorall/)(String) | Επιστρέφει ένα NodeList όλων των Elements στο έγγραφο, που ταιριάζουν με τον selector |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Η μέθοδος removeChild() του interface Node αφαιρεί ένα child node από το DOM και επιστρέφει το αφαιρεθέν node. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα event listener αφαιρεθεί από ένα event target ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Τα Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα event listener αφαιρεθεί από ένα event target ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Τα Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα event listener αφαιρεθεί από ένα event target ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Τα Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [renderTo](../../com.aspose.html.dom/document/renderto/)(IDevice) | Αυτή η μέθοδος χρησιμοποιείται για την απόδοση του περιεχομένου του τρέχοντος εγγράφου σε μια καθορισμένη γραφική συσκευή. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Αντικαθιστά τον παιδικό κόμβο oldChild με το newChild στη λίστα των παιδιών και επιστρέφει τον κόμβο oldChild. Εάν το newChild είναι ένα αντικείμενο [`DocumentFragment`](../documentfragment/), το oldChild αντικαθίσταται από όλα τα παιδιά του [`DocumentFragment`](../documentfragment/), τα οποία εισάγονται με την ίδια σειρά. Εάν το newChild βρίσκεται ήδη στο δέντρο, αφαιρείται πρώτα. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |
| [write](../../com.aspose.html.dom/document/write/)(params String[]) | Γράψτε μια συμβολοσειρά κειμένου σε ροή εγγράφου που ανοίχθηκε με το open(). Σημειώστε ότι η λειτουργία θα δημιουργήσει ένα έγγραφο που δεν είναι απαραίτητα καθοδηγούμενο από DTD και επομένως μπορεί να παράγει μη έγκυρο αποτέλεσμα στο πλαίσιο του εγγράφου. |
| [writeLn](../../com.aspose.html.dom/document/writeln/)(params String[]) | Γράψτε μια συμβολοσειρά κειμένου ακολουθούμενη από χαρακτήρα νέας γραμμής σε ροή εγγράφου που ανοίχθηκε με το open(). Σημειώστε ότι η λειτουργία θα δημιουργήσει ένα έγγραφο που δεν είναι απαραίτητα καθοδηγούμενο από DTD και επομένως μπορεί να παράγει μη έγκυρο αποτέλεσμα στο πλαίσιο του εγγράφου. |

## Συμβάντα

| Όνομα | Περιγραφή |
| --- | --- |
| event [OnAbort](../../com.aspose.html.dom/document/onabort/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnAbort. |
| event [OnBlur](../../com.aspose.html.dom/document/onblur/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnBlur. |
| event [OnCancel](../../com.aspose.html.dom/document/oncancel/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnCancel. |
| event [OnCanplay](../../com.aspose.html.dom/document/oncanplay/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnCanplay. |
| event [OnCanPlayThrough](../../com.aspose.html.dom/document/oncanplaythrough/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnCanPlayThrough. |
| event [OnChange](../../com.aspose.html.dom/document/onchange/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnChange. |
| event [OnClick](../../com.aspose.html.dom/document/onclick/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnClick. |
| event [OnCueChange](../../com.aspose.html.dom/document/oncuechange/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnCueChange. |
| event [OnDblClick](../../com.aspose.html.dom/document/ondblclick/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnDblClick. |
| event [OnDurationChange](../../com.aspose.html.dom/document/ondurationchange/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnDurationChange. |
| event [OnEmptied](../../com.aspose.html.dom/document/onemptied/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnEmptied. |
| event [OnEnded](../../com.aspose.html.dom/document/onended/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnEnded. |
| event [OnError](../../com.aspose.html.dom/document/onerror/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnError. |
| event [OnFocus](../../com.aspose.html.dom/document/onfocus/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnFocus. |
| event [OnInput](../../com.aspose.html.dom/document/oninput/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnInput. |
| event [OnInvalid](../../com.aspose.html.dom/document/oninvalid/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnInvalid. |
| event [OnKeyDown](../../com.aspose.html.dom/document/onkeydown/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnKeyDown. |
| event [OnKeyPress](../../com.aspose.html.dom/document/onkeypress/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnKeyPress. |
| event [OnKeyUp](../../com.aspose.html.dom/document/onkeyup/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnKeyUp. |
| event [OnLoad](../../com.aspose.html.dom/document/onload/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnLoad. |
| event [OnLoadedData](../../com.aspose.html.dom/document/onloadeddata/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnLoadedData. |
| event [OnLoadedMetadata](../../com.aspose.html.dom/document/onloadedmetadata/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnLoadedMetadata. |
| event [OnLoadStart](../../com.aspose.html.dom/document/onloadstart/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnLoadStart. |
| event [OnMouseDown](../../com.aspose.html.dom/document/onmousedown/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnMouseDown. |
| event [OnMouseEnter](../../com.aspose.html.dom/document/onmouseenter/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnMouseEnter. |
| event [OnMouseLeave](../../com.aspose.html.dom/document/onmouseleave/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnMouseLeave. |
| event [OnMouseMove](../../com.aspose.html.dom/document/onmousemove/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnMouseMove. |
| event [OnMouseOut](../../com.aspose.html.dom/document/onmouseout/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnMouseOut. |
| event [OnMouseOver](../../com.aspose.html.dom/document/onmouseover/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnMouseOver. |
| event [OnMouseUp](../../com.aspose.html.dom/document/onmouseup/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnMouseUp. |
| event [OnMouseWheel](../../com.aspose.html.dom/document/onmousewheel/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnMouseWheel. |
| event [OnPause](../../com.aspose.html.dom/document/onpause/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnPause. |
| event [OnPlay](../../com.aspose.html.dom/document/onplay/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnPlay. |
| event [OnPlaying](../../com.aspose.html.dom/document/onplaying/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnPlaying. |
| event [OnProgress](../../com.aspose.html.dom/document/onprogress/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnProgress. |
| event [OnRateChange](../../com.aspose.html.dom/document/onratechange/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnRateChange. |
| event [OnReadyStateChange](../../com.aspose.html.dom/document/onreadystatechange/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnReadyStateChange. |
| event [OnReset](../../com.aspose.html.dom/document/onreset/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnReset. |
| event [OnResize](../../com.aspose.html.dom/document/onresize/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnResize. |
| event [OnScroll](../../com.aspose.html.dom/document/onscroll/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnScroll. |
| event [OnSeeked](../../com.aspose.html.dom/document/onseeked/) | Λαμβάνει ή ορίζει τον χειριστή συμβάντος για το συμβάν OnSeeked. |
| event [OnSeeking](../../com.aspose.html.dom/document/onseeking/) | Λαμβάνει ή ορίζει τον χειριστή συμβάντος για το συμβάν OnSeeking. |
| event [OnSelect](../../com.aspose.html.dom/document/onselect/) | Λαμβάνει ή ορίζει τον χειριστή συμβάντος για το συμβάν OnSelect. |
| event [OnShow](../../com.aspose.html.dom/document/onshow/) | Λαμβάνει ή ορίζει τον χειριστή συμβάντος για το συμβάν OnShow. |
| event [OnStalled](../../com.aspose.html.dom/document/onstalled/) | Λαμβάνει ή ορίζει τον χειριστή συμβάντος για το συμβάν OnStalled. |
| event [OnSubmit](../../com.aspose.html.dom/document/onsubmit/) | Λαμβάνει ή ορίζει τον χειριστή συμβάντος για το συμβάν OnSubmit. |
| event [OnSuspend](../../com.aspose.html.dom/document/onsuspend/) | Λαμβάνει ή ορίζει τον χειριστή συμβάντος για το συμβάν OnSuspend. |
| event [OnTimeUpdate](../../com.aspose.html.dom/document/ontimeupdate/) | Λαμβάνει ή ορίζει τον χειριστή συμβάντος για το συμβάν OnTimeUpdate. |
| event [OnToggle](../../com.aspose.html.dom/document/ontoggle/) | Λαμβάνει ή ορίζει τον χειριστή συμβάντος για το συμβάν OnToggle. |
| event [OnVolumeChange](../../com.aspose.html.dom/document/onvolumechange/) | Λαμβάνει ή ορίζει τον χειριστή συμβάντος για το συμβάν OnVolumeChange. |
| event [OnWaiting](../../com.aspose.html.dom/document/onwaiting/) | Λαμβάνει ή ορίζει τον χειριστή συμβάντος για το συμβάν OnWaiting. |

### Δείτε επίσης

* class [Node](../node/)
* interface [IDocumentEvent](../../com.aspose.html.dom.events/idocumentevent/)
* interface [IDocumentStyle](../../com.aspose.html.dom.css/idocumentstyle/)
* interface [IDocumentTraversal](../../com.aspose.html.dom.traversal/idocumenttraversal/)
* interface [IGlobalEventHandlers](../iglobaleventhandlers/)
* interface [INonElementParentNode](../inonelementparentnode/)
* interface [IParentNode](../iparentnode/)
* interface [IXPathEvaluator](../../com.aspose.html.dom.xpath/ixpathevaluator/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
