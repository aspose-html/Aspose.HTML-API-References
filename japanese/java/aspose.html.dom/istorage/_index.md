---
title: "IStorage インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.IStorage インターフェイス。Web Storage API のこのインターフェイスは、特定のドメインのセッションまたはローカルストレージへのアクセスを提供します。Web Storage 仕様 https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage を参照してください。"
type: docs

url: /ja/java/com.aspose.html.dom/istorage/
---
## IStorage interface

Web Storage API のこのインターフェイスは、特定のドメインのセッションまたはローカルストレージへのアクセスを提供します。Web Storage 仕様をご覧ください: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```java
public interface IStorage
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getLength](../../com.aspose.html.dom/istorage/length/) キー/バリューのペア数を返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [clear](../../com.aspose.html.dom/istorage/clear/)() | 存在する場合、すべてのキー/値ペアを削除します。 |
| [getItem](../../com.aspose.html.dom/istorage/getitem/)(String) | 指定されたキーに関連付けられた現在の値を返します。キーが存在しない場合は null を返します。 |
| [key](../../com.aspose.html.dom/istorage/key/)(long) | n 番目のキーの名前を返します。n がキー/値ペアの数以上の場合は null を返します。 |
| [removeItem](../../com.aspose.html.dom/istorage/removeitem/)(String) | 指定されたキーのキー/値ペアが存在する場合、それを削除します。 |
| [setItem](../../com.aspose.html.dom/istorage/setitem/)(String, String) | キーで識別されるペアの値を value に設定します。以前にキーが存在しなかった場合は新しいキー/値ペアを作成します。 |

### 関連項目

* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
