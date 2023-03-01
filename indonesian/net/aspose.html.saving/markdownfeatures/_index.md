---
title: Enum MarkdownFeatures
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Saving.MarkdownFeatures enum. AMarkdownFeatures set flag adalah sekumpulan nol atau lebih dari flag berikut yang digunakan untuk memilih elemen yang dikonversi menjadi markdown.
type: docs
weight: 4620
url: /id/net/aspose.html.saving/markdownfeatures/
---
## MarkdownFeatures enumeration

A`MarkdownFeatures` set flag adalah sekumpulan nol atau lebih dari flag berikut, yang digunakan untuk memilih elemen yang dikonversi menjadi markdown.

```csharp
[Flags]
public enum MarkdownFeatures
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| InlineHTML | `1` | Bendera ini memungkinkan inlining elemen HTML. Jika bendera ini disetel dari elemen level blok (seperti`div` ) yang`penurunan harga` nilai atribut sama`Di barisan` akan dimasukkan ke dalam penurunan harga yang dihasilkan. |
| AutomaticParagraph | `2` | Bendera ini memungkinkan konversi`gugus kalimat` elemen. Konten dari elemen tersebut akan ditempatkan pada baris terpisah, sehingga penangan penurunan harga akan membungkusnya. |
| Header | `4` | Bendera ini memungkinkan konversi`tajuk` elemen. |
| Blockquote | `8` | Bendera ini memungkinkan konversi`blockquote` elemen. |
| List | `10` | Bendera ini memungkinkan konversi`daftar` elemen. |
| CodeBlock | `20` | Bendera ini memungkinkan konversi blok kode. Blok kode terdiri dari 2 elemen`pra` Dan`kode` , isi konstruksi tersebut adalah proses "sebagaimana adanya". |
| HorizontalRule | `40` | Bendera ini memungkinkan konversi`aturan horisontal` . |
| Link | `80` | Bendera ini memungkinkan konversi`A` elemen. |
| Emphasis | `100` | Bendera ini memungkinkan konversi`tekanan` elemen. |
| InlineCode | `200` | Bendera ini memungkinkan konversi`kode` elemen. |
| Image | `400` | Bendera ini memungkinkan konversi`img` elemen. |
| LineBreak | `800` | Bendera ini memungkinkan konversi`br` elemen. |
| Video | `1000` | Bendera ini memungkinkan konversi`video` elemen. |
| Table | `2000` | Bendera ini memungkinkan konversi`meja` elemen. |
| TaskList | `4000` | Bendera ini mengaktifkan konversi daftar tugas. Daftar tugas terdiri dari`memasukkan` elemen, yang harus menjadi anak pertama dari`daftar` elemen dan siapa`jenis` nilai atribut harus sama`kotak centang` . |
| Strikethrough | `8000` | Bendera ini memungkinkan konversi`del` elemen. |
| Strong | `10000` | Bendera ini memungkinkan konversi`kuat` elemen. |

### Lihat juga

* ruang nama [Aspose.Html.Saving](../../aspose.html.saving/)
* perakitan [Aspose.HTML](../../)


