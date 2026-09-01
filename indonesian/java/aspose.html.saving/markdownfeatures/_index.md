---
title: "Enum MarkdownFeatures"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "enum com.aspose.html.saving.MarkdownFeatures. Set bendera MarkdownFeatures adalah sekumpulan nol atau lebih dari bendera berikut yang digunakan untuk memilih elemen yang dikonversi ke markdown"
type: docs

url: /id/java/com.aspose.html.saving/markdownfeatures/
---
## MarkdownFeatures enumeration

Set bendera `MarkdownFeatures` adalah sekumpulan nol atau lebih dari bendera berikut, yang digunakan untuk memilih elemen yang dikonversi ke markdown.

```java
[Flags]
public enum MarkdownFeatures
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| InlineHTML | `1` | Bendera ini mengaktifkan penyisipan elemen HTML. Jika bendera ini diatur, maka elemen tingkat blok (seperti `div`) yang nilai atribut `markdown`-nya sama dengan `inline` akan dimasukkan ke dalam markdown hasil. |
| AutomaticParagraph | `2` | Bendera ini mengaktifkan konversi elemen `paragraph`. Konten elemen tersebut akan ditempatkan pada baris terpisah, sehingga penangan markdown akan membungkusnya. |
| Header | `4` | Bendera ini mengaktifkan konversi elemen `header`. |
| Blockquote | `8` | Bendera ini mengaktifkan konversi elemen `blockquote`. |
| List | `10` | Bendera ini mengaktifkan konversi elemen `list`. |
| CodeBlock | `20` | Bendera ini mengaktifkan konversi blok kode. Blok kode terdiri dari 2 elemen `pre` dan `code`, konten konstruksi tersebut diproses "as is". |
| HorizontalRule | `40` | Bendera ini mengaktifkan konversi `horizontal rules`. |
| Link | `80` | Bendera ini mengaktifkan konversi elemen `a`. |
| Emphasis | `100` | Flag ini mengaktifkan konversi elemen `emphasis`. |
| InlineCode | `200` | Flag ini mengaktifkan konversi elemen `code`. |
| Image | `400` | Flag ini mengaktifkan konversi elemen `img`. |
| LineBreak | `800` | Flag ini mengaktifkan konversi elemen `br`. |
| Video | `1000` | Flag ini mengaktifkan konversi elemen `video`. |
| Table | `2000` | Flag ini mengaktifkan konversi elemen `table`. |
| TaskList | `4000` | Flag ini mengaktifkan konversi daftar tugas. Daftar tugas terdiri dari elemen `input`, yang harus menjadi anak pertama dari elemen `list` dan nilai atribut `type`-nya harus sama dengan `checkbox`. |
| Strikethrough | `8000` | Flag ini mengaktifkan konversi elemen `del`. |
| Strong | `10000` | Flag ini mengaktifkan konversi elemen `strong`. |

### Lihat Juga

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
