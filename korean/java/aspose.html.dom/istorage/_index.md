---
title: "IStorage 인터페이스"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.dom.IStorage 인터페이스. Web Storage API의 이 인터페이스는 특정 도메인의 세션 또는 로컬 스토리지에 대한 접근을 제공합니다. Web Storage 사양을 참조하십시오 https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs

url: /ko/java/com.aspose.html.dom/istorage/
---
## IStorage interface

Web Storage API의 이 인터페이스는 특정 도메인의 세션 또는 로컬 스토리지에 대한 접근을 제공합니다. Web Storage 사양을 참조하십시오: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```java
public interface IStorage
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getLength](../../com.aspose.html.dom/istorage/length/) 키/값 쌍의 수를 반환합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [clear](../../com.aspose.html.dom/istorage/clear/)() | 키/값 쌍이 있으면 모두 제거합니다. |
| [getItem](../../com.aspose.html.dom/istorage/getitem/)(String) | 주어진 키와 연결된 현재 값을 반환하며, 해당 키가 존재하지 않으면 null을 반환합니다. |
| [key](../../com.aspose.html.dom/istorage/key/)(long) | n번째 키의 이름을 반환하고, n이 키/값 쌍의 개수보다 크거나 같으면 null을 반환합니다. |
| [removeItem](../../com.aspose.html.dom/istorage/removeitem/)(String) | 주어진 키와 일치하는 키/값 쌍이 존재하면 해당 쌍을 제거합니다. |
| [setItem](../../com.aspose.html.dom/istorage/setitem/)(String, String) | 키로 식별된 쌍의 값을 value로 설정하고, 이전에 해당 키가 없었을 경우 새로운 키/값 쌍을 생성합니다. |

### 또 보기

* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
