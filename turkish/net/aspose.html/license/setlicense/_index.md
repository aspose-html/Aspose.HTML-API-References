---
title: License.SetLicense
second_title: Aspose.HTML for .NET API Referansı
description: License yöntem. Bileşeni lisanslar.
type: docs
weight: 20
url: /tr/net/aspose.html/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Bileşeni lisanslar.

```csharp
public void SetLicense(string licenseName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| licenseName | String | Tam veya kısa bir dosya adı olabilir veya katıştırılmış bir kaynağın adı. Değerlendirme moduna geçmek için boş bir dize kullanın. |

### Notlar

Lisansı aşağıdaki konumlarda bulmaya çalışır:

1. Açık yol.

2. Aspose bileşen montajını içeren klasör.

3. İstemcinin çağrı derlemesini içeren klasör.

4. Giriş (başlangıç) derlemesini içeren klasör.

5. İstemcinin çağrı derlemesinde katıştırılmış bir kaynak.

**Not:**.NET Compact Framework üzerinde, lisansı yalnızca şu konumlarda bulmaya çalışır:

1. Açık yol.

2. İstemcinin çağrı derlemesinde katıştırılmış bir kaynak.

2. Aspose bileşen JAR dosyasını içeren klasör.

3. İstemcinin çağıran JAR dosyasını içeren klasör.

### Örnekler

Bu örnekte, içeren klasörde MyLicense.lic adlı bir lisans dosyası bulunmaya çalışılacaktır. bileşen, çağıran derlemeyi içeren klasörde, giriş derlemesinin klasöründe ve ardından çağıran derlemenin katıştırılmış kaynaklarında.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

bileşen jar dosyası:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Ayrıca bakınız

* class [License](../)
* ad alanı [Aspose.Html](../../license/)
* toplantı [Aspose.HTML](../../../)

---

## SetLicense(Stream) {#setlicense}

Bileşeni lisanslar.

```csharp
public void SetLicense(Stream stream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Lisansı içeren bir akış. |

### Notlar

Akıştan lisans yüklemek için bu yöntemi kullanın.

### Örnekler

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);
```

### Ayrıca bakınız

* class [License](../)
* ad alanı [Aspose.Html](../../license/)
* toplantı [Aspose.HTML](../../../)


