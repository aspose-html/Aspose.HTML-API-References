---
title: Class NamedNodeMap
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Collections.NamedNodeMap 수업. 이름으로 액세스할 수 있는 특성 모음을 나타냅니다.
type: docs
weight: 40
url: /ko/net/aspose.html.collections/namednodemap/
---
## NamedNodeMap class

이름으로 액세스할 수 있는 특성 모음을 나타냅니다.

```csharp
public class NamedNodeMap : DOMObject, IDisposable, IEnumerable<Attr>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Item](../../aspose.html.collections/namednodemap/item/) { get; } | 맵에서 인덱스 번째 항목을 반환합니다. 인덱스가 이 맵의 노드 수보다 크거나 같으면 null을 반환합니다. (2 indexers) |
| [Length](../../aspose.html.collections/namednodemap/length/) { get; } | 이 맵의 노드 수입니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [GetEnumerator](../../aspose.html.collections/namednodemap/getenumerator/)() | 컬렉션을 반복하는 열거자를 반환합니다. |
| [GetNamedItem](../../aspose.html.collections/namednodemap/getnameditem/)(string) | 이름으로 지정된 노드를 검색합니다. |
| [GetNamedItemNS](../../aspose.html.collections/namednodemap/getnameditemns/)(string, string) | 로컬 이름과 네임스페이스 URI로 지정된 노드를 검색합니다. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 개체를 검색하는 데 사용됩니다.Type . |
| [RemoveNamedItem](../../aspose.html.collections/namednodemap/removenameditem/)(string) | 이름으로 지정된 노드를 제거합니다. |
| [RemoveNamedItemNS](../../aspose.html.collections/namednodemap/removenameditemns/)(string, string) | 로컬 이름 및 네임스페이스 URI로 지정된 노드를 제거합니다. |
| [SetNamedItem](../../aspose.html.collections/namednodemap/setnameditem/)(Attr) | nodeName 특성을 사용하여 노드를 추가합니다. 해당 이름의 노드가 이 맵에 이미 있으면 새 노드로 대체됩니다. 노드 자체를 교체해도 아무런 효과가 없습니다. |
| [SetNamedItemNS](../../aspose.html.collections/namednodemap/setnameditemns/)(Attr) | namespaceURI 및 localName을 사용하여 노드를 추가합니다. 해당 네임스페이스 URI 및 해당 로컬 이름이 있는 노드가 이 맵에 이미 있으면 새 노드로 대체됩니다. 노드 자체를 교체해도 아무런 효과가 없습니다. |

### 또한보십시오

* class [DOMObject](../../aspose.html.dom/domobject/)
* class [Attr](../../aspose.html.dom/attr/)
* 네임스페이스 [Aspose.Html.Collections](../../aspose.html.collections/)
* 집회 [Aspose.HTML](../../)


