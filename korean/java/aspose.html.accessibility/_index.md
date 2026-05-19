---
title: "com.aspose.html.accessibility"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.accessibility 패키지는 웹 접근성과 관련된 모든 조작을 위해 제공됩니다. 국제 표준인 W3C 웹 접근성 이니셔티브를 준수합니다."
type: docs

url: /ko/java/com.aspose.html.accessibility/
---
The **com.aspose.html.accessibility** 패키지는 모든 웹 접근성 관련 조작을 위해 제공됩니다. 국제 표준인 W3C 웹 접근성 이니셔티브를 준수합니다.

## 클래스

| 클래스 | 설명 |
| --- | --- |
| [AccessibilityRules](./accessibilityrules/) | Web Content Accessibility Guidelines (WCAG) 2 요구사항(성공 기준) 및 기술에 대한 빠른 참고 자료입니다. 원칙 목록을 포함합니다. https://www.w3.org/WAI/WCAG21/quickref/ |
| [AccessibilityValidator](./accessibilityvalidator/) | Validator 클래스는 빠른 참고 규칙을 처리합니다. 접근성을 확인하는 Validate 메서드를 포함합니다. |
| [Criterion](./criterion/) | 각 권고안에 대해 검증 가능한 성공 기준이 제공되어, 준수 테스트가 필요한 영역에 WCAG 2.0을 적용할 수 있습니다. https://www.w3.org/WAI/WCAG21/Understanding/understanding-techniques |
| [Guideline](./guideline/) | Guidelines - 원칙 다음 단계입니다. 테스트 가능하지는 않지만, 프레임워크와 일반 목표를 개요하여 저자가 성공 기준을 이해하고 기술을 더 잘 적용하도록 돕습니다. Guidelines는 RuleDirectory{Criterion} 유형의 수용 기준 목록입니다. |
| [Principle](./principle/) | Accessibility Principle - 웹 접근성의 기반을 제공하는 최고 수준으로, RuleCollection{Guideline} 유형의 Guidelines 목록을 포함합니다. 이 객체는 어셈블리 외부에서 생성될 수 없습니다. https://www.w3.org/WAI/fundamentals/accessibility-principles/ |
| [Rule](./rule/) | Rule의 특성을 정의하고 IRule 인터페이스를 구현하는 추상 클래스입니다. |
| [Target](./target/) | 클래스는 오류가 발견된 HTML 또는 CSS 요소의 항목을 포함합니다. |
| [ValidationBuilder](./validationbuilder/) | ValidationBuilder 클래스는 구성 단계에 대한 구체적인 구현을 제공합니다. ValidationSettings 클래스에 대한 메서드와 설정을 정의합니다. |
| [WebAccessibility](./webaccessibility/) | Web Content Accessibility Guidelines (WCAG) 2 요구사항(성공 기준) 및 기술에 대한 객체입니다. https://www.w3.org/WAI/WCAG21/quickref/ |
## 인터페이스

| 인터페이스 | 설명 |
| --- | --- |
| [IError](./ierror/) | 인터페이스는 검증 오류를 설명합니다. |
| [IRule](./irule/) | 규칙의 주요 속성을 설명하는 인터페이스입니다. |
| [ITechniqueResult](./itechniqueresult/) | 기술 검증 결과를 설명합니다. |
## 열거형

| 열거형 | 설명 |
| --- | --- |
| [TargetTypes](./targettypes/) | 오류를 포함하는 HTML 문서에서 생성된 객체 유형의 열거형입니다. |
