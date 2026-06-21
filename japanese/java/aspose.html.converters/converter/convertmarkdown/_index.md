---
title: "Converter.ConvertMarkdown"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Converter メソッド。入力ストリームで提供される MD マークダウン ソースを HTML に変換します。結果は HTMLDocument で、出力ファイルパスを通じて保存できます。"
type: docs

url: /ja/java/com.aspose.html.converters/converter/convertmarkdown/
---
## ConvertMarkdown(Stream, String) {#convertmarkdown}

入力ストリームで提供される MD（マークダウン）ソースを HTML に変換します。結果は [`HTMLDocument`](../../../com.aspose.html/htmldocument/) で、出力ファイルパスを通じて保存できます。

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | MD（マークダウン）変換用入力データストリーム。 |
| baseUri | 文字列 | ドキュメントのベース URI。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |

### 戻り値

変換結果として新しく生成された [`HTMLDocument`](../../../com.aspose.html/htmldocument/) は、出力ファイルパスを通じて保存できます。

## 備考

Markdown コンバータ

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

変換手順

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル MD ファイルを検出するか、入力データストリームを変換ソースとして作成します。変換結果。メソッド署名に応じて、直接 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) を取得するか、結果の出力ファイルパスを定義できます。Converter クラスの ConvertMarkdown() メソッドを使用して MD を HTML 結果として保存します。また、オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加できます。オンライン MD コンバータ

無料のオンライン [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) にも興味があるかもしれません。このツールは高品質で簡単かつ高速に MD を HTML に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！また、他のオンライン MD コンバータも確認できます：[MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf)、[MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx)、[MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) そして適切な [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) を見つけてください。

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.html");
       
      // ソースファイルをストリームとして開く
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // 変換プロセスを開始する
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty);
         
        // 変換結果を保存
        document.Save(resultPath);
      }





*InputFolder - user source folder path.



```

*OutputFolder - user output file path.

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration) {#convertmarkdown_1}

入力ストリームで提供される MD（マークダウン）ソースを HTML に変換します。結果は [`HTMLDocument`](../../../com.aspose.html/htmldocument/) で、出力ファイルパスを通じて保存できます。

```java
public static HTMLDocument ConvertMarkdown(Stream stream, String baseUri, 
    Configuration configuration)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | MD（マークダウン）変換用入力データストリーム。 |
| baseUri | 文字列 | ドキュメントのベース URI。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |

### 戻り値

変換結果として新しく生成された [`HTMLDocument`](../../../com.aspose.html/htmldocument/) は、出力ファイルパスを通じて保存できます。

## 備考

Markdown コンバータ

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

変換手順

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル MD ファイルを検出するか、入力データストリームを変換ソースとして作成します。変換結果。メソッド署名に応じて、直接 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) を取得するか、結果の出力ファイルパスを定義できます。Converter クラスの ConvertMarkdown() メソッドを使用して MD を HTML 結果として保存します。また、オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加できます。オンライン MD コンバータ

