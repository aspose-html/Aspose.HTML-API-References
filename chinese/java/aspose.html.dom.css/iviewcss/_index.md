---
title: "IViewCSS 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.css.IViewCSS 接口。IViewCSS 接口表示对 Window 对象的扩展，提供对元素所有 CSS 属性值的访问。"
type: docs

url: /zh/java/com.aspose.html.dom.css/iviewcss/
---
## IViewCSS interface

IViewCSS 接口表示对 Window 对象的扩展，提供对元素所有 CSS 属性值的访问。

可以使用 IViewCSS.GetComputedStyle() 方法获取给定元素的 CSS 样式。

```java
public interface IViewCSS : IAbstractView
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [getComputedStyle](../../com.aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle)(Element) | IViewCSS.getComputedStyle() 方法返回一个对象，其中包含元素所有 CSS 属性的值，该值在应用活动样式表并解析可能的基本计算后得到。 |
| [getComputedStyle](../../com.aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle_1)(Element, String) | IViewCSS.getComputedStyle() 方法返回一个对象，其中包含元素所有 CSS 属性的值，该值在应用活动样式表并解析可能的基本计算后得到。 |

## 备注

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参考

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### 另请参见

* interface [IAbstractView](../../com.aspose.html.dom.views/iabstractview/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
