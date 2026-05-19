---
title: "EpubRenderer クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.rendering.EpubRenderer クラス。EPub ドキュメントレンダラを表します"
type: docs

url: /ja/java/com.aspose.html.rendering/epubrenderer/
---
## EpubRenderer class

EPub ドキュメントレンダラーを表します。

```java
public class EpubRenderer : Renderer<Stream>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [EpubRenderer](epubrenderer/)() | デフォルトコンストラクタ。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | アンマネージドおよび（オプションで）マネージド リソースを解放します。 |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_9)(IDevice, CancellationToken, params Stream[]) | 複数の EPub ドキュメントを特定の[`IDevice`](../idevice/) にレンダリングするメソッドを定義し、キャンセルトークンを使用して操作のキャンセルを要求します。 |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_1)(IDevice, IList&lt;Stream&gt;, Configuration) | 複数の EPub ドキュメントを指定された[`IDevice`](../idevice/) にレンダリングします。 |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params Stream[]) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_4)(IDevice, Stream, Configuration) | EPub ドキュメントを指定された[`IDevice`](../idevice/) にレンダリングします。 |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, Stream, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_10)(IDevice, TimeSpan, params Stream[]) | 複数の EPub ストリームを特定の[`IDevice`](../idevice/) にレンダリングするメソッドを定義します。リソースの読み込み、アクティブなタイマー、アニメーションタスクのネットワーク操作がなくなり、指定されたタイムアウトが経過した時点でレンダリングが実行されます。 |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_2)(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) | 複数の EPub ドキュメントを指定された[`IDevice`](../idevice/) にレンダリングします。リソースの読み込み、アクティブなタイマー、アニメーションタスクのネットワーク操作がなくなり、指定されたタイムアウトが経過した時点でレンダリングが実行されます。 |
| [render](../../com.aspose.html.rendering/epubrenderer/render/#render_5)(IDevice, Stream, Configuration, TimeSpan) | EPub ドキュメントを指定された[`IDevice`](../idevice/) にレンダリングします。リソースの読み込み、アクティブなタイマー、アニメーションタスクのネットワーク操作がなくなり、指定されたタイムアウトが経過した時点でレンダリングが実行されます。 |

### 関連項目

* class [Renderer&lt;TSource&gt;](../renderer-1/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
