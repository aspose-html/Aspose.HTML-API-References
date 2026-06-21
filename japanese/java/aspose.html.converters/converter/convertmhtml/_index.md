---
title: "Converter.ConvertMHTML"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Converter メソッド。入力ストリームで提示された MHTML ソースを変換します。結果は出力ファイルパスで作成された XPS ファイルです。"
type: docs

url: /ja/java/com.aspose.html.converters/converter/convertmhtml/
---
## ConvertMHTML(Stream, XpsSaveOptions, String) {#convertmhtml_31}

入力 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) で提示された MHTML ソースを変換します。結果は出力ファイルパスで作成された xps ファイルです。

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | 入力 mhtml (.mht) データストリーム。 |
| options | XpsSaveOptions | `[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な xps ファイル パス。 |

## 備考

MHTML コンバータ

特定のタスクで XPS フォーマットを活用するために、MHTML から [XPS](https://docs.fileformat.com/page-description-language/xps/) への変換がしばしば必要です。XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)を参照してください。そこでは、[`Converter`](../)クラスの ConvertHTML() メソッドを使用して MHTML を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。

MHTML を XPS に変換

Converter クラスは、MHTML から XPS へのいくつかの特定変換を提供します。MHTML を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。ローカルに存在する MHTML (.mht) ファイルまたはリモートの[`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。標準またはカスタムの特定ストリームを変換ソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータで MHTML を XPS 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質かつ簡単・高速に XPS に変換する無料のオンライン [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // デフォルトの XpsSaveOptions オブジェクトを定義する
      var options = new XpsSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, String) {#convertmhtml_47}

完全なファイルパスで指定された MHTML ソースを XPS に変換します。結果は、出力ファイルパスで作成された XPS ファイルです。

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | MHTML ソースの完全ファイルパス。 |
| options | XpsSaveOptions | `[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な xps ファイル パス。 |

## 備考

MHTML コンバータ

特定のタスクで XPS フォーマットを活用するために、MHTML から [XPS](https://docs.fileformat.com/page-description-language/xps/) への変換がしばしば必要です。XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)を参照してください。そこでは、[`Converter`](../)クラスの ConvertHTML() メソッドを使用して MHTML を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。

MHTML を XPS に変換

Converter クラスは、MHTML から XPS へのいくつかの特定変換を提供します。MHTML を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。ローカルに存在する MHTML (.mht) ファイルまたはリモートの[`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。標準またはカスタムの特定ストリームを変換ソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータで MHTML を XPS 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質かつ簡単・高速に XPS に変換する無料のオンライン [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// フォームのソースファイルパス
	var sourcePath = Path.Combine(InputFolder, "sample.mht");

	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// デフォルトの XpsSaveOptions オブジェクトを定義する
	var options = new XpsSaveOptions();

	// 変換プロセスを開始する
	Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, String) {#convertmhtml_15}

URL で指定された MHTML ソースを変換します。結果は、出力ファイルパスで作成された XPS ファイルです。

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | MHTML ソースドキュメントの URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| options | XpsSaveOptions | `[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な xps ファイル パス。 |

## 備考

MHTML コンバータ

特定のタスクで XPS フォーマットを活用するために、MHTML から [XPS](https://docs.fileformat.com/page-description-language/xps/) への変換がしばしば必要です。XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)を参照してください。そこでは、[`Converter`](../)クラスの ConvertHTML() メソッドを使用して MHTML を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。

MHTML を XPS に変換

Converter クラスは、MHTML から XPS へのいくつかの特定変換を提供します。MHTML を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。ローカルに存在する MHTML (.mht) ファイルまたはリモートの[`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。標準またはカスタムの特定ストリームを変換ソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータで MHTML を XPS 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質かつ簡単・高速に XPS に変換する無料のオンライン [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// フォームのソースファイルパス
	var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// デフォルトの XpsSaveOptions オブジェクトを定義する
	var options = new XpsSaveOptions();

	// 変換プロセスを開始する
	Converter.ConvertMHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, String) {#convertmhtml_23}

入力 [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) で指定された MHTML ソースを変換します。結果は、出力ファイルパスで作成された XPS ファイルです。

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | 変換元の mhtml (.mht) データストリーム。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | XpsSaveOptions | `[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な xps ファイル パス。 |

## 備考

MHTML コンバータ

特定のタスクで XPS フォーマットを活用するために、MHTML から [XPS](https://docs.fileformat.com/page-description-language/xps/) への変換がしばしば必要です。XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)を参照してください。そこでは、[`Converter`](../)クラスの ConvertHTML() メソッドを使用して MHTML を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。

MHTML を XPS に変換

Converter クラスは、MHTML から XPS へのいくつかの特定変換を提供します。MHTML を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。ローカルに存在する MHTML (.mht) ファイルまたはリモートの[`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。標準またはカスタムの特定ストリームを変換ソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータで MHTML を XPS 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質かつ簡単・高速に XPS に変換する無料のオンライン [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // デフォルトの XpsSaveOptions オブジェクトを定義する
      var options = new XpsSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertMHTML(File.OpenRead(sourcePath), new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, XpsSaveOptions, String) {#convertmhtml_39}

完全なファイルパスで指定された MHTML ソースを XPS に変換します。結果は、出力ファイルパスで作成された XPS ファイルです。

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | MHTML ソースの完全ファイルパス。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | XpsSaveOptions | `[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な xps ファイル パス。 |

## 備考

MHTML コンバータ

特定のタスクで XPS フォーマットを活用するために、MHTML から [XPS](https://docs.fileformat.com/page-description-language/xps/) への変換がしばしば必要です。XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)を参照してください。そこでは、[`Converter`](../)クラスの ConvertHTML() メソッドを使用して MHTML を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。

MHTML を XPS に変換

Converter クラスは、MHTML から XPS へのいくつかの特定変換を提供します。MHTML を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。ローカルに存在する MHTML (.mht) ファイルまたはリモートの[`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。標準またはカスタムの特定ストリームを変換ソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータで MHTML を XPS 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質かつ簡単・高速に XPS に変換する無料のオンライン [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // デフォルトの XpsSaveOptions オブジェクトを定義する
      var options = new XpsSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, XpsSaveOptions, String) {#convertmhtml_7}

URL で指定された MHTML ソースを変換します。結果は、出力ファイルパスで作成された XPS ファイルです。

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | MHTML ソースドキュメントの URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | XpsSaveOptions | `[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な xps ファイル パス。 |

## 備考

MHTML コンバータ

特定のタスクで XPS フォーマットを活用するために、MHTML から [XPS](https://docs.fileformat.com/page-description-language/xps/) への変換がしばしば必要です。XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)を参照してください。そこでは、[`Converter`](../)クラスの ConvertHTML() メソッドを使用して MHTML を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。

MHTML を XPS に変換

Converter クラスは、MHTML から XPS へのいくつかの特定変換を提供します。MHTML を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。ローカルに存在する MHTML (.mht) ファイルまたはリモートの[`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。標準またはカスタムの特定ストリームを変換ソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータで MHTML を XPS 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質かつ簡単・高速に XPS に変換する無料のオンライン [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // フォームのソースファイルパス
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // デフォルトの XpsSaveOptions オブジェクトを定義する
      var options = new XpsSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_30}

入力ストリームで提供される MHTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertMHTML(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | 変換元の mhtml (.mht) データストリーム。 |
| options | XpsSaveOptions | `[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## 備考

MHTML コンバータ

特定のタスクで XPS フォーマットを活用するために、MHTML から [XPS](https://docs.fileformat.com/page-description-language/xps/) への変換がしばしば必要です。XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)を参照してください。そこでは、[`Converter`](../)クラスの ConvertHTML() メソッドを使用して MHTML を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。

MHTML を XPS に変換

Converter クラスは、MHTML から XPS へのいくつかの特定変換を提供します。MHTML を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。ローカルに存在する MHTML (.mht) ファイルまたはリモートの[`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。標準またはカスタムの特定ストリームを変換ソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータで MHTML を XPS 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質かつ簡単・高速に XPS に変換する無料のオンライン [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import com.aspose.html.io;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider の実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルトの XpsSaveOptions オブジェクトを定義する
      var options = new XpsSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 関連項目

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_46}

完全ファイルパスで提供される MHTML ソースを XPS に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertMHTML(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | MHTML ソースの完全ファイルパス。 |
| options | XpsSaveOptions | `[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装。 |

## 備考

MHTML コンバータ

特定のタスクで XPS フォーマットを活用するために、MHTML から [XPS](https://docs.fileformat.com/page-description-language/xps/) への変換がしばしば必要です。XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)を参照してください。そこでは、[`Converter`](../)クラスの ConvertHTML() メソッドを使用して MHTML を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。

MHTML を XPS に変換

Converter クラスは、MHTML から XPS へのいくつかの特定変換を提供します。MHTML を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。ローカルに存在する MHTML (.mht) ファイルまたはリモートの[`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。標準またはカスタムの特定ストリームを変換ソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータで MHTML を XPS 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質かつ簡単・高速に XPS に変換する無料のオンライン [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import com.aspose.html.io;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの XpsSaveOptions オブジェクトを定義する
      var options = new XpsSaveOptions();

      // ICreateStreamProvider の実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 変換プロセスを開始する
      Converter.ConvertMHTML(sourcePath, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 関連項目

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_14}

[`URL`](../../../com.aspose.html/url/) で提供される MHTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertMHTML(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | MHTML ソースドキュメントの URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| options | XpsSaveOptions | `[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## 備考

MHTML コンバータ

特定のタスクで XPS フォーマットを活用するために、MHTML から [XPS](https://docs.fileformat.com/page-description-language/xps/) への変換がしばしば必要です。XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)を参照してください。そこでは、[`Converter`](../)クラスの ConvertHTML() メソッドを使用して MHTML を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。

MHTML を XPS に変換

Converter クラスは、MHTML から XPS へのいくつかの特定変換を提供します。MHTML を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。ローカルに存在する MHTML (.mht) ファイルまたはリモートの[`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。標準またはカスタムの特定ストリームを変換ソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータで MHTML を XPS 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質かつ簡単・高速に XPS に変換する無料のオンライン [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import com.aspose.html.io; 
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // フォームのソースファイルパス
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの XpsSaveOptions オブジェクトを定義する
      var options = new XpsSaveOptions();

      // ICreateStreamProvider の実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 変換プロセスを開始する
      Converter.ConvertMHTML(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_22}

入力ストリームで提供される MHTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | 変換元の mhtml (.mht) データストリーム。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | XpsSaveOptions | `[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## 備考

MHTML コンバータ

特定のタスクで XPS フォーマットを活用するために、MHTML から [XPS](https://docs.fileformat.com/page-description-language/xps/) への変換がしばしば必要です。XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)を参照してください。そこでは、[`Converter`](../)クラスの ConvertHTML() メソッドを使用して MHTML を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。

MHTML を XPS に変換

Converter クラスは、MHTML から XPS へのいくつかの特定変換を提供します。MHTML を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。ローカルに存在する MHTML (.mht) ファイルまたはリモートの[`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。標準またはカスタムの特定ストリームを変換ソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータで MHTML を XPS 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質かつ簡単・高速に XPS に変換する無料のオンライン [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import com.aspose.html.io;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider の実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルトの XpsSaveOptions オブジェクトを定義する
      var options = new XpsSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_38}

完全ファイルパスで提供される MHTML ソースを XPS に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | MHTML ソースの完全ファイルパス。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | XpsSaveOptions | `[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装。 |

## 備考

MHTML コンバータ

特定のタスクで XPS フォーマットを活用するために、MHTML から [XPS](https://docs.fileformat.com/page-description-language/xps/) への変換がしばしば必要です。XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)を参照してください。そこでは、[`Converter`](../)クラスの ConvertHTML() メソッドを使用して MHTML を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。

MHTML を XPS に変換

Converter クラスは、MHTML から XPS へのいくつかの特定変換を提供します。MHTML を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。ローカルに存在する MHTML (.mht) ファイルまたはリモートの[`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。標準またはカスタムの特定ストリームを変換ソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータで MHTML を XPS 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質かつ簡単・高速に XPS に変換する無料のオンライン [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの XpsSaveOptions オブジェクトを定義する
      var options = new XpsSaveOptions();

      // ICreateStreamProvider の実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertmhtml_6}

URL で提供される MHTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | MHTML ソースドキュメントの URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | XpsSaveOptions | `[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装。 |

## 備考

MHTML コンバータ

特定のタスクで XPS フォーマットを活用するために、MHTML から [XPS](https://docs.fileformat.com/page-description-language/xps/) への変換がしばしば必要です。XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/)を参照してください。そこでは、[`Converter`](../)クラスの ConvertHTML() メソッドを使用して MHTML を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。

MHTML を XPS に変換

Converter クラスは、MHTML から XPS へのいくつかの特定変換を提供します。MHTML を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。ローカルに存在する MHTML (.mht) ファイルまたはリモートの[`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。標準またはカスタムの特定ストリームを変換ソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータで MHTML を XPS 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質かつ簡単・高速に XPS に変換する無料のオンライン [MHTML to XPS Converter](https://products.aspose.app/html/en/conversion/mhtml-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // フォームのソースファイルパス
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの XpsSaveOptions オブジェクトを定義する
      var options = new XpsSaveOptions();

      // ICreateStreamProvider の実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, DocSaveOptions, String) {#convertmhtml_25}

入力ストリームで提示された MHTML ソースを変換します。結果は出力ファイルパスで作成された docx ファイルです。

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | MHTML 変換の入力データストリーム。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な docx ファイルパス。 |

## 備考

MHTML コンバータ

特定のタスクで [DOCX](https://docs.fileformat.com/word-processing/docx/) フォーマットを活用するために、MHTML から DOCX への変換がしばしば必要になります。DOCX は Microsoft Word ドキュメントで広く知られているフォーマットです。テキスト、表、ラスタおよびベクター画像、ビデオ、音声、図表など、さまざまなデータを含めることができます。このフォーマットは、複雑な書式設定機能をサポートし、ユーザーにあらゆる種類の文書を作成するための多様なオプションを提供する点で人気があります。

MHTML を DOCX に変換する方法や、[`Converter`](../) クラスの ConvertMHTML() メソッドの使用方法、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法については、[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) を参照してください。

MHTML を DOCX に変換

Converter クラスは MHTML から DOCX へのいくつかの特定変換を提供します。MHTML を DOCX に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。標準またはカスタムの特定ストリームを変換元として使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を DOCX 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 関連項目

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, DocSaveOptions, String) {#convertmhtml_41}

完全なファイルパスで提示された MHTML ソースを DOCX に変換します。結果は出力ファイルパスで作成された docx ファイルです。

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | MHTML ソースファイルパス。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な docx ファイルパス。 |

## 備考

MHTML コンバータ

特定のタスクで [DOCX](https://docs.fileformat.com/word-processing/docx/) フォーマットを活用するために、MHTML から DOCX への変換がしばしば必要になります。DOCX は Microsoft Word ドキュメントで広く知られているフォーマットです。テキスト、表、ラスタおよびベクター画像、ビデオ、音声、図表など、さまざまなデータを含めることができます。このフォーマットは、複雑な書式設定機能をサポートし、ユーザーにあらゆる種類の文書を作成するための多様なオプションを提供する点で人気があります。

MHTML を DOCX に変換する方法や、[`Converter`](../) クラスの ConvertMHTML() メソッドの使用方法、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法については、[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) を参照してください。

MHTML を DOCX に変換

Converter クラスは MHTML から DOCX へのいくつかの特定変換を提供します。MHTML を DOCX に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。標準またはカスタムの特定ストリームを変換元として使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を DOCX 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, DocSaveOptions, String) {#convertmhtml_9}

URL で指定された MHTML ソースを変換します。結果は、出力ファイルパスで作成された DOCX ファイルです。

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | MHTML ソースドキュメントの URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な docx ファイルパス。 |

## 備考

MHTML コンバータ

特定のタスクで [DOCX](https://docs.fileformat.com/word-processing/docx/) フォーマットを活用するために、MHTML から DOCX への変換がしばしば必要になります。DOCX は Microsoft Word ドキュメントで広く知られているフォーマットです。テキスト、表、ラスタおよびベクター画像、ビデオ、音声、図表など、さまざまなデータを含めることができます。このフォーマットは、複雑な書式設定機能をサポートし、ユーザーにあらゆる種類の文書を作成するための多様なオプションを提供する点で人気があります。

MHTML を DOCX に変換する方法や、[`Converter`](../) クラスの ConvertMHTML() メソッドの使用方法、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法については、[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) を参照してください。

MHTML を DOCX に変換

Converter クラスは MHTML から DOCX へのいくつかの特定変換を提供します。MHTML を DOCX に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。標準またはカスタムの特定ストリームを変換元として使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を DOCX 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertMHTML(sourceUrl, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, DocSaveOptions, String) {#convertmhtml_17}

入力ストリームで提示された MHTML ソースを変換します。結果は出力ファイルパスで作成された docx ファイルです。

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | MHTML 変換の入力データストリーム。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な docx ファイルパス。 |

## 備考

MHTML コンバータ

特定のタスクで [DOCX](https://docs.fileformat.com/word-processing/docx/) フォーマットを活用するために、MHTML から DOCX への変換がしばしば必要になります。DOCX は Microsoft Word ドキュメントで広く知られているフォーマットです。テキスト、表、ラスタおよびベクター画像、ビデオ、音声、図表など、さまざまなデータを含めることができます。このフォーマットは、複雑な書式設定機能をサポートし、ユーザーにあらゆる種類の文書を作成するための多様なオプションを提供する点で人気があります。

MHTML を DOCX に変換する方法や、[`Converter`](../) クラスの ConvertMHTML() メソッドの使用方法、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法については、[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) を参照してください。

MHTML を DOCX に変換

Converter クラスは MHTML から DOCX へのいくつかの特定変換を提供します。MHTML を DOCX に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。標準またはカスタムの特定ストリームを変換元として使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を DOCX 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, DocSaveOptions, String) {#convertmhtml_33}

完全なファイルパスで提示された MHTML ソースを DOCX に変換します。結果は出力ファイルパスで作成された docx ファイルです。

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | MHTML ソースの完全ファイルパス。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な docx ファイルパス。 |

## 備考

MHTML コンバータ

特定のタスクで [DOCX](https://docs.fileformat.com/word-processing/docx/) フォーマットを活用するために、MHTML から DOCX への変換がしばしば必要になります。DOCX は Microsoft Word ドキュメントで広く知られているフォーマットです。テキスト、表、ラスタおよびベクター画像、ビデオ、音声、図表など、さまざまなデータを含めることができます。このフォーマットは、複雑な書式設定機能をサポートし、ユーザーにあらゆる種類の文書を作成するための多様なオプションを提供する点で人気があります。

MHTML を DOCX に変換する方法や、[`Converter`](../) クラスの ConvertMHTML() メソッドの使用方法、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法については、[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) を参照してください。

MHTML を DOCX に変換

Converter クラスは MHTML から DOCX へのいくつかの特定変換を提供します。MHTML を DOCX に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。標準またはカスタムの特定ストリームを変換元として使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を DOCX 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, DocSaveOptions, String) {#convertmhtml_1}

[`URL`](../../../com.aspose.html/url/) で提供される MHTML ソースを変換します。結果は出力ファイルパスで形成された docx ファイルです。

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | MHTML ソースドキュメント [`URL`](../../../com.aspose.html/url/) - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な docx ファイルパス。 |

## 備考

MHTML コンバータ

特定のタスクで [DOCX](https://docs.fileformat.com/word-processing/docx/) フォーマットを活用するために、MHTML から DOCX への変換がしばしば必要になります。DOCX は Microsoft Word ドキュメントで広く知られているフォーマットです。テキスト、表、ラスタおよびベクター画像、ビデオ、音声、図表など、さまざまなデータを含めることができます。このフォーマットは、複雑な書式設定機能をサポートし、ユーザーにあらゆる種類の文書を作成するための多様なオプションを提供する点で人気があります。

MHTML を DOCX に変換する方法や、[`Converter`](../) クラスの ConvertMHTML() メソッドの使用方法、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法については、[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) を参照してください。

MHTML を DOCX に変換

Converter クラスは MHTML から DOCX へのいくつかの特定変換を提供します。MHTML を DOCX に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。標準またはカスタムの特定ストリームを変換元として使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を DOCX 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_24}

入力ストリームで提供される MHTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertMHTML(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | MHTML 変換の入力データストリーム。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## 備考

MHTML コンバータ

特定のタスクで [DOCX](https://docs.fileformat.com/word-processing/docx/) フォーマットを活用するために、MHTML から DOCX への変換がしばしば必要になります。DOCX は Microsoft Word ドキュメントで広く知られているフォーマットです。テキスト、表、ラスタおよびベクター画像、ビデオ、音声、図表など、さまざまなデータを含めることができます。このフォーマットは、複雑な書式設定機能をサポートし、ユーザーにあらゆる種類の文書を作成するための多様なオプションを提供する点で人気があります。

MHTML を DOCX に変換する方法や、[`Converter`](../) クラスの ConvertMHTML() メソッドの使用方法、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法については、[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) を参照してください。

MHTML を DOCX に変換

Converter クラスは MHTML から DOCX へのいくつかの特定変換を提供します。MHTML を DOCX に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。標準またはカスタムの特定ストリームを変換元として使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を DOCX 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider の実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_40}

完全ファイルパスで提供される MHTML ソースを DOCX に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertMHTML(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | MHTML ソースの完全ファイルパス。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## 備考

MHTML コンバータ

特定のタスクで [DOCX](https://docs.fileformat.com/word-processing/docx/) フォーマットを活用するために、MHTML から DOCX への変換がしばしば必要になります。DOCX は Microsoft Word ドキュメントで広く知られているフォーマットです。テキスト、表、ラスタおよびベクター画像、ビデオ、音声、図表など、さまざまなデータを含めることができます。このフォーマットは、複雑な書式設定機能をサポートし、ユーザーにあらゆる種類の文書を作成するための多様なオプションを提供する点で人気があります。

MHTML を DOCX に変換する方法や、[`Converter`](../) クラスの ConvertMHTML() メソッドの使用方法、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法については、[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) を参照してください。

MHTML を DOCX に変換

Converter クラスは MHTML から DOCX へのいくつかの特定変換を提供します。MHTML を DOCX に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。標準またはカスタムの特定ストリームを変換元として使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を DOCX 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // ICreateStreamProvider の実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 変換プロセスを開始する
      Converter.ConvertMHTML(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_8}

URL で提供される MHTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertMHTML(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | MHTML ソースドキュメント [`URL`](../../../com.aspose.html/url/) - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装。 |

## 備考

MHTML コンバータ

特定のタスクで [DOCX](https://docs.fileformat.com/word-processing/docx/) フォーマットを活用するために、MHTML から DOCX への変換がしばしば必要になります。DOCX は Microsoft Word ドキュメントで広く知られているフォーマットです。テキスト、表、ラスタおよびベクター画像、ビデオ、音声、図表など、さまざまなデータを含めることができます。このフォーマットは、複雑な書式設定機能をサポートし、ユーザーにあらゆる種類の文書を作成するための多様なオプションを提供する点で人気があります。

MHTML を DOCX に変換する方法や、[`Converter`](../) クラスの ConvertMHTML() メソッドの使用方法、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法については、[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) を参照してください。

MHTML を DOCX に変換

Converter クラスは MHTML から DOCX へのいくつかの特定変換を提供します。MHTML を DOCX に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。標準またはカスタムの特定ストリームを変換元として使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を DOCX 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // ICreateStreamProvider の実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 変換プロセスを開始する
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_16}

入力ストリームで提供される MHTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | MHTML 変換の入力データストリーム。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装。 |

## 備考

MHTML コンバータ

特定のタスクで [DOCX](https://docs.fileformat.com/word-processing/docx/) フォーマットを活用するために、MHTML から DOCX への変換がしばしば必要になります。DOCX は Microsoft Word ドキュメントで広く知られているフォーマットです。テキスト、表、ラスタおよびベクター画像、ビデオ、音声、図表など、さまざまなデータを含めることができます。このフォーマットは、複雑な書式設定機能をサポートし、ユーザーにあらゆる種類の文書を作成するための多様なオプションを提供する点で人気があります。

MHTML を DOCX に変換する方法や、[`Converter`](../) クラスの ConvertMHTML() メソッドの使用方法、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法については、[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) を参照してください。

MHTML を DOCX に変換

Converter クラスは MHTML から DOCX へのいくつかの特定変換を提供します。MHTML を DOCX に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。標準またはカスタムの特定ストリームを変換元として使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を DOCX 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider の実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml_32}

完全ファイルパスで提供される MHTML ソースを DOCX に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | MHTML ソースの完全ファイルパス。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## 備考

MHTML コンバータ

特定のタスクで [DOCX](https://docs.fileformat.com/word-processing/docx/) フォーマットを活用するために、MHTML から DOCX への変換がしばしば必要になります。DOCX は Microsoft Word ドキュメントで広く知られているフォーマットです。テキスト、表、ラスタおよびベクター画像、ビデオ、音声、図表など、さまざまなデータを含めることができます。このフォーマットは、複雑な書式設定機能をサポートし、ユーザーにあらゆる種類の文書を作成するための多様なオプションを提供する点で人気があります。

MHTML を DOCX に変換する方法や、[`Converter`](../) クラスの ConvertMHTML() メソッドの使用方法、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法については、[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) を参照してください。

MHTML を DOCX に変換

Converter クラスは MHTML から DOCX へのいくつかの特定変換を提供します。MHTML を DOCX に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。標準またはカスタムの特定ストリームを変換元として使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして configuration を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を DOCX 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // ICreateStreamProvider の実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertmhtml}

[`URL`](../../../com.aspose.html/url/) で提供される MHTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | MHTML ソースドキュメント [`URL`](../../../com.aspose.html/url/) - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## 備考

MHTML コンバータ

特定のタスクで [DOCX](https://docs.fileformat.com/word-processing/docx/) フォーマットを活用するために、MHTML から DOCX への変換がしばしば必要になります。DOCX は Microsoft Word ドキュメントで広く知られているフォーマットです。テキスト、表、ラスタおよびベクター画像、ビデオ、音声、図表など、さまざまなデータを含めることができます。このフォーマットは、複雑な書式設定機能をサポートし、ユーザーにあらゆる種類の文書を作成するための多様なオプションを提供する点で人気があります。

MHTML を DOCX に変換する方法や、[`Converter`](../) クラスの ConvertMHTML() メソッドの使用方法、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法については、[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) を参照してください。

MHTML を DOCX に変換

Converter クラスは MHTML から DOCX へのいくつかの特定変換を提供します。MHTML を DOCX に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。標準またはカスタムの特定ストリームを変換元として使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして configuration を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を DOCX 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [MHTML to DOCX Converter](https://products.aspose.app/html/en/conversion/mhtml-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // ICreateStreamProvider の実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source folder path.

*OutputFolder - user output folder path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, PdfSaveOptions, String) {#convertmhtml_29}

入力ストリームで提示された MHTML ソースを変換します。結果は出力ファイルパスで作成された pdf ファイルです。

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | MHTML 変換の入力データストリーム。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options) をご覧ください。 |
| outputPath | 文字列 | 出力変換結果としての完全な pdf ファイルパスです。 |

## 備考

MHTML コンバータ

MHTML を PDF に変換することは、特定のタスクで [PDF](https://docs.fileformat.com/pdf/) フォーマットを活用するためにしばしば必要です。PDF は他のファイルにはない多くの利点を持っています。例えば、多くのプログラムやアプリが PDF ドキュメントをサポートしており、PDF ファイルは印刷に最適化されていて、文書の紙媒体コピーを作成するのに理想的です。また、PDF ファイルのセキュリティ設定を構成でき、印刷や編集、電子署名の使用などを無効にすることができます。

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertMHTML() メソッドを使用して MHTML を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

MHTML を PDF に変換

Converter クラスは、MHTML 固有の PDF への変換をいくつか提供します。MHTML を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート URL を変換元として検出します。標準またはカスタムの特定の [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) をソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を PDF 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質・簡単・高速に PDF に変換する無料のオンライン [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, PdfSaveOptions, String) {#convertmhtml_45}

完全なファイルパスで指定された MHTML ソースを PDF に変換します。結果は、出力ファイルパスで作成された PDF ファイルです。

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | MHTML ソースの完全ファイルパス。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options) をご覧ください。 |
| outputPath | 文字列 | 出力変換結果としての完全な pdf ファイルパスです。 |

## 備考

MHTML コンバータ

MHTML を PDF に変換することは、特定のタスクで [PDF](https://docs.fileformat.com/pdf/) フォーマットを活用するためにしばしば必要です。PDF は他のファイルにはない多くの利点を持っています。例えば、多くのプログラムやアプリが PDF ドキュメントをサポートしており、PDF ファイルは印刷に最適化されていて、文書の紙媒体コピーを作成するのに理想的です。また、PDF ファイルのセキュリティ設定を構成でき、印刷や編集、電子署名の使用などを無効にすることができます。

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertMHTML() メソッドを使用して MHTML を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

MHTML を PDF に変換

Converter クラスは、MHTML 固有の PDF への変換をいくつか提供します。MHTML を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート URL を変換元として検出します。標準またはカスタムの特定の [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) をソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を PDF 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質・簡単・高速に PDF に変換する無料のオンライン [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, PdfSaveOptions, String) {#convertmhtml_13}

URL で指定された MHTML ソースを変換します。結果は、出力ファイルパスで作成された PDF ファイルです。

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | MHTML ソースドキュメントの URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options) をご覧ください。 |
| outputPath | 文字列 | 出力変換結果としての完全な pdf ファイルパスです。 |

## 備考

MHTML コンバータ

MHTML を PDF に変換することは、特定のタスクで [PDF](https://docs.fileformat.com/pdf/) フォーマットを活用するためにしばしば必要です。PDF は他のファイルにはない多くの利点を持っています。例えば、多くのプログラムやアプリが PDF ドキュメントをサポートしており、PDF ファイルは印刷に最適化されていて、文書の紙媒体コピーを作成するのに理想的です。また、PDF ファイルのセキュリティ設定を構成でき、印刷や編集、電子署名の使用などを無効にすることができます。

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertMHTML() メソッドを使用して MHTML を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

MHTML を PDF に変換

Converter クラスは、MHTML 固有の PDF への変換をいくつか提供します。MHTML を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート URL を変換元として検出します。標準またはカスタムの特定の [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) をソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を PDF 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質・簡単・高速に PDF に変換する無料のオンライン [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, String) {#convertmhtml_21}

入力ストリームで提示された MHTML ソースを変換します。結果は出力ファイルパスで作成された pdf ファイルです。

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | MHTML 変換の入力データストリーム。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options) をご覧ください。 |
| outputPath | 文字列 | 出力変換結果としての完全な pdf ファイルパスです。 |

## 備考

MHTML コンバータ

MHTML を PDF に変換することは、特定のタスクで [PDF](https://docs.fileformat.com/pdf/) フォーマットを活用するためにしばしば必要です。PDF は他のファイルにはない多くの利点を持っています。例えば、多くのプログラムやアプリが PDF ドキュメントをサポートしており、PDF ファイルは印刷に最適化されていて、文書の紙媒体コピーを作成するのに理想的です。また、PDF ファイルのセキュリティ設定を構成でき、印刷や編集、電子署名の使用などを無効にすることができます。

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertMHTML() メソッドを使用して MHTML を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

MHTML を PDF に変換

Converter クラスは、MHTML 固有の PDF への変換をいくつか提供します。MHTML を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート URL を変換元として検出します。標準またはカスタムの特定の [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) をソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を PDF 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質・簡単・高速に PDF に変換する無料のオンライン [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, PdfSaveOptions, String) {#convertmhtml_37}

完全なファイルパスで指定された MHTML ソースを PDF に変換します。結果は、出力ファイルパスで作成された PDF ファイルです。

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | MHTML ソースファイルパス。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options) をご覧ください。 |
| outputPath | 文字列 | 出力変換結果としての完全な pdf ファイルパスです。 |

## 備考

MHTML コンバータ

MHTML を PDF に変換することは、特定のタスクで [PDF](https://docs.fileformat.com/pdf/) フォーマットを活用するためにしばしば必要です。PDF は他のファイルにはない多くの利点を持っています。例えば、多くのプログラムやアプリが PDF ドキュメントをサポートしており、PDF ファイルは印刷に最適化されていて、文書の紙媒体コピーを作成するのに理想的です。また、PDF ファイルのセキュリティ設定を構成でき、印刷や編集、電子署名の使用などを無効にすることができます。

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertMHTML() メソッドを使用して MHTML を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

MHTML を PDF に変換

Converter クラスは、MHTML 固有の PDF への変換をいくつか提供します。MHTML を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート URL を変換元として検出します。標準またはカスタムの特定の [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) をソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を PDF 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質・簡単・高速に PDF に変換する無料のオンライン [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, PdfSaveOptions, String) {#convertmhtml_5}

URL で指定された MHTML ソースを変換します。結果は、出力ファイルパスで作成された PDF ファイルです。

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | MHTML ソースドキュメントの URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options) をご覧ください。 |
| outputPath | 文字列 | 出力変換結果としての完全な pdf ファイルパスです。 |

## 備考

MHTML コンバータ

MHTML を PDF に変換することは、特定のタスクで [PDF](https://docs.fileformat.com/pdf/) フォーマットを活用するためにしばしば必要です。PDF は他のファイルにはない多くの利点を持っています。例えば、多くのプログラムやアプリが PDF ドキュメントをサポートしており、PDF ファイルは印刷に最適化されていて、文書の紙媒体コピーを作成するのに理想的です。また、PDF ファイルのセキュリティ設定を構成でき、印刷や編集、電子署名の使用などを無効にすることができます。

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertMHTML() メソッドを使用して MHTML を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

MHTML を PDF に変換

Converter クラスは、MHTML 固有の PDF への変換をいくつか提供します。MHTML を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート URL を変換元として検出します。標準またはカスタムの特定の [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) をソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を PDF 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質・簡単・高速に PDF に変換する無料のオンライン [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_28}

入力ストリームで提供される MHTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertMHTML(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | MHTML 変換の入力データストリーム。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options) をご覧ください。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装。 |

## 備考

MHTML コンバータ

MHTML を PDF に変換することは、特定のタスクで [PDF](https://docs.fileformat.com/pdf/) フォーマットを活用するためにしばしば必要です。PDF は他のファイルにはない多くの利点を持っています。例えば、多くのプログラムやアプリが PDF ドキュメントをサポートしており、PDF ファイルは印刷に最適化されていて、文書の紙媒体コピーを作成するのに理想的です。また、PDF ファイルのセキュリティ設定を構成でき、印刷や編集、電子署名の使用などを無効にすることができます。

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertMHTML() メソッドを使用して MHTML を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

MHTML を PDF に変換

Converter クラスは、MHTML 固有の PDF への変換をいくつか提供します。MHTML を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート URL を変換元として検出します。標準またはカスタムの特定の [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) をソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を PDF 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質・簡単・高速に PDF に変換する無料のオンライン [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider の実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_44}

完全なファイルパスで指定された MHTML ソースを PDF に変換します。結果は、[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertMHTML(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | MHTML ソースファイルパス。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options) をご覧ください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## 備考

MHTML コンバータ

MHTML を PDF に変換することは、特定のタスクで [PDF](https://docs.fileformat.com/pdf/) フォーマットを活用するためにしばしば必要です。PDF は他のファイルにはない多くの利点を持っています。例えば、多くのプログラムやアプリが PDF ドキュメントをサポートしており、PDF ファイルは印刷に最適化されていて、文書の紙媒体コピーを作成するのに理想的です。また、PDF ファイルのセキュリティ設定を構成でき、印刷や編集、電子署名の使用などを無効にすることができます。

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertMHTML() メソッドを使用して MHTML を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

MHTML を PDF に変換

Converter クラスは、MHTML 固有の PDF への変換をいくつか提供します。MHTML を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート URL を変換元として検出します。標準またはカスタムの特定の [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) をソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を PDF 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質・簡単・高速に PDF に変換する無料のオンライン [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // ICreateStreamProvider の実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 変換プロセスを開始する
      Converter.ConvertMHTML(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_12}

URL で提供される MHTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertMHTML(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | MHTML ソースドキュメントの URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options) をご覧ください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## 備考

MHTML コンバータ

MHTML を PDF に変換することは、特定のタスクで [PDF](https://docs.fileformat.com/pdf/) フォーマットを活用するためにしばしば必要です。PDF は他のファイルにはない多くの利点を持っています。例えば、多くのプログラムやアプリが PDF ドキュメントをサポートしており、PDF ファイルは印刷に最適化されていて、文書の紙媒体コピーを作成するのに理想的です。また、PDF ファイルのセキュリティ設定を構成でき、印刷や編集、電子署名の使用などを無効にすることができます。

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertMHTML() メソッドを使用して MHTML を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

MHTML を PDF に変換

Converter クラスは、MHTML 固有の PDF への変換をいくつか提供します。MHTML を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート URL を変換元として検出します。標準またはカスタムの特定の [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) をソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を PDF 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質・簡単・高速に PDF に変換する無料のオンライン [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // ICreateStreamProvider の実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 変換プロセスを開始する
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_20}

入力ストリームで提供される MHTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | MHTML 変換の入力データストリーム。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options) をご覧ください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## 備考

MHTML コンバータ

MHTML を PDF に変換することは、特定のタスクで [PDF](https://docs.fileformat.com/pdf/) フォーマットを活用するためにしばしば必要です。PDF は他のファイルにはない多くの利点を持っています。例えば、多くのプログラムやアプリが PDF ドキュメントをサポートしており、PDF ファイルは印刷に最適化されていて、文書の紙媒体コピーを作成するのに理想的です。また、PDF ファイルのセキュリティ設定を構成でき、印刷や編集、電子署名の使用などを無効にすることができます。

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertMHTML() メソッドを使用して MHTML を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

MHTML を PDF に変換

Converter クラスは、MHTML 固有の PDF への変換をいくつか提供します。MHTML を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート URL を変換元として検出します。標準またはカスタムの特定の [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) をソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を PDF 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質・簡単・高速に PDF に変換する無料のオンライン [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider の実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_36}

完全なファイルパスで指定された MHTML ソースを PDF に変換します。結果は、[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | MHTML ソースの完全ファイルパス。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options) をご覧ください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## 備考

MHTML コンバータ

MHTML を PDF に変換することは、特定のタスクで [PDF](https://docs.fileformat.com/pdf/) フォーマットを活用するためにしばしば必要です。PDF は他のファイルにはない多くの利点を持っています。例えば、多くのプログラムやアプリが PDF ドキュメントをサポートしており、PDF ファイルは印刷に最適化されていて、文書の紙媒体コピーを作成するのに理想的です。また、PDF ファイルのセキュリティ設定を構成でき、印刷や編集、電子署名の使用などを無効にすることができます。

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertMHTML() メソッドを使用して MHTML を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

MHTML を PDF に変換

Converter クラスは、MHTML 固有の PDF への変換をいくつか提供します。MHTML を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート URL を変換元として検出します。標準またはカスタムの特定の [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) をソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を PDF 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質・簡単・高速に PDF に変換する無料のオンライン [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // ICreateStreamProvider の実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertmhtml_4}

[`URL`](../../../com.aspose.html/url/) で提供される MHTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | MHTML ソースドキュメントの URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#save-options) をご覧ください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## 備考

MHTML コンバータ

MHTML を PDF に変換することは、特定のタスクで [PDF](https://docs.fileformat.com/pdf/) フォーマットを活用するためにしばしば必要です。PDF は他のファイルにはない多くの利点を持っています。例えば、多くのプログラムやアプリが PDF ドキュメントをサポートしており、PDF ファイルは印刷に最適化されていて、文書の紙媒体コピーを作成するのに理想的です。また、PDF ファイルのセキュリティ設定を構成でき、印刷や編集、電子署名の使用などを無効にすることができます。

[article](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertMHTML() メソッドを使用して MHTML を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

MHTML を PDF に変換

Converter クラスは、MHTML 固有の PDF への変換をいくつか提供します。MHTML を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート URL を変換元として検出します。標準またはカスタムの特定の [stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-6.0) をソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を PDF 結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質・簡単・高速に PDF に変換する無料のオンライン [MHTML to PDF Converter](https://products.aspose.app/html/en/conversion/mhtml-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // ICreateStreamProvider の実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, ImageSaveOptions, String) {#convertmhtml_27}

入力ストリームで提示された MHTML ソースを画像に変換します。結果は出力ファイルパスで作成された画像ファイルです。

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | MHTML 変換の入力データストリーム。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## 備考

MHTML コンバータ

拡張子が [MHTML](https://docs.fileformat.com/web/mhtml/) のファイルは、さまざまなアプリケーションが作成できるウェブページアーカイブ形式を表します。この形式は、ウェブの HTML コードと関連リソースを単一ファイルに保存するため、アーカイブ形式として知られています。これらのリソースには、画像、アプレット、アニメーション、音声ファイルなど、ウェブページにリンクされたすべてが含まれます。MHTML ファイルは、Internet Explorer や Microsoft Word などのさまざまなアプリケーションで開くことができます。形式の実際の仕様は、[RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) に詳述されています。

記事を参照してください。そこでは、Converter クラスの ConvertMHTML() メソッドを使用して MHTML をさまざまな形式の画像に変換する方法と、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータを適用する方法が記載されています。

MHTML を画像に変換

Converter クラスは、MHTML を画像に変換するいくつかの機能を提供します。サポートされている形式は [JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[GIF](https://docs.fileformat.com/image/gif/) および [TIFF](https://docs.fileformat.com/image/tiff/) です。MHTML を画像に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。標準またはカスタムの特定のストリームをソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG です。オプションパラメータとして configuration を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を画像結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質・簡単・高速に JPEG ファイルに変換する無料のオンライン [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // 変換プロセスを開始する
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, ImageSaveOptions, String) {#convertmhtml_43}

完全なファイルパスで提示された MHTML ソースを変換します。結果は出力ファイルパスで作成された画像ファイルです。

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | MHTML ソースの完全ファイルパス。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## 備考

MHTML コンバータ

拡張子が [MHTML](https://docs.fileformat.com/web/mhtml/) のファイルは、さまざまなアプリケーションが作成できるウェブページアーカイブ形式を表します。この形式は、ウェブの HTML コードと関連リソースを単一ファイルに保存するため、アーカイブ形式として知られています。これらのリソースには、画像、アプレット、アニメーション、音声ファイルなど、ウェブページにリンクされたすべてが含まれます。MHTML ファイルは、Internet Explorer や Microsoft Word などのさまざまなアプリケーションで開くことができます。形式の実際の仕様は、[RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) に詳述されています。

記事を参照してください。そこでは、Converter クラスの ConvertMHTML() メソッドを使用して MHTML をさまざまな形式の画像に変換する方法と、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータを適用する方法が記載されています。

MHTML を画像に変換

Converter クラスは、MHTML を画像に変換するいくつかの機能を提供します。サポートされている形式は [JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[GIF](https://docs.fileformat.com/image/gif/) および [TIFF](https://docs.fileformat.com/image/tiff/) です。MHTML を画像に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。標準またはカスタムの特定のストリームをソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG です。オプションパラメータとして configuration を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を画像結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質・簡単・高速に JPEG ファイルに変換する無料のオンライン [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // 変換プロセスを開始する
      Converter.ConvertMHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, ImageSaveOptions, String) {#convertmhtml_11}

URL で指定された MHTML ソースを変換します。結果は、出力ファイルパスで作成された画像ファイルです。

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | MHTML ソースドキュメントの URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## 備考

MHTML コンバータ

拡張子が [MHTML](https://docs.fileformat.com/web/mhtml/) のファイルは、さまざまなアプリケーションが作成できるウェブページアーカイブ形式を表します。この形式は、ウェブの HTML コードと関連リソースを単一ファイルに保存するため、アーカイブ形式として知られています。これらのリソースには、画像、アプレット、アニメーション、音声ファイルなど、ウェブページにリンクされたすべてが含まれます。MHTML ファイルは、Internet Explorer や Microsoft Word などのさまざまなアプリケーションで開くことができます。形式の実際の仕様は、[RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) に詳述されています。

記事を参照してください。そこでは、Converter クラスの ConvertMHTML() メソッドを使用して MHTML をさまざまな形式の画像に変換する方法と、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータを適用する方法が記載されています。

MHTML を画像に変換

Converter クラスは、MHTML を画像に変換するいくつかの機能を提供します。サポートされている形式は [JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[GIF](https://docs.fileformat.com/image/gif/) および [TIFF](https://docs.fileformat.com/image/tiff/) です。MHTML を画像に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。標準またはカスタムの特定のストリームをソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG です。オプションパラメータとして configuration を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を画像結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質・簡単・高速に JPEG ファイルに変換する無料のオンライン [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // 変換プロセスを開始する
      Converter.ConvertMHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, String) {#convertmhtml_19}

入力ストリームで提示された MHTML ソースを画像に変換します。結果は出力ファイルパスで作成された画像ファイルです。

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | MHTML 変換の入力データストリーム。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## 備考

MHTML コンバータ

拡張子が [MHTML](https://docs.fileformat.com/web/mhtml/) のファイルは、さまざまなアプリケーションが作成できるウェブページアーカイブ形式を表します。この形式は、ウェブの HTML コードと関連リソースを単一ファイルに保存するため、アーカイブ形式として知られています。これらのリソースには、画像、アプレット、アニメーション、音声ファイルなど、ウェブページにリンクされたすべてが含まれます。MHTML ファイルは、Internet Explorer や Microsoft Word などのさまざまなアプリケーションで開くことができます。形式の実際の仕様は、[RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) に詳述されています。

記事を参照してください。そこでは、Converter クラスの ConvertMHTML() メソッドを使用して MHTML をさまざまな形式の画像に変換する方法と、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータを適用する方法が記載されています。

MHTML を画像に変換

Converter クラスは、MHTML を画像に変換するいくつかの機能を提供します。サポートされている形式は [JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[GIF](https://docs.fileformat.com/image/gif/) および [TIFF](https://docs.fileformat.com/image/tiff/) です。MHTML を画像に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。標準またはカスタムの特定のストリームをソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG です。オプションパラメータとして configuration を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を画像結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質・簡単・高速に JPEG ファイルに変換する無料のオンライン [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, ImageSaveOptions, String) {#convertmhtml_35}

完全なファイルパスで提示された MHTML ソースを変換します。結果は出力ファイルパスで作成された画像ファイルです。

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | MHTML ソースの完全ファイルパス。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## 備考

MHTML コンバータ

拡張子が [MHTML](https://docs.fileformat.com/web/mhtml/) のファイルは、さまざまなアプリケーションが作成できるウェブページアーカイブ形式を表します。この形式は、ウェブの HTML コードと関連リソースを単一ファイルに保存するため、アーカイブ形式として知られています。これらのリソースには、画像、アプレット、アニメーション、音声ファイルなど、ウェブページにリンクされたすべてが含まれます。MHTML ファイルは、Internet Explorer や Microsoft Word などのさまざまなアプリケーションで開くことができます。形式の実際の仕様は、[RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) に詳述されています。

記事を参照してください。そこでは、Converter クラスの ConvertMHTML() メソッドを使用して MHTML をさまざまな形式の画像に変換する方法と、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータを適用する方法が記載されています。

MHTML を画像に変換

Converter クラスは、MHTML を画像に変換するいくつかの機能を提供します。サポートされている形式は [JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[GIF](https://docs.fileformat.com/image/gif/) および [TIFF](https://docs.fileformat.com/image/tiff/) です。MHTML を画像に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。標準またはカスタムの特定のストリームをソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG です。オプションパラメータとして configuration を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を画像結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質・簡単・高速に JPEG ファイルに変換する無料のオンライン [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, ImageSaveOptions, String) {#convertmhtml_3}

URL で指定された MHTML ソースを変換します。結果は、出力ファイルパスで作成された画像ファイルです。

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | MHTML ソースドキュメントの URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## 備考

MHTML コンバータ

拡張子が [MHTML](https://docs.fileformat.com/web/mhtml/) のファイルは、さまざまなアプリケーションが作成できるウェブページアーカイブ形式を表します。この形式は、ウェブの HTML コードと関連リソースを単一ファイルに保存するため、アーカイブ形式として知られています。これらのリソースには、画像、アプレット、アニメーション、音声ファイルなど、ウェブページにリンクされたすべてが含まれます。MHTML ファイルは、Internet Explorer や Microsoft Word などのさまざまなアプリケーションで開くことができます。形式の実際の仕様は、[RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) に詳述されています。

記事を参照してください。そこでは、Converter クラスの ConvertMHTML() メソッドを使用して MHTML をさまざまな形式の画像に変換する方法と、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータを適用する方法が記載されています。

MHTML を画像に変換

Converter クラスは、MHTML を画像に変換するいくつかの機能を提供します。サポートされている形式は [JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[GIF](https://docs.fileformat.com/image/gif/) および [TIFF](https://docs.fileformat.com/image/tiff/) です。MHTML を画像に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。標準またはカスタムの特定のストリームをソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG です。オプションパラメータとして configuration を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を画像結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質・簡単・高速に JPEG ファイルに変換する無料のオンライン [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_26}

入力ストリームで提供される MHTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertMHTML(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | MHTML 変換の入力データストリーム。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## 備考

MHTML コンバータ

拡張子が [MHTML](https://docs.fileformat.com/web/mhtml/) のファイルは、さまざまなアプリケーションが作成できるウェブページアーカイブ形式を表します。この形式は、ウェブの HTML コードと関連リソースを単一ファイルに保存するため、アーカイブ形式として知られています。これらのリソースには、画像、アプレット、アニメーション、音声ファイルなど、ウェブページにリンクされたすべてが含まれます。MHTML ファイルは、Internet Explorer や Microsoft Word などのさまざまなアプリケーションで開くことができます。形式の実際の仕様は、[RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) に詳述されています。

記事を参照してください。そこでは、Converter クラスの ConvertMHTML() メソッドを使用して MHTML をさまざまな形式の画像に変換する方法と、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータを適用する方法が記載されています。

MHTML を画像に変換

Converter クラスは、MHTML を画像に変換するいくつかの機能を提供します。サポートされている形式は [JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[GIF](https://docs.fileformat.com/image/gif/) および [TIFF](https://docs.fileformat.com/image/tiff/) です。MHTML を画像に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。標準またはカスタムの特定のストリームをソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG です。オプションパラメータとして configuration を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を画像結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質・簡単・高速に JPEG ファイルに変換する無料のオンライン [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider の実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_42}

完全なファイルパスで指定された MHTML ソースを画像に変換します。結果は、[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertMHTML(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | MHTML ソースの完全ファイルパス。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装。 |

## 備考

MHTML コンバータ

拡張子が [MHTML](https://docs.fileformat.com/web/mhtml/) のファイルは、さまざまなアプリケーションが作成できるウェブページアーカイブ形式を表します。この形式は、ウェブの HTML コードと関連リソースを単一ファイルに保存するため、アーカイブ形式として知られています。これらのリソースには、画像、アプレット、アニメーション、音声ファイルなど、ウェブページにリンクされたすべてが含まれます。MHTML ファイルは、Internet Explorer や Microsoft Word などのさまざまなアプリケーションで開くことができます。形式の実際の仕様は、[RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) に詳述されています。

記事を参照してください。そこでは、Converter クラスの ConvertMHTML() メソッドを使用して MHTML をさまざまな形式の画像に変換する方法と、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータを適用する方法が記載されています。

MHTML を画像に変換

Converter クラスは、MHTML を画像に変換するいくつかの機能を提供します。サポートされている形式は [JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[GIF](https://docs.fileformat.com/image/gif/) および [TIFF](https://docs.fileformat.com/image/tiff/) です。MHTML を画像に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。標準またはカスタムの特定のストリームをソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG です。オプションパラメータとして configuration を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を画像結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質・簡単・高速に JPEG ファイルに変換する無料のオンライン [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions();

      // ICreateStreamProvider の実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 変換プロセスを開始する
      Converter.ConvertMHTML(sourcePath, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_10}

URL で提供される MHTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertMHTML(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | MHTML ソースドキュメントの URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装。 |

## 備考

MHTML コンバータ

拡張子が [MHTML](https://docs.fileformat.com/web/mhtml/) のファイルは、さまざまなアプリケーションが作成できるウェブページアーカイブ形式を表します。この形式は、ウェブの HTML コードと関連リソースを単一ファイルに保存するため、アーカイブ形式として知られています。これらのリソースには、画像、アプレット、アニメーション、音声ファイルなど、ウェブページにリンクされたすべてが含まれます。MHTML ファイルは、Internet Explorer や Microsoft Word などのさまざまなアプリケーションで開くことができます。形式の実際の仕様は、[RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) に詳述されています。

記事を参照してください。そこでは、Converter クラスの ConvertMHTML() メソッドを使用して MHTML をさまざまな形式の画像に変換する方法と、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータを適用する方法が記載されています。

MHTML を画像に変換

Converter クラスは、MHTML を画像に変換するいくつかの機能を提供します。サポートされている形式は [JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[GIF](https://docs.fileformat.com/image/gif/) および [TIFF](https://docs.fileformat.com/image/tiff/) です。MHTML を画像に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。標準またはカスタムの特定のストリームをソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG です。オプションパラメータとして configuration を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を画像結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質・簡単・高速に JPEG ファイルに変換する無料のオンライン [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // ICreateStreamProvider の実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 変換プロセスを開始する
      Converter.ConvertMHTML(sourceUrl, options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_18}

入力ストリームで提供される MHTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertMHTML(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | MHTML 変換の入力データストリーム。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## 備考

MHTML コンバータ

拡張子が [MHTML](https://docs.fileformat.com/web/mhtml/) のファイルは、さまざまなアプリケーションが作成できるウェブページアーカイブ形式を表します。この形式は、ウェブの HTML コードと関連リソースを単一ファイルに保存するため、アーカイブ形式として知られています。これらのリソースには、画像、アプレット、アニメーション、音声ファイルなど、ウェブページにリンクされたすべてが含まれます。MHTML ファイルは、Internet Explorer や Microsoft Word などのさまざまなアプリケーションで開くことができます。形式の実際の仕様は、[RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) に詳述されています。

記事を参照してください。そこでは、Converter クラスの ConvertMHTML() メソッドを使用して MHTML をさまざまな形式の画像に変換する方法と、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータを適用する方法が記載されています。

MHTML を画像に変換

Converter クラスは、MHTML を画像に変換するいくつかの機能を提供します。サポートされている形式は [JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[GIF](https://docs.fileformat.com/image/gif/) および [TIFF](https://docs.fileformat.com/image/tiff/) です。MHTML を画像に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。標準またはカスタムの特定のストリームをソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG です。オプションパラメータとして configuration を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を画像結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質・簡単・高速に JPEG ファイルに変換する無料のオンライン [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider の実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertMHTML(System.IO.File.OpenRead(sourcePath), new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_34}

完全なファイルパスで指定された MHTML ソースを画像に変換します。結果は、[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertMHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | MHTML ソースの完全ファイルパス。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [` interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## 備考

MHTML コンバータ

拡張子が [MHTML](https://docs.fileformat.com/web/mhtml/) のファイルは、さまざまなアプリケーションが作成できるウェブページアーカイブ形式を表します。この形式は、ウェブの HTML コードと関連リソースを単一ファイルに保存するため、アーカイブ形式として知られています。これらのリソースには、画像、アプレット、アニメーション、音声ファイルなど、ウェブページにリンクされたすべてが含まれます。MHTML ファイルは、Internet Explorer や Microsoft Word などのさまざまなアプリケーションで開くことができます。形式の実際の仕様は、[RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) に詳述されています。

記事を参照してください。そこでは、Converter クラスの ConvertMHTML() メソッドを使用して MHTML をさまざまな形式の画像に変換する方法と、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータを適用する方法が記載されています。

MHTML を画像に変換

Converter クラスは、MHTML を画像に変換するいくつかの機能を提供します。サポートされている形式は [JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[GIF](https://docs.fileformat.com/image/gif/) および [TIFF](https://docs.fileformat.com/image/tiff/) です。MHTML を画像に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。標準またはカスタムの特定のストリームをソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG です。オプションパラメータとして configuration を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を画像結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質・簡単・高速に JPEG ファイルに変換する無料のオンライン [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.mht");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions();

      // ICreateStreamProvider の実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertMHTML(sourcePath, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMHTML(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertmhtml_2}

URL で提供される MHTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertMHTML(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | MHTML ソースドキュメントの URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## 備考

MHTML コンバータ

拡張子が [MHTML](https://docs.fileformat.com/web/mhtml/) のファイルは、さまざまなアプリケーションが作成できるウェブページアーカイブ形式を表します。この形式は、ウェブの HTML コードと関連リソースを単一ファイルに保存するため、アーカイブ形式として知られています。これらのリソースには、画像、アプレット、アニメーション、音声ファイルなど、ウェブページにリンクされたすべてが含まれます。MHTML ファイルは、Internet Explorer や Microsoft Word などのさまざまなアプリケーションで開くことができます。形式の実際の仕様は、[RFC 2557](https://datatracker.ietf.org/doc/html/rfc2557) に詳述されています。

記事を参照してください。そこでは、Converter クラスの ConvertMHTML() メソッドを使用して MHTML をさまざまな形式の画像に変換する方法と、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) および [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータを適用する方法が記載されています。

MHTML を画像に変換

Converter クラスは、MHTML を画像に変換するいくつかの機能を提供します。サポートされている形式は [JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[GIF](https://docs.fileformat.com/image/gif/) および [TIFF](https://docs.fileformat.com/image/tiff/) です。MHTML を画像に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル MHTML (.mht) ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。標準またはカスタムの特定のストリームをソースとして使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG です。オプションパラメータとして configuration を追加することもできます。Converter クラスの ConvertMHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで MHTML を画像結果として保存します。オンライン MHTML コンバータ

Aspose.HTML は、MHTML を高品質・簡単・高速に JPEG ファイルに変換する無料のオンライン [MHTML to JPEG Converter](https://products.aspose.app/html/en/conversion/mhtml-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.mht"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // ICreateStreamProvider の実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertMHTML(sourceUrl, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
