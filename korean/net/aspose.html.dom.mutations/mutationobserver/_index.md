---
title: Class MutationObserver
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Dom.Mutations.MutationObserver 수업. AMutationObserver 개체는 트리의 돌연변이를 관찰하는 데 사용할 수 있습니다.Node .
type: docs
weight: 970
url: /ko/net/aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

A`MutationObserver` 개체는 트리의 돌연변이를 관찰하는 데 사용할 수 있습니다.[`Node`](../../aspose.html.dom/node/) .

```csharp
public class MutationObserver : DOMObject
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | MutationObserver 개체를 구성하고[`MutationCallback`](../mutationcallback/) 콜백합니다. MutationRecord 객체 목록을 첫 번째 인수로, 생성된 MutationObserver 객체를 두 번째 인수로 사용하여 콜백이 호출됩니다. 노드에 등록된 후에 호출됩니다.!:Observe(Node, IMutationObserverInit) 메서드가 변경되었습니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Disconnect](../../aspose.html.dom.mutations/mutationobserver/disconnect/)() | 관찰자가 돌연변이를 관찰하지 못하도록 합니다. observe() 메서드를 다시 사용할 때까지 관찰자의 콜백이 호출되지 않습니다. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 개체를 검색하는 데 사용됩니다.Type . |
| [Observe](../../aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | 주어진 대상(노드)을 관찰하고 옵션(객체)에 의해 주어진 기준에 따라 모든 돌연변이를 보고하도록 사용자 에이전트에 지시합니다. 옵션 인수를 사용하면 객체 구성원을 통해 돌연변이 관찰 옵션을 설정할 수 있습니다. |
| [Observe](../../aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | 주어진 대상(노드)을 관찰하고 옵션(객체)에 의해 주어진 기준에 따라 모든 돌연변이를 보고하도록 사용자 에이전트에 지시합니다. 옵션 인수를 사용하면 객체 구성원을 통해 돌연변이 관찰 옵션을 설정할 수 있습니다. |
| [TakeRecords](../../aspose.html.dom.mutations/mutationobserver/takerecords/)() | 메서드는 레코드 대기열의 복사본을 반환한 다음 레코드 대기열을 비웁니다. |

### 또한보십시오

* class [DOMObject](../../aspose.html.dom/domobject/)
* 네임스페이스 [Aspose.Html.Dom.Mutations](../../aspose.html.dom.mutations/)
* 집회 [Aspose.HTML](../../)


