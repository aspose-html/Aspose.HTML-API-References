---
title: "IXPathNSResolver Interface"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.xpath.IXPathNSResolver interface. Η διεπαφή XPathNSResolver επιτρέπει στα Strings προθέματος στην έκφραση να δεσμεύονται σωστά σε Strings packageURI. Το IXPathEvaluator μπορεί να κατασκευάσει μια υλοποίηση του IXPathNSResolver από έναν κόμβο ή η διεπαφή μπορεί να υλοποιηθεί από οποιαδήποτε εφαρμογή"
type: docs

url: /el/java/com.aspose.html.dom.xpath/ixpathnsresolver/
---
## IXPathNSResolver interface

Το `XPathNSResolver` interface επιτρέπει στα `prefix` Strings στην έκφραση να δεσμεύονται σωστά σε `packageURI` Strings. [`IXPathEvaluator`](../ixpathevaluator/) μπορεί να κατασκευάσει μια υλοποίηση του `IXPathNSResolver` από έναν κόμβο, ή η διεπαφή μπορεί να υλοποιηθεί από οποιαδήποτε εφαρμογή.

```java
public interface IXPathNSResolver
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [lookupNamespaceURI](../../com.aspose.html.dom.xpath/ixpathnsresolver/lookuppackageuri/)(String) | Αναζητήστε το URI του πακέτου που σχετίζεται με το δεδομένο πρόθεμα πακέτου. Ο αξιολογητής XPath δεν πρέπει ποτέ να καλέσει αυτό με όρισμα `null` ή κενό, επειδή το αποτέλεσμα αυτής της κλήσης είναι ακαθόριστο. |

### Δείτε επίσης

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
