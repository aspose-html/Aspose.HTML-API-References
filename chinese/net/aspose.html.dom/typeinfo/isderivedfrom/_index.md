---
title: TypeInfo.IsDerivedFrom
second_title: Aspose.HTML for .NET API 参考
description: TypeInfo 方法. 如果引用类型定义即调用该方法的 TypeInfo与其他类型定义即作为参数传递的类型定义之间存在派生关系则此方法返回
type: docs
weight: 30
url: /zh/net/aspose.html.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

如果引用类型定义（即调用该方法的 TypeInfo）与其他类型定义（即作为参数传递的类型定义）之间存在派生关系，则此方法返回。

```csharp
public bool IsDerivedFrom(string typeNamespaceArg, string typeNameArg, ulong derivationMethod)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| typeNamespaceArg | String | 其他类型定义的命名空间 |
| typeNameArg | String | 其他类型定义的名称。 |
| derivationMethod | UInt64 | 派生类型和两种类型之间应用的条件，如该接口中提供的常量列表中所述。 |

### 返回值

如果文档的模式是 DTD 或没有模式与文档相关联，则此方法将始终返回 false。如果文档的模式是 XML 模式，如果引用类型定义是根据派生参数从其他类型定义派生的，则该方法将为真。如果参数的值为 0（derivationMethod 参数没有位设置为 1），如果可以通过递归{基本类型定义}、{项目类型定义}的任意组合来达到其他类型定义，则该方法将返回 true ，或引用类型定义中的{成员类型定义}.

### 也可以看看

* class [TypeInfo](../)
* 命名空间 [Aspose.Html.Dom](../../typeinfo/)
* 部件 [Aspose.HTML](../../../)


