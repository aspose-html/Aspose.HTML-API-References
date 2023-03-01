---
title: Class Document
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Dom.Document τάξη. Το Έγγραφο αντιπροσωπεύει ολόκληρο το έγγραφο HTML XML ή SVG. Εννοιολογικά είναι η ρίζα του δέντρου εγγράφου και παρέχει την κύρια πρόσβαση στα δεδομένα του εγγράφου.
type: docs
weight: 660
url: /el/net/aspose.html.dom/document/
---
## Document class

Το Έγγραφο αντιπροσωπεύει ολόκληρο το έγγραφο HTML, XML ή SVG. Εννοιολογικά, είναι η ρίζα του δέντρου εγγράφου και παρέχει την κύρια πρόσβαση στα δεδομένα του εγγράφου.

```csharp
public class Document : Node, IDocumentEvent, IDocumentStyle, IDocumentTraversal, 
    IGlobalEventHandlers, INonElementParentNode, IParentNode, IXPathEvaluator
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| virtual [Attributes](../../aspose.html.dom/node/attributes/) { get; } | Ένας NamedNodeMap που περιέχει τα χαρακτηριστικά αυτού του κόμβου (εάν είναι Στοιχείο) ή αλλιώς null. |
| override [BaseURI](../../aspose.html.dom/document/baseuri/) { get; } | Το απόλυτο βασικό URI αυτού του κόμβου ή μηδενικό εάν η υλοποίηση δεν ήταν σε θέση να αποκτήσει ένα απόλυτο URI. |
| [CharacterSet](../../aspose.html.dom/document/characterset/) { get; } | Λαμβάνει την κωδικοποίηση του εγγράφου. |
| [Charset](../../aspose.html.dom/document/charset/) { get; } | Λαμβάνει την κωδικοποίηση του εγγράφου. |
| [ChildElementCount](../../aspose.html.dom/document/childelementcount/) { get; } | Επιστρέφει τον τρέχοντα αριθμό κόμβων στοιχείων που είναι παιδιά αυτού του στοιχείου. 0 εάν αυτό το στοιχείο δεν έχει θυγατρικούς κόμβους που είναι τύπου node 1. |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | Μια λίστα κόμβων που περιέχει όλα τα παιδιά αυτού του κόμβου. Εάν δεν υπάρχουν παιδιά, αυτή είναι μια NodeList που δεν περιέχει κόμβους.. |
| [Children](../../aspose.html.dom/document/children/) { get; } | Επιστρέφει τα θυγατρικά στοιχεία. |
| [ContentType](../../aspose.html.dom/document/contenttype/) { get; } | Λαμβάνει τον τύπο περιεχομένου του εγγράφου. |
| [Context](../../aspose.html.dom/document/context/) { get; } | Λαμβάνει το τρέχον περιβάλλον περιήγησης. |
| [DefaultView](../../aspose.html.dom/document/defaultview/) { get; } | Το χαρακτηριστικό defaultView IDL της διεπαφής Document, κατά τη λήψη, πρέπει να επιστρέψει το αντικείμενο WindowProxy του περιβάλλοντος περιήγησης αυτού του εγγράφου, εάν αυτό το Έγγραφο έχει συσχετισμένο περιβάλλον περιήγησης, ή μηδενικό διαφορετικά. |
| [Doctype](../../aspose.html.dom/document/doctype/) { get; } | Η δήλωση τύπου εγγράφου που σχετίζεται με αυτό το έγγραφο. |
| [DocumentElement](../../aspose.html.dom/document/documentelement/) { get; } | Αυτό είναι ένα χαρακτηριστικό ευκολίας που επιτρέπει την άμεση πρόσβαση στον θυγατρικό κόμβο που είναι το στοιχείο εγγράφου του εγγράφου. |
| [DocumentURI](../../aspose.html.dom/document/documenturi/) { get; } | Η θέση του εγγράφου ή μηδενική εάν δεν έχει καθοριστεί ή εάν το Έγγραφο δημιουργήθηκε χρησιμοποιώντας το DOMImplementation.createDocument. |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | Το πρώτο παιδί αυτού του κόμβου. Εάν δεν υπάρχει τέτοιος κόμβος, αυτός επιστρέφει null. |
| [FirstElementChild](../../aspose.html.dom/document/firstelementchild/) { get; } | Επιστρέφει τον πρώτο κόμβο θυγατρικού στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει θυγατρικά στοιχεία. |
| [Implementation](../../aspose.html.dom/document/implementation/) { get; } | Το αντικείμενο DOMImplementation που χειρίζεται αυτό το έγγραφο. |
| [InputEncoding](../../aspose.html.dom/document/inputencoding/) { get; } | Λαμβάνει την κωδικοποίηση του εγγράφου. |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | Το τελευταίο παιδί αυτού του κόμβου. Εάν δεν υπάρχει τέτοιος κόμβος, αυτός επιστρέφει null. |
| [LastElementChild](../../aspose.html.dom/document/lastelementchild/) { get; } | Επιστρέφει τον τελευταίο κόμβο θυγατρικού στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει θυγατρικά στοιχεία. |
| virtual [LocalName](../../aspose.html.dom/node/localname/) { get; } | Επιστρέφει το τοπικό τμήμα του αναγνωρισμένου ονόματος αυτού του κόμβου. Για κόμβους οποιουδήποτε τύπου εκτός από ELEMENT_NODE και ATTRIBUTE_NODE και κόμβους που έχουν δημιουργηθεί με μια μέθοδο DOM Level 1, όπως Document.createElement(), αυτό είναι πάντα null. |
| [Location](../../aspose.html.dom/document/location/) { get; } | Η θέση του εγγράφου. |
| virtual [NamespaceURI](../../aspose.html.dom/node/namespaceuri/) { get; } | Το URI χώρου ονομάτων αυτού του κόμβου ή μηδενικό εάν δεν έχει καθοριστεί. |
| [NextElementSibling](../../aspose.html.dom/document/nextelementsibling/) { get; } | Επιστρέφει τον επόμενο κόμβο αδελφικού στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει κανένα στοιχείο αδελφούς κόμβους που έρχονται μετά από αυτό στο δέντρο εγγράφων. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | Ο κόμβος αμέσως μετά από αυτόν τον κόμβο. Εάν δεν υπάρχει τέτοιος κόμβος, αυτός επιστρέφει null. |
| override [NodeName](../../aspose.html.dom/document/nodename/) { get; } | Το όνομα αυτού του κόμβου, ανάλογα με τον τύπο του. |
| override [NodeType](../../aspose.html.dom/document/nodetype/) { get; } | Ένας κωδικός που αντιπροσωπεύει τον τύπο του υποκείμενου αντικειμένου. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | Η τιμή αυτού του κόμβου, ανάλογα με τον τύπο του. |
| [Origin](../../aspose.html.dom/document/origin/) { get; } | Λαμβάνει την προέλευση του εγγράφου. |
| override [OwnerDocument](../../aspose.html.dom/document/ownerdocument/) { get; } | Λαμβάνει το έγγραφο κατόχου. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | Παίρνει τον γονέα[`Element`](../element/) αυτού του κόμβου. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | Ο γονέας αυτού του κόμβου. Όλοι οι κόμβοι, εκτός από τα Attr, Document, DocumentFragment, Entity και Notation, μπορεί να έχουν γονέα. Ωστόσο, εάν ένας κόμβος έχει μόλις δημιουργηθεί και δεν έχει προστεθεί ακόμη στο δέντρο, ή εάν έχει αφαιρεθεί από το δέντρο, αυτό είναι null. |
| virtual [Prefix](../../aspose.html.dom/node/prefix/) { get; set; } | Το πρόθεμα χώρου ονομάτων αυτού του κόμβου ή μηδενικό εάν δεν έχει καθοριστεί. Όταν ορίζεται ότι είναι null, η ρύθμιση του δεν έχει effect |
| [PreviousElementSibling](../../aspose.html.dom/document/previouselementsibling/) { get; } | Επιστρέφει τον προηγούμενο κόμβο αδελφικού στοιχείου αυτού του στοιχείου. null εάν αυτό το στοιχείο δεν έχει κόμβους αδερφού στοιχείου που βρίσκονται πριν από αυτό στο δέντρο εγγράφων. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | Ο κόμβος αμέσως πριν από αυτόν τον κόμβο. Εάν δεν υπάρχει τέτοιος κόμβος, αυτός επιστρέφει null. |
| [ReadyState](../../aspose.html.dom/document/readystate/) { get; } | Επιστρέφει την ετοιμότητα του εγγράφου. Η "φόρτωση" κατά τη φόρτωση του εγγράφου, "διαδραστική" μόλις ολοκληρωθεί η ανάλυση αλλά εξακολουθεί να φορτώνει υπο-πόρους και "ολοκληρώνεται" μόλις φορτωθεί. |
| [StrictErrorChecking](../../aspose.html.dom/document/stricterrorchecking/) { get; set; } | Χαρακτηριστικό που προσδιορίζει εάν επιβάλλεται έλεγχος σφαλμάτων ή όχι. Όταν οριστεί σε false, η υλοποίηση είναι ελεύθερη να μην δοκιμάζει κάθε πιθανή περίπτωση σφάλματος που κανονικά ορίζεται σε λειτουργίες DOM και να μην δημιουργεί καμία εξαίρεση DOME στις λειτουργίες DOM ή να αναφέρει σφάλματα κατά τη χρήση της Document.normalizeDocument(). Σε περίπτωση λάθους, η συμπεριφορά είναι απροσδιόριστη. Αυτό το χαρακτηριστικό είναι αληθές από προεπιλογή. |
| [StyleSheets](../../aspose.html.dom/document/stylesheets/) { get; } | Μια λίστα που περιέχει όλα τα φύλλα στυλ ρητά συνδεδεμένα ή ενσωματωμένα σε ένα έγγραφο. Για έγγραφα HTML, αυτό περιλαμβάνει εξωτερικά φύλλα στυλ, που περιλαμβάνονται μέσω του στοιχείου HTML LINK και ενσωματωμένα στοιχεία STYLE. |
| virtual [TextContent](../../aspose.html.dom/node/textcontent/) { get; set; } | Αυτό το χαρακτηριστικό επιστρέφει το περιεχόμενο κειμένου αυτού του κόμβου και των απογόνων του. Όταν ορίζεται ότι είναι μηδενικό, η ρύθμιση του δεν έχει αποτέλεσμα. Κατά τη ρύθμιση, τυχόν παιδιά που μπορεί να έχει αυτός ο κόμβος αφαιρούνται και, εάν η νέα συμβολοσειρά δεν είναι κενή ή μηδενική, αντικαθίστανται από έναν μόνο κόμβο κειμένου που περιέχει τη συμβολοσειρά στην οποία έχει οριστεί αυτό το χαρακτηριστικό. |
| [XmlStandalone](../../aspose.html.dom/document/xmlstandalone/) { get; set; } | Ένα χαρακτηριστικό που προσδιορίζει, ως μέρος της δήλωσης XML, εάν αυτό το έγγραφο είναι αυτόνομο. Αυτό είναι ψευδές όταν δεν καθορίζεται. |
| [XmlVersion](../../aspose.html.dom/document/xmlversion/) { get; set; } | Ένα χαρακτηριστικό που προσδιορίζει, ως μέρος της δήλωσης XML, τον αριθμό έκδοσης αυτού του εγγράφου. Εάν δεν υπάρχει δήλωση και εάν αυτό το έγγραφο υποστηρίζει τη δυνατότητα "XML", η τιμή είναι "1.0". Εάν αυτό το έγγραφο δεν υποστηρίζει τη δυνατότητα "XML", η τιμή είναι πάντα null. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | Αυτή η μέθοδος επιτρέπει την εγγραφή των ακροατών συμβάντων στον στόχο συμβάντος. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | Αυτή η μέθοδος επιτρέπει την εγγραφή των ακροατών συμβάντων στον στόχο συμβάντος. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | Αυτή η μέθοδος επιτρέπει την εγγραφή των ακροατών συμβάντων στον στόχο συμβάντος. |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | Προσθέτει τον κόμβο newChild στο τέλος της λίστας των παιδιών αυτού του κόμβου. Εάν το newChild βρίσκεται ήδη στο δέντρο, πρώτα αφαιρείται. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | Επιστρέφει ένα αντίγραφο αυτού του κόμβου, δηλαδή, χρησιμεύει ως γενικός κατασκευαστής αντιγράφων για κόμβους. Ο διπλότυπος κόμβος δεν έχει γονικό (parentNode είναι null) και δεν έχει δεδομένα χρήστη. |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | Επιστρέφει ένα αντίγραφο αυτού του κόμβου, δηλαδή, χρησιμεύει ως γενικός κατασκευαστής αντιγράφων για κόμβους. Ο διπλότυπος κόμβος δεν έχει γονικό (parentNode είναι null) και δεν έχει δεδομένα χρήστη. |
| [CreateAttribute](../../aspose.html.dom/document/createattribute/)(string) | Δημιουργεί ένα Attr του συγκεκριμένου ονόματος. |
| [CreateAttributeNS](../../aspose.html.dom/document/createattributens/)(string, string) | Δημιουργεί ένα χαρακτηριστικό του δεδομένου αναγνωρισμένου ονόματος και χώρου ονομάτων URI. |
| [CreateCDATASection](../../aspose.html.dom/document/createcdatasection/)(string) | Δημιουργεί έναν κόμβο ενότητας CDATAS του οποίου η τιμή είναι η καθορισμένη συμβολοσειρά. |
| [CreateComment](../../aspose.html.dom/document/createcomment/)(string) | Δημιουργεί έναν κόμβο σχολίων με την καθορισμένη συμβολοσειρά. |
| [CreateDocumentFragment](../../aspose.html.dom/document/createdocumentfragment/)() | Δημιουργεί ένα κενό αντικείμενο DocumentFragment. |
| [CreateDocumentType](../../aspose.html.dom/document/createdocumenttype/)(string, string, string, string) | Δημιουργεί έναν κόμβο DocumentType. |
| [CreateElement](../../aspose.html.dom/document/createelement/)(string) | Δημιουργεί ένα στοιχείο του καθορισμένου τύπου. Σημειώστε ότι η εμφάνιση που επιστράφηκε υλοποιεί τη διεπαφή Element, επομένως τα χαρακτηριστικά μπορούν να καθοριστούν απευθείας στο επιστρεφόμενο αντικείμενο. |
| [CreateElementNS](../../aspose.html.dom/document/createelementns/)(string, string) | Δημιουργεί ένα στοιχείο του συγκεκριμένου ονόματος και χώρου ονομάτων URI. |
| [CreateEntityReference](../../aspose.html.dom/document/createentityreference/)(string) | Δημιουργεί ένα αντικείμενο EntityReference. Επιπλέον, εάν η αναφερόμενη οντότητα είναι γνωστή, η θυγατρική λίστα του κόμβου EntityReference γίνεται ίδια με αυτή του αντίστοιχου κόμβου Entity. |
| [CreateEvent](../../aspose.html.dom/document/createevent/)(string) | Δημιουργεί ένα[`Event`](../../aspose.html.dom.events/event/) τύπου που υποστηρίζεται από την υλοποίηση. |
| [CreateExpression](../../aspose.html.dom/document/createexpression/)(string, IXPathNSResolver) | Δημιουργεί μια αναλυμένη έκφραση XPath με επιλυμένους χώρους ονομάτων. Αυτό είναι χρήσιμο όταν μια έκφραση θα επαναχρησιμοποιηθεί σε μια εφαρμογή, καθώς καθιστά δυνατή την να μεταγλωττίσει τη συμβολοσειρά έκφρασης σε μια πιο αποτελεσματική εσωτερική μορφή και να επιλύσει εκ των προτέρων όλα τα προθέματα χώρου ονομάτων που εμφανίζονται μέσα στην έκφραση. |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/#createnodeiterator)(Node) | Δημιουργήστε ένα νέο NodeIterator πάνω από το υποδέντρο που έχει ρίζες στον καθορισμένο κόμβο . |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/#createnodeiterator_1)(Node, long) | Δημιουργήστε ένα νέο NodeIterator πάνω από το υποδέντρο που έχει ρίζες στον καθορισμένο κόμβο . |
| [CreateNodeIterator](../../aspose.html.dom/document/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | Δημιουργήστε ένα νέο NodeIterator πάνω από το υποδέντρο που έχει ρίζες στον καθορισμένο κόμβο . |
| [CreateNSResolver](../../aspose.html.dom/document/creatensresolver/)(Node) | Προσαρμόζει οποιονδήποτε κόμβο DOM για την επίλυση χώρων ονομάτων, έτσι ώστε μια έκφραση XPath να μπορεί εύκολα να αξιολογηθεί σε σχέση με το περιβάλλον του κόμβου όπου εμφανίστηκε στο έγγραφο. Αυτός ο προσαρμογέας λειτουργεί όπως η μέθοδος DOM Level 3`lookupNamespaceURI` σε κόμβους για την επίλυση του namespaceURI από ένα δεδομένο πρόθεμα χρησιμοποιώντας τις τρέχουσες πληροφορίες που είναι διαθέσιμες στην ιεραρχία του κόμβου στο time lookupNamespaceURI καλείται, επιλύοντας επίσης σωστά το σιωπηρό πρόθεμα xml. |
| [CreateProcessingInstruction](../../aspose.html.dom/document/createprocessinginstruction/)(string, string) | Δημιουργεί έναν κόμβο ProcessingInstruction με το καθορισμένο όνομα και τις συμβολοσειρές δεδομένων. |
| [CreateTextNode](../../aspose.html.dom/document/createtextnode/)(string) | Δημιουργεί έναν κόμβο κειμένου με την καθορισμένη συμβολοσειρά. |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/#createtreewalker)(Node) | Δημιουργήστε ένα νέο TreeWalker πάνω από το υποδέντρο που έχει ρίζες στον καθορισμένο κόμβο . |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/#createtreewalker_1)(Node, long) | Δημιουργήστε ένα νέο TreeWalker πάνω από το υποδέντρο που έχει ρίζες στον καθορισμένο κόμβο . |
| [CreateTreeWalker](../../aspose.html.dom/document/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | Δημιουργήστε ένα νέο TreeWalker πάνω από το υποδέντρο που έχει ρίζες στον καθορισμένο κόμβο . |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Αυτή η μέθοδος επιτρέπει την αποστολή συμβάντων στο μοντέλο συμβάντων υλοποιήσεων. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Εκτελεί εργασίες που καθορίζονται από την εφαρμογή που σχετίζονται με την απελευθέρωση, την απελευθέρωση ή την επαναφορά μη διαχειριζόμενων πόρων. |
| [Evaluate](../../aspose.html.dom/document/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | Αξιολογεί μια συμβολοσειρά έκφρασης XPath και επιστρέφει ένα αποτέλεσμα του καθορισμένου τύπου εάν είναι δυνατόν. |
| [GetElementById](../../aspose.html.dom/document/getelementbyid/)(string) | Επιστρέφει το Στοιχείο που έχει ένα χαρακτηριστικό ID με τη δεδομένη τιμή. Εάν δεν υπάρχει τέτοιο στοιχείο, επιστρέφει μηδενικό. Εάν περισσότερα από ένα στοιχεία έχουν ένα χαρακτηριστικό ID με αυτήν την τιμή, αυτό που επιστρέφεται είναι απροσδιόριστο. |
| [GetElementsByClassName](../../aspose.html.dom/document/getelementsbyclassname/)(string) | Επιστρέφει ένα ζωντανό αντικείμενο NodeList που περιέχει όλα τα στοιχεία του εγγράφου που έχουν όλες τις κλάσεις που καθορίζονται στο όρισμα. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/document/getelementsbytagname/)(string) | Επιστρέφει μια NodeList με όλα τα στοιχεία με σειρά εγγράφου με ένα δεδομένο όνομα ετικέτας και περιέχονται στο έγγραφο. |
| [GetElementsByTagNameNS](../../aspose.html.dom/document/getelementsbytagnamens/)(string, string) | Επιστρέφει μια NodeList όλων των στοιχείων με ένα δεδομένο τοπικό όνομα και URI χώρου ονομάτων με σειρά εγγράφων. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση αντικειμένου ECMAScriptType . |
| virtual [HasAttributes](../../aspose.html.dom/node/hasattributes/)() | Επιστρέφει εάν αυτός ο κόμβος (αν είναι στοιχείο) έχει κάποια χαρακτηριστικά |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | Επιστρέφει εάν αυτός ο κόμβος έχει παιδιά. |
| [ImportNode](../../aspose.html.dom/document/importnode/)(Node, bool) | Εισάγει έναν κόμβο από άλλο έγγραφο σε αυτό το έγγραφο, χωρίς να τροποποιεί ή να αφαιρεί τον κόμβο προέλευσης από το αρχικό έγγραφο. αυτή η μέθοδος δημιουργεί ένα νέο αντίγραφο του κόμβου προέλευσης. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | Εισάγει τον κόμβο πριν από το υπάρχον θυγατρικό θυγατρικό κόμβο. Εάν το παιδί είναι μηδενικό, εισαγάγετε τον κόμβο στο τέλος της λίστας παιδιών. Εάν το θυγατρικό είναι αντικείμενο DocumentFragment, όλα τα θυγατρικά του εισάγονται, με την ίδια σειρά, πριν από το θυγατρικό. Εάν το παιδί είναι ήδη στο δέντρο, αφαιρείται πρώτα. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | Αυτή η μέθοδος ελέγχει εάν το καθορισμένο namespaceURI είναι ο προεπιλεγμένος χώρος ονομάτων ή όχι. |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | Ελέγχει εάν δύο κόμβοι είναι ίσοι. Αυτή η μέθοδος ελέγχει την ισότητα των κόμβων, όχι την ομοιότητα (δηλαδή, εάν οι δύο κόμβοι είναι αναφορές στο ίδιο αντικείμενο) που μπορεί να ελεγχθεί με το Node.isSameNode(). Όλοι οι κόμβοι που είναι ίδιοι θα είναι επίσης ίσοι, αν και το αντίστροφο μπορεί να μην ισχύει. |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | Επιστρέφει εάν αυτός ο κόμβος είναι ο ίδιος κόμβος με τον δεδομένο. Αυτή η μέθοδος παρέχει έναν τρόπο προσδιορισμού του εάν δύο αναφορές κόμβου που επιστρέφονται από την υλοποίηση αναφέρονται στο ίδιο αντικείμενο. Όταν δύο αναφορές κόμβου είναι αναφορές στο ίδιο αντικείμενο, ακόμη και αν μέσω διακομιστή μεσολάβησης, οι αναφορές μπορούν να χρησιμοποιούνται εντελώς εναλλακτικά, έτσι ώστε όλα τα χαρακτηριστικά να έχουν τις ίδιες τιμές και η κλήση της ίδιας μεθόδου DOM σε κάθε αναφορά έχει πάντα ακριβώς το ίδιο αποτέλεσμα. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | Αναζητήστε το URI του χώρου ονομάτων που σχετίζεται με το δεδομένο πρόθεμα, ξεκινώντας από αυτόν τον κόμβο. |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | Αναζητήστε το πρόθεμα που σχετίζεται με το δεδομένο URI χώρου ονομάτων, ξεκινώντας από αυτόν τον κόμβο. Οι προεπιλεγμένες δηλώσεις χώρου ονομάτων αγνοούνται από αυτήν τη μέθοδο. Ανατρέξτε στην Αναζήτηση προθέματος χώρου ονομάτων για λεπτομέρειες σχετικά με τον αλγόριθμο που χρησιμοποιείται από αυτήν τη μέθοδο. |
| [Navigate](../../aspose.html.dom/document/navigate/#navigate)(RequestMessage) | Φορτώνει το έγγραφο με βάση το καθορισμένο αντικείμενο αιτήματος, αντικαθιστώντας το προηγούμενο περιεχόμενο. |
| [Navigate](../../aspose.html.dom/document/navigate/#navigate_4)(string) | Φορτώνει το έγγραφο στον καθορισμένο Uniform Resource Locator (URL) στην τρέχουσα παρουσία, αντικαθιστώντας το προηγούμενο περιεχόμενο. |
| [Navigate](../../aspose.html.dom/document/navigate/#navigate_1)(Url) | Φορτώνει το έγγραφο στον καθορισμένο Uniform Resource Locator (URL) στην τρέχουσα παρουσία, αντικαθιστώντας το προηγούμενο περιεχόμενο. |
| [Navigate](../../aspose.html.dom/document/navigate/#navigate_3)(Stream, string) | Φορτώνει το έγγραφο από καθορισμένο περιεχόμενο και χρησιμοποιεί το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο. Η φόρτωση του εγγράφου ξεκινά από την τρέχουσα θέση στη ροή. |
| [Navigate](../../aspose.html.dom/document/navigate/#navigate_2)(Stream, Url) | Φορτώνει το έγγραφο από καθορισμένο περιεχόμενο και χρησιμοποιεί το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο. Η φόρτωση του εγγράφου ξεκινά από την τρέχουσα θέση στη ροή. |
| [Navigate](../../aspose.html.dom/document/navigate/#navigate_6)(string, string) | Φορτώνει το έγγραφο από καθορισμένο περιεχόμενο και χρησιμοποιεί το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο. |
| [Navigate](../../aspose.html.dom/document/navigate/#navigate_5)(string, Url) | Φορτώνει το έγγραφο από καθορισμένο περιεχόμενο και χρησιμοποιεί το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο. |
| [Normalize](../../aspose.html.dom/node/normalize/)() | Τοποθετεί όλους τους κόμβους κειμένου στο πλήρες βάθος του υποδέντρου κάτω από αυτόν τον κόμβο, συμπεριλαμβανομένων των κόμβων χαρακτηριστικών, σε μια "κανονική" μορφή όπου μόνο η δομή (π.χ. στοιχεία, σχόλια, οδηγίες επεξεργασίας, ενότητες CDATA και αναφορές οντοτήτων) διαχωρίζει το κείμενο κόμβοι, δηλαδή, δεν υπάρχουν ούτε γειτονικοί κόμβοι κειμένου ούτε κενοί κόμβοι κειμένου. Αυτό μπορεί να χρησιμοποιηθεί για να διασφαλιστεί ότι η προβολή DOM ενός εγγράφου είναι ίδια όπως αν είχε αποθηκευτεί και φορτωθεί ξανά και είναι χρήσιμο όταν οι λειτουργίες (όπως οι αναζητήσεις XPointer [XPointer]) που εξαρτώνται από μια συγκεκριμένη δομή δέντρου εγγράφου πρόκειται να να χρησιμοποιηθεί. Εάν η παράμετρος "normalize-characters" του αντικειμένου DOMConfiguration που είναι προσαρτημένο στο Node.ownerDocument είναι αληθής, αυτή η μέθοδος θα κανονικοποιήσει επίσης πλήρως τους χαρακτήρες των κόμβων κειμένου. |
| [QuerySelector](../../aspose.html.dom/document/queryselector/)(string) | Επιστρέφει το πρώτο Στοιχείο στο έγγραφο, το οποίο ταιριάζει με τον επιλογέα |
| [QuerySelectorAll](../../aspose.html.dom/document/queryselectorall/)(string) | Επιστρέφει μια NodeList με όλα τα στοιχεία του εγγράφου, τα οποία ταιριάζουν με τον selector |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | Αφαιρεί τον θυγατρικό κόμβο που υποδεικνύεται από το oldChild από τη λίστα των παιδιών και τον επιστρέφει. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών συμβάντων από τον στόχο συμβάντος. Εάν[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) αφαιρείται από ένα[`EventTarget`](../eventtarget/) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Δεν είναι δυνατή η επίκληση των Ακροατών συμβάντων μετά την αφαίρεση. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών συμβάντων από τον στόχο συμβάντος. Εάν[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) αφαιρείται από ένα[`EventTarget`](../eventtarget/) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Δεν είναι δυνατή η επίκληση των Ακροατών συμβάντων μετά την αφαίρεση. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | Αυτή η μέθοδος επιτρέπει την αφαίρεση των ακροατών συμβάντων από τον στόχο συμβάντος. Εάν[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) αφαιρείται από ένα[`EventTarget`](../eventtarget/) ενώ επεξεργάζεται ένα συμβάν, δεν θα ενεργοποιηθεί από τις τρέχουσες ενέργειες. Δεν είναι δυνατή η επίκληση των Ακροατών συμβάντων μετά την αφαίρεση. |
| virtual [RenderTo](../../aspose.html.dom/document/renderto/)(IDevice) | Αυτή η μέθοδος χρησιμοποιείται για την απόδοση των περιεχομένων του τρέχοντος εγγράφου σε μια καθορισμένη γραφική συσκευή. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | Αντικαθιστά τον θυγατρικό κόμβο oldChild με newChild στη λίστα των παιδιών και επιστρέφει τον κόμβο oldChild. Εάν το newChild είναι αντικείμενο DocumentFragment, το oldChild αντικαθίσταται από όλα τα θυγατρικά DocumentFragment, τα οποία εισάγονται με την ίδια σειρά. Εάν το newChild βρίσκεται ήδη στο δέντρο, πρώτα αφαιρείται. |
| override [ToString](../../aspose.html.dom/node/tostring/)() | Επιστρέφει αString που αντιπροσωπεύει αυτήν την περίπτωση. |
| [Write](../../aspose.html.dom/document/write/)(params string[]) | Γράψτε μια συμβολοσειρά κειμένου σε μια ροή εγγράφου που ανοίγει από open(). Σημειώστε ότι η συνάρτηση θα παράγει ένα document το οποίο δεν οδηγείται απαραίτητα από ένα DTD και επομένως μπορεί να είναι παράγει ένα μη έγκυρο αποτέλεσμα στο πλαίσιο του εγγράφου. |
| [WriteLn](../../aspose.html.dom/document/writeln/)(params string[]) | Γράψτε μια συμβολοσειρά κειμένου ακολουθούμενη από έναν χαρακτήρα νέας γραμμής σε μια ροή document που ανοίγει από το open(). Σημειώστε ότι η συνάρτηση θα παράγει ένα έγγραφο το οποίο δεν καθοδηγείται απαραίτητα από ένα DTD και επομένως μπορεί να παράγει ένα μη έγκυρο αποτέλεσμα στο πλαίσιο του document |

## Εκδηλώσεις

| Ονομα | Περιγραφή |
| --- | --- |
| event [OnAbort](../../aspose.html.dom/document/onabort/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnAbort. |
| event [OnBlur](../../aspose.html.dom/document/onblur/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnBlur. |
| event [OnCancel](../../aspose.html.dom/document/oncancel/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnCancel. |
| event [OnCanplay](../../aspose.html.dom/document/oncanplay/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για την εκδήλωση OnCanplay. |
| event [OnCanPlayThrough](../../aspose.html.dom/document/oncanplaythrough/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnCanPlayThrough. |
| event [OnChange](../../aspose.html.dom/document/onchange/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnChange. |
| event [OnClick](../../aspose.html.dom/document/onclick/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnClick. |
| event [OnCueChange](../../aspose.html.dom/document/oncuechange/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnCueChange. |
| event [OnDblClick](../../aspose.html.dom/document/ondblclick/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnDblClick. |
| event [OnDurationChange](../../aspose.html.dom/document/ondurationchange/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnDurationChange. |
| event [OnEmptied](../../aspose.html.dom/document/onemptied/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnEmptied. |
| event [OnEnded](../../aspose.html.dom/document/onended/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για συμβάν OnEnded. |
| event [OnError](../../aspose.html.dom/document/onerror/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnError. |
| event [OnFocus](../../aspose.html.dom/document/onfocus/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnFocus. |
| event [OnInput](../../aspose.html.dom/document/oninput/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnInput. |
| event [OnInvalid](../../aspose.html.dom/document/oninvalid/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnInvalid. |
| event [OnKeyDown](../../aspose.html.dom/document/onkeydown/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnKeyDown. |
| event [OnKeyPress](../../aspose.html.dom/document/onkeypress/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnKeyPress. |
| event [OnKeyUp](../../aspose.html.dom/document/onkeyup/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnKeyUp. |
| event [OnLoad](../../aspose.html.dom/document/onload/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnLoad. |
| event [OnLoadedData](../../aspose.html.dom/document/onloadeddata/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnLoadedData. |
| event [OnLoadedMetadata](../../aspose.html.dom/document/onloadedmetadata/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnLoadedMetadata. |
| event [OnLoadStart](../../aspose.html.dom/document/onloadstart/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnLoadStart. |
| event [OnMouseDown](../../aspose.html.dom/document/onmousedown/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnMouseDown. |
| event [OnMouseEnter](../../aspose.html.dom/document/onmouseenter/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnMouseEnter. |
| event [OnMouseLeave](../../aspose.html.dom/document/onmouseleave/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnMouseLeave. |
| event [OnMouseMove](../../aspose.html.dom/document/onmousemove/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnMouseMove. |
| event [OnMouseOut](../../aspose.html.dom/document/onmouseout/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnMouseOut. |
| event [OnMouseOver](../../aspose.html.dom/document/onmouseover/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnMouseOver. |
| event [OnMouseUp](../../aspose.html.dom/document/onmouseup/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnMouseUp. |
| event [OnMouseWheel](../../aspose.html.dom/document/onmousewheel/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnMouseWheel. |
| event [OnPause](../../aspose.html.dom/document/onpause/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnPause. |
| event [OnPlay](../../aspose.html.dom/document/onplay/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnPlay. |
| event [OnPlaying](../../aspose.html.dom/document/onplaying/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnPlaying. |
| event [OnProgress](../../aspose.html.dom/document/onprogress/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnProgress. |
| event [OnRateChange](../../aspose.html.dom/document/onratechange/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnRateChange. |
| event [OnReadyStateChange](../../aspose.html.dom/document/onreadystatechange/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnReadyStateChange. |
| event [OnReset](../../aspose.html.dom/document/onreset/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnReset. |
| event [OnResize](../../aspose.html.dom/document/onresize/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnResize. |
| event [OnScroll](../../aspose.html.dom/document/onscroll/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnScroll. |
| event [OnSeeked](../../aspose.html.dom/document/onseeked/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnSeeked. |
| event [OnSeeking](../../aspose.html.dom/document/onseeking/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnSeeking. |
| event [OnSelect](../../aspose.html.dom/document/onselect/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnSelect. |
| event [OnShow](../../aspose.html.dom/document/onshow/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnShow. |
| event [OnStalled](../../aspose.html.dom/document/onstalled/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnStalled. |
| event [OnSubmit](../../aspose.html.dom/document/onsubmit/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnSubmit. |
| event [OnSuspend](../../aspose.html.dom/document/onsuspend/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnSuspend. |
| event [OnTimeUpdate](../../aspose.html.dom/document/ontimeupdate/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnTimeUpdate. |
| event [OnToggle](../../aspose.html.dom/document/ontoggle/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnToggle. |
| event [OnVolumeChange](../../aspose.html.dom/document/onvolumechange/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnVolumeChange. |
| event [OnWaiting](../../aspose.html.dom/document/onwaiting/) | Λαμβάνει ή ορίζει το πρόγραμμα χειρισμού συμβάντων για το συμβάν OnWaiting. |

### Δείτε επίσης

* class [Node](../node/)
* interface [IDocumentEvent](../../aspose.html.dom.events/idocumentevent/)
* interface [IDocumentStyle](../../aspose.html.dom.css/idocumentstyle/)
* interface [IDocumentTraversal](../../aspose.html.dom.traversal/idocumenttraversal/)
* interface [IGlobalEventHandlers](../iglobaleventhandlers/)
* interface [INonElementParentNode](../inonelementparentnode/)
* interface [IParentNode](../iparentnode/)
* interface [IXPathEvaluator](../../aspose.html.dom.xpath/ixpathevaluator/)
* χώρος ονομάτων [Aspose.Html.Dom](../../aspose.html.dom/)
* συνέλευση [Aspose.HTML](../../)


