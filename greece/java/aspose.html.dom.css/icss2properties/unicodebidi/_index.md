---
title: "ICSS2Properties.UnicodeBidi"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Ιδιότητα ICSS2Properties. Οι τιμές για αυτήν την ιδιότητα έχουν τις ακόλουθες σημασίες"
type: docs

url: /el/java/com.aspose.html.dom.css/icss2properties/unicodebidi/
---
## ICSS2Properties.UnicodeBidi property

Οι τιμές για αυτήν την ιδιότητα έχουν τις ακόλουθες σημασίες:

normal - Το στοιχείο δεν ανοίγει ένα πρόσθετο επίπεδο ενσωμάτωσης σε σχέση με τον αλγόριθμο διπλής κατεύθυνσης. Για στοιχεία σε επίπεδο inline, η έμμεση επαναδιάταξη λειτουργεί διασχίζοντας τα όρια των στοιχείων. embed - Εάν το στοιχείο είναι σε επίπεδο inline, αυτή η τιμή ανοίγει ένα πρόσθετο επίπεδο ενσωμάτωσης σε σχέση με τον αλγόριθμο διπλής κατεύθυνσης. Η κατεύθυνση αυτού του επιπέδου ενσωμάτωσης καθορίζεται από την ιδιότητα ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction). Μέσα στο στοιχείο, η επαναδιάταξη γίνεται έμμεσα. Αυτό αντιστοιχεί στην προσθήκη ενός LRE (U+202A; για 'direction: ltr') ή RLE (U+202B; για 'direction: rtl') στην αρχή του στοιχείου και ενός PDF (U+202C) στο τέλος του στοιχείου. bidi-override - Εάν το στοιχείο είναι σε επίπεδο inline ή ένα στοιχείο σε επίπεδο block που περιέχει μόνο στοιχεία σε επίπεδο inline, αυτό δημιουργεί παράκαμψη. Αυτό σημαίνει ότι μέσα στο στοιχείο, η επαναδιάταξη ακολουθεί αυστηρά τη σειρά σύμφωνα με την ιδιότητα ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction); το έμμερο μέρος του αλγορίθμου διπλής κατεύθυνσης αγνοείται. Αυτό αντιστοιχεί στην προσθήκη ενός LRO (U+202D; για 'direction: ltr') ή RLO (U+202E; για 'direction: rtl') στην αρχή του στοιχείου και ενός PDF (U+202C) στο τέλος του στοιχείου.

```java
public String UnicodeBidi { get; set; }
```

### Τιμή επιστροφής

ιδιότητα unicode-bidi

### Δείτε επίσης

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
