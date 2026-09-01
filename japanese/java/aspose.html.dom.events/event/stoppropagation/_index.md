---
title: "Event.StopPropagation"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Event メソッド。StopPropagation メソッドは、イベントフロー中にイベントのさらなる伝播を防止するために使用されます。"
type: docs

url: /ja/java/com.aspose.html.dom.events/event/stoppropagation/
---
## Event.StopPropagation method

`StopPropagation` メソッドは、イベントフロー中にイベントのさらなる伝播を防止するために使用されます。

```java
public void StopPropagation()
```

## 備考

このメソッドが任意の [`IEventListener`](../../ieventlistener/) によって呼び出された場合、イベントはツリー上での伝播を停止します。イベントは、イベントフローが停止する前に現在の [`IEventTarget`](../../ieventtarget/) 上のすべてのリスナーへのディスパッチを完了します。このメソッドは、イベントフローの任意の段階で使用できます。

### 関連項目

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
