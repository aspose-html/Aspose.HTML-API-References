---
title: "IWindow インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.window.IWindow インターフェイス。window オブジェクトは DOM ドキュメントを含むウィンドウを表します。"
type: docs

url: /ja/java/com.aspose.html.window/iwindow/
---
## IWindow interface

window オブジェクトは、DOM ドキュメントを含むウィンドウを表します。

```java
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getDocument](../../com.aspose.html.window/iwindow/document/) document 属性は Window オブジェクトの最新の Document オブジェクトを返す必要があります。 |
| [getFrameElement](../../com.aspose.html.window/iwindow/frameelement/) Document の frameElement オブジェクト。 |
| [getLocalStorage](../../com.aspose.html.window/iwindow/localstorage/) ユーザーエージェントにキー/バリューのペアを保存できる Storage オブジェクトを返します。 |
| [getLocation](../../com.aspose.html.window/iwindow/location/) Window インターフェイスの location 属性は、その Window オブジェクトの Document に対する Location オブジェクトを返す必要があります。 |
[getName]
[setName] The name attribute of the Window object must, on getting, return the current name of the browsing context, and, on setting, set the name of the browsing context to the new value. |
| [getOpener](../../com.aspose.html.window/iwindow/opener/) Window オブジェクトの opener IDL 属性は、取得時に、現在のブラウジングコンテキストが作成された元のブラウジングコンテキスト（その opener ブラウジングコンテキスト）が存在し、かつ利用可能で、かつ現在のブラウジングコンテキストがその opener を放棄していない場合、WindowProxy オブジェクトを返します。それ以外の場合は null を返します。設定時に新しい値が null の場合、現在のブラウジングコンテキストは opener を放棄しなければなりません。新しい値がそれ以外の場合、ユーザーエージェントは Window オブジェクトの [[DefineOwnProperty]] 内部メソッドを呼び出し、プロパティ名 "opener" をプロパティキーとして渡し、プロパティ記述子 { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } を使用します。ここで value は新しい値です。 |
| [getParent](../../com.aspose.html.window/iwindow/parent/) ブラウジングコンテキスト b 内の Document の Window オブジェクトの parent IDL 属性は、親ブラウジングコンテキストが存在する場合（すなわち b が子ブラウジングコンテキストである場合）にはその WindowProxy オブジェクトを返し、存在しない場合（すなわちトップレベルまたは分離されたネストされたブラウジングコンテキストの場合）にはコンテキスト b 自身の WindowProxy オブジェクトを返します。 |
| [getSelf](../../com.aspose.html.window/iwindow/self/) Window オブジェクトのブラウジングコンテキストの WindowProxy オブジェクトを返します。 |
| [getTop](../../com.aspose.html.window/iwindow/top/) ブラウジングコンテキスト b 内の Document の Window オブジェクトの top IDL 属性は、トップレベルのブラウジングコンテキストが存在する場合はその WindowProxy オブジェクト（それがトップレベルコンテキスト自身であれば自身の WindowProxy）を返し、存在しない場合は自身の WindowProxy オブジェクトを返します（例：分離されたネストされたコンテキストの場合）。 |
| [getWindow](../../com.aspose.html.window/iwindow/window/) Window オブジェクトのブラウジングコンテキストの WindowProxy オブジェクトを返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [alert](../../com.aspose.html.window/iwindow/alert/)(String) | 指定されたメッセージでモーダルアラートを表示し、ユーザーが閉じるまで待機します。 |
| [atob](../../com.aspose.html.window/iwindow/atob/)(String) | 入力データを、Base64 エンコードされたバイナリデータを含む Unicode 文字列の形で受け取り、デコードして、U+0000 から U+00FF の範囲の文字で構成された文字列を返します。各文字は 0x00 から 0xFF のバイナリバイトを表します。 |
| [btoa](../../com.aspose.html.window/iwindow/btoa/)(String) | 入力データを、U+0000 から U+00FF の範囲の文字のみを含む Unicode 文字列の形で受け取り、各文字が 0x00 から 0xFF のバイナリバイトを表すものとして、Base64 表現に変換し、その結果を返します。 |
| [confirm](../../com.aspose.html.window/iwindow/confirm/)(String) | 指定されたメッセージでモーダルの OK/Cancel プロンプトを表示し、ユーザーが操作するまで待機し、ユーザーが OK をクリックした場合は true、Cancel をクリックした場合は false を返します。 |
| [matchMedia](../../com.aspose.html.window/iwindow/matchmedia/)(String) | 新しい MediaQueryList オブジェクトを返します。このオブジェクトは、ドキュメントがメディアクエリ文字列に一致するかどうかを判定したり、一致（または不一致）したときに検出するためにドキュメントを監視したりするのに使用できます。CSSOM View Module 仕様をご覧ください: [https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface](https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface) |
| [prompt](../../com.aspose.html.window/iwindow/prompt/)(String, String) | 指定されたメッセージでモーダルのテキストフィールドプロンプトを表示し、ユーザーが操作するまで待機し、ユーザーが入力した値を返します。ユーザーがキャンセルした場合は null を返します。第2引数が指定されている場合、その値がデフォルトとして使用されます。 |

### 関連項目

* interface [IDocumentView](../../com.aspose.html.dom.views/idocumentview/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../com.aspose.html.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
