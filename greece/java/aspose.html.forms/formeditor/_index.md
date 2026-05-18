---
title: "Κλάση FormEditor"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Η κλάση com.aspose.html.forms.FormEditor. Αυτή η κλάση αναπαριστά τον επεξεργαστή πάνω στο HTMLFormElement που δημιουργεί έναν πιο εύκολο τρόπο για προγραμματιστές .net να επεξεργάζονται τις html φόρμες."
type: docs

url: /el/java/com.aspose.html.forms/formeditor/
---
## FormEditor class

Αυτή η κλάση αναπαριστά τον επεξεργαστή πάνω στο [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) που δημιουργεί έναν πιο εύκολο τρόπο για προγραμματιστές .net να επεξεργάζονται τις html φόρμες.

```java
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
| [getCount](../../com.aspose.html.forms/formeditor/count/) Ο αριθμός των στοιχείων ελέγχου φόρμας στη φόρμα. |
| [getForm](../../com.aspose.html.forms/formeditor/form/) Το αρχικό [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) που συνδέεται με την τρέχουσα παρουσία του `FormEditor`. |
| [getItem](../../com.aspose.html.forms/formeditor/item/) Επιστρέφει το στοιχείο με τον καθορισμένο δείκτη. (2 indexers) |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | Δημιουργεί ένα νέο `FormEditor` βασισμένο στο [`HTMLFormElement`](../../com.aspose.html/htmlformelement/). |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | Δημιουργεί ένα νέο `FormEditor` βασισμένο στο [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) που επιλέγεται από τη συλλογή [`Forms`](../../com.aspose.html/htmldocument/forms/) με βάση τον δείκτη. |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, String) | Δημιουργεί ένα νέο `FormEditor` βασισμένο στο [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) που επιλέγεται από το έγγραφο με βάση το id. |
| static [CreateNew](../../com.aspose.html.forms/formeditor/createnew/)(HTMLDocument) | Δημιουργεί ένα νέο [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) και το συσχετίζει με το `FormEditor`. Το [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) δημιουργείται σε κατάσταση αποσύνδεσης από το έγγραφο· για να το συνδέσετε με το έγγραφο, παρακαλούμε επιλέξτε την κατάλληλη θέση και χρησιμοποιήστε τη μέθοδο [`AppendChild`](../../com.aspose.html.dom/node/appendchild/). |
| [Add&lt;T&gt;](../../com.aspose.html.forms/formeditor/add/)(String) | Δημιουργεί ένα νέο [`HTMLElement`](../../com.aspose.html/htmlelement/) και το προσθέτει στο τέλος της φόρμας. |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput)(String) | Δημιουργεί ένα νέο [`InputElement`](../inputelement/) και το προσθέτει στο τέλος της φόρμας. |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput_1)(String, InputElementType) | Δημιουργεί ένα νέο [`InputElement`](../inputelement/) και το προσθέτει στο τέλος της φόρμας. |
| [dispose](../../com.aspose.html.forms/formeditor/dispose/)() | Απελευθερώνει μη διαχειριζόμενους και διαχειριζόμενους πόρους. |
| [fill](../../com.aspose.html.forms/formeditor/fill/)(Dictionary&lt;String, String&gt;) |  |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement)(int) | Επιστρέφει το στοιχείο με τον καθορισμένο δείκτη. |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement_1)(String) | Επιστρέφει το στοιχείο με το καθορισμένο όνομα. |
| [getEnumerator](../../com.aspose.html.forms/formeditor/getenumerator/)() | Λαμβάνει τον enumerator. |

### Δείτε επίσης

* class [FormElement](../formelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
