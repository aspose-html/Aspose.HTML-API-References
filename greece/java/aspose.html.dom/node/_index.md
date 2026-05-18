---
title: "Κλάση Node"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.Node κλάση. Η διεπαφή Node είναι ο κύριος τύπος δεδομένων για ολόκληρο το Document Object Model. Αντιπροσωπεύει έναν μοναδικό κόμβο στο δέντρο του εγγράφου. Ενώ όλα τα αντικείμενα που υλοποιούν τη διεπαφή Node εκθέτουν μεθόδους για τη διαχείριση παιδιών, δεν όλα τα αντικείμενα που υλοποιούν τη διεπαφή Node μπορεί να έχουν παιδιά. Για παράδειγμα, οι κόμβοι Text μπορεί να μην έχουν παιδιά και η προσθήκη παιδιών σε τέτοιους κόμβους οδηγεί σε εξαίρεση DOMException."
type: docs

url: /el/java/com.aspose.html.dom/node/
---
## Node class

The διεπαφή Node είναι ο κύριος τύπος δεδομένων για ολόκληρο το Document Object Model. Αντιπροσωπεύει έναν μοναδικό κόμβο στο δέντρο του εγγράφου. Ενώ όλα τα αντικείμενα που υλοποιούν τη διεπαφή Node εκθέτουν μεθόδους για τη διαχείριση παιδιών, δεν όλα τα αντικείμενα που υλοποιούν τη διεπαφή Node μπορεί να έχουν παιδιά. Για παράδειγμα, οι κόμβοι [`Text`](../text/) μπορεί να μην έχουν παιδιά, και η προσθήκη παιδιών σε τέτοιους κόμβους προκαλεί την εμφάνιση ενός [`DOMException`](../domexception/).

Τα χαρακτηριστικά [`nodeName`](./nodename/), [`nodeValue`](./nodevalue/) και attributes περιλαμβάνονται ως μηχανισμός για την πρόσβαση σε πληροφορίες κόμβου χωρίς να γίνεται μετατροπή στο συγκεκριμένο παράγωγο διεπαφής. Σε περιπτώσεις όπου δεν υπάρχει προφανής αντιστοίχηση αυτών των χαρακτηριστικών για ένα συγκεκριμένο [`nodeType`](./nodetype/) (π.χ., nodeValue για ένα [`Element`](../element/) ή attributes για ένα [`Comment`](../comment/)), αυτή επιστρέφει null. Σημειώστε ότι οι εξειδικευμένες διεπαφές μπορεί να περιέχουν πρόσθετους και πιο βολικούς μηχανισμούς για την λήψη και ορισμό των σχετικών πληροφοριών.

