---
title: Class DOMException
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Dom.DOMException τάξη. Η διεπαφή DOMException αντιπροσωπεύει ένα μη κανονικό συμβάν που ονομάζεται εξαίρεση που προκύπτει ως αποτέλεσμα της κλήσης μιας μεθόδου ή της πρόσβασης σε μια ιδιότητα ενός API Ιστού. Αυτός είναι βασικά ο τρόπος με τον οποίο περιγράφονται οι συνθήκες σφάλματος στα web API.
type: docs
weight: 640
url: /el/net/aspose.html.dom/domexception/
---
## DOMException class

Η διεπαφή DOMException αντιπροσωπεύει ένα μη κανονικό συμβάν (που ονομάζεται εξαίρεση) που προκύπτει ως αποτέλεσμα της κλήσης μιας μεθόδου ή της πρόσβασης σε μια ιδιότητα ενός API Ιστού. Αυτός είναι βασικά ο τρόπος με τον οποίο περιγράφονται οι συνθήκες σφάλματος στα web API.

```csharp
public class DOMException : PlatformException
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [DOMException](domexception/#constructor)(string) | Αρχικοποιεί μια νέα παρουσία του`DOMException` τάξη. |
| [DOMException](domexception/#constructor_1)(string, string) | Αρχικοποιεί μια νέα παρουσία του`DOMException` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Code](../../aspose.html.dom/domexception/code/) { get; } | Επιστρέφει μια τιμή που περιέχει μία από τις σταθερές του κωδικού σφάλματος ή 0 εάν καμία δεν ταιριάζει. Αυτό το πεδίο χρησιμοποιείται για ιστορικούς λόγους. |
| override [Message](../../aspose.html.dom/domexception/message/) { get; } | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει ένα μήνυμα ή περιγραφή που σχετίζεται με το δεδομένο όνομα σφάλματος. |
| [Name](../../aspose.html.dom/domexception/name/) { get; } | Επιστρέφει μια συμβολοσειρά που περιέχει μία από τις συμβολοσειρές που σχετίζονται με ένα όνομα σφάλματος. |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| const [ABORT_ERR](../../aspose.html.dom/domexception/abort_err/) | Η επέμβαση ματαιώθηκε. |
| const [DATA_CLONE_ERR](../../aspose.html.dom/domexception/data_clone_err/) | Το αντικείμενο δεν μπορεί να κλωνοποιηθεί. |
| const [DOMSTRING_SIZE_ERR](../../aspose.html.dom/domexception/domstring_size_err/) | Εάν το καθορισμένο εύρος κειμένου δεν ταιριάζει σε ένα DOMString. |
| const [HIERARCHY_REQUEST_ERR](../../aspose.html.dom/domexception/hierarchy_request_err/) | Εάν κάποιος κόμβος έχει εισαχθεί κάπου δεν ανήκει. |
| const [INDEX_SIZE_ERR](../../aspose.html.dom/domexception/index_size_err/) | Εάν ο δείκτης ή το μέγεθος είναι αρνητικό ή μεγαλύτερο από την επιτρεπόμενη τιμή. |
| const [INUSE_ATTRIBUTE_ERR](../../aspose.html.dom/domexception/inuse_attribute_err/) | Εάν γίνει προσπάθεια να προστεθεί ένα χαρακτηριστικό που χρησιμοποιείται ήδη αλλού. |
| const [INVALID_ACCESS_ERR](../../aspose.html.dom/domexception/invalid_access_err/) | Εάν μια παράμετρος ή μια λειτουργία δεν υποστηρίζεται από το υποκείμενο αντικείμενο. |
| const [INVALID_CHARACTER_ERR](../../aspose.html.dom/domexception/invalid_character_err/) | Εάν έχει καθοριστεί ένας μη έγκυρος ή παράνομος χαρακτήρας, όπως σε ένα όνομα XML. |
| const [INVALID_EXPRESSION_ERR](../../aspose.html.dom/domexception/invalid_expression_err/) | Η έκφραση έχει συντακτικό σφάλμα ή δεν είναι νομική έκφραση σύμφωνα με τους κανόνες του specific XPathEvaluator ή περιέχει εξειδικευμένες συναρτήσεις επέκτασης ή μεταβλητές που δεν υποστηρίζονται από αυτήν την υλοποίηση. |
| const [INVALID_MODIFICATION_ERR](../../aspose.html.dom/domexception/invalid_modification_err/) | Εάν γίνει προσπάθεια τροποποίησης του τύπου του υποκείμενου αντικειμένου. |
| const [INVALID_NODE_TYPE_ERR](../../aspose.html.dom/domexception/invalid_node_type_err/) | Ο παρεχόμενος κόμβος είναι λανθασμένος ή έχει λανθασμένο πρόγονο για αυτήν τη λειτουργία. |
| const [INVALID_STATE_ERR](../../aspose.html.dom/domexception/invalid_state_err/) | Εάν γίνει προσπάθεια να χρησιμοποιηθεί ένα αντικείμενο που δεν είναι ή δεν είναι πλέον χρησιμοποιήσιμο. |
| const [NAMESPACE_ERR](../../aspose.html.dom/domexception/namespace_err/) | Εάν γίνει προσπάθεια να δημιουργηθεί ή να αλλάξει ένα αντικείμενο με τρόπο που είναι λανθασμένος όσον αφορά τους χώρους ονομάτων. |
| const [NETWORK_ERR](../../aspose.html.dom/domexception/network_err/) | Παρουσιάστηκε σφάλμα δικτύου. |
| const [NOT_FOUND_ERR](../../aspose.html.dom/domexception/not_found_err/) | Εάν γίνει προσπάθεια αναφοράς σε έναν Κόμβο σε περιβάλλον όπου δεν υπάρχει. |
| const [NOT_SUPPORTED_ERR](../../aspose.html.dom/domexception/not_supported_err/) | Εάν η υλοποίηση δεν υποστηρίζει τον ζητούμενο τύπο αντικειμένου ή λειτουργίας. |
| const [NO_DATA_ALLOWED_ERR](../../aspose.html.dom/domexception/no_data_allowed_err/) | Εάν έχουν καθοριστεί δεδομένα για έναν κόμβο που δεν υποστηρίζει δεδομένα. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../aspose.html.dom/domexception/no_modification_allowed_err/) | Εάν γίνει προσπάθεια τροποποίησης ενός αντικειμένου όπου δεν επιτρέπονται τροποποιήσεις. |
| const [QUOTA_EXCEEDED_ERR](../../aspose.html.dom/domexception/quota_exceeded_err/) | Έχει γίνει υπέρβαση του ορίου. |
| const [SECURITY_ERR](../../aspose.html.dom/domexception/security_err/) | Η λειτουργία δεν είναι ασφαλής. |
| const [SYNTAX_ERR](../../aspose.html.dom/domexception/syntax_err/) | Εάν έχει καθοριστεί μη έγκυρη ή παράνομη συμβολοσειρά. |
| const [TIMEOUT_ERR](../../aspose.html.dom/domexception/timeout_err/) | Η λειτουργία έληξε. |
| const [TYPE_ERR](../../aspose.html.dom/domexception/type_err/) | Η έκφραση δεν μπορεί να μετατραπεί για να επιστρέψει τον καθορισμένο τύπο. |
| const [TYPE_MISMATCH_ERR](../../aspose.html.dom/domexception/type_mismatch_err/) | Εάν ο τύπος ενός αντικειμένου δεν είναι συμβατός με τον αναμενόμενο τύπο της παραμέτρου που σχετίζεται με το αντικείμενο. |
| const [URL_MISMATCH_ERR](../../aspose.html.dom/domexception/url_mismatch_err/) | Η δεδομένη διεύθυνση URL δεν ταιριάζει με άλλη διεύθυνση URL. |
| const [VALIDATION_ERR](../../aspose.html.dom/domexception/validation_err/) | Εάν μια κλήση σε μια μέθοδο όπως το insertBefore ή το removeChild καθιστούσε τον Κόμβο άκυρο όσον αφορά τη "μερική εγκυρότητα", αυτή η εξαίρεση θα δημιουργηθεί και η λειτουργία δεν θα εκτελεστεί. Αυτός ο κωδικός χρησιμοποιείται στο [DOM Level 3 Validation]. Ανατρέξτε σε αυτήν την προδιαγραφή για περισσότερες πληροφορίες. |
| const [WRONG_DOCUMENT_ERR](../../aspose.html.dom/domexception/wrong_document_err/) | Εάν ένας Κόμβος χρησιμοποιείται σε διαφορετικό έγγραφο από αυτό που τον δημιούργησε (που δεν τον υποστηρίζει). |

### Δείτε επίσης

* class [PlatformException](../../aspose.html/platformexception/)
* χώρος ονομάτων [Aspose.Html.Dom](../../aspose.html.dom/)
* συνέλευση [Aspose.HTML](../../)


