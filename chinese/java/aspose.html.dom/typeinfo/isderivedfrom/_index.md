---
title: "TypeInfo.IsDerivedFrom"
second_title: "Aspose.HTML for Java API 参考"
description: "TypeInfo 方法。此方法返回引用类型定义（即调用该方法的 TypeInfo）与另一个类型定义（即作为参数传入的类型）之间是否存在派生关系。"
type: docs

url: /zh/java/com.aspose.html.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

此方法返回引用类型定义（即调用该方法的 TypeInfo）与另一个类型定义（即作为参数传入的类型）之间是否存在派生关系。

```java
public bool IsDerivedFrom(String typeNamespaceArg, String typeNameArg, ulong derivationMethod)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| typeNamespaceArg | String | 另一个类型定义的命名空间。 |
| typeNameArg | String | 另一个类型定义的名称。 |
| derivationMethod | UInt64 | 两种类型之间的派生类型及其适用条件，如本接口提供的常量列表所述。 |

### 返回值

如果文档的模式是 DTD 或文档未关联任何模式，则此方法始终返回 false。如果文档的模式是 XML Schema，则当引用类型定义根据 derivation 参数从另一个类型定义派生时，方法返回 true。如果参数值为 0（即 derivationMethod 参数的位均未设置为 1），则当可以通过从引用类型定义递归任意组合的 {base type definition}、{item type definition} 或 {member type definitions} 到达另一个类型定义时，方法返回 true。

### 另请参阅

* class [TypeInfo](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
