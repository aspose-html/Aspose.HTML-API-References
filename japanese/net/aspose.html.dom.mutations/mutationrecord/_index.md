---
title: Class MutationRecord
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Mutations.MutationRecord クラス. MutationRecord は個々の DOM ミューテーションを表します渡されるオブジェクトですMutationObserver sMutationCallback.
type: docs
weight: 990
url: /ja/net/aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

MutationRecord は、個々の DOM ミューテーションを表します。渡されるオブジェクトです。[`MutationObserver`](../mutationobserver/) s[`MutationCallback`](../mutationcallback/).

```csharp
public class MutationRecord : DOMObject
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AddedNodes](../../aspose.html.dom.mutations/mutationrecord/addednodes/) { get; } | 追加されたノードを返します。 |
| [AttributeName](../../aspose.html.dom.mutations/mutationrecord/attributename/) { get; } | 変更された属性のローカル名を返し、それ以外の場合は null を返します。 |
| [AttributeNamespace](../../aspose.html.dom.mutations/mutationrecord/attributenamespace/) { get; } | 変更された属性の名前空間を返し、それ以外の場合は null を返します。 |
| [NextSibling](../../aspose.html.dom.mutations/mutationrecord/nextsibling/) { get; } | 追加または削除されたノードの次の兄弟、または null を返します。 |
| [OldValue](../../aspose.html.dom.mutations/mutationrecord/oldvalue/) { get; } | 戻り値は型によって異なります。 「attributes」の場合、変更前の変更された属性の値です。 「characterData」の場合、変更前の変更されたノードのデータです。 「childList」の場合、null です。 |
| [PreviousSibling](../../aspose.html.dom.mutations/mutationrecord/previoussibling/) { get; } | 追加または削除されたノードの前の兄弟、または null を返します。 |
| [RemovedNodes](../../aspose.html.dom.mutations/mutationrecord/removednodes/) { get; } | 削除されたノードを返します。 |
| [Target](../../aspose.html.dom.mutations/mutationrecord/target/) { get; } | タイプに応じて、ミューテーションが影響したノードを返します。 「属性」の場合、属性が変更された要素です。 「characterData」の場合は CharacterData ノードです。 「childList」の場合、子が変更されたノードです。 |
| [Type](../../aspose.html.dom.mutations/mutationrecord/type/) { get; } | 属性の変更の場合は「attributes」、CharacterData ノードの変更の場合は「characterData」、ノードのツリーの変更の場合は「childList」を返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | このメソッドは、ECMAScript オブジェクトを取得するために使用されますType. |

### 関連項目

* class [DOMObject](../../aspose.html.dom/domobject/)
* 名前空間 [Aspose.Html.Dom.Mutations](../../aspose.html.dom.mutations/)
* 組み立て [Aspose.HTML](../../)


