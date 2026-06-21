---
title: "ResourceHandler.HandleResourceReference"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ResourceHandler メソッド。このメソッドはリソース参照の処理を担当します。このメソッドでは、処理中のリソースへの参照がどのようになるかを設定できます。"
type: docs

url: /ja/java/com.aspose.html.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

このメソッドはリソース参照の処理を担当します。このメソッド内で、処理対象のリソースへの参照がどのようになるかを設定できます。

```java
public String HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| resource | Resource | 処理される[`Resource`](../../../com.aspose.html.saving/resource/)。 |
| コンテキスト | ResourceHandlingContext | リソース処理コンテキスト。 |

### 戻り値

現在処理中のリソースへの参照を表す、親リソースに書き込まれる文字列。

### 例外

| 例外 | 条件 |
| --- | --- |
| InvalidOperationException | `[`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/)` が `null` で、[`Status`](../../../com.aspose.html.saving/resource/status/) が Saved の場合にスローされます。保存されたリソースには [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) を指定する必要があります。指定しないと、このリソースを参照するリソースで正しい参照を設定できません。 |

### 関連項目

* class [Resource](../../../com.aspose.html.saving/resource/)
* class [ResourceHandlingContext](../../../com.aspose.html.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* package [com.aspose.html.saving.ResourceHandlers](../../../com.aspose.html.saving.resourcehandlers/)
* package [Aspose.HTML](../../../)
