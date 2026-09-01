---
title: "Document.Navigate"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Μέθοδος Document. Φορτώνει το έγγραφο στη συγκεκριμένη διεύθυνση Uniform Resource Locator URL στην τρέχουσα παρουσία, αντικαθιστώντας το προηγούμενο περιεχόμενο."
type: docs

url: /el/java/com.aspose.html.dom/document/navigate/
---
## Navigate(String) {#navigate_4}

Φορτώνει το έγγραφο στη συγκεκριμένη Uniform Resource Locator (URL) στην τρέχουσα παρουσία, αντικαθιστώντας το προηγούμενο περιεχόμενο.

```java
public void Navigate(String address)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| διεύθυνση | String | Η διεύθυνση του εγγράφου. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει ένα απόλυτο URL. |

### Δείτε επίσης

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

Φορτώνει το έγγραφο στη συγκεκριμένη Uniform Resource Locator (URL) στην τρέχουσα παρουσία, αντικαθιστώντας το προηγούμενο περιεχόμενο.

```java
public void Navigate(Url url)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Η διεύθυνση URL του εγγράφου. |

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, String) {#navigate_6}

Φορτώνει το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο.

```java
public void Navigate(String content, String baseUri)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | Το περιεχόμενο του εγγράφου. |
| baseUri | String | Το base URI για την επίλυση σχετικών πόρων. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει μια απόλυτη URL. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | `baseUri` είναι `null`. |

### Δείτε επίσης

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, Url) {#navigate_5}

Φορτώνει το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο.

```java
public void Navigate(String content, Url baseUri)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | String | Το περιεχόμενο του εγγράφου. |
| baseUri | Url | Το base URI για την επίλυση σχετικών πόρων. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | `baseUri` είναι `null`. |

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, String) {#navigate_3}

Φορτώνει το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο. Η φόρτωση του εγγράφου ξεκινά από τη τρέχουσα θέση στη ροή.

```java
public void Navigate(Stream content, String baseUri)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | Ροή | Το περιεχόμενο του εγγράφου. |
| baseUri | String | Το base URI για την επίλυση σχετικών πόρων. Θα συνδυαστεί με τη διαδρομή του τρέχοντος καταλόγου για να δημιουργήσει μια απόλυτη URL. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | `baseUri` είναι `null`. |

### Δείτε επίσης

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

Φορτώνει το έγγραφο από το καθορισμένο περιεχόμενο και χρησιμοποιώντας το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο. Η φόρτωση του εγγράφου ξεκινά από τη τρέχουσα θέση στη ροή.

```java
public void Navigate(Stream content, Url baseUri)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| περιεχόμενο | Ροή | Το περιεχόμενο του εγγράφου. |
| baseUri | Url | Το base URI για την επίλυση σχετικών πόρων. |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | `baseUri` είναι `null`. |

### Δείτε επίσης

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

Φορτώνει το έγγραφο βάσει του καθορισμένου αντικειμένου αίτησης, αντικαθιστώντας το προηγούμενο περιεχόμενο.

```java
public void Navigate(RequestMessage request)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αίτημα | RequestMessage | Το αντικείμενο request που χρησιμοποιείται για τη φόρτωση του περιεχομένου του εγγράφου. |

### Δείτε επίσης

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
