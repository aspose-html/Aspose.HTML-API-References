---
title: "IWindowTimers インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.window.IWindowTimers インターフェイス。作者がタイマーに基づくコールバックをスケジュールできるようにします。"
type: docs

url: /ja/java/com.aspose.html.window/iwindowtimers/
---
## IWindowTimers interface

作者がタイマーに基づくコールバックをスケジュールできるようにします。

```java
public interface IWindowTimers
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [clearInterval](../../com.aspose.html.window/iwindowtimers/clearinterval/)(int) | handle で識別される setInterval() に設定されたタイムアウトをキャンセルします。 |
| [clearTimeout](../../com.aspose.html.window/iwindowtimers/cleartimeout/)(int) | handle で識別される setTimeout() に設定されたタイムアウトをキャンセルします。 |
| [setInterval](../../com.aspose.html.window/iwindowtimers/setinterval/)(object, int, params object[]) | タイムアウトミリ秒ごとにハンドラを実行するタイムアウトをスケジュールします。引数はそのままハンドラに渡されます。 |
| [setTimeout](../../com.aspose.html.window/iwindowtimers/settimeout/)(object, int, params object[]) | タイムアウトミリ秒後にハンドラを実行するタイムアウトをスケジュールします。引数はそのままハンドラに渡されます。 |

### 関連項目

* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
