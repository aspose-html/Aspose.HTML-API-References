---
title: Document.Navigate
second_title: Aspose.HTML για Αναφορά API .NET
description: Document μέθοδος. Φορτώνει το έγγραφο στον καθορισμένο Uniform Resource Locator URL στην τρέχουσα παρουσία αντικαθιστώντας το προηγούμενο περιεχόμενο.
type: docs
weight: 1010
url: /el/net/aspose.html.dom/document/navigate/
---
## Navigate(string) {#navigate_4}

Φορτώνει το έγγραφο στον καθορισμένο Uniform Resource Locator (URL) στην τρέχουσα παρουσία, αντικαθιστώντας το προηγούμενο περιεχόμενο.

```csharp
public void Navigate(string address)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| address | String | Η διεύθυνση του εγγράφου. Θα συνδυαστεί με την τρέχουσα διαδρομή καταλόγου για να σχηματιστεί μια απόλυτη διεύθυνση URL. |

### Δείτε επίσης

* class [Document](../)
* χώρος ονομάτων [Aspose.Html.Dom](../../document/)
* συνέλευση [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

Φορτώνει το έγγραφο στον καθορισμένο Uniform Resource Locator (URL) στην τρέχουσα παρουσία, αντικαθιστώντας το προηγούμενο περιεχόμενο.

```csharp
public void Navigate(Url url)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | Url | Το URL του εγγράφου. |

### Δείτε επίσης

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* χώρος ονομάτων [Aspose.Html.Dom](../../document/)
* συνέλευση [Aspose.HTML](../../../)

---

## Navigate(string, string) {#navigate_6}

Φορτώνει το έγγραφο από καθορισμένο περιεχόμενο και χρησιμοποιεί το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο.

```csharp
public void Navigate(string content, string baseUri)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| content | String | Το περιεχόμενο του εγγράφου. |
| baseUri | String | Το βασικό URI για την επίλυση σχετικών πόρων. Θα συνδυαστεί με την τρέχουσα διαδρομή καταλόγου για να σχηματιστεί μια απόλυτη διεύθυνση URL. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | `baseUri` είναι`μηδενικό`. |

### Δείτε επίσης

* class [Document](../)
* χώρος ονομάτων [Aspose.Html.Dom](../../document/)
* συνέλευση [Aspose.HTML](../../../)

---

## Navigate(string, Url) {#navigate_5}

Φορτώνει το έγγραφο από καθορισμένο περιεχόμενο και χρησιμοποιεί το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο.

```csharp
public void Navigate(string content, Url baseUri)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| content | String | Το περιεχόμενο του εγγράφου. |
| baseUri | Url | Το βασικό URI για την επίλυση σχετικών πόρων. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | `baseUri` είναι`μηδενικό`. |

### Δείτε επίσης

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* χώρος ονομάτων [Aspose.Html.Dom](../../document/)
* συνέλευση [Aspose.HTML](../../../)

---

## Navigate(Stream, string) {#navigate_3}

Φορτώνει το έγγραφο από καθορισμένο περιεχόμενο και χρησιμοποιεί το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο. Η φόρτωση του εγγράφου ξεκινά από την τρέχουσα θέση στη ροή.

```csharp
public void Navigate(Stream content, string baseUri)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| content | Stream | Το περιεχόμενο του εγγράφου. |
| baseUri | String | Το βασικό URI για την επίλυση σχετικών πόρων. Θα συνδυαστεί με την τρέχουσα διαδρομή καταλόγου για να σχηματιστεί μια απόλυτη διεύθυνση URL. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | `baseUri` είναι`μηδενικό`. |

### Δείτε επίσης

* class [Document](../)
* χώρος ονομάτων [Aspose.Html.Dom](../../document/)
* συνέλευση [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

Φορτώνει το έγγραφο από καθορισμένο περιεχόμενο και χρησιμοποιεί το baseUri για την επίλυση σχετικών πόρων, αντικαθιστώντας το προηγούμενο περιεχόμενο. Η φόρτωση του εγγράφου ξεκινά από την τρέχουσα θέση στη ροή.

```csharp
public void Navigate(Stream content, Url baseUri)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| content | Stream | Το περιεχόμενο του εγγράφου. |
| baseUri | Url | Το βασικό URI για την επίλυση σχετικών πόρων. |

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | `baseUri` είναι`μηδενικό`. |

### Δείτε επίσης

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* χώρος ονομάτων [Aspose.Html.Dom](../../document/)
* συνέλευση [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

Φορτώνει το έγγραφο με βάση το καθορισμένο αντικείμενο αιτήματος, αντικαθιστώντας το προηγούμενο περιεχόμενο.

```csharp
public void Navigate(RequestMessage request)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| request | RequestMessage | Το αντικείμενο αιτήματος που χρησιμοποιείται για τη φόρτωση του περιεχομένου του εγγράφου. |

### Δείτε επίσης

* class [RequestMessage](../../../aspose.html.net/requestmessage/)
* class [Document](../)
* χώρος ονομάτων [Aspose.Html.Dom](../../document/)
* συνέλευση [Aspose.HTML](../../../)


