---
title: "IFile インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.io.IFile インターフェイス。File オブジェクトは Blob オブジェクトで、name 属性は文字列です。コンストラクタを使用して Web アプリケーション内で作成できるか、基盤となる OS のファイルシステムからのファイルのバイトシーケンスへの参照です。"
type: docs

url: /ja/java/com.aspose.html.io/ifile/
---
## IFile interface

File オブジェクトは name 属性（文字列）を持つ Blob オブジェクトです。コンストラクタを使用してウェブアプリケーション内で作成することも、基盤となる（OS）ファイルシステムのファイルからのバイトシーケンスへの参照であることもあります。

```java
public interface IFile : IBlob
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getLastModified](../../com.aspose.html.io/ifile/lastmodified/) ファイルの最終更新日時です。取得時に、ユーザーエージェントがこの情報を提供できる場合、Unix エポックからのミリ秒数としてファイルが最後に変更された時刻を示す long long を返す必要があります。 |
| [getName](../../com.aspose.html.io/ifile/name/) ファイルの名前です。取得時には、ファイル名を文字列として返す必要があります。 |

### 関連項目

* interface [IBlob](../iblob/)
* package [com.aspose.html.io](../../com.aspose.html.io/)
* package [Aspose.HTML](../../)
