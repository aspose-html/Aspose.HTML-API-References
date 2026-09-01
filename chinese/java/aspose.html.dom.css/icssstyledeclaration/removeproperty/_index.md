---
title: "ICSSStyleDeclaration.RemoveProperty"
second_title: "Aspose.HTML for Java API 参考"
description: "ICSSStyleDeclaration 方法。CSSStyleDeclaration.removeProperty 方法接口用于从 CSS 样式声明对象中移除属性。"
type: docs

url: /zh/java/com.aspose.html.dom.css/icssstyledeclaration/removeproperty/
---
## ICSSStyleDeclaration.RemoveProperty method

CSSStyleDeclaration.removeProperty() 方法接口从 CSS 样式声明对象中移除属性。

```java
public String RemoveProperty(String propertyName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| propertyName | String | propertyName 是一个字符串，表示要移除的属性名称。请注意，多词属性名称使用连字符而非驼峰式。 |

### 返回值

oldValue 是一个 DOMString，等于属性被移除前的 CSS 属性值。

### 异常

| 异常 | 条件 |
| --- | --- |
| DOMException | NO_MODIFICATION_ALLOWED_ERR：如果属性或声明块是只读的。 |

### 另请参见

* interface [ICSSStyleDeclaration](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
