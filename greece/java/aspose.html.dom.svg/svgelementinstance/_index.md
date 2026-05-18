---
title: "SVGElementInstance Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.svg.SVGElementInstance κλάση. Το αντικείμενο ρίζας κάθε δέντρου σκιάς στοιχείου χρήσης υλοποιεί τη διεπαφή SVGUseElementShadowRoot. Αυτή η διεπαφή αυτή τη στιγμή δεν ορίζει καμία επέκταση στις ιδιότητες και μεθόδους που ορίζονται για τη διεπαφή ShadowRoot και το mixin DocumentOrShadowRoot. Ωστόσο, το δέντρο που ρίζεται σε αυτόν τον κόμβο είναι εντελώς μόνο για ανάγνωση από την προοπτική των σεναρίων του δημιουργού."
type: docs

url: /el/java/com.aspose.html.dom.svg/svgelementinstance/
---
## SVGElementInstance class

Το ριζικό αντικείμενο κάθε δέντρου σκιάς στοιχείου use εφαρμόζει τη διεπαφή SVGUseElementShadowRoot. Αυτή η διεπαφή αυτή τη στιγμή δεν ορίζει καμία επέκταση στις ιδιότητες και μεθόδους που ορίζονται για τη διεπαφή ShadowRoot και το mixin DocumentOrShadowRoot. Ωστόσο, το δέντρο που ριζώνει σε αυτόν τον κόμβο είναι εντελώς μόνο για ανάγνωση από την προοπτική των σεναρίων του δημιουργού.

