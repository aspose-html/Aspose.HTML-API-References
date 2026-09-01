---
title: "HTMLSelectElement Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.HTMLSelectElement κλάση. Το στοιχείο select επιτρέπει την επιλογή μιας επιλογής. Οι περιεχόμενες επιλογές μπορούν να προσπελαστούν άμεσα μέσω του στοιχείου select ως συλλογή. Δείτε τον ορισμό του στοιχείου SELECT στο HTML 4.01"
type: docs

url: /el/java/com.aspose.html/htmlselectelement/
---
## HTMLSelectElement class

Το στοιχείο select επιτρέπει την επιλογή μιας επιλογής. Οι περιεχόμενες επιλογές μπορούν να προσπελαστούν άμεσα μέσω του στοιχείου select ως συλλογή. Δείτε τον ορισμό του στοιχείου SELECT στο HTML 4.01.

Δείτε επίσης την [Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109).

```java
public class HTMLSelectElement : HTMLElement
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getAttributes](../../com.aspose.html.dom/element/attributes/) Ένας NamedNodeMap που περιέχει τα χαρακτηριστικά αυτού του κόμβου (αν είναι Element) ή null διαφορετικά. |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Η ιδιότητα μόνο για ανάγνωση baseURI της διεπαφής Node επιστρέφει το απόλυτο βασικό URL του εγγράφου που περιέχει τον κόμβο. |
| [getChildElementCount](../../com.aspose.html.dom/element/childelementcount/) Επιστρέφει τον τρέχοντα αριθμό των κόμβων στοιχείων που είναι παιδιά αυτού του στοιχείου. 0 εάν αυτό το στοιχείο δεν έχει κόμβους παιδία τύπου nodeType 1. |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Η ιδιότητα μόνο για ανάγνωση childNodes της διεπαφής Node επιστρέφει μια ζωντανή λίστα [`NodeList`](../../com.aspose.html.collections/nodelist/) των κόμβων-παιδιών του δεδομένου στοιχείου, όπου ο πρώτος κόμβος‑παιδί έχει δείκτη 0. Οι κόμβοι‑παιδιά περιλαμβάνουν στοιχεία, κείμενο και σχόλια. |
| [getChildren](../../com.aspose.html.dom/element/children/) Επιστρέφει τα στοιχεία-παιδιά του τρέχοντος στοιχείου. |
| [getClassList](../../com.aspose.html.dom/element/classlist/) Επιστρέφει μια ζωντανή DOMTokenList που περιέχει διακριτικά που προέρχονται από την ανάλυση του χαρακτηριστικού "class". |
[getClassName]
[setClassName] The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
[getDir]
[setDir] Specifies the base direction of directionally neutral text and the directionality of tables. See the dir attribute definition in HTML 4.01. |
[getDisabled]
[setDisabled] The control is unavailable in this context. See the disabled attribute definition in HTML 4.01. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) Η ιδιότητα μόνο για ανάγνωση firstChild της διεπαφής [`Node`](../../com.aspose.html.dom/node/) επιστρέφει το πρώτο παιδί του κόμβου στο δέντρο, ή null εάν ο κόμβος δεν έχει παιδιά. |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) Επιστρέφει τον πρώτο κόμβο-στοιχείο παιδί αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει στοιχεία-παιδιά. |
| [getForm](../../com.aspose.html/htmlselectelement/form/) Ο αριθμός των επιλογών σε αυτό το `SELECT`. |
[getId]
[setId] The element's identifier. See the id attribute definition in HTML 4.01. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
[getLang]
[setLang] Language code defined in RFC 1766. See the lang attribute definition in HTML 4.01. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) Η ιδιότητα μόνο για ανάγνωση lastChild της διεπαφής [`Node`](../../com.aspose.html.dom/node/) επιστρέφει το τελευταίο παιδί του κόμβου. Εάν ο γονέας του είναι στοιχείο, τότε το παιδί είναι γενικά ένας κόμβος στοιχείου, ένας κόμβος κειμένου ή ένας κόμβος σχολίου. Επιστρέφει null εάν δεν υπάρχουν στοιχεία-παιδιά |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) Επιστρέφει τον τελευταίο κόμβο στοιχείου παιδιού αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει στοιχεία παιδιού. |
[getLength]
[setLength] The number of options in this `SELECT`. @version DOM Level 2 |
| [getLocalName](../../com.aspose.html.dom/element/localname/) Επιστρέφει το τοπικό μέρος του πλήρους ονόματος αυτού του κόμβου. Για κόμβους οποιουδήποτε τύπου εκτός από ELEMENT_NODE και ATTRIBUTE_NODE και κόμβους που δημιουργήθηκαν με μέθοδο DOM Level 1, όπως Document.createElement(), αυτό είναι πάντα null. |
[getMultiple]
[setMultiple] If true, multiple `OPTION` elements may be selected in this `SELECT`. See the multiple attribute definition in HTML 4.01. |
[getName]
[setName] Form control or object name when submitted with a form. See the name attribute definition in HTML 4.01. |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) Το URI του πακέτου αυτού του κόμβου, ή null εάν δεν έχει οριστεί. |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) Επιστρέφει τον επόμενο αδερφό κόμβο στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει αδερφούς στοιχείου που έρχονται μετά από αυτό στο δέντρο του εγγράφου. |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) Η ιδιότητα μόνο για ανάγνωση nextSibling της διεπαφής [`Node`](../../com.aspose.html.dom/node/) επιστρέφει τον κόμβο που ακολουθεί αμέσως τον καθορισμένο στον γονέα του [`childNodes`](../../com.aspose.html.dom/node/childnodes/), ή επιστρέφει null εάν ο καθορισμένος κόμβος είναι το τελευταίο παιδί στο γονικό στοιχείο. |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) Το όνομα αυτού του κόμβου, ανάλογα με τον τύπο του. |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) Ένας κώδικας που αντιπροσωπεύει τον τύπο του υποκείμενου αντικειμένου. |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | The nodeValue property of the [`Node `](../../com.aspose.html.dom/node/)interface returns or sets the value of the current node. Η ιδιότητα nodeValue της διεπαφής [`Node`](../../com.aspose.html.dom/node/) επιστρέφει ή ορίζει την τιμή του τρέχοντος κόμβου. |
| [getOptions](../../com.aspose.html/htmlselectelement/options/) Η συλλογή των στοιχείων `OPTION` που περιέχονται σε αυτό το στοιχείο. @version DOM Level 2 |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Η ιδιότητα μόνο για ανάγνωση ownerDocument της διεπαφής Node επιστρέφει το αντικείμενο εγγράφου ανώτερου επιπέδου του κόμβου. |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) Η ιδιότητα μόνο για ανάγνωση parentElement της διεπαφής [`Node`](../../com.aspose.html.dom/node/) επιστρέφει το γονικό [`Element`](../../com.aspose.html.dom/element/) του κόμβου DOM, ή null εάν ο κόμβος είτε δεν έχει γονέα, είτε ο γονέας του δεν είναι στοιχείο DOM. |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Η ιδιότητα μόνο για ανάγνωση parentNode της διεπαφής Node επιστρέφει τον γονέα του καθορισμένου κόμβου στο δέντρο DOM. |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) Το πρόθεμα πακέτου αυτού του κόμβου, ή null εάν δεν έχει οριστεί. Όταν ορίζεται σε null, η ρύθμιση του δεν έχει καμία επίδραση. |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) Επιστρέφει τον προηγούμενο αδερφό κόμβο στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει αδερφούς στοιχείου που έρχονται πριν από αυτό στο δέντρο του εγγράφου. |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) Η ιδιότητα μόνο για ανάγνωση previousSibling της διεπαφής [`Node`](../../com.aspose.html.dom/node/) επιστρέφει τον κόμβο που προηγείται αμέσως του καθορισμένου στη λίστα [`childNodes`](../../com.aspose.html.dom/node/firstchild/) του γονέα του, ή null εάν ο καθορισμένος κόμβος είναι ο πρώτος σε αυτή τη λίστα. |
[getSelectedIndex]
[setSelectedIndex] The ordinal index of the selected option, starting from 0. The value -1 is returned if no element is selected. If multiple options are selected, the index of the first selected option is returned. |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) Επιστρέφει το shadowRoot που αποθηκεύεται σε αυτό το στοιχείο ή null εάν είναι κλειστό. |
[getSize]
[setSize] Number of visible rows. See the size attribute definition in HTML 4.01. |
| [getStyle](../../com.aspose.html/htmlelement/style/) Αντιπροσωπεύει ένα χαρακτηριστικό στυλ που επιτρέπει στον δημιουργό να εφαρμόσει άμεσα πληροφορίες στυλ σε συγκεκριμένο στοιχείο. |
[getTabIndex]
[setTabIndex] Index that represents the element's position in the tabbing order. See the tabindex attribute definition in HTML 4.01. |
| [getTagName](../../com.aspose.html.dom/element/tagname/) Το όνομα του στοιχείου. |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | This attribute returns the text content of this node and its descendants. When it is defined to be null, setting it has no effect. On setting, any possible children this node may have are removed and, if it the new String is not empty or null, replaced by a single Text node containing the String this attribute is set to. Αυτό το χαρακτηριστικό επιστρέφει το περιεχόμενο κειμένου αυτού του κόμβου και των απογόνων του. Όταν ορίζεται σε null, η ρύθμιση του δεν έχει καμία επίδραση. Κατά τη ρύθμιση, τυχόν παιδιά που μπορεί να έχει αυτός ο κόμβος αφαιρούνται και, εάν η νέα συμβολοσειρά δεν είναι κενή ή null, αντικαθίστανται από έναν μοναδικό κόμβο Text που περιέχει τη συμβολοσειρά στην οποία ορίζεται αυτό το χαρακτηριστικό. |
[getTitle]
[setTitle] The element's advisory title. See the title attribute definition in HTML 4.01. |
| [getType](../../com.aspose.html/htmlselectelement/type/) Ο τύπος αυτού του στοιχείου ελέγχου φόρμας. Αυτό είναι το String \"select-multiple\" όταν το χαρακτηριστικό multiple είναι `true` και το String \"select-one\" όταν είναι `false`. |
[getValue]
[setValue] The current form control value (i.e. the value of the currently selected option), if multiple options are selected this is the value of the first selected option. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | The addEventListener() method of the [`EventTarget `](../../com.aspose.html.dom/eventtarget/)interface sets up a function that will be called whenever the specified event is delivered to the target. Η μέθοδος addEventListener() της διεπαφής [`EventTarget`](../../com.aspose.html.dom/eventtarget/) ρυθμίζει μια συνάρτηση που θα κληθεί όποτε το καθορισμένο γεγονός παραδοθεί στον στόχο. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | Η μέθοδος addEventListener() του [EventTarget ](T:com.aspose.html.dom.EventTarget)interface ρυθμίζει μια λειτουργία που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | Η μέθοδος addEventListener() του [EventTarget ](T:com.aspose.html.dom.EventTarget)interface ρυθμίζει μια λειτουργία που θα κληθεί όποτε το καθορισμένο συμβάν παραδοθεί στον στόχο. |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | Η μέθοδος appendChild() της διεπαφής Node προσθέτει έναν κόμβο στο τέλος της λίστας των παιδιών ενός καθορισμένου γονικού κόμβου. Εάν το δοσμένο παιδί είναι αναφορά σε έναν υπάρχοντα κόμβο στο έγγραφο, η appendChild() τον μετακινεί από την τρέχουσα θέση του στη νέα θέση (δεν υπάρχει απαίτηση να αφαιρεθεί ο κόμβος από τον γονικό του πριν προσαρτηθεί σε κάποιον άλλο κόμβο). |
| [attachShadow](../../com.aspose.html.dom/element/attachshadow/)(ShadowRootMode) | Δημιουργεί σκιώδη ρίζα και την επισυνάπτει στο τρέχον στοιχείο. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | Η μέθοδος cloneNode() της διεπαφής Node επιστρέφει ένα αντίγραφο του κόμβου στον οποίο κλήθηκε αυτή η μέθοδος. Η παράμετρός της ελέγχει αν το υποδένδρο που περιέχεται σε έναν κόμβο κλωνοποιείται επίσης ή όχι. |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | Η μέθοδος cloneNode() της διεπαφής Node επιστρέφει ένα αντίγραφο του κόμβου στον οποίο κλήθηκε αυτή η μέθοδος. Η παράμετρός της ελέγχει αν το υποδένδρο που περιέχεται σε έναν κόμβο κλωνοποιείται επίσης ή όχι. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Αποστέλλει ένα Event στο καθορισμένο [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (συγχρονισμένα) καλώντας τους επηρεαζόμενους EventListeners με τη σωστή σειρά. Οι κανονικοί κανόνες επεξεργασίας συμβάντων (συμπεριλαμβανομένης της φάσης σύλληψης και της προαιρετικής φάσης διάδοσης) ισχύουν επίσης για συμβάντα που αποστέλλονται χειροκίνητα με το [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Εκτελεί εργασίες που ορίζονται από την εφαρμογή και σχετίζονται με την απελευθέρωση, την αποδέσμευση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| [getAttribute](../../com.aspose.html.dom/element/getattribute/)(String) | Ανακτά την τιμή ενός χαρακτηριστικού με βάση το όνομα. |
| [getAttributeNames](../../com.aspose.html.dom/element/getattributenames/)() | Επιστρέφει τα ονόματα των χαρακτηριστικών του στοιχείου ως έναν Πίνακα από Strings. Εάν το στοιχείο δεν έχει χαρακτηριστικά, επιστρέφει έναν κενό πίνακα. |
| [getAttributeNode](../../com.aspose.html.dom/element/getattributenode/)(String) | Ανακτά έναν κόμβο χαρακτηριστικού με βάση το όνομα. |
| [getAttributeNodeNS](../../com.aspose.html.dom/element/getattributenodens/)(String, String) | Ανακτά έναν κόμβο Attr με τοπικό όνομα και URI πακέτου. |
| [getAttributeNS](../../com.aspose.html.dom/element/getattributens/)(String, String) | Ανακτά την τιμή ενός χαρακτηριστικού με τοπικό όνομα και URI πακέτου. |
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | Επιστρέφει το αντικείμενο [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) που περιέχει όλα τα στοιχεία εντός του [`element`](../../com.aspose.html.dom/element/) που έχουν όλες τις κλάσεις που καθορίζονται ως όρισμα. |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | Επιστρέφει το αντικείμενο [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) που περιέχει όλα τα [`elements`](../../com.aspose.html.dom/element/) με ένα συγκεκριμένο όνομα ετικέτας, με τη σειρά του εγγράφου. |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | Επιστρέφει το αντικείμενο [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) που περιέχει όλα τα [`elements`](../../com.aspose.html.dom/element/) με ένα συγκεκριμένο τοπικό όνομα και συμβολοσειρά URI πακέτου, με τη σειρά του εγγράφου. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του αντικειμένου ECMAScript. |
| [hasAttribute](../../com.aspose.html.dom/element/hasattribute/)(String) | Επιστρέφει true όταν ένα χαρακτηριστικό με το δοσμένο όνομα είναι καθορισμένο σε αυτό το στοιχείο ή έχει προεπιλεγμένη τιμή, αλλιώς false. |
| [hasAttributeNS](../../com.aspose.html.dom/element/hasattributens/)(String, String) | Επιστρέφει true όταν ένα χαρακτηριστικό με το δοσμένο τοπικό όνομα και URI πακέτου είναι καθορισμένο σε αυτό το στοιχείο ή έχει προεπιλεγμένη τιμή, αλλιώς false. |
| [hasAttributes](../../com.aspose.html.dom/element/hasattributes/)() | Επιστρέφει αν αυτός ο κόμβος (αν είναι στοιχείο) έχει οποιαδήποτε χαρακτηριστικά |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Η μέθοδος hasChildNodes() της διεπαφής Node επιστρέφει μια boolean τιμή που υποδεικνύει αν ο δεδομένος [`Node`](../../com.aspose.html.dom/node/) έχει παιδικούς κόμβους ή όχι. |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | Η μέθοδος insertBefore() της διεπαφής Node εισάγει έναν κόμβο πριν από έναν κόμβο αναφοράς ως παιδί ενός καθορισμένου γονικού κόμβου. |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | Η μέθοδος isDefaultNamespace() της διεπαφής Node δέχεται ένα URI πακέτου ως όρισμα. Επιστρέφει μια boolean τιμή που είναι true εάν το πακέτο είναι το προεπιλεγμένο πακέτο στον δεδομένο κόμβο και false εάν όχι. |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | Η μέθοδος isEqualNode() της διεπαφής [`Node`](../../com.aspose.html.dom/node/) ελέγχει αν δύο κόμβοι είναι ίσοι. Δύο κόμβοι είναι ίσοι όταν έχουν τον ίδιο τύπο, χαρακτηριστικά ορισμού (για στοιχεία, αυτό θα ήταν το ID τους, ο αριθμός των παιδιών κ.λπ.), τα χαρακτηριστικά τους ταιριάζουν κ.ά. Το συγκεκριμένο σύνολο δεδομένων που πρέπει να ταιριάζει διαφέρει ανάλογα με τους τύπους των κόμβων. |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Η μέθοδος isSameNode() της διεπαφής Node είναι ένας παλαιός ψευδώνυμος για τον τελεστή === αυστηρής ισότητας. Δηλαδή, ελέγχει αν δύο κόμβοι είναι οι ίδιοι (με άλλα λόγια, αν αναφέρονται στο ίδιο αντικείμενο). |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Η μέθοδος lookupNamespaceURI() της διεπαφής Node λαμβάνει ένα πρόθεμα ως παράμετρο και επιστρέφει το URI πακέτου που σχετίζεται με αυτό στον δεδομένο κόμβο αν βρεθεί (και null αν όχι). |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Η μέθοδος lookupPrefix() της διεπαφής Node επιστρέφει μια String που περιέχει το πρόθεμα για ένα δεδομένο URI πακέτου, αν υπάρχει, και null αν όχι. Όταν είναι δυνατά πολλαπλά προθέματα, επιστρέφεται το πρώτο πρόθεμα. |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | Τοποθετεί όλους τους [`Text`](../../com.aspose.html.dom/text/) κόμβους σε όλο το βάθος του υποδέντρου κάτω από αυτόν τον Κόμβο, συμπεριλαμβανομένων των κόμβων χαρακτηριστικών, σε μια "κανονική" μορφή όπου μόνο η δομή (π.χ., [`elements`](../../com.aspose.html.dom/element/), [`comments`](../../com.aspose.html.dom/comment/), [`processing instructions`](../../com.aspose.html.dom/processinginstruction/), [`CDATA sections`](../../com.aspose.html.dom/cdatasection/), και [`entity references`](../../com.aspose.html.dom/entityreference/)) χωρίζει τους κόμβους [`Text`](../../com.aspose.html.dom/text/), δηλαδή δεν υπάρχουν γειτονικοί κόμβοι Text ούτε κενά κόμβοι Text. Αυτό μπορεί να χρησιμοποιηθεί για να διασφαλιστεί ότι η προβολή DOM ενός εγγράφου είναι η ίδια όπως αν αποθηκευτεί και ξαναφορτωθεί, και είναι χρήσιμο όταν εκτελούνται λειτουργίες (όπως αναζητήσεις XPointer [XPointer]) που εξαρτώνται από μια συγκεκριμένη δομή δέντρου εγγράφου. Εάν η παράμετρος "normalize-characters" του αντικειμένου [`DOMConfiguration`](../configuration/) που είναι συνδεδεμένο με το [`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) είναι αληθής, αυτή η μέθοδος θα κανονικοποιήσει επίσης πλήρως τους χαρακτήρες των κόμβων Text. |
| [querySelector](../../com.aspose.html.dom/element/queryselector/)(String) | Επιστρέφει το πρώτο Element στο έγγραφο, που ταιριάζει με τον selector |
| [querySelectorAll](../../com.aspose.html.dom/element/queryselectorall/)(String) | Επιστρέφει ένα NodeList από όλα τα Elements στο έγγραφο, που ταιριάζουν με τον selector |
| [remove](../../com.aspose.html.dom/element/remove/)() | Αφαιρεί αυτήν την instance. |
| [removeAttribute](../../com.aspose.html.dom/element/removeattribute/)(String) | Αφαιρεί ένα attribute με όνομα. |
| [removeAttributeNode](../../com.aspose.html.dom/element/removeattributenode/)(Attr) | Αφαιρεί το καθορισμένο attribute node. |
| [removeAttributeNS](../../com.aspose.html.dom/element/removeattributens/)(String, String) | Αφαιρεί ένα attribute με το local name και το package URI. |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Η μέθοδος removeChild() του interface Node αφαιρεί έναν child node από το DOM και επιστρέφει τον αφαιρεθέντα node. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένας αφαιρεθεί από ένα ενώ επεξεργάζεται ένα event, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένας αφαιρεθεί από ένα ενώ επεξεργάζεται ένα event, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των event listeners από το event target. Εάν ένας αφαιρεθεί από ένα ενώ επεξεργάζεται ένα event, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Οι Event Listeners δεν μπορούν ποτέ να κληθούν μετά την αφαίρεσή τους. |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | Αντικαθιστά τον child node oldChild με το newChild στη λίστα των παιδιών και επιστρέφει τον κόμβο oldChild. Εάν το newChild είναι ένα [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) αντικείμενο, το oldChild αντικαθίσταται από όλα τα παιδιά του [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/), τα οποία εισάγονται με την ίδια σειρά. Εάν το newChild βρίσκεται ήδη στο δέντρο, αφαιρείται πρώτα. |
| [setAttribute](../../com.aspose.html.dom/element/setattribute/)(String, String) | Προσθέτει ένα νέο attribute. Εάν ένα attribute με αυτό το όνομα υπάρχει ήδη στο element, η τιμή του αλλάζει ώστε να είναι η τιμή του παραμέτρου value. |
| [setAttributeNode](../../com.aspose.html.dom/element/setattributenode/)(Attr) | Προσθέτει ένα νέο attribute node. Εάν ένα attribute με αυτό το όνομα (nodeName) υπάρχει ήδη στο element, αντικαθίσταται από το νέο. |
| [setAttributeNodeNS](../../com.aspose.html.dom/element/setattributenodens/)(Attr) | Προσθέτει ένα νέο attribute. Εάν ένα attribute με αυτό το local name και αυτό το package URI υπάρχει ήδη στο element, αντικαθίσταται από το νέο. |
| [setAttributeNS](../../com.aspose.html.dom/element/setattributens/)(String, String, String) | Προσθέτει ένα νέο attribute. Εάν ένα attribute με το ίδιο local name και package URI υπάρχει ήδη στο element, το πρόθεμά του αλλάζει ώστε να είναι το πρόθεμα του qualifiedName, και η τιμή του αλλάζει ώστε να είναι η τιμή του παραμέτρου value. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String) | Εάν δεν δοθεί το force, «εναλλάσσει» το qualifiedName, αφαιρώντας το αν υπάρχει και προσθέτοντάς το αν δεν υπάρχει. Εάν το force είναι true, προσθέτει το qualifiedName. Εάν το force είναι false, αφαιρεί το qualifiedName. |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String, bool) | Εάν δεν δοθεί το force, «εναλλάσσει» το qualifiedName, αφαιρώντας το αν υπάρχει και προσθέτοντάς το αν δεν υπάρχει. Εάν το force είναι true, προσθέτει το qualifiedName. Εάν το force είναι false, αφαιρεί το qualifiedName. |
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
