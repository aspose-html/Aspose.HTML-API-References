---
title: "IDOMImplementation 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.IDOMImplementation 接口。DOMImplementation 接口提供了多种方法，用于执行与特定文档对象模型实例无关的操作。"
type: docs

url: /zh/java/com.aspose.html.dom/idomimplementation/
---
## IDOMImplementation interface

DOMImplementation 接口提供了多种方法，用于执行独立于文档对象模型特定实例的操作。

```java
public interface IDOMImplementation
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [createDocument](../../com.aspose.html.dom/idomimplementation/createdocument/)(String, String, DocumentType) | 创建一个指定类型的 DOM Document 对象及其文档元素。 |
| [createDocumentType](../../com.aspose.html.dom/idomimplementation/createdocumenttype/)(String, String, String) | 创建一个空的 DocumentType 节点。实体声明和符号未提供。实体引用展开和默认属性添加不会发生。 |
| [createHTMLDocument](../../com.aspose.html.dom/idomimplementation/createhtmldocument/)(String) | 返回一个文档，已构建包含标题元素的基本树，除非省略了 title 参数。 |
| [hasFeature](../../com.aspose.html.dom/idomimplementation/hasfeature/)() | 测试 DOM 实现是否实现了 DOM Features 中指定的特定功能和版本。 |

### 另请参阅

* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
