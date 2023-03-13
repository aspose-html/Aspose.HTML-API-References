---
title: Class SVGAngle
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Svg.DataTypes.SVGAngle kelas. Antarmuka SVGAngle sesuai dengan tipe data dasar sudut.
type: docs
weight: 1060
url: /id/net/aspose.html.dom.svg.datatypes/svgangle/
---
## SVGAngle class

Antarmuka SVGAngle sesuai dengan tipe data dasar sudut.

```csharp
public class SVGAngle : SVGValueType
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [UnitType](../../aspose.html.dom.svg.datatypes/svgangle/unittype/) { get; } | Jenis nilai seperti yang ditentukan oleh salah satu konstanta SVG_ANGLETYPE_* yang ditentukan pada antarmuka ini. |
| [Value](../../aspose.html.dom.svg.datatypes/svgangle/value/) { get; set; } | Nilai sudut sebagai nilai floating point, dalam derajat. Menetapkan atribut ini akan menyebabkan valueInSpecifiedUnits dan valueAsString diperbarui secara otomatis untuk mencerminkan pengaturan ini. |
| [ValueAsString](../../aspose.html.dom.svg.datatypes/svgangle/valueasstring/) { get; set; } | Nilai sudut sebagai nilai string, dalam satuan yang dinyatakan oleh unitType. Menyetel atribut ini akan menyebabkan nilai, valueInSpecifiedUnits, dan unitType diperbarui secara otomatis untuk mencerminkan setelan ini. |
| [ValueInSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svgangle/valueinspecifiedunits/) { get; set; } | Nilai sudut sebagai nilai floating point, dalam satuan yang dinyatakan oleh unitType. Menyetel atribut ini akan menyebabkan value dan valueAsString diperbarui secara otomatis untuk mencerminkan setelan ini. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svgangle/converttospecifiedunits/)(ushort) | Pertahankan nilai tersimpan dasar yang sama, tetapi setel ulang pengidentifikasi unit tersimpan ke unitType yang diberikan. Atribut objek unitType, valueInSpecifiedUnits, dan valueAsString mungkin dimodifikasi sebagai hasil dari metode ini. |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Merilis sumber daya yang tidak dikelola dan - opsional - dikelola. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScriptType . |
| [NewValueSpecifiedUnits](../../aspose.html.dom.svg.datatypes/svgangle/newvaluespecifiedunits/)(ushort, float) | Setel ulang nilai sebagai angka dengan unitType terkait, sehingga mengganti nilai untuk semua atribut pada objek. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgangle/tostring/)() | Mengembalikan aString yang mewakili instance ini. |

## Bidang

| Nama | Keterangan |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_deg/) | Jenis unit secara eksplisit disetel ke derajat. |
| const [SVG_ANGLETYPE_GRAD](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_grad/) | Jenis satuan adalah radian. |
| const [SVG_ANGLETYPE_RAD](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_rad/) | Jenis satuan adalah radian. |
| const [SVG_ANGLETYPE_UNKNOWN](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unknown/) | Tipe unit bukan salah satu dari tipe unit yang telah ditentukan sebelumnya. Tidak valid mencoba menentukan nilai baru dari jenis ini atau mencoba mengalihkan nilai yang ada ke jenis ini. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../aspose.html.dom.svg.datatypes/svgangle/svg_angletype_unspecified/) | Tidak ada tipe unit yang diberikan (yaitu, nilai tanpa unit ditentukan). Untuk sudut, nilai tanpa satuan diperlakukan sama seperti jika derajat ditentukan. |

### Lihat juga

* class [SVGValueType](../svgvaluetype/)
* ruang nama [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* perakitan [Aspose.HTML](../../)


