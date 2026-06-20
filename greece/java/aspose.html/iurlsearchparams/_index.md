---
title: "IUrlSearchParams Διεπαφή"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.IUrlSearchParams διεπαφή. Παρέχει μεθόδους για εργασία με τη συμβολοσειρά ερωτήματος URLs"
type: docs

url: /el/java/com.aspose.html/iurlsearchparams/
---
## IUrlSearchParams interface

Παρέχει μεθόδους για εργασία με το query String των URL.

```java
public interface IUrlSearchParams : IEnumerable<String[]>
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [append](../../com.aspose.html/iurlsearchparams/append/)(String, String) | Προσθέτει ένα νέο ζεύγος όνομα-τιμή του οποίου το όνομα είναι `name` και η τιμή είναι `value`. |
| [delete](../../com.aspose.html/iurlsearchparams/delete/)(String) | Αφαιρεί όλα τα ζεύγη όνομα-τιμή του οποίου το όνομα είναι `name`. |
| [get](../../com.aspose.html/iurlsearchparams/get/)(String) | Επιστρέφει την τιμή του πρώτου ζεύγος όνομα-τιμή του οποίου το όνομα είναι `name`. |
| [getAll](../../com.aspose.html/iurlsearchparams/getall/)(String) | Επιστρέφει όλες τις τιμές του οποίου το όνομα είναι `name`. |
| [has](../../com.aspose.html/iurlsearchparams/has/)(String) | Ελέγχει αν υπάρχει ζεύγος όνομα-τιμή του οποίου το όνομα είναι `name` στη λίστα. |
| [set](../../com.aspose.html/iurlsearchparams/set/)(String, String) | Ορίζει την τιμή του πρώτου βρεθέντος ζεύγους όνομα-τιμή στην καθορισμένη τιμή και αφαιρεί τα υπόλοιπα. Εάν δεν βρεθούν ζεύγη όνομα-τιμή με το καθορισμένο όνομα, θα προστεθεί ένα νέο στη λίστα. |
| [sort](../../com.aspose.html/iurlsearchparams/sort/)() | Ταξινομεί όλα τα ζεύγη όνομα-τιμή, εφόσον υπάρχουν, κατά τα ονόματά τους. |

### Δείτε επίσης

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
