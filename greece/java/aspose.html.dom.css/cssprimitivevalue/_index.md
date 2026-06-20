---
title: "CSSPrimitiveValue Κλάση"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "com.aspose.html.dom.css.CSSPrimitiveValue κλάση. Η διεπαφή CSSPrimitiveValue προέρχεται από τη διεπαφή CSSValue και αντιπροσωπεύει την τρέχουσα υπολογισμένη τιμή μιας ιδιότητας CSS."
type: docs

url: /el/java/com.aspose.html.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

Η διεπαφή CSSPrimitiveValue προέρχεται από τη διεπαφή CSSValue και αντιπροσωπεύει την τρέχουσα υπολογισμένη τιμή μιας ιδιότητας CSS.

Σημείωση: Αυτή η διεπαφή ήταν μέρος μιας προσπάθειας δημιουργίας ενός τυποποιημένου CSS Object Model. Η προσπάθεια αυτή έχει εγκαταλειφθεί, και οι περισσότεροι browsers δεν την υλοποιούν.

```java
public abstract class CSSPrimitiveValue : CSSValue
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | Η ιδιότητα cssText της διεπαφής [`CSSValue`](../cssvalue/) αντιπροσωπεύει την τρέχουσα υπολογισμένη τιμή ιδιότητας CSS. |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) Ένας κώδικας που ορίζει τον τύπο της τιμής. |
| [getPrimitiveType](../../com.aspose.html.dom.css/cssprimitivevalue/primitivetype/) Ο τύπος της τιμής όπως ορίζεται από τις παραπάνω σταθερές. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | Καθορίζει εάν το συγκεκριμένο Object είναι ίσο με αυτήν την παρουσία. |
| abstract [GetCounterValue](../../com.aspose.html.dom.css/cssprimitivevalue/getcountervalue/)() | Αυτή η μέθοδος χρησιμοποιείται για την απόκτηση της τιμής Counter. Εάν αυτή η τιμή CSS δεν περιέχει τιμή counter, προκαλείται μια DOMException. Η τροποποίηση της αντίστοιχης ιδιότητας στυλ μπορεί να επιτευχθεί χρησιμοποιώντας τη διεπαφή Counter. |
| abstract [GetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/getfloatvalue/)(ushort) | Αυτή η μέθοδος χρησιμοποιείται για την απόκτηση μιας τιμής float σε συγκεκριμένη μονάδα. Εάν αυτή η τιμή CSS δεν περιέχει τιμή float ή δεν μπορεί να μετατραπεί στην καθορισμένη μονάδα, προκαλείται ένα DOMException. |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | Επιστρέφει έναν κωδικό κατακερματισμού για αυτό το αντικείμενο. |
| abstract [GetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/getintvalue/)(ushort) | Αυτή η μέθοδος χρησιμοποιείται για την απόκτηση μιας τιμής int σε συγκεκριμένη μονάδα. Εάν αυτή η τιμή CSS δεν περιέχει τιμή int ή δεν μπορεί να μετατραπεί στην καθορισμένη μονάδα, προκαλείται ένα DOMException. |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | Αυτή η μέθοδος χρησιμοποιείται για την ανάκτηση του τύπου αντικειμένου ECMAScript. |
| abstract [GetRectValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrectvalue/)() | Αυτή η μέθοδος χρησιμοποιείται για την απόκτηση της τιμής Rect. Εάν αυτή η τιμή CSS δεν περιέχει τιμή rect, προκαλείται ένα DOMException. Η τροποποίηση της αντίστοιχης ιδιότητας στυλ μπορεί να επιτευχθεί χρησιμοποιώντας τη διεπαφή Rect. |
| abstract [GetRGBColorValue](../../com.aspose.html.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | Αυτή η μέθοδος χρησιμοποιείται για την απόκτηση του χρώματος RGB. Εάν αυτή η τιμή CSS δεν περιέχει τιμή χρώματος RGB, προκαλείται ένα DOMException. Η τροποποίηση της αντίστοιχης ιδιότητας στυλ μπορεί να επιτευχθεί χρησιμοποιώντας τη διεπαφή RGBColor. |
| abstract [GetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/getStringvalue/)() | Αυτή η μέθοδος χρησιμοποιείται για την απόκτηση της τιμής String. Εάν η τιμή CSS δεν περιέχει τιμή String, προκαλείται ένα DOMException. |
| abstract [SetFloatValue](../../com.aspose.html.dom.css/cssprimitivevalue/setfloatvalue/)(ushort, float) | Μια μέθοδος για τον ορισμό της τιμής float με συγκεκριμένη μονάδα. Εάν η ιδιότητα που συνδέεται με αυτήν την τιμή δεν μπορεί να αποδεχτεί την καθορισμένη μονάδα ή την τιμή float, η τιμή θα παραμείνει αμετάβλητη και θα προκληθεί ένα DOMException. |
| abstract [SetIntValue](../../com.aspose.html.dom.css/cssprimitivevalue/setintvalue/)(ushort, int) | Μια μέθοδος για τον ορισμό της τιμής int με συγκεκριμένη μονάδα. Εάν η ιδιότητα που συνδέεται με αυτήν την τιμή δεν μπορεί να αποδεχτεί την καθορισμένη μονάδα ή την τιμή int, η τιμή θα παραμείνει αμετάβλητη και θα προκληθεί ένα DOMException. |
| abstract [SetStringValue](../../com.aspose.html.dom.css/cssprimitivevalue/setStringvalue/)(ushort, String) | Μια μέθοδος για τον ορισμό της τιμής String με την καθορισμένη μονάδα. Εάν η ιδιότητα που συνδέεται με αυτήν την τιμή δεν μπορεί να αποδεχτεί την καθορισμένη μονάδα ή την τιμή String, η τιμή θα παραμείνει αμετάβλητη και θα προκληθεί ένα DOMException. |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτό το αντικείμενο. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [CSS_ATTR](../../com.aspose.html.dom.css/cssprimitivevalue/css_attr/) | Η τιμή είναι μια συνάρτηση χαρακτηριστικού. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getStringValue. |
| const [CSS_CH](../../com.aspose.html.dom.css/cssprimitivevalue/css_ch/) | Η τιμή είναι ένα μήκος (ch). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_CM](../../com.aspose.html.dom.css/cssprimitivevalue/css_cm/) | Η τιμή είναι ένα μήκος (cm). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_COUNTER](../../com.aspose.html.dom.css/cssprimitivevalue/css_counter/) | Η τιμή είναι μια συνάρτηση counter ή counters. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο GetCounterValue. |
| const [CSS_DEG](../../com.aspose.html.dom.css/cssprimitivevalue/css_deg/) | Η τιμή είναι μια γωνία (deg). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_DIMENSION](../../com.aspose.html.dom.css/cssprimitivevalue/css_dimension/) | Η τιμή είναι ένας αριθμός με άγνωστη διάσταση. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_DPCM](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpcm/) | Η τιμή είναι κουκκίδες ανά εκατοστό (dpcm). |
| const [CSS_DPI](../../com.aspose.html.dom.css/cssprimitivevalue/css_dpi/) | Η τιμή είναι κουκκίδες ανά ίντσα (dpi). |
| const [CSS_DPPX](../../com.aspose.html.dom.css/cssprimitivevalue/css_dppx/) | Η τιμή είναι κουκκίδες ανά μονάδα ‘px’ (dppx). |
| const [CSS_EMS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ems/) | Η τιμή είναι ένα μήκος (ems). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_EXS](../../com.aspose.html.dom.css/cssprimitivevalue/css_exs/) | Η τιμή είναι ένα μήκος (exs). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_GRAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_grad/) | Η τιμή είναι μια γωνία (grad). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_HZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_hz/) | Η τιμή είναι μια συχνότητα (Hz). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_IDENT](../../com.aspose.html.dom.css/cssprimitivevalue/css_ident/) | Η τιμή είναι ένα αναγνωριστικό. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getStringValue. |
| const [CSS_IN](../../com.aspose.html.dom.css/cssprimitivevalue/css_in/) | Η τιμή είναι ένα μήκος (in). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_KHZ](../../com.aspose.html.dom.css/cssprimitivevalue/css_khz/) | Η τιμή είναι μια συχνότητα (kHz). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_MM](../../com.aspose.html.dom.css/cssprimitivevalue/css_mm/) | Η τιμή είναι ένα μήκος (mm). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_MS](../../com.aspose.html.dom.css/cssprimitivevalue/css_ms/) | Η τιμή είναι χρόνος (ms). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_NUMBER](../../com.aspose.html.dom.css/cssprimitivevalue/css_number/) | Η τιμή είναι απλός αριθμός. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_PC](../../com.aspose.html.dom.css/cssprimitivevalue/css_pc/) | Η τιμή είναι μήκος (pc). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_PERCENTAGE](../../com.aspose.html.dom.css/cssprimitivevalue/css_percentage/) | Η τιμή είναι ποσοστό. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_PT](../../com.aspose.html.dom.css/cssprimitivevalue/css_pt/) | Η τιμή είναι μήκος (pt). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_PX](../../com.aspose.html.dom.css/cssprimitivevalue/css_px/) | Η τιμή είναι μήκος (px). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_RAD](../../com.aspose.html.dom.css/cssprimitivevalue/css_rad/) | Η τιμή είναι γωνία (rad). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_RECT](../../com.aspose.html.dom.css/cssprimitivevalue/css_rect/) | Η τιμή είναι συνάρτηση rect. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο GetRectValue. |
| const [CSS_REM](../../com.aspose.html.dom.css/cssprimitivevalue/css_rem/) | Η τιμή είναι μήκος (rem). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_RGBCOLOR](../../com.aspose.html.dom.css/cssprimitivevalue/css_rgbcolor/) | Η τιμή είναι χρώμα RGB. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο GetRGBColorValue. |
| const [CSS_S](../../com.aspose.html.dom.css/cssprimitivevalue/css_s/) | Η τιμή είναι χρόνος (s). Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getFloatValue. |
| const [CSS_STRING](../../com.aspose.html.dom.css/cssprimitivevalue/css_String/) | Η τιμή είναι STRING. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getStringValue. |
| const [CSS_UNKNOWN](../../com.aspose.html.dom.css/cssprimitivevalue/css_unknown/) | Η τιμή δεν είναι αναγνωρισμένη τιμή CSS2. Η τιμή μπορεί να ληφθεί μόνο χρησιμοποιώντας το χαρακτηριστικό cssText. |
| const [CSS_URI](../../com.aspose.html.dom.css/cssprimitivevalue/css_uri/) | Η τιμή είναι URI. Η τιμή μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο getStringValue. |
| const [CSS_VH](../../com.aspose.html.dom.css/cssprimitivevalue/css_vh/) | Η τιμή είναι ποσοστό του πλήρους ύψους του viewport. |
| const [CSS_VMAX](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmax/) | Η τιμή είναι ποσοστό του πλάτους ή του ύψους του viewport, όποιο είναι μεγαλύτερο. |
| const [CSS_VMIN](../../com.aspose.html.dom.css/cssprimitivevalue/css_vmin/) | Η τιμή είναι ποσοστό του πλάτους ή του ύψους του viewport, όποιο είναι μικρότερο. |
| const [CSS_VW](../../com.aspose.html.dom.css/cssprimitivevalue/css_vw/) | Η τιμή είναι ποσοστό του πλήρους πλάτους του viewport. |

### Δείτε επίσης

* class [CSSValue](../cssvalue/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
