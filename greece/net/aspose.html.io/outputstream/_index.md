---
title: Class OutputStream
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.IO.OutputStream τάξη. Μια υποκατάστατη ροή τυλίγει την πραγματική ροή εξόδου και ελέγχει την πρόσβαση σε αυτήν. OutputStream περιέχει δεδομένα URI που περιγράφουν τη θέση της ροής εξόδου.
type: docs
weight: 3750
url: /el/net/aspose.html.io/outputstream/
---
## OutputStream class

Μια υποκατάστατη ροή τυλίγει την πραγματική ροή εξόδου και ελέγχει την πρόσβαση σε αυτήν. `OutputStream` περιέχει δεδομένα URI που περιγράφουν τη θέση της ροής εξόδου.

```csharp
public class OutputStream : Stream
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [OutputStream](outputstream/)(Stream, string) | Αρχικοποιεί μια νέα παρουσία του`OutputStream` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| override [CanRead](../../aspose.html.io/outputstream/canread/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η τυλιγμένη ροή εξόδου υποστηρίζει ανάγνωση. |
| override [CanSeek](../../aspose.html.io/outputstream/canseek/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η περιτυλιγμένη ροή εξόδου υποστηρίζει αναζήτηση. |
| override [CanWrite](../../aspose.html.io/outputstream/canwrite/) { get; } | Λαμβάνει μια τιμή που υποδεικνύει εάν η τυλιγμένη ροή εξόδου υποστηρίζει εγγραφή. |
| override [Length](../../aspose.html.io/outputstream/length/) { get; } | Λαμβάνει το μήκος σε byte της περιτυλιγμένης ροής εξόδου. |
| override [Position](../../aspose.html.io/outputstream/position/) { get; set; } | Λαμβάνει ή ορίζει τη θέση εντός της περιτυλιγμένης ροής εξόδου. |
| [Uri](../../aspose.html.io/outputstream/uri/) { get; } | Λαμβάνει το URI της τοποθεσίας ροής. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| override [Close](../../aspose.html.io/outputstream/close/)() | Κλείνει την περιτυλιγμένη ροή εξόδου και την τρέχουσα ροή. |
| override [Flush](../../aspose.html.io/outputstream/flush/)() | Διαγράφει όλα τα buffer για την περιτυλιγμένη ροή εξόδου και προκαλεί την εγγραφή τυχόν αποθηκευμένων δεδομένων στην υποκείμενη συσκευή. |
| override [Read](../../aspose.html.io/outputstream/read/)(byte[], int, int) | Διαβάζει μια ακολουθία byte από την περιτυλιγμένη ροή εξόδου και προωθεί τη θέση εντός της ροής κατά τον αριθμό των byte που διαβάζονται. |
| override [Seek](../../aspose.html.io/outputstream/seek/)(long, SeekOrigin) | Ορίζει τη θέση εντός της περιτυλιγμένης ροής εξόδου. |
| override [SetLength](../../aspose.html.io/outputstream/setlength/)(long) | Ορίζει το μήκος της περιτυλιγμένης ροής εξόδου. |
| override [Write](../../aspose.html.io/outputstream/write/)(byte[], int, int) | Γράφει μια ακολουθία byte στο τυλιγμένο ρεύμα output και προωθεί την τρέχουσα θέση σε αυτήν τη ροή κατά τον αριθμό των byte που γράφτηκαν. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.Html.IO](../../aspose.html.io/)
* συνέλευση [Aspose.HTML](../../)


