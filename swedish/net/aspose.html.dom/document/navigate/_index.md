---
title: Document.Navigate
second_title: Aspose.HTML för .NET API Referens
description: Document metod. Laddar dokumentet på den angivna URLadressen Uniform Resource Locator till den aktuella instansen och ersätter det tidigare innehållet.
type: docs
weight: 1010
url: /sv/net/aspose.html.dom/document/navigate/
---
## Navigate(string) {#navigate_4}

Laddar dokumentet på den angivna URL-adressen (Uniform Resource Locator) till den aktuella instansen och ersätter det tidigare innehållet.

```csharp
public void Navigate(string address)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| address | String | Dokumentets adress. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |

### Se även

* class [Document](../)
* namnutrymme [Aspose.Html.Dom](../../document/)
* hopsättning [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

Laddar dokumentet på den angivna URL-adressen (Uniform Resource Locator) till den aktuella instansen och ersätter det tidigare innehållet.

```csharp
public void Navigate(Url url)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | Url | Dokumentets URL. |

### Se även

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* namnutrymme [Aspose.Html.Dom](../../document/)
* hopsättning [Aspose.HTML](../../../)

---

## Navigate(string, string) {#navigate_6}

Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, ersätter det tidigare innehållet.

```csharp
public void Navigate(string content, string baseUri)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Dokumentets innehåll. |
| baseUri | String | Bas-URI för att lösa relativa resurser. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | `baseUri` är`null`. |

### Se även

* class [Document](../)
* namnutrymme [Aspose.Html.Dom](../../document/)
* hopsättning [Aspose.HTML](../../../)

---

## Navigate(string, Url) {#navigate_5}

Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, ersätter det tidigare innehållet.

```csharp
public void Navigate(string content, Url baseUri)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | String | Dokumentets innehåll. |
| baseUri | Url | Bas-URI för att lösa relativa resurser. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | `baseUri` är`null`. |

### Se även

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* namnutrymme [Aspose.Html.Dom](../../document/)
* hopsättning [Aspose.HTML](../../../)

---

## Navigate(Stream, string) {#navigate_3}

Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, ersätter det tidigare innehållet. Dokumentladdning startar från den aktuella positionen i strömmen.

```csharp
public void Navigate(Stream content, string baseUri)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | Stream | Dokumentets innehåll. |
| baseUri | String | Bas-URI för att lösa relativa resurser. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | `baseUri` är`null`. |

### Se även

* class [Document](../)
* namnutrymme [Aspose.Html.Dom](../../document/)
* hopsättning [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, ersätter det tidigare innehållet. Dokumentladdning startar från den aktuella positionen i strömmen.

```csharp
public void Navigate(Stream content, Url baseUri)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | Stream | Dokumentets innehåll. |
| baseUri | Url | Bas-URI för att lösa relativa resurser. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | `baseUri` är`null`. |

### Se även

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* namnutrymme [Aspose.Html.Dom](../../document/)
* hopsättning [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

Laddar dokumentet baserat på angivet förfrågningsobjekt och ersätter det tidigare innehållet.

```csharp
public void Navigate(RequestMessage request)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| request | RequestMessage | Begäranobjektet som används för att ladda dokumentinnehåll. |

### Se även

* class [RequestMessage](../../../aspose.html.net/requestmessage/)
* class [Document](../)
* namnutrymme [Aspose.Html.Dom](../../document/)
* hopsättning [Aspose.HTML](../../../)


