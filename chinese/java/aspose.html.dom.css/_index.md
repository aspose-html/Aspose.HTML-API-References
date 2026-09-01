---
title: "com.aspose.html.dom.css"
second_title: "Aspose.HTML for Java API 参考"
description: "提供 DOM Level 2 样式规范的接口。层叠样式表（CSS）是一种样式表语言，允许作者和用户将样式（例如字体和间距）附加到结构化文档（例如 HTML 文档和 XML 应用程序）。它支持针对特定媒体的样式表，使作者能够为可视浏览器、听觉设备、打印机、盲文设备、手持设备等定制文档的呈现。它还支持内容定位、表格布局、国际化以及一些与用户界面相关的属性。通过将文档的呈现样式与内容分离，CSS 简化了 Web 编写和站点维护。"
type: docs

url: /zh/java/com.aspose.html.dom.css/
---
提供 DOM Level 2 样式规范的接口。层叠样式表（CSS）是一种样式表语言，允许作者和用户将样式（例如字体和间距）附加到结构化文档（例如 HTML 文档和 XML 应用程序）。它支持特定媒体的样式表，使作者能够针对可视浏览器、听觉设备、打印机、盲文设备、手持设备等定制文档的呈现。它还支持内容定位、表格布局、国际化特性以及一些与用户界面相关的属性。通过将文档的呈现样式与内容分离，CSS 简化了 Web 编写和站点维护。

## 类

| 类 | 描述 |
| --- | --- |
| [Counter](./counter/) | Counter 接口用于表示任何计数器或 counters 函数的值。该接口反映底层样式属性中的值。 |
| [CSSPrimitiveValue](./cssprimitivevalue/) | CSSPrimitiveValue 接口继承自 CSSValue 接口，表示 CSS 属性的当前计算值。 |
| [CSSValue](./cssvalue/) | 表示一个简单或复合值。CSSValue 对象仅出现在 CSS 属性的上下文中。 |
| [CSSValueList](./cssvaluelist/) | CSSValueList 接口提供 CSS 值有序集合的抽象。 |
| [Rect](./rect/) | Rect 接口用于表示任何 rect 值。该接口反映底层样式属性中的值。因此，对 [`CSSPrimitiveValue`](../com.aspose.html.dom.css/cssprimitivevalue/) 对象所做的修改会修改样式属性。 |
| [RGBColor](./rgbcolor/) | RGBColor 接口用于表示任何 RGB 颜色值。该接口反映底层样式属性中的值。因此，对 CSSPrimitiveValue 对象所做的修改会修改样式属性。 |
## 接口

