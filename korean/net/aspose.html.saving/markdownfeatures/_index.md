---
title: Enum MarkdownFeatures
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Saving.MarkdownFeatures 열거형. AMarkdownFeatures flag set은 마크다운으로 변환된 요소를 선택하는 데 사용되는 다음 플래그 중 0개 이상의 집합입니다.
type: docs
weight: 4620
url: /ko/net/aspose.html.saving/markdownfeatures/
---
## MarkdownFeatures enumeration

A`MarkdownFeatures` flag set은 마크다운으로 변환된 요소를 선택하는 데 사용되는 다음 플래그 중 0개 이상의 집합입니다.

```csharp
[Flags]
public enum MarkdownFeatures
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| InlineHTML | `1` | 이 플래그는 HTML 요소 인라인을 활성화합니다. 이 플래그가 블록 수준 요소(예:`사업부` ) 누구의`가격 인하` 속성 값이 같음`인라인` 결과 markdown. 에 삽입됩니다. |
| AutomaticParagraph | `2` | 이 플래그는`절` 강요. 이러한 요소의 콘텐츠는 별도의 줄에 배치되므로 마크다운 처리기가 이를 래핑합니다. |
| Header | `4` | 이 플래그는`머리글` 요소. |
| Blockquote | `8` | 이 플래그는`인용구` 요소. |
| List | `10` | 이 플래그는`목록` 요소. |
| CodeBlock | `20` | 이 플래그는 코드 블록의 변환을 가능하게 합니다. 코드 블록은 2개의 요소로 구성됩니다.`미리` 그리고`암호` , 그러한 구성의 내용은 "있는 그대로" 프로세스입니다. |
| HorizontalRule | `40` | 이 플래그는`수평 규칙` . |
| Link | `80` | 이 플래그는`ㅏ` 요소. |
| Emphasis | `100` | 이 플래그는`중요성` 요소. |
| InlineCode | `200` | 이 플래그는`암호` 요소. |
| Image | `400` | 이 플래그는`이미지` 요소. |
| LineBreak | `800` | 이 플래그는`br` 요소. |
| Video | `1000` | 이 플래그는`동영상` 요소. |
| Table | `2000` | 이 플래그는`테이블` 요소. |
| TaskList | `4000` | 이 플래그는 작업 목록의 변환을 가능하게 합니다. 작업 목록은 다음으로 구성됩니다.`입력` 의 첫 번째 자식이어야 하는 요소`목록` 요소와 누구의`유형` 속성 값은 같아야 합니다.`확인란` . |
| Strikethrough | `8000` | 이 플래그는`델` 요소. |
| Strong | `10000` | 이 플래그는`강한` 요소. |

### 또한보십시오

* 네임스페이스 [Aspose.Html.Saving](../../aspose.html.saving/)
* 집회 [Aspose.HTML](../../)


