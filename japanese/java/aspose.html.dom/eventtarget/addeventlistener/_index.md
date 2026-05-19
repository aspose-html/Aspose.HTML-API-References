---
title: "EventTarget.AddEventListener"
second_title: "Aspose.HTML for Java API リファレンス"
description: "EventTarget メソッド。EventTarget インターフェイスの addEventListener メソッドは、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します"
type: docs

url: /ja/java/com.aspose.html.dom/eventtarget/addeventlistener/
---
## AddEventListener(String, DOMEventHandler, bool) {#addeventlistener}

addEventListener() メソッドは、[EventTarget ](T:com.aspose.html.dom.EventTarget) インターフェイスのもので、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。

呼び出された EventTarget の指定されたイベントタイプのイベントリスナーリストに、関数または [EventListener](T:com.aspose.html.dom.events.IEventListener) を実装したオブジェクトを追加することで機能します。関数またはオブジェクトがすでにこのターゲットのイベントリスナーリストに存在する場合、二度目は追加されません。

```java
public void AddEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| type | 文字列 | ユーザーが登録するイベントタイプ |
| ハンドラ | DOMEventHandler | イベントが発生したときに呼び出されるものを受け取ります。 |
| useCapture | Boolean | true の場合、useCapture はユーザーがキャプチャを開始したいことを示します。キャプチャが開始されると、指定されたタイプのすべてのイベントは、ツリー内の下位の Event Target にディスパッチされる前に、登録された対象へディスパッチされます。ツリー上部へバブリングするイベントは、キャプチャを使用するよう指定された対象をトリガーしません。 |

## Remarks

イベント処理中に an が an に追加された場合、現在のアクションではトリガーされませんが、バブリングフェーズなどイベントフローの後段でトリガーされる可能性があります。同じ対象に同一パラメータで複数の同一 Event Listener が登録されている場合、重複したインスタンスは破棄されます。これによりリスナーが二度呼び出されることはなく、破棄されたため method で削除する必要もありません。

### 関連項目

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener) {#addeventlistener_1}

[`EventTarget `](../) インターフェイスの addEventListener() メソッドは、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。

呼び出された EventTarget の指定されたイベントタイプのイベントリスナーリストに、関数または [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/) を実装したオブジェクトを追加することで機能します。関数またはオブジェクトがすでにこのターゲットのイベントリスナーリストに存在する場合、二度目は追加されません。

```java
public void AddEventListener(String type, IEventListener listener)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| type | 文字列 | ユーザーが登録するイベントタイプ |
| リスナー | IEventListener | イベントが発生した際に呼び出されるメソッドを含む、ユーザーが実装したインターフェイスを受け取ります。 |

## Remarks

イベント処理中に an が an に追加された場合、現在のアクションではトリガーされませんが、バブリングフェーズなどイベントフローの後段でトリガーされる可能性があります。同じ対象に同一パラメータで複数の同一 Event Listener が登録されている場合、重複したインスタンスは破棄されます。これによりリスナーが二度呼び出されることはなく、破棄されたため method で削除する必要もありません。

### 関連項目

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_2}

addEventListener() メソッドは、[EventTarget ](T:com.aspose.html.dom.EventTarget) インターフェイスのもので、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。

呼び出された EventTarget の指定されたイベントタイプのイベントリスナーリストに、関数または [EventListener](T:com.aspose.html.dom.events.IEventListener) を実装したオブジェクトを追加することで機能します。関数またはオブジェクトがすでにこのターゲットのイベントリスナーリストに存在する場合、二度目は追加されません。

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| type | 文字列 | ユーザーが登録するイベントタイプ |
| リスナー | IEventListener | イベントが発生した際に呼び出されるメソッドを含む、ユーザーが実装したインターフェイスを受け取ります。 |
| useCapture | Boolean | true の場合、useCapture はユーザーがキャプチャを開始したいことを示します。キャプチャが開始されると、指定されたタイプのすべてのイベントは、ツリー内の下位の Event Target にディスパッチされる前に、登録された対象へディスパッチされます。ツリー上部へバブリングするイベントは、キャプチャを使用するよう指定された対象をトリガーしません。 |

## Remarks

イベント処理中に an が an に追加された場合、現在のアクションではトリガーされませんが、バブリングフェーズなどイベントフローの後段でトリガーされる可能性があります。同じ対象に同一パラメータで複数の同一 Event Listener が登録されている場合、重複したインスタンスは破棄されます。これによりリスナーが二度呼び出されることはなく、破棄されたため method で削除する必要もありません。

### 関連項目

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
