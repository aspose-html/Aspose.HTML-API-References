---
title: "SVGZoomEvent クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.svg.events.SVGZoomEvent クラス。ユーザーがアクションを開始し、SVG ドキュメントフラグメントの現在のビューが再スケーリングされるとズームイベントが発生します。イベントハンドラは svg 要素でのみ認識されます。"
type: docs

url: /ja/java/com.aspose.html.dom.svg.events/svgzoomevent/
---
## SVGZoomEvent class

ズームイベントは、ユーザーが現在の SVG ドキュメントフラグメントのビューを再スケーリングさせるアクションを開始したときに発生します。イベントハンドラは ‘svg’ 要素でのみ認識されます。

```java
public class SVGZoomEvent : Event
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) イベントがバブリングイベントかどうかを示すために使用されます。イベントがバブリングできる場合は true、そうでない場合は false です。 |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) イベントのデフォルトアクションを防止できるかどうかを示すために使用されます。デフォルトアクションが防止できる場合は true、そうでない場合は false です。 |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) 現在処理中の [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) の [`IEventListener`](../../com.aspose.html.dom.events/ieventlistener/) を示すために使用されます。キャプチャおよびバブリング時に特に有用です。 |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) cancelable 属性が true のときに preventDefault() が呼び出された場合は true を返し、そうでない場合は false を返します。 |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) 現在評価されているイベントフローのフェーズを示すために使用されます。 |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) isTrusted属性は初期化された値を返す必要があります。イベントが作成されるとき、この属性はfalseに初期化されなければなりません。 |
| [getNewScale](../../com.aspose.html.dom.svg.events/svgzoomevent/newscale/) ズーム操作が処理された後に適用されるスケール係数です。 |
| [getNewTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/newtranslate/) ズーム操作が処理された後に適用される平行移動値です。SVGPoint オブジェクトは読み取り専用です。 |
| [getPreviousScale](../../com.aspose.html.dom.svg.events/svgzoomevent/previousscale/) ズーム操作が発生する前に適用されていた、過去のズーム操作からのスケール係数です。 |
| [getPreviousTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/previoustranslate/) ズーム操作が発生する前に適用されていた、過去のズーム操作からの平行移動値です。SVGPoint オブジェクトは読み取り専用です。 |
| [getTarget](../../com.aspose.html.dom.events/event/target/) イベントが元々ディスパッチされた [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) を示すために使用されます。 |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) イベントが作成された時刻（エポックからのミリ秒）を指定するために使用されます。一部のシステムがこの情報を提供しない場合、timeStampの値はすべてのイベントで利用できないことがあります。利用できない場合は0が返されます。エポック時刻の例としてはシステム起動時やUTC 1970年1月1日 0:0:0 があります。 |
| [getType](../../com.aspose.html.dom.events/event/type/) イベントの名前（大文字小文字を区別しない）。名前はXML名でなければなりません。 |
| [getZoomRectScreen](../../com.aspose.html.dom.svg.events/svgzoomevent/zoomrectscreen/) 画面単位で指定されたズーム矩形です。SVGRect オブジェクトは読み取り専用です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | この [`InitEvent`](../../com.aspose.html.dom.events/event/initevent/) メソッドは、[`IDocumentEvent`](../../com.aspose.html.dom.events/idocumentevent/) インターフェイスを介して作成された [`Event`](../../com.aspose.html.dom.events/event/) の値を初期化するために使用されます。 |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | イベントがキャンセル可能な場合、[`PreventDefault`](../../com.aspose.html.dom.events/event/preventdefault/) メソッドは、イベントをキャンセルすることを示すために使用されます。つまり、イベントの結果として実装が通常行うデフォルトの動作は実行されません。 |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | このメソッドを呼び出すと、現在のリスナーの後に登録されたすべてのイベントリスナーにイベントが到達するのを防ぎ、ツリー内でディスパッチされた場合は他のオブジェクトにもイベントが到達するのを防止します。 |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | この [`StopPropagation`](../../com.aspose.html.dom.events/event/stoppropagation/) メソッドは、イベントフロー中のイベントのさらなる伝播を防止するために使用されます。 |

### 関連項目

* class [Event](../../com.aspose.html.dom.events/event/)
* package [com.aspose.html.dom.svg.events](../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../)
