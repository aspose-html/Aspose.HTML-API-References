---
title: "MutationObserverInit 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.mutations.MutationObserverInit 类。此类表示用于配置 MutationObserver 的选项集合。"
type: docs

url: /zh/java/com.aspose.html.dom.mutations/mutationobserverinit/
---
## MutationObserverInit class

此类表示用于配置 [`MutationObserver`](../mutationobserver/) 的选项集合。

```java
public class MutationObserverInit : IDictionary<String, object>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MutationObserverInit](mutationobserverinit/)() | 初始化 `MutationObserverInit` 类的新实例。 |

## 属性

| 名称 | 描述 |
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
| [getCount](../../com.aspose.html.dom.mutations/mutationobserverinit/count/) 获取 `MutationObserverInit` 集合中包含的键/值对的数量。 |
| [getIsReadOnly](../../com.aspose.html.dom.mutations/mutationobserverinit/isreadonly/) 确定 `MutationObserverInit` 集合是否可变。 |
[getItem]
[setItem] Gets or sets the element with the specified key. |
| [getKeys](../../com.aspose.html.dom.mutations/mutationobserverinit/keys/) 获取包含 `MutationObserverInit` 集合中键的集合。 |
[getSubtree]
[setSubtree] Set to true if mutations to not just target, but also target’s descendants are to be observed |
| [getValues](../../com.aspose.html.dom.mutations/mutationobserverinit/values/) 获取包含 `MutationObserverInit` 集合中值的集合。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [add](../../com.aspose.html.dom.mutations/mutationobserverinit/add/#add)(KeyValuePair&lt;String, object&gt;) |  |
| [add](../../com.aspose.html.dom.mutations/mutationobserverinit/add/#add_1)(String, object) | 将指定的键和值添加到 `MutationObserverInit` 集合中。 |
| [clear](../../com.aspose.html.dom.mutations/mutationobserverinit/clear/)() | 从 `MutationObserverInit` 集合中移除所有元素。 |
| [contains](../../com.aspose.html.dom.mutations/mutationobserverinit/contains/)(KeyValuePair&lt;String, object&gt;) |  |
| [containsKey](../../com.aspose.html.dom.mutations/mutationobserverinit/containskey/)(String) | 确定 `MutationObserverInit` 集合是否包含指定的键。 |
| [copyTo](../../com.aspose.html.dom.mutations/mutationobserverinit/copyto/)(KeyValuePair&lt;String, object&gt;[], int) |  |
| [getEnumerator](../../com.aspose.html.dom.mutations/mutationobserverinit/getenumerator/)() | 返回一个枚举器，用于遍历 `MutationObserverInit` 元素。 |
| [remove](../../com.aspose.html.dom.mutations/mutationobserverinit/remove/#remove)(KeyValuePair&lt;String, object&gt;) |  |
| [remove](../../com.aspose.html.dom.mutations/mutationobserverinit/remove/#remove_1)(String) | 从 `MutationObserverInit` 集合中移除与指定键关联的值。 |
| [tryGetValue](../../com.aspose.html.dom.mutations/mutationobserverinit/trygetvalue/)(String, out object) | 获取与指定键关联的值。 |

### 另请参阅

* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
