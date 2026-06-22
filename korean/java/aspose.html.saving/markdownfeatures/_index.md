---
title: "MarkdownFeatures 열거형"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.saving.MarkdownFeatures 열거형. MarkdownFeatures 플래그 집합은 마크다운으로 변환되는 요소를 선택하는 데 사용되는 다음 플래그 중 0개 이상으로 구성됩니다."
type: docs

url: /ko/java/com.aspose.html.saving/markdownfeatures/
---
## MarkdownFeatures enumeration

`MarkdownFeatures` 플래그 집합은 마크다운으로 변환되는 요소를 선택하는 데 사용되는 다음 플래그 중 0개 이상으로 구성됩니다.

```java
[Flags]
public enum MarkdownFeatures
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| InlineHTML | `1` | 이 플래그는 HTML 요소 인라인을 활성화합니다. 이 플래그가 설정되면 `div`와 같은 블록 레벨 요소 중 `markdown` 속성 값이 `inline`인 요소가 결과 마크다운에 삽입됩니다. |
| AutomaticParagraph | `2` | 이 플래그는 `paragraph` 요소의 변환을 활성화합니다. 해당 요소의 내용은 별도의 줄에 배치되어 마크다운 처리기가 이를 감쌀 것입니다. |
| Header | `4` | 이 플래그는 `header` 요소의 변환을 활성화합니다. |
| Blockquote | `8` | 이 플래그는 `blockquote` 요소의 변환을 활성화합니다. |
| List | `10` | 이 플래그는 `list` 요소의 변환을 활성화합니다. |
| CodeBlock | `20` | 이 플래그는 코드 블록의 변환을 활성화합니다. 코드 블록은 `pre`와 `code` 두 요소로 구성되며, 이러한 구조의 내용은 그대로 처리됩니다. "as is" |
| HorizontalRule | `40` | 이 플래그는 `horizontal rules` 요소의 변환을 활성화합니다. |
| Link | `80` | 이 플래그는 `a` 요소의 변환을 활성화합니다. |
| Emphasis | `100` | 이 플래그는 `emphasis` 요소의 변환을 활성화합니다. |
| InlineCode | `200` | 이 플래그는 `code` 요소의 변환을 활성화합니다. |
| Image | `400` | 이 플래그는 `img` 요소의 변환을 활성화합니다. |
| LineBreak | `800` | 이 플래그는 `br` 요소의 변환을 활성화합니다. |
| Video | `1000` | 이 플래그는 `video` 요소의 변환을 활성화합니다. |
| Table | `2000` | 이 플래그는 `table` 요소의 변환을 활성화합니다. |
| TaskList | `4000` | 이 플래그는 작업 목록의 변환을 활성화합니다. 작업 목록은 `input` 요소로 구성되며, 이 요소는 `list` 요소의 첫 번째 자식이어야 하고 `type` 속성 값이 `checkbox`와 일치해야 합니다. |
| Strikethrough | `8000` | 이 플래그는 `del` 요소의 변환을 활성화합니다. |
| Strong | `10000` | 이 플래그는 `strong` 요소의 변환을 활성화합니다. |

### 또 보기

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
