---
title: "NodeListT 클래스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.toolkit.markdown.syntax.NodeList1T 클래스. NodeList의 기본 구현입니다."
type: docs

url: /ko/java/com.aspose.html.toolkit.markdown.syntax/nodelist-1/
---
## NodeList&lt;T&gt; class

NodeList의 기본 구현입니다.

```java
public abstract class NodeList<T> : IEnumerable<T>, IWritable
    where T : MarkdownSyntaxNode
```

| Parameter | 설명 |
| --- | --- |
| T | T 타입입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| 추상 [getCount](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/count/) 리스트에 있는 노드 수를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| abstract [Get](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/get/)(int) | 지정된 인덱스의 노드를 가져옵니다. |
| abstract [GetEnumerator](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/getenumerator/)() | 컬렉션에 있는 노드들을 가져옵니다. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/writeto/)(TextWriter) | 노드를 텍스트 라이터에 씁니다. |

### 또 보기

* interface [IWritable](../iwritable/)
* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
