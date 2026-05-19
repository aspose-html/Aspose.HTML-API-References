---
title: "Resource.Embed"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Resource メソッド。このリソースを Base64 エンコードして親に埋め込みます。エンコード結果は OutputUrl に書き込まれます"
type: docs

url: /ja/java/com.aspose.html.saving/resource/embed/
---
## Resource.Embed method

このリソースを Base64 エンコードして親に埋め込みます。エンコード結果は [`OutputUrl`](../outputurl/) に書き込まれます。

```java
public Resource Embed(ResourceHandlingContext context)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテキスト | ResourceHandlingContext | リソース処理コンテキスト。 |

### 戻り値

このリソースは、呼び出しをチェーンできるようにします。

### 例外

| 例外 | 条件 |
| --- | --- |
| InvalidOperationException | 結果を埋め込む場所がないため、[`ParentResource`](../../resourcehandlingcontext/parentresource/) が存在しない場合に発生します。 |

### 関連項目

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
