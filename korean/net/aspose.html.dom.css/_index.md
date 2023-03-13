---
title: Aspose.Html.Dom.Css
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Css 네임스페이스는 모든 CSS 관련 조작을 위한 것입니다. CSS 속성 이름  CSS 공식 문서에 지정된 값 쌍 에 집중합니다.
type: docs
weight: 70
url: /ko/net/aspose.html.dom.css/
---
**Aspose.Html.Dom.Css** 네임스페이스는 모든 CSS 관련 조작을 위한 것입니다. CSS 속성 이름 - CSS 공식 문서에 지정된 값 쌍 에 집중합니다.

## 클래스

| 수업 | 설명 |
| --- | --- |
| [Counter](./counter/) | 카운터 인터페이스는 카운터 또는 카운터 함수 값을 나타내는 데 사용됩니다. 이 인터페이스는 기본 스타일 속성의 값을 반영합니다. |
| [CSSPrimitiveValue](./cssprimitivevalue/) | CSSPrimitiveValue 인터페이스는 단일 CSS 값을 나타냅니다. 이 인터페이스는 현재 블록에 설정된 특정 스타일 속성의 값을 결정하거나 블록 내에서 명시적으로 특정 스타일 속성을 설정하는 데 사용할 수 있습니다. 이 인터페이스의 인스턴스는 CSSStyleDeclaration 인터페이스의 getPropertyCSSValue 메서드에서 가져올 수 있습니다. CSSPrimitiveValue 개체는 CSS 속성의 컨텍스트에서만 발생합니다. |
| [CSSValue](./cssvalue/) | 단순하거나 복잡한 값을 나타냅니다. CSSValue 개체는 CSS 속성의 컨텍스트에서만 발생합니다. |
| [CSSValueList](./cssvaluelist/) | CSSValueList 인터페이스는 순서가 지정된 CSS 값 모음의 추상화를 제공합니다. |
| [Rect](./rect/) | Rect 인터페이스는 모든 rect 값을 나타내는 데 사용됩니다. 이 인터페이스는 기본 스타일 속성의 값을 반영합니다. 따라서 CSSPrimitiveValue 개체를 수정하면 스타일 속성이 수정됩니다. |
| [RGBColor](./rgbcolor/) | RGBColor 인터페이스는 RGB 색상 값을 나타내는 데 사용됩니다. 이 인터페이스는 기본 스타일 속성의 값을 반영합니다. 따라서 CSSPrimitiveValue 개체를 수정하면 스타일 속성이 수정됩니다. |
## 인터페이스

