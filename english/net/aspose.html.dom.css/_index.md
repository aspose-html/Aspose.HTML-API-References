---
title: Aspose.Html.Dom.Css
second_title: Aspose.HTML for .NET API Reference
description: The Aspose.Html.Dom.Css namespace is for all CSS related manipulations. It concentrates around CSS property name - value pairs specified by CSS official documents
type: docs
weight: 110
url: /net/aspose.html.dom.css/
---
The **Aspose.Html.Dom.Css** namespace is for all CSS related manipulations. It concentrates around CSS property name - value pairs specified by CSS official documents.

## Classes

| Class | Description |
| --- | --- |
| [Counter](./counter/) | The Counter interface is used to represent any counter or counters function value. This interface reflects the values in the underlying style property. |
| [CSSPrimitiveValue](./cssprimitivevalue/) | The CSSPrimitiveValue interface represents a single CSS value. This interface may be used to determine the value of a specific style property currently set in a block or to set a specific style property explicitly within the block. An instance of this interface might be obtained from the getPropertyCSSValue method of the CSSStyleDeclaration interface. A CSSPrimitiveValue object only occurs in a context of a CSS property. |
| [CSSValue](./cssvalue/) | Represents a simple or a complex value. A CSSValue object only occurs in a context of a CSS property. |
| [CSSValueList](./cssvaluelist/) | The CSSValueList interface provides the abstraction of an ordered collection of CSS values. |
| [Rect](./rect/) | The Rect interface is used to represent any rect value. This interface reflects the values in the underlying style property. Hence, modifications made to the CSSPrimitiveValue objects modify the style property. |
| [RGBColor](./rgbcolor/) | The RGBColor interface is used to represent any RGB color value. This interface reflects the values in the underlying style property. Hence, modifications made to the CSSPrimitiveValue objects modify the style property. |
## Interfaces

| Interface | Description |
| --- | --- |
| [ICSS2Properties](./icss2properties/) | Provides interface for CSS2 properties set values manipulation in the context of certain HTML element |
| [ICSSCharsetRule](./icsscharsetrule/) | The CSSCharsetRule interface represents a @charset rule in a CSS style sheet. The value of the encoding attribute does not affect the encoding of text data in the DOM objects; this encoding is always UTF-16. After a stylesheet is loaded, the value of the encoding attribute is the value found in the @charset rule. If there was no @charset in the original document, then no CSSCharsetRule is created. The value of the encoding attribute may also be used as a hint for the encoding used on serialization of the style sheet. |
| [ICSSCounterStyleRule](./icsscounterstylerule/) | The @counter-style rule allows authors to define a custom counter style. |
| [ICSSFontFaceRule](./icssfontfacerule/) | The CSSFontFaceRule interface represents a @font-face rule in a CSS style sheet. The @font-face rule is used to hold a set of font descriptions. |
| [ICSSImportRule](./icssimportrule/) | The CSSImportRule interface represents a @import rule within a CSS style sheet. The @import rule is used to import style rules from other style sheets. |
| [ICSSKeyframeRule](./icsskeyframerule/) | The CSSKeyframeRule interface represents the style rule for a single key. |
| [ICSSKeyframesRule](./icsskeyframesrule/) | The CSSKeyframesRule interface represents a complete set of keyframes for a single animation |
| [ICSSMarginRule](./icssmarginrule/) | The CSSMarginRule interface represents a margin at-rule. |
| [ICSSMediaRule](./icssmediarule/) | The CSSMediaRule interface represents a @media rule in a CSS style sheet. A @media rule can be used to delimit style rules for specific media types. |
| [ICSSPageRule](./icsspagerule/) | The CSSPageRule interface represents a @page rule within a CSS style sheet. The @page rule is used to specify the dimensions, orientation, margins, etc. of a page box for paged media. |
| [ICSSRule](./icssrule/) | The CSSRule interface is the abstract base interface for any type of CSS statement. This includes both rule sets and at-rules. An implementation is expected to preserve all rules specified in a CSS style sheet, even if the rule is not recognized by the parser. Unrecognized rules are represented using the ICSSUnknownRule interface. |
| [ICSSRuleList](./icssrulelist/) | The CSSRuleList interface provides the abstraction of an ordered collection of CSS rules. |
| [ICSSStyleDeclaration](./icssstyledeclaration/) | The CSSStyleDeclaration interface represents a single CSS declaration block. This interface may be used to determine the style properties currently set in a block or to set style properties explicitly within the block. |
| [ICSSStyleRule](./icssstylerule/) | The CSSStyleRule interface represents a single rule set in a CSS style sheet. |
| [ICSSStyleSheet](./icssstylesheet/) | The CSSStyleSheet interface is a concrete interface used to represent a CSS style sheet i.e., a style sheet whose content type is "text/css". |
| [ICSSUnknownRule](./icssunknownrule/) | The CSSUnknownRule interface represents an at-rule not supported by this user agent. |
| [ICSSValueList](./icssvaluelist/) | The interface provides the abstraction of an ordered collection of CSS values. |
| [IDocumentCSS](./idocumentcss/) | This interface represents a document with a CSS view. |
| [IDocumentStyle](./idocumentstyle/) | The DocumentStyle interface provides a mechanism by which the style sheets embedded in a document can be retrieved. The expectation is that an instance of the DocumentStyle interface can be obtained by using binding-specific casting methods on an instance of the Document interface. |
| [IElementCSSInlineStyle](./ielementcssinlinestyle/) | Inline style information attached to elements is exposed through the style attribute. This represents the contents of the STYLE attribute for HTML elements (or elements in other schemas or DTDs which use the STYLE attribute in the same way). |
| [ILinkStyle](./ilinkstyle/) | The LinkStyle interface provides a mechanism by which a style sheet can be retrieved from the node responsible for linking it into a document. An instance of the LinkStyle interface can be obtained using binding-specific casting methods on an instance of a linking node (HTMLLinkElement, HTMLStyleElement or ProcessingInstruction in DOM Level 2). |
| [IMediaList](./imedialist/) | The MediaList interface provides the abstraction of an ordered collection of media, without defining or constraining how this collection is implemented. An empty list is the same as a list that contains the medium "all". |
| [IStyleSheet](./istylesheet/) | The StyleSheet interface is the abstract base interface for any type of style sheet. It represents a single style sheet associated with a structured document. |
| [IStyleSheetList](./istylesheetlist/) | The StyleSheetList interface provides the abstraction of an ordered collection of style sheets. |
| [IViewCSS](./iviewcss/) | This interface represents a CSS view. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [CSSEngineMode](./cssenginemode/) | Specifies CSSEngine mode |
