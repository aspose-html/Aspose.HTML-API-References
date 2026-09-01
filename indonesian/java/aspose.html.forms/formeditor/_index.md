---
title: "Kelas FormEditor"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "kelas com.aspose.html.forms.FormEditor. Kelas ini mewakili editor atas HTMLFormElement yang menyediakan cara lebih mudah bagi pengembang .net untuk mengedit formulir html"
type: docs

url: /id/java/com.aspose.html.forms/formeditor/
---
## FormEditor class

Kelas ini mewakili editor atas [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) yang menyediakan cara lebih mudah bagi pengembang .net untuk mengedit formulir html.

```java
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
| [getCount](../../com.aspose.html.forms/formeditor/count/) Jumlah kontrol formulir dalam formulir. |
| [getForm](../../com.aspose.html.forms/formeditor/form/) [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) asli yang terkait dengan instance `FormEditor` saat ini. |
| [getItem](../../com.aspose.html.forms/formeditor/item/) Mengembalikan elemen berdasarkan indeks yang ditentukan. (2 indexer) |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | Membuat `FormEditor` baru berdasarkan [`HTMLFormElement`](../../com.aspose.html/htmlformelement/). |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | Membuat `FormEditor` baru berdasarkan [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) yang dipilih dari koleksi [`Forms`](../../com.aspose.html/htmldocument/forms/) berdasarkan indeks. |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, String) | Membuat `FormEditor` baru berdasarkan [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) yang dipilih dari dokumen berdasarkan id. |
| static [CreateNew](../../com.aspose.html.forms/formeditor/createnew/)(HTMLDocument) | Membuat [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) baru dan mengaitkannya dengan `FormEditor`. [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) dibuat dalam keadaan terlepas dari dokumen; untuk melampirkannya ke dokumen, silakan pilih lokasi yang tepat dan gunakan metode [`AppendChild`](../../com.aspose.html.dom/node/appendchild/). |
| [Add&lt;T&gt;](../../com.aspose.html.forms/formeditor/add/)(String) | Membuat [`HTMLElement`](../../com.aspose.html/htmlelement/) baru dan menambahkannya ke akhir formulir. |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput)(String) | Membuat [`InputElement`](../inputelement/) baru dan menambahkannya ke akhir formulir. |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput_1)(String, InputElementType) | Membuat [`InputElement`](../inputelement/) baru dan menambahkannya ke akhir formulir. |
| [dispose](../../com.aspose.html.forms/formeditor/dispose/)() | Melepaskan sumber daya yang tidak dikelola dan yang dikelola. |
| [fill](../../com.aspose.html.forms/formeditor/fill/)(Dictionary&lt;String, String&gt;) |  |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement)(int) | Mengembalikan elemen berdasarkan indeks yang ditentukan. |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement_1)(String) | Mengembalikan elemen berdasarkan nama yang ditentukan. |
| [getEnumerator](../../com.aspose.html.forms/formeditor/getenumerator/)() | Mendapatkan enumerator. |

### Lihat Juga

* class [FormElement](../formelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
