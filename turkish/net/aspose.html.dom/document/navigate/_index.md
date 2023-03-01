---
title: Document.Navigate
second_title: Aspose.HTML for .NET API Referansı
description: Document yöntem. Belirtilen Tekdüzen Kaynak Bulucudaki URL belgeyi önceki içeriği değiştirerek mevcut örneğe yükler.
type: docs
weight: 1010
url: /tr/net/aspose.html.dom/document/navigate/
---
## Navigate(string) {#navigate_4}

Belirtilen Tekdüzen Kaynak Bulucudaki (URL) belgeyi, önceki içeriği değiştirerek mevcut örneğe yükler.

```csharp
public void Navigate(string address)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| address | String | Belge adresi. Mutlak bir URL oluşturmak için geçerli dizin yolu ile birleştirilecektir. |

### Ayrıca bakınız

* class [Document](../)
* ad alanı [Aspose.Html.Dom](../../document/)
* toplantı [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

Belirtilen Tekdüzen Kaynak Bulucudaki (URL) belgeyi, önceki içeriği değiştirerek mevcut örneğe yükler.

```csharp
public void Navigate(Url url)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| url | Url | Belge URL'si. |

### Ayrıca bakınız

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* ad alanı [Aspose.Html.Dom](../../document/)
* toplantı [Aspose.HTML](../../../)

---

## Navigate(string, string) {#navigate_6}

Belgeyi belirtilen içerikten yükler ve baseUri kullanarak göreli kaynakları çözerek önceki içeriği değiştirir.

```csharp
public void Navigate(string content, string baseUri)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| content | String | Belge içeriği. |
| baseUri | String | Göreceli kaynakları çözmek için temel URI. Mutlak bir URL oluşturmak için geçerli dizin yolu ile birleştirilecektir. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | `baseUri` dır-dir`hükümsüz`. |

### Ayrıca bakınız

* class [Document](../)
* ad alanı [Aspose.Html.Dom](../../document/)
* toplantı [Aspose.HTML](../../../)

---

## Navigate(string, Url) {#navigate_5}

Belgeyi belirtilen içerikten yükler ve baseUri kullanarak göreli kaynakları çözerek önceki içeriği değiştirir.

```csharp
public void Navigate(string content, Url baseUri)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| content | String | Belge içeriği. |
| baseUri | Url | Göreceli kaynakları çözmek için temel URI. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | `baseUri` dır-dir`hükümsüz`. |

### Ayrıca bakınız

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* ad alanı [Aspose.Html.Dom](../../document/)
* toplantı [Aspose.HTML](../../../)

---

## Navigate(Stream, string) {#navigate_3}

Belgeyi belirtilen içerikten yükler ve göreli kaynakları çözmek için baseUri kullanarak önceki içeriği değiştirir. Belge yükleme, akıştaki geçerli konumdan başlar.

```csharp
public void Navigate(Stream content, string baseUri)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| content | Stream | Belge içeriği. |
| baseUri | String | Göreceli kaynakları çözmek için temel URI. Mutlak bir URL oluşturmak için geçerli dizin yolu ile birleştirilecektir. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | `baseUri` dır-dir`hükümsüz`. |

### Ayrıca bakınız

* class [Document](../)
* ad alanı [Aspose.Html.Dom](../../document/)
* toplantı [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

Belgeyi belirtilen içerikten yükler ve göreli kaynakları çözmek için baseUri kullanarak önceki içeriği değiştirir. Belge yükleme, akıştaki geçerli konumdan başlar.

```csharp
public void Navigate(Stream content, Url baseUri)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| content | Stream | Belge içeriği. |
| baseUri | Url | Göreceli kaynakları çözmek için temel URI. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | `baseUri` dır-dir`hükümsüz`. |

### Ayrıca bakınız

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* ad alanı [Aspose.Html.Dom](../../document/)
* toplantı [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

Önceki içeriği değiştirerek belirtilen istek nesnesine göre belgeyi yükler.

```csharp
public void Navigate(RequestMessage request)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| request | RequestMessage | Belge içeriğini yüklemek için kullanılan istek nesnesi. |

### Ayrıca bakınız

* class [RequestMessage](../../../aspose.html.net/requestmessage/)
* class [Document](../)
* ad alanı [Aspose.Html.Dom](../../document/)
* toplantı [Aspose.HTML](../../../)


