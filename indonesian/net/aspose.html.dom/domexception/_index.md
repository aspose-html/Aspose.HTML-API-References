---
title: Class DOMException
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.DOMException kelas. Antarmuka DOMException mewakili kejadian abnormal disebut pengecualian yang terjadi sebagai akibat dari pemanggilan metode atau pengaksesan properti API web. Ini pada dasarnya adalah bagaimana kondisi kesalahan dijelaskan dalam API web.
type: docs
weight: 640
url: /id/net/aspose.html.dom/domexception/
---
## DOMException class

Antarmuka DOMException mewakili kejadian abnormal (disebut pengecualian) yang terjadi sebagai akibat dari pemanggilan metode atau pengaksesan properti API web. Ini pada dasarnya adalah bagaimana kondisi kesalahan dijelaskan dalam API web.

```csharp
public class DOMException : PlatformException
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [DOMException](domexception/#constructor)(string) | Menginisialisasi instance baru dari`DOMException` kelas. |
| [DOMException](domexception/#constructor_1)(string, string) | Menginisialisasi instance baru dari`DOMException` kelas. |

## Properti

| Nama | Keterangan |
| --- | --- |
| [Code](../../aspose.html.dom/domexception/code/) { get; } | Mengembalikan nilai yang berisi salah satu konstanta kode kesalahan, atau 0 jika tidak ada yang cocok. Kolom ini digunakan untuk alasan historis. |
| override [Message](../../aspose.html.dom/domexception/message/) { get; } | Mengembalikan string yang mewakili pesan atau deskripsi yang terkait dengan nama kesalahan yang diberikan. |
| [Name](../../aspose.html.dom/domexception/name/) { get; } | Mengembalikan string yang berisi salah satu string yang terkait dengan nama kesalahan. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| const [ABORT_ERR](../../aspose.html.dom/domexception/abort_err/) | Operasi dibatalkan. |
| const [DATA_CLONE_ERR](../../aspose.html.dom/domexception/data_clone_err/) | Objek tidak dapat digandakan. |
| const [DOMSTRING_SIZE_ERR](../../aspose.html.dom/domexception/domstring_size_err/) | Jika rentang teks yang ditentukan tidak sesuai dengan DOMString. |
| const [HIERARCHY_REQUEST_ERR](../../aspose.html.dom/domexception/hierarchy_request_err/) | Jika ada Node yang disisipkan di tempat yang bukan tempatnya. |
| const [INDEX_SIZE_ERR](../../aspose.html.dom/domexception/index_size_err/) | Jika indeks atau ukuran negatif, atau lebih besar dari nilai yang diperbolehkan. |
| const [INUSE_ATTRIBUTE_ERR](../../aspose.html.dom/domexception/inuse_attribute_err/) | Jika dilakukan upaya untuk menambahkan atribut yang sudah digunakan di tempat lain. |
| const [INVALID_ACCESS_ERR](../../aspose.html.dom/domexception/invalid_access_err/) | Jika parameter atau operasi tidak didukung oleh objek yang mendasarinya. |
| const [INVALID_CHARACTER_ERR](../../aspose.html.dom/domexception/invalid_character_err/) | Jika karakter yang tidak valid atau ilegal ditentukan, seperti dalam nama XML. |
| const [INVALID_EXPRESSION_ERR](../../aspose.html.dom/domexception/invalid_expression_err/) | Ekspresi memiliki kesalahan sintaksis atau bukan ekspresi legal menurut aturan spesifik XPathEvaluator atau berisi fungsi atau variabel ekstensi khusus yang tidak didukung oleh implementasi ini. |
| const [INVALID_MODIFICATION_ERR](../../aspose.html.dom/domexception/invalid_modification_err/) | Jika dilakukan upaya untuk mengubah jenis objek yang mendasarinya. |
| const [INVALID_NODE_TYPE_ERR](../../aspose.html.dom/domexception/invalid_node_type_err/) | Node yang disediakan salah atau memiliki ancestor yang salah untuk operasi ini. |
| const [INVALID_STATE_ERR](../../aspose.html.dom/domexception/invalid_state_err/) | Jika upaya dilakukan untuk menggunakan objek yang tidak, atau tidak lagi, dapat digunakan. |
| const [NAMESPACE_ERR](../../aspose.html.dom/domexception/namespace_err/) | Jika upaya dilakukan untuk membuat atau mengubah objek dengan cara yang salah sehubungan dengan ruang nama. |
| const [NETWORK_ERR](../../aspose.html.dom/domexception/network_err/) | Terjadi kesalahan jaringan. |
| const [NOT_FOUND_ERR](../../aspose.html.dom/domexception/not_found_err/) | Jika upaya dilakukan untuk mereferensikan Node dalam konteks yang tidak ada. |
| const [NOT_SUPPORTED_ERR](../../aspose.html.dom/domexception/not_supported_err/) | Jika implementasi tidak mendukung jenis objek atau operasi yang diminta. |
| const [NO_DATA_ALLOWED_ERR](../../aspose.html.dom/domexception/no_data_allowed_err/) | Jika data ditentukan untuk Node yang tidak mendukung data. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../aspose.html.dom/domexception/no_modification_allowed_err/) | Jika ada upaya untuk mengubah objek yang tidak diperbolehkan modifikasi. |
| const [QUOTA_EXCEEDED_ERR](../../aspose.html.dom/domexception/quota_exceeded_err/) | Kuota telah terlampaui. |
| const [SECURITY_ERR](../../aspose.html.dom/domexception/security_err/) | Operasi tidak aman. |
| const [SYNTAX_ERR](../../aspose.html.dom/domexception/syntax_err/) | Jika string yang tidak valid atau ilegal ditentukan. |
| const [TIMEOUT_ERR](../../aspose.html.dom/domexception/timeout_err/) | Waktu operasi habis. |
| const [TYPE_ERR](../../aspose.html.dom/domexception/type_err/) | Ekspresi tidak dapat dikonversi untuk mengembalikan tipe yang ditentukan. |
| const [TYPE_MISMATCH_ERR](../../aspose.html.dom/domexception/type_mismatch_err/) | Jika tipe objek tidak sesuai dengan tipe yang diharapkan dari parameter yang terkait dengan objek. |
| const [URL_MISMATCH_ERR](../../aspose.html.dom/domexception/url_mismatch_err/) | URL yang diberikan tidak cocok dengan URL lain. |
| const [VALIDATION_ERR](../../aspose.html.dom/domexception/validation_err/) | Jika panggilan ke metode seperti insertBefore atau removeChild akan membuat Node tidak valid sehubungan dengan "validitas parsial", pengecualian ini akan dimunculkan dan operasi tidak akan dilakukan. Kode ini digunakan di [Validasi DOM Level 3]. Lihat spesifikasi ini untuk informasi lebih lanjut. |
| const [WRONG_DOCUMENT_ERR](../../aspose.html.dom/domexception/wrong_document_err/) | Jika sebuah Node digunakan dalam dokumen yang berbeda dari dokumen yang membuatnya (yang tidak mendukungnya). |

### Lihat juga

* class [PlatformException](../../aspose.html/platformexception/)
* ruang nama [Aspose.Html.Dom](../../aspose.html.dom/)
* perakitan [Aspose.HTML](../../)


