---
title: "SVGLength.ConvertToSpecifiedUnits"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode SVGLength. Menjaga nilai yang tersimpan di bawah tetap sama tetapi mengatur ulang pengidentifikasi satuan yang disimpan ke unitType yang diberikan. Atribut objek unitType, valueInSpecifiedUnits, dan valueAsString dapat dimodifikasi sebagai hasil dari metode ini. Misalnya, jika nilai asli adalah 0,5cm dan metode dipanggil untuk mengonversi ke milimeter, maka unitType akan diubah menjadi SVG_LENGTHTYPE_MM, valueInSpecifiedUnits akan diubah menjadi nilai numerik 5, dan valueAsString akan diubah menjadi 5mm."
type: docs

url: /id/java/com.aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

Pertahankan nilai yang tersimpan di bawah yang sama, tetapi atur ulang pengidentifikasi unit yang tersimpan ke unitType yang diberikan. Atribut objek unitType, valueInSpecifiedUnits, dan valueAsString mungkin dimodifikasi sebagai hasil dari metode ini. Misalnya, jika nilai asli adalah "0.5cm" dan metode dipanggil untuk mengonversi ke milimeter, maka unitType akan diubah menjadi SVG_LENGTHTYPE_MM, valueInSpecifiedUnits akan diubah menjadi nilai numerik 5, dan valueAsString akan diubah menjadi "5mm".

```java
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| unitType | UInt16 | Tipe unit yang akan diganti (misalnya, SVG_LENGTHTYPE_MM). |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kode [`NOT_SUPPORTED_ERR`](../../../com.aspose.html.dom/domexception/not_supported_err/) Dikeluarkan jika unitType adalah SVG_LENGTHTYPE_UNKNOWN atau bukan konstanta tipe unit yang valid (salah satu konstanta SVG_LENGTHTYPE_* lainnya yang didefinisikan pada antarmuka ini). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Kode [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)Dikeluarkan ketika panjang sesuai dengan atribut hanya-baca atau ketika objek itu sendiri hanya-baca. |

### Lihat Juga

* class [SVGLength](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
