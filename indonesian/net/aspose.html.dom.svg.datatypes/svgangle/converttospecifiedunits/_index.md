---
title: SVGAngle.ConvertToSpecifiedUnits
second_title: Aspose.HTML untuk Referensi .NET API
description: SVGAngle metode. Pertahankan nilai tersimpan dasar yang sama tetapi setel ulang pengidentifikasi unit tersimpan ke unitType yang diberikan. Atribut objek unitType valueInSpecifiedUnits dan valueAsString mungkin dimodifikasi sebagai hasil dari metode ini.
type: docs
weight: 50
url: /id/net/aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

Pertahankan nilai tersimpan dasar yang sama, tetapi setel ulang pengidentifikasi unit tersimpan ke unitType yang diberikan. Atribut objek unitType, valueInSpecifiedUnits, dan valueAsString mungkin dimodifikasi sebagai hasil dari metode ini.

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| unitType | UInt16 | Jenis unit untuk dialihkan (misalnya, SVG_ANGLETYPE_DEG). |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Kode [`NOT_SUPPORTED_ERR`](../../../aspose.html.dom/domexception/not_supported_err/) Dimunculkan jika unitType adalah SVG_ANGLETYPE_UNKNOWN atau bukan konstanta tipe unit yang valid (salah satu dari konstanta SVG_ANGLETYPE_* lain yang ditentukan pada antarmuka ini). |
| [DOMException](../../../aspose.html.dom/domexception/) | Kode [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/) Dibesarkan saat sudut sesuai dengan atribut hanya baca atau saat objek itu sendiri hanya dapat dibaca. |

### Lihat juga

* class [SVGAngle](../)
* ruang nama [Aspose.Html.Dom.Svg.DataTypes](../../svgangle/)
* perakitan [Aspose.HTML](../../../)


