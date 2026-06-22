---
title: "Document.CreateAttribute"
second_title: "Java용 Aspose.HTML API 참조"
description: "Document 메서드. Document.createAttribute 메서드는 새로운 속성 노드를 생성하고 반환합니다. 생성된 객체는 Attr 인터페이스를 구현하는 노드입니다. DOM은 이 방식으로 특정 요소에 추가할 수 있는 속성 종류를 강제하지 않습니다."
type: docs

url: /ko/java/com.aspose.html.dom/document/createattribute/
---
## Document.CreateAttribute method

Document.createAttribute() 메서드는 새로운 속성 노드를 생성하고 반환합니다. 생성된 객체는 [`Attr`](../../attr/) 인터페이스를 구현하는 노드입니다. DOM은 이 방식으로 특정 요소에 추가할 수 있는 속성 종류를 강제하지 않습니다.

```java
public Attr CreateAttribute(String localName)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| localName | String | name은 속성의 이름을 포함하는 문자열입니다. |

### 반환 값

하나의 [`Attr`](../../attr/) 노드입니다.

## 예제

```java
var element = document.GetElementById("div");
var attr = document.CreateAttribute("my_attr");
attr.Value = "my_value";
element.SetAttributeNode(attr);
```

### 또 보기

* class [Attr](../../attr/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