無料のオンライン [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) にも興味があるかもしれません。このツールは高品質で簡単かつ高速に MD を HTML に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！また、他のオンライン MD コンバータも確認できます：[MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf)、[MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx)、[MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) そして適切な [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) を見つけてください。

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // ソースファイルをストリームとして開く
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // デフォルト構成で変換プロセスを開始する
        var document = Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration());

        // 変換結果を保存
        document.Save(resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, String) {#convertmarkdown_5}

入力ストリームで提示された MD（markdown）ソースを html に変換します。結果は出力ファイルパスで作成された html ファイルです。

```java
public static void ConvertMarkdown(Stream stream, String baseUri, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | MD（マークダウン）変換用入力データストリーム。 |
| baseUri | 文字列 | ドキュメントのベース URI。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |
| outputPath | 文字列 | 出力変換結果としての完全な HTML ファイルパス。 |

## 備考

Markdown コンバータ

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

変換手順

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル MD ファイルを検出するか、入力データストリームを変換ソースとして作成します。変換結果。メソッド署名に応じて、直接 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) を取得するか、結果の出力ファイルパスを定義できます。Converter クラスの ConvertMarkdown() メソッドを使用して MD を HTML 結果として保存します。また、オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加できます。オンライン MD コンバータ

無料のオンライン [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) にも興味があるかもしれません。このツールは高品質で簡単かつ高速に MD を HTML に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！また、他のオンライン MD コンバータも確認できます：[MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf)、[MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx)、[MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) そして適切な [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) を見つけてください。

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // ソースファイルをストリームとして開く
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // 変換プロセスを開始する
        Converter.ConvertMarkdown(sourceStream, String.Empty, resultPath);
      }





*InputFolder - user source folder path.

```

*OutputFolder - user output file path.

### 関連項目

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(Stream, String, Configuration, String) {#convertmarkdown_4}

入力ストリームで提示された MD（markdown）ソースを html に変換します。結果は出力ファイルパスで作成された html ファイルです。

```java
public static void ConvertMarkdown(Stream stream, String baseUri, Configuration configuration, 
    String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | MD（マークダウン）変換用入力データストリーム。 |
| baseUri | 文字列 | ドキュメントのベース URI。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| outputPath | 文字列 | 出力変換結果としての完全な HTML ファイルパス。 |

## 備考

Markdown コンバータ

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

変換手順

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル MD ファイルを検出するか、入力データストリームを変換ソースとして作成します。変換結果。メソッド署名に応じて、直接 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) を取得するか、結果の出力ファイルパスを定義できます。Converter クラスの ConvertMarkdown() メソッドを使用して MD を HTML 結果として保存します。また、オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加できます。オンライン MD コンバータ

無料のオンライン [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) にも興味があるかもしれません。このツールは高品質で簡単かつ高速に MD を HTML に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！また、他のオンライン MD コンバータも確認できます：[MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf)、[MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx)、[MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) そして適切な [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) を見つけてください。

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // ソースファイルをストリームとして開く
      using (var sourceStream = File.OpenRead(sourcePath))
      {
        // デフォルト構成で変換プロセスを開始する
        Converter.ConvertMarkdown(sourceStream, String.Empty, new Configuration(), resultPath);
      }
```

*InputFolder - user source folder path.

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String) {#convertmarkdown_2}

完全なファイルパスで提供される MD（マークダウン）ソースを HTML に変換します。結果は [`HTMLDocument`](../../../com.aspose.html/htmldocument/) で、出力ファイルパスを通じて保存できます。

```java
public static HTMLDocument ConvertMarkdown(String sourcePath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | MD（マークダウン）ソースの完全なファイルパス。 |

### 戻り値

変換結果として新しく生成された [`HTMLDocument`](../../../com.aspose.html/htmldocument/) は、出力ファイルパスを通じて保存できます。

## 備考

Markdown コンバータ

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

変換手順

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル MD ファイルを検出するか、入力データストリームを変換ソースとして作成します。変換結果。メソッド署名に応じて、直接 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) を取得するか、結果の出力ファイルパスを定義できます。Converter クラスの ConvertMarkdown() メソッドを使用して MD を HTML 結果として保存します。また、オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加できます。オンライン MD コンバータ

無料のオンライン [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) にも興味があるかもしれません。このツールは高品質で簡単かつ高速に MD を HTML に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！また、他のオンライン MD コンバータも確認できます：[MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf)、[MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx)、[MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) そして適切な [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) を見つけてください。

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 変換プロセスを開始する
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath))
      {
        // 変換結果をローカルファイルとして保存
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration) {#convertmarkdown_3}

完全なファイルパスで提供される MD（マークダウン）ソースを HTML に変換します。結果は [`HTMLDocument`](../../../com.aspose.html/htmldocument/) で、出力ファイルパスを通じて保存できます。

```java
public static HTMLDocument ConvertMarkdown(String sourcePath, Configuration configuration)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | MD（マークダウン）ソースの完全なファイルパス。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |

### 戻り値

変換結果として新しく生成された [`HTMLDocument`](../../../com.aspose.html/htmldocument/) は、出力ファイルパスを通じて保存できます。

## 備考

Markdown コンバータ

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

変換手順

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル MD ファイルを検出するか、入力データストリームを変換ソースとして作成します。変換結果。メソッド署名に応じて、直接 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) を取得するか、結果の出力ファイルパスを定義できます。Converter クラスの ConvertMarkdown() メソッドを使用して MD を HTML 結果として保存します。また、オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加できます。オンライン MD コンバータ

無料のオンライン [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) にも興味があるかもしれません。このツールは高品質で簡単かつ高速に MD を HTML に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！また、他のオンライン MD コンバータも確認できます：[MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf)、[MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx)、[MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) そして適切な [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) を見つけてください。

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // デフォルト構成で変換プロセスを開始する
      using (HTMLDocument document = Converter.ConvertMarkdown(sourcePath, new Configuration()))
      {
        // 変換結果をローカルファイルとして保存
        document.Save(resultPath);
      }
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, String) {#convertmarkdown_7}

完全なファイルパスで提示された MD（markdown）ソースを html に変換します。結果は出力ファイルパスで作成された html ファイルです。

```java
public static void ConvertMarkdown(String sourcePath, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | ソース Markdown ファイルへのパス。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |
| outputPath | 文字列 | 出力変換結果としての完全な HTML ファイルパス。 |

## 備考

Markdown コンバータ

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

変換手順

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル MD ファイルを検出するか、入力データストリームを変換ソースとして作成します。変換結果。メソッド署名に応じて、直接 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) を取得するか、結果の出力ファイルパスを定義できます。Converter クラスの ConvertMarkdown() メソッドを使用して MD を HTML 結果として保存します。また、オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加できます。オンライン MD コンバータ

無料のオンライン [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) にも興味があるかもしれません。このツールは高品質で簡単かつ高速に MD を HTML に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！また、他のオンライン MD コンバータも確認できます：[MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf)、[MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx)、[MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) そして適切な [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) を見つけてください。

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // 変換プロセスを開始する
      Converter.ConvertMarkdown(sourcePath, resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### 関連項目

* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertMarkdown(String, Configuration, String) {#convertmarkdown_6}

完全なファイルパスで提示された MD（markdown）ソースを html に変換します。結果は出力ファイルパスで作成された html ファイルです。

```java
public static void ConvertMarkdown(String sourcePath, Configuration configuration, 
    String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | ソース Markdown ファイルへのパス。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| outputPath | 文字列 | 出力変換結果としての完全な HTML ファイルパス。 |

## 備考

Markdown コンバータ

[MD](https://docs.fileformat.com/word-processing/md/) (Markdown) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. Its design allows it to be easily converted to many output formats, but initially it was created to convert only to HTML. Using the Aspose.HTML class library in your C# application, you can easily convert Markdown into an HTML file with just a few lines of code! Refer to [article](https://docs.aspose.com/html/net/converting-between-formats/markdown-converter/), where you find more information.

変換手順

[`Converter`](../) class offers few ways to convert MD to html wherein you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル MD ファイルを検出するか、入力データストリームを変換ソースとして作成します。変換結果。メソッド署名に応じて、直接 [`HTMLDocument`](../../../com.aspose.html/htmldocument/) を取得するか、結果の出力ファイルパスを定義できます。Converter クラスの ConvertMarkdown() メソッドを使用して MD を HTML 結果として保存します。また、オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加できます。オンライン MD コンバータ

無料のオンライン [MD to HTML Converter](https://products.aspose.app/html/en/conversion/md-to-html) にも興味があるかもしれません。このツールは高品質で簡単かつ高速に MD を HTML に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！また、他のオンライン MD コンバータも確認できます：[MD to PDF](https://products.aspose.app/html/en/conversion/md-to-pdf)、[MD to DOCX](https://products.aspose.app/html/en/conversion/md-to-docx)、[MD to XPS](https://products.aspose.app/html/en/conversion/md-to-xps) そして適切な [MD to image converters](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) を見つけてください。

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
      var sourcePath = Path.Combine(InputFolder, "simple.md");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.html");

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertMarkdown(sourcePath, new Configuration(), resultPath);
```

*InputFolder - user source template folder.

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
