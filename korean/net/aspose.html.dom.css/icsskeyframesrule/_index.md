---
title: Interface ICSSKeyframesRule
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Css.ICSSKeyframesRule 상호 작용. CSSKeyframesRule 인터페이스는 단일 animation 에 대한 전체 키프레임 세트를 나타냅니다.
type: docs
weight: 430
url: /ko/net/aspose.html.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

CSSKeyframesRule 인터페이스는 단일 animation 에 대한 전체 키프레임 세트를 나타냅니다.

```csharp
public interface ICSSKeyframesRule : ICSSRule
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [CSSRules](../../aspose.html.dom.css/icsskeyframesrule/cssrules/) { get; } | 이 속성은 list 의 키프레임에 대한 액세스를 제공합니다. |
| [Name](../../aspose.html.dom.css/icsskeyframesrule/name/) { get; } | 이 속성은 'animation-name' 속성에서 사용하는 키프레임의 이름입니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AppendRule](../../aspose.html.dom.css/icsskeyframesrule/appendrule/)(string) | appendRule 메서드는 전달된 CSSKeyframeRule을 전달된 key 의 목록에 추가합니다. |
| [DeleteRule](../../aspose.html.dom.css/icsskeyframesrule/deleterule/)(string) | deleteRule 메서드는 전달된 키가 있는 CSSKeyframeRule을 삭제합니다. 이 키가 있는 규칙이 존재하지 않으면 메서드는 아무것도 수행하지 않습니다 |
| [FindRule](../../aspose.html.dom.css/icsskeyframesrule/findrule/)(string) | findRule 메서드는 전달된 키와 일치하는 키가 있는 규칙을 반환합니다. 해당 규칙이 없으면 null 값이 반환됩니다 |

### 또한보십시오

* interface [ICSSRule](../icssrule/)
* 네임스페이스 [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* 집회 [Aspose.HTML](../../)


