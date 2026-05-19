---
title: "IEventListener Interface"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.events.IEventListener interface. The interface is the primary method for handling events. Users implement the interface and register their listener on an using the method. The users should also remove their from its after they have completed using the listener"
type: docs

url: /ja/java/com.aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

このインターフェイスは、イベント処理の主要な手段です。ユーザーはインターフェイスを実装し、メソッドを使用してリスナーを登録します。リスナーの使用が完了したら、ユーザーはそれを削除すべきです。

```java
public interface IEventListener
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [handleEvent](../../com.aspose.html.dom.events/ieventlistener/handleevent/)(Event) | This method is called whenever an event occurs of the type for which the interface was registered. |

## Remarks

When a Node is copied using the cloneNode method the Event Listeners attached to the source Node are not attached to the copied Node. If the user wishes the same Event Listeners to be added to the newly created copy the user must add them manually.

### 関連項目

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
