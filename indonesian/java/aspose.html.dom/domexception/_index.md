---
title: "Kelas DOMException"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Kelas com.aspose.html.dom.DOMException. Antarmuka DOMException mewakili peristiwa abnormal yang disebut pengecualian yang terjadi sebagai hasil pemanggilan metode atau mengakses properti dari sebuah web API. Ini pada dasarnya cara kondisi kesalahan dijelaskan dalam web API."
type: docs

url: /id/java/com.aspose.html.dom/domexception/
---
## DOMException class

Antarmuka DOMException merepresentasikan peristiwa abnormal (disebut pengecualian) yang terjadi sebagai hasil pemanggilan metode atau mengakses properti dari sebuah web API. Pada dasarnya inilah cara kondisi kesalahan dijelaskan dalam web API.

```java
public class DOMException : PlatformException
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [DOMException](domexception/#constructor)(String) | Menginisialisasi sebuah instance baru dari kelas `DOMException`. |
| [DOMException](domexception/#constructor_1)(String, String) | Menginisialisasi sebuah instance baru dari kelas `DOMException`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getCode](../../com.aspose.html.dom/domexception/code/) Mengembalikan nilai yang berisi salah satu konstanta kode kesalahan, atau 0 jika tidak ada yang cocok. Field ini digunakan untuk alasan historis. |
| [getMessage](../../com.aspose.html.dom/domexception/message/) Mengembalikan sebuah String yang mewakili pesan atau deskripsi yang terkait dengan nama kesalahan yang diberikan. |
| [getName](../../com.aspose.html.dom/domexception/name/) Mengembalikan sebuah String yang berisi salah satu String yang terkait dengan nama kesalahan. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [ABORT_ERR](../../com.aspose.html.dom/domexception/abort_err/) | Operasi dibatalkan. |
| const [DATA_CLONE_ERR](../../com.aspose.html.dom/domexception/data_clone_err/) | Objek tidak dapat digandakan. |
| const [DOMSTRING_SIZE_ERR](../../com.aspose.html.dom/domexception/domString_size_err/) | Jika rentang teks yang ditentukan tidak muat dalam DOMString. |
| const [HIERARCHY_REQUEST_ERR](../../com.aspose.html.dom/domexception/hierarchy_request_err/) | Jika ada Node yang disisipkan di tempat yang tidak semestinya. |
| const [INDEX_SIZE_ERR](../../com.aspose.html.dom/domexception/index_size_err/) | Jika indeks atau ukuran bernilai negatif, atau lebih besar dari nilai yang diizinkan. |
| const [INUSE_ATTRIBUTE_ERR](../../com.aspose.html.dom/domexception/inuse_attribute_err/) | Jika ada upaya menambahkan atribut yang sudah digunakan di tempat lain. |
| const [INVALID_ACCESS_ERR](../../com.aspose.html.dom/domexception/invalid_access_err/) | Jika sebuah parameter atau operasi tidak didukung oleh objek dasar. |
| const [INVALID_CHARACTER_ERR](../../com.aspose.html.dom/domexception/invalid_character_err/) | Jika karakter yang tidak valid atau ilegal ditentukan, seperti pada nama XML. |
| const [INVALID_EXPRESSION_ERR](../../com.aspose.html.dom/domexception/invalid_expression_err/) | Ekspresi memiliki kesalahan sintaks atau tidak merupakan ekspresi yang sah menurut aturan XPathEvaluator tertentu atau mengandung fungsi ekstensi khusus atau variabel yang tidak didukung oleh implementasi ini. |
| const [INVALID_MODIFICATION_ERR](../../com.aspose.html.dom/domexception/invalid_modification_err/) | Jika ada upaya mengubah tipe objek dasar. |
| const [INVALID_NODE_TYPE_ERR](../../com.aspose.html.dom/domexception/invalid_node_type_err/) | Node yang diberikan tidak tepat atau memiliki nenek moyang yang tidak tepat untuk operasi ini. |
| const [INVALID_STATE_ERR](../../com.aspose.html.dom/domexception/invalid_state_err/) | Jika percobaan dilakukan untuk menggunakan objek yang tidak, atau tidak lagi, dapat digunakan. |
| const [NAMESPACE_ERR](../../com.aspose.html.dom/domexception/package_err/) | Jika percobaan dilakukan untuk membuat atau mengubah objek dengan cara yang tidak tepat terkait paket. |
| const [NETWORK_ERR](../../com.aspose.html.dom/domexception/network_err/) | Terjadi kesalahan jaringan. |
| const [NOT_FOUND_ERR](../../com.aspose.html.dom/domexception/not_found_err/) | Jika percobaan dilakukan untuk merujuk Node dalam konteks di mana Node tersebut tidak ada. |
| const [NOT_SUPPORTED_ERR](../../com.aspose.html.dom/domexception/not_supported_err/) | Jika implementasi tidak mendukung tipe objek atau operasi yang diminta. |
| const [NO_DATA_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_data_allowed_err/) | Jika data ditentukan untuk Node yang tidak mendukung data. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../com.aspose.html.dom/domexception/no_modification_allowed_err/) | Jika percobaan dilakukan untuk memodifikasi objek di mana modifikasi tidak diizinkan. |
| const [QUOTA_EXCEEDED_ERR](../../com.aspose.html.dom/domexception/quota_exceeded_err/) | Kuota telah terlampaui. |
| const [SECURITY_ERR](../../com.aspose.html.dom/domexception/security_err/) | Operasi tidak aman. |
| const [SYNTAX_ERR](../../com.aspose.html.dom/domexception/syntax_err/) | Jika String yang tidak valid atau ilegal ditentukan. |
| const [TIMEOUT_ERR](../../com.aspose.html.dom/domexception/timeout_err/) | Operasi kehabisan waktu. |
| const [TYPE_ERR](../../com.aspose.html.dom/domexception/type_err/) | Ekspresi tidak dapat dikonversi untuk mengembalikan tipe yang ditentukan. |
| const [TYPE_MISMATCH_ERR](../../com.aspose.html.dom/domexception/type_mismatch_err/) | Jika tipe objek tidak kompatibel dengan tipe yang diharapkan dari parameter yang terkait dengan objek. |
| const [URL_MISMATCH_ERR](../../com.aspose.html.dom/domexception/url_mismatch_err/) | URL yang diberikan tidak cocok dengan URL lain. |
| const [VALIDATION_ERR](../../com.aspose.html.dom/domexception/validation_err/) | Jika pemanggilan metode seperti insertBefore atau removeChild akan membuat Node tidak valid terkait \"partial validity\", pengecualian ini akan dilempar dan operasi tidak akan dilakukan. Kode ini digunakan dalam [DOM Level 3 Validation]. Lihat spesifikasi ini untuk informasi lebih lanjut. |
| const [WRONG_DOCUMENT_ERR](../../com.aspose.html.dom/domexception/wrong_document_err/) | Jika Node digunakan dalam dokumen yang berbeda dari yang membuatnya (yang tidak mendukungnya). |

### Lihat Juga

* class [PlatformException](../../com.aspose.html/platformexception/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
