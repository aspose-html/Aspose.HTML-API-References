---
title: "MutationRecord クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.mutations.MutationRecord クラス。MutationRecord は個々の DOM 変異を表します。これは MutationObserver の MutationCallback に渡されるオブジェクトです。"
type: docs

url: /ja/java/com.aspose.html.dom.mutations/mutationrecord/
---
## MutationRecord class

MutationRecord は個々の DOM 変異を表します。これは [`MutationObserver`](../mutationobserver/) の [`MutationCallback`](../mutationcallback/) に渡されるオブジェクトです。

```java
public class MutationRecord : DOMObject
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getAddedNodes](../../com.aspose.html.dom.mutations/mutationrecord/addednodes/) 追加されたノードを返します。 |
| [getAttributeName](../../com.aspose.html.dom.mutations/mutationrecord/attributename/) 変更された属性のローカル名を返し、そうでない場合は null を返します。 |
| [getAttributeNamespace](../../com.aspose.html.dom.mutations/mutationrecord/attributepackage/) 変更された属性のパッケージを返し、そうでない場合は null を返します。 |
| [getNextSibling](../../com.aspose.html.dom.mutations/mutationrecord/nextsibling/) 追加または削除されたノードの次の兄弟ノードを返します。null になることもあります。 |
| [getOldValue](../../com.aspose.html.dom.mutations/mutationrecord/oldvalue/) 戻り値はタイプに依存します。\"attributes\" の場合、変更前の属性の値が返されます。\"characterData\" の場合、変更前のノードのデータが返されます。\"childList\" の場合は null が返されます。 |
| [getPreviousSibling](../../com.aspose.html.dom.mutations/mutationrecord/previoussibling/) 追加または削除されたノードの前の兄弟ノードを返します。null になることもあります。 |
| [getRemovedNodes](../../com.aspose.html.dom.mutations/mutationrecord/removednodes/) 削除されたノードを返します。 |
| [getTarget](../../com.aspose.html.dom.mutations/mutationrecord/target/) 変異が影響したノードを返します。タイプに応じて、\"attributes\" の場合は属性が変更された要素、\"characterData\" の場合は CharacterData ノード、\"childList\" の場合は子が変更されたノードです。 |
| [getType](../../com.aspose.html.dom.mutations/mutationrecord/type/) \"attributes\" は属性の変異の場合、\"characterData\" は CharacterData ノードへの変異の場合、\"childList\" はノードツリーへの変異の場合に返されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |

### 関連項目

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
