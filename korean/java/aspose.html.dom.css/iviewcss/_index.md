---
title: "IViewCSS 인터페이스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.css.IViewCSS 인터페이스. IViewCSS 인터페이스는 Window 객체에 대한 확장으로, 요소의 모든 CSS 속성 값에 접근할 수 있게 합니다."
type: docs

url: /ko/java/com.aspose.html.dom.css/iviewcss/
---
## IViewCSS interface

IViewCSS 인터페이스는 요소의 모든 CSS 속성 값을 접근할 수 있게 하는 Window 객체의 확장을 나타냅니다.

주어진 요소의 CSS 스타일은 IViewCSS.GetComputedStyle() 메서드를 사용하여 얻을 수 있습니다.

```java
public interface IViewCSS : IAbstractView
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getComputedStyle](../../com.aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle)(Element) | IViewCSS.getComputedStyle() 메서드는 활성 스타일시트를 적용하고 해당 값이 포함할 수 있는 기본 계산을 해결한 후, 요소의 모든 CSS 속성 값을 포함하는 객체를 반환합니다. |
| [getComputedStyle](../../com.aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle_1)(Element, String) | IViewCSS.getComputedStyle() 메서드는 활성 스타일시트를 적용하고 해당 값이 포함할 수 있는 기본 계산을 해결한 후, 요소의 모든 CSS 속성 값을 포함하는 객체를 반환합니다. |

## 비고

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

참조

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### 또 보기

* interface [IAbstractView](../../com.aspose.html.dom.views/iabstractview/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
