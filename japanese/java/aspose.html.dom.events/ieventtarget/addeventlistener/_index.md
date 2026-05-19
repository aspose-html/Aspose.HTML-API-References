---
title: "IEventTarget.AddEventListener"
second_title: "Aspose.HTML for Java API リファレンス"
description: "IEventTarget メソッド。EventTarget の addEventListener メソッドは、指定されたイベントがターゲットに送られるたびに呼び出される関数を設定します。"
type: docs

url: /ja/java/com.aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(String, IEventListener) {#addeventlistener}

EventTarget のメソッド addEventListener() は、指定されたイベントがターゲットに送信されるたびに呼び出される関数を設定します。

一般的なターゲットは Element、Document、Window ですが、イベントをサポートする任意のオブジェクト（例: XMLHttpRequest）でもターゲットにできます。

```java
public void AddEventListener(String type, IEventListener listener)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| type | 文字列 | リッスン対象のイベントタイプを表す大文字小文字を区別する文字列です。 |
| リスナー | IEventListener | イベントが発生した際に呼び出されるメソッドを含む、ユーザーが実装したインターフェイスを受け取ります。 |

## Remarks

イベント処理中に an が an に追加された場合、現在のアクションではトリガーされませんが、バブリングフェーズなどイベントフローの後段でトリガーされる可能性があります。同じ対象に同一パラメータで複数の同一 Event Listener が登録されている場合、重複したインスタンスは破棄されます。これによりリスナーが二度呼び出されることはなく、破棄されたため method で削除する必要もありません。

### 関連項目

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_1}

EventTarget のメソッド addEventListener() は、指定されたイベントがターゲットに送信されるたびに呼び出される関数を設定します。

一般的なターゲットは Element、Document、Window ですが、イベントをサポートする任意のオブジェクト（例: XMLHttpRequest）でもターゲットにできます。

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| type | 文字列 | リッスン対象のイベントタイプを表す大文字小文字を区別する文字列です。 |
| リスナー | IEventListener | イベントが発生した際に呼び出されるメソッドを含む、ユーザーが実装したインターフェイスを受け取ります。 |
| useCapture | Boolean | true の場合、useCapture はユーザーがキャプチャを開始したいことを示します。キャプチャが開始されると、指定されたタイプのすべてのイベントは、ツリー内の下位の Event Target にディスパッチされる前に、登録された対象へディスパッチされます。ツリー上部へバブリングするイベントは、キャプチャを使用するよう指定された対象をトリガーしません。 |

## Remarks

イベント処理中に an が an に追加された場合、現在のアクションではトリガーされませんが、バブリングフェーズなどイベントフローの後段でトリガーされる可能性があります。同じ対象に同一パラメータで複数の同一 Event Listener が登録されている場合、重複したインスタンスは破棄されます。これによりリスナーが二度呼び出されることはなく、破棄されたため method で削除する必要もありません。

### 関連項目

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
