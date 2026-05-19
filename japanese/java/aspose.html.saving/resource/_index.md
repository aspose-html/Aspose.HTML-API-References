---
title: "Resource クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.saving.Resource クラス。このクラスはリソースを記述し、その処理のためのメソッドを提供します"
type: docs

url: /ja/java/com.aspose.html.saving/resource/
---
## Resource class

このクラスはリソースを記述し、その処理のためのメソッドを提供します。

```java
public class Resource
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getMimeType](../../com.aspose.html.saving/resource/mimetype/) このリソースの [`MimeType`](../../com.aspose.html/mimetype/) を返します。リソースが見つからない場合は `null` になることがあります。 |
| [getOriginalReference](../../com.aspose.html.saving/resource/originalreference/) このリソースへの元の参照を含む文字列を返します。 |
| [getOriginalUrl](../../com.aspose.html.saving/resource/originalurl/) このリソースが所在した場所を示す URL を返します。 |
[getOutputUrl]
[setOutputUrl] Gets or sets the URL indicating where the resource will be located after processing. |
| [getStatus](../../com.aspose.html.saving/resource/status/) リソースの現在のステータスを返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [embed](../../com.aspose.html.saving/resource/embed/)(ResourceHandlingContext) | このリソースをBase64でエンコードして親に埋め込みます。エンコード結果は[`OutputUrl`](./outputurl/)に書き込まれます。 |
| [save](../../com.aspose.html.saving/resource/save/)(Stream, ResourceHandlingContext) | リソースを提供されたストリームに保存します。 |
| [withOutputUrl](../../com.aspose.html.saving/resource/withoutputurl/)(Url) | 処理後にリソースが配置される場所を示す新しいURLを指定します。 |

### 関連項目

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
