---
title: IWindow.Opener
second_title: Aspose.HTML for .NET API リファレンス
description: IWindow 財産. Window オブジェクトのオープナー IDL 属性は取得時に現在のブラウジング コンテキストが作成されたブラウジング コンテキスト そのオープナー ブラウジング コンテキスト の WindowProxy オブジェクトを返す必要があります現在のブラウジング コンテキストはオープナーを否定していませんそれ以外の場合はnull を返す必要があります設定時に新しい値が null の場合現在のブラウジング コンテキストはそのオープナーを否認する必要があります新しい値がそれ以外の場合ユーザー エージェントは Window オブジェクトの DefineOwnProperty 内部メソッドを呼び出しプロパティ名openerをプロパティ キーとして渡しProperty Descriptor  Value value  Writable true Enumerable true Configurable true  はプロパティ記述子として値は新しい値です.
type: docs
weight: 50
url: /ja/net/aspose.html.window/iwindow/opener/
---
## IWindow.Opener property

Window オブジェクトのオープナー IDL 属性は、取得時に、現在のブラウジング コンテキストが作成されたブラウジング コンテキスト (そのオープナー ブラウジング コンテキスト) の WindowProxy オブジェクトを返す必要があります。現在のブラウジング コンテキストはオープナーを否定していません。それ以外の場合は、null を返す必要があります。設定時に、新しい値が null の場合、現在のブラウジング コンテキストはそのオープナーを否認する必要があります。新しい値がそれ以外の場合、ユーザー エージェントは Window オブジェクトの [[DefineOwnProperty]] 内部メソッドを呼び出し、プロパティ名「opener」をプロパティ キーとして渡し、Property Descriptor { [[Value]]: value , [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } はプロパティ記述子として、値は新しい値です.

```csharp
public IWindow Opener { get; }
```

### プロパティ値

オープナー.

### 関連項目

* interface [IWindow](../)
* 名前空間 [Aspose.Html.Window](../../iwindow/)
* 組み立て [Aspose.HTML](../../../)


