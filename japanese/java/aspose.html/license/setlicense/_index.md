---
title: "License.SetLicense"
second_title: "Aspose.HTML for Java API リファレンス"
description: "License メソッド。コンポーネントにライセンスを適用します。"
type: docs

url: /ja/java/com.aspose.html/license/setlicense/
---
## SetLicense(String) {#setlicense_1}

コンポーネントにライセンスを付与します。

```java
public void SetLicense(String licenseName)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| licenseName | 文字列 | 完全または短いファイル名、または埋め込みリソースの名前を指定できます。空の文字列を使用すると評価モードに切り替わります。 |

## Remarks

次の場所でライセンスを検索します:

1. 明示的なパス。

2. Aspose コンポーネント アセンブリが含まれるフォルダー。

3. クライアントの呼び出しアセンブリが含まれるフォルダー。

4. エントリ (スタートアップ) アセンブリが含まれるフォルダー。

5. クライアントの呼び出しアセンブリ内の埋め込みリソース。

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. 明示的なパス。

2. クライアントの呼び出しアセンブリ内の埋め込みリソース。

2. Aspose コンポーネント JAR ファイルが含まれるフォルダー。

3. クライアントの呼び出し JAR ファイルが含まれるフォルダー。

## 例

この例では、コンポーネントが含まれるフォルダー、呼び出しアセンブリが含まれるフォルダー、エントリアセンブリのフォルダー、そして呼び出しアセンブリの埋め込みリソースの順に、MyLicense.lic という名前のライセンスファイルを検索しようとします。

```java
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

コンポーネントの JAR ファイル:

```java
License license = new License();
license.setLicense("MyLicense.lic");
```

### 関連項目

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## SetLicense(Stream) {#setlicense}

コンポーネントにライセンスを付与します。

```java
public void SetLicense(Stream stream)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | ライセンスを含むストリーム。 |

## Remarks

このメソッドを使用して、ストリームからライセンスをロードします。

## 例

```java
[C#]

License license = new License();
license.SetLicense(myStream);
```

### 関連項目

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
