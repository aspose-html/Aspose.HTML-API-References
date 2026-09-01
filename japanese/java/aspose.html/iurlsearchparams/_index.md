---
title: "IUrlSearchParams インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.IUrlSearchParams インターフェイス。URL のクエリ文字列を操作するメソッドを提供します"
type: docs

url: /ja/java/com.aspose.html/iurlsearchparams/
---
## IUrlSearchParams interface

URL のクエリ文字列を操作するためのメソッドを提供します。

```java
public interface IUrlSearchParams : IEnumerable<String[]>
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [append](../../com.aspose.html/iurlsearchparams/append/)(String, String) | 名前が `name` で値が `value` の新しい名前-値ペアを追加します。 |
| [delete](../../com.aspose.html/iurlsearchparams/delete/)(String) | `name` が名前のすべての名前-値ペアを削除します。 |
| [get](../../com.aspose.html/iurlsearchparams/get/)(String) | `name` が名前の最初の名前-値ペアの値を返します。 |
| [getAll](../../com.aspose.html/iurlsearchparams/getall/)(String) | `name` が名前のすべての値を返します。 |
| [has](../../com.aspose.html/iurlsearchparams/has/)(String) | リストに `name` が名前の名前-値ペアが存在するか確認します。 |
| [set](../../com.aspose.html/iurlsearchparams/set/)(String, String) | 最初に見つかった名前-値ペアの値を指定された値に設定し、他のペアを削除します。指定された名前の名前-値ペアが見つからない場合は、新しいペアがリストに追加されます。 |
| [sort](../../com.aspose.html/iurlsearchparams/sort/)() | 存在するすべての名前-値ペアを名前でソートします。 |

### 関連項目

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
