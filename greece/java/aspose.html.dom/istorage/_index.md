---
title: "IStorage Διεπαφή"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.IStorage διεπαφή. Αυτή η διεπαφή του Web Storage API παρέχει πρόσβαση στη συνεδρία ή στην τοπική αποθήκευση ενός συγκεκριμένου τομέα. Δείτε την προδιαγραφή Web Storage https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs

url: /el/java/com.aspose.html.dom/istorage/
---
## IStorage interface

Αυτή η διεπαφή του Web Storage API παρέχει πρόσβαση στην αποθήκευση συνεδρίας ή τοπική αποθήκευση ενός συγκεκριμένου τομέα. Δείτε την προδιαγραφή Web Storage: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```java
public interface IStorage
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getLength](../../com.aspose.html.dom/istorage/length/) Επιστρέφει τον αριθμό των ζευγών κλειδί/τιμή. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [clear](../../com.aspose.html.dom/istorage/clear/)() | Αφαιρεί όλα τα ζεύγη κλειδιού/τιμής, εάν υπάρχουν. |
| [getItem](../../com.aspose.html.dom/istorage/getitem/)(String) | Επιστρέφει την τρέχουσα τιμή που συσχετίζεται με το δοσμένο κλειδί, ή null εάν το δοσμένο κλειδί δεν υπάρχει. |
| [key](../../com.aspose.html.dom/istorage/key/)(long) | Επιστρέφει το όνομα του n‑ου κλειδιού, ή null εάν το n είναι μεγαλύτερο ή ίσο με τον αριθμό των ζευγών κλειδιού/τιμής. |
| [removeItem](../../com.aspose.html.dom/istorage/removeitem/)(String) | Αφαιρεί το ζεύγος κλειδιού/τιμής με το δοσμένο κλειδί, εάν υπάρχει ζεύγος κλειδιού/τιμής με το δοσμένο κλειδί. |
| [setItem](../../com.aspose.html.dom/istorage/setitem/)(String, String) | Ορίζει την τιμή του ζεύγους που προσδιορίζεται από το κλειδί σε value, δημιουργώντας ένα νέο ζεύγος κλειδιού/τιμής εάν δεν υπήρχε προηγουμένως για το κλειδί. |

### Δείτε επίσης

* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
