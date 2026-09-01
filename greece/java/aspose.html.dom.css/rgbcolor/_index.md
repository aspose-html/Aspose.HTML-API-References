---
title: "Κλάση RGBColor"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.css.RGBColor class. Η διεπαφή RGBColor χρησιμοποιείται για την αναπαράσταση οποιασδήποτε τιμής χρώματος RGB. Αυτή η διεπαφή αντικατοπτρίζει τις τιμές στην υποκείμενη ιδιότητα style. Συνεπώς, οι τροποποιήσεις που γίνονται στα αντικείμενα CSSPrimitiveValue τροποποιούν την ιδιότητα style."
type: docs

url: /el/java/com.aspose.html.dom.css/rgbcolor/
---
## RGBColor class

Η διεπαφή RGBColor χρησιμοποιείται για την αναπαράσταση οποιασδήποτε τιμής χρώματος RGB. Αυτή η διεπαφή αντικατοπτρίζει τις τιμές στην υποκείμενη ιδιότητα στυλ. Συνεπώς, οι τροποποιήσεις που γίνονται στα αντικείμενα CSSPrimitiveValue τροποποιούν την ιδιότητα στυλ.

Ένα καθορισμένο χρώμα RGB δεν περικόπτεται (ακόμη και αν ο αριθμός είναι εκτός του εύρους 0-255 ή 0%-100%). Ένα υπολογισμένο χρώμα RGB περικόπτεται ανάλογα με τη συσκευή.

Ακόμη και αν ένα φύλλο στυλ μπορεί να περιέχει μόνο έναν ακέραιο για μια τιμή χρώματος, η εσωτερική αποθήκευση αυτού του ακέραιου είναι δεκαδικός αριθμός, και αυτός μπορεί να χρησιμοποιηθεί ως δεκαδικός αριθμός στο καθορισμένο ή το υπολογισμένο στυλ.

Μια τιμή χρώματος σε ποσοστό μπορεί πάντα να μετατραπεί σε αριθμό και αντίστροφα.

```java
public class RGBColor : DOMObject
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [getAlpha](../../com.aspose.html.dom.css/rgbcolor/alpha/) Λαμβάνει την τιμή του συστατικού alpha αυτής της δομής Color. |
| [getBlue](../../com.aspose.html.dom.css/rgbcolor/blue/) Λαμβάνει την τιμή του συστατικού blue αυτής της δομής Color. |
| [getGreen](../../com.aspose.html.dom.css/rgbcolor/green/) Λαμβάνει την τιμή του συστατικού green αυτής της δομής Color. |
| [getRed](../../com.aspose.html.dom.css/rgbcolor/red/) Λαμβάνει την τιμή του συστατικού red αυτής της δομής Color. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του αντικειμένου ECMAScript. |
| [toNative](../../com.aspose.html.dom.css/rgbcolor/tonative/)() | Μετατρέπει σε αντικείμενο εγγενούς χρώματος. |

## Παρατηρήσεις

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Αναφορά

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### Δείτε επίσης

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