| 상호 작용 | 설명 |
| --- | --- |
| [ICSS2Properties](./icss2properties/) | 특정 HTML의 컨텍스트에서 CSS2 속성 설정 값 조작을 위한 인터페이스를 제공합니다. |
| [ICSSCharsetRule](./icsscharsetrule/) | CSSCharsetRule 인터페이스는 CSS 스타일 시트의 @charset 규칙을 나타냅니다. 인코딩 속성 값은 DOM 개체의 텍스트 데이터 인코딩에 영향을 주지 않습니다. 이 인코딩은 항상 UTF-16입니다. 스타일시트가 로드된 후 인코딩 속성의 값은 @charset 규칙에서 찾은 값입니다. 원본 문서에 @charset이 없으면 CSSCharsetRule이 생성되지 않습니다. 인코딩 속성의 값은 스타일 시트의 직렬화에 사용되는 인코딩에 대한 힌트로도 사용될 수 있습니다. |
| [ICSSCounterStyleRule](./icsscounterstylerule/) | @counter-style 규칙을 사용하면 작성자가 사용자 지정 카운터 스타일을 정의할 수 있습니다. |
| [ICSSFontFaceRule](./icssfontfacerule/) | CSSFontFaceRule 인터페이스는 CSS 스타일 시트의 @font-face 규칙을 나타냅니다. @font-face 규칙은 일련의 글꼴 설명을 유지하는 데 사용됩니다. |
| [ICSSImportRule](./icssimportrule/) | CSSImportRule 인터페이스는 CSS 스타일 시트 내의 @import 규칙을 나타냅니다. @import 규칙은 다른 스타일 시트에서 스타일 규칙을 가져오는 데 사용됩니다. |
| [ICSSKeyframeRule](./icsskeyframerule/) | CSSKeyframeRule 인터페이스는 단일 키에 대한 스타일 규칙을 나타냅니다. |
| [ICSSKeyframesRule](./icsskeyframesrule/) | CSSKeyframesRule 인터페이스는 단일 animation 에 대한 전체 키프레임 세트를 나타냅니다. |
| [ICSSMarginRule](./icssmarginrule/) | CSSMarginRule 인터페이스는 여백 at-rule을 나타냅니다. |
| [ICSSMediaRule](./icssmediarule/) | CSSMediaRule 인터페이스는 CSS 스타일 시트의 @media 규칙을 나타냅니다. @media 규칙을 사용하여 특정 미디어 유형에 대한 스타일 규칙을 구분할 수 있습니다. |
| [ICSSPageRule](./icsspagerule/) | CSSPageRule 인터페이스는 CSS 스타일 시트 내의 @page 규칙을 나타냅니다. @page 규칙은 페이징된 미디어에 대한 페이지 상자의 크기, 방향, 여백 등을 지정하는 데 사용됩니다. |
| [ICSSRule](./icssrule/) | CSSRule 인터페이스는 모든 유형의 CSS 문에 대한 추상 기본 인터페이스입니다. 여기에는 규칙 집합과 at-규칙이 모두 포함됩니다. 구문 분석기에서 규칙을 인식하지 못하는 경우에도 구현 시 CSS 스타일 시트에 지정된 모든 규칙을 보존해야 합니다. 인식할 수 없는 규칙은!:ICSSUnknownRule 인터페이스. |
| [ICSSRuleList](./icssrulelist/) | CSSRuleList 인터페이스는 순서가 지정된 CSS 규칙 모음의 추상화를 제공합니다. |
| [ICSSStyleDeclaration](./icssstyledeclaration/) | CSSStyleDeclaration 인터페이스는 단일 CSS 선언 블록을 나타냅니다. 이 인터페이스는 현재 블록에 설정된 스타일 속성을 결정하거나 블록 내에서 명시적으로 스타일 속성을 설정하는 데 사용할 수 있습니다. |
| [ICSSStyleRule](./icssstylerule/) | CSSStyleRule 인터페이스는 CSS 스타일 시트의 단일 규칙 집합을 나타냅니다. |
| [ICSSStyleSheet](./icssstylesheet/) | CSSStyleSheet 인터페이스는 콘텐츠 유형이 "text/css"인 스타일 시트인 CSS 스타일 시트를 나타내는 데 사용되는 구체적인 인터페이스입니다. |
| [ICSSUnknownRule](./icssunknownrule/) | CSSUnknownRule 인터페이스는 이 사용자 에이전트에서 지원하지 않는 at-rule을 나타냅니다. |
| [ICSSValueList](./icssvaluelist/) | 인터페이스는 순서가 지정된 CSS 값 모음의 추상화를 제공합니다. |
| [IDocumentCSS](./idocumentcss/) | 이 인터페이스는 CSS 보기가 있는 문서를 나타냅니다. |
| [IDocumentStyle](./idocumentstyle/) | DocumentStyle 인터페이스는 문서에 포함된 스타일 시트를 검색할 수 있는 메커니즘을 제공합니다. Document 인터페이스의 인스턴스에서 바인딩 특정 캐스팅 메서드를 사용하여 DocumentStyle 인터페이스의 인스턴스를 얻을 수 있습니다. |
| [IElementCSSInlineStyle](./ielementcssinlinestyle/) | 요소에 첨부된 인라인 스타일 정보는 style 속성을 통해 노출됩니다. 이는 HTML 요소(또는 동일한 방식으로 STYLE 속성을 사용하는 다른 스키마 또는 DTD의 요소)에 대한 STYLE 속성의 내용을 나타냅니다. |
| [ILinkStyle](./ilinkstyle/) | LinkStyle 인터페이스는 스타일 시트를 문서에 연결하는 역할을 하는 노드에서 검색할 수 있는 메커니즘을 제공합니다. LinkStyle 인터페이스의 인스턴스는 연결 노드의 인스턴스에서 바인딩별 캐스팅 메서드를 사용하여 가져올 수 있습니다(DOM 레벨 2의 HTMLLinkElement, HTMLStyleElement 또는 ProcessingInstruction). |
| [IMediaList](./imedialist/) | MediaList 인터페이스는 이 컬렉션이 구현되는 방법을 정의하거나 제한하지 않고 정렬된 미디어 컬렉션의 추상화를 제공합니다. 빈 목록은 매체 "all"을 포함하는 목록과 동일합니다. |
| [IStyleSheet](./istylesheet/) | StyleSheet 인터페이스는 모든 유형의 스타일 시트에 대한 추상 기본 인터페이스입니다. 구조화된 문서와 연결된 단일 스타일 시트를 나타냅니다. |
| [IStyleSheetList](./istylesheetlist/) | StyleSheetList 인터페이스는 정렬된 스타일 시트 모음의 추상화를 제공합니다. |
| [IViewCSS](./iviewcss/) | 이 인터페이스는 CSS 보기를 나타냅니다. |
## 열거

| 열거 | 설명 |
| --- | --- |
| [CSSEngineMode](./cssenginemode/) | CSSEngine 모드 지정 |


