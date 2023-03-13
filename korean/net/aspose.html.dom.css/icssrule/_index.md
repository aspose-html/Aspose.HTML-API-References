---
title: Interface ICSSRule
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Css.ICSSRule 상호 작용. CSSRule 인터페이스는 모든 유형의 CSS 문에 대한 추상 기본 인터페이스입니다. 여기에는 규칙 집합과 at규칙이 모두 포함됩니다. 구문 분석기에서 규칙을 인식하지 못하는 경우에도 구현 시 CSS 스타일 시트에 지정된 모든 규칙을 보존해야 합니다. 인식할 수 없는 규칙은ICSSUnknownRule 인터페이스.
type: docs
weight: 470
url: /ko/net/aspose.html.dom.css/icssrule/
---
## ICSSRule interface

CSSRule 인터페이스는 모든 유형의 CSS 문에 대한 추상 기본 인터페이스입니다. 여기에는 규칙 집합과 at-규칙이 모두 포함됩니다. 구문 분석기에서 규칙을 인식하지 못하는 경우에도 구현 시 CSS 스타일 시트에 지정된 모든 규칙을 보존해야 합니다. 인식할 수 없는 규칙은!:ICSSUnknownRule 인터페이스.

```csharp
public interface ICSSRule
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [CSSText](../../aspose.html.dom.css/icssrule/csstext/) { get; set; } | 규칙의 구문 분석 가능한 텍스트 표현입니다. 이것은 초기 값이 아니라 규칙의 현재 상태를 반영합니다. |
| [ParentRule](../../aspose.html.dom.css/icssrule/parentrule/) { get; } | 이 규칙이 다른 규칙(예: @media 블록 내부의 스타일 규칙) 내에 포함된 경우 이것이 포함하는 규칙입니다. 이 규칙이 다른 규칙 내에 중첩되지 않은 경우 null을 반환합니다. |
| [ParentStyleSheet](../../aspose.html.dom.css/icssrule/parentstylesheet/) { get; } | 이 규칙을 포함하는 스타일시트입니다. |
| [Type](../../aspose.html.dom.css/icssrule/type/) { get; } | 위에 정의된 규칙의 유형입니다. CSSRule 인터페이스의 인스턴스에서 type. 가 암시하는 특정 파생 인터페이스로 캐스트 다운하는 데 바인딩 특정 캐스팅 메서드를 사용할 수 있습니다. |

### 또한보십시오

* 네임스페이스 [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* 집회 [Aspose.HTML](../../)


