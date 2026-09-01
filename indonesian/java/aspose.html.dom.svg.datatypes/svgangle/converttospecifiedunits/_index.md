---
title: "SVGAngle.ConvertToSpecifiedUnits"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode SVGAngle. Mempertahankan nilai yang tersimpan di bawahnya tetap sama tetapi mengatur ulang pengidentifikasi unit yang disimpan ke unitType yang diberikan. Atribut objek unitType, valueInSpecifiedUnits, dan valueAsString mungkin dimodifikasi sebagai hasil dari metode ini."
type: docs

url: /id/java/com.aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

Pertahankan nilai dasar yang tersimpan yang sama, tetapi setel ulang pengidentifikasi unit yang disimpan ke unitType yang diberikan. Atribut objek unitType, valueInSpecifiedUnits, dan valueAsString mungkin dimodifikasi sebagai hasil dari metode ini.

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| unitType | UInt16 | Tipe unit untuk beralih ke (mis., SVG_ANGLETYPE_DEG). |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kode [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) Dikeluarkan jika unitType adalah SVG_ANGLETYPE_UNKNOWN atau bukan konstanta tipe unit yang valid (salah satu dari konstanta SVG_ANGLETYPE_* lainnya yang didefinisikan pada antarmuka ini). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kode [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/) Dikeluarkan ketika sudut sesuai dengan atribut hanya-baca atau ketika objek itu sendiri hanya-baca. |

### Lihat Juga

* class [SVGAngle](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
