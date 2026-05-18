---
title: "Κλάση HTMLBodyElement"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Κλάση com.aspose.html.HTMLBodyElement. Το σώμα του εγγράφου HTML. Αυτό το στοιχείο είναι πάντα παρόν στο API DOM ακόμη και αν οι ετικέτες δεν υπάρχουν στο πηγαίο έγγραφο. Δείτε τον ορισμό του στοιχείου BODY στο HTML 4.01"
type: docs

url: /el/java/com.aspose.html/htmlbodyelement/
---
## HTMLBodyElement class

Το σώμα του εγγράφου HTML. Αυτό το στοιχείο είναι πάντα παρόν στο API DOM, ακόμη και αν οι ετικέτες δεν υπάρχουν στο πηγαίο έγγραφο. Δείτε τον ορισμό του στοιχείου BODY στο HTML 4.01.

Δείτε επίσης την [Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109).

```java
public class HTMLBodyElement : HTMLElement
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
[getALink]
[setALink] Color of active links (after mouse-button down, but before mouse-button up). See the alink attribute definition in HTML 4.01. This attribute is deprecated in HTML 4.01. |
| [getAttributes](../../com.aspose.html.dom/element/attributes/) Ένα NamedNodeMap που περιέχει τα χαρακτηριστικά αυτού του κόμβου (αν είναι Element) ή null διαφορετικά. |
[getBackground]
[setBackground] URI [[IETF RFC 2396](http://www.ietf.org/rfc/rfc2396.txt)] of the background texture tile image. See the background attribute definition in HTML 4.01. This attribute is deprecated in HTML 4.01. |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Η ιδιότητα μόνο για ανάγνωση baseURI της διεπαφής Node επιστρέφει το απόλυτο βασικό URL του εγγράφου που περιέχει τον κόμβο. |
[getBgColor]
[setBgColor] Document background color. See the bgcolor attribute definition in HTML 4.01. This attribute is deprecated in HTML 4.01. |
| [getChildElementCount](../../com.aspose.html.dom/element/childelementcount/) Επιστρέφει τον τρέχοντα αριθμό των κόμβων στοιχείων που είναι παιδιά αυτού του στοιχείου. 0 εάν αυτό το στοιχείο δεν έχει κόμβους παιδιών τύπου nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Η ιδιότητα μόνο για ανάγνωση childNodes της διεπαφής Node επιστρέφει μια ζωντανή λίστα [`NodeList`](../../com.aspose.html.collections/nodelist/) των κόμβων-παιδιών του δεδομένου στοιχείου, όπου ο πρώτος κόμβος παιδί έχει δείκτη 0. Οι κόμβοι-παιδιά περιλαμβάνουν στοιχεία, κείμενο και σχόλια. |
| [getChildren](../../com.aspose.html.dom/element/children/) Επιστρέφει τα στοιχεία-παιδιά του τρέχοντος στοιχείου. |
| [getClassList](../../com.aspose.html.dom/element/classlist/) Επιστρέφει μια ζωντανή DOMTokenList που περιέχει διακριτικά που προέρχονται από την ανάλυση του χαρακτηριστικού \"class\". |
[getClassName]
[setClassName] The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
[getDir]
[setDir] Specifies the base direction of directionally neutral text and the directionality of tables. See the dir attribute definition in HTML 4.01. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Η ιδιότητα μόνο για ανάγνωση firstChild της διεπαφής [`Node`](../../com.aspose.html.dom/node/) επιστρέφει το πρώτο παιδί του κόμβου στο δέντρο, ή null εάν ο κόμβος δεν έχει παιδιά. |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) Επιστρέφει τον πρώτο κόμβο-παιδί στοιχείο αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει στοιχεία-παιδιά. |
[getId]
[setId] The element's identifier. See the id attribute definition in HTML 4.01. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
[getLang]
[setLang] Language code defined in RFC 1766. See the lang attribute definition in HTML 4.01. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Η ιδιότητα μόνο για ανάγνωση lastChild της διεπαφής [`Node`](../../com.aspose.html.dom/node/) επιστρέφει το τελευταίο παιδί του κόμβου. Εάν ο γονέας του είναι στοιχείο, τότε το παιδί είναι γενικά ένας κόμβος στοιχείου, ένας κόμβος κειμένου ή ένας κόμβος σχολίου. Επιστρέφει null εάν δεν υπάρχουν στοιχεία-παιδιά |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) Επιστρέφει τον τελευταίο κόμβο στοιχείου παιδιού αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει στοιχεία παιδιού. |
[getLink]
[setLink] Color of links that are not active and unvisited. See the link attribute definition in HTML 4.01. This attribute is deprecated in HTML 4.01. |
| [getLocalName](../../com.aspose.html.dom/element/localname/) Επιστρέφει το τοπικό μέρος του πλήρους ονόματος αυτού του κόμβου. Για κόμβους οποιουδήποτε τύπου εκτός από ELEMENT_NODE και ATTRIBUTE_NODE και κόμβους που δημιουργήθηκαν με μέθοδο DOM Level 1, όπως Document.createElement(), αυτό είναι πάντα null. |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) Το URI του πακέτου αυτού του κόμβου, ή null εάν δεν έχει οριστεί. |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) Επιστρέφει τον επόμενο αδελφό κόμβο στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει αδελφούς κόμβους στοιχείου που έρχονται μετά από αυτό στο δέντρο του εγγράφου. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Η μόνο-ανάγνωση ιδιότητα nextSibling του interface [`Node`](../../com.aspose.html.dom/node/) επιστρέφει τον κόμβο που ακολουθεί αμέσως τον καθορισμένο στον γονέα του [`childNodes`](../../com.aspose.html.dom/node/childnodes/), ή επιστρέφει null εάν ο καθορισμένος κόμβος είναι το τελευταίο παιδί στο γονικό στοιχείο. |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) Το όνομα αυτού του κόμβου, ανάλογα με τον τύπο του. |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) Ένας κώδικας που αντιπροσωπεύει τον τύπο του υποκείμενου αντικειμένου. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | Η ιδιότητα nodeValue του interface [`Node `](../../com.aspose.html.dom/node/) επιστρέφει ή ορίζει την τιμή του τρέχοντος κόμβου. |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Η μόνο-ανάγνωση ιδιότητα ownerDocument του interface Node επιστρέφει το αντικείμενο εγγράφου υψηλότερου επιπέδου του κόμβου. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Η μόνο-ανάγνωση ιδιότητα parentElement του interface [`Node`](../../com.aspose.html.dom/node/) επιστρέφει το γονικό [`Element`](../../com.aspose.html.dom/element/) του κόμβου DOM, ή null εάν ο κόμβος είτε δεν έχει γονέα, είτε ο γονέας του δεν είναι στοιχείο DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Η μόνο-ανάγνωση ιδιότητα parentNode του interface Node επιστρέφει τον γονέα του καθορισμένου κόμβου στο δέντρο DOM. |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) Το πρόθεμα του πακέτου αυτού του κόμβου, ή null εάν δεν έχει οριστεί. Όταν ορίζεται σε null, η ρύθμιση του δεν έχει καμία επίδραση. |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) Επιστρέφει τον προηγούμενο αδελφό κόμβο στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει αδελφούς κόμβους στοιχείου που έρχονται πριν από αυτό στο δέντρο του εγγράφου. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Η μόνο-ανάγνωση ιδιότητα previousSibling του interface [`Node`](../../com.aspose.html.dom/node/) επιστρέφει τον κόμβο που προηγείται αμέσως του καθορισμένου στη λίστα των [`childNodes`](../../com.aspose.html.dom/node/firstchild/) του γονέα του, ή null εάν ο καθορισμένος κόμβος είναι ο πρώτος σε αυτή τη λίστα. |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) Επιστρέφει το shadowRoot που αποθηκεύεται σε αυτό το στοιχείο ή null εάν είναι κλειστό. |
| [getStyle](../../com.aspose.html/htmlelement/style/) Αναπαριστά ένα χαρακτηριστικό στυλ που επιτρέπει στον δημιουργό να εφαρμόζει άμεσα πληροφορίες στυλ σε συγκεκριμένο στοιχείο. |
| [getTagName](../../com.aspose.html.dom/element/tagname/) Το όνομα του στοιχείου. |
[getText]
[setText] Document text color. See the text attribute definition in HTML 4.01. This attribute is deprecated in HTML 4.01. |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | Αυτό το χαρακτηριστικό επιστρέφει το κείμενο περιεχομένου αυτού του κόμβου και των απογόνων του. Όταν ορίζεται σε null, η ρύθμιση του δεν έχει καμία επίδραση. Κατά τη ρύθμιση, τυχόν παιδιά που μπορεί να έχει αυτός ο κόμβος αφαιρούνται και, εάν η νέα συμβολοσειρά δεν είναι κενή ή null, αντικαθίστανται από έναν μοναδικό κόμβο Text που περιέχει τη συμβολοσειρά στην οποία ορίστηκε αυτό το χαρακτηριστικό. |
[getTitle]
[setTitle] The element's advisory title. See the title attribute definition in HTML 4.01. |
[getVLink]
[setVLink] Color of links that have been visited by the user. See the vlink attribute definition in HTML 4.01. This attribute is deprecated in HTML 4.01. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | Η μέθοδος addEventListener() του interface [`EventTarget `](../../com.aspose.html.dom/eventtarget/) ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο γεγονός παραδοθεί στον στόχο. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Η μέθοδος addEventListener() του interface [EventTarget ](T:com.aspose.html.dom.EventTarget) ορίζει μια συνάρτηση που θα κληθεί κάθε φορά που το καθορισμένο συμβάν παραδίδεται στον στόχο. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Η μέθοδος addEventListener() του interface [EventTarget ](T:com.aspose.html.dom.EventTarget) ορίζει μια συνάρτηση που θα κληθεί κάθε φορά που το καθορισμένο συμβάν παραδίδεται στον στόχο. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Η μέθοδος appendChild() του interface Node προσθέτει έναν κόμβο στο τέλος της λίστας των παιδιών ενός καθορισμένου γονικού κόμβου. Εάν το δοσμένο παιδί είναι αναφορά σε έναν υπάρχοντα κόμβο στο έγγραφο, η appendChild() τον μετακινεί από την τρέχουσα θέση του στη νέα θέση (δεν απαιτείται η αφαίρεση του κόμβου από τον γονικό του πριν την προσθήκη του σε κάποιον άλλο κόμβο). |
| [attachShadow](../../com.aspose.html.dom/element/attachshadow/)(ShadowRootMode) | Δημιουργεί σκιώδη ρίζα και την συνδέει με το τρέχον στοιχείο. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Η μέθοδος cloneNode() του interface Node επιστρέφει ένα αντίγραφο του κόμβου στον οποίο κλήθηκε αυτή η μέθοδος. Η παράμετρός της ελέγχει αν το υποδέντρο που περιέχεται σε έναν κόμβο θα κλωνοποιηθεί επίσης ή όχι. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Η μέθοδος cloneNode() του interface Node επιστρέφει ένα αντίγραφο του κόμβου στον οποίο κλήθηκε αυτή η μέθοδος. Η παράμετρός της ελέγχει αν το υποδέντρο που περιέχεται σε έναν κόμβο θα κλωνοποιηθεί επίσης ή όχι. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Αποστέλλει ένα Event στο καθορισμένο [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (συγχρονισμένα) ενεργοποιώντας τους επηρεαζόμενους EventListeners με τη σωστή σειρά. Οι κανονικοί κανόνες επεξεργασίας συμβάντων (συμπεριλαμβανομένου του πλαισίου σύλληψης και του προαιρετικού φάσης φουσκώματος) ισχύουν επίσης για συμβάντα που αποστέλλονται χειροκίνητα με την [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Εκτελεί εργασίες που ορίζονται από την εφαρμογή και σχετίζονται με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| [getAttribute](../../com.aspose.html.dom/element/getattribute/)(String) | Ανακτά την τιμή ενός χαρακτηριστικού με βάση το όνομα. |
| [getAttributeNames](../../com.aspose.html.dom/element/getattributenames/)() | Επιστρέφει τα ονόματα των χαρακτηριστικών του στοιχείου ως Πίνακα (Array) από Συμβολοσειρές. Εάν το στοιχείο δεν έχει χαρακτηριστικά, επιστρέφει έναν κενό πίνακα. |
| [getAttributeNode](../../com.aspose.html.dom/element/getattributenode/)(String) | Ανακτά έναν κόμβο χαρακτηριστικού με βάση το όνομα. |
| [getAttributeNodeNS](../../com.aspose.html.dom/element/getattributenodens/)(String, String) | Ανακτά έναν κόμβο Attr με βάση το τοπικό όνομα και το URI του πακέτου. |
| [getAttributeNS](../../com.aspose.html.dom/element/getattributens/)(String, String) | Ανακτά την τιμή ενός χαρακτηριστικού με βάση το τοπικό όνομα και το URI του πακέτου. |
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | Επιστρέφει το αντικείμενο [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) που περιέχει όλα τα στοιχεία μέσα στο [`element`](../../com.aspose.html.dom/element/) που έχουν όλες τις κλάσεις που καθορίζονται στο όρισμα. |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | Επιστρέφει το αντικείμενο [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) που περιέχει όλα τα [`elements`](../../com.aspose.html.dom/element/) με ένα δεδομένο όνομα ετικέτας, με τη σειρά του εγγράφου. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | Επιστρέφει το αντικείμενο [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) που περιέχει όλα τα [`elements`](../../com.aspose.html.dom/element/) με ένα δεδομένο τοπικό όνομα και συμβολοσειρά URI πακέτου, με τη σειρά του εγγράφου. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του αντικειμένου ECMAScript. |
| [hasAttribute](../../com.aspose.html.dom/element/hasattribute/)(String) | Επιστρέφει true όταν ένα χαρακτηριστικό με το δεδομένο όνομα είναι καθορισμένο σε αυτό το στοιχείο ή έχει προεπιλεγμένη τιμή, διαφορετικά false. |
| [hasAttributeNS](../../com.aspose.html.dom/element/hasattributens/)(String, String) | Επιστρέφει true όταν ένα χαρακτηριστικό με το δεδομένο τοπικό όνομα και URI πακέτου είναι καθορισμένο σε αυτό το στοιχείο ή έχει προεπιλεγμένη τιμή, διαφορετικά false. |
| [hasAttributes](../../com.aspose.html.dom/element/hasattributes/)() | Επιστρέφει αν αυτός ο κόμβος (αν είναι στοιχείο) έχει οποιαδήποτε χαρακτηριστικά. |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Η μέθοδος hasChildNodes() του interface Node επιστρέφει μια Boolean τιμή που υποδεικνύει αν ο δεδομένος [`Node`](../../com.aspose.html.dom/node/) έχει παιδικούς κόμβους ή όχι. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Η μέθοδος insertBefore() του interface Node εισάγει έναν κόμβο πριν από έναν κόμβο αναφοράς ως παιδί ενός καθορισμένου γονικού κόμβου. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Η μέθοδος isDefaultNamespace() του interface Node δέχεται ένα URI πακέτου ως όρισμα. Επιστρέφει μια Boolean τιμή που είναι true εάν το πακέτο είναι το προεπιλεγμένο πακέτο στον δεδομένο κόμβο και false εάν όχι. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Η μέθοδος isEqualNode() του interface [`Node`](../../com.aspose.html.dom/node/) ελέγχει αν δύο κόμβοι είναι ίσοι. Δύο κόμβοι είναι ίσοι όταν έχουν τον ίδιο τύπο, χαρακτηριστικά (για στοιχεία, αυτό θα ήταν το ID τους, ο αριθμός των παιδιών κ.λπ.), τα χαρακτηριστικά τους ταιριάζουν, κ.ά. Το συγκεκριμένο σύνολο δεδομένων που πρέπει να ταιριάζει διαφέρει ανάλογα με τους τύπους των κόμβων. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Η μέθοδος isSameNode() του interface Node είναι ένα παλαιότερο ψευδώνυμο για τον τελεστή αυστηρής ισότητας ===. Δηλαδή, ελέγχει αν δύο κόμβοι είναι οι ίδιοι (δηλαδή, αν αναφέρονται στο ίδιο αντικείμενο). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Η μέθοδος lookupNamespaceURI() του interface Node λαμβάνει ένα πρόθεμα ως παράμετρο και επιστρέφει το URI του πακέτου που σχετίζεται με αυτό στον δεδομένο κόμβο, εάν βρεθεί (και null εάν όχι). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Η μέθοδος lookupPrefix() του interface Node επιστρέφει μια Συμβολοσειρά που περιέχει το πρόθεμα για ένα δεδομένο URI πακέτου, εάν υπάρχει, και null εάν όχι. Όταν είναι δυνατές πολλαπλές προθέματα, επιστρέφεται το πρώτο πρόθεμα. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Τοποθετεί όλους τους κόμβους [`Text`](../../com.aspose.html.dom/text/) σε όλο το βάθος του υποδέντρου κάτω από αυτόν τον Κόμβο, συμπεριλαμβανομένων των κόμβων χαρακτηριστικών, σε μια «κανονική» μορφή όπου μόνο η δομή (π.χ., [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), και [`entity references`](../../com.aspose.html.dom/entityreference/)) χωρίζει τους κόμβους [`Text`](../../com.aspose.html.dom/text/), δηλαδή δεν υπάρχουν ούτε γειτονικοί κόμβοι Text ούτε κενά κόμβοι Text. Αυτό μπορεί να χρησιμοποιηθεί για να διασφαλιστεί ότι η προβολή DOM ενός εγγράφου είναι η ίδια όπως θα ήταν αν αποθηκευτεί και ξαναφορτωθεί, και είναι χρήσιμο όταν εκτελούνται λειτουργίες (όπως αναζητήσεις XPointer [XPointer]) που εξαρτώνται από μια συγκεκριμένη δομή δέντρου εγγράφου. Εάν η παράμετρος «normalize-characters» του αντικειμένου [`DOMConfiguration`](../configuration/) που είναι συνδεδεμένο με το [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) είναι αληθής, αυτή η μέθοδος θα κανονικοποιήσει επίσης πλήρως τους χαρακτήρες των κόμβων Text. |
| [querySelector](../../com.aspose.html.dom/element/queryselector/)(String) | Επιστρέφει το πρώτο Element στο έγγραφο, που ταιριάζει με τον selector |
| [querySelectorAll](../../com.aspose.html.dom/element/queryselectorall/)(String) | Επιστρέφει ένα NodeList όλων των Elements στο έγγραφο, που ταιριάζουν με τον selector |
| [remove](../../com.aspose.html.dom/element/remove/)() | Αφαιρεί αυτήν την instance. |
| [removeAttribute](../../com.aspose.html.dom/element/removeattribute/)(String) | Αφαιρεί ένα attribute με όνομα. |
| [removeAttributeNode](../../com.aspose.html.dom/element/removeattributenode/)(Attr) | Αφαιρεί το καθορισμένο attribute node. |
| [removeAttributeNS](../../com.aspose.html.dom/element/removeattributens/)(String, String) | Αφαιρεί ένα attribute με το local name και το package URI. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Η μέθοδος removeChild() του interface Node αφαιρεί ένα child node από το DOM και επιστρέφει το αφαιρεθέν node. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα event listener αφαιρεθεί από ένα event target ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Τα Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα event listener αφαιρεθεί από ένα event target ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Τα Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένα event listener αφαιρεθεί από ένα event target ενώ επεξεργάζεται ένα γεγονός, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Τα Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Αντικαθιστά το child node oldChild με το newChild στη λίστα των παιδιών, και επιστρέφει το node oldChild. Εάν το newChild είναι ένα [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) αντικείμενο, το oldChild αντικαθίσταται από όλα τα παιδιά του [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/), τα οποία εισάγονται με την ίδια σειρά. Εάν το newChild βρίσκεται ήδη στο δέντρο, αφαιρείται πρώτα. |
| [setAttribute](../../com.aspose.html.dom/element/setattribute/)(String, String) | Προσθέτει ένα νέο attribute. Εάν ένα attribute με αυτό το όνομα υπάρχει ήδη στο element, η τιμή του αλλάζει ώστε να είναι η τιμή του παραμέτρου value. |
| [setAttributeNode](../../com.aspose.html.dom/element/setattributenode/)(Attr) | Προσθέτει ένα νέο attribute node. Εάν ένα attribute με αυτό το όνομα (nodeName) υπάρχει ήδη στο element, αντικαθίσταται από το νέο. |
| [setAttributeNodeNS](../../com.aspose.html.dom/element/setattributenodens/)(Attr) | Προσθέτει ένα νέο attribute. Εάν ένα attribute με αυτό το local name και αυτό το package URI υπάρχει ήδη στο element, αντικαθίσταται από το νέο. |
| [setAttributeNS](../../com.aspose.html.dom/element/setattributens/)(String, String, String) | Προσθέτει ένα νέο attribute. Εάν ένα attribute με το ίδιο local name και package URI υπάρχει ήδη στο element, το πρόθεμά του αλλάζει ώστε να είναι το πρόθεμα του qualifiedName, και η τιμή του αλλάζει ώστε να είναι η τιμή του παραμέτρου value. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String) | Εάν δεν δοθεί το force, κάνει "toggles" το qualifiedName, αφαιρώντας το εάν υπάρχει και προσθέτοντάς το εάν δεν υπάρχει. Εάν το force είναι true, προσθέτει το qualifiedName. Εάν το force είναι false, αφαιρεί το qualifiedName. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String, bool) | Εάν δεν δοθεί το force, κάνει "toggles" το qualifiedName, αφαιρώντας το εάν υπάρχει και προσθέτοντάς το εάν δεν υπάρχει. Εάν το force είναι true, προσθέτει το qualifiedName. Εάν το force είναι false, αφαιρεί το qualifiedName. |
| [toString](../../com.aspose.html.dom/node/toString/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |

## Συμβάντα

| Όνομα | Περιγραφή |
| --- | --- |
| event [OnAbort](../../com.aspose.html/htmlelement/onabort/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnAbort. |
| event [OnBlur](../../com.aspose.html/htmlelement/onblur/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnBlur. |
| event [OnCancel](../../com.aspose.html/htmlelement/oncancel/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnCancel. |
| event [OnCanplay](../../com.aspose.html/htmlelement/oncanplay/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnCanplay. |
| event [OnCanPlayThrough](../../com.aspose.html/htmlelement/oncanplaythrough/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnCanPlayThrough. |
| event [OnChange](../../com.aspose.html/htmlelement/onchange/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnChange. |
| event [OnClick](../../com.aspose.html/htmlelement/onclick/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnClick. |
| event [OnCueChange](../../com.aspose.html/htmlelement/oncuechange/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnCueChange. |
| event [OnDblClick](../../com.aspose.html/htmlelement/ondblclick/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnDblClick. |
| event [OnDurationChange](../../com.aspose.html/htmlelement/ondurationchange/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnDurationChange. |
| event [OnEmptied](../../com.aspose.html/htmlelement/onemptied/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnEmptied. |
| event [OnEnded](../../com.aspose.html/htmlelement/onended/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnEnded. |
| event [OnError](../../com.aspose.html/htmlelement/onerror/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnError. |
| event [OnFocus](../../com.aspose.html/htmlelement/onfocus/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnFocus. |
| event [OnInput](../../com.aspose.html/htmlelement/oninput/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnInput. |
| event [OnInvalid](../../com.aspose.html/htmlelement/oninvalid/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnInvalid. |
| event [OnKeyDown](../../com.aspose.html/htmlelement/onkeydown/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnKeyDown. |
| event [OnKeyPress](../../com.aspose.html/htmlelement/onkeypress/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnKeyPress. |
| event [OnKeyUp](../../com.aspose.html/htmlelement/onkeyup/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnKeyUp. |
| event [OnLoad](../../com.aspose.html/htmlelement/onload/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnLoad. |
| event [OnLoadedData](../../com.aspose.html/htmlelement/onloadeddata/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnLoadedData. |
| event [OnLoadedMetadata](../../com.aspose.html/htmlelement/onloadedmetadata/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnLoadedMetadata. |
| event [OnLoadStart](../../com.aspose.html/htmlelement/onloadstart/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnLoadStart. |
| event [OnMouseDown](../../com.aspose.html/htmlelement/onmousedown/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnMouseDown. |
| event [OnMouseEnter](../../com.aspose.html/htmlelement/onmouseenter/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnMouseEnter. |
| event [OnMouseLeave](../../com.aspose.html/htmlelement/onmouseleave/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnMouseLeave. |
| event [OnMouseMove](../../com.aspose.html/htmlelement/onmousemove/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnMouseMove. |
| event [OnMouseOut](../../com.aspose.html/htmlelement/onmouseout/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnMouseOut. |
| event [OnMouseOver](../../com.aspose.html/htmlelement/onmouseover/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnMouseOver. |
| event [OnMouseUp](../../com.aspose.html/htmlelement/onmouseup/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnMouseUp. |
| event [OnMouseWheel](../../com.aspose.html/htmlelement/onmousewheel/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnMouseWheel. |
| event [OnPause](../../com.aspose.html/htmlelement/onpause/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnPause. |
| event [OnPlay](../../com.aspose.html/htmlelement/onplay/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnPlay. |
| event [OnPlaying](../../com.aspose.html/htmlelement/onplaying/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnPlaying. |
| event [OnProgress](../../com.aspose.html/htmlelement/onprogress/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnProgress. |
| event [OnRateChange](../../com.aspose.html/htmlelement/onratechange/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnRateChange. |
| event [OnReset](../../com.aspose.html/htmlelement/onreset/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnReset. |
| event [OnResize](../../com.aspose.html/htmlelement/onresize/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnResize. |
| event [OnScroll](../../com.aspose.html/htmlelement/onscroll/) | Λαμβάνει ή ορίζει τον διαχειριστή συμβάντος για το συμβάν OnScroll. |
| event [OnSeeked](../../com.aspose.html/htmlelement/onseeked/) | Λαμβάνει ή ορίζει τον χειριστή συμβάντος για το συμβάν OnSeeked. |
| event [OnSeeking](../../com.aspose.html/htmlelement/onseeking/) | Λαμβάνει ή ορίζει τον χειριστή συμβάντος για το συμβάν OnSeeking. |
| event [OnSelect](../../com.aspose.html/htmlelement/onselect/) | Λαμβάνει ή ορίζει τον χειριστή συμβάντος για το συμβάν OnSelect. |
| event [OnShow](../../com.aspose.html/htmlelement/onshow/) | Λαμβάνει ή ορίζει τον χειριστή συμβάντος για το συμβάν OnShow. |
| event [OnStalled](../../com.aspose.html/htmlelement/onstalled/) | Λαμβάνει ή ορίζει τον χειριστή συμβάντος για το συμβάν OnStalled. |
| event [OnSubmit](../../com.aspose.html/htmlelement/onsubmit/) | Λαμβάνει ή ορίζει τον χειριστή συμβάντος για το συμβάν OnSubmit. |
| event [OnSuspend](../../com.aspose.html/htmlelement/onsuspend/) | Λαμβάνει ή ορίζει τον χειριστή συμβάντος για το συμβάν OnSuspend. |
| event [OnTimeUpdate](../../com.aspose.html/htmlelement/ontimeupdate/) | Λαμβάνει ή ορίζει τον χειριστή συμβάντος για το συμβάν OnTimeUpdate. |
| event [OnToggle](../../com.aspose.html/htmlelement/ontoggle/) | Λαμβάνει ή ορίζει τον χειριστή συμβάντος για το συμβάν OnToggle. |
| event [OnVolumeChange](../../com.aspose.html/htmlelement/onvolumechange/) | Λαμβάνει ή ορίζει τον χειριστή συμβάντος για το συμβάν OnVolumeChange. |
| event [OnWaiting](../../com.aspose.html/htmlelement/onwaiting/) | Λαμβάνει ή ορίζει τον χειριστή συμβάντος για το συμβάν OnWaiting. |

### Δείτε επίσης

* class [HTMLElement](../htmlelement/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
