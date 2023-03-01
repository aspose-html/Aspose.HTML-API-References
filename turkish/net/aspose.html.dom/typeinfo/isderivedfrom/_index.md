---
title: TypeInfo.IsDerivedFrom
second_title: Aspose.HTML for .NET API Referansı
description: TypeInfo yöntem. Bu yöntem başvuru türü tanımı yani yöntemin çağrıldığı TypeInfo ile diğer tür tanımı yani parametre olarak iletilen arasında bir türev varsa döndürür.
type: docs
weight: 30
url: /tr/net/aspose.html.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

Bu yöntem, başvuru türü tanımı, yani yöntemin çağrıldığı TypeInfo ile diğer tür tanımı, yani parametre olarak iletilen arasında bir türev varsa döndürür.

```csharp
public bool IsDerivedFrom(string typeNamespaceArg, string typeNameArg, ulong derivationMethod)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| typeNamespaceArg | String | diğer tür tanımının ad alanı |
| typeNameArg | String | diğer tür tanımının adı. |
| derivationMethod | UInt64 | bu arabirimde sağlanan sabitler listesinde açıklandığı gibi, türetme türü ve iki tür arasında uygulanan koşullar. |

### Geri dönüş değeri

Belgenin şeması bir DTD ise veya belgeyle ilişkilendirilmiş bir şema yoksa, bu yöntem her zaman yanlış döndürür. Belgenin şeması bir XML Şeması ise, referans tipi tanımı türetme parametresine göre diğer tip tanımından türetilmişse yöntem doğru olacaktır. Parametrenin değeri 0 ise (derivasyonMetodu parametresi için hiçbir bit 1 olarak ayarlanmaz), {temel tip tanımı}, {öğe tipi tanımı}'nın herhangi bir kombinasyonunu yineleyerek diğer tür tanımına ulaşılabiliyorsa, yöntem true değerini döndürür. veya referans türü tanımından {üye türü tanımları}.

### Ayrıca bakınız

* class [TypeInfo](../)
* ad alanı [Aspose.Html.Dom](../../typeinfo/)
* toplantı [Aspose.HTML](../../../)


