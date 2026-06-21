---
title: "Antarmuka ISVGAnimatedPathData"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "com.aspose.html.dom.svg.paths.ISVGAnimatedPathData interface. Antarmuka SVGAnimatedPathData mendukung elemen yang memiliki atribut d yang berisi data jalur SVG dan mendukung kemampuan untuk menganimasikan atribut tersebut."
type: docs

url: /id/java/com.aspose.html.dom.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

Antarmuka SVGAnimatedPathData mendukung elemen yang memiliki atribut ‘d’ yang berisi data jalur SVG, dan mendukung kemampuan untuk menganimasikan atribut tersebut.

```java
public interface ISVGAnimatedPathData
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getAnimatedPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/animatedpathseglist/) Menyediakan akses ke konten animasi terkini dari atribut ‘d’ dalam bentuk yang cocok satu-satu dengan sintaks SVG. Jika atribut atau properti yang diberikan sedang dianimasikan, berisi nilai animasi terkini dari atribut atau properti tersebut, dan objek serta isinya bersifat baca saja. Jika atribut atau properti tidak sedang dianimasikan, berisi nilai yang sama dengan pathSegList. |
| [getPathSegList](../../com.aspose.html.dom.svg.paths/isvganimatedpathdata/pathseglist/) Menyediakan akses ke konten dasar (yaitu statis) dari atribut ‘d’ dalam bentuk yang cocok satu-satu dengan sintaks SVG. Jadi, jika atribut ‘d’ memiliki perintah "absolute moveto (M)" dan "absolute arcto (A)", maka pathSegList akan memiliki dua entri: sebuah SVG_PATHSEG_MOVETO_ABS dan sebuah SVG_PATHSEG_ARC_ABS. |

### Lihat Juga

* package [com.aspose.html.dom.svg.paths](../../com.aspose.html.dom.svg.paths/)
* package [Aspose.HTML](../../)
