---
title: "Enum MarkdownFeatures"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Enum com.aspose.html.saving.MarkdownFeatures. Set flag MarkdownFeatures adalah kumpulan nol atau lebih dari flag berikut yang digunakan untuk memilih elemen yang dikonversi ke markdown"
type: docs

url: /id/java/com.aspose.html.saving/markdownfeatures/
---
## MarkdownFeatures enumeration

Set flag `MarkdownFeatures` adalah kumpulan nol atau lebih dari flag berikut, yang digunakan untuk memilih elemen yang dikonversi ke markdown.

```java
[Flags]
public enum MarkdownFeatures
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| InlineHTML | `1` | Flag ini mengaktifkan penyisipan elemen HTML. Jika flag ini diatur, maka elemen tingkat blok (seperti `div`) yang nilai atribut `markdown`-nya sama dengan `inline` akan disisipkan ke dalam markdown hasil. |
| AutomaticParagraph | `2` | Flag ini mengaktifkan konversi elemen `paragraph`. Konten elemen tersebut akan ditempatkan pada baris terpisah, sehingga penangan markdown akan membungkusnya. |
| Header | `4` | Flag ini mengaktifkan konversi elemen `header`. |
| Blockquote | `8` | Flag ini mengaktifkan konversi elemen `blockquote`. |
| List | `10` | Flag ini mengaktifkan konversi elemen `list`. |
| CodeBlock | `20` | Flag ini mengaktifkan konversi blok kode. Blok kode terdiri dari 2 elemen `pre` dan `code`, konten konstruksi tersebut diproses "as is". |
| HorizontalRule | `40` | Flag ini mengaktifkan konversi `horizontal rules`. |
| Link | `80` | Flag ini mengaktifkan konversi elemen `a`. |
| Emphasis | `100` | Bendera ini mengaktifkan konversi elemen `emphasis`. |
| InlineCode | `200` | Bendera ini mengaktifkan konversi elemen `code`. |
| Image | `400` | Bendera ini mengaktifkan konversi elemen `img`. |
| LineBreak | `800` | Bendera ini mengaktifkan konversi elemen `br`. |
| Video | `1000` | Bendera ini mengaktifkan konversi elemen `video`. |
| Table | `2000` | Bendera ini mengaktifkan konversi elemen `table`. |
| TaskList | `4000` | Bendera ini mengaktifkan konversi daftar tugas. Daftar tugas terdiri dari elemen `input`, yang harus menjadi anak pertama dari elemen `list` dan nilai atribut `type`-nya harus sama dengan `checkbox`. |
| Strikethrough | `8000` | Bendera ini mengaktifkan konversi elemen `del`. |
| Strong | `10000` | Bendera ini mengaktifkan konversi elemen `strong`. |

### Lihat Juga

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
