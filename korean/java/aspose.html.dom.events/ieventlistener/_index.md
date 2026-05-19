---
title: "IEventListener 인터페이스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.dom.events.IEventListener 인터페이스. 이 인터페이스는 이벤트를 처리하기 위한 주요 방법입니다. 사용자는 인터페이스를 구현하고 해당 메서드를 사용하여 리스너를 등록합니다. 사용자는 리스너 사용을 완료한 후에는 이를 제거해야 합니다."
type: docs

url: /ko/java/com.aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

이 인터페이스는 이벤트를 처리하기 위한 기본 방법입니다. 사용자는 인터페이스를 구현하고 해당 메서드를 사용하여 리스너를 등록합니다. 사용자는 리스너 사용을 완료한 후 해당 리스너를 제거해야 합니다.

```java
public interface IEventListener
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [handleEvent](../../com.aspose.html.dom.events/ieventlistener/handleevent/)(Event) | 이 메서드는 인터페이스가 등록된 유형의 이벤트가 발생할 때마다 호출됩니다. |

## 비고

Node를 cloneNode 메서드로 복사할 때 원본 Node에 연결된 이벤트 리스너는 복사된 Node에 자동으로 연결되지 않습니다. 사용자가 동일한 이벤트 리스너를 새로 만든 복사본에 추가하려면 직접 추가해야 합니다.

### 또 보기

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
