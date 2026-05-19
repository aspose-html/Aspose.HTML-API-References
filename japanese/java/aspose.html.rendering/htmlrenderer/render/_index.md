---
title: "HtmlRenderer.Render"
second_title: "Aspose.HTML for Java API リファレンス"
description: "HtmlRenderer メソッド。複数の HTMLDocument を特定の IDevice にレンダリングするメソッドを定義します。"
type: docs

url: /ja/java/com.aspose.html.rendering/htmlrenderer/render/
---
## Render(IDevice, TimeSpan, params HTMLDocument[]) {#render_6}

複数の [`HTMLDocument`](../../../com.aspose.html/htmldocument/)s を特定の [`IDevice`](../../idevice/) にレンダリングするメソッドを定義します。

```java
public void Render(IDevice device, TimeSpan timeout, params HTMLDocument[] sources)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| デバイス | IDevice | 出力デバイスです。 |
| タイムアウト | TimeSpan | 待機するミリ秒数を表す TimeSpan、または無期限に待機することを示す -1 ミリ秒の TimeSpan です。 |
| ソース | HTMLDocument[] | レンダリングする HTML ドキュメント。 |

### 関連項目

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params HTMLDocument[]) {#render_5}

キャンセル トークンを使用して操作のキャンセルを要求する、複数の [`HTMLDocument`](../../../com.aspose.html/htmldocument/)s を特定の [`IDevice`](../../idevice/) にレンダリングするメソッドを定義します。

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params HTMLDocument[] sources)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| デバイス | IDevice | 出力デバイスです。 |
| cancellationToken | CancellationToken | タスクの完了を待機中に監視するための CancellationToken。 |
| ソース | HTMLDocument[] | レンダリングする HTML ドキュメント。 |

### 関連項目

* interface [IDevice](../../idevice/)
* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [HtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
