---
title: Class TypeInfo
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.TypeInfo 班级. TypeInfo 表示从 Element 或 Attr 节点引用的类型在与文档关联的模式中指定
type: docs
weight: 2530
url: /zh/net/aspose.html.dom/typeinfo/
---
## TypeInfo class

TypeInfo 表示从 Element 或 Attr 节点引用的类型，在与文档关联的模式中指定。

```csharp
public class TypeInfo : DOMObject
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [TypeName](../../aspose.html.dom/typeinfo/typename/) { get; } | 为关联元素或属性声明的类型名称，如果未知则为 null。 |
| [TypeNamespace](../../aspose.html.dom/typeinfo/typenamespace/) { get; } | 获取类型命名空间。为关联元素或属性声明的类型的命名空间；如果元素没有声明或没有可用的命名空间信息，则为 null。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |
| [IsDerivedFrom](../../aspose.html.dom/typeinfo/isderivedfrom/)(string, string, ulong) | 如果引用类型定义（即调用该方法的 TypeInfo）与其他类型定义（即作为参数传递的类型定义）之间存在派生关系，则此方法返回。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [DERIVATION_EXTENSION](../../aspose.html.dom/typeinfo/derivation_extension/) | 如果文档的模式是 XML 模式 [XML 模式第 1 部分]，则此常量表示扩展派生。 |
| const [DERIVATION_LIST](../../aspose.html.dom/typeinfo/derivation_list/) | 如果文档的模式是 XML 模式 [XML 模式第 1 部分]，则此常量表示列表。 |
| const [DERIVATION_RESTRICTION](../../aspose.html.dom/typeinfo/derivation_restriction/) | 如果文档的模式是 XML 模式 [XML 模式第 1 部分]，如果涉及复杂类型，则此常量表示限制派生，如果涉及简单类型，则表示限制。 |
| const [DERIVATION_UNION](../../aspose.html.dom/typeinfo/derivation_union/) | 如果文档的模式是 XML 模式 [XML 模式第 1 部分]，如果涉及简单类型，则此常量表示联合。 |

### 也可以看看

* class [DOMObject](../domobject/)
* 命名空间 [Aspose.Html.Dom](../../aspose.html.dom/)
* 部件 [Aspose.HTML](../../)


