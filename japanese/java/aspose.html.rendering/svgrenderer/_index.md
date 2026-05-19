---
title: "SvgRenderer クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.rendering.SvgRenderer クラス。SVG ドキュメントのレンダラーを表します。"
type: docs

url: /ja/java/com.aspose.html.rendering/svgrenderer/
---
## SvgRenderer class

SVG ドキュメントレンダラーを表します。

```java
public class SvgRenderer : Renderer<SVGDocument>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SvgRenderer](svgrenderer/)() | デフォルトコンストラクタ。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | アンマネージドおよび（オプションで）マネージド リソースを解放します。 |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, SVGDocument) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, params SVGDocument[]) |  |
| [render](../../com.aspose.html.rendering/svgrenderer/render/#render_5)(IDevice, CancellationToken, params SVGDocument[]) | 特定の[`IDevice`](../idevice/)に�数の[`SVGDocument`](../../com.aspose.html.dom.svg/svgdocument/)をレンダリングするメソッドを定義し、キャンセルトークンを使用して操作のキャンセルを要求します。 |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, int, params SVGDocument[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, SVGDocument, int) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/)(IDevice, SVGDocument, TimeSpan) |  |
| [render](../../com.aspose.html.rendering/svgrenderer/render/#render_6)(IDevice, TimeSpan, params SVGDocument[]) | 特定の[`IDevice`](../idevice/)に複数の[`SVGDocument`](../../com.aspose.html.dom.svg/svgdocument/)をレンダリングするメソッドを定義します。リソースの読み込み、アクティブなタイマー、アニメーションタスクのネットワーク操作がなくなり、指定されたタイムアウトが経過した時にレンダリングが実行されます。 |

### 関連項目

* class [SVGDocument](../../com.aspose.html.dom.svg/svgdocument/)
* class [Renderer&lt;TSource&gt;](../renderer-1/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
