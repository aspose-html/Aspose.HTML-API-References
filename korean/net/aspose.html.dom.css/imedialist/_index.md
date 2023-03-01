---
title: Interface IMediaList
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Css.IMediaList 상호 작용. MediaList 인터페이스는 이 컬렉션이 구현되는 방법을 정의하거나 제한하지 않고 정렬된 미디어 컬렉션의 추상화를 제공합니다. 빈 목록은 매체 all을 포함하는 목록과 동일합니다.
type: docs
weight: 580
url: /ko/net/aspose.html.dom.css/imedialist/
---
## IMediaList interface

MediaList 인터페이스는 이 컬렉션이 구현되는 방법을 정의하거나 제한하지 않고 정렬된 미디어 컬렉션의 추상화를 제공합니다. 빈 목록은 매체 "all"을 포함하는 목록과 동일합니다.

```csharp
public interface IMediaList : IEnumerable<string>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Item](../../aspose.html.dom.css/imedialist/item/) { get; } | 목록에서 인덱스를 반환합니다. 인덱스가 목록의 미디어 수보다 크거나 같으면 null을 반환합니다. 미디어 인덱스입니다. |
| [Length](../../aspose.html.dom.css/imedialist/length/) { get; } | 목록의 미디어 수입니다. 유효한 미디어의 범위는 0에서 길이-1까지입니다. |
| [MediaText](../../aspose.html.dom.css/imedialist/mediatext/) { get; } | 미디어 목록의 구문 분석 가능한 텍스트 표현입니다. 쉼표로 구분된 미디어 목록입니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AppendMedium](../../aspose.html.dom.css/imedialist/appendmedium/)(string) | 매체 newMedium을 목록 끝에 추가합니다. newMedium이 이미 사용 중이면 먼저 제거됩니다. |
| [DeleteMedium](../../aspose.html.dom.css/imedialist/deletemedium/)(string) | 목록에서 oldMedium으로 표시된 매체를 삭제합니다. |

### 또한보십시오

* 네임스페이스 [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* 집회 [Aspose.HTML](../../)


