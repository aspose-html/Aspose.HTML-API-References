---
title: "License.SetLicense"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Metode License. Memberi lisensi pada komponen"
type: docs

url: /id/java/com.aspose.html/license/setlicense/
---
## SetLicense(String) {#setlicense_1}

Melisensikan komponen.

```java
public void SetLicense(String licenseName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| licenseName | String | Dapat berupa nama file lengkap atau singkat atau nama sumber daya yang disematkan. Gunakan String kosong untuk beralih ke mode evaluasi. |

## Catatan

Mencoba menemukan lisensi di lokasi berikut:

1. Jalur eksplisit.

2. Folder yang berisi assembly komponen Aspose.

3. Folder yang berisi assembly pemanggil klien.

4. Folder yang berisi assembly entri (startup).

5. Sumber daya yang disematkan dalam assembly pemanggil klien.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Jalur eksplisit.

2. Sumber daya yang disematkan dalam assembly pemanggil klien.

2. Folder yang berisi file JAR komponen Aspose.

3. Folder yang berisi file JAR pemanggil klien.

## Contoh

Dalam contoh ini, akan dicoba mencari file lisensi bernama MyLicense.lic di folder yang berisi komponen, di folder yang berisi assembly pemanggil, di folder assembly entri, dan kemudian di sumber daya tersemat dari assembly pemanggil.

```java
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

file jar komponen:

```java
License license = new License();
license.setLicense("MyLicense.lic");
```

### Lihat Juga

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## SetLicense(Stream) {#setlicense}

Melisensikan komponen.

```java
public void SetLicense(Stream stream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| aliran | Aliran | Aliran yang berisi lisensi. |

## Catatan

Gunakan metode ini untuk memuat lisensi dari aliran.

## Contoh

```java
[C#]

License license = new License();
license.SetLicense(myStream);
```

### Lihat Juga

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
