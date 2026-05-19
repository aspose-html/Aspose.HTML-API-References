---
title: "ValidationBuilder 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.accessibility.ValidationBuilder 클래스. ValidationBuilder 클래스는 구성 단계에 대한 구체적인 구현을 제공합니다. ValidationSettings 클래스에 대한 메서드와 설정을 정의합니다."
type: docs

url: /ko/java/com.aspose.html.accessibility/validationbuilder/
---
## ValidationBuilder class

ValidationBuilder 클래스는 구성 단계에 대한 구체적인 구현을 제공합니다. ValidationSettings 클래스에 대한 메서드와 설정을 정의합니다.

```java
public class ValidationBuilder
```

## 속성

| 이름 | 설명 |
| --- | --- |
| static [getAll](../../com.aspose.html.accessibility/validationbuilder/all/) 모든 레벨 및 모든 기술 설정을 포함합니다. |
| static [getDefault](../../com.aspose.html.accessibility/validationbuilder/default/) 기본 설정: 일반 기술만 사용되며 최저 기준 레벨에 해당합니다. |
| static [getNone](../../com.aspose.html.accessibility/validationbuilder/none/) 설정 없음 - 매개변수가 지정되지 않았습니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [allLevels](../../com.aspose.html.accessibility/validationbuilder/alllevels/)() | 모든 기준 레벨을 설정하는 메서드. 그리고 문서가 세 가지 레벨 모두의 기준에 따라 검사될 것임을 나타냅니다. |
| [allTechnologies](../../com.aspose.html.accessibility/validationbuilder/alltechnologies/)() | 테스트 기준에 모든 기술을 설정하는 메서드 |
| [setHTMLTags](../../com.aspose.html.accessibility/validationbuilder/sethtmltags/)(params String[]) | 검사할 HTML 태그 목록. 태그가 명시적으로 지정되지 않으면, 태그 배열이 비어 있으며 모든 태그를 대상으로 검사가 진행됩니다. |
| [useCSS](../../com.aspose.html.accessibility/validationbuilder/usecss/)() | 규칙 집합에 CSS 기술을 포함하는 메서드 |
| [useFailures](../../com.aspose.html.accessibility/validationbuilder/usefailures/)() | 규칙 집합에 실패 항목을 포함하는 메서드 |
| [useGeneral](../../com.aspose.html.accessibility/validationbuilder/usegeneral/)() | 규칙 집합에 일반 기술을 포함하는 메서드 |
| [useHighestLevel](../../com.aspose.html.accessibility/validationbuilder/usehighestlevel/)() | 규칙에서 기준의 최고 레벨 AAA 사용 |
| [useHTML](../../com.aspose.html.accessibility/validationbuilder/usehtml/)() | 규칙 집합에 HTML 기술을 포함하는 메서드 |
| [useLowestLevel](../../com.aspose.html.accessibility/validationbuilder/uselowestlevel/)() | 규칙에서 기준의 최저 레벨 A 사용 |
| [useMiddleLevel](../../com.aspose.html.accessibility/validationbuilder/usemiddlelevel/)() | 규칙에서 기준의 중간 레벨 AA 사용 |
| [useScript](../../com.aspose.html.accessibility/validationbuilder/usescript/)() | 규칙 집합에 ClientSideScript 기술을 포함하는 메서드 |

### 또 보기

* package [com.aspose.html.accessibility](../../com.aspose.html.accessibility/)
* package [Aspose.HTML](../../)
