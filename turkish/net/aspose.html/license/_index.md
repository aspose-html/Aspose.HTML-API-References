---
title: Class License
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.License sınıf. Bileşeni lisanslamak için yöntemler sağlar.
type: docs
weight: 3810
url: /tr/net/aspose.html/license/
---
## License class

Bileşeni lisanslamak için yöntemler sağlar.

```csharp
public class License
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [License](license/)() | Bu sınıfın yeni bir örneğini başlatır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [SetLicense](../../aspose.html/license/setlicense/#setlicense)(Stream) | Bileşeni lisanslar. |
| [SetLicense](../../aspose.html/license/setlicense/#setlicense_1)(string) | Bileşeni lisanslar. |

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

* ad alanı [Aspose.Html](../../aspose.html/)
* toplantı [Aspose.HTML](../../)


