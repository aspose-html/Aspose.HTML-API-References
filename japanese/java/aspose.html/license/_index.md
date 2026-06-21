---
title: "License クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.License クラス。コンポーネントにライセンスを付与するためのメソッドを提供します。"
type: docs

url: /ja/java/com.aspose.html/license/
---
## License class

コンポーネントをライセンスするためのメソッドを提供します。

```java
public class License
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [License](license/)() | このクラスの新しいインスタンスを初期化します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense)(Stream) | コンポーネントにライセンスを付与します。 |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense_1)(String) | コンポーネントにライセンスを付与します。 |

## サンプル

この例では、コンポーネントが含まれるフォルダー、呼び出しアセンブリが含まれるフォルダー、エントリ アセンブリのフォルダー、そして呼び出しアセンブリの埋め込みリソース内で、MyLicense.lic という名前のライセンス ファイルを検索しようとします。

```java
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

コンポーネントの jar ファイル:

```java
License license = new License();
license.setLicense("MyLicense.lic");
```

### 関連項目

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
