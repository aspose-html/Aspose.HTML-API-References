---
title: "com.aspose.html.dom.css"
second_title: "Aspose.HTML for Java API 참조"
description: "DOM Level 2 스타일 사양을 위한 인터페이스를 제공합니다. Cascading Style Sheets(CSS)는 저자와 사용자가 스타일(예: 글꼴 및 간격)을 구조화된 문서(예: HTML 문서 및 XML 애플리케이션)에 적용할 수 있게 하는 스타일시트 언어입니다. 미디어별 스타일시트를 지원하여 저자가 시각 브라우저, 청각 장치, 프린터, 점자 장치, 핸드헬드 장치 등 다양한 매체에 맞게 문서의 표현을 조정할 수 있습니다. 또한 국제화를 위한 콘텐츠 위치 지정, 표 레이아웃 기능 및 사용자 인터페이스와 관련된 일부 속성을 지원합니다. 문서의 프레젠테이션 스타일을 내용과 분리함으로써 CSS는 웹 저작 및 사이트 유지 관리를 단순화합니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/
---
DOM Level 2 스타일 사양을 위한 인터페이스를 제공합니다. Cascading Style Sheets(CSS)는 저자와 사용자가 구조화된 문서(예: HTML 문서 및 XML 애플리케이션)에 스타일(예: 글꼴 및 간격)을 적용할 수 있게 하는 스타일시트 언어입니다. 미디어별 스타일시트를 지원하여 저자가 시각 브라우저, 청각 장치, 프린터, 점자 장치, 핸드헬드 장치 등에 맞게 문서의 표시를 조정할 수 있습니다. 또한 콘텐츠 위치 지정, 테이블 레이아웃, 국제화 기능 및 사용자 인터페이스와 관련된 일부 속성을 지원합니다. 문서의 표현 스타일을 내용과 분리함으로써 CSS는 웹 저작 및 사이트 유지 관리를 단순화합니다.

## 클래스

| 클래스 | 설명 |
| --- | --- |
| [Counter](./counter/) | Counter 인터페이스는 모든 카운터 또는 counters 함수 값을 나타내는 데 사용됩니다. 이 인터페이스는 기본 스타일 속성의 값을 반영합니다. |
| [CSSPrimitiveValue](./cssprimitivevalue/) | CSSPrimitiveValue 인터페이스는 CSSValue 인터페이스를 상속하며 CSS 속성의 현재 계산된 값을 나타냅니다. |
| [CSSValue](./cssvalue/) | 단순값 또는 복합값을 나타냅니다. CSSValue 객체는 CSS 속성의 컨텍스트에서만 발생합니다. |
| [CSSValueList](./cssvaluelist/) | CSSValueList 인터페이스는 CSS 값들의 순서가 있는 컬렉션에 대한 추상화를 제공합니다. |
| [Rect](./rect/) | Rect 인터페이스는 모든 rect 값을 나타내는 데 사용됩니다. 이 인터페이스는 기본 스타일 속성의 값을 반영합니다. 따라서 [`CSSPrimitiveValue`](../com.aspose.html.dom.css/cssprimitivevalue/) 객체에 대한 수정은 스타일 속성을 변경합니다. |
| [RGBColor](./rgbcolor/) | RGBColor 인터페이스는 모든 RGB 색상 값을 나타내는 데 사용됩니다. 이 인터페이스는 기본 스타일 속성의 값을 반영합니다. 따라서 CSSPrimitiveValue 객체에 대한 수정은 스타일 속성을 변경합니다. |
## 인터페이스

