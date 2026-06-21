---
title: "IWindow.Atob"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode IWindow. Mengambil data masukan dalam bentuk Unicode String yang berisi data biner yang di-encode base64, mendekodenya, dan mengembalikan String yang terdiri dari karakter dalam rentang U0000 hingga U00FF masing-masing mewakili byte biner dengan nilai 0x00 hingga 0xFF secara berurutan yang sesuai dengan data biner tersebut."
type: docs

url: /id/java/com.aspose.html.window/iwindow/atob/
---
## IWindow.Atob method

Menerima data masukan, berupa String Unicode yang berisi data biner yang di-encode base64, mendekodenya, dan mengembalikan String yang terdiri dari karakter dalam rentang U+0000 hingga U+00FF, masing-masing mewakili byte biner dengan nilai 0x00 hingga 0xFF secara berurutan, yang sesuai dengan data biner tersebut.

```java
public String Atob(String data)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | String | Unicode String yang berisi data biner yang di-encode base64 |

### Nilai Kembali

String yang terdiri dari karakter dalam rentang U+0000 hingga U+00FF

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Melemparkan "InvalidCharacterError" DOMException jika String masukan bukan data base64 yang valid. |

### Lihat Juga

* interface [IWindow](../)
* package [com.aspose.html.window](../../../com.aspose.html.window/)
* package [Aspose.HTML](../../../)
