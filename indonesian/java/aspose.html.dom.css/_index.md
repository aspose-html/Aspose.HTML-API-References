---
title: "com.aspose.html.dom.css"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Menyediakan antarmuka untuk Spesifikasi Gaya DOM Level 2. Cascading Style Sheets (CSS) adalah bahasa lembar gaya yang memungkinkan penulis dan pengguna menambahkan gaya seperti font dan spasi ke dokumen terstruktur seperti dokumen HTML dan aplikasi XML. Ini mendukung lembar gaya khusus media sehingga penulis dapat menyesuaikan tampilan dokumen mereka untuk peramban visual, perangkat audio, printer, perangkat braille, perangkat genggam, dll. Ini juga mendukung penempatan konten, fitur tata letak tabel untuk internasionalisasi, dan beberapa properti yang terkait dengan antarmuka pengguna. Dengan memisahkan gaya presentasi dokumen dari konten dokumen, CSS menyederhanakan penulisan Web dan pemeliharaan situs."
type: docs

url: /id/java/com.aspose.html.dom.css/
---
Menyediakan antarmuka untuk Spesifikasi Gaya DOM Level 2. Cascading Style Sheets (CSS) adalah bahasa lembar gaya yang memungkinkan penulis dan pengguna menambahkan gaya (mis., font dan spasi) ke dokumen terstruktur (mis., dokumen HTML dan aplikasi XML). CSS mendukung lembar gaya khusus media sehingga penulis dapat menyesuaikan tampilan dokumen mereka untuk peramban visual, perangkat audio, printer, perangkat braille, perangkat genggam, dll. CSS juga mendukung penempatan konten, tata letak tabel, fitur internasionalisasi, dan beberapa properti terkait antarmuka pengguna. Dengan memisahkan gaya presentasi dokumen dari kontennya, CSS menyederhanakan penulisan Web dan pemeliharaan situs.

## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [Counter](./counter/) | Antarmuka Counter digunakan untuk merepresentasikan nilai fungsi counter atau counters apa pun. Antarmuka ini mencerminkan nilai-nilai dalam properti gaya yang mendasarinya. |
| [CSSPrimitiveValue](./cssprimitivevalue/) | Antarmuka CSSPrimitiveValue diturunkan dari antarmuka CSSValue dan merepresentasikan nilai terhitung saat ini dari sebuah properti CSS. |
| [CSSValue](./cssvalue/) | Merepresentasikan nilai sederhana atau kompleks. Objek CSSValue hanya muncul dalam konteks sebuah properti CSS. |
| [CSSValueList](./cssvaluelist/) | Antarmuka CSSValueList menyediakan abstraksi dari koleksi terurut nilai-nilai CSS. |
| [Rect](./rect/) | Antarmuka Rect digunakan untuk merepresentasikan nilai rect apa pun. Antarmuka ini mencerminkan nilai-nilai dalam properti gaya yang mendasarinya. Oleh karena itu, modifikasi yang dilakukan pada objek [`CSSPrimitiveValue`](../com.aspose.html.dom.css/cssprimitivevalue/) akan mengubah properti gaya. |
| [RGBColor](./rgbcolor/) | Antarmuka RGBColor digunakan untuk merepresentasikan nilai warna RGB apa pun. Antarmuka ini mencerminkan nilai-nilai dalam properti gaya yang mendasarinya. Oleh karena itu, modifikasi yang dilakukan pada objek CSSPrimitiveValue akan mengubah properti gaya. |
## Antarmuka

