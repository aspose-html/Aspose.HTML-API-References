---
title: "IEventListener インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.events.IEventListener インターフェイス。このインターフェイスはイベント処理の主要な手段です。ユーザーはインターフェイスを実装し、メソッドを使用してリスナーを登録します。ユーザーはリスナーの使用が完了した後、リスナーを削除する必要があります。"
type: docs

url: /ja/java/com.aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

このインターフェイスは、イベント処理の主要な手段です。ユーザーはインターフェイスを実装し、メソッドを使用してリスナーを登録します。リスナーの使用が完了したら、ユーザーはそれを削除すべきです。

```java
public interface IEventListener
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [handleEvent](../../com.aspose.html.dom.events/ieventlistener/handleevent/)(Event) | このメソッドは、インターフェイスが登録されたタイプのイベントが発生するたびに呼び出されます。 |

## 備考

cloneNode メソッドを使用してノードをコピーした場合、元のノードに添付されていたイベントリスナーはコピーされたノードには添付されません。ユーザーが同じイベントリスナーを新しく作成されたコピーに追加したい場合は、手動で追加する必要があります。

### 関連項目

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
