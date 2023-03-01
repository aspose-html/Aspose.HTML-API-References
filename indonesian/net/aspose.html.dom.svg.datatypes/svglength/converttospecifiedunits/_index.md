---
title: SVGLength.ConvertToSpecifiedUnits
second_title: Aspose.HTML untuk Referensi .NET API
description: SVGLength metode. Pertahankan nilai tersimpan dasar yang sama tetapi setel ulang pengidentifikasi unit tersimpan ke unitType yang diberikan. Atribut objek unitType valueInSpecifiedUnits dan valueAsString mungkin dimodifikasi sebagai hasil dari metode ini. Misalnya jika nilai aslinya adalah 05 cm dan metode dipanggil untuk diubah menjadi milimeter maka unitType akan diubah menjadi SVG_LENGTHTYPE_MM valueInSpecifiedUnits akan diubah menjadi nilai numerik 5 dan valueAsString akan diubah menjadi 5mm.
type: docs
weight: 50
url: /id/net/aspose.html.dom.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

Pertahankan nilai tersimpan dasar yang sama, tetapi setel ulang pengidentifikasi unit tersimpan ke unitType yang diberikan. Atribut objek unitType, valueInSpecifiedUnits, dan valueAsString mungkin dimodifikasi sebagai hasil dari metode ini. Misalnya, jika nilai aslinya adalah "0,5 cm" dan metode dipanggil untuk diubah menjadi milimeter, maka unitType akan diubah menjadi SVG_LENGTHTYPE_MM, valueInSpecifiedUnits akan diubah menjadi nilai numerik 5 dan valueAsString akan diubah menjadi "5mm".

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| unitType | UInt16 | Jenis unit untuk dialihkan (misalnya, SVG_LENGTHTYPE_MM). |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Kode [`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) Dimunculkan jika unitType adalah SVG_LENGTHTYPE_UNKNOWN atau bukan konstanta tipe unit yang valid (salah satu dari konstanta SVG_LENGTHTYPE_* lain yang ditentukan pada antarmuka ini). |
| [DOMException](../../../aspose.html.dom/domexception/) | Kode [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Dibesarkan saat panjangnya sesuai dengan atribut hanya baca atau saat objek itu sendiri hanya baca. |

### Lihat juga

* class [SVGLength](../)
* ruang nama [Aspose.Html.Dom.Svg.DataTypes](../../svglength/)
* perakitan [Aspose.HTML](../../../)


