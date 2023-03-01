---
title: Class FormEditor
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Forms.FormEditor kelas. Kelas ini mewakili editor di atasHTMLFormElement yang menciptakan cara yang lebih mudah bagi pengembang .net untuk mengedit formulir html.
type: docs
weight: 2930
url: /id/net/aspose.html.forms/formeditor/
---
## FormEditor class

Kelas ini mewakili editor di atas[`HTMLFormElement`](../../aspose.html/htmlformelement/) yang menciptakan cara yang lebih mudah bagi pengembang .net untuk mengedit formulir html.

```csharp
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Action](../../aspose.html.forms/formeditor/action/) { get; set; } | Pengendali formulir sisi server. Lihat definisi atribut tindakan dalam HTML 4.01. |
| [Count](../../aspose.html.forms/formeditor/count/) { get; } | Jumlah kontrol formulir dalam formulir. |
| [Form](../../aspose.html.forms/formeditor/form/) { get; } | Asli[`HTMLFormElement`](../../aspose.html/htmlformelement/) yang terkait dengan contoh saat ini`FormEditor` . |
| [Item](../../aspose.html.forms/formeditor/item/) { get; } | Mengembalikan elemen dengan indeks tertentu. (2 indexers) |
| [Method](../../aspose.html.forms/formeditor/method/) { get; set; } | metode HTTP [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt) digunakan untuk mengirimkan formulir. Lihat definisi atribut metode dalam HTML 4.01. |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [Create](../../aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | Membuat yang baru`FormEditor` berdasarkan[`HTMLFormElement`](../../aspose.html/htmlformelement/) . |
| static [Create](../../aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | Membuat yang baru`FormEditor` berdasarkan[`HTMLFormElement`](../../aspose.html/htmlformelement/) dipilih dari[`Forms`](../../aspose.html/htmldocument/forms/) koleksi menurut index. |
| static [Create](../../aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, string) | Membuat yang baru`FormEditor` berdasarkan[`HTMLFormElement`](../../aspose.html/htmlformelement/) dipilih dari dokumen dengan id. |
| static [CreateNew](../../aspose.html.forms/formeditor/createnew/)(HTMLDocument) | Membuat yang baru[`HTMLFormElement`](../../aspose.html/htmlformelement/) dan diasosiasikan dengan`FormEditor` .[`HTMLFormElement`](../../aspose.html/htmlformelement/) dibuat terpisah dari status dokumen; untuk melampirkannya ke dokumen, pilih lokasi yang tepat dan gunakan[`AppendChild`](../../aspose.html.dom/node/appendchild/) metode. |
| [Add&lt;T&gt;](../../aspose.html.forms/formeditor/add/)(string) | Membuat yang baru[`HTMLElement`](../../aspose.html/htmlelement/) dan menambahkannya ke akhir form. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput)(string) | Membuat yang baru[`InputElement`](../inputelement/) dan menambahkannya ke akhir form. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput_1)(string, InputElementType) | Membuat yang baru[`InputElement`](../inputelement/) dan menambahkannya ke akhir form. |
| [Dispose](../../aspose.html.forms/formeditor/dispose/)() | Melepaskan sumber daya yang tidak dikelola dan dikelola. |
| [Fill](../../aspose.html.forms/formeditor/fill/)(Dictionary&lt;string, string&gt;) | Metode ini mengisi seluruh formulir dengan nilai yang ditentukan. |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement)(int) | Mengembalikan elemen dengan indeks tertentu. |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement_1)(string) | Mengembalikan elemen dengan nama tertentu. |
| [GetEnumerator](../../aspose.html.forms/formeditor/getenumerator/)() | Mendapatkan enumerator. |

### Lihat juga

* class [FormElement](../formelement/)
* ruang nama [Aspose.Html.Forms](../../aspose.html.forms/)
* perakitan [Aspose.HTML](../../)


