---
title: "Κλάση Comment"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.Comment class. Κληρονομεί από το CharacterData και αντιπροσωπεύει το περιεχόμενο ενός σχολίου, δηλαδή όλους τους χαρακτήρες μεταξύ της έναρξης"
type: docs

url: /el/java/com.aspose.html.dom/comment/
---
## Comment class

Κληρονομεί από την CharacterData και αντιπροσωπεύει το περιεχόμενο ενός σχολίου, δηλαδή όλους τους χαρακτήρες μεταξύ του αρχικού ''.

```java
public class Comment : CharacterData
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Η ιδιότητα μόνο για ανάγνωση baseURI της διεπαφής Node επιστρέφει το απόλυτο βασικό URL του εγγράφου που περιέχει τον κόμβο. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Η ιδιότητα μόνο για ανάγνωση childNodes της διεπαφής Node επιστρέφει μια ζωντανή λίστα [`NodeList`](../../com.aspose.html.collections/nodelist/) των κόμβων-παιδιών του δεδομένου στοιχείου, όπου ο πρώτος κόμβος παιδί έχει δείκτη 0. Οι κόμβοι-παιδιά περιλαμβάνουν στοιχεία, κείμενο και σχόλια. |
| [data](../../com.aspose.html.dom/characterdata/data/) { get; set; } | Τα δεδομένα χαρακτήρων του κόμβου που υλοποιεί αυτή τη διεπαφή. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Η ιδιότητα μόνο για ανάγνωση firstChild της διεπαφής [`Node`](../node/) επιστρέφει το πρώτο παιδί του κόμβου στο δέντρο, ή null εάν ο κόμβος δεν έχει παιδιά. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Η ιδιότητα μόνο για ανάγνωση lastChild της διεπαφής [`Node`](../node/) επιστρέφει το τελευταίο παιδί του κόμβου. Εάν ο γονέας του είναι ένα στοιχείο, τότε το παιδί είναι γενικά ένας κόμβος στοιχείου, ένας κόμβος κειμένου ή ένας κόμβος σχολίου. Επιστρέφει null εάν δεν υπάρχουν παιδικά στοιχεία. |
| [getLength](../../com.aspose.html.dom/characterdata/length/) Ο αριθμός των 16-bit μονάδων που είναι διαθέσιμες μέσω των δεδομένων και της μεθόδου subStringData παρακάτω. Αυτό μπορεί να έχει τιμή μηδέν, δηλαδή οι κόμβοι CharacterData μπορεί να είναι κενά. |
| [getLocalName](../../com.aspose.html.dom/node/localname/) Επιστρέφει το τοπικό μέρος του πλήρους ονόματος αυτού του κόμβου. Για κόμβους οποιουδήποτε τύπου εκτός από [`ELEMENT_NODE`](../node/element_node/) και [`ATTRIBUTE_NODE`](../node/attribute_node/) και κόμβους που δημιουργήθηκαν με μέθοδο DOM Level 1, όπως [`Document.createElement()`](../document/createelement/), αυτό είναι πάντα null. |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Η ιδιότητα μόνο για ανάγνωση Element.packageURI επιστρέφει το URI του πακέτου του στοιχείου, ή null εάν το στοιχείο δεν βρίσκεται σε πακέτο. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Η ιδιότητα μόνο για ανάγνωση nextSibling της διεπαφής [`Node`](../node/) επιστρέφει τον κόμβο που ακολουθεί αμέσως τον καθορισμένο στον γονέα του [`childNodes`](../node/childnodes/), ή επιστρέφει null εάν ο καθορισμένος κόμβος είναι το τελευταίο παιδί στο γονικό στοιχείο. |
| [getNodeName](../../com.aspose.html.dom/comment/nodename/) Το όνομα αυτού του κόμβου, ανάλογα με τον τύπο του. |
| [getNodeType](../../com.aspose.html.dom/comment/nodetype/) Ένας κώδικας που αντιπροσωπεύει τον τύπο του υποκείμενου αντικειμένου. |
| [nodeValue](../../com.aspose.html.dom/comment/nodevalue/) { get; set; } | Η τιμή αυτού του κόμβου, ανάλογα με τον τύπο του. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Η μόνο-ανάγνωση ιδιότητα ownerDocument του interface Node επιστρέφει το αντικείμενο εγγράφου υψηλότερου επιπέδου του κόμβου. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Η ιδιότητα μόνο για ανάγνωση parentElement της διεπαφής [`Node`](../node/) επιστρέφει τον γονικό [`Element`](../element/) του κόμβου DOM, ή null εάν ο κόμβος δεν έχει γονέα ή ο γονέας του δεν είναι στοιχείο DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Η μόνο-ανάγνωση ιδιότητα parentNode του interface Node επιστρέφει τον γονέα του καθορισμένου κόμβου στο δέντρο DOM. |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | Η ιδιότητα μόνο για ανάγνωση prefix επιστρέφει το πρόθεμα πακέτου του συγκεκριμένου στοιχείου, ή null εάν δεν έχει καθοριστεί πρόθεμα. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Η ιδιότητα μόνο για ανάγνωση previousSibling της διεπαφής [`Node`](../node/) επιστρέφει τον κόμβο που προηγείται αμέσως του καθορισμένου στη λίστα των [`childNodes`](../node/firstchild/) του γονέα του, ή null εάν ο καθορισμένος κόμβος είναι ο πρώτος σε αυτή τη λίστα. |
| [textContent](../../com.aspose.html.dom/comment/textcontent/) { get; set; } | Αυτό το χαρακτηριστικό επιστρέφει το κείμενο περιεχομένου αυτού του κόμβου και των απογόνων του. Όταν ορίζεται σε null, η ρύθμιση του δεν έχει καμία επίδραση. Κατά τη ρύθμιση, τυχόν παιδιά που μπορεί να έχει αυτός ο κόμβος αφαιρούνται και, εάν η νέα συμβολοσειρά δεν είναι κενή ή null, αντικαθίστανται από έναν μοναδικό κόμβο Text που περιέχει τη συμβολοσειρά στην οποία ορίστηκε αυτό το χαρακτηριστικό. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Η μέθοδος addEventListener() της διεπαφής [`EventTarget `](../eventtarget/) ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Η μέθοδος addEventListener() του interface [EventTarget ](T:com.aspose.html.dom.EventTarget) ορίζει μια συνάρτηση που θα κληθεί κάθε φορά που το καθορισμένο συμβάν παραδίδεται στον στόχο. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Η μέθοδος addEventListener() του interface [EventTarget ](T:com.aspose.html.dom.EventTarget) ορίζει μια συνάρτηση που θα κληθεί κάθε φορά που το καθορισμένο συμβάν παραδίδεται στον στόχο. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Η μέθοδος appendChild() του interface Node προσθέτει έναν κόμβο στο τέλος της λίστας των παιδιών ενός καθορισμένου γονικού κόμβου. Εάν το δοσμένο παιδί είναι αναφορά σε έναν υπάρχοντα κόμβο στο έγγραφο, η appendChild() τον μετακινεί από την τρέχουσα θέση του στη νέα θέση (δεν απαιτείται η αφαίρεση του κόμβου από τον γονικό του πριν την προσθήκη του σε κάποιον άλλο κόμβο). |
| [appendData](../../com.aspose.html.dom/characterdata/appenddata/)(String) | Προσθέτει τη String στο τέλος των δεδομένων χαρακτήρων του κόμβου. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Η μέθοδος cloneNode() του interface Node επιστρέφει ένα αντίγραφο του κόμβου στον οποίο κλήθηκε αυτή η μέθοδος. Η παράμετρός της ελέγχει αν το υποδέντρο που περιέχεται σε έναν κόμβο θα κλωνοποιηθεί επίσης ή όχι. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Η μέθοδος cloneNode() του interface Node επιστρέφει ένα αντίγραφο του κόμβου στον οποίο κλήθηκε αυτή η μέθοδος. Η παράμετρός της ελέγχει αν το υποδέντρο που περιέχεται σε έναν κόμβο θα κλωνοποιηθεί επίσης ή όχι. |
| [deleteData](../../com.aspose.html.dom/characterdata/deletedata/)(int, int) | Αφαιρεί μια περιοχή 16-bit μονάδων από τον κόμβο. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Αποστέλλει ένα Event στο καθορισμένο [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (συγχρονισμένα) ενεργοποιώντας τους επηρεαζόμενους EventListeners με τη σωστή σειρά. Οι κανονικοί κανόνες επεξεργασίας συμβάντων (συμπεριλαμβανομένου του πλαισίου σύλληψης και του προαιρετικού φάσης φουσκώματος) ισχύουν επίσης για συμβάντα που αποστέλλονται χειροκίνητα με την [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Εκτελεί εργασίες που ορίζονται από την εφαρμογή και σχετίζονται με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του αντικειμένου ECMAScript. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Η μέθοδος hasChildNodes() της διεπαφής Node επιστρέφει μια λογική τιμή που υποδεικνύει εάν το δεδομένο [`Node`](../node/) έχει παιδικούς κόμβους ή όχι. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Η μέθοδος insertBefore() του interface Node εισάγει έναν κόμβο πριν από έναν κόμβο αναφοράς ως παιδί ενός καθορισμένου γονικού κόμβου. |
| [insertData](../../com.aspose.html.dom/characterdata/insertdata/)(int, String) | Εισάγει μια String στην καθορισμένη μετατόπιση 16-bit μονάδας. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Η μέθοδος isDefaultNamespace() του interface Node δέχεται ένα URI πακέτου ως όρισμα. Επιστρέφει μια Boolean τιμή που είναι true εάν το πακέτο είναι το προεπιλεγμένο πακέτο στον δεδομένο κόμβο και false εάν όχι. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Η μέθοδος isEqualNode() της διεπαφής [`Node`](../node/) ελέγχει εάν δύο κόμβοι είναι ίσοι. Δύο κόμβοι είναι ίσοι όταν έχουν τον ίδιο τύπο, χαρακτηριστικά ορισμού (για στοιχεία, αυτό θα ήταν το ID τους, ο αριθμός των παιδιών κ.λπ.), τα χαρακτηριστικά τους ταιριάζουν, κ.ά. Το συγκεκριμένο σύνολο δεδομένων που πρέπει να ταιριάζει διαφέρει ανάλογα με τους τύπους των κόμβων. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Η μέθοδος isSameNode() του interface Node είναι ένα παλαιότερο ψευδώνυμο για τον τελεστή αυστηρής ισότητας ===. Δηλαδή, ελέγχει αν δύο κόμβοι είναι οι ίδιοι (δηλαδή, αν αναφέρονται στο ίδιο αντικείμενο). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Η μέθοδος lookupNamespaceURI() του interface Node λαμβάνει ένα πρόθεμα ως παράμετρο και επιστρέφει το URI του πακέτου που σχετίζεται με αυτό στον δεδομένο κόμβο, εάν βρεθεί (και null εάν όχι). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Η μέθοδος lookupPrefix() του interface Node επιστρέφει μια Συμβολοσειρά που περιέχει το πρόθεμα για ένα δεδομένο URI πακέτου, εάν υπάρχει, και null εάν όχι. Όταν είναι δυνατές πολλαπλές προθέματα, επιστρέφεται το πρώτο πρόθεμα. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Τοποθετεί όλους τους κόμβους [`Text`](../text/) σε πλήρη βάθος του υποδέντρου κάτω από αυτόν τον Node, συμπεριλαμβανομένων των κόμβων χαρακτηριστικών, σε μια "κανονική" μορφή όπου μόνο η δομή (π.χ., [`elements`](../element/), `comments`, [`processing instructions`](../processinginstruction/), [`CDATA sections`](../cdatasection/), και [`entity references`](../entityreference/)) διαχωρίζει τους κόμβους [`Text`](../text/), δηλαδή δεν υπάρχουν γειτονικοί κόμβοι Text ούτε κενά Text. Αυτό μπορεί να χρησιμοποιηθεί για να διασφαλιστεί ότι η προβολή DOM ενός εγγράφου είναι η ίδια όπως αν αποθηκευτεί και φορτωθεί ξανά, και είναι χρήσιμο όταν οι λειτουργίες (όπως οι αναζητήσεις XPointer [XPointer]) που εξαρτώνται από μια συγκεκριμένη δομή δέντρου εγγράφου πρέπει να χρησιμοποιηθούν. Εάν η παράμετρος "normalize-characters" του αντικειμένου [`DOMConfiguration`](../../com.aspose.html/configuration/) που είναι συνδεδεμένο με το [`Node.ownerDocument`](../node/ownerdocument/) είναι αληθής, αυτή η μέθοδος θα κανονικοποιήσει επίσης πλήρως τους χαρακτήρες των κόμβων Text. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Η μέθοδος removeChild() του interface Node αφαιρεί ένα child node από το DOM και επιστρέφει το αφαιρεθέν node. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα event listener αφαιρεθεί από ένα event target ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Τα Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα event listener αφαιρεθεί από ένα event target ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Τα Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα event listener αφαιρεθεί από ένα event target ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Τα Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Αντικαθιστά τον παιδικό κόμβο oldChild με το newChild στη λίστα των παιδιών και επιστρέφει τον κόμβο oldChild. Εάν το newChild είναι ένα αντικείμενο [`DocumentFragment`](../documentfragment/), το oldChild αντικαθίσταται από όλα τα παιδιά του [`DocumentFragment`](../documentfragment/), τα οποία εισάγονται με την ίδια σειρά. Εάν το newChild βρίσκεται ήδη στο δέντρο, αφαιρείται πρώτα. |
| [replaceData](../../com.aspose.html.dom/characterdata/replacedata/)(int, int, String) | Αντικαθιστά τους χαρακτήρες που αρχίζουν στην καθορισμένη μετατόπιση 16-bit μονάδας με τη συγκεκριμένη String. |
| [subStringData](../../com.aspose.html.dom/characterdata/subStringdata/)(int, int) | Εξάγει ένα εύρος δεδομένων από τον κόμβο. |
| [toString](../../com.aspose.html.dom/characterdata/toString/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |

### Δείτε επίσης

* class [CharacterData](../characterdata/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
