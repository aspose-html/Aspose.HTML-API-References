---
title: "SVGAngle.NewValueSpecifiedUnits"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode SVGAngle. Mengatur ulang nilai sebagai angka dengan unitType terkait sehingga menggantikan nilai untuk semua atribut pada objek."
type: docs

url: /id/java/com.aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

Setel ulang nilai sebagai angka dengan unitType terkait, sehingga menggantikan nilai untuk semua atribut pada objek.

```java
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newUnitType | UInt16 | Tipe unit untuk nilai (mis., SVG_ANGLETYPE_DEG). |
| valueInSpecifiedUnits | Single | Nilai sudut. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kode [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) Dikeluarkan jika unitType adalah SVG_ANGLETYPE_UNKNOWN atau bukan konstanta tipe unit yang valid (salah satu dari konstanta SVG_ANGLETYPE_* lainnya yang didefinisikan pada antarmuka ini). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kode [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) Dikeluarkan ketika sudut sesuai dengan atribut hanya-baca atau ketika objek itu sendiri hanya-baca. |

### Lihat Juga

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