```java
public abstract class Node : EventTarget, IXPathNSResolver
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Η ιδιότητα μόνο για ανάγνωση baseURI της διεπαφής Node επιστρέφει το απόλυτο βασικό URL του εγγράφου που περιέχει τον κόμβο. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Η ιδιότητα μόνο για ανάγνωση childNodes της διεπαφής Node επιστρέφει μια ζωντανή λίστα [`NodeList`](../../com.aspose.html.collections/nodelist/) των κόμβων-παιδιών του δεδομένου στοιχείου, όπου ο πρώτος κόμβος παιδί έχει δείκτη 0. Οι κόμβοι-παιδιά περιλαμβάνουν στοιχεία, κείμενο και σχόλια. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Η ιδιότητα μόνο για ανάγνωση firstChild της διεπαφής `Node` επιστρέφει το πρώτο παιδί του κόμβου στο δέντρο, ή null εάν ο κόμβος δεν έχει παιδιά. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Η ιδιότητα μόνο για ανάγνωση lastChild της διεπαφής `Node` επιστρέφει το τελευταίο παιδί του κόμβου. Εάν ο γονέας του είναι ένα στοιχείο, τότε το παιδί είναι γενικά ένας κόμβος στοιχείου, ένας κόμβος κειμένου ή ένας κόμβος σχολίου. Επιστρέφει null εάν δεν υπάρχουν παιδικά στοιχεία |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Επιστρέφει το τοπικό μέρος του πλήρους ονόματος αυτού του κόμβου. Για κόμβους οποιουδήποτε τύπου εκτός από [`ELEMENT_NODE`](./element_node/) και [`ATTRIBUTE_NODE`](./attribute_node/) και κόμβους που δημιουργήθηκαν με μέθοδο DOM Level 1, όπως [`Document.createElement()`](../document/createelement/), αυτό είναι πάντα null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Η ιδιότητα μόνο για ανάγνωση Element.packageURI επιστρέφει το URI του πακέτου του στοιχείου, ή null εάν το στοιχείο δεν βρίσκεται σε πακέτο. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Η ιδιότητα μόνο για ανάγνωση nextSibling της διεπαφής `Node` επιστρέφει τον κόμβο που ακολουθεί αμέσως τον καθορισμένο στον γονέα του, μέσω των [`childNodes`](./childnodes/), ή επιστρέφει null εάν ο καθορισμένος κόμβος είναι το τελευταίο παιδί στο γονικό στοιχείο. |
| abstract [getNodeName](../../com.aspose.html.dom/node/nodename/) Η ιδιότητα μόνο για ανάγνωση nodeName του Node επιστρέφει το όνομα του τρέχοντος κόμβου ως String. |
| abstract [getNodeType](../../com.aspose.html.dom/node/nodetype/) Ένας κώδικας που αντιπροσωπεύει τον τύπο του υποκείμενου αντικειμένου. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | Η ιδιότητα nodeValue της διεπαφής `Node `επιστρέφει ή ορίζει την τιμή του τρέχοντος κόμβου. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Η μόνο-ανάγνωση ιδιότητα ownerDocument του interface Node επιστρέφει το αντικείμενο εγγράφου υψηλότερου επιπέδου του κόμβου. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Η ιδιότητα μόνο για ανάγνωση parentElement της διεπαφής `Node` επιστρέφει τον γονικό [`Element`](../element/) του κόμβου DOM, ή null εάν ο κόμβος είτε δεν έχει γονέα, είτε ο γονέας του δεν είναι στοιχείο DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Η μόνο-ανάγνωση ιδιότητα parentNode του interface Node επιστρέφει τον γονέα του καθορισμένου κόμβου στο δέντρο DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | Η ιδιότητα μόνο για ανάγνωση prefix επιστρέφει το πρόθεμα πακέτου του συγκεκριμένου στοιχείου, ή null εάν δεν έχει καθοριστεί πρόθεμα. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Η ιδιότητα μόνο για ανάγνωση previousSibling της διεπαφής `Node` επιστρέφει τον κόμβο που προηγείται αμέσως του καθορισμένου στη λίστα των [`childNodes`](./firstchild/) του γονέα του, ή null εάν ο καθορισμένος κόμβος είναι ο πρώτος σε αυτή τη λίστα. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | Η ιδιότητα textContent της διεπαφής `Node` αντιπροσωπεύει το κειμενικό περιεχόμενο του κόμβου και των απογόνων του. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Η μέθοδος addEventListener() της διεπαφής [`EventTarget `](../eventtarget/) ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Η μέθοδος addEventListener() του interface [EventTarget ](T:com.aspose.html.dom.EventTarget) ορίζει μια συνάρτηση που θα κληθεί κάθε φορά που το καθορισμένο συμβάν παραδίδεται στον στόχο. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Η μέθοδος addEventListener() του interface [EventTarget ](T:com.aspose.html.dom.EventTarget) ορίζει μια συνάρτηση που θα κληθεί κάθε φορά που το καθορισμένο συμβάν παραδίδεται στον στόχο. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Η μέθοδος appendChild() του interface Node προσθέτει έναν κόμβο στο τέλος της λίστας των παιδιών ενός καθορισμένου γονικού κόμβου. Εάν το δοσμένο παιδί είναι αναφορά σε έναν υπάρχοντα κόμβο στο έγγραφο, η appendChild() τον μετακινεί από την τρέχουσα θέση του στη νέα θέση (δεν απαιτείται η αφαίρεση του κόμβου από τον γονικό του πριν την προσθήκη του σε κάποιον άλλο κόμβο). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode)() | Η μέθοδος cloneNode() του interface Node επιστρέφει ένα αντίγραφο του κόμβου στον οποίο κλήθηκε αυτή η μέθοδος. Η παράμετρός της ελέγχει αν το υποδέντρο που περιέχεται σε έναν κόμβο θα κλωνοποιηθεί επίσης ή όχι. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode_1)(bool) | Η μέθοδος cloneNode() του interface Node επιστρέφει ένα αντίγραφο του κόμβου στον οποίο κλήθηκε αυτή η μέθοδος. Η παράμετρός της ελέγχει αν το υποδέντρο που περιέχεται σε έναν κόμβο θα κλωνοποιηθεί επίσης ή όχι. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Αποστέλλει ένα Event στο καθορισμένο [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (συγχρονισμένα) ενεργοποιώντας τους επηρεαζόμενους EventListeners με τη σωστή σειρά. Οι κανονικοί κανόνες επεξεργασίας συμβάντων (συμπεριλαμβανομένου του πλαισίου σύλληψης και του προαιρετικού φάσης φουσκώματος) ισχύουν επίσης για συμβάντα που αποστέλλονται χειροκίνητα με την [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Εκτελεί εργασίες που ορίζονται από την εφαρμογή και σχετίζονται με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του αντικειμένου ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Η μέθοδος hasChildNodes() της διεπαφής Node επιστρέφει μια boolean τιμή που υποδεικνύει εάν ο δεδομένος `Node` έχει παιδικούς κόμβους ή όχι. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Η μέθοδος insertBefore() του interface Node εισάγει έναν κόμβο πριν από έναν κόμβο αναφοράς ως παιδί ενός καθορισμένου γονικού κόμβου. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Η μέθοδος isDefaultNamespace() του interface Node δέχεται ένα URI πακέτου ως όρισμα. Επιστρέφει μια Boolean τιμή που είναι true εάν το πακέτο είναι το προεπιλεγμένο πακέτο στον δεδομένο κόμβο και false εάν όχι. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Η μέθοδος isEqualNode() της διεπαφής `Node` ελέγχει εάν δύο κόμβοι είναι ίσοι. Δύο κόμβοι είναι ίσοι όταν έχουν τον ίδιο τύπο, χαρακτηριστικά ορισμού (για στοιχεία, αυτό θα ήταν το ID τους, ο αριθμός των παιδιών κ.λπ.), τα attributes τους ταιριάζουν, κ.λπ. Το συγκεκριμένο σύνολο δεδομένων που πρέπει να ταιριάζει διαφέρει ανάλογα με τους τύπους των κόμβων. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Η μέθοδος isSameNode() του interface Node είναι ένα παλαιότερο ψευδώνυμο για τον τελεστή αυστηρής ισότητας ===. Δηλαδή, ελέγχει αν δύο κόμβοι είναι οι ίδιοι (δηλαδή, αν αναφέρονται στο ίδιο αντικείμενο). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Η μέθοδος lookupNamespaceURI() του interface Node λαμβάνει ένα πρόθεμα ως παράμετρο και επιστρέφει το URI του πακέτου που σχετίζεται με αυτό στον δεδομένο κόμβο, εάν βρεθεί (και null εάν όχι). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Η μέθοδος lookupPrefix() του interface Node επιστρέφει μια Συμβολοσειρά που περιέχει το πρόθεμα για ένα δεδομένο URI πακέτου, εάν υπάρχει, και null εάν όχι. Όταν είναι δυνατές πολλαπλές προθέματα, επιστρέφεται το πρώτο πρόθεμα. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Τοποθετεί όλους τους κόμβους [`Text`](../text/) σε όλο το βάθος του υποδέντρου κάτω από αυτόν τον Node, συμπεριλαμβανομένων των κόμβων attribute, σε μια "κανονική" μορφή όπου μόνο η δομή (π.χ., [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), και [`entity references`](../entityreference/)) διαχωρίζει τους κόμβους [`Text`](../text/), δηλαδή δεν υπάρχουν ούτε γειτονικοί Text κόμβοι ούτε κενά Text κόμβοι. Αυτό μπορεί να χρησιμοποιηθεί για να διασφαλιστεί ότι η προβολή DOM ενός εγγράφου είναι η ίδια όπως αν αποθηκευόταν και φορτωνόταν ξανά, και είναι χρήσιμο όταν λειτουργίες (όπως αναζητήσεις XPointer [XPointer]) που εξαρτώνται από συγκεκριμένη δομή δέντρου εγγράφου πρέπει να χρησιμοποιηθούν. Εάν η παράμετρος "normalize-characters" του αντικειμένου [`DOMConfiguration`](../../com.aspose.html/configuration/) που είναι συνδεδεμένο με το [`Node.ownerDocument`](./ownerdocument/) είναι true, αυτή η μέθοδος θα κανονικοποιήσει επίσης πλήρως τους χαρακτήρες των Text κόμβων. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Η μέθοδος removeChild() του interface Node αφαιρεί ένα child node από το DOM και επιστρέφει το αφαιρεθέν node. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα event listener αφαιρεθεί από ένα event target ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Τα Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα event listener αφαιρεθεί από ένα event target ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Τα Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα event listener αφαιρεθεί από ένα event target ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Τα Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Αντικαθιστά τον παιδικό κόμβο oldChild με το newChild στη λίστα των παιδιών και επιστρέφει τον κόμβο oldChild. Εάν το newChild είναι ένα αντικείμενο [`DocumentFragment`](../documentfragment/), το oldChild αντικαθίσταται από όλα τα παιδιά του [`DocumentFragment`](../documentfragment/), τα οποία εισάγονται με την ίδια σειρά. Εάν το newChild βρίσκεται ήδη στο δέντρο, αφαιρείται πρώτα. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [ATTRIBUTE_NODE](../../com.aspose.html.dom/node/attribute_node/) | Ένα [`Attribute`](../attr/) ενός [`Element`](../element/). |
| const [CDATA_SECTION_NODE](../../com.aspose.html.dom/node/cdata_section_node/) | Ένα [`CDATASection`](../cdatasection/), όπως &lt;!CDATA[[ … ]]&gt;. |
| const [COMMENT_NODE](../../com.aspose.html.dom/node/comment_node/) | Ένας κόμβος [`Comment`](../comment/), όπως &lt;!-- … --&gt;. |
| const [DOCUMENT_FRAGMENT_NODE](../../com.aspose.html.dom/node/document_fragment_node/) | Ένας κόμβος [`DocumentFragment`](../documentfragment/). |
| const [DOCUMENT_NODE](../../com.aspose.html.dom/node/document_node/) | Ένας κόμβος [`Document`](../document/). |
| const [DOCUMENT_TYPE_NODE](../../com.aspose.html.dom/node/document_type_node/) | Ένας κόμβος [`DocumentType`](../documenttype/), όπως &lt;!DOCTYPE html&gt;. |
| const [ELEMENT_NODE](../../com.aspose.html.dom/node/element_node/) | Ένας κόμβος [`Element`](../element/) όπως &lt;p&gt; ή &lt;div&gt;. |
| const [ENTITY_NODE](../../com.aspose.html.dom/node/entity_node/) | Ένας κόμβος [`Entity`](../entity/). |
| const [ENTITY_REFERENCE_NODE](../../com.aspose.html.dom/node/entity_reference_node/) | Ένας κόμβος [`EntityReference`](../entityreference/). |
| const [NOTATION_NODE](../../com.aspose.html.dom/node/notation_node/) | Ένας κόμβος [`Notation`](../notation/). |
| const [PROCESSING_INSTRUCTION_NODE](../../com.aspose.html.dom/node/processing_instruction_node/) | Ένα [`ProcessingInstruction`](../processinginstruction/) ενός εγγράφου XML, όπως &lt;?xml-stylesheet … ?&gt;. |
| const [TEXT_NODE](../../com.aspose.html.dom/node/text_node/) | Το πραγματικό [`Text`](../text/) μέσα σε ένα [`Element`](../element/) ή ένα [`Attr`](../attr/). |

## Παρατηρήσεις

Αναφορά:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # interface-node](https://dom.spec.whatwg.org/#interface-node).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Δείτε επίσης

* class [EventTarget](../eventtarget/)
* interface [IXPathNSResolver](../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
