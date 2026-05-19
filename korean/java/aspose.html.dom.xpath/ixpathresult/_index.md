---
title: "IXPathResult 인터페이스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.xpath.IXPathResult 인터페이스. XPathResult 인터페이스는 특정 노드 컨텍스트 내에서 XPath 1.0 식을 평가한 결과를 나타냅니다. XPath 식의 평가는 다양한 결과 유형을 만들 수 있기 때문에 이 객체를 통해 결과의 유형과 값을 확인하고 조작할 수 있습니다"
type: docs

url: /ko/java/com.aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

`XPathResult` 인터페이스는 특정 노드의 컨텍스트 내에서 XPath 1.0 식을 평가한 결과를 나타냅니다. XPath 식의 평가는 다양한 결과 유형을 반환할 수 있기 때문에, 이 객체를 통해 결과의 유형과 값을 확인하고 조작할 수 있습니다.

```java
public interface IXPathResult
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getBooleanValue](../../com.aspose.html.dom.xpath/ixpathresult/booleanvalue/) 이 부울 결과의 값입니다. |
| [getInvalidIteratorState](../../com.aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) 반복자가 무효가 되었음을 나타냅니다. `resultType`이 `UnorderedNodeIterator` 유형이거나 `OrderedNodeIterator` 유형이고 문서가 이 결과가 반환된 이후에 수정된 경우 true입니다. |
| [getNumberValue](../../com.aspose.html.dom.xpath/ixpathresult/numbervalue/) 이 숫자 결과의 값입니다. |
| [getResultType](../../com.aspose.html.dom.xpath/ixpathresult/resulttype/) 이 결과의 유형을 나타내는 코드이며, http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult[`XPathResultType`](../xpathresulttype/) 열거형에 의해 정의됩니다. |
| [getSingleNodeValue](../../com.aspose.html.dom.xpath/ixpathresult/singlenodevalue/) 이 단일 노드 결과의 값이며, `null`일 수 있습니다. |
| [getSnapshotLength](../../com.aspose.html.dom.xpath/ixpathresult/snapshotlength/) 결과 스냅샷에 포함된 노드 수입니다. snapshotItem 인덱스의 유효값은 `0`부터 `snapshotLength-1`까지 포함됩니다. |
| [getStringValue](../../com.aspose.html.dom.xpath/ixpathresult/Stringvalue/) 이 문자열 결과의 값입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [iterateNext](../../com.aspose.html.dom.xpath/ixpathresult/iteratenext/)() | 노드 집합을 순회하며 다음 노드를 반환합니다. 더 이상 노드가 없으면 `null`을 반환합니다. |
| [snapshotItem](../../com.aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | `index`번째 스냅샷 컬렉션 항목을 반환합니다. `index`가 목록의 노드 수보다 크거나 같으면 이 메서드는 `null`을 반환합니다. 반복자 결과와 달리 스냅샷은 무효화되지 않지만, 문서가 변경된 경우 현재 문서와 일치하지 않을 수 있습니다. |

### 또 보기

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
