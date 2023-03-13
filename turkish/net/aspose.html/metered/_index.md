---
title: Class Metered
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Metered sınıf. Ölçülen anahtarı ayarlamak için yöntemler sağlar.
type: docs
weight: 3830
url: /tr/net/aspose.html/metered/
---
## Metered class

Ölçülen anahtarı ayarlamak için yöntemler sağlar.

```csharp
public class Metered
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Metered](metered/)() | Bu sınıfın yeni bir örneğini başlatır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [SetMeteredKey](../../aspose.html/metered/setmeteredkey/)(string, string) | Ölçülü açık ve özel anahtarı ayarlar. Ölçülü lisans satın alırsanız, uygulamayı başlattığınızda bu API çağrılmalıdır, normalde bu yeterlidir. Ancak, her zaman tüketim verilerini yükleyemez ve 24 saati aşarsa, lisans değerlendirme durumuna ayarlanır, böyle bir durumla karşılaşmamak için, lisans durumunu düzenli olarak kontrol etmelisiniz, değerlendirme durumuysa, bu API'yi tekrar arayın. |
| static [GetConsumptionCredit](../../aspose.html/metered/getconsumptioncredit/)() | Tüketim kredisi alır |
| static [GetConsumptionQuantity](../../aspose.html/metered/getconsumptionquantity/)() | Tüketim dosyası boyutunu alır |

### Örnekler

Bu örnekte, ölçülü genel ve özel anahtar ayarlanmaya çalışılacaktır.

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

bileşen jar dosyası:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Ayrıca bakınız

* ad alanı [Aspose.Html](../../aspose.html/)
* toplantı [Aspose.HTML](../../)


