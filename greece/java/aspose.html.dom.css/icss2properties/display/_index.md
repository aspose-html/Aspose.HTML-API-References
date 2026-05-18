---
title: "ICSS2Properties.Display"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Ιδιότητα ICSS2Properties. Οι τιμές αυτής της ιδιότητας έχουν τις ακόλουθες σημασίες"
type: docs

url: /el/java/com.aspose.html.dom.css/icss2properties/display/
---
## ICSS2Properties.Display property

Οι τιμές αυτής της ιδιότητας έχουν τις ακόλουθες σημασίες:

block - Αυτή η τιμή κάνει ένα στοιχείο να δημιουργήσει ένα κύριο block κουτί. inline - Αυτή η τιμή κάνει ένα στοιχείο να δημιουργήσει ένα ή περισσότερα inline κουτιά. list-item - Αυτή η τιμή κάνει ένα στοιχείο (π.χ., LI σε HTML) να δημιουργήσει ένα κύριο block κουτί και ένα inline κουτί τύπου list-item. Για πληροφορίες σχετικά με τις λίστες και παραδείγματα μορφοποίησης λιστών, παρακαλούμε συμβουλευτείτε την ενότητα για [lists](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#lists). marker - Αυτή η τιμή δηλώνει [generated content](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html) πριν ή μετά από ένα κουτί ως δείκτη. Αυτή η τιμή πρέπει να χρησιμοποιείται μόνο με ψευδο-στοιχεία [:before και :after](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#before-after-content) που συνδέονται με στοιχεία σε επίπεδο block. Σε άλλες περιπτώσεις, αυτή η τιμή ερμηνεύεται ως 'inline'. Παρακαλούμε συμβουλευτείτε την ενότητα για [markers](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#markers) για περισσότερες πληροφορίες. none - Αυτή η τιμή κάνει ένα στοιχείο να μην δημιουργήσει κουτιά στη [formatting structure](https://www.w3.org/TR/1998/REC-CSS2-19980512/intro.html#formatting-structure) (δηλαδή, το στοιχείο δεν έχει καμία επίδραση στη διάταξη). Τα απογόνους στοιχεία επίσης δεν δημιουργούν κουτιά· αυτή η συμπεριφορά δεν μπορεί να παρακαμφθεί ορίζοντας την ιδιότητα ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) στα απογόνους. Σημειώστε ότι η τιμή 'none' δεν δημιουργεί αόρατο κουτί· δεν δημιουργεί κανένα κουτί. Το CSS περιλαμβάνει μηχανισμούς που επιτρέπουν σε ένα στοιχείο να δημιουργήσει κουτιά στη δομή μορφοποίησης που επηρεάζουν τη μορφοποίηση αλλά δεν είναι ορατά. Παρακαλούμε συμβουλευτείτε την ενότητα για [visibility](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#visibility) για λεπτομέρειες. run-in and compact - Αυτές οι τιμές δημιουργούν είτε block είτε inline κουτιά, ανάλογα με το πλαίσιο. Οι ιδιότητες εφαρμόζονται σε κουτιά run-in και compact βάσει του τελικού τους status (inline-level ή block-level). Για παράδειγμα, η ιδιότητα ['white-space'](https://www.w3.org/TR/1998/REC-CSS2-19980512/text.html#propdef-white-space) εφαρμόζεται μόνο εάν το κουτί γίνεται block κουτί. table, inline-table, table-row-group, [table-column](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#value-def-table-column), table-column-group, table-header-group, table-footer-group, table-row, table-cell, and table-caption - Αυτές οι τιμές κάνουν ένα στοιχείο να συμπεριφέρεται όπως ένα στοιχείο πίνακα (υπόκειται σε περιορισμούς που περιγράφονται στο κεφάλαιο για [tables](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html)).

```java
public String Display { get; set; }
```

### Τιμή επιστροφής

ιδιότητα display

### Δείτε επίσης

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
