---
title: "Τάξη TypeInfo"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.TypeInfo class. Το TypeInfo αντιπροσωπεύει έναν τύπο που αναφέρεται από κόμβους Element ή Attr που καθορίζονται στα σχήματα που σχετίζονται με το έγγραφο."
type: docs

url: /el/java/com.aspose.html.dom/typeinfo/
---
## TypeInfo class

Η TypeInfo αντιπροσωπεύει έναν τύπο που αναφέρεται από κόμβους Element ή Attr, καθορισμένο στα σχήματα που σχετίζονται με το έγγραφο.

```java
public class TypeInfo : DOMObject
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getTypeName](../../com.aspose.html.dom/typeinfo/typename/) Το όνομα ενός τύπου που δηλώνεται για το σχετικό στοιχείο ή attribute, ή null εάν είναι άγνωστο. |
| [getTypeNamespace](../../com.aspose.html.dom/typeinfo/typepackage/) Λαμβάνει το πακέτο τύπου. Το πακέτο του τύπου που δηλώνεται για το σχετικό στοιχείο ή attribute ή null εάν το στοιχείο δεν έχει δήλωση ή εάν δεν υπάρχουν διαθέσιμες πληροφορίες πακέτου. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του αντικειμένου ECMAScript. |
| [isDerivedFrom](../../com.aspose.html.dom/typeinfo/isderivedfrom/)(String, String, ulong) | Αυτή η μέθοδος επιστρέφει εάν υπάρχει παράγωγος μεταξύ του ορισμού τύπου αναφοράς, δηλαδή του TypeInfo πάνω στο οποίο καλείται η μέθοδος, και του άλλου ορισμού τύπου, δηλαδή του που περνιέται ως παράμετρος. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [DERIVATION_EXTENSION](../../com.aspose.html.dom/typeinfo/derivation_extension/) | Εάν το σχήμα του εγγράφου είναι ένα XML Schema [XML Schema Part 1], αυτή η σταθερά αντιπροσωπεύει την παράγωγο μέσω επέκτασης. |
| const [DERIVATION_LIST](../../com.aspose.html.dom/typeinfo/derivation_list/) | Εάν το σχήμα του εγγράφου είναι ένα XML Schema [XML Schema Part 1], αυτή η σταθερά αντιπροσωπεύει τη λίστα. |
| const [DERIVATION_RESTRICTION](../../com.aspose.html.dom/typeinfo/derivation_restriction/) | Εάν το σχήμα του εγγράφου είναι ένα XML Schema [XML Schema Part 1], αυτή η σταθερά αντιπροσωπεύει την παράγωγο μέσω περιορισμού εάν εμπλέκονται σύνθετοι τύποι, ή έναν περιορισμό εάν εμπλέκονται απλοί τύποι. |
| const [DERIVATION_UNION](../../com.aspose.html.dom/typeinfo/derivation_union/) | Εάν το σχήμα του εγγράφου είναι ένα XML Schema [XML Schema Part 1], αυτή η σταθερά αντιπροσωπεύει την ένωση εάν εμπλέκονται απλοί τύποι. |

### Δείτε επίσης

* class [DOMObject](../domobject/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