| 인터페이스 | 설명 |
| --- | --- |
| [ICSS2Properties](./icss2properties/) | CSS2Properties 인터페이스는 [`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/) 내에서 속성을 검색하고 설정하기 위한 편리한 메커니즘을 제공합니다. 이 인터페이스의 속성은 CSS2에 지정된 모든 속성과 대응합니다. 이 인터페이스의 속성을 가져오는 것은 [`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/) 인터페이스의 getPropertyValue 메서드를 호출하는 것과 동일합니다. 이 인터페이스의 속성을 설정하는 것은 [`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/) 인터페이스의 setProperty 메서드를 호출하는 것과 동일합니다. |
| [ICSSCharsetRule](./icsscharsetrule/) | CSSCharsetRule 인터페이스는 CSS 스타일시트의 @charset 규칙을 나타냅니다. encoding 속성의 값은 DOM 객체의 텍스트 데이터 인코딩에 영향을 주지 않으며, 이 인코딩은 항상 UTF-16입니다. 스타일시트가 로드된 후, encoding 속성의 값은 @charset 규칙에서 찾은 값이 됩니다. 원본 문서에 @charset이 없으면 CSSCharsetRule가 생성되지 않습니다. encoding 속성의 값은 스타일시트 직렬화 시 사용되는 인코딩에 대한 힌트로도 사용될 수 있습니다. |
| [ICSSCounterStyleRule](./icsscounterstylerule/) | CSSCounterStyleRule 인터페이스는 저자가 사용자 정의 카운터 스타일을 정의할 수 있게 하는 @counter-style at-rule을 나타냅니다. |
| [ICSSFontFaceRule](./icssfontfacerule/) | CSSFontFaceRule 인터페이스는 CSS 스타일시트의 @font-face 규칙을 나타냅니다. @font-face 규칙은 일련의 글꼴 설명을 보관하는 데 사용됩니다. |
| [ICSSImportRule](./icssimportrule/) | CSSImportRule 인터페이스는 CSS 스타일시트 내의 @import 규칙을 나타냅니다. @import 규칙은 다른 스타일시트에서 스타일 규칙을 가져오는 데 사용됩니다. |
| [ICSSKeyframeRule](./icsskeyframerule/) | `[`CSSKeyframeRule`](../com.aspose.html.dom.css/icsskeyframerule/)` 인터페이스는 특정 키프레임에 대한 스타일 집합을 나타내는 객체를 설명합니다. 이는 @keyframes at-rule의 단일 키프레임 내용에 해당합니다. |
| [ICSSKeyframesRule](./icsskeyframesrule/) | CSSKeyframeRule 인터페이스의 name 속성은 animation-name 속성에서 사용되는 애니메이션 이름을 가져오고 설정합니다. |
| [ICSSMarginRule](./icssmarginrule/) | CSSMarginRule 인터페이스는 @page at-rule 내의 마진 at-rule(예: @top-left)을 나타냅니다. |
| [ICSSMediaRule](./icssmediarule/) | CSSMediaRule 인터페이스는 CSS 스타일시트의 @media 규칙을 나타냅니다. @media 규칙은 특정 미디어 유형에 대한 스타일 규칙을 구분하는 데 사용할 수 있습니다. |
| [ICSSPageRule](./icsspagerule/) | CSSPageRule 인터페이스는 CSS 스타일시트 내의 @page 규칙을 나타냅니다. @page 규칙은 페이지 매체용 페이지 박스의 크기, 방향, 여백 등을 지정하는 데 사용됩니다. |
| [ICSSRule](./icssrule/) | CSSRule 인터페이스는 모든 유형의 CSS 구문에 대한 추상 기본 인터페이스입니다. 여기에는 규칙 집합과 at-rule이 모두 포함됩니다. 구현은 파서가 인식하지 못하더라도 CSS 스타일시트에 지정된 모든 규칙을 보존해야 합니다. 인식되지 않은 규칙은 이 인터페이스를 사용하여 표현됩니다. |
| [ICSSRuleList](./icssrulelist/) | CSSRuleList는 읽기 전용 [`CSSRule`](../com.aspose.html.dom.css/icssrule/) 객체들의 순서가 있는 컬렉션을 나타냅니다. |
| [ICSSStyleDeclaration](./icssstyledeclaration/) | CSSStyleDeclaration 인터페이스는 CSS 선언 블록인 객체를 나타내며, 스타일 정보와 다양한 스타일 관련 메서드 및 속성을 노출합니다. |
| [ICSSStyleRule](./icssstylerule/) | CSSStyleRule 인터페이스는 단일 CSS 스타일 규칙을 나타냅니다. selectorText 속성을 가져올 때는 관련 선택자 그룹을 직렬화한 결과를 반환해야 합니다. |
| [ICSSStyleSheet](./icssstylesheet/) | CSSStyleSheet 인터페이스는 단일 CSS 스타일시트를 나타내며, 스타일시트에 포함된 규칙 목록을 검사하고 수정할 수 있게 합니다. 이 인터페이스는 상위인 [`IStyleSheet`](../com.aspose.html.dom.css/istylesheet/)의 속성과 메서드를 상속합니다. |
| [ICSSUnknownRule](./icssunknownrule/) | CSSUnknownRule 인터페이스는 이 사용자 에이전트가 지원하지 않는 at-rule을 나타냅니다. |
| [ICSSValueList](./icssvaluelist/) | CSSValueList 인터페이스는 [`CSSValue`](../com.aspose.html.dom.css/cssvalue/) 인터페이스를 상속하며, CSS 값들의 순서가 있는 컬렉션 추상화를 제공합니다. |
| [IDocumentCSS](./idocumentcss/) | 이 인터페이스는 CSS 뷰를 가진 문서를 나타냅니다. |
| [IDocumentStyle](./idocumentstyle/) | DocumentStyle 인터페이스는 문서에 포함된 스타일시트를 검색할 수 있는 메커니즘을 제공합니다. Document 인터페이스의 인스턴스에 바인딩 전용 캐스팅 메서드를 사용하여 DocumentStyle 인터페이스의 인스턴스를 얻을 수 있다고 기대합니다. |
| [IElementCSSInlineStyle](./ielementcssinlinestyle/) | 요소에 부착된 인라인 스타일 정보는 style 속성을 통해 노출됩니다. 이는 HTML 요소의 STYLE 속성 내용(또는 동일한 방식으로 STYLE 속성을 사용하는 다른 스키마나 DTD의 요소)을 나타냅니다. 요소가 인라인 CSS 스타일 정보를 지원할 경우, Element 인터페이스의 인스턴스에 바인딩 전용 캐스팅 메서드를 사용하여 ElementCSSInlineStyle 인터페이스의 인스턴스를 얻을 수 있다고 기대합니다. |
| [ILinkStyle](./ilinkstyle/) | LinkStyle 인터페이스는 스타일시트를 문서에 연결하는 노드로부터 검색할 수 있는 메커니즘을 제공합니다. 연결 노드(HTMLLinkElement 등)의 인스턴스에 바인딩 전용 캐스팅 메서드를 사용하여 LinkStyle 인터페이스의 인스턴스를 얻을 수 있습니다. |
| [IMediaList](./imedialist/) | MediaList 인터페이스는 이 컬렉션이 어떻게 구현되는지를 정의하거나 제한하지 않고, 미디어의 순서가 있는 컬렉션 추상화를 제공합니다. 빈 리스트는 미디어 \"all\"을 포함하는 리스트와 동일합니다. |
| [IStyleSheet](./istylesheet/) | StyleSheet 인터페이스는 모든 종류의 스타일시트에 대한 추상 기본 인터페이스입니다. 이는 구조화된 문서와 연결된 단일 스타일시트를 나타냅니다. HTML에서는 StyleSheet 인터페이스가 HTML LINK 요소를 통해 포함된 외부 스타일시트 또는 인라인 STYLE 요소를 나타냅니다. XML에서는 이 인터페이스가 스타일시트 처리 명령을 통해 포함된 외부 스타일시트를 나타냅니다. CSS 스타일시트는 추가로 보다 특화된 [`CSSStyleSheet`](../com.aspose.html.dom.css/icssstylesheet/) 인터페이스를 구현합니다. |
| [IStyleSheetList](./istylesheetlist/) | StyleSheetList 인터페이스는 [`CSSStyleSheet`](../com.aspose.html.dom.css/icssstylesheet/) 객체들의 리스트를 나타냅니다. 이 객체의 인스턴스는 [`Document.styleSheets`](../com.aspose.html.dom/document/stylesheets/)를 통해 반환될 수 있습니다. |
| [IViewCSS](./iviewcss/) | IViewCSS 인터페이스는 요소의 모든 CSS 속성 값을 접근할 수 있게 하는 Window 객체의 확장을 나타냅니다. |
## 열거형

| 열거형 | 설명 |
| --- | --- |
| [CSSEngineMode](./cssenginemode/) | CSSEngine 모드를 지정합니다. 값은 다음과 같은 의미를 가집니다: |
