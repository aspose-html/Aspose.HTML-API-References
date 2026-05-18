---
title: "Κατηγορία DOMException"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "κλάση com.aspose.html.dom.DOMException. Η διεπαφή DOMException αντιπροσωπεύει ένα ανώμαλο γεγονός που ονομάζεται εξαίρεση, το οποίο συμβαίνει ως αποτέλεσμα κλήσης μιας μεθόδου ή πρόσβασης σε μια ιδιότητα ενός web API. Αυτό είναι βασικά ο τρόπος με τον οποίο περιγράφονται οι συνθήκες σφάλματος στα web APIs."
type: docs

url: /el/java/com.aspose.html.dom/domexception/
---
## DOMException class

Η διεπαφή DOMException αντιπροσωπεύει ένα ανώμαλο γεγονός (ονομάζεται εξαίρεση) που συμβαίνει ως αποτέλεσμα κλήσης μεθόδου ή πρόσβασης σε ιδιότητα ενός web API. Αυτό είναι ουσιαστικά ο τρόπος με τον οποίο περιγράφονται οι συνθήκες σφάλματος στα web APIs.

```java
public class DOMException : PlatformException
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [DOMException](domexception/#constructor)(String) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `DOMException`. |
| [DOMException](domexception/#constructor_1)(String, String) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `DOMException`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getCode](../../com.aspose.html.dom/domexception/code/) Επιστρέφει μια τιμή που περιέχει μία από τις σταθερές κωδικών σφάλματος, ή 0 εάν καμία δεν ταιριάζει. Αυτό το πεδίο χρησιμοποιείται για ιστορικούς λόγους. |
| [getMessage](../../com.aspose.html.dom/domexception/message/) Επιστρέφει ένα String που αντιπροσωπεύει ένα μήνυμα ή περιγραφή που συνδέεται με το δεδομένο όνομα σφάλματος. |
| [getName](../../com.aspose.html.dom/domexception/name/) Επιστρέφει ένα String που περιέχει ένα από τα Strings που συνδέονται με ένα όνομα σφάλματος. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [ABORT_ERR](../../com.aspose.html.dom/domexception/abort_err/) | Η λειτουργία ακυρώθηκε. |
| const [DATA_CLONE_ERR](../../com.aspose.html.dom/domexception/data_clone_err/) | Το αντικείμενο δεν μπορεί να κλωνοποιηθεί. |
| const [DOMSTRING_SIZE_ERR](../../com.aspose.html.dom/domexception/domString_size_err/) | Εάν το καθορισμένο εύρος κειμένου δεν χωράει σε ένα DOMString. |
| const [HIERARCHY_REQUEST_ERR](../../com.aspose.html.dom/domexception/hierarchy_request_err/) | Εάν οποιοσδήποτε Node εισαχθεί κάπου που δεν ανήκει. |
| const [INDEX_SIZE_ERR](../../com.aspose.html.dom/domexception/index_size_err/) | Εάν το index ή το size είναι αρνητικό, ή μεγαλύτερο από την επιτρεπόμενη τιμή. |
| const [INUSE_ATTRIBUTE_ERR](../../com.aspose.html.dom/domexception/inuse_attribute_err/) | Εάν γίνει προσπάθεια προσθήκης ενός χαρακτηριστικού που χρησιμοποιείται ήδη αλλού. |
| const [INVALID_ACCESS_ERR](../../com.aspose.html.dom/domexception/invalid_access_err/) | Εάν μια παράμετρος ή μια λειτουργία δεν υποστηρίζεται από το υποκείμενο αντικείμενο. |
| const [INVALID_CHARACTER_ERR](../../com.aspose.html.dom/domexception/invalid_character_err/) | Εάν καθοριστεί ένας μη έγκυρος ή παράνομος χαρακτήρας, όπως σε ένα όνομα XML. |
| const [INVALID_EXPRESSION_ERR](../../com.aspose.html.dom/domexception/invalid_expression_err/) | Η έκφραση έχει συντακτικό σφάλμα ή διαφορετικά δεν είναι έγκυρη έκφραση σύμφωνα με τους κανόνες του συγκεκριμένου XPathEvaluator ή περιέχει εξειδικευμένες λειτουργίες επέκτασης ή μεταβλητές που δεν υποστηρίζονται από αυτήν την υλοποίηση. |
| const [INVALID_MODIFICATION_ERR](../../com.aspose.html.dom/domexception/invalid_modification_err/) | Εάν γίνει προσπάθεια τροποποίησης του τύπου του υποκείμενου αντικειμένου. |
| const [INVALID_NODE_TYPE_ERR](../../com.aspose.html.dom/domexception/invalid_node_type_err/) | Ο παρεχόμενος κόμβος είναι εσφαλμένος ή έχει λανθασμένο πρόγονο για αυτήν τη λειτουργία. |
| const [INVALID_STATE_ERR](../../com.aspose.html.dom/domexception/invalid_state_err/) | Εάν γίνει προσπάθεια χρήσης ενός αντικειμένου που δεν είναι, ή δεν είναι πλέον, χρησιμοποιήσιμο. |
| const [NAMESPACE_ERR](../../com.aspose.html.dom/domexception/package_err/) | Εάν γίνει προσπάθεια δημιουργίας ή τροποποίησης ενός αντικειμένου με τρόπο που είναι λανθασμένος ως προς τα πακέτα. |
| const [NETWORK_ERR](../../com.aspose.html.dom/domexception/network_err/) | Παρουσιάστηκε σφάλμα δικτύου. |
| const [NOT_FOUND_ERR](../../com.aspose.html.dom/domexception/not_found_err/) | Εάν γίνει προσπάθεια αναφοράς σε έναν Node σε ένα πλαίσιο όπου δεν υπάρχει. |
| const [NOT_SUPPORTED_ERR](../../com.aspose.html.dom/domexception/not_supported_err/) | Εάν η υλοποίηση δεν υποστηρίζει τον ζητούμενο τύπο αντικειμένου ή λειτουργίας. |
| const [NO_DATA_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_data_allowed_err/) | Εάν καθοριστούν δεδομένα για έναν Node που δεν υποστηρίζει δεδομένα. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_modification_allowed_err/) | Εάν γίνει προσπάθεια τροποποίησης ενός αντικειμένου όπου οι τροποποιήσεις δεν επιτρέπονται. |
| const [QUOTA_EXCEEDED_ERR](../../com.aspose.html.dom/domexception/quota_exceeded_err/) | Το όριο έχει ξεπεραστεί. |
| const [SECURITY_ERR](../../com.aspose.html.dom/domexception/security_err/) | Η λειτουργία είναι μη ασφαλής. |
| const [SYNTAX_ERR](../../com.aspose.html.dom/domexception/syntax_err/) | Εάν καθοριστεί μια μη έγκυρη ή παράνομη String. |
| const [TIMEOUT_ERR](../../com.aspose.html.dom/domexception/timeout_err/) | Η λειτουργία έληξε το χρονικό όριο. |
| const [TYPE_ERR](../../com.aspose.html.dom/domexception/type_err/) | Η έκφραση δεν μπορεί να μετατραπεί ώστε να επιστρέψει τον καθορισμένο τύπο. |
| const [TYPE_MISMATCH_ERR](../../com.aspose.html.dom/domexception/type_mismatch_err/) | Εάν ο τύπος ενός αντικειμένου είναι ασύμβατος με τον αναμενόμενο τύπο της παραμέτρου που σχετίζεται με το αντικείμενο. |
| const [URL_MISMATCH_ERR](../../com.aspose.html.dom/domexception/url_mismatch_err/) | Το δοσμένο URL δεν ταιριάζει με άλλο URL. |
| const [VALIDATION_ERR](../../com.aspose.html.dom/domexception/validation_err/) | Εάν μια κλήση σε μια μέθοδο όπως insertBefore ή removeChild θα έκανε τον Node μη έγκυρο ως προς την \"μερική εγκυρότητα\", αυτή η εξαίρεση θα εγερθεί και η λειτουργία δεν θα εκτελεστεί. Αυτός ο κώδικας χρησιμοποιείται στο [DOM Level 3 Validation]. Ανατρέξτε σε αυτήν την προδιαγραφή για περισσότερες πληροφορίες. |
| const [WRONG_DOCUMENT_ERR](../../com.aspose.html.dom/domexception/wrong_document_err/) | Εάν ένας Node χρησιμοποιείται σε διαφορετικό έγγραφο από αυτό που τον δημιούργησε (που δεν το υποστηρίζει). |

### Δείτε επίσης

* class [PlatformException](../../com.aspose.html/platformexception/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
