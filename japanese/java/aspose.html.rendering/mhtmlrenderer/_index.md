---
title: "MhtmlRenderer クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.rendering.MhtmlRenderer クラス。MHTML ドキュメントレンダラーを表します"
type: docs

url: /ja/java/com.aspose.html.rendering/mhtmlrenderer/
---
## MhtmlRenderer class

MHTML ドキュメントレンダラーを表します。

```java
public class MhtmlRenderer : Renderer<Stream>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MhtmlRenderer](mhtmlrenderer/)() | デフォルトコンストラクタ。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | アンマネージドおよび（オプションで）マネージドリソースを解放します。 |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_9)(IDevice, CancellationToken, params Stream[]) | キャンセル トークンを使用して操作のキャンセルを要求しながら、特定の[`IDevice`](../idevice/)に複数の MHTML ドキュメントをレンダリングするメソッドを定義します。 |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_1)(IDevice, IList&lt;Stream&gt;, Configuration) | 指定された[`IDevice`](../idevice/)に複数の MHTML ドキュメントをレンダリングします。 |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_4)(IDevice, Stream, Configuration) | 指定された[`IDevice`](../idevice/)に MHTML ドキュメントをレンダリングします。 |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_10)(IDevice, TimeSpan, params Stream[]) | 指定された[`IDevice`](../idevice/)に複数の MHTML ドキュメントをレンダリングします。リソースの読み込み、アクティブなタイマー、アニメーションタスクのネットワーク操作がなくなり、指定されたタイムアウトが経過した時にレンダリングが実行されます。 |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_2)(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) | 指定された[`IDevice`](../idevice/)に複数の MHTML ドキュメントをレンダリングします。リソースの読み込み、アクティブなタイマー、アニメーションタスクのネットワーク操作がなくなり、指定されたタイムアウトが経過した時にレンダリングが実行されます。 |
| [render](../../com.aspose.html.rendering/mhtmlrenderer/render/#render_5)(IDevice, Stream, Configuration, TimeSpan) | 指定された[`IDevice`](../idevice/)に MHTML ドキュメントをレンダリングします。リソースの読み込み、アクティブなタイマー、アニメーションタスクのネットワーク操作がなくなり、指定されたタイムアウトが経過した時にレンダリングが実行されます。 |

### 関連項目

* class [Renderer&lt;TSource&gt;](../renderer-1/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
