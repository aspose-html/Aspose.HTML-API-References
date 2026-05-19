---
title: "MutationObserverInit クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.mutations.MutationObserverInit クラス。このクラスは MutationObserver を構成するために使用されるオプションコレクションを表します。"
type: docs

url: /ja/java/com.aspose.html.dom.mutations/mutationobserverinit/
---
## MutationObserverInit class

このクラスは [`MutationObserver`](../mutationobserver/) を構成するために使用されるオプションコレクションを表します。

```java
public class MutationObserverInit : IDictionary<String, object>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MutationObserverInit](mutationobserverinit/)() | `MutationObserverInit` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
[getAttributeFilter]
[setAttributeFilter] Set to a list of attribute local names (without package) if not all attribute mutations need to be observed and attributes is true or omitted. |
[getAttributeOldValue]
[setAttributeOldValue] Set to true if attributes is true or omitted and target’s attribute value before the mutation needs to be recorded. |
[getAttributes]
[setAttributes] Set to true if mutations to target’s attributes are to be observed. Can be omitted if attributeOldValue and/or attributeFilter is specified. |
[getCharacterData]
[setCharacterData] Set to true if mutations to target’s data are to be observed. Can be omitted if characterDataOldValue is specified |
[getCharacterDataOldValue]
[setCharacterDataOldValue] Set to true if characterData is set to true or omitted and target’s data before the mutation needs to be recorded. |
[getChildList]
[setChildList] Set to true if mutations to target’s children are to be observed. |
| [getCount](../../com.aspose.html.dom.mutations/mutationobserverinit/count/) `MutationObserverInit` コレクションに含まれるキー/値ペアの数を取得します。 |
| [getIsReadOnly](../../com.aspose.html.dom.mutations/mutationobserverinit/isreadonly/) `MutationObserverInit` コレクションが変更可能かどうかを判断します。 |
[getItem]
[setItem] Gets or sets the element with the specified key. |
| [getKeys](../../com.aspose.html.dom.mutations/mutationobserverinit/keys/) `MutationObserverInit` コレクション内のキーを含むコレクションを取得します。 |
[getSubtree]
[setSubtree] Set to true if mutations to not just target, but also target’s descendants are to be observed |
| [getValues](../../com.aspose.html.dom.mutations/mutationobserverinit/values/) `MutationObserverInit` コレクション内の値を含むコレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [add](../../com.aspose.html.dom.mutations/mutationobserverinit/add/#add)(KeyValuePair&lt;String, object&gt;) |  |
| [add](../../com.aspose.html.dom.mutations/mutationobserverinit/add/#add_1)(String, object) | 指定されたキーと値を `MutationObserverInit` コレクションに追加します。 |
| [clear](../../com.aspose.html.dom.mutations/mutationobserverinit/clear/)() | `MutationObserverInit` コレクションからすべての要素を削除します。 |
| [contains](../../com.aspose.html.dom.mutations/mutationobserverinit/contains/)(KeyValuePair&lt;String, object&gt;) |  |
| [containsKey](../../com.aspose.html.dom.mutations/mutationobserverinit/containskey/)(String) | `MutationObserverInit` コレクションが指定されたキーを含むかどうかを判断します。 |
| [copyTo](../../com.aspose.html.dom.mutations/mutationobserverinit/copyto/)(KeyValuePair&lt;String, object&gt;[], int) |  |
| [getEnumerator](../../com.aspose.html.dom.mutations/mutationobserverinit/getenumerator/)() | `MutationObserverInit` 要素を列挙する列挙子を返します。 |
| [remove](../../com.aspose.html.dom.mutations/mutationobserverinit/remove/#remove)(KeyValuePair&lt;String, object&gt;) |  |
| [remove](../../com.aspose.html.dom.mutations/mutationobserverinit/remove/#remove_1)(String) | 指定されたキーに関連付けられた値を `MutationObserverInit` コレクションから削除します。 |
| [tryGetValue](../../com.aspose.html.dom.mutations/mutationobserverinit/trygetvalue/)(String, out object) | 指定されたキーに関連付けられた値を取得します。 |

### 関連項目

* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
