---
title: "SVGDocument.Save"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος SVGDocument. Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από το url. Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν σε γειτονικό φάκελο του οποίου το όνομα θα κατασκευαστεί ως output_file_name  _files"
type: docs

url: /el/java/com.aspose.html.dom.svg/svgdocument/save/
---
## Save(Url) {#save_3}

Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από το `url`. Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν σε διπλανό φάκελο, του οποίου το όνομα θα κατασκευαστεί ως: output_file_name + "_files".

```java
public void Save(Url url)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Τοπική URL για το αρχείο εξόδου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εγείρεται εάν το καθορισμένο `url` δεν είναι έγκυρη τοπική URL αρχείου. |

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String) {#save_6}

Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από το `path`. Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν σε διπλανό φάκελο, του οποίου το όνομα θα κατασκευαστεί ως: output_file_name + "_files".

```java
public void Save(String path)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| διαδρομή | String | Τοπική διαδρομή για το αρχείο εξόδου. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εγείρεται εάν η καθορισμένη `path` δεν είναι έγκυρη τοπική διαδρομή αρχείου. |

### Δείτε επίσης

* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler) {#save}

Αποθηκεύει το περιεχόμενο του εγγράφου και τους πόρους χρησιμοποιώντας το [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Ο διαχειριστής πόρων [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |

### Δείτε επίσης

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String, SVGSaveFormat) {#save_7}

Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από το `path`. Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν σε διπλανό φάκελο, του οποίου το όνομα θα κατασκευαστεί ως: output_file_name + "_files".

```java
public void Save(String path, SVGSaveFormat saveFormat)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| διαδρομή | String | Τοπική διαδρομή για το αρχείο εξόδου. |
| saveFormat | SVGSaveFormat | Μορφή στην οποία αποθηκεύεται το έγγραφο. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εγείρεται εάν η καθορισμένη `path` δεν είναι έγκυρη τοπική διαδρομή αρχείου. |

### Δείτε επίσης

* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, SVGSaveFormat) {#save_1}

Αποθηκεύει το περιεχόμενο του εγγράφου και τους πόρους χρησιμοποιώντας το [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, SVGSaveFormat saveFormat)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Ο διαχειριστής πόρων [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveFormat | SVGSaveFormat | Μορφή στην οποία αποθηκεύεται το έγγραφο. |

### Δείτε επίσης

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String, SVGSaveOptions) {#save_8}

Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από το `path`. Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν σε διπλανό φάκελο, του οποίου το όνομα θα κατασκευαστεί ως: output_file_name + "_files".

```java
public void Save(String path, SVGSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| διαδρομή | String | Τοπική διαδρομή για το αρχείο εξόδου. |
| saveOptions | SVGSaveOptions | Επιλογές αποθήκευσης SVG. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εγείρεται εάν η καθορισμένη `path` δεν είναι έγκυρη τοπική διαδρομή αρχείου. |

### Δείτε επίσης

* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, SVGSaveOptions) {#save_2}

Αποθηκεύει το περιεχόμενο του εγγράφου και τους πόρους χρησιμοποιώντας το [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/).

```java
public void Save(ResourceHandler resourceHandler, SVGSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| resourceHandler | ResourceHandler | Ο διαχειριστής πόρων [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/). |
| saveOptions | SVGSaveOptions | Επιλογές αποθήκευσης SVG. |

### Δείτε επίσης

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveFormat) {#save_4}

Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από το `url`. Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν σε διπλανό φάκελο, του οποίου το όνομα θα κατασκευαστεί ως: output_file_name + "_files".

```java
public void Save(Url url, SVGSaveFormat saveFormat)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Τοπική URL για το αρχείο εξόδου. |
| saveFormat | SVGSaveFormat | Μορφή στην οποία αποθηκεύεται το έγγραφο. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εγείρεται εάν το καθορισμένο `url` δεν είναι έγκυρη τοπική URL αρχείου. |

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveOptions) {#save_5}

Αποθηκεύει το έγγραφο σε τοπικό αρχείο που καθορίζεται από το `url`. Όλοι οι πόροι που χρησιμοποιούνται σε αυτό το έγγραφο θα αποθηκευτούν σε διπλανό φάκελο, του οποίου το όνομα θα κατασκευαστεί ως: output_file_name + "_files".

```java
public void Save(Url url, SVGSaveOptions saveOptions)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Τοπική URL για το αρχείο εξόδου. |
| saveOptions | SVGSaveOptions | Επιλογές αποθήκευσης SVG. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentException | Εγείρεται εάν το καθορισμένο `url` δεν είναι έγκυρη τοπική URL αρχείου. |

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
