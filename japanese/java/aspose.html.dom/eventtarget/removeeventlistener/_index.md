---
title: "EventTarget.RemoveEventListener"
second_title: "Aspose.HTML for Java API リファレンス"
description: "EventTarget メソッド。このメソッドはイベントターゲットからイベントリスナーを削除できるようにします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。削除されたイベントリスナーは決して呼び出されません"
type: docs

url: /ja/java/com.aspose.html.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(String, DOMEventHandler, bool) {#removeeventlistener}

このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。

```java
public void RemoveEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | 文字列 | 削除される対象のイベントタイプを指定します。 |
| ハンドラ | DOMEventHandler | パラメーターは削除される対象を示します。 |
| useCapture | Boolean | 削除される EventListener がキャプチャリスナーとして登録されていたかどうかを指定します。リスナーが 2 回登録されている場合、1 つはキャプチャあり、もう 1 つはキャプチャなしで、各々を個別に削除する必要があります。キャプチャリスナーの削除は、同じリスナーの非キャプチャバージョンには影響せず、その逆も同様です。 |

### 関連項目

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener) {#removeeventlistener_1}

このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。

```java
public void RemoveEventListener(String type, IEventListener listener)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | 文字列 | 削除される対象のイベントタイプを指定します。 |
| リスナー | IEventListener | パラメーターは削除される対象を示します。 |

### 関連項目

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener, bool) {#removeeventlistener_2}

このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。

```java
public void RemoveEventListener(String type, IEventListener listener, bool useCapture)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | 文字列 | 削除される対象のイベントタイプを指定します。 |
| リスナー | IEventListener | パラメーターは削除される対象を示します。 |
| useCapture | Boolean | 削除される EventListener がキャプチャリスナーとして登録されていたかどうかを指定します。リスナーが 2 回登録されている場合、1 つはキャプチャあり、もう 1 つはキャプチャなしで、各々を個別に削除する必要があります。キャプチャリスナーの削除は、同じリスナーの非キャプチャバージョンには影響せず、その逆も同様です。 |

### 関連項目

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
