---
title: "TypeInfo.IsDerivedFrom"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος TypeInfo. Αυτή η μέθοδος επιστρέφει εάν υπάρχει παράγωγη μεταξύ του ορισμού τύπου αναφοράς, δηλαδή του TypeInfo στο οποίο καλείται η μέθοδος, και του άλλου ορισμού τύπου, δηλαδή του που περνιέται ως παράμετρος"
type: docs

url: /el/java/com.aspose.html.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

Αυτή η μέθοδος επιστρέφει εάν υπάρχει παράγωγος μεταξύ του ορισμού τύπου αναφοράς, δηλαδή του TypeInfo πάνω στο οποίο καλείται η μέθοδος, και του άλλου ορισμού τύπου, δηλαδή του που περνιέται ως παράμετρος.

```java
public bool IsDerivedFrom(String typeNamespaceArg, String typeNameArg, ulong derivationMethod)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| typeNamespaceArg | String | το πακέτο του άλλου ορισμού τύπου |
| typeNameArg | String | το όνομα του άλλου ορισμού τύπου. |
| derivationMethod | UInt64 | ο τύπος της παράγωγης και οι συνθήκες που εφαρμόζονται μεταξύ δύο τύπων, όπως περιγράφεται στη λίστα των σταθερών που παρέχονται σε αυτή τη διεπαφή. |

### Τιμή Επιστροφής

Εάν το σχήμα του εγγράφου είναι DTD ή δεν υπάρχει σχήμα συσχετισμένο με το έγγραφο, αυτή η μέθοδος θα επιστρέφει πάντα false. Εάν το σχήμα του εγγράφου είναι XML Schema, η μέθοδος θα επιστρέφει true εάν ο ορισμός τύπου αναφοράς προέρχεται από τον άλλο ορισμό τύπου σύμφωνα με την παράμετρο παράγωγης. Εάν η τιμή της παραμέτρου είναι 0 (κανένα bit δεν έχει οριστεί σε 1 για την παράμετρο derivationMethod), η μέθοδος θα επιστρέφει true εάν ο άλλος ορισμός τύπου μπορεί να προσεγγιστεί επαναληπτικά με οποιονδήποτε συνδυασμό των {base type definition}, {item type definition} ή {member type definitions} από τον ορισμό τύπου αναφοράς.

### Δείτε επίσης

* class [TypeInfo](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
