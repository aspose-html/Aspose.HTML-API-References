---
title: "SvgRenderer.Render"
second_title: "Aspose.HTML for Java API リファレンス"
description: "SvgRenderer メソッド。複数の SVGDocument を特定の IDevice にレンダリングするメソッドを定義します。リソースの読み込みのためのネットワーク操作やアクティブなタイマー、アニメーションタスクが存在せず、指定されたタイムアウトが経過した時にレンダリングが実行されます。"
type: docs

url: /ja/java/com.aspose.html.rendering/svgrenderer/render/
---
## Render(IDevice, TimeSpan, params SVGDocument[]) {#render_6}

複数の [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を特定の [`IDevice`](../../idevice/) にレンダリングするメソッドを定義します。リソースの読み込みのためのネットワーク操作やアクティブなタイマー、アニメーションタスクが存在せず、指定されたタイムアウトが経過した時にレンダリングが実行されます。

```java
public void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| デバイス | IDevice | 出力デバイスです。 |
| タイムアウト | TimeSpan | 待機するミリ秒数を表す TimeSpan、または無期限に待機することを示す -1 ミリ秒の TimeSpan です。 |
| ドキュメント | SVGDocument[] | レンダリングするドキュメント。 |

### 関連項目

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params SVGDocument[]) {#render_5}

複数の [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を特定の [`IDevice`](../../idevice/) にレンダリングするメソッドを定義します。操作のキャンセルを要求するためにキャンセルトークンを使用します。

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| デバイス | IDevice | 出力デバイスです。 |
| cancellationToken | CancellationToken | タスクの完了を待機中に監視するキャンセルトークンです。 |
| ソース | SVGDocument[] | レンダリングする SVG ドキュメントです。 |

### 関連項目

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [SvgRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
