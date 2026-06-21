---
title: "IWindow.Btoa"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode IWindow. Mengambil data masukan dalam bentuk Unicode String yang hanya berisi karakter dalam rentang U0000 hingga U00FF masing-masing mewakili byte biner dengan nilai 0x00 hingga 0xFF secara berurutan dan mengonversinya ke representasi base64 yang dikembalikan."
type: docs

url: /id/java/com.aspose.html.window/iwindow/btoa/
---
## IWindow.Btoa method

Menerima data masukan, berupa String Unicode yang hanya berisi karakter dalam rentang U+0000 hingga U+00FF, masing-masing mewakili byte biner dengan nilai 0x00 hingga 0xFF secara berurutan, dan mengubahnya menjadi representasi base64, yang kemudian dikembalikan.

```java
public String Btoa(String data)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | String | String Unicode yang berisi hanya karakter dalam rentang U+0000 hingga U+00FF. |

### Nilai Kembali

String base64.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Melemparkan pengecualian "InvalidCharacterError" DOMException jika String masukan berisi karakter di luar rentang. |

### Lihat Juga

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
