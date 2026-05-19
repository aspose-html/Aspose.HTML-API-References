---
title: "SVGListBaseT 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.svg.collections.SVGListBase1T 클래스. 이 인터페이스는 모든 SVG 목록의 기본 목록을 정의합니다."
type: docs

url: /ko/java/com.aspose.html.dom.svg.collections/svglistbase-1/
---
## SVGListBase&lt;T&gt; class

이 인터페이스는 모든 SVG 리스트의 기본 목록을 정의합니다.

```java
public abstract class SVGListBase<T> : SVGValueType, IEnumerable<T>
```

| 매개변수 | 설명 |
| --- | --- |
| T | 목록에 저장된 항목의 유형. |

## 속성

| 이름 | 설명 |
| --- | --- |
[getItem]
[setItem] Returns the indexth item in the list. |
| [getLength](../../com.aspose.html.dom.svg.collections/svglistbase-1/length/) 목록에 있는 항목 수. |
| [getNumberOfItems](../../com.aspose.html.dom.svg.collections/svglistbase-1/numberofitems/) 목록에 있는 항목 수. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [appendItem](../../com.aspose.html.dom.svg.collections/svglistbase-1/appenditem/)(T) | 목록 끝에 새 항목을 삽입합니다. |
| [clear](../../com.aspose.html.dom.svg.collections/svglistbase-1/clear/)() | 목록의 모든 기존 항목을 제거하여 빈 목록이 됩니다. |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 관리되지 않는 리소스와 (옵션으로) 관리되는 리소스를 해제합니다. |
| [getEnumerator](../../com.aspose.html.dom.svg.collections/svglistbase-1/getenumerator/)() | 열거자를 가져옵니다. |
| [getItem](../../com.aspose.html.dom.svg.collections/svglistbase-1/getitem/)(ulong) | 목록에서 지정된 항목을 반환합니다. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 객체를 검색하는 데 사용됩니다. |
| [initialize](../../com.aspose.html.dom.svg.collections/svglistbase-1/initialize/)(T) | 목록의 모든 기존 항목을 제거하고 매개변수로 지정된 단일 항목을 보관하도록 목록을 다시 초기화합니다. |
| [insertItemBefore](../../com.aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/)(T, ulong) | 지정된 위치에 새 항목을 목록에 삽입합니다. 첫 번째 항목은 번호 0입니다. |
| [removeItem](../../com.aspose.html.dom.svg.collections/svglistbase-1/removeitem/)(ulong) | 목록에서 기존 항목을 제거합니다. |
| [replaceItem](../../com.aspose.html.dom.svg.collections/svglistbase-1/replaceitem/)(T, ulong) | 목록의 기존 항목을 새 항목으로 교체합니다. |

### 또 보기

* class [SVGValueType](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/)
* package [com.aspose.html.dom.svg.collections](../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../)
