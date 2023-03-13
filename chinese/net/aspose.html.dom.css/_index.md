---
title: Aspose.Html.Dom.Css
second_title: Aspose.HTML for .NET API 参考
description: 的 Aspose.Html.Dom.CSS命名空间用于所有与CSS相关的操作 它集中在CSS官方文档指定的CSS属性名称值对 
type: docs
weight: 70
url: /zh/net/aspose.html.dom.css/
---
的 **Aspose.Html.Dom.CSS**命名空间用于所有与CSS相关的操作。 它集中在CSS官方文档指定的CSS属性名称-值对 。

## 课程

| 班级 | 描述 |
| --- | --- |
| [Counter](./counter/) | Counter 接口用于表示任何计数器或计数器函数值。此接口反映了底层样式属性中的值。 |
| [CSSPrimitiveValue](./cssprimitivevalue/) | CSSPrimitiveValue 接口表示单个 CSS 值。此接口可用于确定当前在块中设置的特定样式属性的值，或在块中显式设置特定样式属性。该接口的实例可以从 CSSStyleDeclaration 接口的 getPropertyCSSValue 方法获得。 CSSPrimitiveValue 对象仅出现在 CSS 属性的上下文中。 |
| [CSSValue](./cssvalue/) | 表示简单值或复杂值。 CSSValue 对象仅出现在 CSS 属性的上下文中。 |
| [CSSValueList](./cssvaluelist/) | CSSValueList 接口提供了 CSS 值有序集合的抽象。 |
| [Rect](./rect/) | Rect 接口用于表示任何矩形值。该接口反映了底层样式属性中的值。因此，对 CSSPrimitiveValue 对象所做的修改会修改样式属性。 |
| [RGBColor](./rgbcolor/) | RGBColor 接口用于表示任何 RGB 颜色值。该接口反映了底层样式属性中的值。因此，对 CSSPrimitiveValue 对象所做的修改会修改样式属性。 |
## 接口

| 界面 | 描述 |
| --- | --- |
| [ICSS2Properties](./icss2properties/) | 在特定 HTML 元素的上下文中为 CSS2 属性设置值操作提供接口 |
| [ICSSCharsetRule](./icsscharsetrule/) | CSSCharsetRule 接口表示 CSS 样式表中的@charset 规则。 编码属性的值不影响 DOM 对象中文本数据的编码；此编码始终为 UTF-16。加载样式表后，编码属性的值是在@charset 规则中找到的值。如果原始文档中没有@charset，则不会创建 CSSCharsetRule。 编码属性的值也可以用作样式表序列化所用编码的提示。 |
| [ICSSCounterStyleRule](./icsscounterstylerule/) | @counter-style 规则允许作者定义自定义计数器样式。 |
| [ICSSFontFaceRule](./icssfontfacerule/) | CSSFontFaceRule 接口表示 CSS 样式表中的@font-face 规则。 @font-face 规则用于保存一组字体描述。 |
| [ICSSImportRule](./icssimportrule/) | CSSImportRule 接口表示 CSS 样式表中的@import 规则。 @import 规则用于从其他样式表导入样式规则。 |
| [ICSSKeyframeRule](./icsskeyframerule/) | CSSKeyframeRule 接口表示单个键的样式规则。 |
| [ICSSKeyframesRule](./icsskeyframesrule/) | CSSKeyframesRule 接口表示单个动画的一组完整关键帧 |
| [ICSSMarginRule](./icssmarginrule/) | CSSMarginRule 接口表示规则的边距。 |
| [ICSSMediaRule](./icssmediarule/) | CSSMediaRule 接口表示 CSS 样式表中的@media 规则。 @media 规则可用于分隔特定媒体类型的样式规则。 |
| [ICSSPageRule](./icsspagerule/) | CSSPageRule 接口表示 CSS 样式表中的@page 规则。 @page 规则用于为分页媒体指定页面框的尺寸、方向、边距等。 |
| [ICSSRule](./icssrule/) | CSSRule 接口是任何类型的CSS 语句的抽象基接口。这包括规则集和规则。期望实现保留 CSS 样式表中指定的所有规则，即使解析器无法识别该规则。无法识别的规则使用!:ICSSUnknownRule接口. |
| [ICSSRuleList](./icssrulelist/) | CSSRuleList 接口提供了 CSS 规则有序集合的抽象。 |
| [ICSSStyleDeclaration](./icssstyledeclaration/) | CSSStyleDeclaration 接口表示单个 CSS 声明块。此接口可用于确定当前在块中设置的样式属性或在块中显式设置样式属性。 |
| [ICSSStyleRule](./icssstylerule/) | CSSStyleRule 接口表示 CSS 样式表中的单个规则集。 |
| [ICSSStyleSheet](./icssstylesheet/) | CSSStyleSheet接口是一个具体的接口，用于表示CSS样式表，即内容类型为“text/css”的样式表。 |
| [ICSSUnknownRule](./icssunknownrule/) | CSSUnknownRule 接口表示此用户代理不支持的规则。 |
| [ICSSValueList](./icssvaluelist/) | 该接口提供了 CSS 值有序集合的抽象。 |
| [IDocumentCSS](./idocumentcss/) | 此接口表示具有 CSS 视图的文档。 |
| [IDocumentStyle](./idocumentstyle/) | DocumentStyle 接口提供了一种机制，通过该机制可以检索嵌入在文档中的样式表。预期是可以通过对 Document 接口的实例使用特定于绑定的转换方法来获得 DocumentStyle 接口的实例。 |
| [IElementCSSInlineStyle](./ielementcssinlinestyle/) | 附加到元素的内联样式信息通过 style 属性公开。这表示 HTML 元素（或以相同方式使用 STYLE 属性的其他模式或 DTD 中的元素）的 STYLE 属性的内容。 |
| [ILinkStyle](./ilinkstyle/) | LinkStyle 接口提供了一种机制，通过该机制可以从负责将样式表链接到文档的节点中检索样式表。 LinkStyle 接口的实例可以在链接节点的实例（DOM 级别 2 中的 HTMLLinkElement、HTMLStyleElement 或 ProcessingInstruction）上使用特定于绑定的转换方法来获得。 |
| [IMediaList](./imedialist/) | MediaList 接口提供了媒体有序集合的抽象，但没有定义或限制该集合的实现方式。空列表与包含介质“all”的列表相同。 |
| [IStyleSheet](./istylesheet/) | StyleSheet 接口是任何类型样式表的抽象基础接口。它表示与结构化文档关联的单个样式表。 |
| [IStyleSheetList](./istylesheetlist/) | StyleSheetList 接口提供了样式表有序集合的抽象。 |
| [IViewCSS](./iviewcss/) | 此接口代表一个 CSS 视图。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [CSSEngineMode](./cssenginemode/) | 指定 CSSEngine 模式 |


