---
title: "EventTarget.DispatchEvent"
second_title: "Aspose.HTML for Java API リファレンス"
description: "EventTarget メソッド。指定された EventTarget に対してイベントを同期的にディスパッチし、影響を受けた EventListener を適切な順序で呼び出します。キャプチャフェーズやオプションのバブリングフェーズを含む通常のイベント処理規則は、dispatchEvent で手動でディスパッチされたイベントにも適用されます"
type: docs

url: /ja/java/com.aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

指定された [`EventTarget`](../../../com.aspose.html.dom.events/ieventtarget/) に対してイベントをディスパッチし（同期的に）、影響を受けた EventListener を適切な順序で呼び出します。キャプチャフェーズやオプションのバブリングフェーズを含む通常のイベント処理規則は、[`dispatchEvent()`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) で手動でディスパッチされたイベントにも適用されます。

```java
public bool DispatchEvent(Event @event)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| イベント | イベント | イベント処理に使用するイベントタイプ、動作、およびコンテキスト情報を指定します。 |

### 戻り値

戻り値は、イベントを処理したリスナーが呼び出されたかどうかを示します。呼び出された場合は false、そうでない場合は true です。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../domexception/) |  |

## Remarks

この方法でディスパッチされたイベントは、実装が直接ディスパッチするイベントと同じキャプチャおよびバブリングの動作を持ちます。イベントのターゲットは、呼び出された対象です。

### 関連項目

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
