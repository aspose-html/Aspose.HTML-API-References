---
title: "CSSValueList 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.css.CSSValueList 类。CSSValueList 接口提供了有序 CSS 值集合的抽象。"
type: docs

url: /zh/java/com.aspose.html.dom.css/cssvaluelist/
---
## CSSValueList class

CSSValueList 接口提供了 CSS 值有序集合的抽象。

注意：此接口曾是创建类型化 CSS 对象模型的尝试的一部分。该尝试已被放弃，大多数浏览器并未实现它。

```java
public class CSSValueList : CSSValue, ICSSValueList, IEnumerable<CSSValue>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [CSSValueList](cssvaluelist/#constructor)() | 初始化 `CSSValueList` 类的新实例。 |
| [CSSValueList](cssvaluelist/#constructor_1)(params CSSValue[]) | 初始化 `CSSValueList` 类的新实例。 |
| [CSSValueList](cssvaluelist/#constructor_2)(IEnumerable&lt;CSSValue&gt;) | 初始化 `CSSValueList` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [cSSText](../../com.aspose.html.dom.css/cssvaluelist/csstext/) { get; set; } | [`CSSValue`](../cssvalue/) 接口的 cssText 属性表示当前计算得到的 CSS 属性值。 |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) 定义该值类型的代码。 |
| [getItem](../../com.aspose.html.dom.css/cssvaluelist/item/) CSSValueList 接口的 item() 方法用于通过序数索引检索 CSSValue。 |
| [getLength](../../com.aspose.html.dom.css/cssvaluelist/length/) CSSValueList 接口的只读属性 length 表示列表中 CSSValue 的数量。索引的有效取值范围为 0 到 length-1（含）。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | 确定指定的对象是否等于此实例。 |
| [getEnumerator](../../com.aspose.html.dom.css/cssvaluelist/getenumerator/)() | 返回一个遍历集合的枚举器。 |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | 返回此实例的哈希码。 |
| [getPlatformType](../../com.aspose.html.dom.css/cssvaluelist/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | 返回表示此实例的字符串。 |

### 另请参阅

* class [CSSValue](../cssvalue/)
* interface [ICSSValueList](../icssvaluelist/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
