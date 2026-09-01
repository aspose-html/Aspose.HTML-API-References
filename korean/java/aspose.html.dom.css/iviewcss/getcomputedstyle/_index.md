---
title: "IViewCSS.GetComputedStyle"
second_title: "Java용 Aspose.HTML API 참조"
description: "IViewCSS 메서드. IViewCSS.getComputedStyle 메서드는 활성 스타일시트를 적용하고 해당 값에 대한 기본 계산을 해결한 후 요소의 모든 CSS 속성 값을 포함하는 객체를 반환합니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/iviewcss/getcomputedstyle/
---
## GetComputedStyle(Element) {#getcomputedstyle}

IViewCSS.getComputedStyle() 메서드는 활성 스타일시트를 적용하고 해당 값이 포함할 수 있는 기본 계산을 해결한 후, 요소의 모든 CSS 속성 값을 포함하는 객체를 반환합니다.

개별 CSS 속성 값은 객체가 제공하는 API를 통해 또는 CSS 속성 이름으로 인덱싱하여 접근할 수 있습니다.

```java
public ICSSStyleDeclaration GetComputedStyle(Element element)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| element | Element | 계산된 스타일을 가져올 [`Element`](../../../com.aspose.html.dom/element/)입니다. 이 매개변수는 null일 수 없습니다. |

### 반환 값

반환된 스타일은 라이브 [`CSSStyleDeclaration`](../../icssstyledeclaration/) 객체이며, 요소의 스타일이 변경될 때 자동으로 업데이트됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| TypeError | 전달된 객체가 Element가 아니거나 pseudoElt가 유효한 의사 요소 선택자가 아닌 경우. |

## 비고

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

참조

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### 또 보기

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

---

## GetComputedStyle(Element, String) {#getcomputedstyle_1}

IViewCSS.getComputedStyle() 메서드는 활성 스타일시트를 적용하고 해당 값이 포함할 수 있는 기본 계산을 해결한 후, 요소의 모든 CSS 속성 값을 포함하는 객체를 반환합니다.

개별 CSS 속성 값은 객체가 제공하는 API를 통해 또는 CSS 속성 이름으로 인덱싱하여 접근할 수 있습니다.

```java
public ICSSStyleDeclaration GetComputedStyle(Element element, String pseudoElement)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| element | Element | 계산된 스타일을 가져올 [`Element`](../../../com.aspose.html.dom/element/)입니다. 이 매개변수는 null일 수 없습니다. |
| pseudoElement | String | 매치할 의사 요소를 지정하는 문자열입니다. 실제 요소의 경우 생략(또는 null)합니다. |

### 반환 값

반환된 스타일은 라이브 [`CSSStyleDeclaration`](../../icssstyledeclaration/) 객체이며, 요소의 스타일이 변경될 때 자동으로 업데이트됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| TypeError | 전달된 객체가 Element가 아니거나 pseudoElt가 유효한 의사 요소 선택자가 아닌 경우. |

## 비고

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

참조

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### 또 보기

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
