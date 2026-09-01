---
title: "Device-2.MoveTo"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Device メソッド。現在の点をパラメータ pt の座標へ移動させ、接続線分を省略して新しいサブパスを開始します。現在のパス内で前のパス構築メソッドも MoveTo だった場合、新しい MoveTo がそれを上書きし、以前の MoveTo 操作の痕跡はパスに残りません。"
type: docs

url: /ja/java/com.aspose.html.rendering/device-2/moveto/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt;.MoveTo method

現在の点をパラメータ pt の座標へ移動させ、新しいサブパスを開始します。この際、接続線セグメントは省略されます。もし現在のパスにおける直前のパス構築メソッドが同じく \"MoveTo\" であった場合、新しい \"MoveTo\" がそれを上書きします。パス内に以前の \"MoveTo\" 操作の痕跡は残りません。

```java
public void MoveTo(PointF pt)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pt | PointF | パスを移動させる点。 |

### 関連項目

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
