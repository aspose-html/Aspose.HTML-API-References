---
title: Class MutationRecord
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Dom.Mutations.MutationRecord sınıf. Mutasyon Kaydı tek bir DOM mutasyonunu temsil eder. Bu kendisine iletilen nesnedir.MutationObserver SMutationCallback .
type: docs
weight: 990
url: /tr/net/aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

Mutasyon Kaydı, tek bir DOM mutasyonunu temsil eder. Bu, kendisine iletilen nesnedir.[`MutationObserver`](../mutationobserver/) S[`MutationCallback`](../mutationcallback/) .

```csharp
public class MutationRecord : DOMObject
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AddedNodes](../../aspose.html.dom.mutations/mutationrecord/addednodes/) { get; } | Eklenen düğümleri döndürür. |
| [AttributeName](../../aspose.html.dom.mutations/mutationrecord/attributename/) { get; } | Değiştirilen özniteliğin yerel adını döndürür, aksi takdirde boştur. |
| [AttributeNamespace](../../aspose.html.dom.mutations/mutationrecord/attributenamespace/) { get; } | Değiştirilen özniteliğin ad alanını döndürür, aksi takdirde boştur. |
| [NextSibling](../../aspose.html.dom.mutations/mutationrecord/nextsibling/) { get; } | Eklenen veya kaldırılan düğümlerin bir sonraki kardeşini veya null. 'yi döndür |
| [OldValue](../../aspose.html.dom.mutations/mutationrecord/oldvalue/) { get; } | Dönüş değeri türe göre değişir. "attributes" için, değiştirilen özelliğin değişiklikten önceki değeridir. "characterData" için, değiştirilen düğümün değişiklikten önceki değeridir. "childList" için null. |
| [PreviousSibling](../../aspose.html.dom.mutations/mutationrecord/previoussibling/) { get; } | Eklenen veya kaldırılan düğümlerin önceki kardeşini veya null. döndürür |
| [RemovedNodes](../../aspose.html.dom.mutations/mutationrecord/removednodes/) { get; } | Kaldırılan düğümleri döndürür. |
| [Target](../../aspose.html.dom.mutations/mutationrecord/target/) { get; } | Türüne bağlı olarak mutasyonun etkilediği düğümü döndürür. "Nitelikler" için, niteliği değişen öğedir. "characterData" için bu, CharacterData düğümüdür. "childList" için çocukları değişen düğümdür. |
| [Type](../../aspose.html.dom.mutations/mutationrecord/type/) { get; } | Bir öznitelik mutasyonuysa "öznitelikleri", bir CharacterData düğümünün mutasyonuysa "characterData" ve düğüm ağacının bir mutasyonuysa "childList" döndürür. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Bu yöntem ECMAScript nesnesini almak için kullanılır.Type . |

### Ayrıca bakınız

* class [DOMObject](../../aspose.html.dom/domobject/)
* ad alanı [Aspose.Html.Dom.Mutations](../../aspose.html.dom.mutations/)
* toplantı [Aspose.HTML](../../)


