---
title: "RendererTSource クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.rendering.Renderer1TSource クラス。すべてのレンダラーの抽象クラスを表します"
type: docs

url: /ja/java/com.aspose.html.rendering/renderer-1/
---
## Renderer&lt;TSource&gt; class

すべてのレンダラーの抽象クラスを表します。

```java
public abstract class Renderer<TSource> : Renderer
```

| Parameter | 説明 |
| --- | --- |
| TDocument | ドキュメントのタイプです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | アンマネージドおよび（オプションで）マネージド リソースを解放します。 |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_3)(IDevice, TSource) | 指定された[`IDevice`](../idevice/)に !:TDocument をレンダリングするメソッドを定義します。 |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_6)(IDevice, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_1)(IDevice, CancellationToken, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render)(IDevice, int, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_2)(IDevice, TimeSpan, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_4)(IDevice, TSource, int) | 指定された[`IDevice`](../idevice/)に !:TDocument をレンダリングするメソッドを定義します。リソースの読み込み、アクティブなタイマー、アニメーションタスクのネットワーク操作がなく、指定されたタイムアウトが経過した時にレンダリングが実行されます。 |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_5)(IDevice, TSource, TimeSpan) | 指定された[`IDevice`](../idevice/)に !:TDocument をレンダリングするメソッドを定義します。リソースの読み込み、アクティブなタイマー、アニメーションタスクのネットワーク操作がなく、指定されたタイムアウトが経過した時にレンダリングが実行されます。 |

### 関連項目

* class [Renderer](../renderer/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
