---
title: Class DOMException
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.DOMException 班级. DOMException 接口表示异常事件称为异常它是由于调用方法或访问 Web API 的属性而发生的这基本上是 Web API 中描述错误情况的方式
type: docs
weight: 640
url: /zh/net/aspose.html.dom/domexception/
---
## DOMException class

DOMException 接口表示异常事件（称为异常），它是由于调用方法或访问 Web API 的属性而发生的。这基本上是 Web API 中描述错误情况的方式。

```csharp
public class DOMException : PlatformException
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [DOMException](domexception/#constructor)(string) | 初始化一个新的实例`DOMException`类. |
| [DOMException](domexception/#constructor_1)(string, string) | 初始化一个新的实例`DOMException`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Code](../../aspose.html.dom/domexception/code/) { get; } | 返回一个包含错误代码常量之一的值，如果不匹配则返回 0。由于历史原因使用该字段。 |
| override [Message](../../aspose.html.dom/domexception/message/) { get; } | 返回表示与给定错误名称关联的消息或描述的字符串。 |
| [Name](../../aspose.html.dom/domexception/name/) { get; } | 返回一个字符串，其中包含与错误名称关联的字符串之一。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [ABORT_ERR](../../aspose.html.dom/domexception/abort_err/) | 操作被中止。 |
| const [DATA_CLONE_ERR](../../aspose.html.dom/domexception/data_clone_err/) | 无法克隆对象。 |
| const [DOMSTRING_SIZE_ERR](../../aspose.html.dom/domexception/domstring_size_err/) | 如果指定的文本范围不适合 DOMString. |
| const [HIERARCHY_REQUEST_ERR](../../aspose.html.dom/domexception/hierarchy_request_err/) | 如果任何节点被插入到它不属于的地方。 |
| const [INDEX_SIZE_ERR](../../aspose.html.dom/domexception/index_size_err/) | 如果索引或大小为负数，或大于允许值。 |
| const [INUSE_ATTRIBUTE_ERR](../../aspose.html.dom/domexception/inuse_attribute_err/) | 如果尝试添加已在别处使用的属性。 |
| const [INVALID_ACCESS_ERR](../../aspose.html.dom/domexception/invalid_access_err/) | 如果底层对象不支持参数或操作。 |
| const [INVALID_CHARACTER_ERR](../../aspose.html.dom/domexception/invalid_character_err/) | 如果指定了无效或非法字符，例如在 XML 名称中。 |
| const [INVALID_EXPRESSION_ERR](../../aspose.html.dom/domexception/invalid_expression_err/) | 表达式有语法错误，或者根据 specific XPathEvaluator 的规则不是合法表达式，或者包含此实现不支持的专用扩展函数或变量。 |
| const [INVALID_MODIFICATION_ERR](../../aspose.html.dom/domexception/invalid_modification_err/) | 如果尝试修改基础对象的类型。 |
| const [INVALID_NODE_TYPE_ERR](../../aspose.html.dom/domexception/invalid_node_type_err/) | 提供的节点不正确或此操作的祖先不正确。 |
| const [INVALID_STATE_ERR](../../aspose.html.dom/domexception/invalid_state_err/) | 如果尝试使用不可用或不再可用的对象。 |
| const [NAMESPACE_ERR](../../aspose.html.dom/domexception/namespace_err/) | 如果尝试以不正确的命名空间方式创建或更改对象。 |
| const [NETWORK_ERR](../../aspose.html.dom/domexception/network_err/) | 发生网络错误。 |
| const [NOT_FOUND_ERR](../../aspose.html.dom/domexception/not_found_err/) | 如果尝试在不存在的上下文中引用节点。 |
| const [NOT_SUPPORTED_ERR](../../aspose.html.dom/domexception/not_supported_err/) | 如果实现不支持请求的对象或操作类型。 |
| const [NO_DATA_ALLOWED_ERR](../../aspose.html.dom/domexception/no_data_allowed_err/) | 如果为不支持数据的节点指定了数据。 |
| const [NO_MODIFICATION_ALLOWED_ERR](../../aspose.html.dom/domexception/no_modification_allowed_err/) | 如果尝试修改不允许修改的对象。 |
| const [QUOTA_EXCEEDED_ERR](../../aspose.html.dom/domexception/quota_exceeded_err/) | 已超出配额。 |
| const [SECURITY_ERR](../../aspose.html.dom/domexception/security_err/) | 操作不安全。 |
| const [SYNTAX_ERR](../../aspose.html.dom/domexception/syntax_err/) | 如果指定了无效或非法的字符串。 |
| const [TIMEOUT_ERR](../../aspose.html.dom/domexception/timeout_err/) | 操作超时。 |
| const [TYPE_ERR](../../aspose.html.dom/domexception/type_err/) | 表达式无法转换为返回指定类型。 |
| const [TYPE_MISMATCH_ERR](../../aspose.html.dom/domexception/type_mismatch_err/) | 如果对象的类型与关联到该对象的参数的预期类型不兼容。 |
| const [URL_MISMATCH_ERR](../../aspose.html.dom/domexception/url_mismatch_err/) | 给定的 URL 与另一个 URL 不匹配。 |
| const [VALIDATION_ERR](../../aspose.html.dom/domexception/validation_err/) | 如果调用 insertBefore 或 removeChild 等方法会使节点在“部分有效性”方面无效，则会引发此异常并且不会完成操作。此代码用于 [DOM Level 3 Validation]。有关详细信息，请参阅此规范。 |
| const [WRONG_DOCUMENT_ERR](../../aspose.html.dom/domexception/wrong_document_err/) | 如果节点在与创建它的文档不同的文档中使用（不支持它）。 |

### 也可以看看

* class [PlatformException](../../aspose.html/platformexception/)
* 命名空间 [Aspose.Html.Dom](../../aspose.html.dom/)
* 部件 [Aspose.HTML](../../)