| 接口 | 描述 |
| --- | --- |
| [ICSS2Properties](./icss2properties/) | CSS2Properties 接口提供了一种便捷机制，用于在 [`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/) 中检索和设置属性。该接口的属性对应于 CSS2 中指定的所有属性。获取该接口的属性等同于调用 [`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/) 接口的 getPropertyValue 方法。设置该接口的属性等同于调用 [`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/) 接口的 setProperty 方法。 |
| [ICSSCharsetRule](./icsscharsetrule/) | CSSCharsetRule 接口表示 CSS 样式表中的 @charset 规则。encoding 属性的值不影响 DOM 对象中文本数据的编码；该编码始终为 UTF-16。样式表加载后，encoding 属性的值即为 @charset 规则中找到的值。如果原始文档中没有 @charset，则不会创建 CSSCharsetRule。encoding 属性的值也可用作序列化样式表时所使用编码的提示。 |
| [ICSSCounterStyleRule](./icsscounterstylerule/) | CSSCounterStyleRule 接口表示 @counter-style at-rule，允许作者定义自定义计数器样式。 |
| [ICSSFontFaceRule](./icssfontfacerule/) | CSSFontFaceRule 接口表示 CSS 样式表中的 @font-face 规则。@font-face 规则用于保存一组字体描述。 |
| [ICSSImportRule](./icssimportrule/) | CSSImportRule 接口表示 CSS 样式表中的 @import 规则。@import 规则用于从其他样式表导入样式规则。 |
| [ICSSKeyframeRule](./icsskeyframerule/) | The [`CSSKeyframeRule`](../com.aspose.html.dom.css/icsskeyframerule/) 接口描述了一个表示给定关键帧样式集合的对象。它对应于 @keyframes at-rule 中单个关键帧的内容。 |
| [ICSSKeyframesRule](./icsskeyframesrule/) | CSSKeyframeRule 接口的 name 属性获取和设置动画名称，该名称用于 animation-name 属性。 |
| [ICSSMarginRule](./icssmarginrule/) | CSSMarginRule 接口表示 @page at-rule 中的 margin at-rule（例如 @top-left）。 |
| [ICSSMediaRule](./icssmediarule/) | CSSMediaRule 接口表示 CSS 样式表中的 @media 规则。@media 规则可用于限定特定媒体类型的样式规则。 |
| [ICSSPageRule](./icsspagerule/) | CSSPageRule 接口表示 CSS 样式表中的 @page 规则。@page 规则用于指定分页媒体中页面框的尺寸、方向、边距等。 |
| [ICSSRule](./icssrule/) | CSSRule 接口是任何类型 CSS 语句的抽象基接口。它包括规则集和 at-rule。实现应保留 CSS 样式表中指定的所有规则，即使解析器未识别某些规则。未识别的规则使用该接口表示。 |
| [ICSSRuleList](./icssrulelist/) | CSSRuleList 表示只读 [`CSSRule`](../com.aspose.html.dom.css/icssrule/) 对象的有序集合。 |
| [ICSSStyleDeclaration](./icssstyledeclaration/) | CSSStyleDeclaration 接口表示一个 CSS 声明块对象，并公开样式信息以及各种与样式相关的方法和属性。 |
| [ICSSStyleRule](./icssstylerule/) | CSSStyleRule 接口表示单个 CSS 样式规则。获取 selectorText 属性时，必须返回关联选择器组序列化后的结果。 |
| [ICSSStyleSheet](./icssstylesheet/) | CSSStyleSheet 接口表示单个 CSS 样式表，并允许您检查和修改样式表中包含的规则列表。它继承自其父接口 [`IStyleSheet`](../com.aspose.html.dom.css/istylesheet/)。 |
| [ICSSUnknownRule](./icssunknownrule/) | CSSUnknownRule 接口表示此用户代理不支持的 at-rule。 |
| [ICSSValueList](./icssvaluelist/) | CSSValueList 接口派生自 [`CSSValue`](../com.aspose.html.dom.css/cssvalue/) 接口，并提供 CSS 值有序集合的抽象。 |
| [IDocumentCSS](./idocumentcss/) | 此接口表示具有 CSS 视图的文档。 |
| [IDocumentStyle](./idocumentstyle/) | DocumentStyle 接口提供一种机制，可检索嵌入文档中的样式表。预期可以通过在 Document 接口的实例上使用特定绑定的强制转换方法来获取 DocumentStyle 接口的实例。 |
| [IElementCSSInlineStyle](./ielementcssinlinestyle/) | 附加到元素的内联样式信息通过 style 属性公开。这代表 HTML 元素的 STYLE 属性内容（或在其他模式或 DTD 中以相同方式使用 STYLE 属性的元素）。预期当元素支持内联 CSS 样式信息时，可以通过在 Element 接口的实例上使用特定绑定的强制转换方法来获取 ElementCSSInlineStyle 接口的实例。 |
| [ILinkStyle](./ilinkstyle/) | LinkStyle 接口提供一种机制，可从负责将样式表链接到文档的节点检索该样式表。可以使用在链接节点 (HTMLLinkElement, 上的特定绑定强制转换方法来获取 LinkStyle 接口的实例。 |
| [IMediaList](./imedialist/) | MediaList 接口提供媒体有序集合的抽象，而不定义或限制该集合的实现方式。空列表等同于包含媒体 "all" 的列表。 |
| [IStyleSheet](./istylesheet/) | StyleSheet 接口是任何类型样式表的抽象基接口。它表示与结构化文档关联的单个样式表。在 HTML 中，StyleSheet 接口表示通过 HTML LINK 元素包含的外部样式表或内联 STYLE 元素。在 XML 中，该接口表示通过样式表处理指令包含的外部样式表。CSS 样式表将进一步实现更专用的 [`CSSStyleSheet`](../com.aspose.html.dom.css/icssstylesheet/) 接口。 |
| [IStyleSheetList](./istylesheetlist/) | StyleSheetList 接口表示一组 [`CSSStyleSheet`](../com.aspose.html.dom.css/icssstylesheet/) 对象的列表。可以通过 [`Document.styleSheets`](../com.aspose.html.dom/document/stylesheets/) 获取该对象的实例。 |
| [IViewCSS](./iviewcss/) | IViewCSS 接口表示对 Window 对象的扩展，提供对元素所有 CSS 属性值的访问。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [CSSEngineMode](./cssenginemode/) | 指定 CSSEngine 模式。各值含义如下： |
