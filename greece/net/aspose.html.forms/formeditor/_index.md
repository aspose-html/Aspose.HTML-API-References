---
title: Class FormEditor
second_title: Aspose.HTML για Αναφορά API .NET
description: Aspose.Html.Forms.FormEditor τάξη. Αυτή η κλάση αντιπροσωπεύει τον επεξεργαστή πάνω από τοHTMLFormElement που δημιουργεί έναν ευκολότερο τρόπο για τους προγραμματιστές .net να επεξεργάζονται τις φόρμες html.
type: docs
weight: 2930
url: /el/net/aspose.html.forms/formeditor/
---
## FormEditor class

Αυτή η κλάση αντιπροσωπεύει τον επεξεργαστή πάνω από το[`HTMLFormElement`](../../aspose.html/htmlformelement/) που δημιουργεί έναν ευκολότερο τρόπο για τους προγραμματιστές .net να επεξεργάζονται τις φόρμες html.

```csharp
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Action](../../aspose.html.forms/formeditor/action/) { get; set; } | Πρόγραμμα χειρισμού φορμών από την πλευρά του διακομιστή. Δείτε τον ορισμό του χαρακτηριστικού δράσης στην HTML 4.01. |
| [Count](../../aspose.html.forms/formeditor/count/) { get; } | Ο αριθμός των στοιχείων ελέγχου φόρμας στη φόρμα. |
| [Form](../../aspose.html.forms/formeditor/form/) { get; } | Το πρωτότυπο[`HTMLFormElement`](../../aspose.html/htmlformelement/) που σχετίζεται με την τρέχουσα παρουσία του`FormEditor` . |
| [Item](../../aspose.html.forms/formeditor/item/) { get; } | Επιστρέφει το στοιχείο κατά καθορισμένο ευρετήριο. (2 indexers) |
| [Method](../../aspose.html.forms/formeditor/method/) { get; set; } | Μέθοδος HTTP [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt) χρησιμοποιείται για την υποβολή φόρμας. Δείτε τον ορισμό του χαρακτηριστικού της μεθόδου στην HTML 4.01. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [Create](../../aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | Δημιουργεί ένα νέο`FormEditor` βασισμένο στο[`HTMLFormElement`](../../aspose.html/htmlformelement/) . |
| static [Create](../../aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | Δημιουργεί ένα νέο`FormEditor` βασισμένο στο[`HTMLFormElement`](../../aspose.html/htmlformelement/) επιλεγμένο από το[`Forms`](../../aspose.html/htmldocument/forms/) συλλογή κατά ευρετήριο. |
| static [Create](../../aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, string) | Δημιουργεί ένα νέο`FormEditor` βασισμένο στο[`HTMLFormElement`](../../aspose.html/htmlformelement/) επιλεγμένο από το έγγραφο με id. |
| static [CreateNew](../../aspose.html.forms/formeditor/createnew/)(HTMLDocument) | Δημιουργεί ένα νέο[`HTMLFormElement`](../../aspose.html/htmlformelement/) και το συσχέτισε με`FormEditor` .[`HTMLFormElement`](../../aspose.html/htmlformelement/) δημιουργείται σε κατάσταση αποσύνδεσης από το έγγραφο. για να το επισυνάψετε στο έγγραφο, επιλέξτε τη σωστή θέση και χρήση[`AppendChild`](../../aspose.html.dom/node/appendchild/) μέθοδος. |
| [Add&lt;T&gt;](../../aspose.html.forms/formeditor/add/)(string) | Δημιουργεί ένα νέο[`HTMLElement`](../../aspose.html/htmlelement/) και το προσθέτει στο τέλος της φόρμας. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput)(string) | Δημιουργεί ένα νέο[`InputElement`](../inputelement/) και το προσθέτει στο τέλος της φόρμας. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput_1)(string, InputElementType) | Δημιουργεί ένα νέο[`InputElement`](../inputelement/) και το προσθέτει στο τέλος της φόρμας. |
| [Dispose](../../aspose.html.forms/formeditor/dispose/)() | Απελευθερώνει μη διαχειριζόμενους και διαχειριζόμενους πόρους. |
| [Fill](../../aspose.html.forms/formeditor/fill/)(Dictionary&lt;string, string&gt;) | Αυτή η μέθοδος συμπληρώνει ολόκληρη τη φόρμα με τις καθορισμένες τιμές. |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement)(int) | Επιστρέφει το στοιχείο κατά καθορισμένο ευρετήριο. |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement_1)(string) | Επιστρέφει το στοιχείο με καθορισμένο όνομα. |
| [GetEnumerator](../../aspose.html.forms/formeditor/getenumerator/)() | Παίρνει τον απαριθμητή. |

### Δείτε επίσης

* class [FormElement](../formelement/)
* χώρος ονομάτων [Aspose.Html.Forms](../../aspose.html.forms/)
* συνέλευση [Aspose.HTML](../../)


