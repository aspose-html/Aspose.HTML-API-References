---
title: "ITrueTypeFont 인터페이스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.drawing.ITrueTypeFont 인터페이스. TrueType 글꼴을 다루는 메서드를 선언합니다."
type: docs

url: /ko/java/com.aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

TrueType 글꼴을 다루는 메서드를 선언합니다.

```java
public interface ITrueTypeFont
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getDataSize](../../com.aspose.html.drawing/itruetypefont/datasize/) 폰트 데이터의 크기를 바이트 단위로 반환합니다. |
| [getFamilyName](../../com.aspose.html.drawing/itruetypefont/familyname/) 글꼴 패밀리 이름을 가져옵니다. |
| [getFullFontName](../../com.aspose.html.drawing/itruetypefont/fullfontname/) 이는 "FamilyName"과 "SubFamilyName"의 조합이어야 합니다. 예외: "SubFamilyName"에 "Regular" 로 표시된 경우에는 "FamilyName"에 포함된 패밀리 이름만 사용합니다. 위의 Full font name 정의에 대한 예외는 Microsoft 플랫폼의 CFF OpenType 글꼴 문자열에 적용됩니다: 이 경우 Full font name 문자열은 CFF Name INDEX의 PostScript FontName과 동일해야 합니다. |
| [getSubFamilyName](../../com.aspose.html.drawing/itruetypefont/subfamilyname/) Font Subfamily 이름은 동일한 Font Family 이름을 가진 그룹 내에서 글꼴을 구분합니다. 이는 스타일(italic, oblique)과 굵기(light, bold, black 등)를 나타내는 것으로 간주됩니다. 굵기나 스타일에 특별한 차이가 없는 글꼴(예: 중간 굵기, 이탤릭이 아니며 fsSelection 비트 6이 설정된 경우)에는 이 위치에 문자열 "Regular"가 저장되어야 합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [getAscent](../../com.aspose.html.drawing/itruetypefont/getascent/)(float) | 어센트를 포인트 단위로 반환합니다. |
| [getData](../../com.aspose.html.drawing/itruetypefont/getdata/)() | 폰트 데이터가 포함된 스트림을 엽니다. 호출자는 스트림을 해제할 책임이 있습니다. |
| [getDescent](../../com.aspose.html.drawing/itruetypefont/getdescent/)(float) | 디센트를 포인트 단위로 반환합니다. |

### 또 보기

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
