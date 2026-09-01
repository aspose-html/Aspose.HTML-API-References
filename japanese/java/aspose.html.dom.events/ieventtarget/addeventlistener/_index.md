---
title: "IEventTarget.AddEventListener"
second_title: "Aspose.HTML for Java API リファレンス"
description: "IEventTarget メソッド。EventTarget の addEventListener メソッドは、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。"
type: docs

url: /ja/java/com.aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(String, IEventListener) {#addeventlistener}

EventTarget のメソッド addEventListener() は、指定されたイベントがターゲットに送信されるたびに呼び出される関数を設定します。

一般的なターゲットは Element、Document、Window ですが、ターゲットはイベントをサポートする任意のオブジェクト（例: XMLHttpRequest）でも構いません。

```java
public void AddEventListener(String type, IEventListener listener)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | 文字列 | リスンするイベントタイプを表す大文字小文字を区別する文字列。 |
| リスナー | IEventListener | ユーザーが実装したインターフェイスを受け取り、イベントが発生したときに呼び出されるメソッドを含みます。 |

## 備考

イベント処理中に an が an に追加された場合、現在のアクションではトリガーされませんが、バブリングフェーズなど後続のイベントフロー段階でトリガーされる可能性があります。同じ対象に同一パラメータで複数の同一 Event Listeners が登録されている場合、重複インスタンスは破棄されます。これによりリスナーが二度呼び出されることはなく、破棄されたため method で削除する必要もありません。

### 関連項目

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_1}

EventTarget のメソッド addEventListener() は、指定されたイベントがターゲットに送信されるたびに呼び出される関数を設定します。

一般的なターゲットは Element、Document、Window ですが、ターゲットはイベントをサポートする任意のオブジェクト（例: XMLHttpRequest）でも構いません。

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | 文字列 | リスンするイベントタイプを表す大文字小文字を区別する文字列。 |
| リスナー | IEventListener | ユーザーが実装したインターフェイスを受け取り、イベントが発生したときに呼び出されるメソッドを含みます。 |
| useCapture | Boolean | true の場合、useCapture はユーザーがキャプチャを開始したいことを示します。キャプチャを開始すると、指定されたタイプのすべてのイベントは、ツリー内の下位の Event Targets にディスパッチされる前に、登録された対象にディスパッチされます。ツリーを上向きにバブリングするイベントは、キャプチャを使用するよう指定されたものをトリガーしません。 |

## 備考

イベント処理中に an が an に追加された場合、現在のアクションではトリガーされませんが、バブリングフェーズなど後続のイベントフロー段階でトリガーされる可能性があります。同じ対象に同一パラメータで複数の同一 Event Listeners が登録されている場合、重複インスタンスは破棄されます。これによりリスナーが二度呼び出されることはなく、破棄されたため method で削除する必要もありません。

### 関連項目

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
