---
title: Class TypeInfo
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.TypeInfo sınıf. TypeInfo Document. ile ilişkili şemalarda belirtilen Element veya Attr düğümlerinden başvurulan bir türü temsil eder.
type: docs
weight: 2530
url: /tr/net/aspose.html.dom/typeinfo/
---
## TypeInfo class

TypeInfo, Document. ile ilişkili şemalarda belirtilen Element veya Attr düğümlerinden başvurulan bir türü temsil eder.

```csharp
public class TypeInfo : DOMObject
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [TypeName](../../aspose.html.dom/typeinfo/typename/) { get; } | İlişkili öğe veya öznitelik için bildirilen türün adı veya bilinmiyorsa boş. |
| [TypeNamespace](../../aspose.html.dom/typeinfo/typenamespace/) { get; } | Tür ad alanını alır. İlişkili öğe veya öznitelik için bildirilen türün ad alanını veya öğenin bildirimi yoksa veya ad alanı bilgisi yoksa boştur. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Bu yöntem ECMAScript nesnesini almak için kullanılır.Type . |
| [IsDerivedFrom](../../aspose.html.dom/typeinfo/isderivedfrom/)(string, string, ulong) | Bu yöntem, başvuru türü tanımı, yani yöntemin çağrıldığı TypeInfo ile diğer tür tanımı, yani parametre olarak iletilen arasında bir türev varsa döndürür. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [DERIVATION_EXTENSION](../../aspose.html.dom/typeinfo/derivation_extension/) | Belgenin şeması bir XML Şeması [XML Şeması Bölüm 1] ise, bu sabit uzantı yoluyla türetmeyi temsil eder. |
| const [DERIVATION_LIST](../../aspose.html.dom/typeinfo/derivation_list/) | Belgenin şeması bir XML Şeması [XML Şeması Bölüm 1] ise, bu sabit listeyi temsil eder. |
| const [DERIVATION_RESTRICTION](../../aspose.html.dom/typeinfo/derivation_restriction/) | Belgenin şeması bir XML Şeması [XML Şeması Bölüm 1] ise, bu sabit, karmaşık türler söz konusuysa kısıtlama yoluyla türetmeyi veya basit türler söz konusuysa bir kısıtlamayı temsil eder. |
| const [DERIVATION_UNION](../../aspose.html.dom/typeinfo/derivation_union/) | Belgenin şeması bir XML Şeması [XML Şeması Bölüm 1] ise, basit tipler söz konusuysa bu sabit birleşimi temsil eder. |

### Ayrıca bakınız

* class [DOMObject](../domobject/)
* ad alanı [Aspose.Html.Dom](../../aspose.html.dom/)
* toplantı [Aspose.HTML](../../)


