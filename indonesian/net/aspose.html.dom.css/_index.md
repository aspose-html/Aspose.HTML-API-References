---
title: Aspose.Html.Dom.Css
second_title: Aspose.HTML untuk Referensi .NET API
description: Itu Aspose.Html.Dom.Css namespace adalah untuk semua manipulasi terkait CSS. Berkonsentrasi di sekitar nama properti CSS  pasangan nilai ditentukan oleh dokumen resmi CSS.
type: docs
weight: 70
url: /id/net/aspose.html.dom.css/
---
Itu **Aspose.Html.Dom.Css** namespace adalah untuk semua manipulasi terkait CSS. Berkonsentrasi di sekitar nama properti CSS - pasangan nilai ditentukan oleh dokumen resmi CSS.

## Kelas

| Kelas | Keterangan |
| --- | --- |
| [Counter](./counter/) | Antarmuka Penghitung digunakan untuk merepresentasikan nilai fungsi penghitung atau penghitung apa pun. Antarmuka ini mencerminkan nilai dalam properti style yang mendasarinya. |
| [CSSPrimitiveValue](./cssprimitivevalue/) | Antarmuka CSSPrimitiveValue mewakili satu nilai CSS. Antarmuka ini dapat digunakan untuk menentukan nilai properti gaya tertentu yang saat ini disetel dalam blok atau untuk menyetel properti gaya tertentu secara eksplisit di dalam blok. Contoh antarmuka ini dapat diperoleh dari metode getPropertyCSSValue dari antarmuka CSSStyleDeclaration. Objek CSSPrimitiveValue hanya muncul dalam konteks properti CSS. |
| [CSSValue](./cssvalue/) | Merupakan nilai sederhana atau kompleks. Objek CSSValue hanya terjadi dalam konteks properti CSS. |
| [CSSValueList](./cssvaluelist/) | Antarmuka CSSValueList menyediakan abstraksi kumpulan nilai CSS yang diurutkan. |
| [Rect](./rect/) | Antarmuka Rect digunakan untuk mewakili nilai rect apa pun. Antarmuka ini mencerminkan nilai dalam properti style yang mendasarinya. Oleh karena itu, modifikasi yang dibuat pada objek CSSPrimitiveValue mengubah properti style. |
| [RGBColor](./rgbcolor/) | Antarmuka RGBColor digunakan untuk mewakili nilai warna RGB apa pun. Antarmuka ini mencerminkan nilai dalam properti style yang mendasarinya. Oleh karena itu, modifikasi yang dibuat pada objek CSSPrimitiveValue mengubah properti style. |
## Antarmuka

