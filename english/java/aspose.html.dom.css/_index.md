---
title: com.aspose.html.dom.css
second_title: Aspose.HTML for Java API Reference
description: Provides interfaces for DOM Level 2 Style Specification. Cascading Style Sheets CSS is a style sheet language that allows authors and users to attach style e.g. fonts and spacing to structured documents e.g. HTML documents and XML applications. It supports media-specific style sheets so that authors may tailor the presentation of their documents to visual browsers aural devices printers braille devices handheld devices etc. It also supports content positioning table layout features for internationalization and some properties related to user interface. By separating the presentation style of documents from the content of documents CSS simplifies Web authoring and site maintenance
type: docs
weight: 110
url: /java/com.aspose.html.dom.css/
---
Provides interfaces for DOM Level 2 Style Specification. Cascading Style Sheets (CSS) is a style sheet language that allows authors and users to attach style (e.g., fonts and spacing) to structured documents (e.g., HTML documents and XML applications). It supports media-specific style sheets so that authors may tailor the presentation of their documents to visual browsers, aural devices, printers, braille devices, handheld devices, etc. It also supports content positioning, table layout, features for internationalization and some properties related to user interface. By separating the presentation style of documents from the content of documents, CSS simplifies Web authoring and site maintenance.

## Classes

| Class | Description |
| --- | --- |
| [Counter](./counter/) | The Counter interface is used to represent any counter or counters function value. This interface reflects the values in the underlying style property. |
| [CSSPrimitiveValue](./cssprimitivevalue/) | The CSSPrimitiveValue interface derives from the CSSValue interface and represents the current computed value of a CSS property. |
| [CSSValue](./cssvalue/) | Represents a simple or a complex value. A CSSValue object only occurs in a context of a CSS property. |
| [CSSValueList](./cssvaluelist/) | The CSSValueList interface provides the abstraction of an ordered collection of CSS values. |
| [Rect](./rect/) | The Rect interface is used to represent any rect value. This interface reflects the values in the underlying style property. Hence, modifications made to the [`CSSPrimitiveValue`](../com.aspose.html.dom.css/cssprimitivevalue/) objects modify the style property. |
| [RGBColor](./rgbcolor/) | The RGBColor interface is used to represent any RGB color value. This interface reflects the values in the underlying style property. Hence, modifications made to the CSSPrimitiveValue objects modify the style property. |
## Interfaces

