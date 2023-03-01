---
title: Class MutationRecord
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Mutations.MutationRecord kelas. MutationRecord mewakili mutasi DOM individual. Itu adalah objek yang diteruskan keMutationObserver SMutationCallback .
type: docs
weight: 990
url: /id/net/aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

MutationRecord mewakili mutasi DOM individual. Itu adalah objek yang diteruskan ke[`MutationObserver`](../mutationobserver/) S[`MutationCallback`](../mutationcallback/) .

```csharp
public class MutationRecord : DOMObject
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [AddedNodes](../../aspose.html.dom.mutations/mutationrecord/addednodes/) { get; } | Mengembalikan node yang ditambahkan. |
| [AttributeName](../../aspose.html.dom.mutations/mutationrecord/attributename/) { get; } | Mengembalikan nama lokal dari atribut yang diubah, dan null sebaliknya. |
| [AttributeNamespace](../../aspose.html.dom.mutations/mutationrecord/attributenamespace/) { get; } | Mengembalikan namespace dari atribut yang diubah, dan null sebaliknya. |
| [NextSibling](../../aspose.html.dom.mutations/mutationrecord/nextsibling/) { get; } | Mengembalikan saudara berikutnya dari node yang ditambahkan atau dihapus, atau null. |
| [OldValue](../../aspose.html.dom.mutations/mutationrecord/oldvalue/) { get; } | Nilai yang dikembalikan bergantung pada jenis. Untuk "atribut", itu adalah nilai dari atribut yang diubah sebelum perubahan. Untuk "characterData", itu adalah data node yang diubah sebelum perubahan. Untuk "childList", itu adalah null. |
| [PreviousSibling](../../aspose.html.dom.mutations/mutationrecord/previoussibling/) { get; } | Mengembalikan saudara sebelumnya dari node yang ditambahkan atau dihapus, atau null. |
| [RemovedNodes](../../aspose.html.dom.mutations/mutationrecord/removednodes/) { get; } | Kembalikan node yang dihapus. |
| [Target](../../aspose.html.dom.mutations/mutationrecord/target/) { get; } | Mengembalikan simpul yang terpengaruh mutasi, tergantung pada jenisnya. Untuk "atribut", itu adalah elemen yang atributnya berubah. Untuk "characterData", itu adalah node CharacterData. Untuk "childList", itu adalah simpul yang anaknya berubah. |
| [Type](../../aspose.html.dom.mutations/mutationrecord/type/) { get; } | Mengembalikan "atribut" jika itu adalah mutasi atribut, "characterData" jika itu adalah mutasi ke node CharacterData dan "childList" jika itu adalah mutasi ke pohon node. |

## Metode

| Nama | Keterangan |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScriptType . |

### Lihat juga

* class [DOMObject](../../aspose.html.dom/domobject/)
* ruang nama [Aspose.Html.Dom.Mutations](../../aspose.html.dom.mutations/)
* perakitan [Aspose.HTML](../../)


