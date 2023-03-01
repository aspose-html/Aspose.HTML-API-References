---
title: Class WheelEvent
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Events.WheelEvent クラス. WheelEvent インターフェイスはホイール イベントに関連する特定のコンテキスト情報を提供します WheelEvent インターフェイスのインスタンスを作成するにはWheelEvent コンストラクターを使用してオプションの WheelEventInit 辞書を渡します
type: docs
weight: 860
url: /ja/net/aspose.html.dom.events/wheelevent/
---
## WheelEvent class

WheelEvent インターフェイスは、ホイール イベントに関連する特定のコンテキスト情報を提供します。 WheelEvent インターフェイスのインスタンスを作成するには、WheelEvent コンストラクターを使用して、オプションの WheelEventInit 辞書を渡します。

```csharp
public class WheelEvent : MouseEvent
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [WheelEvent](wheelevent/#constructor)(string) | の新しいインスタンスを初期化します`WheelEvent` class. |
| [WheelEvent](wheelevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | の新しいインスタンスを初期化します`WheelEvent` class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/mouseevent/altkey/) { get; } | altKey 属性を参照してください。 |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | イベントがバブリング イベントかどうかを示すために使用されます。イベントがバブルできる場合、値は true、それ以外の場合、値は false. |
| [Button](../../aspose.html.dom.events/mouseevent/button/) { get; } | マウス ボタンを押したり離したりすることによって発生するマウス イベントの間、ボタンを使用して、どのポインター デバイス ボタンの状態が変化したかを示す必要があります。 |
| [Buttons](../../aspose.html.dom.events/mouseevent/buttons/) { get; } | マウス イベントの間、現在押されているマウス ボタンの組み合わせを示すためにボタンを使用する必要があります。 |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | イベントのデフォルト アクションを防止できるかどうかを示すために使用されます。デフォルト アクションを防止できる場合、値は true であり、それ以外の場合、値は false. です。 |
| [ClientX](../../aspose.html.dom.events/mouseevent/clientx/) { get; } | イベントに関連付けられたビューポートを基準とした、イベントが発生した水平座標。 |
| [ClientY](../../aspose.html.dom.events/mouseevent/clienty/) { get; } | イベントに関連付けられたビューポートを基準とした、イベントが発生した垂直座標。 |
| [CtrlKey](../../aspose.html.dom.events/mouseevent/ctrlkey/) { get; } | ctrlKey 属性を参照してください。 |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | を示すために使用されます[`IEventTarget`](../ieventtarget/)だれの[`IEventListener`](../ieventlistener/) は現在処理中です. これは、キャプチャとバブリング中に特に役立ちます. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | cancelable 属性値が true のときに preventDefault() が呼び出された場合は true を返し、それ以外の場合は false を返します。 |
| [DeltaMode](../../aspose.html.dom.events/wheelevent/deltamode/) { get; } | deltaMode 属性には、デルタ値の測定単位の指示が含まれています。デフォルト値は DOM_DELTA_PIXEL (ピクセル). です。 |
| [DeltaX](../../aspose.html.dom.events/wheelevent/deltax/) { get; } | wheel イベントのデフォルト アクションがスクロールであるユーザー エージェントでは、値は、イベントがキャンセルされない場合にスクロールされる x 軸に沿った測定値 (ピクセル、ライン、またはページ単位) でなければなりません。それ以外の場合、これは x 軸を中心としたホイール デバイスの動きの実装固有の測定値 (ピクセル、ライン、またはページ単位) です。 |
| [DeltaY](../../aspose.html.dom.events/wheelevent/deltay/) { get; } | wheel イベントのデフォルト アクションがスクロールであるユーザー エージェントでは、値は、イベントがキャンセルされない場合にスクロールされる y 軸に沿った測定値 (ピクセル、ライン、またはページ単位) でなければなりません。それ以外の場合、これは、y 軸を中心としたホイール デバイスの動きの実装固有の測定値 (ピクセル、ライン、またはページ単位) です。 |
| [DeltaZ](../../aspose.html.dom.events/wheelevent/deltaz/) { get; } | wheel イベントのデフォルト アクションがスクロールであるユーザー エージェントでは、値は、イベントがキャンセルされない場合にスクロールされる z 軸に沿った測定値 (ピクセル、ライン、またはページ単位) でなければなりません。それ以外の場合、これは z 軸を中心としたホイール デバイスの動きの実装固有の測定値 (ピクセル、ライン、またはページ単位) です。 |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | イベントのタイプに応じて、イベントに関する詳細情報を指定します。 |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | イベントフローのどのフェーズが現在評価されているかを示すために使用されます. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | isTrusted 属性は、初期化された値を返す必要があります。イベントが作成されたら、属性を false. に初期化する必要があります。 |
| [MetaKey](../../aspose.html.dom.events/mouseevent/metakey/) { get; } | metaKey 属性を参照してください。 |
| [RelatedTarget](../../aspose.html.dom.events/mouseevent/relatedtarget/) { get; } | イベントのタイプに応じて、UI イベントに関連するセカンダリ EventTarget を識別するために使用されます。 |
| [ScreenX](../../aspose.html.dom.events/mouseevent/screenx/) { get; } | 画面座標系の原点を基準とした、イベントが発生した水平座標。 |
| [ScreenY](../../aspose.html.dom.events/mouseevent/screeny/) { get; } | 画面座標系の原点を基準とした、イベントが発生した垂直座標。 |
| [ShiftKey](../../aspose.html.dom.events/mouseevent/shiftkey/) { get; } | shiftKey 属性を参照してください。 |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | を示すために使用されます[`IEventTarget`](../ieventtarget/)イベントが最初にディスパッチされた先. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | イベントが作成された時刻 (エポックからのミリ秒単位) を指定するために使用されます。 、値 0 が返されます。 エポック時間の例は、システムの開始時間または 1970 年 1 月 1 日の 0:0:0 UTC です。 |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | イベントの名前 (大文字と小文字を区別しない)。名前は XML 名でなければなりません. |
| [View](../../aspose.html.dom.events/uievent/view/) { get; } | ビュー属性は、イベントが生成されたウィンドウを識別します. この属性の初期化されていない値は null でなければなりません. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | このメソッドは、ECMAScript オブジェクトを取得するために使用されますType. |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | [`InitEvent`](../event/initevent/)メソッドは、の値を初期化するために使用されます[`Event`](../event/) the で作成[`IDocumentEvent`](../idocumentevent/)インターフェイス. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | イベントがキャンセル可能な場合、[`PreventDefault`](../event/preventdefault/)メソッドは、イベントがキャンセルされることを示すために使用されます。 は、イベントの結果として実装によって通常実行されるデフォルト アクションが発生しないことを意味します。 |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | このメソッドを呼び出すと、イベントが現在のイベントリスナーの後に登録されたイベントリスナーに到達するのを防ぎ、ツリーでディスパッチされたときに、イベントが他のオブジェクトに到達するのを防ぎます. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | [`StopPropagation`](../event/stoppropagation/)メソッドが使用され、イベント フロー中にイベントがさらに伝播するのを防ぎます。 |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [DOM_DELTA_LINE](../../aspose.html.dom.events/wheelevent/dom_delta_line/) | デルタの測定単位は、個々のテキスト行でなければなりません。これは、多くのフォーム コントロールの場合です。 |
| const [DOM_DELTA_PAGE](../../aspose.html.dom.events/wheelevent/dom_delta_page/) | デルタの測定単位は、単一の画面または境界のあるページとして定義されたページでなければなりません. |
| const [DOM_DELTA_PIXEL](../../aspose.html.dom.events/wheelevent/dom_delta_pixel/) | デルタの測定単位はピクセルでなければなりません。これは、ほとんどのオペレーティング システムおよび実装構成で最も一般的なケースです。 |

### 関連項目

* class [MouseEvent](../mouseevent/)
* 名前空間 [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* 組み立て [Aspose.HTML](../../)