| Interface | Description |
| --- | --- |
| [ICSS2Properties](./icss2properties/) | The CSS2Properties interface represents a convenience mechanism for retrieving and setting properties within a [`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/). The attributes of this interface correspond to all the properties specified in CSS2. Getting an attribute of this interface is equivalent to calling the getPropertyValue method of the [`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/) interface. Setting an attribute of this interface is equivalent to calling the setProperty method of the [`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/) interface. |
| [ICSSCharsetRule](./icsscharsetrule/) | The CSSCharsetRule interface represents a @charset rule in a CSS style sheet. The value of the encoding attribute does not affect the encoding of text data in the DOM objects; this encoding is always UTF-16. After a stylesheet is loaded, the value of the encoding attribute is the value found in the @charset rule. If there was no @charset in the original document, then no CSSCharsetRule is created. The value of the encoding attribute may also be used as a hint for the encoding used on serialization of the style sheet. |
| [ICSSCounterStyleRule](./icsscounterstylerule/) | The CSSCounterStyleRule interface represents an @counter-style at-rule that allows authors to define a custom counter style. |
| [ICSSFontFaceRule](./icssfontfacerule/) | The CSSFontFaceRule interface represents a @font-face rule in a CSS style sheet. The @font-face rule is used to hold a set of font descriptions. |
| [ICSSImportRule](./icssimportrule/) | The CSSImportRule interface represents a @import rule within a CSS style sheet. The @import rule is used to import style rules from other style sheets. |
| [ICSSKeyframeRule](./icsskeyframerule/) | The [`CSSKeyframeRule`](../com.aspose.html.dom.css/icsskeyframerule/) interface describes an object representing a set of styles for a given keyframe. It corresponds to the contents of a single keyframe of a @keyframes at-rule. |
| [ICSSKeyframesRule](./icsskeyframesrule/) | The name property of the CSSKeyframeRule interface gets and sets the name of the animation as used by the animation-name property. |
| [ICSSMarginRule](./icssmarginrule/) | The CSSMarginRule interface represents a margin at-rule (e.g. @top-left) in an @page at-rule. |
| [ICSSMediaRule](./icssmediarule/) | The CSSMediaRule interface represents a @media rule in a CSS style sheet. A @media rule can be used to delimit style rules for specific media types. |
| [ICSSPageRule](./icsspagerule/) | The CSSPageRule interface represents a @page rule within a CSS style sheet. The @page rule is used to specify the dimensions, orientation, margins, etc. of a page box for paged media. |
| [ICSSRule](./icssrule/) | The CSSRule interface is the abstract base interface for any type of CSS statement. This includes both rule sets and at-rules. An implementation is expected to preserve all rules specified in a CSS style sheet, even if the rule is not recognized by the parser. Unrecognized rules are represented using the interface. |
| [ICSSRuleList](./icssrulelist/) | A CSSRuleList represents an ordered collection of read-only [`CSSRule`](../com.aspose.html.dom.css/icssrule/) objects. |
| [ICSSStyleDeclaration](./icssstyledeclaration/) | The CSSStyleDeclaration interface represents an object that is a CSS declaration block, and exposes style information and various style-related methods and properties. |
| [ICSSStyleRule](./icssstylerule/) | The CSSStyleRule interface represents a single CSS style rule. The selectorText attribute, on getting, must return the result of serializing the associated group of selectors |
| [ICSSStyleSheet](./icssstylesheet/) | The CSSStyleSheet interface represents a single CSS stylesheet, and lets you inspect and modify the list of rules contained in the stylesheet. It inherits properties and methods from its parent, [`IStyleSheet`](../com.aspose.html.dom.css/istylesheet/). |
| [ICSSUnknownRule](./icssunknownrule/) | The CSSUnknownRule interface represents an at-rule not supported by this user agent. |
| [ICSSValueList](./icssvaluelist/) | The CSSValueList interface derives from the [`CSSValue`](../com.aspose.html.dom.css/cssvalue/) interface and provides the abstraction of an ordered collection of CSS values. |
| [IDocumentCSS](./idocumentcss/) | This interface represents a document with a CSS view. |
| [IDocumentStyle](./idocumentstyle/) | The DocumentStyle interface provides a mechanism by which the style sheets embedded in a document can be retrieved. The expectation is that an instance of the DocumentStyle interface can be obtained by using binding-specific casting methods on an instance of the Document interface. |
| [IElementCSSInlineStyle](./ielementcssinlinestyle/) | Inline style information attached to elements is exposed through the style attribute. This represents the contents of the STYLE attribute for HTML elements (or elements in other schemas or DTDs which use the STYLE attribute in the same way). The expectation is that an instance of the ElementCSSInlineStyle interface can be obtained by using binding-specific casting methods on an instance of the Element interface when the element supports inline CSS style informations. |
| [ILinkStyle](./ilinkstyle/) | The LinkStyle interface provides a mechanism by which a style sheet can be retrieved from the node responsible for linking it into a document. An instance of the LinkStyle interface can be obtained using binding-specific casting methods on an instance of a linking node (HTMLLinkElement, |
| [IMediaList](./imedialist/) | The MediaList interface provides the abstraction of an ordered collection of media, without defining or constraining how this collection is implemented. An empty list is the same as a list that contains the medium "all". |
| [IStyleSheet](./istylesheet/) | The StyleSheet interface is the abstract base interface for any type of style sheet. It represents a single style sheet associated with a structured document. In HTML, the StyleSheet interface represents either an external style sheet, included via the HTML LINK element, or an inline STYLE element. In XML, this interface represents an external style sheet, included via a style sheet processing instruction. CSS style sheets will further implement the more specialized [`CSSStyleSheet`](../com.aspose.html.dom.css/icssstylesheet/) interface. |
| [IStyleSheetList](./istylesheetlist/) | The StyleSheetList interface represents a list of [`CSSStyleSheet`](../com.aspose.html.dom.css/icssstylesheet/) objects. An instance of this object can be returned by [`Document.styleSheets`](../com.aspose.html.dom/document/stylesheets/). |
| [IViewCSS](./iviewcss/) | The IViewCSS interface represents an extension to the Window object that give an access to the values of all CSS properties of an element. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [CSSEngineMode](./cssenginemode/) | Specifies CSSEngine mode. Values have the following meaning: |
