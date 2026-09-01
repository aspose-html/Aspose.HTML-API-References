---
title: "IEventTarget.RemoveEventListener"
second_title: "Aspose.HTML for Java API リファレンス"
description: "IEventTarget メソッド。このメソッドはイベントターゲットからイベントリスナーを削除することを可能にします。イベントを処理中にリスナーが削除された場合、現在のアクションではトリガーされません。削除されたイベントリスナーは二度と呼び出されることはありません"
type: docs

url: /ja/java/com.aspose.html.dom.events/ieventtarget/removeeventlistener/
---
## RemoveEventListener(String, IEventListener) {#removeeventlistener}

このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。

```java
public void RemoveEventListener(String type, IEventListener listener)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | 文字列 | 削除される対象のイベントタイプを指定します。 |
| リスナー | IEventListener | パラメーターは削除される対象を示します。 |

### 関連項目

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener, bool) {#removeeventlistener_1}

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

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
