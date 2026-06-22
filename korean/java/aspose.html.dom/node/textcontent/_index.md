---
title: "Node.TextContent"
second_title: "Java용 Aspose.HTML API 참조"
description: "Node 속성. Node 인터페이스의 textContent 속성은 노드와 그 하위 노드들의 텍스트 내용을 나타냅니다"
type: docs

url: /ko/java/com.aspose.html.dom/node/textcontent/
---
## Node.TextContent property

[`Node`](../) 인터페이스의 textContent 속성은 노드와 그 하위 노드들의 텍스트 내용을 나타냅니다.

```java
public String TextContent { get; set; }
```

### Property Value

문자열 또는 null. 값은 상황에 따라 달라집니다:

노드가 문서이거나 doctype인 경우, textContent는 null을 반환합니다. 참고: 전체 문서의 모든 텍스트와 CDATA 데이터를 가져오려면 document.documentElement.textContent를 사용하십시오. 노드가 CDATA 섹션, 주석, 처리 명령 또는 텍스트 노드인 경우, textContent는 노드 내부의 텍스트를 반환하거나 설정합니다, 즉 [`Node.nodeValue`](../nodevalue/)입니다. 다른 노드 유형의 경우, textContent는 주석 및 처리 명령을 제외한 모든 자식 노드의 textContent를 연결하여 반환합니다.

## 비고

참조:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-textcontent](https://dom.spec.whatwg.org/#dom-node-textcontent).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### 또 보기

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
