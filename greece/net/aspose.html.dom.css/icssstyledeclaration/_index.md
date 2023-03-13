---
title: Interface ICSSStyleDeclaration
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Dom.Css.ICSSStyleDeclaration διεπαφή. Η διεπαφή CSSStyleDeclaration αντιπροσωπεύει ένα ενιαίο μπλοκ δήλωσης CSS. Αυτή η διεπαφή μπορεί να χρησιμοποιηθεί για τον προσδιορισμό των ιδιοτήτων στυλ που ορίζονται αυτήν τη στιγμή σε ένα μπλοκ ή για τον ορισμό ιδιοτήτων στυλ ρητά εντός του μπλοκ.
type: docs
weight: 490
url: /el/net/aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

Η διεπαφή CSSStyleDeclaration αντιπροσωπεύει ένα ενιαίο μπλοκ δήλωσης CSS. Αυτή η διεπαφή μπορεί να χρησιμοποιηθεί για τον προσδιορισμό των ιδιοτήτων στυλ που ορίζονται αυτήν τη στιγμή σε ένα μπλοκ ή για τον ορισμό ιδιοτήτων στυλ ρητά εντός του μπλοκ.

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [CSSText](../../aspose.html.dom.css/icssstyledeclaration/csstext/) { get; set; } | Η αναλυόμενη κειμενική αναπαράσταση του μπλοκ δήλωσης (εξαιρουμένων των γύρω σγουρά άγκιστρα). Η ρύθμιση αυτού του χαρακτηριστικού θα έχει ως αποτέλεσμα την ανάλυση της νέας τιμής και την επαναφορά όλων των ιδιοτήτων στο μπλοκ δήλωσης, συμπεριλαμβανομένης της αφαίρεσης ή της προσθήκης ιδιοτήτων. |
| [Item](../../aspose.html.dom.css/icssstyledeclaration/item/) { get; } | Χρησιμοποιείται για την ανάκτηση των ιδιοτήτων που έχουν οριστεί ρητά σε αυτό το μπλοκ δήλωσης. Η σειρά των ιδιοτήτων που ανακτήθηκαν χρησιμοποιώντας αυτήν τη μέθοδο δεν χρειάζεται να είναι η σειρά με την οποία ορίστηκαν. Αυτή η μέθοδος μπορεί να χρησιμοποιηθεί για επανάληψη σε όλες τις ιδιότητες σε αυτό το μπλοκ δήλωσης. |
| [Length](../../aspose.html.dom.css/icssstyledeclaration/length/) { get; } | Ο αριθμός των ιδιοτήτων που έχουν οριστεί ρητά σε αυτό το μπλοκ δήλωσης. Το εύρος των έγκυρων δεικτών είναι από 0 έως μήκος-1 συμπεριλαμβανομένου. |
| [ParentRule](../../aspose.html.dom.css/icssstyledeclaration/parentrule/) { get; } | Ο κανόνας CSS που περιέχει αυτό το μπλοκ δήλωσης ή είναι null, εάν αυτή η CSSStyleDeclaration δεν είναι συνδεδεμένη σε έναν κανόνα CSS. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(string) | Χρησιμοποιείται για την ανάκτηση της αναπαράστασης αντικειμένου της τιμής μιας ιδιότητας CSS, εάν έχει οριστεί ρητά σε αυτό το μπλοκ δήλωσης. Αυτή η μέθοδος επιστρέφει μηδενική αν η ιδιότητα είναι συντομογραφία. Οι τιμές των συντομογραφικών ιδιοτήτων μπορούν να προσπελαστούν και να τροποποιηθούν μόνο ως συμβολοσειρές, χρησιμοποιώντας τις μεθόδους getPropertyValue και setProperty. |
| [GetPropertyPriority](../../aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(string) | Χρησιμοποιείται για την ανάκτηση της προτεραιότητας μιας ιδιότητας CSS (π.χ. του προσδιοριστικού "σημαντικού") εάν η ιδιότητα έχει οριστεί ρητά σε αυτό το μπλοκ δήλωσης. |
| [GetPropertyValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(string) | Χρησιμοποιείται για την ανάκτηση της τιμής μιας ιδιότητας CSS, εάν έχει οριστεί ρητά σε αυτό το μπλοκ δήλωσης. |
| [RemoveProperty](../../aspose.html.dom.css/icssstyledeclaration/removeproperty/)(string) | Χρησιμοποιείται για την αφαίρεση μιας ιδιότητας CSS εάν έχει οριστεί ρητά σε αυτό το μπλοκ δήλωσης. |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(string, string) | Χρησιμοποιείται για τον ορισμό μιας τιμής ιδιότητας με προεπιλεγμένη προτεραιότητα σε αυτό το μπλοκ δήλωσης. Η προεπιλεγμένη προτεραιότητα δεν είναι "σημαντική", π.χ. String.Empty |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(string, string, string) | Χρησιμοποιείται για τον ορισμό τιμής ιδιότητας και προτεραιότητας σε αυτό το μπλοκ δήλωσης. |

### Δείτε επίσης

* interface [ICSS2Properties](../icss2properties/)
* χώρος ονομάτων [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* συνέλευση [Aspose.HTML](../../)


