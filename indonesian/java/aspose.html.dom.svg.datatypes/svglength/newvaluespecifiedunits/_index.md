---
title: "SVGLength.NewValueSpecifiedUnits"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "SVGLength method. Mengatur ulang nilai sebagai angka dengan unitType terkait sehingga menggantikan nilai untuk semua atribut pada objek"
type: docs

url: /id/java/com.aspose.html.dom.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

Setel ulang nilai sebagai angka dengan unitType terkait, sehingga menggantikan nilai untuk semua atribut pada objek.

```java
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| unitType | UInt16 | Tipe unit untuk nilai ini. |
| valueInSpecifiedUnits | Single | Nilai baru.. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kode [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) Dikeluarkan jika unitType adalah SVG_LENGTHTYPE_UNKNOWN atau bukan konstanta tipe unit yang valid (salah satu konstanta SVG_LENGTHTYPE_* lainnya yang didefinisikan pada antarmuka ini). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kode [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)Dikeluarkan ketika panjang sesuai dengan atribut hanya-baca atau ketika objek itu sendiri hanya-baca. |

### Lihat Juga

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
