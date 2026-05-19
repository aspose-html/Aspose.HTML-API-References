---
title: "CustomEvent Class"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.events.CustomEvent class. Events using the CustomEvent interface can be used to carry custom data"
type: docs

url: /ja/java/com.aspose.html.dom.events/customevent/
---
## CustomEvent class

CustomEvent インターフェイスを使用したイベントは、カスタムデータを運ぶために使用できます。

```java
public class CustomEvent : Event
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [CustomEvent](customevent/#constructor)(String) | Initializes a new instance of the `CustomEvent` class. |
| [CustomEvent](customevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) イベントがバブリングイベントかどうかを示すために使用されます。イベントがバブリングできる場合は true、そうでない場合は false です。 |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) イベントのデフォルトアクションを防止できるかどうかを示すために使用されます。デフォルトアクションが防止できる場合は true、そうでない場合は false です。 |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) 現在処理中の [`IEventTarget`](../ieventtarget/) と、その [`IEventListener`](../ieventlistener/) がどれかを示すために使用されます。これはキャプチャおよびバブリング時に特に有用です。 |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) cancelable 属性が true のときに preventDefault() が呼び出された場合は true を返し、そうでない場合は false を返します。 |
| [getDetail](../../com.aspose.html.dom.events/customevent/detail/) Gets the custom data. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) 現在評価されているイベントフローのフェーズを示すために使用されます。 |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) isTrusted 属性は初期化された値を返す必要があります。イベントが作成されると、この属性は false に初期化されなければなりません。 |
| [getTarget](../../com.aspose.html.dom.events/event/target/) イベントが元々ディスパッチされた [`IEventTarget`](../ieventtarget/) を示すために使用されます。 |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) イベントが作成された時刻（エポックからのミリ秒）を指定するために使用されます。一部のシステムがこの情報を提供しない場合、timeStamp の値はすべてのイベントで利用できないことがあります。利用できない場合は 0 が返されます。エポック時刻の例としてはシステム起動時や 1970年1月1日 0:0:0 UTC が挙げられます。 |
| [getType](../../com.aspose.html.dom.events/event/type/) イベントの名前（大文字小文字を区別しない）。名前は XML 名でなければなりません。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [initCustomEvent](../../com.aspose.html.dom.events/customevent/initcustomevent/)(String, bool, bool, object) | /// The [`InitEvent`](../event/initevent/) method is used to initialize the value of an [`Event`](../event/) created through the [`IDocumentEvent`](../idocumentevent/) interface. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | The [`InitEvent`](../event/initevent/) メソッドは、[`IDocumentEvent`](../idocumentevent/) インターフェイスを介して作成された [`Event`](../event/) の値を初期化するために使用されます。 |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | イベントがキャンセル可能な場合、[`PreventDefault`](../event/preventdefault/) メソッドはイベントをキャンセルすることを示すために使用されます。つまり、イベントの結果として実装が通常行うデフォルトの動作は実行されません。 |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | このメソッドを呼び出すと、現在のリスナーの後に登録されたすべてのイベントリスナーにイベントが届くのを防ぎ、ツリー内でディスパッチされた場合は他のオブジェクトにもイベントが届くのを防止します。 |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | The [`StopPropagation`](../event/stoppropagation/) メソッドは、イベントフロー中のイベントのさらなる伝搬を防止するために使用されます。 |

### 関連項目

* class [Event](../event/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
