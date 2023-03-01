---
title: Class SVGZoomEvent
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Svg.Events.SVGZoomEvent クラス. ズーム イベントはSVG ドキュメント フラグメントの現在のビューを再スケーリングするアクションをユーザーが開始したときに発生しますイベント ハンドラーはsvg 要素でのみ認識されます
type: docs
weight: 1330
url: /ja/net/aspose.html.dom.svg.events/svgzoomevent/
---
## SVGZoomEvent class

ズーム イベントは、SVG ドキュメント フラグメントの現在のビューを再スケーリングするアクションをユーザーが開始したときに発生します。イベント ハンドラーは、'svg' 要素でのみ認識されます。

```csharp
public class SVGZoomEvent : Event
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | イベントがバブリング イベントかどうかを示すために使用されます。イベントがバブルできる場合、値は true、それ以外の場合、値は false. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | イベントのデフォルト アクションを防止できるかどうかを示すために使用されます。デフォルト アクションを防止できる場合、値は true であり、それ以外の場合、値は false. です。 |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | を示すために使用されます[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/)だれの[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) は現在処理中です. これは、キャプチャとバブリング中に特に役立ちます. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | cancelable 属性値が true のときに preventDefault() が呼び出された場合は true を返し、それ以外の場合は false を返します。 |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | イベントフローのどのフェーズが現在評価されているかを示すために使用されます. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | isTrusted 属性は、初期化された値を返す必要があります。イベントが作成されたら、属性を false. に初期化する必要があります。 |
| [NewScale](../../aspose.html.dom.svg.events/svgzoomevent/newscale/) { get; } | ズーム操作が処理された後に適用される倍率。 |
| [NewTranslate](../../aspose.html.dom.svg.events/svgzoomevent/newtranslate/) { get; } | ズーム操作が処理された後に配置される変換値. SVGPoint オブジェクトは読み取り専用です. |
| [PreviousScale](../../aspose.html.dom.svg.events/svgzoomevent/previousscale/) { get; } | ズーム操作が発生する前に設定されていた、以前のズーム操作からの倍率。 |
| [PreviousTranslate](../../aspose.html.dom.svg.events/svgzoomevent/previoustranslate/) { get; } | ズーム操作が発生する前に設定されていた、以前のズーム操作からの変換値。 SVGPoint オブジェクトは読み取り専用です。 |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | を示すために使用されます[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/)イベントが最初にディスパッチされた先. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | イベントが作成された時刻 (エポックからのミリ秒単位) を指定するために使用されます。 、値 0 が返されます。 エポック時間の例は、システムの開始時間または 1970 年 1 月 1 日の 0:0:0 UTC です。 |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | イベントの名前 (大文字と小文字を区別しない)。名前は XML 名でなければなりません. |
| [ZoomRectScreen](../../aspose.html.dom.svg.events/svgzoomevent/zoomrectscreen/) { get; } | 画面単位で指定されたズーム四角形。 SVGRect オブジェクトは読み取り専用です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | このメソッドは、ECMAScript オブジェクトを取得するために使用されますType. |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | [`InitEvent`](../../aspose.html.dom.events/event/initevent/)メソッドは、の値を初期化するために使用されます[`Event`](../../aspose.html.dom.events/event/) the で作成[`IDocumentEvent`](../../aspose.html.dom.events/idocumentevent/)インターフェイス. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | イベントがキャンセル可能な場合、[`PreventDefault`](../../aspose.html.dom.events/event/preventdefault/)メソッドは、イベントがキャンセルされることを示すために使用されます。 は、イベントの結果として実装によって通常実行されるデフォルト アクションが発生しないことを意味します。 |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | このメソッドを呼び出すと、イベントが現在のイベントリスナーの後に登録されたイベントリスナーに到達するのを防ぎ、ツリーでディスパッチされたときに、イベントが他のオブジェクトに到達するのを防ぎます. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | [`StopPropagation`](../../aspose.html.dom.events/event/stoppropagation/)メソッドが使用され、イベント フロー中にイベントがさらに伝播するのを防ぎます。 |

### 関連項目

* class [Event](../../aspose.html.dom.events/event/)
* 名前空間 [Aspose.Html.Dom.Svg.Events](../../aspose.html.dom.svg.events/)
* 組み立て [Aspose.HTML](../../)


