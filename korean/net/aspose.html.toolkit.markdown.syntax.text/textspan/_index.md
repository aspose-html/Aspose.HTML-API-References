---
title: Struct TextSpan
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Toolkit.Markdown.Syntax.Text.TextSpan 구조체. 텍스트 범위를 나타냅니다.
type: docs
weight: 5660
url: /ko/net/aspose.html.toolkit.markdown.syntax.text/textspan/
---
## TextSpan structure

텍스트 범위를 나타냅니다.

```csharp
public struct TextSpan : IComparable<TextSpan>, IEquatable<TextSpan>
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextSpan](textspan/)(int, int) | TextSpan 만들기 |

## 속성

| 이름 | 설명 |
| --- | --- |
| [End](../../aspose.html.toolkit.markdown.syntax.text/textspan/end/) { get; } | 끝 인덱스를 가져옵니다. |
| [Length](../../aspose.html.toolkit.markdown.syntax.text/textspan/length/) { get; } | 길이를 가져옵니다. |
| [Start](../../aspose.html.toolkit.markdown.syntax.text/textspan/start/) { get; } | 시작 색인을 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [Combine](../../aspose.html.toolkit.markdown.syntax.text/textspan/combine/)(TextSpan, TextSpan) | 텍스트 spans 를 결합합니다. |
| static [Create](../../aspose.html.toolkit.markdown.syntax.text/textspan/create/)(int, int) | TextSpan 만들기 |
| static [CreateEmpty](../../aspose.html.toolkit.markdown.syntax.text/textspan/createempty/#createempty)() | 빈 텍스트 범위를 만듭니다. |
| static [CreateEmpty](../../aspose.html.toolkit.markdown.syntax.text/textspan/createempty/#createempty_1)(int) | 시작 위치에서 빈 TextSpan을 만듭니다. |
| static [CreateFromStartEnd](../../aspose.html.toolkit.markdown.syntax.text/textspan/createfromstartend/)(int, int) | TextSpan 만들기 |
| [CompareTo](../../aspose.html.toolkit.markdown.syntax.text/textspan/compareto/)(TextSpan) | 다른 TextSpan 와 비교 |
| override [Equals](../../aspose.html.toolkit.markdown.syntax.text/textspan/equals/#equals_1)(object) | 다른 object 와 비교 |
| [Equals](../../aspose.html.toolkit.markdown.syntax.text/textspan/equals/#equals)(TextSpan) | 다른 TextSpan 와 비교 |
| override [GetHashCode](../../aspose.html.toolkit.markdown.syntax.text/textspan/gethashcode/)() | 해시코드 가져오기 |
| [IsEmpty](../../aspose.html.toolkit.markdown.syntax.text/textspan/isempty/)() | 길이 ==0이면 참 반환. |
| override [ToString](../../aspose.html.toolkit.markdown.syntax.text/textspan/tostring/)() | Get ToString() override |
| [operator ==](../../aspose.html.toolkit.markdown.syntax.text/textspan/op_equality/) | == 연산자를 재정의합니다. |
| [operator !=](../../aspose.html.toolkit.markdown.syntax.text/textspan/op_inequality/) | != operator 를 재정의합니다. |

### 또한보십시오

* 네임스페이스 [Aspose.Html.Toolkit.Markdown.Syntax.Text](../../aspose.html.toolkit.markdown.syntax.text/)
* 집회 [Aspose.HTML](../../)


