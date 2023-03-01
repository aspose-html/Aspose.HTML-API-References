---
title: HTMLDocument.Save
second_title: Aspose.HTML για Αναφορά API .NET
description: HTMLDocument μέθοδος. Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται απόurl Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν στο σε παρακείμενο φάκελο το όνομα του οποίου θα κατασκευαστεί ως output_file_name  _files.
type: docs
weight: 130
url: /el/net/aspose.html/htmldocument/save/
---
## Save(Url) {#save_5}

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

* class [Url](../../url/)
* class [HTMLDocument](../)
* χώρος ονομάτων [Aspose.Html](../../htmldocument/)
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
* class [HTMLDocument](../)
* χώρος ονομάτων [Aspose.Html](../../htmldocument/)
* συνέλευση [Aspose.HTML](../../../)

---

## Save(string) {#save_10}

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

* class [HTMLDocument](../)
* χώρος ονομάτων [Aspose.Html](../../htmldocument/)
* συνέλευση [Aspose.HTML](../../../)

---

## Save(string, HTMLSaveFormat) {#save_11}

Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από`μονοπάτι` Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν στο σε παρακείμενο φάκελο, το όνομα του οποίου θα κατασκευαστεί ως: output_file_name + "_files".

```csharp
public void Save(string path, HTMLSaveFormat saveFormat)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | String | Τοπική διαδρομή προς το αρχείο εξόδου. |
| saveFormat | HTMLSaveFormat | Μορφοποίηση στην οποία αποθηκεύεται το έγγραφο. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentException | Αυξάνεται εάν το καθορισμένο`μονοπάτι` δεν είναι έγκυρη τοπική διαδρομή αρχείου. |

### Δείτε επίσης

* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* χώρος ονομάτων [Aspose.Html](../../htmldocument/)
* συνέλευση [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveFormat) {#save_6}

Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από`url` Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν στο σε παρακείμενο φάκελο, το όνομα του οποίου θα κατασκευαστεί ως: output_file_name + "_files".

```csharp
public void Save(Url url, HTMLSaveFormat saveFormat)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Τοπική διεύθυνση URL στο αρχείο εξόδου. |
| saveFormat | HTMLSaveFormat | Μορφοποίηση στην οποία αποθηκεύεται το έγγραφο. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentException | Αυξάνεται εάν το καθορισμένο`url` δεν είναι έγκυρη διεύθυνση URL τοπικού αρχείου. |

### Δείτε επίσης

* class [Url](../../url/)
* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* χώρος ονομάτων [Aspose.Html](../../htmldocument/)
* συνέλευση [Aspose.HTML](../../../)

---

## Save(IOutputStorage, HTMLSaveFormat) {#save_1}

Αποθηκεύει το περιεχόμενο και τους πόρους του εγγράφου στον χώρο αποθήκευσης εξόδου.

