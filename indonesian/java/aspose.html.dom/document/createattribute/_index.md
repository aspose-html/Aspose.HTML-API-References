---
title: "Document.CreateAttribute"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode Document. Metode Document.createAttribute membuat node atribut baru dan mengembalikannya. Objek yang dibuat adalah node yang mengimplementasikan antarmuka Attr. DOM tidak memaksa jenis atribut apa yang dapat ditambahkan ke elemen tertentu dengan cara ini."
type: docs

url: /id/java/com.aspose.html.dom/document/createattribute/
---
## Document.CreateAttribute method

Metode Document.createAttribute() membuat node atribut baru, dan mengembalikannya. Objek yang dibuat adalah node yang mengimplementasikan antarmuka [`Attr`](../../attr/). DOM tidak memaksa jenis atribut apa yang dapat ditambahkan ke elemen tertentu dengan cara ini.

```java
public Attr CreateAttribute(String localName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | String | name adalah String yang berisi nama atribut. |

### Nilai Kembali

Sebuah node [`Attr`](../../attr/).

## Contoh

```java
var element = document.GetElementById("div");
var attr = document.CreateAttribute("my_attr");
attr.Value = "my_value";
element.SetAttributeNode(attr);
```

### Lihat Juga

* class [Attr](../../attr/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
