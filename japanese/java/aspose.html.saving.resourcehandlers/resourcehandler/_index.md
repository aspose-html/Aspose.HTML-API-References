---
title: "ResourceHandler クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.saving.ResourceHandlers.ResourceHandler クラス。このクラスはリソースの処理を担当します。リソースに対して行う操作や、親リソースに書き込まれる参照を制御できるメソッドを提供します。"
type: docs

url: /ja/java/com.aspose.html.saving.resourcehandlers/resourcehandler/
---
## ResourceHandler class

このクラスはリソースの処理を担当します。[`Resource`](../../com.aspose.html.saving/resource/) に対して何を行うか、また親の[`Resource`](../../com.aspose.html.saving/resource/) に書き込まれる参照を制御できるメソッドを提供します。

```java
public abstract class ResourceHandler
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [HandleResource](../../com.aspose.html.saving.resourcehandlers/resourcehandler/handleresource/)(Resource, ResourceHandlingContext) | このメソッドはリソースの処理を担当します。その中で、[`Resource`](../../com.aspose.html.saving/resource/) をストリームに保存したり、親リソースに埋め込んだりできます。 |
| [handleResourceReference](../../com.aspose.html.saving.resourcehandlers/resourcehandler/handleresourcereference/)(Resource, ResourceHandlingContext) | このメソッドはリソース参照の処理を担当します。このメソッド内で、処理対象のリソースへの参照がどのようになるかを設定できます。 |

### 関連項目

* package [com.aspose.html.saving.ResourceHandlers](../../com.aspose.html.saving.resourcehandlers/)
* package [Aspose.HTML](../../)
