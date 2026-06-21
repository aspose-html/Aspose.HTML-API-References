---
title: "IEventTarget インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.events.IEventTarget インターフェイス。EventTarget インターフェイスは、DOM イベントモデルをサポートする実装におけるすべてのノードで実装されています。そのため、このインターフェイスは Node インターフェイスのインスタンスに対してバインディング固有のキャストメソッドを使用することで取得できます。このインターフェイスは、Event Listener の登録と削除、およびイベントのディスパッチを可能にします。"
type: docs

url: /ja/java/com.aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

EventTarget インターフェイスは、DOM イベントモデルをサポートする実装におけるすべてのノードで実装されています。そのため、このインターフェイスは Node インターフェイスのインスタンスに対してバインディング固有のキャストメソッドを使用することで取得できます。このインターフェイスは、イベントリスナーの登録と削除、およびその対象へのイベントディスパッチを可能にします。

```java
public interface IEventTarget
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(String, IEventListener) | EventTarget のメソッド addEventListener() は、指定されたイベントがターゲットに送信されるたびに呼び出される関数を設定します。 |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener, bool) | EventTarget のメソッド addEventListener() は、指定されたイベントがターゲットに送信されるたびに呼び出される関数を設定します。 |
| [dispatchEvent](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | 指定された EventTarget に対してイベントをディスパッチし（同期的に）、影響を受けた EventListener を適切な順序で呼び出します。通常のイベント処理規則（キャプチャフェーズやオプションのバブリングフェーズを含む）も、dispatchEvent() で手動にディスパッチされたイベントに適用されます。 |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(String, IEventListener) | このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener, bool) | このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |

### 関連項目

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
