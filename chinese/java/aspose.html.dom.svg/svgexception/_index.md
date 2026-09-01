---
title: "SVGException 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.svg.SVGException 类。当特定的 SVG 操作无法执行时会抛出此异常。"
type: docs

url: /zh/java/com.aspose.html.dom.svg/svgexception/
---
## SVGException class

当特定的 SVG 操作无法执行时，会抛出此异常。

```java
public class SVGException : PlatformException
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGException](svgexception/)(ushort) | 初始化 `SVGException` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [getCode](../../com.aspose.html.dom.svg/svgexception/code/) 一个代码，用于标识请求的操作无法执行的原因。此成员的值将是 SVGException 代码组中的常量之一。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [SVG_INVALID_VALUE_ERR](../../com.aspose.html.dom.svg/svgexception/svg_invalid_value_err/) | 当向操作传递无效值或分配给属性时抛出此异常。 |
| const [SVG_MATRIX_NOT_INVERTABLE](../../com.aspose.html.dom.svg/svgexception/svg_matrix_not_invertable/) | 当尝试求逆一个不可逆的矩阵时抛出此异常。 |
| const [SVG_WRONG_TYPE_ERR](../../com.aspose.html.dom.svg/svgexception/svg_wrong_type_err/) | 当向操作传递错误类型的对象时抛出此异常。 |

### 另请参见

* class [PlatformException](../../com.aspose.html/platformexception/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)
