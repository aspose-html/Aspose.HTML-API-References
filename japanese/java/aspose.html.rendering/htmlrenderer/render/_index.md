---
title: "HtmlRenderer.Render"
second_title: "Aspose.HTML for Java API リファレンス"
description: "HtmlRenderer メソッド。複数の HTMLDocument を特定の IDevice にレンダリングするメソッドを定義します。"
type: docs

url: /ja/java/com.aspose.html.rendering/htmlrenderer/render/
---
## Render(IDevice, TimeSpan, params HTMLDocument[]) {#render_6}

複数の [`HTMLDocument`](../../../com.aspose.html/htmldocument/) を特定の [`IDevice`](../../idevice/) にレンダリングするメソッドを定義します。

```java
public void Render(IDevice device, TimeSpan timeout, params HTMLDocument[] sources)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| デバイス | IDevice | 出力デバイスです。 |
| タイムアウト | TimeSpan | 待機するミリ秒数を表す TimeSpan、または無期限に待機することを表す -1 ミリ秒の TimeSpan を表します。 |
| ソース | HTMLDocument[] | レンダリングする HTML ドキュメントです。 |

### 関連項目

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params HTMLDocument[]) {#render_5}

複数の [`HTMLDocument`](../../../com.aspose.html/htmldocument/) を特定の [`IDevice`](../../idevice/) にレンダリングするメソッドを定義します。操作のキャンセルを要求するためにキャンセルトークンを使用します。

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params HTMLDocument[] sources)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| デバイス | IDevice | 出力デバイスです。 |
| cancellationToken | CancellationToken | タスクの完了を待機中に監視するための CancellationToken。 |
| ソース | HTMLDocument[] | レンダリングする HTML ドキュメントです。 |

### 関連項目

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