| Antarmuka | Keterangan |
| --- | --- |
| [ICSS2Properties](./icss2properties/) | Menyediakan antarmuka untuk manipulasi nilai kumpulan properti CSS2 dalam konteks elemen HTML tertentu |
| [ICSSCharsetRule](./icsscharsetrule/) | Antarmuka CSSCharsetRule mewakili aturan @charset dalam lembar gaya CSS. Nilai atribut penyandian tidak memengaruhi penyandian data teks dalam objek DOM; penyandian ini selalu UTF-16. Setelah lembar gaya dimuat, nilai atribut penyandian adalah nilai yang ditemukan dalam aturan @charset. Jika tidak ada @charset di dokumen asli, maka tidak ada CSSCharsetRule yang dibuat. Nilai atribut encoding juga dapat digunakan sebagai petunjuk untuk encoding yang digunakan pada serialisasi style sheet. |
| [ICSSCounterStyleRule](./icsscounterstylerule/) | Aturan @counter-style memungkinkan penulis menentukan gaya penghitung kustom. |
| [ICSSFontFaceRule](./icssfontfacerule/) | Antarmuka CSSFontFaceRule merepresentasikan aturan @font-face dalam lembar gaya CSS. Aturan @font-face digunakan untuk menyimpan sekumpulan deskripsi font. |
| [ICSSImportRule](./icssimportrule/) | Antarmuka CSSImportRule mewakili aturan @import dalam lembar gaya CSS. Aturan @import digunakan untuk mengimpor aturan gaya dari lembar gaya lain. |
| [ICSSKeyframeRule](./icsskeyframerule/) | Antarmuka CSSKeyframeRule mewakili aturan gaya untuk satu kunci. |
| [ICSSKeyframesRule](./icsskeyframesrule/) | Antarmuka CSSKeyframesRule mewakili satu set keyframe lengkap untuk satu animasi |
| [ICSSMarginRule](./icssmarginrule/) | Antarmuka CSSMarginRule merepresentasikan margin sesuai aturan. |
| [ICSSMediaRule](./icssmediarule/) | Antarmuka CSSMediaRule mewakili aturan @media dalam lembar gaya CSS. Aturan @media dapat digunakan untuk membatasi aturan gaya untuk jenis media tertentu. |
| [ICSSPageRule](./icsspagerule/) | Antarmuka CSSPageRule merepresentasikan aturan @page dalam lembar gaya CSS. Aturan @halaman digunakan untuk menentukan dimensi, orientasi, margin, dll. kotak halaman untuk media halaman. |
| [ICSSRule](./icssrule/) | Antarmuka CSSRule adalah antarmuka dasar abstrak untuk semua jenis pernyataan CSS. Ini termasuk kumpulan aturan dan at-rules. Implementasi diharapkan untuk mempertahankan semua aturan yang ditentukan dalam lembar gaya CSS, bahkan jika aturan tersebut tidak dikenali oleh parser. Aturan yang tidak dikenal direpresentasikan menggunakan!:ICSSUnknownRule antarmuka. |
| [ICSSRuleList](./icssrulelist/) | Antarmuka CSSRuleList menyediakan abstraksi kumpulan aturan CSS yang diurutkan. |
| [ICSSStyleDeclaration](./icssstyledeclaration/) | Antarmuka CSSStyleDeclaration mewakili satu blok deklarasi CSS. Antarmuka ini dapat digunakan untuk menentukan properti gaya yang saat ini disetel di blok atau untuk menyetel properti gaya secara eksplisit di dalam blok. |
| [ICSSStyleRule](./icssstylerule/) | Antarmuka CSSStyleRule mewakili aturan tunggal yang ditetapkan dalam lembar gaya CSS. |
| [ICSSStyleSheet](./icssstylesheet/) | Antarmuka CSSStyleSheet adalah antarmuka konkret yang digunakan untuk mewakili lembar gaya CSS yaitu, lembar gaya yang jenis kontennya adalah "teks/css". |
| [ICSSUnknownRule](./icssunknownrule/) | Antarmuka CSSUnknownRule menunjukkan at-rule yang tidak didukung oleh agen pengguna ini. |
| [ICSSValueList](./icssvaluelist/) | Antarmuka menyediakan abstraksi kumpulan nilai CSS yang diurutkan. |
| [IDocumentCSS](./idocumentcss/) | Antarmuka ini mewakili dokumen dengan tampilan CSS. |
| [IDocumentStyle](./idocumentstyle/) | Antarmuka DocumentStyle menyediakan mekanisme dimana style sheet tertanam dalam dokumen dapat diambil. Harapannya adalah bahwa instance antarmuka DocumentStyle dapat diperoleh dengan menggunakan metode pengecoran khusus yang mengikat pada instance antarmuka Dokumen. |
| [IElementCSSInlineStyle](./ielementcssinlinestyle/) | Informasi gaya sebaris yang dilampirkan ke elemen ditampilkan melalui atribut gaya. Ini merepresentasikan konten dari atribut STYLE untuk elemen HTML (atau elemen dalam skema atau DTD lain yang menggunakan atribut STYLE dengan cara yang sama). |
| [ILinkStyle](./ilinkstyle/) | Antarmuka LinkStyle menyediakan mekanisme di mana lembar gaya dapat diambil dari node yang bertanggung jawab untuk menautkannya ke dalam dokumen. Instance antarmuka LinkStyle dapat diperoleh dengan menggunakan metode pengecoran khusus yang mengikat pada instance node penautan (HTMLLinkElement, HTMLStyleElement, atau ProcessingInstruction di DOM Level 2). |
| [IMediaList](./imedialist/) | Antarmuka MediaList menyediakan abstraksi kumpulan media yang dipesan, tanpa menentukan atau membatasi bagaimana kumpulan ini diimplementasikan. Daftar kosong sama dengan daftar yang berisi media "all". |
| [IStyleSheet](./istylesheet/) | Antarmuka StyleSheet adalah antarmuka dasar abstrak untuk semua jenis style sheet. Ini mewakili satu lembar gaya yang terkait dengan dokumen terstruktur. |
| [IStyleSheetList](./istylesheetlist/) | Antarmuka StyleSheetList menyediakan abstraksi koleksi terurut dari style sheet. |
| [IViewCSS](./iviewcss/) | Antarmuka ini mewakili tampilan CSS. |
## Pencacahan

| Pencacahan | Keterangan |
| --- | --- |
| [CSSEngineMode](./cssenginemode/) | Menentukan mode CSSEngine |


