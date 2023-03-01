---
title: Interface IFile
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.IO.IFile インターフェース. File オブジェクトは文字列である name 属性を持つ Blob オブジェクトですコンストラクターを介して Web アプリケーション内で作成するか基になる OS ファイル システムのファイルからのバイト シーケンスへの参照です
type: docs
weight: 3720
url: /ja/net/aspose.html.io/ifile/
---
## IFile interface

File オブジェクトは、文字列である name 属性を持つ Blob オブジェクトです。コンストラクターを介して Web アプリケーション内で作成するか、基になる (OS) ファイル システムのファイルからのバイト シーケンスへの参照です。

```csharp
public interface IFile : IBlob
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [LastModified](../../aspose.html.io/ifile/lastmodified/) { get; } | ファイルの最終更新日。取得時に、ユーザー エージェントがこの情報を利用可能にすることができる場合、 これは、Unix エポックからのミリ秒数として、ファイルが最後に変更された時刻の long long セットを返さなければなりません。 |
| [Name](../../aspose.html.io/ifile/name/) { get; } | ファイルの名前。 取得時に、ファイルの名前を文字列として返す必要があります。 |

### 関連項目

* interface [IBlob](../iblob/)
* 名前空間 [Aspose.Html.IO](../../aspose.html.io/)
* 組み立て [Aspose.HTML](../../)


