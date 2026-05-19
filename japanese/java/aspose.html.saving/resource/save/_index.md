---
title: "Resource.Save"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Resource メソッド。リソースを指定されたストリームに保存します。"
type: docs

url: /ja/java/com.aspose.html.saving/resource/save/
---
## Resource.Save method

リソースを提供されたストリームに保存します。

```java
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | リソースが保存されるストリームです。 |
| コンテキスト | ResourceHandlingContext | リソース処理コンテキスト。 |

### 戻り値

このリソースは、呼び出しをチェーンできるようにします。

### 例外

| 例外 | 条件 |
| --- | --- |
| InvalidOperationException | [`OutputUrl`](../outputurl/) が `null` の場合に発生します。[`OutputUrl`](../outputurl/) はリソースを保存する前に指定する必要があります。そうしないと、このリソースを参照するリソースで正しい参照を指定できなくなります。 |

### 関連項目

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
