---
title: Interface ICSSStyleDeclaration
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Css.ICSSStyleDeclaration 상호 작용. CSSStyleDeclaration 인터페이스는 단일 CSS 선언 블록을 나타냅니다. 이 인터페이스는 현재 블록에 설정된 스타일 속성을 결정하거나 블록 내에서 명시적으로 스타일 속성을 설정하는 데 사용할 수 있습니다.
type: docs
weight: 490
url: /ko/net/aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

CSSStyleDeclaration 인터페이스는 단일 CSS 선언 블록을 나타냅니다. 이 인터페이스는 현재 블록에 설정된 스타일 속성을 결정하거나 블록 내에서 명시적으로 스타일 속성을 설정하는 데 사용할 수 있습니다.

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [CSSText](../../aspose.html.dom.css/icssstyledeclaration/csstext/) { get; set; } | 선언 블록의 구문 분석 가능한 텍스트 표현(둘러싸는 중괄호 제외). 이 속성을 설정하면 속성의 제거 또는 추가를 포함하여 선언 블록의 모든 속성이 재설정되고 새 값이 구문 분석됩니다. |
| [Item](../../aspose.html.dom.css/icssstyledeclaration/item/) { get; } | 이 선언 블록에 명시적으로 설정된 속성을 검색하는 데 사용됩니다. 이 방법을 사용하여 검색된 속성의 순서는 속성이 설정된 순서일 필요는 없습니다. 이 메서드는 이 선언 블록의 모든 속성을 반복하는 데 사용할 수 있습니다. |
| [Length](../../aspose.html.dom.css/icssstyledeclaration/length/) { get; } | 이 선언 블록에 명시적으로 설정된 속성의 수입니다. 유효한 인덱스의 범위는 0에서 길이-1까지입니다. |
| [ParentRule](../../aspose.html.dom.css/icssstyledeclaration/parentrule/) { get; } | 이 CSSStyleDeclaration이 CSSRule에 첨부되지 않은 경우 이 선언 블록 또는 null을 포함하는 CSS 규칙입니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(string) | 이 선언 블록 내에서 명시적으로 설정된 경우 CSS 속성 값의 개체 표현을 검색하는 데 사용됩니다. 이 메서드는 속성이 속기 속성인 경우 null을 반환합니다. 약식 속성 값은 getPropertyValue 및 setProperty 메서드를 사용하여 문자열로만 액세스하고 수정할 수 있습니다. |
| [GetPropertyPriority](../../aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(string) | 속성이 이 선언 블록에 명시적으로 설정된 경우 CSS 속성(예: "중요" 한정자)의 우선 순위를 검색하는 데 사용됩니다. |
| [GetPropertyValue](../../aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(string) | 이 선언 블록 내에서 명시적으로 설정된 경우 CSS 속성 값을 검색하는 데 사용됩니다. |
| [RemoveProperty](../../aspose.html.dom.css/icssstyledeclaration/removeproperty/)(string) | 이 선언 블록 내에서 명시적으로 설정된 경우 CSS 속성을 제거하는 데 사용됩니다. |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(string, string) | 이 선언 블록 내에서 기본 우선 순위로 속성 값을 설정하는 데 사용됩니다. 기본 우선 순위는 "중요"하지 않습니다(예: String.Empty ). |
| [SetProperty](../../aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(string, string, string) | 이 선언 블록 내에서 속성 값과 우선 순위를 설정하는 데 사용됩니다. |

### 또한보십시오

* interface [ICSS2Properties](../icss2properties/)
* 네임스페이스 [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* 집회 [Aspose.HTML](../../)