```csharp
public void Save(IOutputStorage outputStorage, HTMLSaveFormat saveFormat)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| outputStorage | IOutputStorage | Η αποθήκευση εξόδου[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveFormat | HTMLSaveFormat | Μορφοποίηση στην οποία αποθηκεύεται το έγγραφο. |

### Δείτε επίσης

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* enum [HTMLSaveFormat](../../../aspose.html.saving/htmlsaveformat/)
* class [HTMLDocument](../)
* χώρος ονομάτων [Aspose.Html](../../htmldocument/)
* συνέλευση [Aspose.HTML](../../../)

---

## Save(string, HTMLSaveOptions) {#save_12}

Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από`μονοπάτι` Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν στο σε παρακείμενο φάκελο, το όνομα του οποίου θα κατασκευαστεί ως: output_file_name + "_files".

```csharp
public void Save(string path, HTMLSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | String | Τοπική διαδρομή προς το αρχείο εξόδου. |
| saveOptions | HTMLSaveOptions | Επιλογές αποθήκευσης HTML. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentException | Αυξάνεται εάν το καθορισμένο`μονοπάτι` δεν είναι έγκυρη τοπική διαδρομή αρχείου. |

### Δείτε επίσης

* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* χώρος ονομάτων [Aspose.Html](../../htmldocument/)
* συνέλευση [Aspose.HTML](../../../)

---

## Save(Url, HTMLSaveOptions) {#save_7}

Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από`url` Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν στο σε παρακείμενο φάκελο, το όνομα του οποίου θα κατασκευαστεί ως: output_file_name + "_files".

```csharp
public void Save(Url url, HTMLSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Τοπική διεύθυνση URL στο αρχείο εξόδου. |
| saveOptions | HTMLSaveOptions | Επιλογές αποθήκευσης HTML. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentException | Αυξάνεται εάν το καθορισμένο`url` δεν είναι έγκυρη διεύθυνση URL τοπικού αρχείου. |

### Δείτε επίσης

* class [Url](../../url/)
* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* χώρος ονομάτων [Aspose.Html](../../htmldocument/)
* συνέλευση [Aspose.HTML](../../../)

---

## Save(IOutputStorage, HTMLSaveOptions) {#save_2}

Αποθηκεύει το περιεχόμενο και τους πόρους του εγγράφου στον χώρο αποθήκευσης εξόδου.

```csharp
public void Save(IOutputStorage outputStorage, HTMLSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| outputStorage | IOutputStorage | Η αποθήκευση εξόδου[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveOptions | HTMLSaveOptions | Επιλογές αποθήκευσης HTML. |

### Δείτε επίσης

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [HTMLSaveOptions](../../../aspose.html.saving/htmlsaveoptions/)
* class [HTMLDocument](../)
* χώρος ονομάτων [Aspose.Html](../../htmldocument/)
* συνέλευση [Aspose.HTML](../../../)

---

## Save(string, MarkdownSaveOptions) {#save_13}

Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από`μονοπάτι` Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν στο σε παρακείμενο φάκελο, το όνομα του οποίου θα κατασκευαστεί ως: output_file_name + "_files".

```csharp
public void Save(string path, MarkdownSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | String | Τοπική διαδρομή προς το αρχείο εξόδου. |
| saveOptions | MarkdownSaveOptions | Επιλογές αποθήκευσης Markdown. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentException | Αυξάνεται εάν το καθορισμένο`μονοπάτι` δεν είναι έγκυρη τοπική διαδρομή αρχείου. |

### Δείτε επίσης

* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* χώρος ονομάτων [Aspose.Html](../../htmldocument/)
* συνέλευση [Aspose.HTML](../../../)

---

## Save(Url, MarkdownSaveOptions) {#save_8}

Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από`url` Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν στο σε παρακείμενο φάκελο, το όνομα του οποίου θα κατασκευαστεί ως: output_file_name + "_files".

```csharp
public void Save(Url url, MarkdownSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Τοπική διεύθυνση URL στο αρχείο εξόδου. |
| saveOptions | MarkdownSaveOptions | Επιλογές αποθήκευσης Markdown. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentException | Αυξάνεται εάν το καθορισμένο`url` δεν είναι έγκυρη διεύθυνση URL τοπικού αρχείου. |

### Δείτε επίσης

* class [Url](../../url/)
* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* χώρος ονομάτων [Aspose.Html](../../htmldocument/)
* συνέλευση [Aspose.HTML](../../../)

---

## Save(IOutputStorage, MarkdownSaveOptions) {#save_3}

Αποθηκεύει το περιεχόμενο και τους πόρους του εγγράφου στον χώρο αποθήκευσης εξόδου.

```csharp
public void Save(IOutputStorage outputStorage, MarkdownSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| outputStorage | IOutputStorage | Η αποθήκευση εξόδου[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveOptions | MarkdownSaveOptions | Επιλογές αποθήκευσης Markdown. |

### Δείτε επίσης

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [MarkdownSaveOptions](../../../aspose.html.saving/markdownsaveoptions/)
* class [HTMLDocument](../)
* χώρος ονομάτων [Aspose.Html](../../htmldocument/)
* συνέλευση [Aspose.HTML](../../../)

---

## Save(string, MHTMLSaveOptions) {#save_14}

Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από`μονοπάτι` Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν στο σε παρακείμενο φάκελο, το όνομα του οποίου θα κατασκευαστεί ως: output_file_name + "_files".

```csharp
public void Save(string path, MHTMLSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | String | Τοπική διαδρομή προς το αρχείο εξόδου. |
| saveOptions | MHTMLSaveOptions | Επιλογές αποθήκευσης MHTML. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentException | Αυξάνεται εάν το καθορισμένο`μονοπάτι` δεν είναι έγκυρη τοπική διαδρομή αρχείου. |

### Δείτε επίσης

* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* χώρος ονομάτων [Aspose.Html](../../htmldocument/)
* συνέλευση [Aspose.HTML](../../../)

---

## Save(Url, MHTMLSaveOptions) {#save_9}

Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από`url` Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν στο σε παρακείμενο φάκελο, το όνομα του οποίου θα κατασκευαστεί ως: output_file_name + "_files".

```csharp
public void Save(Url url, MHTMLSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Τοπική διεύθυνση URL στο αρχείο εξόδου. |
| saveOptions | MHTMLSaveOptions | Επιλογές αποθήκευσης MHTML. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentException | Αυξάνεται εάν το καθορισμένο`url` δεν είναι έγκυρη διεύθυνση URL τοπικού αρχείου. |

### Δείτε επίσης

* class [Url](../../url/)
* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* χώρος ονομάτων [Aspose.Html](../../htmldocument/)
* συνέλευση [Aspose.HTML](../../../)

---

## Save(IOutputStorage, MHTMLSaveOptions) {#save_4}

Αποθηκεύει το περιεχόμενο και τους πόρους του εγγράφου στον χώρο αποθήκευσης εξόδου.

```csharp
public void Save(IOutputStorage outputStorage, MHTMLSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| outputStorage | IOutputStorage | Η αποθήκευση εξόδου[`IOutputStorage`](../../../aspose.html.io/ioutputstorage/). |
| saveOptions | MHTMLSaveOptions | Επιλογές αποθήκευσης MHTML. |

### Δείτε επίσης

* interface [IOutputStorage](../../../aspose.html.io/ioutputstorage/)
* class [MHTMLSaveOptions](../../../aspose.html.saving/mhtmlsaveoptions/)
* class [HTMLDocument](../)
* χώρος ονομάτων [Aspose.Html](../../htmldocument/)
* συνέλευση [Aspose.HTML](../../../)