| Antarmuka | Deskripsi |
| --- | --- |
| [ICSS2Properties](./icss2properties/) | Antarmuka CSS2Properties mewakili mekanisme kemudahan untuk mengambil dan mengatur properti dalam sebuah [`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/). Atribut-atribut antarmuka ini sesuai dengan semua properti yang ditentukan dalam CSS2. Mengambil sebuah atribut dari antarmuka ini setara dengan memanggil metode getPropertyValue pada antarmuka [`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/). Mengatur sebuah atribut pada antarmuka ini setara dengan memanggil metode setProperty pada antarmuka [`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/). |
| [ICSSCharsetRule](./icsscharsetrule/) | Antarmuka CSSCharsetRule mewakili aturan @charset dalam lembar gaya CSS. Nilai atribut encoding tidak memengaruhi encoding data teks dalam objek DOM; encoding ini selalu UTF-16. Setelah sebuah stylesheet dimuat, nilai atribut encoding adalah nilai yang ditemukan dalam aturan @charset. Jika tidak ada @charset dalam dokumen asli, maka tidak dibuat CSSCharsetRule. Nilai atribut encoding juga dapat digunakan sebagai petunjuk untuk encoding yang digunakan pada serialisasi lembar gaya. |
| [ICSSCounterStyleRule](./icsscounterstylerule/) | Antarmuka CSSCounterStyleRule mewakili at-rule @counter-style yang memungkinkan penulis mendefinisikan gaya counter khusus. |
| [ICSSFontFaceRule](./icssfontfacerule/) | Antarmuka CSSFontFaceRule mewakili aturan @font-face dalam lembar gaya CSS. Aturan @font-face digunakan untuk menyimpan sekumpulan deskripsi font. |
| [ICSSImportRule](./icssimportrule/) | Antarmuka CSSImportRule mewakili aturan @import dalam lembar gaya CSS. Aturan @import digunakan untuk mengimpor aturan gaya dari lembar gaya lain. |
| [ICSSKeyframeRule](./icsskeyframerule/) | Antarmuka [`CSSKeyframeRule`](../com.aspose.html.dom.css/icsskeyframerule/) menjelaskan objek yang merepresentasikan sekumpulan gaya untuk sebuah keyframe tertentu. Ini sesuai dengan isi sebuah keyframe tunggal dari at-rule @keyframes. |
| [ICSSKeyframesRule](./icsskeyframesrule/) | Properti name pada antarmuka CSSKeyframeRule mengambil dan mengatur nama animasi sebagaimana digunakan oleh properti animation-name. |
| [ICSSMarginRule](./icssmarginrule/) | Antarmuka CSSMarginRule mewakili at-rule margin (misalnya @top-left) dalam at-rule @page. |
| [ICSSMediaRule](./icssmediarule/) | Antarmuka CSSMediaRule mewakili aturan @media dalam lembar gaya CSS. Aturan @media dapat digunakan untuk membatasi aturan gaya bagi tipe media tertentu. |
| [ICSSPageRule](./icsspagerule/) | Antarmuka CSSPageRule mewakili aturan @page dalam lembar gaya CSS. Aturan @page digunakan untuk menentukan dimensi, orientasi, margin, dll. dari kotak halaman untuk media berhalaman. |
| [ICSSRule](./icssrule/) | Antarmuka CSSRule adalah antarmuka dasar abstrak untuk setiap jenis pernyataan CSS. Ini mencakup baik rule set maupun at-rule. Implementasi diharapkan mempertahankan semua aturan yang ditentukan dalam lembar gaya CSS, bahkan jika aturan tersebut tidak dikenali oleh parser. Aturan yang tidak dikenali direpresentasikan menggunakan antarmuka ini. |
| [ICSSRuleList](./icssrulelist/) | CSSRuleList merepresentasikan koleksi terurut objek [`CSSRule`](../com.aspose.html.dom.css/icssrule/) yang hanya-baca. |
| [ICSSStyleDeclaration](./icssstyledeclaration/) | Antarmuka CSSStyleDeclaration mewakili objek yang merupakan blok deklarasi CSS, dan mengekspos informasi gaya serta berbagai metode dan properti terkait gaya. |
| [ICSSStyleRule](./icssstylerule/) | Antarmuka CSSStyleRule mewakili satu aturan gaya CSS. Atribut selectorText, saat diakses, harus mengembalikan hasil serialisasi grup selector yang terkait. |
| [ICSSStyleSheet](./icssstylesheet/) | Antarmuka CSSStyleSheet mewakili satu lembar gaya CSS, dan memungkinkan Anda memeriksa serta mengubah daftar aturan yang terdapat dalam lembar gaya tersebut. Ia mewarisi properti dan metode dari induknya, [`IStyleSheet`](../com.aspose.html.dom.css/istylesheet/). |
| [ICSSUnknownRule](./icssunknownrule/) | Antarmuka CSSUnknownRule mewakili at-rule yang tidak didukung oleh agen pengguna ini. |
| [ICSSValueList](./icssvaluelist/) | Antarmuka CSSValueList diturunkan dari antarmuka [`CSSValue`](../com.aspose.html.dom.css/cssvalue/) dan menyediakan abstraksi koleksi terurut nilai-nilai CSS. |
| [IDocumentCSS](./idocumentcss/) | Antarmuka ini mewakili dokumen dengan tampilan CSS. |
| [IDocumentStyle](./idocumentstyle/) | Antarmuka DocumentStyle menyediakan mekanisme untuk mengambil lembar gaya yang disematkan dalam sebuah dokumen. Diharapkan bahwa sebuah instance dari antarmuka DocumentStyle dapat diperoleh dengan menggunakan metode casting spesifik binding pada sebuah instance dari antarmuka Document. |
| [IElementCSSInlineStyle](./ielementcssinlinestyle/) | Informasi gaya inline yang terlampir pada elemen diekspos melalui atribut style. Ini mewakili isi atribut STYLE untuk elemen HTML (atau elemen dalam skema atau DTD lain yang menggunakan atribut STYLE dengan cara yang sama). Diharapkan bahwa sebuah instance dari antarmuka ElementCSSInlineStyle dapat diperoleh dengan menggunakan metode casting spesifik binding pada sebuah instance dari antarmuka Element ketika elemen tersebut mendukung informasi gaya CSS inline. |
| [ILinkStyle](./ilinkstyle/) | Antarmuka LinkStyle menyediakan mekanisme untuk mengambil lembar gaya dari node yang bertanggung jawab menautkannya ke dalam dokumen. Sebuah instance dari antarmuka LinkStyle dapat diperoleh dengan menggunakan metode casting spesifik binding pada sebuah instance dari node penaut (HTMLLinkElement, |
| [IMediaList](./imedialist/) | Antarmuka MediaList menyediakan abstraksi koleksi terurut media, tanpa mendefinisikan atau membatasi cara koleksi ini diimplementasikan. Daftar kosong sama dengan daftar yang berisi medium "all". |
| [IStyleSheet](./istylesheet/) | Antarmuka StyleSheet adalah antarmuka dasar abstrak untuk segala jenis lembar gaya. Ia mewakili satu lembar gaya yang terkait dengan dokumen terstruktur. Dalam HTML, antarmuka StyleSheet mewakili baik lembar gaya eksternal yang disertakan melalui elemen HTML LINK, maupun elemen STYLE inline. Dalam XML, antarmuka ini mewakili lembar gaya eksternal yang disertakan melalui instruksi pemrosesan lembar gaya. Lembar gaya CSS selanjutnya akan mengimplementasikan antarmuka yang lebih khusus [`CSSStyleSheet`](../com.aspose.html.dom.css/icssstylesheet/). |
| [IStyleSheetList](./istylesheetlist/) | Antarmuka StyleSheetList mewakili daftar objek [`CSSStyleSheet`](../com.aspose.html.dom.css/icssstylesheet/). Sebuah instance dari objek ini dapat dikembalikan oleh [`Document.styleSheets`](../com.aspose.html.dom/document/stylesheets/). |
| [IViewCSS](./iviewcss/) | Antarmuka IViewCSS mewakili ekstensi pada objek Window yang memberikan akses ke nilai semua properti CSS suatu elemen. |
## Enumerasi

| Enumerasi | Deskripsi |
| --- | --- |
| [CSSEngineMode](./cssenginemode/) | Menentukan mode CSSEngine. Nilai-nilai memiliki arti berikut: |
