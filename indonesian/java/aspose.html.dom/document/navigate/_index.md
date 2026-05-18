---
title: "Document.Navigate"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Document metode. Memuat dokumen pada URL Uniform Resource Locator yang ditentukan ke dalam instance saat ini, menggantikan konten sebelumnya."
type: docs

url: /id/java/com.aspose.html.dom/document/navigate/
---
## Navigate(String) {#navigate_4}

Memuat dokumen pada Uniform Resource Locator (URL) yang ditentukan ke dalam instance saat ini, menggantikan konten sebelumnya.

```java
public void Navigate(String address)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alamat | String | Alamat dokumen. Akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |

### Lihat Juga

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

Memuat dokumen pada Uniform Resource Locator (URL) yang ditentukan ke dalam instance saat ini, menggantikan konten sebelumnya.

```java
public void Navigate(Url url)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | Url | URL dokumen. |

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, String) {#navigate_6}

Memuat dokumen dari konten yang ditentukan dan menggunakan baseUri untuk menyelesaikan sumber daya relatif, menggantikan konten sebelumnya.

```java
public void Navigate(String content, String baseUri)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | Konten dokumen. |
| baseUri | String | URI dasar untuk menyelesaikan sumber daya relatif. URI ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | `baseUri` adalah `null`. |

### Lihat Juga

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, Url) {#navigate_5}

Memuat dokumen dari konten yang ditentukan dan menggunakan baseUri untuk menyelesaikan sumber daya relatif, menggantikan konten sebelumnya.

```java
public void Navigate(String content, Url baseUri)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | String | Konten dokumen. |
| baseUri | Url | URI dasar untuk menyelesaikan sumber daya relatif. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | `baseUri` adalah `null`. |

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, String) {#navigate_3}

Memuat dokumen dari konten yang ditentukan dan menggunakan baseUri untuk menyelesaikan sumber daya relatif, menggantikan konten sebelumnya. Pemuatan dokumen dimulai dari posisi saat ini dalam aliran.

```java
public void Navigate(Stream content, String baseUri)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | Aliran | Konten dokumen. |
| baseUri | String | URI dasar untuk menyelesaikan sumber daya relatif. URI ini akan digabungkan dengan jalur direktori saat ini untuk membentuk URL absolut. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | `baseUri` adalah `null`. |

### Lihat Juga

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

Memuat dokumen dari konten yang ditentukan dan menggunakan baseUri untuk menyelesaikan sumber daya relatif, menggantikan konten sebelumnya. Pemuatan dokumen dimulai dari posisi saat ini dalam aliran.

```java
public void Navigate(Stream content, Url baseUri)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| konten | Aliran | Konten dokumen. |
| baseUri | Url | URI dasar untuk menyelesaikan sumber daya relatif. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | `baseUri` adalah `null`. |

### Lihat Juga

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

Memuat dokumen berdasarkan objek permintaan yang ditentukan, menggantikan konten sebelumnya.

```java
public void Navigate(RequestMessage request)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| permintaan | RequestMessage | Objek permintaan yang digunakan untuk memuat konten dokumen. |

### Lihat Juga

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
