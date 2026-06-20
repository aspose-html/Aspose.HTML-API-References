---
title: "Node Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.Node κλάση. Η διεπαφή Node είναι ο κύριος τύπος δεδομένων για ολόκληρο το Document Object Model. Αντιπροσωπεύει έναν μοναδικό κόμβο στο δέντρο του εγγράφου. Ενώ όλα τα αντικείμενα που υλοποιούν τη διεπαφή Node εκθέτουν μεθόδους για τη διαχείριση παιδιών, δεν όλα τα αντικείμενα που υλοποιούν τη διεπαφή Node μπορεί να έχουν παιδιά. Για παράδειγμα, οι κόμβοι Text μπορεί να μην έχουν παιδιά και η προσθήκη παιδιών σε τέτοιους κόμβους προκαλεί την εμφάνιση μιας DOMException."
type: docs

url: /el/java/com.aspose.html.dom/node/
---
## Node class

Η διεπαφή Node είναι ο κύριος τύπος δεδομένων για ολόκληρο το Document Object Model. Αντιπροσωπεύει έναν μοναδικό κόμβο στο δέντρο του εγγράφου. Ενώ όλα τα αντικείμενα που υλοποιούν τη διεπαφή Node εκθέτουν μεθόδους για τη διαχείριση παιδιών, δεν όλα τα αντικείμενα που υλοποιούν τη διεπαφή Node μπορεί να έχουν παιδιά. Για παράδειγμα, οι κόμβοι [`Text`](../text/) μπορεί να μην έχουν παιδιά, και η προσθήκη παιδιών σε τέτοιους κόμβους οδηγεί σε μια [`DOMException`](../domexception/) που εγείρεται.

Τα χαρακτηριστικά [`nodeName`](./nodename/), [`nodeValue`](./nodevalue/) και attributes περιλαμβάνονται ως μηχανισμός για την πρόσβαση σε πληροφορίες κόμβου χωρίς να γίνεται μετατροπή σε συγκεκριμένη παράγωγη διεπαφή. Σε περιπτώσεις όπου δεν υπάρχει προφανής αντιστοίχιση αυτών των χαρακτηριστικών για έναν συγκεκριμένο [`nodeType`](./nodetype/) (π.χ., nodeValue για ένα [`Element`](../element/) ή attributes για ένα [`Comment`](../comment/)), αυτό επιστρέφει null. Σημειώστε ότι οι εξειδικευμένες διεπαφές μπορεί να περιέχουν πρόσθετους και πιο βολικούς μηχανισμούς για την ανάκτηση και ορισμό των σχετικών πληροφοριών.

