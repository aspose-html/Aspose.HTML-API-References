---
title: "Κλάση CSSValue"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Κλάση com.aspose.html.dom.css.CSSValue. Αντιπροσωπεύει μια απλή ή σύνθετη τιμή. Ένα αντικείμενο CSSValue εμφανίζεται μόνο σε ένα πλαίσιο ιδιότητας CSS."
type: docs

url: /el/java/com.aspose.html.dom.css/cssvalue/
---
## CSSValue class

Αντιπροσωπεύει μια απλή ή σύνθετη τιμή. Ένα αντικείμενο CSSValue εμφανίζεται μόνο σε ένα πλαίσιο ιδιότητας CSS.

```java
public abstract class CSSValue : DOMObject
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | Η ιδιότητα cssText της διεπαφής `CSSValue` αντιπροσωπεύει την τρέχουσα υπολογισμένη τιμή ιδιότητας CSS. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) Ένας κώδικας που ορίζει τον τύπο της τιμής. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | Καθορίζει εάν το καθορισμένο Object είναι ίσο με αυτήν την παρουσία. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | Επιστρέφει έναν κωδικό κατακερματισμού για αυτό το αντικείμενο. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου αντικειμένου ECMAScript. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |
| [operator ==](../../com.aspose.html.dom.css/cssvalue/op_equality/) |  |
| [operator !=](../../com.aspose.html.dom.css/cssvalue/op_inequality/) |  |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [CSS_CUSTOM](../../com.aspose.html.dom.css/cssvalue/css_custom/) | Η τιμή είναι προσαρμοσμένη τιμή. |
| const [CSS_INHERIT](../../com.aspose.html.dom.css/cssvalue/css_inherit/) | Η τιμή κληρονομείται και το cssText περιέχει "inherit". |
| const [CSS_PRIMITIVE_VALUE](../../com.aspose.html.dom.css/cssvalue/css_primitive_value/) | Η τιμή είναι πρωτόγονη τιμή και μπορεί να ληφθεί ένα στιγμιότυπο της διεπαφής CSSPrimitiveValue χρησιμοποιώντας μεθόδους μετατροπής ειδικές για το binding σε αυτό το στιγμιότυπο της διεπαφής CSSValue. |
| const [CSS_VALUE_LIST](../../com.aspose.html.dom.css/cssvalue/css_value_list/) | Η τιμή είναι μια λίστα CSSValue και ένα στιγμιότυπο του interface CSSValueList μπορεί να ληφθεί χρησιμοποιώντας μεθόδους μετατροπής ειδικές για το binding σε αυτό το στιγμιότυπο του interface CSSValue. |

### Δείτε επίσης

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
