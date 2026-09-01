---
title: "InputEvent クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.events.InputEvent クラス。入力イベントは、DOM が更新されるたびに通知として送信されます"
type: docs

url: /ja/java/com.aspose.html.dom.events/inputevent/
---
## InputEvent class

DOM が更新されるたびに、入力イベントが通知として送信されます。

```java
public class InputEvent : UIEvent
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [InputEvent](inputevent/#constructor)(String) | `InputEvent` クラスの新しいインスタンスを初期化します。 |
| [InputEvent](inputevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) イベントがバブリングイベントかどうかを示すために使用されます。イベントがバブリングできる場合は true、そうでない場合は false です。 |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) イベントのデフォルトアクションを防止できるかどうかを示すために使用されます。デフォルトアクションが防止できる場合は true、そうでない場合は false です。 |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) 現在処理中の [`IEventListener`](../ieventlistener/) を持つ [`IEventTarget`](../ieventtarget/) を示すために使用されます。これはキャプチャおよびバブリング時に特に有用です。 |
| [getData](../../com.aspose.html.dom.events/inputevent/data/) データは入力メソッドによって生成された文字の値を保持します。これは単一のUnicode文字または空でないUnicode文字のシーケンスである場合があります [Unicode]。文字は [UAX15] で定義された Unicode 正規化形式 NFC に従って正規化されるべきです。この属性は空文字列を含む場合があります。 |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) cancelable 属性が true のときに preventDefault() が呼び出された場合は true を返し、そうでない場合は false を返します。 |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) イベントの種類に応じた詳細情報を指定します。 |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) 現在評価されているイベントフローのフェーズを示すために使用されます。 |
| [getIsComposing](../../com.aspose.html.dom.events/inputevent/iscomposing/) true は、入力イベントが合成セッションの一部として発生した場合（つまり compositionstart イベントの後、対応する compositionend イベントの前）を示します。この属性の未初期化値は false でなければなりません。 |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) isTrusted属性は初期化された値を返す必要があります。イベントが作成されるとき、この属性はfalseに初期化されなければなりません。 |
| [getTarget](../../com.aspose.html.dom.events/event/target/) イベントが元々ディスパッチされた[`IEventTarget`](../ieventtarget/) を示すために使用されます。 |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) イベントが作成された時刻（エポックからのミリ秒）を指定するために使用されます。一部のシステムがこの情報を提供しない場合、timeStampの値はすべてのイベントで利用できないことがあります。利用できない場合は0が返されます。エポック時刻の例としてはシステム起動時やUTC 1970年1月1日 0:0:0 があります。 |
| [getType](../../com.aspose.html.dom.events/event/type/) イベントの名前（大文字小文字を区別しない）。名前はXML名でなければなりません。 |
| [getView](../../com.aspose.html.dom.events/uievent/view/) view 属性は、イベントが生成された Window を識別します。この属性の未初期化値は必ず null でなければなりません。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | この [`InitEvent`](../event/initevent/) メソッドは、[`IDocumentEvent`](../idocumentevent/) インターフェイスを通じて作成された[`Event`](../event/) の値を初期化するために使用されます。 |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | イベントがキャンセル可能な場合、[`PreventDefault`](../event/preventdefault/) メソッドはイベントがキャンセルされることを示すために使用されます。つまり、イベントの結果として実装が通常行うデフォルトの動作は行われません。 |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | このメソッドを呼び出すと、現在のリスナーの後に登録されたすべてのイベントリスナーにイベントが到達するのを防ぎ、ツリー内でディスパッチされた場合は他のオブジェクトにもイベントが到達するのを防止します。 |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | この [`StopPropagation`](../event/stoppropagation/) メソッドは、イベントフロー中のイベントのさらなる伝播を防止するために使用されます。 |

### 関連項目

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