```java
public abstract class Node : EventTarget, IXPathNSResolver
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Η ιδιότητα μόνο για ανάγνωση baseURI της διεπαφής Node επιστρέφει το απόλυτο βασικό URL του εγγράφου που περιέχει τον κόμβο. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Η ιδιότητα μόνο για ανάγνωση childNodes της διεπαφής Node επιστρέφει μια ζωντανή λίστα [`NodeList`](../../com.aspose.html.collections/nodelist/) των κόμβων-παιδιών του δεδομένου στοιχείου, όπου ο πρώτος κόμβος‑παιδί έχει δείκτη 0. Οι κόμβοι‑παιδιά περιλαμβάνουν στοιχεία, κείμενο και σχόλια. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Η ιδιότητα firstChild μόνο για ανάγνωση της διεπαφής `Node` επιστρέφει το πρώτο παιδί του κόμβου στο δέντρο, ή null εάν ο κόμβος δεν έχει παιδιά. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Η ιδιότητα lastChild μόνο για ανάγνωση της διεπαφής `Node` επιστρέφει το τελευταίο παιδί του κόμβου. Εάν ο γονέας του είναι ένα στοιχείο, τότε το παιδί είναι γενικά ένας κόμβος στοιχείου, ένας κόμβος κειμένου ή ένας κόμβος σχολίου. Επιστρέφει null εάν δεν υπάρχουν στοιχεία παιδία. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Επιστρέφει το τοπικό μέρος του πλήρους ονόματος αυτού του κόμβου. Για κόμβους οποιουδήποτε τύπου εκτός από [`ELEMENT_NODE`](./element_node/) και [`ATTRIBUTE_NODE`](./attribute_node/) και κόμβους που δημιουργήθηκαν με μέθοδο DOM Level 1, όπως [`Document.createElement()`](../document/createelement/), αυτό είναι πάντα null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Η ιδιότητα μόνο για ανάγνωση Element.packageURI επιστρέφει το URI του πακέτου του στοιχείου, ή null εάν το στοιχείο δεν βρίσκεται σε πακέτο. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Η ιδιότητα nextSibling μόνο για ανάγνωση της διεπαφής `Node` επιστρέφει τον κόμβο που ακολουθεί αμέσως τον καθορισμένο στον γονέα του [`childNodes`](./childnodes/), ή επιστρέφει null εάν ο καθορισμένος κόμβος είναι το τελευταίο παιδί στο γονικό στοιχείο. |
| abstract [getNodeName](../../com.aspose.html.dom/node/nodename/) Η ιδιότητα nodeName μόνο για ανάγνωση του Node επιστρέφει το όνομα του τρέχοντος κόμβου ως String. |
| abstract [getNodeType](../../com.aspose.html.dom/node/nodetype/) Ένας κώδικας που αντιπροσωπεύει τον τύπο του υποκείμενου αντικειμένου. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | Η ιδιότητα nodeValue της διεπαφής `Node `επιστρέφει ή ορίζει την τιμή του τρέχοντος κόμβου. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Η ιδιότητα μόνο για ανάγνωση ownerDocument της διεπαφής Node επιστρέφει το αντικείμενο εγγράφου ανώτερου επιπέδου του κόμβου. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Η ιδιότητα parentElement μόνο για ανάγνωση της διεπαφής `Node` επιστρέφει τον γονικό [`Element`](../element/) του κόμβου DOM, ή null εάν ο κόμβος είτε δεν έχει γονέα, είτε ο γονέας του δεν είναι στοιχείο DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Η ιδιότητα μόνο για ανάγνωση parentNode της διεπαφής Node επιστρέφει τον γονέα του καθορισμένου κόμβου στο δέντρο DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | Η ιδιότητα μόνο για ανάγνωση prefix επιστρέφει το πρόθεμα πακέτου του συγκεκριμένου στοιχείου, ή null εάν δεν έχει καθοριστεί πρόθεμα. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Η ιδιότητα previousSibling μόνο για ανάγνωση της διεπαφής `Node` επιστρέφει τον κόμβο που προηγείται αμέσως του καθορισμένου στον γονέα του [`childNodes`](./firstchild/) λίστα, ή null εάν ο καθορισμένος κόμβος είναι ο πρώτος σε αυτή τη λίστα. |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | Η ιδιότητα textContent της διεπαφής `Node` αντιπροσωπεύει το κείμενο περιεχομένου του κόμβου και των απογόνων του. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Η μέθοδος addEventListener() της διεπαφής [`EventTarget `](../eventtarget/) ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο γεγονός παραδοθεί στο στόχο. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Η μέθοδος addEventListener() του [EventTarget ](T:com.aspose.html.dom.EventTarget)interface ρυθμίζει μια λειτουργία που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Η μέθοδος addEventListener() του [EventTarget ](T:com.aspose.html.dom.EventTarget)interface ρυθμίζει μια λειτουργία που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Η μέθοδος appendChild() της διεπαφής Node προσθέτει έναν κόμβο στο τέλος της λίστας των παιδιών ενός καθορισμένου γονικού κόμβου. Εάν το δοσμένο παιδί είναι αναφορά σε έναν υπάρχοντα κόμβο στο έγγραφο, η appendChild() τον μετακινεί από την τρέχουσα θέση του στη νέα θέση (δεν υπάρχει απαίτηση να αφαιρεθεί ο κόμβος από τον γονικό του πριν προσαρτηθεί σε κάποιον άλλο κόμβο). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode)() | Η μέθοδος cloneNode() της διεπαφής Node επιστρέφει ένα αντίγραφο του κόμβου στον οποίο κλήθηκε αυτή η μέθοδος. Η παράμετρός της ελέγχει αν το υποδένδρο που περιέχεται σε έναν κόμβο κλωνοποιείται επίσης ή όχι. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode_1)(bool) | Η μέθοδος cloneNode() της διεπαφής Node επιστρέφει ένα αντίγραφο του κόμβου στον οποίο κλήθηκε αυτή η μέθοδος. Η παράμετρός της ελέγχει αν το υποδένδρο που περιέχεται σε έναν κόμβο κλωνοποιείται επίσης ή όχι. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Αποστέλλει ένα Event στο καθορισμένο [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (συγχρονισμένα) καλώντας τους επηρεαζόμενους EventListeners με τη σωστή σειρά. Οι κανονικοί κανόνες επεξεργασίας συμβάντων (συμπεριλαμβανομένης της φάσης σύλληψης και της προαιρετικής φάσης διάδοσης) ισχύουν επίσης για συμβάντα που αποστέλλονται χειροκίνητα με το [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Εκτελεί εργασίες που ορίζονται από την εφαρμογή και σχετίζονται με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του αντικειμένου ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Η μέθοδος hasChildNodes() της διεπαφής Node επιστρέφει μια boolean τιμή που υποδεικνύει εάν ο δεδομένος `Node` έχει παιδικούς κόμβους ή όχι. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Η μέθοδος insertBefore() της διεπαφής Node εισάγει έναν κόμβο πριν από έναν κόμβο αναφοράς ως παιδί ενός καθορισμένου γονικού κόμβου. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Η μέθοδος isDefaultNamespace() της διεπαφής Node δέχεται ένα URI πακέτου ως όρισμα. Επιστρέφει μια boolean τιμή που είναι true εάν το πακέτο είναι το προεπιλεγμένο πακέτο στον δεδομένο κόμβο και false εάν όχι. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Η μέθοδος isEqualNode() της διεπαφής `Node` ελέγχει εάν δύο κόμβοι είναι ίσοι. Δύο κόμβοι είναι ίσοι όταν έχουν τον ίδιο τύπο, χαρακτηριστικά ορισμού (για στοιχεία, αυτό θα ήταν το ID τους, ο αριθμός των παιδιών κ.λπ.), τα attributes τους ταιριάζουν, κ.λπ. Το συγκεκριμένο σύνολο δεδομένων που πρέπει να ταιριάζει διαφέρει ανάλογα με τους τύπους των κόμβων. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Η μέθοδος isSameNode() της διεπαφής Node είναι ένας παλαιός ψευδώνυμος για τον τελεστή === αυστηρής ισότητας. Δηλαδή, ελέγχει αν δύο κόμβοι είναι οι ίδιοι (με άλλα λόγια, αν αναφέρονται στο ίδιο αντικείμενο). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Η μέθοδος lookupNamespaceURI() της διεπαφής Node λαμβάνει ένα πρόθεμα ως παράμετρο και επιστρέφει το URI πακέτου που σχετίζεται με αυτό στον δεδομένο κόμβο αν βρεθεί (και null αν όχι). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Η μέθοδος lookupPrefix() της διεπαφής Node επιστρέφει μια String που περιέχει το πρόθεμα για ένα δεδομένο URI πακέτου, αν υπάρχει, και null αν όχι. Όταν είναι δυνατά πολλαπλά προθέματα, επιστρέφεται το πρώτο πρόθεμα. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Τοποθετεί όλους τους κόμβους [`Text`](../text/) σε πλήρη βάθος του υποδέντρου κάτω από αυτόν τον Node, συμπεριλαμβανομένων των κόμβων attribute, σε μια «κανονική» μορφή όπου μόνο η δομή (π.χ., [`elements`](../element/), [`comments`](../comment/), [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), και [`entity references`](../entityreference/)) διαχωρίζει τους κόμβους [`Text`](../text/), δηλαδή δεν υπάρχουν ούτε γειτονικοί Text κόμβοι ούτε κενά Text κόμβοι. Αυτό μπορεί να χρησιμοποιηθεί για να διασφαλιστεί ότι η προβολή DOM ενός εγγράφου είναι η ίδια όπως αν αποθηκευόταν και φορτωνόταν ξανά, και είναι χρήσιμο όταν λειτουργίες (όπως αναζητήσεις XPointer [XPointer]) που εξαρτώνται από μια συγκεκριμένη δομή δέντρου εγγράφου πρέπει να χρησιμοποιηθούν. Εάν η παράμετρος «normalize-characters» του αντικειμένου [`DOMConfiguration`](../../com.aspose.html/configuration/) που είναι συνημμένο στο [`Node.ownerDocument`](./ownerdocument/) είναι true, αυτή η μέθοδος θα κανονικοποιήσει επίσης πλήρως τους χαρακτήρες των Text κόμβων. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Η μέθοδος removeChild() του interface Node αφαιρεί έναν child node από το DOM και επιστρέφει τον αφαιρεθέντα node. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένας αφαιρεθεί από ένα ενώ επεξεργάζεται ένα event, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένας αφαιρεθεί από ένα ενώ επεξεργάζεται ένα event, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένας αφαιρεθεί από ένα ενώ επεξεργάζεται ένα event, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Αντικαθιστά τον παιδικό κόμβο oldChild με το newChild στη λίστα των παιδιών και επιστρέφει τον κόμβο oldChild. Εάν το newChild είναι ένα αντικείμενο [`DocumentFragment`](../documentfragment/), το oldChild αντικαθίσταται από όλα τα παιδιά του [`DocumentFragment`](../documentfragment/) που εισάγονται με την ίδια σειρά. Εάν το newChild είναι ήδη στο δέντρο, αφαιρείται πρώτα. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [ATTRIBUTE_NODE](../../com.aspose.html.dom/node/attribute_node/) | Ένα [`Attribute`](../attr/) ενός [`Element`](../element/). |
| const [CDATA_SECTION_NODE](../../com.aspose.html.dom/node/cdata_section_node/) | Ένα [`CDATASection`](../cdatasection/), όπως &lt;!CDATA[[ … ]]&gt;. |
| const [COMMENT_NODE](../../com.aspose.html.dom/node/comment_node/) | Ένας [`Comment`](../comment/) κόμβος, όπως &lt;!-- … --&gt;. |
| const [DOCUMENT_FRAGMENT_NODE](../../com.aspose.html.dom/node/document_fragment_node/) | Ένας [`DocumentFragment`](../documentfragment/) κόμβος. |
| const [DOCUMENT_NODE](../../com.aspose.html.dom/node/document_node/) | Ένας [`Document`](../document/) κόμβος. |
| const [DOCUMENT_TYPE_NODE](../../com.aspose.html.dom/node/document_type_node/) | Ένας [`DocumentType`](../documenttype/) κόμβος, όπως &lt;!DOCTYPE html&gt;. |
| const [ELEMENT_NODE](../../com.aspose.html.dom/node/element_node/) | Ένα [`Element`](../element/) κόμβος όπως &lt;p&gt; ή &lt;div&gt;. |
| const [ENTITY_NODE](../../com.aspose.html.dom/node/entity_node/) | Ένας [`Entity`](../entity/) κόμβος. |
| const [ENTITY_REFERENCE_NODE](../../com.aspose.html.dom/node/entity_reference_node/) | Ένας [`EntityReference`](../entityreference/) κόμβος. |
| const [NOTATION_NODE](../../com.aspose.html.dom/node/notation_node/) | Ένας [`Notation`](../notation/) κόμβος |
| const [PROCESSING_INSTRUCTION_NODE](../../com.aspose.html.dom/node/processing_instruction_node/) | Μία [`ProcessingInstruction`](../processinginstruction/) ενός εγγράφου XML, όπως &lt;?xml-stylesheet … ?&gt;. |
| const [TEXT_NODE](../../com.aspose.html.dom/node/text_node/) | Το πραγματικό [`Text`](../text/) μέσα σε ένα [`Element`](../element/) ή [`Attr`](../attr/). |

## Παρατηρήσεις

Αναφορά:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # interface-node](https://dom.spec.whatwg.org/#interface-node).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Δείτε επίσης

* class [EventTarget](../eventtarget/)
* interface [IXPathNSResolver](../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
