---
title: "TypeInfo 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.TypeInfo 类。TypeInfo 表示从文档关联的模式中指定的 Element 或 Attr 节点引用的类型"
type: docs

url: /zh/java/com.aspose.html.dom/typeinfo/
---
## TypeInfo class

TypeInfo 表示从 Element 或 Attr 节点引用的类型，该类型在与文档关联的模式中指定。

```java
public class TypeInfo : DOMObject
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getTypeName](../../com.aspose.html.dom/typeinfo/typename/) 与关联的元素或属性声明的类型名称，如果未知则为 null。 |
| [getTypeNamespace](../../com.aspose.html.dom/typeinfo/typepackage/) 获取类型包。该类型为关联的元素或属性声明的包，如果元素没有声明或没有可用的包信息，则为 null。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |
| [isDerivedFrom](../../com.aspose.html.dom/typeinfo/isderivedfrom/)(String, String, ulong) | 此方法返回引用类型定义（即调用该方法的 TypeInfo）与另一个类型定义（即作为参数传入的类型）之间是否存在派生关系。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [DERIVATION_EXTENSION](../../com.aspose.html.dom/typeinfo/derivation_extension/) | 如果文档的模式是 XML Schema [XML Schema Part 1]，此常量表示通过扩展的派生。 |
| const [DERIVATION_LIST](../../com.aspose.html.dom/typeinfo/derivation_list/) | 如果文档的模式是 XML Schema [XML Schema Part 1]，此常量表示列表。 |
| const [DERIVATION_RESTRICTION](../../com.aspose.html.dom/typeinfo/derivation_restriction/) | 如果文档的模式是 XML Schema [XML Schema Part 1]，此常量表示如果涉及复合类型则通过限制的派生，或者如果涉及简单类型则为限制。 |
| const [DERIVATION_UNION](../../com.aspose.html.dom/typeinfo/derivation_union/) | 如果文档的模式是 XML Schema [XML Schema Part 1]，此常量表示如果涉及简单类型则为联合。 |

### 另请参阅

* class [DOMObject](../domobject/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
