---
title: Interface IWindow
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Window.IWindow インターフェース. window オブジェクトはDOM ドキュメントを含むウィンドウを表します
type: docs
weight: 5850
url: /ja/net/aspose.html.window/iwindow/
---
## IWindow interface

window オブジェクトは、DOM ドキュメントを含むウィンドウを表します。

```csharp
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Document](../../aspose.html.window/iwindow/document/) { get; } | document 属性は Window オブジェクトの最新の Document オブジェクトを返さなければなりません. |
| [FrameElement](../../aspose.html.window/iwindow/frameelement/) { get; } | Document の frameElement オブジェクト。 |
| [Location](../../aspose.html.window/iwindow/location/) { get; } | Window インターフェイスの location 属性は、その Window オブジェクトの Document. の Location オブジェクトを返す必要があります。 |
| [Name](../../aspose.html.window/iwindow/name/) { get; set; } | Window オブジェクトの name 属性は、取得時にブラウジング コンテキストの現在の名前を返し、設定時にブラウジング コンテキストの名前を新しい値に設定する必要があります。 |
| [Opener](../../aspose.html.window/iwindow/opener/) { get; } | Window オブジェクトのオープナー IDL 属性は、取得時に、現在のブラウジング コンテキストが作成されたブラウジング コンテキスト (そのオープナー ブラウジング コンテキスト) の WindowProxy オブジェクトを返す必要があります。現在のブラウジング コンテキストはオープナーを否定していません。それ以外の場合は、null を返す必要があります。設定時に、新しい値が null の場合、現在のブラウジング コンテキストはそのオープナーを否認する必要があります。新しい値がそれ以外の場合、ユーザー エージェントは Window オブジェクトの [[DefineOwnProperty]] 内部メソッドを呼び出し、プロパティ名「opener」をプロパティ キーとして渡し、Property Descriptor { [[Value]]: value , [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } はプロパティ記述子として、値は新しい値です. |
| [Parent](../../aspose.html.window/iwindow/parent/) { get; } | ブラウジング コンテキスト b の Document の Window オブジェクトの親 IDL 属性は、親ブラウジング コンテキストが存在する場合 (つまり、b が子ブラウジング コンテキストの場合)、その WindowProxy オブジェクト、またはブラウジングの WindowProxy オブジェクトを返す必要があります。コンテキスト b 自体。 |
| [Self](../../aspose.html.window/iwindow/self/) { get; } | Window オブジェクトのブラウジング コンテキストの WindowProxy オブジェクトを返します。 |
| [Top](../../aspose.html.window/iwindow/top/) { get; } | ブラウジング コンテキスト b の Document の Window オブジェクトの最上位の IDL 属性は、最上位のブラウジング コンテキストの WindowProxy オブジェクトを返さなければなりません (それが最上位のブラウジング コンテキスト自体である場合は、それ自体の WindowProxy オブジェクトになります)。それ以外の場合は、1 つ、または独自の WindowProxy オブジェクトがあります (たとえば、切り離されたネストされたブラウジング コンテキストの場合)。 |
| [Window](../../aspose.html.window/iwindow/window/) { get; } | Window オブジェクトのブラウジング コンテキストの WindowProxy オブジェクトを返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Alert](../../aspose.html.window/iwindow/alert/)(string) | 指定されたメッセージでモーダル アラートを表示し、ユーザーがそれを閉じるのを待ちます |
| [Confirm](../../aspose.html.window/iwindow/confirm/)(string) | 指定されたメッセージとともにモーダル OK/キャンセル プロンプトを表示し、ユーザーがそれを閉じるのを待ち、ユーザーが [OK] をクリックした場合は true を返し、ユーザーが [キャンセル] をクリックした場合は false を返します。 |
| [Prompt](../../aspose.html.window/iwindow/prompt/)(string, string) | 指定されたメッセージとともにモーダル テキスト フィールド プロンプトを表示し、ユーザーがそれを閉じるのを待って、ユーザーが入力した値を返します。ユーザーがプロンプトをキャンセルすると、代わりに null が返されます。 2 番目の引数が存在する場合、指定された値がデフォルトとして使用されます。 |

### 関連項目

* interface [IDocumentView](../../aspose.html.dom.views/idocumentview/)
* interface [IEventTarget](../../aspose.html.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../aspose.html.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* 名前空間 [Aspose.Html.Window](../../aspose.html.window/)
* 組み立て [Aspose.HTML](../../)


