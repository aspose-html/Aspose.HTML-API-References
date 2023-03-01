---
title: Interface IWindowTimers
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Window.IWindowTimers インターフェース. 作成者がタイマーベースのコールバックをスケジュールできるようにします.
type: docs
weight: 5870
url: /ja/net/aspose.html.window/iwindowtimers/
---
## IWindowTimers interface

作成者がタイマーベースのコールバックをスケジュールできるようにします.

```csharp
public interface IWindowTimers
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [ClearInterval](../../aspose.html.window/iwindowtimers/clearinterval/)(int) | handle で識別される setInterval() で設定されたタイムアウトをキャンセルします |
| [ClearTimeout](../../aspose.html.window/iwindowtimers/cleartimeout/)(int) | handle. で識別される setTimeout() で設定されたタイムアウトをキャンセルします。 |
| [SetInterval](../../aspose.html.window/iwindowtimers/setinterval/)(object, int, params object[]) | タイムアウト ミリ秒ごとにハンドラを実行するためのタイムアウトをスケジュールします。すべての引数は、handler. に直接渡されます。 |
| [SetTimeout](../../aspose.html.window/iwindowtimers/settimeout/)(object, int, params object[]) | timeout ミリ秒後にハンドラーを実行するタイムアウトをスケジュールします。すべての引数は、handler. に直接渡されます。 |

### 関連項目

* 名前空間 [Aspose.Html.Window](../../aspose.html.window/)
* 組み立て [Aspose.HTML](../../)


