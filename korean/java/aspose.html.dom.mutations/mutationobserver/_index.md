---
title: "MutationObserver 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.mutations.MutationObserver 클래스. 객체를 사용하여 트리의 변이를 관찰할 수 있습니다."
type: docs

url: /ko/java/com.aspose.html.dom.mutations/mutationobserver/
---
## MutationObserver class

객체를 사용하여 트리의 변이를 관찰할 수 있습니다 [`.`](../../com.aspose.html.dom/node/)

```java
public class MutationObserver : DOMObject
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MutationObserver](mutationobserver/)(MutationCallback) | MutationObserver 객체를 생성하고 its [`MutationCallback`](../mutationcallback/)을 콜백으로 설정합니다. 콜백은 첫 번째 인수로 MutationRecord 객체 목록을, 두 번째 인수로 생성된 MutationObserver 객체를 전달받아 호출됩니다. 이는 !:Observe(Node, IMutationObserverInit) 메서드에 등록된 노드가 변이된 후 호출됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [disconnect](../../com.aspose.html.dom.mutations/mutationobserver/disconnect/)() | observer가 모든 변이를 관찰하는 것을 중지합니다. observe() 메서드를 다시 사용할 때까지 observer의 콜백은 호출되지 않습니다. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 객체를 검색하는 데 사용됩니다. |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe)(Node) | 사용자 에이전트에게 지정된 대상(노드)을 관찰하고 옵션(객체)으로 제공된 기준에 따라 변이를 보고하도록 지시합니다. options 인자는 객체 멤버를 통해 변이 관찰 옵션을 설정할 수 있게 합니다. |
| [observe](../../com.aspose.html.dom.mutations/mutationobserver/observe/#observe_1)(Node, MutationObserverInit) | 사용자 에이전트에게 지정된 대상(노드)을 관찰하고 옵션(객체)으로 제공된 기준에 따라 변이를 보고하도록 지시합니다. options 인자는 객체 멤버를 통해 변이 관찰 옵션을 설정할 수 있게 합니다. |
| [takeRecords](../../com.aspose.html.dom.mutations/mutationobserver/takerecords/)() | 이 메서드는 레코드 큐의 복사본을 반환한 뒤 레코드 큐를 비웁니다. |

### 또 보기

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.mutations](../../com.aspose.html.dom.mutations/)
* package [Aspose.HTML](../../)
