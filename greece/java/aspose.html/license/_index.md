---
title: "License Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.License κλάση. Παρέχει μεθόδους για την αδειοδότηση του στοιχείου"
type: docs

url: /el/java/com.aspose.html/license/
---
## License class

Παρέχει μεθόδους για την άδεια του στοιχείου.

```java
public class License
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [License](license/)() | Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense)(Stream) | Αδειοδοτεί το στοιχείο. |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense_1)(String) | Αδειοδοτεί το στοιχείο. |

## Παραδείγματα

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να βρεθεί ένα αρχείο άδειας με όνομα MyLicense.lic στον φάκελο που περιέχει το στοιχείο, στον φάκελο που περιέχει το καλούμενο assembly, στον φάκελο του entry assembly και, τέλος, στους ενσωματωμένους πόρους του καλούμενου assembly.

```java
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

το αρχείο jar του στοιχείου:

```java
License license = new License();
license.setLicense("MyLicense.lic");
```

### Δείτε επίσης

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
