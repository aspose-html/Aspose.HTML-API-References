---
title: "ICSSStyleDeclaration.GetPropertyCSSValue"
second_title: "Aspose.HTML for Java API 参考"
description: "ICSSStyleDeclaration 方法。用于检索 CSS 属性值的对象表示（如果该属性已在此声明块中显式设置）。如果属性是简写属性，则此方法返回 null。简写属性的值只能通过 getPropertyValue 和 setProperty 方法以字符串形式访问和修改。"
type: docs

url: /zh/java/com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/
---
## ICSSStyleDeclaration.GetPropertyCSSValue method

用于检索在此声明块中显式设置的 CSS 属性值的对象表示。如果属性是简写属性，则此方法返回 null。简写属性的值只能作为字符串访问和修改，使用 getPropertyValue 和 setProperty 方法。

```java
public CSSValue GetPropertyCSSValue(String propertyName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| propertyName | String | propertyName 是一个字符串，表示要检索的属性名称。 |

### 返回值

value 是一个 CSSValue，包含属性的 CSS 值。如果不存在，则返回 null。

### 另请参见

* class [CSSValue](../../cssvalue/)
* interface [ICSSStyleDeclaration](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
