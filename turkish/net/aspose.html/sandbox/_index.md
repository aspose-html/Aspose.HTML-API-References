---
title: Enum Sandbox
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Sandbox Sıralama. Korumalı alan bayrak seti potansiyel olarak güvenilmeyen kaynakların yeteneklerini kısıtlamak için kullanılan sıfır veya aşağıdaki bayraklardan daha fazlasıdır.
type: docs
weight: 4560
url: /tr/net/aspose.html/sandbox/
---
## Sandbox enumeration

Korumalı alan bayrak seti, potansiyel olarak güvenilmeyen kaynakların yeteneklerini kısıtlamak için kullanılan sıfır veya aşağıdaki bayraklardan daha fazlasıdır.

```csharp
[Flags]
public enum Sandbox
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| None | `0` | İşaret ayarlanmadı, her sanal alan özelliği kabul edildi |
| Navigation | `1` | Bu bayrak, içeriğin, korumalı alan gözatma bağlamının kendisi (veya bunun içinde daha fazla yuvalanmış olan göz atma bağlamları), yardımcı göz atma bağlamları (bir sonraki adımda tanımlanan korumalı alan yardımcı gezinme göz atma bağlamı bayrağı tarafından korunan) ve üst seviye dışındaki göz atma bağlamlarında gezinmesini engeller. göz atma içeriği (aşağıda tanımlanan korumalı alanlı üst düzey gezinme göz atma bağlamı bayrağı tarafından korunur). Korumalı alan yardımcı navigasyon göz atma içeriği bayrağı ayarlanmamışsa, bazı durumlarda kısıtlamalar yine de açılır pencerelerin (yeni üst düzey göz atma bağlamları) açılmasına izin verir. Bu göz atma bağlamlarında her zaman, göz atma bağlamı oluşturulduğunda ayarlanan ve onları oluşturan göz atma bağlamının içlerinde gerçekten gezinmesine izin veren, izin verilen bir sanal alan gezgini vardır. (Aksi takdirde, sanal alan gezinti göz atma bağlamı bayrağı, açılmış olsalar bile bunların gezinmesini engeller. |
| AuxiliaryNavigation | `2` | Bu bayrak, içeriğin yeni yardımcı göz atma bağlamları oluşturmasını engeller, örn. target özniteliği veya window.open() yöntemi. |
| TopLevelNavigation | `4` | Bu bayrak, içeriğin üst düzey göz atma bağlamında gezinmesini ve içeriğin üst düzey göz atma bağlamını kapatmasını engeller. Korumalı alanda üst düzey gezinme göz atma bağlamı bayrağı ayarlanmadığında, içerik üst düzey göz atma bağlamında gezinebilir, ancak diğer göz atma bağlamları, korumalı alanlı gezinme göz atma bağlamı bayrağı ve muhtemelen korumalı alanlı yardımcı gezinme göz atma bağlamı bayrağı tarafından korunmaya devam eder. |
| Plugins | `8` | Bu bayrak, eklentiler güvenli hale getirilmedikçe, içeriğin embed öğesi, object öğesi, applet öğesi kullanılarak veya iç içe geçmiş bir göz atma bağlamında gezinme yoluyla eklentileri başlatmasını engeller. |
| Origin | `10` | Bu bayrak, içeriği benzersiz bir kaynağa zorlar, böylece aynı kaynaktan başka içeriğe erişmesini engeller. |
| Forms | `20` | Bu işaret, form gönderimini engeller. |
| PointerLock | `40` | Bu işaret, İşaretçi Kilidi API'sini devre dışı bırakır. |
| Scripts | `80` | Bu işaret, komut dosyasının yürütülmesini engeller. |
| AutomaticFeatures | `100` | Bu bayrak, bir videoyu otomatik olarak oynatmak veya bir form denetimine otomatik olarak odaklanmak gibi otomatik olarak tetiklenen özellikleri engeller. |
| Fullscreen | `200` | Bu bayrak, içeriğin requestFullscreen() yöntemini kullanmasını engeller. |
| DocumentDomain | `400` | Bu bayrak, içeriğin, etkili betik kaynağını değiştirmek için document.domain özelliğini kullanmasını engeller. |
| Images | `800` | Bu işaret, resim yüklemeyi devre dışı bırakır. |

### Ayrıca bakınız

* ad alanı [Aspose.Html](../../aspose.html/)
* toplantı [Aspose.HTML](../../)


