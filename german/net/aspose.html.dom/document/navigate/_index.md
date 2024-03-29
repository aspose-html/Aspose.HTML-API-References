---
title: Document.Navigate
second_title: Aspose.HTML für .NET-API-Referenz
description: Document methode. Lädt das Dokument unter der angegebenen URL Uniform Resource Locator in die aktuelle Instanz und ersetzt den vorherigen Inhalt.
type: docs
weight: 1010
url: /de/net/aspose.html.dom/document/navigate/
---
## Navigate(string) {#navigate_4}

Lädt das Dokument unter der angegebenen URL (Uniform Resource Locator) in die aktuelle Instanz und ersetzt den vorherigen Inhalt.

```csharp
public void Navigate(string address)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| address | String | Die Dokumentenadresse. Er wird mit dem aktuellen Verzeichnispfad zu einer absoluten URL kombiniert. |

### Siehe auch

* class [Document](../)
* namensraum [Aspose.Html.Dom](../../document/)
* Montage [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

Lädt das Dokument unter der angegebenen URL (Uniform Resource Locator) in die aktuelle Instanz und ersetzt den vorherigen Inhalt.

```csharp
public void Navigate(Url url)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | Url | Die Dokument-URL. |

### Siehe auch

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* namensraum [Aspose.Html.Dom](../../document/)
* Montage [Aspose.HTML](../../../)

---

## Navigate(string, string) {#navigate_6}

Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird.

```csharp
public void Navigate(string content, string baseUri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| content | String | Der Dokumenteninhalt. |
| baseUri | String | Der Basis-URI zum Auflösen relativer Ressourcen. Er wird mit dem aktuellen Verzeichnispfad zu einer absoluten URL kombiniert. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | `baseUri` Ist`Null`. |

### Siehe auch

* class [Document](../)
* namensraum [Aspose.Html.Dom](../../document/)
* Montage [Aspose.HTML](../../../)

---

## Navigate(string, Url) {#navigate_5}

Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird.

```csharp
public void Navigate(string content, Url baseUri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| content | String | Der Dokumenteninhalt. |
| baseUri | Url | Der Basis-URI zum Auflösen relativer Ressourcen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | `baseUri` Ist`Null`. |

### Siehe auch

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* namensraum [Aspose.Html.Dom](../../document/)
* Montage [Aspose.HTML](../../../)

---

## Navigate(Stream, string) {#navigate_3}

Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wodurch der vorherige Inhalt ersetzt wird. Das Laden des Dokuments beginnt an der aktuellen Position im Stream.

```csharp
public void Navigate(Stream content, string baseUri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| content | Stream | Der Dokumenteninhalt. |
| baseUri | String | Der Basis-URI zum Auflösen relativer Ressourcen. Er wird mit dem aktuellen Verzeichnispfad zu einer absoluten URL kombiniert. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | `baseUri` Ist`Null`. |

### Siehe auch

* class [Document](../)
* namensraum [Aspose.Html.Dom](../../document/)
* Montage [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wodurch der vorherige Inhalt ersetzt wird. Das Laden des Dokuments beginnt an der aktuellen Position im Stream.

```csharp
public void Navigate(Stream content, Url baseUri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| content | Stream | Der Dokumenteninhalt. |
| baseUri | Url | Der Basis-URI zum Auflösen relativer Ressourcen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | `baseUri` Ist`Null`. |

### Siehe auch

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* namensraum [Aspose.Html.Dom](../../document/)
* Montage [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

Lädt das Dokument basierend auf dem angegebenen Anforderungsobjekt und ersetzt den vorherigen Inhalt.

```csharp
public void Navigate(RequestMessage request)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| request | RequestMessage | Das Anforderungsobjekt, das zum Laden von Dokumentinhalten verwendet wird. |

### Siehe auch

* class [RequestMessage](../../../aspose.html.net/requestmessage/)
* class [Document](../)
* namensraum [Aspose.Html.Dom](../../document/)
* Montage [Aspose.HTML](../../../)


