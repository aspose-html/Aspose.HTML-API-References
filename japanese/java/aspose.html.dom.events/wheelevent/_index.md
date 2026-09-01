---
title: "WheelEvent クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.events.WheelEvent クラス。WheelEvent インターフェイスは、ホイールイベントに関連する特定のコンテキスト情報を提供します。WheelEvent インターフェイスのインスタンスを作成するには、オプションの WheelEventInit 辞書を渡して WheelEvent コンストラクタを使用します。"
type: docs

url: /ja/java/com.aspose.html.dom.events/wheelevent/
---
## WheelEvent class

WheelEvent インターフェイスは、ホイールイベントに関連する特定のコンテキスト情報を提供します。WheelEvent インターフェイスのインスタンスを作成するには、WheelEvent コンストラクタを使用し、オプションの WheelEventInit 辞書を渡します。

```java
public class WheelEvent : MouseEvent
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [WheelEvent](wheelevent/#constructor)(String) | `WheelEvent` クラスの新しいインスタンスを初期化します。 |
| [WheelEvent](wheelevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/mouseevent/altkey/) altKey 属性を参照してください。 |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) イベントがバブリングイベントかどうかを示すために使用されます。イベントがバブリングできる場合は true、そうでない場合は false です。 |
| [getButton](../../com.aspose.html.dom.events/mouseevent/button/) マウスボタンの押下または解放によって引き起こされるマウスイベントでは、button はどのポインターデバイスのボタンが状態変化したかを示すために使用されなければなりません。 |
| [getButtons](../../com.aspose.html.dom.events/mouseevent/buttons/) 任意のマウスイベント中、buttons は現在押されているマウスボタンの組み合わせをビットマスクで表すために使用されなければなりません。 |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) イベントのデフォルトアクションを防止できるかどうかを示すために使用されます。デフォルトアクションが防止できる場合は true、そうでない場合は false です。 |
| [getClientX](../../com.aspose.html.dom.events/mouseevent/clientx/) イベントが発生した水平座標で、イベントに関連付けられたビューポートを基準とします。 |
| [getClientY](../../com.aspose.html.dom.events/mouseevent/clienty/) イベントが発生した垂直座標で、イベントに関連付けられたビューポートを基準とします。 |
| [getCtrlKey](../../com.aspose.html.dom.events/mouseevent/ctrlkey/) ctrlKey 属性を参照してください。 |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) 現在処理中の [`IEventListener`](../ieventlistener/) を持つ [`IEventTarget`](../ieventtarget/) を示すために使用されます。これはキャプチャおよびバブリング時に特に有用です。 |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) cancelable 属性が true のときに preventDefault() が呼び出された場合は true を返し、そうでない場合は false を返します。 |
| [getDeltaMode](../../com.aspose.html.dom.events/wheelevent/deltamode/) deltaMode 属性は、デルタ値の測定単位を示す情報を含みます。デフォルト値は DOM_DELTA_PIXEL（ピクセル）です。 |
| [getDeltaX](../../com.aspose.html.dom.events/wheelevent/deltax/) ホイールイベントのデフォルト動作がスクロールであるユーザーエージェントでは、イベントがキャンセルされない場合にスクロールされる x 軸方向の測定値（ピクセル、行、またはページ）でなければなりません。そうでない場合、これはホイールデバイスが x 軸周りに動くことの実装固有の測定値（ピクセル、行、またはページ）です。 |
| [getDeltaY](../../com.aspose.html.dom.events/wheelevent/deltay/) ホイールイベントのデフォルト動作がスクロールであるユーザーエージェントでは、イベントがキャンセルされない場合にスクロールされる y 軸方向の測定値（ピクセル、行、またはページ）でなければなりません。そうでない場合、これはホイールデバイスが y 軸周りに動くことの実装固有の測定値（ピクセル、行、またはページ）です。 |
| [getDeltaZ](../../com.aspose.html.dom.events/wheelevent/deltaz/) ホイールイベントのデフォルト動作がスクロールであるユーザーエージェントでは、イベントがキャンセルされない場合にスクロールされる z 軸方向の測定値（ピクセル、行、またはページ）でなければなりません。そうでない場合、これはホイールデバイスが z 軸周りに動くことの実装固有の測定値（ピクセル、行、またはページ）です。 |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) イベントの種類に応じた詳細情報を指定します。 |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) 現在評価されているイベントフローのフェーズを示すために使用されます。 |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) isTrusted属性は初期化された値を返す必要があります。イベントが作成されるとき、この属性はfalseに初期化されなければなりません。 |
| [getMetaKey](../../com.aspose.html.dom.events/mouseevent/metakey/) metaKey 属性を参照してください。 |
| [getRelatedTarget](../../com.aspose.html.dom.events/mouseevent/relatedtarget/) UIイベントの種類に応じて、二次的なEventTargetを識別するために使用されます。 |
| [getScreenX](../../com.aspose.html.dom.events/mouseevent/screenx/) イベントが発生した画面座標系の原点に対する水平座標です。 |
| [getScreenY](../../com.aspose.html.dom.events/mouseevent/screeny/) イベントが発生した画面座標系の原点に対する垂直座標です。 |
| [getShiftKey](../../com.aspose.html.dom.events/mouseevent/shiftkey/) shiftKey属性を参照してください。 |
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

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [DOM_DELTA_LINE](../../com.aspose.html.dom.events/wheelevent/dom_delta_line/) | デルタの測定単位は個々のテキスト行でなければなりません。これは多くのフォームコントロールで当てはまります。 |
| const [DOM_DELTA_PAGE](../../com.aspose.html.dom.events/wheelevent/dom_delta_page/) | デルタの測定単位はページでなければなりません。単一の画面として、または区切られたページとして定義されます。 |
| const [DOM_DELTA_PIXEL](../../com.aspose.html.dom.events/wheelevent/dom_delta_pixel/) | デルタの測定単位はピクセルでなければなりません。これはほとんどのオペレーティングシステムおよび実装構成で最も一般的なケースです。 |

### 関連項目

* class [MouseEvent](../mouseevent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
