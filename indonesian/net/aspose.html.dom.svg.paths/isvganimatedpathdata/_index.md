---
title: Interface ISVGAnimatedPathData
second_title: Aspose.HTML untuk Referensi .NET API
description: Aspose.Html.Dom.Svg.Paths.ISVGAnimatedPathData antarmuka. Antarmuka SVGAnimatedPathData mendukung elemen yang memiliki atribut d yang menyimpan data jalur SVG dan mendukung kemampuan menganimasikan atribut tersebut.
type: docs
weight: 1680
url: /id/net/aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

Antarmuka SVGAnimatedPathData mendukung elemen yang memiliki atribut 'd' yang menyimpan data jalur SVG, dan mendukung kemampuan menganimasikan atribut tersebut.

```csharp
public interface ISVGAnimatedPathData
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [AnimatedPathSegList](../../aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) { get; } | Menyediakan akses ke konten animasi saat ini dari atribut 'd' dalam bentuk yang cocok satu-untuk-satu dengan sintaks SVG. Jika atribut atau properti yang diberikan sedang dianimasikan, berisi nilai animasi saat ini dari atribut atau properti, dan objek itu sendiri serta isinya hanya dapat dibaca. Jika atribut atau properti yang diberikan saat ini tidak sedang dianimasikan, berisi nilai yang sama dengan pathSegList. |
| [PathSegList](../../aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) { get; } | Menyediakan akses ke konten dasar (yaitu, statis) dari atribut 'd' dalam bentuk yang cocok satu-untuk-satu dengan sintaks SVG. Jadi, jika atribut 'd' memiliki perintah "absolute moveto (M)" dan "absolute arcto (A)", maka pathSegList akan memiliki dua entri: SVG_PATHSEG_MOVETO_ABS dan SVG_PATHSEG_ARC_ABS. |

### Lihat juga

* ruang nama [Aspose.Html.Dom.Svg.Paths](../../aspose.html.dom.svg.paths/)
* perakitan [Aspose.HTML](../../)