```java
public class SVGElementInstance : ShadowRoot
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Η ιδιότητα μόνο για ανάγνωση baseURI της διεπαφής Node επιστρέφει το απόλυτο βασικό URL του εγγράφου που περιέχει τον κόμβο. |
| [getChildElementCount](../../com.aspose.html.dom/documentfragment/childelementcount/) Επιστρέφει τον τρέχοντα αριθμό κόμβων στοιχείων που είναι παιδιά αυτού του στοιχείου. 0 εάν αυτό το στοιχείο δεν έχει κόμβους παιδία που είναι τύπου nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Η ιδιότητα μόνο για ανάγνωση childNodes της διεπαφής Node επιστρέφει μια ζωντανή λίστα [`NodeList`](../../com.aspose.html.collections/nodelist/) των κόμβων-παιδιών του δεδομένου στοιχείου, όπου ο πρώτος κόμβος παιδί έχει δείκτη 0. Οι κόμβοι-παιδιά περιλαμβάνουν στοιχεία, κείμενο και σχόλια. |
| [getChildren](../../com.aspose.html.dom/documentfragment/children/) Επιστρέφει τα παιδικά στοιχεία του τρέχοντος στοιχείου. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Η ιδιότητα μόνο για ανάγνωση firstChild της διεπαφής [`Node`](../../com.aspose.html.dom/node/) επιστρέφει το πρώτο παιδί του κόμβου στο δέντρο, ή null εάν ο κόμβος δεν έχει παιδιά. |
| [getFirstElementChild](../../com.aspose.html.dom/documentfragment/firstelementchild/) Επιστρέφει τον πρώτο κόμβο παιδικού στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει παιδικά στοιχεία. |
| [getHost](../../com.aspose.html.dom/shadowroot/host/) Host είναι ένα στοιχείο που περιέχει αυτό το ShadowRoot. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Η ιδιότητα μόνο για ανάγνωση lastChild της διεπαφής [`Node`](../../com.aspose.html.dom/node/) επιστρέφει το τελευταίο παιδί του κόμβου. Εάν ο γονέας του είναι στοιχείο, τότε το παιδί είναι γενικά ένας κόμβος στοιχείου, ένας κόμβος κειμένου ή ένας κόμβος σχολίου. Επιστρέφει null εάν δεν υπάρχουν στοιχεία-παιδιά |
| [getLastElementChild](../../com.aspose.html.dom/documentfragment/lastelementchild/) Επιστρέφει τον τελευταίο κόμβο παιδικού στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει παιδικά στοιχεία. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Επιστρέφει το τοπικό μέρος του πλήρους ονόματος αυτού του κόμβου. Για κόμβους οποιουδήποτε τύπου εκτός από [`ELEMENT_NODE`](../../com.aspose.html.dom/node/element_node/) και [`ATTRIBUTE_NODE`](../../com.aspose.html.dom/node/attribute_node/) και κόμβους που δημιουργήθηκαν με μέθοδο DOM Level 1, όπως το [`Document.createElement()`](../../com.aspose.html.dom/document/createelement/), αυτό είναι πάντα null. |
| [getMode](../../com.aspose.html.dom/shadowroot/mode/) Λειτουργία στην οποία λειτουργεί αυτό το ShadowRoot. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Η ιδιότητα μόνο για ανάγνωση Element.packageURI επιστρέφει το URI του πακέτου του στοιχείου, ή null εάν το στοιχείο δεν βρίσκεται σε πακέτο. |
| [getNextElementSibling](../../com.aspose.html.dom/documentfragment/nextelementsibling/) Επιστρέφει τον επόμενο αδερφό κόμβο στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει αδερφικούς κόμβους στοιχείων που έρχονται μετά από αυτό στο δέντρο του εγγράφου. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Η μόνο-ανάγνωση ιδιότητα nextSibling του interface [`Node`](../../com.aspose.html.dom/node/) επιστρέφει τον κόμβο που ακολουθεί αμέσως τον καθορισμένο στον γονέα του [`childNodes`](../../com.aspose.html.dom/node/childnodes/), ή επιστρέφει null εάν ο καθορισμένος κόμβος είναι το τελευταίο παιδί στο γονικό στοιχείο. |
| [getNodeName](../../com.aspose.html.dom/documentfragment/nodename/) Το όνομα αυτού του κόμβου, ανάλογα με τον τύπο του. |
| [getNodeType](../../com.aspose.html.dom/documentfragment/nodetype/) Ένας κώδικας που αντιπροσωπεύει τον τύπο του υποκείμενου αντικειμένου. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | Η ιδιότητα nodeValue του interface [`Node `](../../com.aspose.html.dom/node/) επιστρέφει ή ορίζει την τιμή του τρέχοντος κόμβου. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Η μόνο-ανάγνωση ιδιότητα ownerDocument του interface Node επιστρέφει το αντικείμενο εγγράφου υψηλότερου επιπέδου του κόμβου. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Η μόνο-ανάγνωση ιδιότητα parentElement του interface [`Node`](../../com.aspose.html.dom/node/) επιστρέφει το γονικό [`Element`](../../com.aspose.html.dom/element/) του κόμβου DOM, ή null εάν ο κόμβος είτε δεν έχει γονέα, είτε ο γονέας του δεν είναι στοιχείο DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Η μόνο-ανάγνωση ιδιότητα parentNode του interface Node επιστρέφει τον γονέα του καθορισμένου κόμβου στο δέντρο DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | Η ιδιότητα μόνο για ανάγνωση prefix επιστρέφει το πρόθεμα πακέτου του συγκεκριμένου στοιχείου, ή null εάν δεν έχει καθοριστεί πρόθεμα. |
| [getPreviousElementSibling](../../com.aspose.html.dom/documentfragment/previouselementsibling/) Επιστρέφει τον προηγούμενο αδερφό κόμβο στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει αδερφικούς κόμβους στοιχείων που έρχονται πριν από αυτό στο δέντρο του εγγράφου. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Η μόνο-ανάγνωση ιδιότητα previousSibling του interface [`Node`](../../com.aspose.html.dom/node/) επιστρέφει τον κόμβο που προηγείται αμέσως του καθορισμένου στη λίστα των [`childNodes`](../../com.aspose.html.dom/node/firstchild/) του γονέα του, ή null εάν ο καθορισμένος κόμβος είναι ο πρώτος σε αυτή τη λίστα. |
| [textContent](../../com.aspose.html.dom/documentfragment/textcontent/) { get; set; } | Αυτό το χαρακτηριστικό επιστρέφει το κείμενο περιεχομένου αυτού του κόμβου και των απογόνων του. Όταν ορίζεται σε null, η ρύθμιση του δεν έχει καμία επίδραση. Κατά τη ρύθμιση, τυχόν παιδιά που μπορεί να έχει αυτός ο κόμβος αφαιρούνται και, εάν η νέα συμβολοσειρά δεν είναι κενή ή null, αντικαθίστανται από έναν μοναδικό κόμβο Text που περιέχει τη συμβολοσειρά στην οποία ορίστηκε αυτό το χαρακτηριστικό. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Η μέθοδος addEventListener() του interface [`EventTarget `](../../com.aspose.html.dom/eventtarget/) ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο γεγονός παραδοθεί στον στόχο. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Η μέθοδος addEventListener() του interface [EventTarget ](T:com.aspose.html.dom.EventTarget) ορίζει μια συνάρτηση που θα κληθεί κάθε φορά που το καθορισμένο συμβάν παραδίδεται στον στόχο. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Η μέθοδος addEventListener() του interface [EventTarget ](T:com.aspose.html.dom.EventTarget) ορίζει μια συνάρτηση που θα κληθεί κάθε φορά που το καθορισμένο συμβάν παραδίδεται στον στόχο. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Η μέθοδος appendChild() του interface Node προσθέτει έναν κόμβο στο τέλος της λίστας των παιδιών ενός καθορισμένου γονικού κόμβου. Εάν το δοσμένο παιδί είναι αναφορά σε έναν υπάρχοντα κόμβο στο έγγραφο, η appendChild() τον μετακινεί από την τρέχουσα θέση του στη νέα θέση (δεν απαιτείται η αφαίρεση του κόμβου από τον γονικό του πριν την προσθήκη του σε κάποιον άλλο κόμβο). |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Η μέθοδος cloneNode() του interface Node επιστρέφει ένα αντίγραφο του κόμβου στον οποίο κλήθηκε αυτή η μέθοδος. Η παράμετρός της ελέγχει αν το υποδέντρο που περιέχεται σε έναν κόμβο θα κλωνοποιηθεί επίσης ή όχι. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Η μέθοδος cloneNode() του interface Node επιστρέφει ένα αντίγραφο του κόμβου στον οποίο κλήθηκε αυτή η μέθοδος. Η παράμετρός της ελέγχει αν το υποδέντρο που περιέχεται σε έναν κόμβο θα κλωνοποιηθεί επίσης ή όχι. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Αποστέλλει ένα Event στο καθορισμένο [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (συγχρονισμένα) ενεργοποιώντας τους επηρεαζόμενους EventListeners με τη σωστή σειρά. Οι κανονικοί κανόνες επεξεργασίας συμβάντων (συμπεριλαμβανομένου του πλαισίου σύλληψης και του προαιρετικού φάσης φουσκώματος) ισχύουν επίσης για συμβάντα που αποστέλλονται χειροκίνητα με την [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Εκτελεί εργασίες που ορίζονται από την εφαρμογή και σχετίζονται με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του αντικειμένου ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Η μέθοδος hasChildNodes() του interface Node επιστρέφει μια Boolean τιμή που υποδεικνύει αν ο δεδομένος [`Node`](../../com.aspose.html.dom/node/) έχει παιδικούς κόμβους ή όχι. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Η μέθοδος insertBefore() του interface Node εισάγει έναν κόμβο πριν από έναν κόμβο αναφοράς ως παιδί ενός καθορισμένου γονικού κόμβου. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Η μέθοδος isDefaultNamespace() του interface Node δέχεται ένα URI πακέτου ως όρισμα. Επιστρέφει μια Boolean τιμή που είναι true εάν το πακέτο είναι το προεπιλεγμένο πακέτο στον δεδομένο κόμβο και false εάν όχι. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Η μέθοδος isEqualNode() του interface [`Node`](../../com.aspose.html.dom/node/) ελέγχει αν δύο κόμβοι είναι ίσοι. Δύο κόμβοι είναι ίσοι όταν έχουν τον ίδιο τύπο, χαρακτηριστικά (για στοιχεία, αυτό θα ήταν το ID τους, ο αριθμός των παιδιών κ.λπ.), τα χαρακτηριστικά τους ταιριάζουν, κ.ά. Το συγκεκριμένο σύνολο δεδομένων που πρέπει να ταιριάζει διαφέρει ανάλογα με τους τύπους των κόμβων. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Η μέθοδος isSameNode() του interface Node είναι ένα παλαιότερο ψευδώνυμο για τον τελεστή αυστηρής ισότητας ===. Δηλαδή, ελέγχει αν δύο κόμβοι είναι οι ίδιοι (δηλαδή, αν αναφέρονται στο ίδιο αντικείμενο). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Η μέθοδος lookupNamespaceURI() του interface Node λαμβάνει ένα πρόθεμα ως παράμετρο και επιστρέφει το URI του πακέτου που σχετίζεται με αυτό στον δεδομένο κόμβο, εάν βρεθεί (και null εάν όχι). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Η μέθοδος lookupPrefix() του interface Node επιστρέφει μια Συμβολοσειρά που περιέχει το πρόθεμα για ένα δεδομένο URI πακέτου, εάν υπάρχει, και null εάν όχι. Όταν είναι δυνατές πολλαπλές προθέματα, επιστρέφεται το πρώτο πρόθεμα. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Τοποθετεί όλους τους κόμβους [`Text`](../../com.aspose.html.dom/text/) σε όλο το βάθος του υποδέντρου κάτω από αυτόν τον Node, συμπεριλαμβανομένων των κόμβων χαρακτηριστικών, σε μια "κανονική" μορφή όπου μόνο η δομή (π.χ., [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), και [`entity references`](../../com.aspose.html.dom/entityreference/)) διαχωρίζει τους κόμβους [`Text`](../../com.aspose.html.dom/text/), δηλαδή δεν υπάρχουν ούτε διαδοχικοί κόμβοι Text ούτε κενά κόμβοι Text. Αυτό μπορεί να χρησιμοποιηθεί για να διασφαλιστεί ότι η προβολή DOM ενός εγγράφου είναι η ίδια όπως αν αποθηκευόταν και φορτωνόταν ξανά, και είναι χρήσιμο όταν λειτουργίες (όπως αναζητήσεις XPointer [XPointer]) που εξαρτώνται από μια συγκεκριμένη δομή δέντρου εγγράφου πρέπει να χρησιμοποιηθούν. Εάν η παράμετρος "normalize-characters" του αντικειμένου [`DOMConfiguration`](../../com.aspose.html/configuration/) που είναι συνδεδεμένο με το [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) είναι true, αυτή η μέθοδος θα κανονικοποιήσει επίσης πλήρως τους χαρακτήρες των κόμβων Text. |
| [querySelector](../../com.aspose.html.dom/documentfragment/queryselector/)(String) | Επιστρέφει το πρώτο Element στο έγγραφο, που ταιριάζει με τον selector |
| [querySelectorAll](../../com.aspose.html.dom/documentfragment/queryselectorall/)(String) | Επιστρέφει ένα NodeList όλων των Elements στο έγγραφο, που ταιριάζουν με τον selector |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Η μέθοδος removeChild() του interface Node αφαιρεί ένα child node από το DOM και επιστρέφει το αφαιρεθέν node. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα event listener αφαιρεθεί από ένα event target ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Τα Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα event listener αφαιρεθεί από ένα event target ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Τα Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα event listener αφαιρεθεί από ένα event target ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Τα Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Αντικαθιστά το child node oldChild με το newChild στη λίστα των παιδιών, και επιστρέφει το node oldChild. Εάν το newChild είναι ένα [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) αντικείμενο, το oldChild αντικαθίσταται από όλα τα παιδιά του [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/), τα οποία εισάγονται με την ίδια σειρά. Εάν το newChild βρίσκεται ήδη στο δέντρο, αφαιρείται πρώτα. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |

### Δείτε επίσης

* class [ShadowRoot](../../com.aspose.html.dom/shadowroot/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)
