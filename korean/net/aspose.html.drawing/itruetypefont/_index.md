---
title: Interface ITrueTypeFont
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Drawing.ITrueTypeFont 상호 작용. 트루타입 글꼴로 작업하기 위한 방법을 선언합니다.
type: docs
weight: 2760
url: /ko/net/aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

트루타입 글꼴로 작업하기 위한 방법을 선언합니다.

```csharp
public interface ITrueTypeFont
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [DataSize](../../aspose.html.drawing/itruetypefont/datasize/) { get; } | 글꼴 데이터의 크기를 bytes 로 반환합니다. |
| [FamilyName](../../aspose.html.drawing/itruetypefont/familyname/) { get; } | 글꼴 패밀리의 이름을 가져옵니다. |
| [FullFontName](../../aspose.html.drawing/itruetypefont/fullfontname/) { get; } | 이것은 "FamilyName"과 "SubFamilyName"의 조합이어야 합니다. 예외: 글꼴이 "SubFamilyName"에 로 표시된 것처럼 "Regular"인 경우 "FamilyName"에 포함된 패밀리 이름만 사용하십시오. 위의 전체 글꼴 이름 정의에 대한 예외는 CFF OpenType 글꼴의 Microsoft 플랫폼 문자열 에 대한 것입니다. 이 경우 전체 글꼴 이름 문자열은 CFF 이름 INDEX의 PostScript FontName과 동일해야 합니다. |
| [SubFamilyName](../../aspose.html.drawing/itruetypefont/subfamilyname/) { get; } | 글꼴 하위 패밀리 이름은 동일한 글꼴 패밀리 이름을 가진 그룹의 글꼴을 구별합니다. 스타일(기울임꼴, 기울임꼴) 및 두께(밝게, 굵게, 검은색 등)를 처리하는 것으로 가정합니다. 두께나 스타일에 특별한 차이가 없는 글꼴(예: 기울임꼴이 아닌 중간 두께, fsSelection 비트 6 설정)은 이 위치에 "Regular" 문자열을 저장해야 합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [GetAscent](../../aspose.html.drawing/itruetypefont/getascent/)(float) | 상승을 포인트 단위로 반환합니다. |
| [GetData](../../aspose.html.drawing/itruetypefont/getdata/)() | 글꼴 데이터가 있는 스트림을 엽니다. 호출자는 스트림 폐기를 담당합니다. |
| [GetDescent](../../aspose.html.drawing/itruetypefont/getdescent/)(float) | 하강을 포인트 단위로 반환합니다. |

### 또한보십시오

* 네임스페이스 [Aspose.Html.Drawing](../../aspose.html.drawing/)
* 집회 [Aspose.HTML](../../)


