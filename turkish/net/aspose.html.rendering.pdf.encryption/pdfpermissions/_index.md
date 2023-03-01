---
title: Enum PdfPermissions
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Rendering.Pdf.Encryption.PdfPermissions Sıralama. Bu sıralama kullanıcının bir pdf için izinlerini temsil eder.
type: docs
weight: 4420
url: /tr/net/aspose.html.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

Bu sıralama, kullanıcının bir pdf için izinlerini temsil eder.

```csharp
[Flags]
public enum PdfPermissions
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| PrintDocument | `4` | (2. revizyon güvenlik işleyicileri) Belgeyi yazdırın. (Revizyon 3 veya üzeri güvenlik işleyicileri) Belgeyi yazdırın ( PrintingQuality'nin de ayarlanıp ayarlanmadığına bağlı olarak, muhtemelen en yüksek kalite düzeyinde olmayabilir). |
| ModifyContent | `8` | ModifyTextAnnotations, FillForm ve 11. tarafından kontrol edilenler dışındaki işlemlerle belgenin içeriğini değiştirin |
| ExtractContent | `10` | Revizyon güvenlik işleyicileri 2) Belgeden metin ve grafikleri kopyalayın veya başka bir şekilde ayıklayın, metin ve grafiklerin çıkarılması dahil (engelli kullanıcıların erişimini desteklemek için veya başka amaçlarla). (revizyon 3 veya üzeri güvenlik işleyicileri) Kopyala ya da ExtractContentWithDisabilities. tarafından kontrol edilen işlemler dışındaki işlemlerle belgeden metin ve grafikleri ayıklayın |
| ModifyTextAnnotations | `20` | Metin açıklamaları ekleyin veya değiştirin, etkileşimli form alanlarını doldurun ve ModifyContent de ayarlanmışsa etkileşimli form alanları (imza alanları dahil) oluşturun veya değiştirin. |
| FillForm | `100` | (Revizyon 3 veya üzeri güvenlik işleyicileri) ModifyTextAnnotations açık olsa bile mevcut etkileşimli form alanlarını (imza alanları dahil) doldurun. |
| ExtractContentWithDisabilities | `200` | (Revizyon 3 veya üzeri güvenlik işleyicileri) Metin ve grafikleri ayıklayın (engelli kullanıcıların erişimini desteklemek için veya başka amaçlar için). |
| AssembleDocument | `400` | (Revizyon 3 veya üzeri güvenlik işleyicileri) Belgeyi birleştirin (sayfaları ekleyin, döndürün veya silin ve yer imleri veya küçük resimler oluşturun), ModifyContent açık olsa bile. |
| PrintingQuality | `800` | (Revizyon 3 veya üzeri güvenlik işleyicileri) Belgeyi, PDF içeriğinin aslına uygun bir dijital kopyasının oluşturulabileceği bir sunuma yazdırın. Bu bit temiz olduğunda (ve bit 3 ayarlandığında), yazdırma düşük -görünümün muhtemelen düşük kalitede temsili. |

### Ayrıca bakınız

* ad alanı [Aspose.Html.Rendering.Pdf.Encryption](../../aspose.html.rendering.pdf.encryption/)
* toplantı [Aspose.HTML](../../)


