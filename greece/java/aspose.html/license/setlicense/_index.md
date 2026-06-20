---
title: "License.SetLicense"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος License. Παρέχει άδεια στο στοιχείο."
type: docs

url: /el/java/com.aspose.html/license/setlicense/
---
## SetLicense(String) {#setlicense_1}

Αδειοδοτεί το στοιχείο.

```java
public void SetLicense(String licenseName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| licenseName | String | Μπορεί να είναι πλήρες ή σύντομο όνομα αρχείου ή όνομα ενσωματωμένου πόρου. Χρησιμοποιήστε μια κενή συμβολοσειρά για να μεταβείτε σε λειτουργία αξιολόγησης. |

## Παρατηρήσεις

Προσπαθεί να βρει την άδεια στις παρακάτω τοποθεσίες:

1. Συγκεκριμένη διαδρομή.

2. Ο φάκελος που περιέχει το assembly του στοιχείου Aspose.

3. Ο φάκελος που περιέχει το assembly που καλεί ο πελάτης.

4. Ο φάκελος που περιέχει το assembly (entry/startup).

5. Ένας ενσωματωμένος πόρος στο assembly που καλεί ο πελάτης.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Συγκεκριμένη διαδρομή.

2. Ένας ενσωματωμένος πόρος στο assembly που καλεί ο πελάτης.

2. Ο φάκελος που περιέχει το αρχείο JAR του στοιχείου Aspose.

3. Ο φάκελος που περιέχει το αρχείο JAR που καλεί ο πελάτης.

## Παραδείγματα

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να βρεθεί ένα αρχείο άδειας με όνομα MyLicense.lic στον φάκελο που περιέχει το στοιχείο, στον φάκελο που περιέχει το κλήσιμο της συναρμολόγησης, στον φάκελο της κύριας συναρμολόγησης και, τέλος, στους ενσωματωμένους πόρους της κλήσης της συναρμολόγησης.

```java
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

το αρχείο jar του component:

```java
License license = new License();
license.setLicense("MyLicense.lic");
```

### Δείτε επίσης

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## SetLicense(Stream) {#setlicense}

Αδειοδοτεί το στοιχείο.

```java
public void SetLicense(Stream stream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Μία ροή που περιέχει την άδεια. |

## Παρατηρήσεις

Χρησιμοποιήστε αυτή τη μέθοδο για να φορτώσετε μια άδεια από μια ροή.

## Παραδείγματα

```java
[C#]

License license = new License();
license.SetLicense(myStream);
```

### Δείτε επίσης

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
