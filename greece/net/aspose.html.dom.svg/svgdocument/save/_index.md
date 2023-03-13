---
title: SVGDocument.Save
second_title: Aspose.HTML για Αναφορά API .NET
description: SVGDocument μέθοδος. Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται απόurl Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν στο σε παρακείμενο φάκελο το όνομα του οποίου θα κατασκευαστεί ως output_file_name  _files.
type: docs
weight: 90
url: /el/net/aspose.html.dom.svg/svgdocument/save/
---
## Save(Url) {#save_3}

Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από`url` Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν στο σε παρακείμενο φάκελο, το όνομα του οποίου θα κατασκευαστεί ως: output_file_name + "_files".

```csharp
public void Save(Url url)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Τοπική διεύθυνση URL στο αρχείο εξόδου. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentException | Αυξάνεται εάν το καθορισμένο`url` δεν είναι έγκυρη διεύθυνση URL τοπικού αρχείου. |

### Δείτε επίσης

* class [Url](../../../aspose.html/url/)
* class [SVGDocument](../)
* χώρος ονομάτων [Aspose.Html.Dom.Svg](../../svgdocument/)
* συνέλευση [Aspose.HTML](../../../)

---

## Save(string) {#save_6}

Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από`μονοπάτι` Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν στο σε παρακείμενο φάκελο, το όνομα του οποίου θα κατασκευαστεί ως: output_file_name + "_files".

```csharp
public void Save(string path)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | String | Τοπική διαδρομή προς το αρχείο εξόδου. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentException | Αυξάνεται εάν το καθορισμένο`μονοπάτι` δεν είναι έγκυρη τοπική διαδρομή αρχείου. |

### Δείτε επίσης

* class [SVGDocument](../)
* χώρος ονομάτων [Aspose.Html.Dom.Svg](../../svgdocument/)
* συνέλευση [Aspose.HTML](../../../)

---

## Save(IOutputStorage) {#save}

Αποθηκεύει το περιεχόμενο και τους πόρους του εγγράφου στον χώρο αποθήκευσης εξόδου.

```csharp
public void Save(IOutputStorage outputStorage)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| outputStorage | IOutputStorage | Η αποθήκευση εξόδου[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |

### Δείτε επίσης

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [SVGDocument](../)
* χώρος ονομάτων [Aspose.Html.Dom.Svg](../../svgdocument/)
* συνέλευση [Aspose.HTML](../../../)

---

## Save(string, SVGSaveFormat) {#save_7}

Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από`μονοπάτι` Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν στο σε παρακείμενο φάκελο, το όνομα του οποίου θα κατασκευαστεί ως: output_file_name + "_files".

```csharp
public void Save(string path, SVGSaveFormat saveFormat)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | String | Τοπική διαδρομή προς το αρχείο εξόδου. |
| saveFormat | SVGSaveFormat | Μορφοποίηση στην οποία αποθηκεύεται το έγγραφο. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentException | Αυξάνεται εάν το καθορισμένο`μονοπάτι` δεν είναι έγκυρη τοπική διαδρομή αρχείου. |

### Δείτε επίσης

* enum [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* χώρος ονομάτων [Aspose.Html.Dom.Svg](../../svgdocument/)
* συνέλευση [Aspose.HTML](../../../)

---

## Save(IOutputStorage, SVGSaveFormat) {#save_1}

Αποθηκεύει το περιεχόμενο και τους πόρους του εγγράφου στον χώρο αποθήκευσης εξόδου.

```csharp
public void Save(IOutputStorage outputStorage, SVGSaveFormat saveFormat)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| outputStorage | IOutputStorage | Η αποθήκευση εξόδου[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveFormat | SVGSaveFormat | Μορφοποίηση στην οποία αποθηκεύεται το έγγραφο. |

### Δείτε επίσης

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* enum [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* χώρος ονομάτων [Aspose.Html.Dom.Svg](../../svgdocument/)
* συνέλευση [Aspose.HTML](../../../)

---

## Save(string, SVGSaveOptions) {#save_8}

Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από`μονοπάτι` Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν στο σε παρακείμενο φάκελο, το όνομα του οποίου θα κατασκευαστεί ως: output_file_name + "_files".

```csharp
public void Save(string path, SVGSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | String | Τοπική διαδρομή προς το αρχείο εξόδου. |
| saveOptions | SVGSaveOptions | Επιλογές αποθήκευσης SVG. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentException | Αυξάνεται εάν το καθορισμένο`μονοπάτι` δεν είναι έγκυρη τοπική διαδρομή αρχείου. |

### Δείτε επίσης

* class [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* χώρος ονομάτων [Aspose.Html.Dom.Svg](../../svgdocument/)
* συνέλευση [Aspose.HTML](../../../)

---

## Save(IOutputStorage, SVGSaveOptions) {#save_2}

Αποθηκεύει το περιεχόμενο και τους πόρους του εγγράφου στον χώρο αποθήκευσης εξόδου.

```csharp
public void Save(IOutputStorage outputStorage, SVGSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| outputStorage | IOutputStorage | Η αποθήκευση εξόδου[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveOptions | SVGSaveOptions | Επιλογές αποθήκευσης SVG. |

### Δείτε επίσης

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* χώρος ονομάτων [Aspose.Html.Dom.Svg](../../svgdocument/)
* συνέλευση [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveFormat) {#save_4}

Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από`url` Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν στο σε παρακείμενο φάκελο, το όνομα του οποίου θα κατασκευαστεί ως: output_file_name + "_files".

```csharp
public void Save(Url url, SVGSaveFormat saveFormat)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Τοπική διεύθυνση URL στο αρχείο εξόδου. |
| saveFormat | SVGSaveFormat | Μορφοποίηση στην οποία αποθηκεύεται το έγγραφο. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentException | Αυξάνεται εάν το καθορισμένο`url` δεν είναι έγκυρη διεύθυνση URL τοπικού αρχείου. |

### Δείτε επίσης

* class [Url](../../../aspose.html/url/)
* enum [SVGSaveFormat](../../../aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* χώρος ονομάτων [Aspose.Html.Dom.Svg](../../svgdocument/)
* συνέλευση [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveOptions) {#save_5}

Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από`url` Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν στο σε παρακείμενο φάκελο, το όνομα του οποίου θα κατασκευαστεί ως: output_file_name + "_files".

```csharp
public void Save(Url url, SVGSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Τοπική διεύθυνση URL στο αρχείο εξόδου. |
| saveOptions | SVGSaveOptions | Επιλογές αποθήκευσης SVG. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentException | Αυξάνεται εάν το καθορισμένο`url` δεν είναι έγκυρη διεύθυνση URL τοπικού αρχείου. |

### Δείτε επίσης

* class [Url](../../../aspose.html/url/)
* class [SVGSaveOptions](../../../aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* χώρος ονομάτων [Aspose.Html.Dom.Svg](../../svgdocument/)
* συνέλευση [Aspose.HTML](../../../)


