---
title: "Converter.ConvertHTML"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Converter メソッド。HTMLDocument によって提示された HTML ソースを変換します。結果は出力ファイルパスで作成された docx ファイルです。"
type: docs

url: /ja/java/com.aspose.html.converters/converter/converthtml/
---
## ConvertHTML(HTMLDocument, DocSaveOptions, String) {#converthtml_1}

[`HTMLDocument`](../../../com.aspose.html/htmldocument/) によって提示された HTML ソースを変換します。結果は出力ファイルパスで作成された docx ファイルです。

```java
public static void ConvertHTML(HTMLDocument document, DocSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| document | HTMLDocument | [`HTMLDocument`](../../../com.aspose.html/htmldocument/) インスタンスを変換ソースとして使用します。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な docx ファイルパス。 |

## Remarks

HTML を DOCX に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

DOCX 変換

DOCX ファイルは Microsoft Word の文書で、通常はテキストを含みますが、表、ラスタおよびベクター グラフィック、ビデオ、音声、図など、さまざまなデータを含めることができます。DOCX ファイルは高度に編集可能で、使いやすく、サイズも管理しやすいです。この形式は、ユーザーがあらゆる種類の文書を書ける多様なオプションを提供するために人気があります。このファイル形式は最も広く使用されているものの一つで、数多くのプログラムで利用可能です。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を DOCX に変換

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで HTML を DOCX 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
	// フォームのソースファイルパス
	var sourcePath = Path.Combine(InputFolder, "source.html");
	
    // デフォルトの構成オブジェクトをインスタンス化する
    var configuration = new Configuration();  

	using (var document = new HTMLDocument(sourcePath, configuration))
	{
		// 出力ファイルパスを定義する
        var resultPath = Path.Combine(OutputFolder, "result.docx");
         
		// デフォルトの DocSaveOptions オブジェクトを定義する
        var options = new DocSaveOptions();
         
		// デフォルトの構成オブジェクトで変換プロセスを開始する
		Converter.ConvertHTML(document, options, resultPath);
	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, DocSaveOptions, String) {#converthtml_23}

URLで提示されたHTMLソースを変換します。結果は、出力ファイルパスによって生成されたdocxファイルです。

```java
public static void ConvertHTML(Url url, DocSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | HTML ソースドキュメント URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な docx ファイルパス。 |

## Remarks

HTML を DOCX に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

DOCX 変換

DOCX ファイルは Microsoft Word の文書で、通常はテキストを含みますが、表、ラスタおよびベクター グラフィック、ビデオ、音声、図など、さまざまなデータを含めることができます。DOCX ファイルは高度に編集可能で、使いやすく、サイズも管理しやすいです。この形式は、ユーザーがあらゆる種類の文書を書ける多様なオプションを提供するために人気があります。このファイル形式は最も広く使用されているものの一つで、数多くのプログラムで利用可能です。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を DOCX に変換

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで HTML を DOCX 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertHTML(sourceUrl, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, DocSaveOptions, String) {#converthtml_12}

URLで提示されたHTMLソースを変換します。結果は、出力ファイルパスによって生成されたdocxファイルです。

```java
public static void ConvertHTML(Url url, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | HTML ソースドキュメント URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な docx ファイルパス。 |

## Remarks

HTML を DOCX に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

DOCX 変換

DOCX ファイルは Microsoft Word の文書で、通常はテキストを含みますが、表、ラスタおよびベクター グラフィック、ビデオ、音声、図など、さまざまなデータを含めることができます。DOCX ファイルは高度に編集可能で、使いやすく、サイズも管理しやすいです。この形式は、ユーザーがあらゆる種類の文書を書ける多様なオプションを提供するために人気があります。このファイル形式は最も広く使用されているものの一つで、数多くのプログラムで利用可能です。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を DOCX に変換

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで HTML を DOCX 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // デフォルトの構成オブジェクトで変換プロセスを開始する
      Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertHTML(String, DocSaveOptions, String) {#converthtml_45}

完全なファイルパスで提示されたHTMLソースをDOCXに変換します。結果は、出力ファイルパスによって生成されたdocxファイルです。

```java
public static void ConvertHTML(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | Html 完全ファイルソースパス。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な docx ファイルパス。 |

## Remarks

HTML を DOCX に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

DOCX 変換

DOCX ファイルは Microsoft Word の文書で、通常はテキストを含みますが、表、ラスタおよびベクター グラフィック、ビデオ、音声、図など、さまざまなデータを含めることができます。DOCX ファイルは高度に編集可能で、使いやすく、サイズも管理しやすいです。この形式は、ユーザーがあらゆる種類の文書を書ける多様なオプションを提供するために人気があります。このファイル形式は最も広く使用されているものの一つで、数多くのプログラムで利用可能です。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を DOCX に変換

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで HTML を DOCX 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, DocSaveOptions, String) {#converthtml_34}

完全なファイルパスで提示されたHTMLソースをDOCXに変換します。結果は、出力ファイルパスによって生成されたdocxファイルです。

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | Html 完全ファイルソースパス。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な docx ファイルパス。 |

## Remarks

HTML を DOCX に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

DOCX 変換

DOCX ファイルは Microsoft Word の文書で、通常はテキストを含みますが、表、ラスタおよびベクター グラフィック、ビデオ、音声、図など、さまざまなデータを含めることができます。DOCX ファイルは高度に編集可能で、使いやすく、サイズも管理しやすいです。この形式は、ユーザーがあらゆる種類の文書を書ける多様なオプションを提供するために人気があります。このファイル形式は最も広く使用されているものの一つで、数多くのプログラムで利用可能です。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を DOCX に変換

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで HTML を DOCX 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // フォームのソースファイルパス
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // フォームの結果ファイルパス
   var resultPath = Path.Combine(OutputFolder, "result.docx");

   // デフォルトの DocSaveOptions オブジェクトを定義する
   var options = new DocSaveOptions();

   // デフォルト構成で変換プロセスを開始する
   Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertHTML(String, String, DocSaveOptions, String) {#converthtml_67}

インライン コンテンツで提示された HTML ソースを変換します。結果は出力ファイルパスで作成された docx ファイルです。

```java
public static void ConvertHTML(String content, String baseUri, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン HTML コンテンツとしての文字列。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な docx ファイルパス。 |

## Remarks

HTML を DOCX に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

DOCX 変換

DOCX ファイルは Microsoft Word の文書で、通常はテキストを含みますが、表、ラスタおよびベクター グラフィック、ビデオ、音声、図など、さまざまなデータを含めることができます。DOCX ファイルは高度に編集可能で、使いやすく、サイズも管理しやすいです。この形式は、ユーザーがあらゆる種類の文書を書ける多様なオプションを提供するために人気があります。このファイル形式は最も広く使用されているものの一つで、数多くのプログラムで利用可能です。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を DOCX に変換

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで HTML を DOCX 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// インライン HTML コンテンツを作成		
	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";
	
	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result.docx");

	// デフォルトの DocSaveOptions オブジェクトを定義する
   	var options = new DocSaveOptions();

	// 変換プロセスを開始する
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### 関連項目

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, DocSaveOptions, String) {#converthtml_56}

インライン コンテンツで提示された HTML ソースを変換します。結果は出力ファイルパスで作成された docx ファイルです。

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン HTML コンテンツとしての文字列。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な docx ファイルパス。 |

## Remarks

HTML を DOCX に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

DOCX 変換

DOCX ファイルは Microsoft Word の文書で、通常はテキストを含みますが、表、ラスタおよびベクター グラフィック、ビデオ、音声、図など、さまざまなデータを含めることができます。DOCX ファイルは高度に編集可能で、使いやすく、サイズも管理しやすいです。この形式は、ユーザーがあらゆる種類の文書を書ける多様なオプションを提供するために人気があります。このファイル形式は最も広く使用されているものの一つで、数多くのプログラムで利用可能です。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を DOCX に変換

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで HTML を DOCX 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// インライン HTML コンテンツを作成		
	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";
	
	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result.docx");
	
	// デフォルトの DocSaveOptions オブジェクトを定義する
   	var options = new DocSaveOptions();

	// デフォルト構成で変換プロセスを開始する
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, DocSaveOptions, ICreateStreamProvider) {#converthtml}

[`HTMLDocument`](../../../com.aspose.html/htmldocument/) によって提示された HTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertHTML(HTMLDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| document | HTMLDocument | [`HTMLDocument`](../../../com.aspose.html/htmldocument/) によって提示された変換ソースです。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

HTML を DOCX に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

DOCX 変換

DOCX ファイルは Microsoft Word の文書で、通常はテキストを含みますが、表、ラスタおよびベクター グラフィック、ビデオ、音声、図など、さまざまなデータを含めることができます。DOCX ファイルは高度に編集可能で、使いやすく、サイズも管理しやすいです。この形式は、ユーザーがあらゆる種類の文書を書ける多様なオプションを提供するために人気があります。このファイル形式は最も広く使用されているものの一つで、数多くのプログラムで利用可能です。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を DOCX に変換

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで HTML を DOCX 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// インライン HTML コンテンツを定義
      	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

      	// デフォルトの構成オブジェクトをインスタンス化する
      	var configuration = new Configuration();

      	// 複数の方法のいずれかで HTML ドキュメントを作成
      	using (var document = new HTMLDocument(content, String.Empty, configuration))
     	 {
        	// 拡張子なしの結果ファイルパスを定義
        	var resultPath = Path.Combine(OutputFolder, "result");

        	// ICreateStreamProvider 実装のいずれかを使用
        	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

			// デフォルトの DocSaveOptions オブジェクトを定義する
			var options = new DocSaveOptions();

        	// 変換プロセスを開始する
        	Converter.ConvertHTML(document, options, provider);
      	}
```

*OutputFolder - user output file path.

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, DocSaveOptions, ICreateStreamProvider) {#converthtml_22}

URL によって提示された HTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertHTML(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | HTML ソースドキュメント URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

HTML を DOCX に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

DOCX 変換

DOCX ファイルは Microsoft Word の文書で、通常はテキストを含みますが、表、ラスタおよびベクター グラフィック、ビデオ、音声、図など、さまざまなデータを含めることができます。DOCX ファイルは高度に編集可能で、使いやすく、サイズも管理しやすいです。この形式は、ユーザーがあらゆる種類の文書を書ける多様なオプションを提供するために人気があります。このファイル形式は最も広く使用されているものの一つで、数多くのプログラムで利用可能です。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を DOCX に変換

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで HTML を DOCX 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 	 
 	  // ソース URL を形成
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // 拡張子なしの結果ファイルパスを定義
      var resultPath = Path.Combine(OutputFolder, "result");

      // 既知の ICreateStreamProvider 実装を使用
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertHTML(sourceUrl, options, provider);
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

## ConvertHTML(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_11}

URL によって提示された HTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertHTML(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | HTML ソースドキュメント URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

HTML を DOCX に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

DOCX 変換

DOCX ファイルは Microsoft Word の文書で、通常はテキストを含みますが、表、ラスタおよびベクター グラフィック、ビデオ、音声、図など、さまざまなデータを含めることができます。DOCX ファイルは高度に編集可能で、使いやすく、サイズも管理しやすいです。この形式は、ユーザーがあらゆる種類の文書を書ける多様なオプションを提供するために人気があります。このファイル形式は最も広く使用されているものの一つで、数多くのプログラムで利用可能です。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を DOCX に変換

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで HTML を DOCX 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 	 
   // ソース URL を形成
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // 拡張子なしの結果ファイルパスを定義
   var resultPath = Path.Combine(OutputFolder, "result");

   // 既知の ICreateStreamProvider 実装を使用
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // デフォルトの DocSaveOptions オブジェクトを定義する
   var options = new DocSaveOptions();

   // デフォルト構成で変換プロセスを開始する
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, DocSaveOptions, ICreateStreamProvider) {#converthtml_44}

完全なファイルパスで提示された HTML ソースを DOCX に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertHTML(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | Html 完全ファイルソースパス。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

HTML を DOCX に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

DOCX 変換

DOCX ファイルは Microsoft Word の文書で、通常はテキストを含みますが、表、ラスタおよびベクター グラフィック、ビデオ、音声、図など、さまざまなデータを含めることができます。DOCX ファイルは高度に編集可能で、使いやすく、サイズも管理しやすいです。この形式は、ユーザーがあらゆる種類の文書を書ける多様なオプションを提供するために人気があります。このファイル形式は最も広く使用されているものの一つで、数多くのプログラムで利用可能です。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を DOCX に変換

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで HTML を DOCX 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // ソース HTML ファイルパスを形成
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // 結果ファイルパスを定義
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの ICreateStreamProvider 実装を使用
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertHTML(sourcePath, options, provider);
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

## ConvertHTML(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_33}

完全なファイルパスで提示された HTML ソースを DOCX に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | Html 完全ファイルソースパス。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions) を参照してください。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装です。 |

## Remarks

HTML を DOCX に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

DOCX 変換

DOCX ファイルは Microsoft Word の文書で、通常はテキストを含みますが、表、ラスタおよびベクター グラフィック、ビデオ、音声、図など、さまざまなデータを含めることができます。DOCX ファイルは高度に編集可能で、使いやすく、サイズも管理しやすいです。この形式は、ユーザーがあらゆる種類の文書を書ける多様なオプションを提供するために人気があります。このファイル形式は最も広く使用されているものの一つで、数多くのプログラムで利用可能です。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を DOCX に変換

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで HTML を DOCX 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // ソース HTML ファイルパスを形成
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // 結果ファイルパスを定義
   var resultPath = Path.Combine(OutputFolder, "result");

   // デフォルトの ICreateStreamProvider 実装を使用
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // デフォルトの DocSaveOptions オブジェクトを定義する
   var options = new DocSaveOptions();

   // デフォルトの構成オブジェクトで変換プロセスを開始する
   Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
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

## ConvertHTML(String, String, DocSaveOptions, ICreateStreamProvider) {#converthtml_66}

インライン コンテンツで提示された HTML ソースを DOCX に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertHTML(String content, String baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン HTML コンテンツとしての文字列。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

HTML を DOCX に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

DOCX 変換

DOCX ファイルは Microsoft Word の文書で、通常はテキストを含みますが、表、ラスタおよびベクター グラフィック、ビデオ、音声、図など、さまざまなデータを含めることができます。DOCX ファイルは高度に編集可能で、使いやすく、サイズも管理しやすいです。この形式は、ユーザーがあらゆる種類の文書を書ける多様なオプションを提供するために人気があります。このファイル形式は最も広く使用されているものの一つで、数多くのプログラムで利用可能です。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を DOCX に変換

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで HTML を DOCX 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	  // HTML インライン コンテンツを形成
      var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

      // 結果ファイルパスを定義
      var resultPath = Path.Combine(OutputFolder, "result");

      // 既知のローカルファイル指向 ICreateStreamProvider 実装を使用
      ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

      // デフォルトの DocSaveOptions オブジェクトをインスタンス化
      var options = new DocSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertHTML(content, String.Empty, options, provider);





```

*OutputFolder - user output file path.

### 関連項目

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, DocSaveOptions, ICreateStreamProvider) {#converthtml_55}

インライン コンテンツで提示された HTML ソースを DOCX に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン HTML コンテンツとしての文字列。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | DocSaveOptions | [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions) を参照してください。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装です。 |

## Remarks

HTML を DOCX に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

DOCX 変換

DOCX ファイルは Microsoft Word の文書で、通常はテキストを含みますが、表、ラスタおよびベクター グラフィック、ビデオ、音声、図など、さまざまなデータを含めることができます。DOCX ファイルは高度に編集可能で、使いやすく、サイズも管理しやすいです。この形式は、ユーザーがあらゆる種類の文書を書ける多様なオプションを提供するために人気があります。このファイル形式は最も広く使用されているものの一つで、数多くのプログラムで利用可能です。

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を DOCX に変換

[`Converter`](../) class offers wide range of HTML specific conversions to [DOCX](https://docs.fileformat.com/word-processing/docx/). To convert HTML to DOCX, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで HTML を DOCX 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [HTML to DOCX Converter](https://products.aspose.app/html/en/conversion/html-to-docx) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	 // HTML インライン コンテンツを形成
   var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

   // 結果ファイルパスを定義
   var resultPath = Path.Combine(OutputFolder, "result");

   // 既知のローカルファイル指向 ICreateStreamProvider 実装を使用
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // デフォルトの DocSaveOptions オブジェクトをインスタンス化
   var options = new DocSaveOptions();

   // デフォルト構成で変換プロセスを開始する
   Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);





```

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, PdfSaveOptions, String) {#converthtml_7}

[`HTMLDocument`](../../../com.aspose.html/htmldocument/) によって提示された HTML ソースを変換します。結果は出力ファイルパスで生成された PDF ファイルです。

```java
public static void ConvertHTML(HTMLDocument document, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| document | HTMLDocument | [`HTMLDocument`](../../../com.aspose.html/htmldocument/) によって提示された変換ソースです。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な pdf ファイルパス。 |

## Remarks

HTML を PDF に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

PDF 変換

Portable Document Format (PDF) は、1990 年代に Adobe が作成した文書形式です。このファイル形式の目的は、アプリケーションソフトウェアやハードウェア、オペレーティングシステムに依存しない形式で、文書やその他の参照資料を表現する標準を導入することでした。PDF ファイルは、PDF 仕様で定義された構文規則に従ってトークンに分類できるバイトの集合です。1 つまたは複数のトークンが結合されて上位レベルの構文エンティティ、主にオブジェクトが形成され、これが PDF 文書を構成する基本データ値となります。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

他の人気のある形式変換

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を PDF に変換

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、HTML を PDF 結果として保存します。シナリオに応じて 3 つ以上のパラメータが必要です。オンライン HTML コンバータ

Aspose.HTML は、[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) という無料のオンラインツールを提供しており、HTML を高品質で簡単かつ高速に PDF に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
 	  // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "source.html");

      // デフォルトの構成オブジェクトをインスタンス化する
      var configuration = new Configuration();

      // 複数の方法のいずれかで HTML ドキュメントを作成
      using (var document = new HTMLDocument(sourcePath, configuration))
      {
		// フォームの結果ファイルパス
        var resultPath = Path.Combine(OutputFolder, "result.pdf");

        // デフォルトの PdfSaveOptions オブジェクトを定義
        var options = new PdfSaveOptions();

		// 変換プロセスをインスタンス化
        Converter.ConvertHTML(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, PdfSaveOptions, String) {#converthtml_29}

URL で提示された HTML ソースを変換します。結果は出力ファイルパスで作成された pdf ファイルです。

```java
public static void ConvertHTML(Url url, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | HTML ソースドキュメント URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な pdf ファイルパス。 |

## Remarks

HTML を PDF に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

PDF 変換

Portable Document Format (PDF) は、1990 年代に Adobe が作成した文書形式です。このファイル形式の目的は、アプリケーションソフトウェアやハードウェア、オペレーティングシステムに依存しない形式で、文書やその他の参照資料を表現する標準を導入することでした。PDF ファイルは、PDF 仕様で定義された構文規則に従ってトークンに分類できるバイトの集合です。1 つまたは複数のトークンが結合されて上位レベルの構文エンティティ、主にオブジェクトが形成され、これが PDF 文書を構成する基本データ値となります。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

他の人気のある形式変換

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を PDF に変換

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、HTML を PDF 結果として保存します。シナリオに応じて 3 つ以上のパラメータが必要です。オンライン HTML コンバータ

Aspose.HTML は、[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) という無料のオンラインツールを提供しており、HTML を高品質で簡単かつ高速に PDF に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...      
      // ファイルベースのソース URL を形成
      var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertHTML(sourceUrl, options, resultPath);
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

## ConvertHTML(Url, Configuration, PdfSaveOptions, String) {#converthtml_18}

URL で提示された HTML ソースを変換します。結果は出力ファイルパスで作成された pdf ファイルです。

```java
public static void ConvertHTML(Url url, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | HTML ソースドキュメント URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な pdf ファイルパス。 |

## Remarks

HTML を PDF に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

PDF 変換

Portable Document Format (PDF) は、1990 年代に Adobe が作成した文書形式です。このファイル形式の目的は、アプリケーションソフトウェアやハードウェア、オペレーティングシステムに依存しない形式で、文書やその他の参照資料を表現する標準を導入することでした。PDF ファイルは、PDF 仕様で定義された構文規則に従ってトークンに分類できるバイトの集合です。1 つまたは複数のトークンが結合されて上位レベルの構文エンティティ、主にオブジェクトが形成され、これが PDF 文書を構成する基本データ値となります。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

他の人気のある形式変換

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を PDF に変換

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、HTML を PDF 結果として保存します。シナリオに応じて 3 つ以上のパラメータが必要です。オンライン HTML コンバータ

Aspose.HTML は、[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) という無料のオンラインツールを提供しており、HTML を高品質で簡単かつ高速に PDF に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...    
   // ファイルベースのソース URL を形成
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // フォームの結果ファイルパス
   var resultPath = Path.Combine(OutputFolder, "result.pdf");

   // デフォルトの PdfSaveOptions オブジェクトを定義
   var options = new PdfSaveOptions();

   // デフォルトの構成オブジェクトで変換プロセスを開始する
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertHTML(String, PdfSaveOptions, String) {#converthtml_51}

完全なファイルパスで提示されたHTMLソースをPDFに変換します。結果は、出力ファイルパスによって生成されたpdfファイルです。

```java
public static void ConvertHTML(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | Html 完全ファイルソースパス。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な pdf ファイルパス。 |

## Remarks

HTML を PDF に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

PDF 変換

Portable Document Format (PDF) は、1990 年代に Adobe が作成した文書形式です。このファイル形式の目的は、アプリケーションソフトウェアやハードウェア、オペレーティングシステムに依存しない形式で、文書やその他の参照資料を表現する標準を導入することでした。PDF ファイルは、PDF 仕様で定義された構文規則に従ってトークンに分類できるバイトの集合です。1 つまたは複数のトークンが結合されて上位レベルの構文エンティティ、主にオブジェクトが形成され、これが PDF 文書を構成する基本データ値となります。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

他の人気のある形式変換

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を PDF に変換

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、HTML を PDF 結果として保存します。シナリオに応じて 3 つ以上のパラメータが必要です。オンライン HTML コンバータ

Aspose.HTML は、[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) という無料のオンラインツールを提供しており、HTML を高品質で簡単かつ高速に PDF に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // フォームのソースファイルパス
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // フォームの結果ファイルパス
   var resultPath = Path.Combine(OutputFolder, "result.pdf");

   // デフォルトの PdfSaveOptions オブジェクトを定義
   var options = new PdfSaveOptions();

   // 変換プロセスを開始する
   Converter.ConvertHTML(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, PdfSaveOptions, String) {#converthtml_40}

完全なファイルパスで提示されたHTMLソースをPDFに変換します。結果は、出力ファイルパスによって生成されたpdfファイルです。

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | Html 完全ファイルソースパス。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な pdf ファイルパス。 |

## Remarks

HTML を PDF に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

PDF 変換

Portable Document Format (PDF) は、1990 年代に Adobe が作成した文書形式です。このファイル形式の目的は、アプリケーションソフトウェアやハードウェア、オペレーティングシステムに依存しない形式で、文書やその他の参照資料を表現する標準を導入することでした。PDF ファイルは、PDF 仕様で定義された構文規則に従ってトークンに分類できるバイトの集合です。1 つまたは複数のトークンが結合されて上位レベルの構文エンティティ、主にオブジェクトが形成され、これが PDF 文書を構成する基本データ値となります。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

他の人気のある形式変換

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を PDF に変換

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、HTML を PDF 結果として保存します。シナリオに応じて 3 つ以上のパラメータが必要です。オンライン HTML コンバータ

Aspose.HTML は、[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) という無料のオンラインツールを提供しており、HTML を高品質で簡単かつ高速に PDF に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
  // フォームのソースファイルパス
  var sourcePath = Path.Combine(InputFolder, "source.html");

  // フォームの結果ファイルパス
  var resultPath = Path.Combine(OutputFolder, "result.pdf");

  // デフォルトの PdfSaveOptions オブジェクトを定義
  var options = new PdfSaveOptions();

  // デフォルト構成で変換プロセスを開始する
  Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertHTML(String, String, PdfSaveOptions, String) {#converthtml_73}

インライン コンテンツで提示された HTML ソースを PDF に変換します。結果は出力ファイルパスで作成された pdf ファイルです。

```java
public static void ConvertHTML(String content, String baseUri, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン HTML コンテンツとしての文字列。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な pdf ファイルパス。 |

## Remarks

HTML を PDF に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

PDF 変換

Portable Document Format (PDF) は、1990 年代に Adobe が作成した文書形式です。このファイル形式の目的は、アプリケーションソフトウェアやハードウェア、オペレーティングシステムに依存しない形式で、文書やその他の参照資料を表現する標準を導入することでした。PDF ファイルは、PDF 仕様で定義された構文規則に従ってトークンに分類できるバイトの集合です。1 つまたは複数のトークンが結合されて上位レベルの構文エンティティ、主にオブジェクトが形成され、これが PDF 文書を構成する基本データ値となります。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

他の人気のある形式変換

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を PDF に変換

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、HTML を PDF 結果として保存します。シナリオに応じて 3 つ以上のパラメータが必要です。オンライン HTML コンバータ

Aspose.HTML は、[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) という無料のオンラインツールを提供しており、HTML を高品質で簡単かつ高速に PDF に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// インライン HTML コンテンツを作成		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result.pdf");

	// デフォルトの PdfSaveOptions オブジェクトを定義
   	var options = new PdfSaveOptions();

	// 変換プロセスを開始する
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### 関連項目

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, PdfSaveOptions, String) {#converthtml_62}

インライン コンテンツで提示された HTML ソースを PDF に変換します。結果は出力ファイルパスで作成された pdf ファイルです。

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン HTML コンテンツとしての文字列。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な pdf ファイルパス。 |

## Remarks

HTML を PDF に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

PDF 変換

Portable Document Format (PDF) は、1990 年代に Adobe が作成した文書形式です。このファイル形式の目的は、アプリケーションソフトウェアやハードウェア、オペレーティングシステムに依存しない形式で、文書やその他の参照資料を表現する標準を導入することでした。PDF ファイルは、PDF 仕様で定義された構文規則に従ってトークンに分類できるバイトの集合です。1 つまたは複数のトークンが結合されて上位レベルの構文エンティティ、主にオブジェクトが形成され、これが PDF 文書を構成する基本データ値となります。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

他の人気のある形式変換

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を PDF に変換

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、HTML を PDF 結果として保存します。シナリオに応じて 3 つ以上のパラメータが必要です。オンライン HTML コンバータ

Aspose.HTML は、[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) という無料のオンラインツールを提供しており、HTML を高品質で簡単かつ高速に PDF に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// インライン HTML コンテンツを作成		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result.pdf");

	// デフォルトの PdfSaveOptions オブジェクトを定義
  	var options = new PdfSaveOptions();

	// デフォルト構成で変換プロセスを開始する
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, PdfSaveOptions, ICreateStreamProvider) {#converthtml_6}

[`HTMLDocument`](../../../com.aspose.html/htmldocument/) で提供される HTML ソースを PDF に変換します。結果は、[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertHTML(HTMLDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| document | HTMLDocument | [`HTMLDocument`](../../../com.aspose.html/htmldocument/) によって提示された変換ソースです。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions) を参照してください。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装です。 |

## Remarks

HTML を PDF に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

PDF 変換

Portable Document Format (PDF) は、1990 年代に Adobe が作成した文書形式です。このファイル形式の目的は、アプリケーションソフトウェアやハードウェア、オペレーティングシステムに依存しない形式で、文書やその他の参照資料を表現する標準を導入することでした。PDF ファイルは、PDF 仕様で定義された構文規則に従ってトークンに分類できるバイトの集合です。1 つまたは複数のトークンが結合されて上位レベルの構文エンティティ、主にオブジェクトが形成され、これが PDF 文書を構成する基本データ値となります。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

他の人気のある形式変換

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を PDF に変換

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、HTML を PDF 結果として保存します。シナリオに応じて 3 つ以上のパラメータが必要です。オンライン HTML コンバータ

Aspose.HTML は、[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) という無料のオンラインツールを提供しており、HTML を高品質で簡単かつ高速に PDF に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// インライン HTML コンテンツを定義
   	var content = @"<!DOCTYPE html><html><body><p>Hello, World!</p></body></html>";

   	// デフォルトの構成オブジェクトをインスタンス化する
   	var configuration = new Configuration();

   	// 複数の方法のいずれかで HTML ドキュメントを作成
   	using (var document = new HTMLDocument(content, String.Empty, configuration))
   	{
		// 拡張子なしの結果ファイルパスを定義
		var resultPath = Path.Combine(OutputFolder, "result");

		// ICreateStreamProvider 実装のいずれかを使用
		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

		// デフォルトの PdfSaveOptions オブジェクトを定義
		var options = new PdfSaveOptions();

		// 変換プロセスを開始する
		Converter.ConvertHTML(document, options, provider);
   	}
```

*OutputFolder - user output file path.

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, PdfSaveOptions, ICreateStreamProvider) {#converthtml_28}

URL によって提示された HTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertHTML(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | HTML ソースドキュメント URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

HTML を PDF に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

PDF 変換

Portable Document Format (PDF) は、1990 年代に Adobe が作成した文書形式です。このファイル形式の目的は、アプリケーションソフトウェアやハードウェア、オペレーティングシステムに依存しない形式で、文書やその他の参照資料を表現する標準を導入することでした。PDF ファイルは、PDF 仕様で定義された構文規則に従ってトークンに分類できるバイトの集合です。1 つまたは複数のトークンが結合されて上位レベルの構文エンティティ、主にオブジェクトが形成され、これが PDF 文書を構成する基本データ値となります。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

他の人気のある形式変換

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を PDF に変換

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、HTML を PDF 結果として保存します。シナリオに応じて 3 つ以上のパラメータが必要です。オンライン HTML コンバータ

Aspose.HTML は、[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) という無料のオンラインツールを提供しており、HTML を高品質で簡単かつ高速に PDF に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // 入力ファイルパスに基づいて Url を作成する
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // フォームの結果ファイルパス
   var resultPath = Path.Combine(OutputFolder, "result");

   // ICreateStreamProvider 実装のいずれかを使用
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // デフォルトの PdfSaveOptions オブジェクトを定義
   var options = new PdfSaveOptions();

   // 変換プロセスを開始する
   Converter.ConvertHTML(sourceUrl, options, provider);
```

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_17}

URL によって提示された HTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertHTML(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | HTML ソースドキュメント URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions) を参照してください。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装です。 |

## Remarks

HTML を PDF に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

PDF 変換

Portable Document Format (PDF) は、1990 年代に Adobe が作成した文書形式です。このファイル形式の目的は、アプリケーションソフトウェアやハードウェア、オペレーティングシステムに依存しない形式で、文書やその他の参照資料を表現する標準を導入することでした。PDF ファイルは、PDF 仕様で定義された構文規則に従ってトークンに分類できるバイトの集合です。1 つまたは複数のトークンが結合されて上位レベルの構文エンティティ、主にオブジェクトが形成され、これが PDF 文書を構成する基本データ値となります。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

他の人気のある形式変換

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を PDF に変換

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、HTML を PDF 結果として保存します。シナリオに応じて 3 つ以上のパラメータが必要です。オンライン HTML コンバータ

Aspose.HTML は、[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) という無料のオンラインツールを提供しており、HTML を高品質で簡単かつ高速に PDF に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // 入力ファイルパスに基づいて Url を作成する
   var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   // フォームの結果ファイルパス
   var resultPath = Path.Combine(OutputFolder, "result ");

   // ICreateStreamProvider 実装のいずれかを使用
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // デフォルトの PdfSaveOptions オブジェクトを定義
   var options = new PdfSaveOptions();

   // デフォルト構成で変換プロセスを開始する
   Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
```

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

## ConvertHTML(String, PdfSaveOptions, ICreateStreamProvider) {#converthtml_50}

完全なファイルパスで提供される HTML ソースを PDF に変換します。結果は、[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertHTML(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | Html 完全ファイルソースパス。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

HTML を PDF に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

PDF 変換

Portable Document Format (PDF) は、1990 年代に Adobe が作成した文書形式です。このファイル形式の目的は、アプリケーションソフトウェアやハードウェア、オペレーティングシステムに依存しない形式で、文書やその他の参照資料を表現する標準を導入することでした。PDF ファイルは、PDF 仕様で定義された構文規則に従ってトークンに分類できるバイトの集合です。1 つまたは複数のトークンが結合されて上位レベルの構文エンティティ、主にオブジェクトが形成され、これが PDF 文書を構成する基本データ値となります。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

他の人気のある形式変換

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を PDF に変換

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、HTML を PDF 結果として保存します。シナリオに応じて 3 つ以上のパラメータが必要です。オンライン HTML コンバータ

Aspose.HTML は、[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) という無料のオンラインツールを提供しており、HTML を高品質で簡単かつ高速に PDF に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
   // ソースファイルパスを作成
   var sourcePath = Path.Combine(InputFolder, "source.html");

   // フォームの結果ファイルパス
   var resultPath = Path.Combine(OutputFolder, "result");

   // ICreateStreamProvider 実装のいずれかを使用
   ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

   // デフォルトの PdfSaveOptions オブジェクトを定義
   var options = new PdfSaveOptions();

   // 変換プロセスを開始する
   Converter.ConvertHTML(sourcePath, options, provider);
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

## ConvertHTML(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_39}

完全なファイルパスで提供される HTML ソースを PDF に変換します。結果は、[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | Html 完全ファイルソースパス。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions) を参照してください。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装です。 |

## Remarks

HTML を PDF に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

PDF 変換

Portable Document Format (PDF) は、1990 年代に Adobe が作成した文書形式です。このファイル形式の目的は、アプリケーションソフトウェアやハードウェア、オペレーティングシステムに依存しない形式で、文書やその他の参照資料を表現する標準を導入することでした。PDF ファイルは、PDF 仕様で定義された構文規則に従ってトークンに分類できるバイトの集合です。1 つまたは複数のトークンが結合されて上位レベルの構文エンティティ、主にオブジェクトが形成され、これが PDF 文書を構成する基本データ値となります。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

他の人気のある形式変換

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を PDF に変換

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、HTML を PDF 結果として保存します。シナリオに応じて 3 つ以上のパラメータが必要です。オンライン HTML コンバータ

Aspose.HTML は、[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) という無料のオンラインツールを提供しており、HTML を高品質で簡単かつ高速に PDF に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
  // ソースファイルパスを作成
  var sourcePath = Path.Combine(InputFolder, "source.html");

  // フォームの結果ファイルパス
  var resultPath = Path.Combine(OutputFolder, "result");

  // ICreateStreamProvider 実装のいずれかを使用
  ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

  // デフォルトの PdfSaveOptions オブジェクトを定義
  var options = new PdfSaveOptions();

  // デフォルト構成で変換プロセスを開始する
  Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
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

## ConvertHTML(String, String, PdfSaveOptions, ICreateStreamProvider) {#converthtml_72}

インラインコンテンツで提供される HTML ソースを PDF に変換します。結果は、[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertHTML(String content, String baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン HTML コンテンツとしての文字列。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions) を参照してください。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装。 |

## Remarks

HTML を PDF に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

PDF 変換

Portable Document Format (PDF) は、1990 年代に Adobe が作成した文書形式です。このファイル形式の目的は、アプリケーションソフトウェアやハードウェア、オペレーティングシステムに依存しない形式で、文書やその他の参照資料を表現する標準を導入することでした。PDF ファイルは、PDF 仕様で定義された構文規則に従ってトークンに分類できるバイトの集合です。1 つまたは複数のトークンが結合されて上位レベルの構文エンティティ、主にオブジェクトが形成され、これが PDF 文書を構成する基本データ値となります。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

他の人気のある形式変換

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を PDF に変換

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、HTML を PDF 結果として保存します。シナリオに応じて 3 つ以上のパラメータが必要です。オンライン HTML コンバータ

Aspose.HTML は、[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) という無料のオンラインツールを提供しており、HTML を高品質で簡単かつ高速に PDF に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// インライン HTML コンテンツを作成		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result");

	// ICreateStreamProvider 実装のいずれかを使用
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// デフォルトの PdfSaveOptions オブジェクトを定義
  	var options = new PdfSaveOptions();

	// 変換プロセスを開始する
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### 関連項目

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#converthtml_61}

インラインコンテンツで提供される HTML ソースを PDF に変換します。結果は、[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン HTML コンテンツとしての文字列。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

HTML を PDF に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

PDF 変換

Portable Document Format (PDF) は、1990 年代に Adobe が作成した文書形式です。このファイル形式の目的は、アプリケーションソフトウェアやハードウェア、オペレーティングシステムに依存しない形式で、文書やその他の参照資料を表現する標準を導入することでした。PDF ファイルは、PDF 仕様で定義された構文規則に従ってトークンに分類できるバイトの集合です。1 つまたは複数のトークンが結合されて上位レベルの構文エンティティ、主にオブジェクトが形成され、これが PDF 文書を構成する基本データ値となります。

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

他の人気のある形式変換

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を PDF に変換

[`Converter`](../) class offers wide range of HTML specific conversions to PDF. To convert HTML to PDF, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、HTML を PDF 結果として保存します。シナリオに応じて 3 つ以上のパラメータが必要です。オンライン HTML コンバータ

Aspose.HTML は、[HTML to PDF Converter](https://products.aspose.app/html/en/conversion/html-to-pdf) という無料のオンラインツールを提供しており、HTML を高品質で簡単かつ高速に PDF に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// インライン HTML コンテンツを作成		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result");

	// ICreateStreamProvider 実装のいずれかを使用
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// デフォルトの PdfSaveOptions オブジェクトを定義
 	var options = new PdfSaveOptions();

	// デフォルト構成で変換プロセスを開始する
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, MHTMLSaveOptions, String) {#converthtml_5}

[`HTMLDocument`](../../../com.aspose.html/htmldocument/) で提供される HTML ソースを変換します。結果は、出力ファイルパスによって生成された mhtml（.mht）ファイルです。

```java
public static void ConvertHTML(HTMLDocument document, MHTMLSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| document | HTMLDocument | [`HTMLDocument`](../../../com.aspose.html/htmldocument/) によって提示された変換ソースです。 |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については、[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な mhtml（.mht）ファイルパス。 |

## Remarks

HTML を MHTML に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

MHTML 変換

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

他の人気のある形式変換

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を MHTML に変換

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、HTML を MHTML 結果として保存します。シナリオに応じて 3 つ以上のパラメータが必要です。オンライン HTML コンバータ

Aspose.HTML は、[HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) という無料のオンラインツールを提供しており、HTML を高品質で簡単かつ高速に MHTML に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// HTML ドキュメントを作成
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// 複数の方法のいずれかで HTML ドキュメントを作成
	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
	{
		// デフォルトの MHTMLSaveOptions オブジェクトを定義する
 		var options = new MHTMLSaveOptions();

		// フォームの結果ファイルパス
		var resultPath = Path.Combine(OutputFolder, "result.mht");

		// 変換プロセスを開始する
 		Converter.ConvertHTML(document, options, resultPath);
}
```

*OutputFolder - user output file path.

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, MHTMLSaveOptions, String) {#converthtml_27}

URLで提示されたHTMLソースを変換します。結果は、出力ファイルパスによって生成されたmhtml（.mht）ファイルです。

```java
public static void ConvertHTML(Url url, MHTMLSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | HTML ソースドキュメント URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については、[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な mhtml（.mht）ファイルパス。 |

## Remarks

HTML を MHTML に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

MHTML 変換

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

他の人気のある形式変換

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を MHTML に変換

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、HTML を MHTML 結果として保存します。シナリオに応じて 3 つ以上のパラメータが必要です。オンライン HTML コンバータ

Aspose.HTML は、[HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) という無料のオンラインツールを提供しており、HTML を高品質で簡単かつ高速に MHTML に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 入力ファイルパスに基づいて Url を作成する
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

	// デフォルトの MHTMLSaveOptions オブジェクトを定義する
	var options = new MHTMLSaveOptions();

	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// 変換プロセスを開始する
	Converter.ConvertHTML(sourceUrl, options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, MHTMLSaveOptions, String) {#converthtml_16}

URLで提示されたHTMLソースを変換します。結果は、出力ファイルパスによって生成されたmhtml（.mht）ファイルです。

```java
public static void ConvertHTML(Url url, Configuration configuration, MHTMLSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | HTML ソースドキュメント URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については、[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な mhtml（.mht）ファイルパス。 |

## Remarks

HTML を MHTML に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

MHTML 変換

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

他の人気のある形式変換

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を MHTML に変換

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、HTML を MHTML 結果として保存します。シナリオに応じて 3 つ以上のパラメータが必要です。オンライン HTML コンバータ

Aspose.HTML は、[HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) という無料のオンラインツールを提供しており、HTML を高品質で簡単かつ高速に MHTML に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 入力ファイルパスに基づいて Url を作成する
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

	// デフォルトの MHTMLSaveOptions オブジェクトを定義する
	var options = new MHTMLSaveOptions();

	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// デフォルト構成で変換プロセスを開始する
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, MHTMLSaveOptions, String) {#converthtml_49}

完全なファイルパスで提示されたHTMLソースをMHTMLに変換します。結果は、出力ファイルパスによって生成されたmhtml（.mht）ファイルです。

```java
public static void ConvertHTML(String sourcePath, MHTMLSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | HTML ファイルのソース パスです。現在のディレクトリ パスと結合され、絶対 URL が形成されます。 |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については、[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な mhtml（.mht）ファイルパス。 |

## Remarks

HTML を MHTML に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

MHTML 変換

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

他の人気のある形式変換

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を MHTML に変換

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、HTML を MHTML 結果として保存します。シナリオに応じて 3 つ以上のパラメータが必要です。オンライン HTML コンバータ

Aspose.HTML は、[HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) という無料のオンラインツールを提供しており、HTML を高品質で簡単かつ高速に MHTML に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// フォームのソースファイルパス
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// デフォルトの MHTMLSaveOptions オブジェクトを定義する
	var options = new MHTMLSaveOptions();

	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// 変換プロセスを開始する
	Converter.ConvertHTML(sourcePath, options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, MHTMLSaveOptions, String) {#converthtml_38}

完全なファイルパスで提示されたHTMLソースをMHTMLに変換します。結果は、出力ファイルパスによって生成されたmhtml（.mht）ファイルです。

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    MHTMLSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | Html 完全ファイルソースパス。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については、[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な mhtml（.mht）ファイルパス。 |

## Remarks

HTML を MHTML に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

MHTML 変換

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

他の人気のある形式変換

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を MHTML に変換

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、HTML を MHTML 結果として保存します。シナリオに応じて 3 つ以上のパラメータが必要です。オンライン HTML コンバータ

Aspose.HTML は、[HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) という無料のオンラインツールを提供しており、HTML を高品質で簡単かつ高速に MHTML に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// フォームのソースファイルパス
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// デフォルトの MHTMLSaveOptions オブジェクトを定義する
	var options = new MHTMLSaveOptions();

	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result.mht");

	// デフォルト構成で変換プロセスを開始する
	Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, MHTMLSaveOptions, String) {#converthtml_71}

インライン コンテンツで提示された HTML ソースを MHTML に変換します。結果は出力ファイルパスで作成された mhtml (.mht) ファイルです。

```java
public static void ConvertHTML(String content, String baseUri, MHTMLSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン HTML コンテンツとしての文字列。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については、[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な mhtml（.mht）ファイルパス。 |

## Remarks

HTML を MHTML に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

MHTML 変換

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

他の人気のある形式変換

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を MHTML に変換

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。カスタムまたはデフォルト設定で新しい [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、HTML を MHTML 結果として保存します。シナリオに応じて 3 つ以上のパラメータが必要です。オンライン HTML コンバータ

Aspose.HTML は、[HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) という無料のオンラインツールを提供しており、HTML を高品質で簡単かつ高速に MHTML に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// インライン HTML コンテンツを作成		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result");

	// デフォルトの保存オプション オブジェクトを定義する
  	var options = new MHTMLSaveOptions();

	// 変換プロセスを開始する
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### 関連項目

* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, MHTMLSaveOptions, String) {#converthtml_60}

インライン コンテンツで提示された HTML ソースを MHTML に変換します。結果は出力ファイルパスで作成された mhtml (.mht) ファイルです。

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    MHTMLSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン HTML コンテンツとしての文字列。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | MHTMLSaveOptions | [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については、[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-using-mhtmlsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な mhtml（.mht）ファイルパス。 |

## Remarks

HTML を MHTML に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

MHTML 変換

[MHTML](https://docs.fileformat.com/web/mhtml/) combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. MHTML uses the MIME email protocol to combine items into a single web page archive file. With MHTML, the archival of online web pages becomes much easier and less cluttered.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

他の人気のある形式変換

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を MHTML に変換

[`Converter`](../) class offers wide range of HTML specific conversions to [MHTML](https://docs.fileformat.com/web/mhtml/). To convert HTML to MHTML, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイル パスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データ バッファとして使用します。カスタムまたはデフォルト設定で新しい [`MHTMLSaveOptions`](../../../com.aspose.html.saving/mhtmlsaveoptions/) オブジェクトを作成します。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザー シナリオに応じて 3 つ以上のパラメータで HTML を MHTML 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、[HTML to MHTML Converter](https://products.aspose.app/html/en/conversion/html-to-mhtml) という無料のオンラインツールを提供しており、HTML を高品質で簡単かつ高速に MHTML に変換します。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// インライン HTML コンテンツを作成		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result");

	// デフォルトの保存オプション オブジェクトを定義する
 	var options = new MHTMLSaveOptions();

	// デフォルト構成で変換プロセスを開始する
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MHTMLSaveOptions](../../../com.aspose.html.saving/mhtmlsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, MarkdownSaveOptions, String) {#converthtml_4}

[`HTMLDocument`](../../../com.aspose.html/htmldocument/) によって提示された HTML ソースを変換します。結果は出力ファイル パスで形成された markdown（.md）ファイルです。

```java
public static void ConvertHTML(HTMLDocument document, MarkdownSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| document | HTMLDocument | [`HTMLDocument`](../../../com.aspose.html/htmldocument/) によって提示された変換ソースです。 |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。詳細については、[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な md ファイル パス。 |

## Remarks

HTML を Markdown に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

Markdown 変換

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

他の人気のある形式変換

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を Markdown に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイル パスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データ バッファとして使用します。カスタムまたはデフォルト設定で新しい [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) オブジェクトを作成します。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザー シナリオに応じて 3 つ以上のパラメータで HTML を Markdown 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質で簡単かつ高速に MD に変換する無料のオンライン [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// フォームのソースファイルパス
		var sourcePath = Path.Combine(InputFolder, "source.html");
       
      	// フォームの結果ファイルパス
      	var outputPath = Path.Combine(OutputFolder, "result.md");

		using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
		{
			// 保存オプション オブジェクト インスタンスを定義する
			var options = new MarkdownSaveOptions();

			// 変換プロセスを開始する
			Converter.ConvertHTML(document, options, outputPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, MarkdownSaveOptions, String) {#converthtml_26}

URLで提示されたHTMLソースを変換します。結果は、出力ファイルパスによって生成されたmarkdown（.md）ファイルです。

```java
public static void ConvertHTML(Url url, MarkdownSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | HTML ソースドキュメント URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。詳細については、[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な md ファイル パス。 |

## Remarks

HTML を Markdown に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

Markdown 変換

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

他の人気のある形式変換

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を Markdown に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイル パスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データ バッファとして使用します。カスタムまたはデフォルト設定で新しい [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) オブジェクトを作成します。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザー シナリオに応じて 3 つ以上のパラメータで HTML を Markdown 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質で簡単かつ高速に MD に変換する無料のオンライン [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 入力ファイルパスに基づいて Url を作成する
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));
    
   	// フォームの結果ファイルパス
   	var outputPath = Path.Combine(OutputFolder, "result.md");

	// 保存オプション オブジェクト インスタンスを定義する
	var options = new MarkdownSaveOptions();

	// 変換プロセスを開始する
	Converter.ConvertHTML(sourceUrl, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, MarkdownSaveOptions, String) {#converthtml_15}

URLで提示されたHTMLソースを変換します。結果は、出力ファイルパスによって生成されたmarkdown（.md）ファイルです。

```java
public static void ConvertHTML(Url url, Configuration configuration, MarkdownSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | HTML ソースドキュメント URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。詳細については、[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な md ファイル パス。 |

## Remarks

HTML を Markdown に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

Markdown 変換

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

他の人気のある形式変換

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を Markdown に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイル パスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データ バッファとして使用します。カスタムまたはデフォルト設定で新しい [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) オブジェクトを作成します。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザー シナリオに応じて 3 つ以上のパラメータで HTML を Markdown 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質で簡単かつ高速に MD に変換する無料のオンライン [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 入力ファイルパスに基づいて Url を作成する
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));
   
  	// フォームの結果ファイルパス
  	var outputPath = Path.Combine(OutputFolder, "result.md");

	// 保存オプション オブジェクト インスタンスを定義する
	var options = new MarkdownSaveOptions();

	// デフォルト構成で変換プロセスを開始する
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, MarkdownSaveOptions, String) {#converthtml_48}

完全なファイルパスで提示されたHTMLソースをMarkdownに変換します。結果は、出力ファイルパスによって生成されたmarkdown（.md）ファイルです。

```java
public static void ConvertHTML(String sourcePath, MarkdownSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | HTML ファイルのソース パスです。現在のディレクトリ パスと結合され、絶対 URL が形成されます。 |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。詳細については、[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な md ファイル パス。 |

## Remarks

HTML を Markdown に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

Markdown 変換

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

他の人気のある形式変換

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を Markdown に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイル パスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データ バッファとして使用します。カスタムまたはデフォルト設定で新しい [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) オブジェクトを作成します。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザー シナリオに応じて 3 つ以上のパラメータで HTML を Markdown 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質で簡単かつ高速に MD に変換する無料のオンライン [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// フォームのソースファイルパス
	var sourcePath = Path.Combine(InputFolder, "source.html");
    
   	// フォームの結果ファイルパス
   	var outputPath = Path.Combine(OutputFolder, "result.md");

	// 保存オプション オブジェクト インスタンスを定義する
	var options = new MarkdownSaveOptions();

	// 変換プロセスを開始する
	Converter.ConvertHTML(sourcePath, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, MarkdownSaveOptions, String) {#converthtml_37}

完全なファイルパスで提示されたHTMLソースをMarkdownに変換します。結果は、出力ファイルパスによって生成されたmarkdown（.md）ファイルです。

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    MarkdownSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | HTML ファイルのソース パスです。現在のディレクトリ パスと結合され、絶対 URL が形成されます。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。詳細については、[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な md ファイル パス。 |

## Remarks

HTML を Markdown に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

Markdown 変換

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

他の人気のある形式変換

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を Markdown に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイル パスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データ バッファとして使用します。カスタムまたはデフォルト設定で新しい [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) オブジェクトを作成します。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザー シナリオに応じて 3 つ以上のパラメータで HTML を Markdown 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質で簡単かつ高速に MD に変換する無料のオンライン [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// フォームのソースファイルパス
	var sourcePath = Path.Combine(InputFolder, "source.html");
   
  	// フォームの結果ファイルパス
  	var outputPath = Path.Combine(OutputFolder, "result.md");

	// 保存オプション オブジェクト インスタンスを定義する
	var options = new MarkdownSaveOptions();

	// デフォルト構成で変換プロセスを開始する
	Converter.ConvertHTML(sourcePath, new Configuration(), options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, MarkdownSaveOptions, String) {#converthtml_70}

インライン コンテンツで提示された HTML ソースを Markdown に変換します。結果は出力ファイルパスで作成された mhtml (.mht) ファイルです。

```java
public static void ConvertHTML(String content, String baseUri, MarkdownSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン HTML コンテンツとしての文字列。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。詳細については、[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な md ファイル パス。 |

## Remarks

HTML を Markdown に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

Markdown 変換

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

他の人気のある形式変換

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を Markdown に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイル パスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データ バッファとして使用します。カスタムまたはデフォルト設定で新しい [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) オブジェクトを作成します。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザー シナリオに応じて 3 つ以上のパラメータで HTML を Markdown 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質で簡単かつ高速に MD に変換する無料のオンライン [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// インライン HTML コンテンツを作成		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result");

	// デフォルトの保存オプション オブジェクトを定義する
  	var options = new MarkdownSaveOptions();

	// 変換プロセスを開始する
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### 関連項目

* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, MarkdownSaveOptions, String) {#converthtml_59}

インライン コンテンツで提示された HTML ソースを Markdown に変換します。結果は出力ファイルパスで作成された mhtml (.mht) ファイルです。

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    MarkdownSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン HTML コンテンツとしての文字列。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | MarkdownSaveOptions | [`MarkdownSaveOptions`](../../../com.aspose.html.saving/markdownsaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。詳細については、[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-using-markdownsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な md ファイル パス。 |

## Remarks

HTML を Markdown に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

Markdown 変換

[Markdown (MD)](https://docs.fileformat.com/word-processing/md/) is a markup language with a plain-text-formatting syntax. Markdown is often used as a format for documentation and readme files since it allows writing in an easy-to-read and easy-to-write style. It is popular with technical writers for its simplicity of use, lightweight learning and broad support. Its design allows it to be easily converted to many output formats, but initially, it was created to convert only to HTML. Aspose.HTML class library provides a reversed conversion from HTML to Markdown. You can access and edit Markdown files or create new content from any device in any text editor.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

他の人気のある形式変換

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を Markdown に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to [Markdown](https://docs.fileformat.com/word-processing/md/). To convert HTML to MD, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント（[`HTMLDocument`](../../../com.aspose.html/htmldocument/)）を作成することもできます。変換結果。結果の出力ファイル パスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データ バッファとして使用します。カスタムまたはデフォルト設定で新しい [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions) オブジェクトを作成します。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザー シナリオに応じて 3 つ以上のパラメータで HTML を Markdown 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質で簡単かつ高速に MD に変換する無料のオンライン [HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// インライン HTML コンテンツを作成		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result");

	// デフォルトの保存オプション オブジェクトを定義する
 	var options = new MarkdownSaveOptions();

	// デフォルト構成で変換プロセスを開始する
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [MarkdownSaveOptions](../../../com.aspose.html.saving/markdownsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, XpsSaveOptions, String) {#converthtml_10}

[`HTMLDocument`](../../../com.aspose.html/htmldocument/) によって提示された HTML ソースを変換します。結果は出力ファイル パスで形成された xps ファイルです。

```java
public static void ConvertHTML(HTMLDocument document, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| document | HTMLDocument | [`HTMLDocument`](../../../com.aspose.html/htmldocument/) によって提示された変換ソースです。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。詳細については、[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な xps ファイル パス。 |

## Remarks

HTML を XPS に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

XPS 変換

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を XPS に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント (HTMLDocument) を作成することもできます。変換結果。結果の出力ファイル パスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データ バッファとして使用します。カスタムまたはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザー シナリオに応じて 3 つ以上のパラメータで HTML を XPS 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質で簡単かつ高速に XPS に変換する無料のオンライン [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
		// フォームのソースファイルパス
      	var sourcePath = Path.Combine(InputFolder, "source.html");

      	// フォームの結果ファイルパス
      	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
		// 複数の方法のいずれかで HTML ドキュメントを作成
      	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
      	{
        	// 保存オプション オブジェクト インスタンスを定義する
        	var options = new XpsSaveOptions();

        	// 変換プロセスを開始する
        	Converter.ConvertHTML(document, options, outputPath);
      	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, XpsSaveOptions, String) {#converthtml_32}

URL で提示された HTML ソースを変換します。結果は出力ファイルパスで作成された xps ファイルです。

```java
public static void ConvertHTML(Url url, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | HTML ソースドキュメント URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。詳細については、[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な xps ファイル パス。 |

## Remarks

HTML を XPS に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

XPS 変換

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を XPS に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント (HTMLDocument) を作成することもできます。変換結果。結果の出力ファイル パスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データ バッファとして使用します。カスタムまたはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザー シナリオに応じて 3 つ以上のパラメータで HTML を XPS 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質で簡単かつ高速に XPS に変換する無料のオンライン [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 入力ファイルパスに基づいて Url を作成する
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// フォームの結果ファイルパス
   	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// 保存オプション オブジェクト インスタンスを定義する
	var options = new XpsSaveOptions();

	// 変換プロセスを開始する
	Converter.ConvertHTML(sourceUrl, options, outputPath);
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

## ConvertHTML(Url, Configuration, XpsSaveOptions, String) {#converthtml_21}

URL で提示された HTML ソースを変換します。結果は出力ファイルパスで作成された xps ファイルです。

```java
public static void ConvertHTML(Url url, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | HTML ソースドキュメント URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な xps ファイル パス。 |

## Remarks

HTML を XPS に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

XPS 変換

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を XPS に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント (HTMLDocument) を作成することもできます。変換結果。結果の出力ファイル パスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データ バッファとして使用します。カスタムまたはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザー シナリオに応じて 3 つ以上のパラメータで HTML を XPS 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質で簡単かつ高速に XPS に変換する無料のオンライン [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 入力ファイルパスに基づいて Url を作成する
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// フォームの結果ファイルパス
  	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// 保存オプション オブジェクト インスタンスを定義する
	var options = new XpsSaveOptions();

	// デフォルト構成で変換プロセスを開始する
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, outputPath);
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

## ConvertHTML(String, XpsSaveOptions, String) {#converthtml_54}

完全なファイルパスで提示されたHTMLソースをXPSに変換します。結果は、出力ファイルパスによって生成されたxpsファイルです。

```java
public static void ConvertHTML(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | HTML ファイルのソース パスです。現在のディレクトリ パスと結合され、絶対 URL が形成されます。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。詳細については、[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な xps ファイル パス。 |

## Remarks

HTML を XPS に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

XPS 変換

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を XPS に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント (HTMLDocument) を作成することもできます。変換結果。結果の出力ファイル パスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データ バッファとして使用します。カスタムまたはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザー シナリオに応じて 3 つ以上のパラメータで HTML を XPS 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質で簡単かつ高速に XPS に変換する無料のオンライン [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// フォームのソースファイルパス
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// フォームの結果ファイルパス
   	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// 保存オプション オブジェクト インスタンスを定義する
	var options = new XpsSaveOptions();

	// 変換プロセスを開始する
	Converter.ConvertHTML(sourcePath, options, outputPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, XpsSaveOptions, String) {#converthtml_43}

完全なファイルパスで提示されたHTMLソースをXPSに変換します。結果は、出力ファイルパスによって生成されたxpsファイルです。

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | Html 完全ファイルソースパス。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。詳細については、[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な xps ファイル パス。 |

## Remarks

HTML を XPS に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

XPS 変換

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を XPS に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント (HTMLDocument) を作成することもできます。変換結果。結果の出力ファイル パスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データ バッファとして使用します。カスタムまたはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザー シナリオに応じて 3 つ以上のパラメータで HTML を XPS 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質で簡単かつ高速に XPS に変換する無料のオンライン [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// フォームのソースファイルパス
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// フォームの結果ファイルパス
  	var outputPath = Path.Combine(OutputFolder, "result.xps");
		
	// 保存オプション オブジェクト インスタンスを定義する
	var options = new XpsSaveOptions();

	// デフォルト構成で変換プロセスを開始する
	Converter.ConvertHTML(sourcePath, new Configuration(), options, outputPath);
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

## ConvertHTML(String, String, XpsSaveOptions, String) {#converthtml_76}

インライン コンテンツで提示された HTML ソースを XPS に変換します。結果は出力ファイルパスで作成された xps ファイルです。

```java
public static void ConvertHTML(String content, String baseUri, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン HTML コンテンツとしての文字列。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。詳細については、[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-using-xpssaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な xps ファイル パス。 |

## Remarks

HTML を XPS に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

XPS 変換

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を XPS に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント (HTMLDocument) を作成することもできます。変換結果。結果の出力ファイル パスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データ バッファとして使用します。カスタムまたはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザー シナリオに応じて 3 つ以上のパラメータで HTML を XPS 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質で簡単かつ高速に XPS に変換する無料のオンライン [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// インライン HTML コンテンツを作成		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result");

	// デフォルトの保存オプション オブジェクトを定義する
  	var options = new XpsSaveOptions();

	// 変換プロセスを開始する
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### 関連項目

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, XpsSaveOptions, String) {#converthtml_65}

インライン コンテンツで提示された HTML ソースを XPS に変換します。結果は出力ファイルパスで作成された xps ファイルです。

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン HTML コンテンツとしての文字列。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な xps ファイル パス。 |

## Remarks

HTML を XPS に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

XPS 変換

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を XPS に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント (HTMLDocument) を作成することもできます。変換結果。結果の出力ファイル パスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データ バッファとして使用します。カスタムまたはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザー シナリオに応じて 3 つ以上のパラメータで HTML を XPS 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質で簡単かつ高速に XPS に変換する無料のオンライン [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// インライン HTML コンテンツを作成		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result");

	// デフォルトの保存オプション オブジェクトを定義する
 	var options = new XpsSaveOptions();

	// デフォルト構成で変換プロセスを開始する
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, XpsSaveOptions, ICreateStreamProvider) {#converthtml_9}

[`HTMLDocument`](../../../com.aspose.html/htmldocument/) によって提示された HTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertHTML(HTMLDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| document | HTMLDocument | [`HTMLDocument`](../../../com.aspose.html/htmldocument/) によって提示された変換ソースです。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

HTML を XPS に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

XPS 変換

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を XPS に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント (HTMLDocument) を作成することもできます。変換結果。結果の出力ファイル パスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データ バッファとして使用します。カスタムまたはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザー シナリオに応じて 3 つ以上のパラメータで HTML を XPS 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質で簡単かつ高速に XPS に変換する無料のオンライン [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// フォームのソースファイルパス
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// フォームの結果ファイルパス
   	var resultPath = Path.Combine(OutputFolder, "result.xps");
		
	// 複数の方法のいずれかで HTML ドキュメントを作成
   	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
   	{
    	// 保存オプション オブジェクト インスタンスを定義する
    	var options = new XpsSaveOptions();

		// 既知の ICreateStreamProvider 実装のいずれかを使用する
  		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

    	// 変換プロセスを開始する
    	Converter.ConvertHTML(document, options, provider);
   	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, XpsSaveOptions, ICreateStreamProvider) {#converthtml_31}

URL によって提示された HTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertHTML(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | HTML ソースドキュメント URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

HTML を XPS に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

XPS 変換

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を XPS に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント (HTMLDocument) を作成することもできます。変換結果。結果の出力ファイル パスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データ バッファとして使用します。カスタムまたはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザー シナリオに応じて 3 つ以上のパラメータで HTML を XPS 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質で簡単かつ高速に XPS に変換する無料のオンライン [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 入力ファイルパスに基づいて Url を作成する
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// フォームの結果ファイルパス
   	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// ICreateStreamProvider 実装のいずれかを使用
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// 保存オプション オブジェクト インスタンスを定義する
	var options = new XpsSaveOptions();

	// 変換プロセスを開始する
	Converter.ConvertHTML(sourceUrl, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_20}

URL によって提示された HTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertHTML(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | HTML ソース URL - 汎用識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

HTML を XPS に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

XPS 変換

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を XPS に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント (HTMLDocument) を作成することもできます。変換結果。結果の出力ファイル パスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データ バッファとして使用します。カスタムまたはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザー シナリオに応じて 3 つ以上のパラメータで HTML を XPS 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質で簡単かつ高速に XPS に変換する無料のオンライン [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 入力ファイルパスに基づいて Url を作成する
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// フォームの結果ファイルパス
  	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// ICreateStreamProvider 実装のいずれかを使用
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// 保存オプション オブジェクト インスタンスを定義する
	var options = new XpsSaveOptions();

	// デフォルト構成で変換プロセスを開始する
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
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

## ConvertHTML(String, XpsSaveOptions, ICreateStreamProvider) {#converthtml_53}

完全なファイル パスで提示された HTML ソースを XPS に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertHTML(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | HTML ファイルのソース パスです。現在のディレクトリ パスと結合され、絶対 URL が形成されます。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装。 |

## Remarks

HTML を XPS に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

XPS 変換

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を XPS に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント (HTMLDocument) を作成することもできます。変換結果。結果の出力ファイル パスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データ バッファとして使用します。カスタムまたはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザー シナリオに応じて 3 つ以上のパラメータで HTML を XPS 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質で簡単かつ高速に XPS に変換する無料のオンライン [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// フォームのソースファイルパス
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// フォームの結果ファイルパス
   	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// ICreateStreamProvider 実装のいずれかを使用
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// 保存オプション オブジェクト インスタンスを定義する
	var options = new XpsSaveOptions();

	// 変換プロセスを開始する
	Converter.ConvertHTML(sourcePath, options, provider);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_42}

完全なファイル パスで提示された HTML ソースを XPS に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | HTML ファイルのソース パスです。現在のディレクトリ パスと結合され、絶対 URL が形成されます。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

HTML を XPS に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

XPS 変換

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を XPS に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント (HTMLDocument) を作成することもできます。変換結果。結果の出力ファイル パスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データ バッファとして使用します。カスタムまたはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザー シナリオに応じて 3 つ以上のパラメータで HTML を XPS 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質で簡単かつ高速に XPS に変換する無料のオンライン [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// フォームのソースファイルパス
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// フォームの結果ファイルパス
  	var resultPath = Path.Combine(OutputFolder, "result.xps");

	// ICreateStreamProvider 実装のいずれかを使用
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);
		
	// 保存オプション オブジェクト インスタンスを定義する
	var options = new XpsSaveOptions();

	// デフォルト構成で変換プロセスを開始する
	Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
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

## ConvertHTML(String, String, XpsSaveOptions, ICreateStreamProvider) {#converthtml_75}

インラインコンテンツで提供されたHTMLソースをXPSに変換します。結果は[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)インターフェイス実装によって生成された出力データです。

```java
public static void ConvertHTML(String content, String baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン HTML コンテンツとしての文字列。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

HTML を XPS に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

XPS 変換

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を XPS に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント (HTMLDocument) を作成することもできます。変換結果。結果の出力ファイル パスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データ バッファとして使用します。カスタムまたはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザー シナリオに応じて 3 つ以上のパラメータで HTML を XPS 結果として保存します。オンライン HTML コンバータ

Aspose.HTMLは、高品質で簡単かつ高速にHTMLをXPSに変換する無料のオンライン[HTML to XPS](https://products.aspose.app/html/en/conversion/html-to-xps)コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// インライン HTML コンテンツを作成		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result");

	// ICreateStreamProvider 実装のいずれかを使用
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// デフォルトの保存オプション オブジェクトを定義する
  	var options = new XpsSaveOptions();

	// 変換プロセスを開始する
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### 関連項目

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#converthtml_64}

インラインコンテンツで提供されたHTMLソースをXPSに変換します。結果は[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)インターフェイス実装によって生成された出力データです。

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン HTML コンテンツとしての文字列。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装。 |

## Remarks

HTML を XPS に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well. The main highlight of Aspose.HTML is the conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The com.aspose.html.converters package implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as [PDF](https://docs.fileformat.com/pdf/), [XPS](https://docs.fileformat.com/page-description-language/xps/), [DOCX](https://docs.fileformat.com/word-processing/docx/), [JPEG](https://docs.fileformat.com/image/jpeg/), [PNG](https://docs.fileformat.com/image/png/), [BMP](https://docs.fileformat.com/image/bmp/), [TIFF](https://docs.fileformat.com/image/tiff/), [GIF](https://docs.fileformat.com/image/gif/), [MHTML](https://docs.fileformat.com/web/mhtml/), and [MD](https://docs.fileformat.com/word-processing/md/).

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

XPS 変換

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. It has a set of advantages that support security features, such as digital signatures to provide greater document security and more. HTML to XPS conversion is often required to establish limited access to document editing or copying. XPS file format provides access rights management and gives high-quality printable documents. XPS files can be used to share documents, and you can be sure that what you see on the page is the same as what other people see when using the XPS Viewer.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

HTML を XPS に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to XPS. To convert HTML to XPS, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカル HTML ファイルまたはリモート URL を変換ソースとして検出します。インライン HTML コンテンツを変換ソースとして定義したり、任意の方法で HTML ドキュメント (HTMLDocument) を作成することもできます。変換結果。結果の出力ファイル パスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データ バッファとして使用します。カスタムまたはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。オプション パラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertHTML() メソッドを使用して、ユーザー シナリオに応じて 3 つ以上のパラメータで HTML を XPS 結果として保存します。オンライン HTML コンバータ

Aspose.HTML は、HTML を高品質で簡単かつ高速に XPS に変換する無料のオンライン [HTML to XPS Converter](https://products.aspose.app/html/en/conversion/html-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の人気のある形式変換を試してみてください

[HTML to PDF](https://products.aspose.app/html/en/conversion/html-to-pdf)

[HTML to DOCX](https://products.aspose.app/html/en/conversion/html-to-docx)

[HTML to MHTML](https://products.aspose.app/html/en/conversion/html-to-mhtml)

[HTML to Markdown](https://products.aspose.app/html/en/conversion/html-to-md)

特定の画像形式変換にも興味があるかもしれません

[HTML to PNG](https://products.aspose.app/html/en/conversion/html-to-png)

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// インライン HTML コンテンツを作成		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result");

	// ICreateStreamProvider 実装のいずれかを使用
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// デフォルトの保存オプション オブジェクトを定義する
 	var options = new XpsSaveOptions();

	// デフォルト構成で変換プロセスを開始する
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
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

## ConvertHTML(HTMLDocument, ImageSaveOptions, String) {#converthtml_3}

`[`HTMLDocument`](../../../com.aspose.html/htmldocument/)`で提供されたHTMLソースを変換します。結果は出力ファイルパスで生成された画像ファイルです。

```java
public static void ConvertHTML(HTMLDocument document, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| document | HTMLDocument | [`HTMLDocument`](../../../com.aspose.html/htmldocument/) によって提示された変換ソースです。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトの使用により、レンダリングプロセスを調整できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## Remarks

HTMLを画像に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

画像変換

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTMLを画像に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカルHTMLファイルまたはリモートURLを変換ソースとして検出します。インラインHTMLコンテンツを変換ソースとして定義したり、任意の方法でHTMLドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)インターフェイス実装を出力データバッファとして使用します。必要な[`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/)を指定して新しい[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトを作成します。デフォルトでは、FormatプロパティはPNGです。オプションパラメータとして[`configuration`](../../../com.aspose.html/configuration/)を追加することもできます。ConverterクラスのConvertHTML()メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータでHTMLを画像として保存します。オンラインHTMLコンバータ

Aspose.HTMLは、高品質で簡単かつ高速にHTMLを画像に変換する無料のオンライン[HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png)を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像形式変換にも興味があるかもしれません

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
// フォームのソースファイルパス
var sourcePath = Path.Combine(InputFolder, "source.html");

// フォームの結果ファイルパス
var outputPath = Path.Combine(OutputFolder, "result.jpg");

import (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
{
	// 保存オプション オブジェクト インスタンスを定義する
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// 変換プロセスを開始する
	Converter.ConvertHTML(document, options, outputPath);
}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, ImageSaveOptions, String) {#converthtml_25}

URLで提示されたHTMLソースを変換します。結果は、出力ファイルパスによって生成された画像ファイルです。

```java
public static void ConvertHTML(Url url, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | HTML ソース URL - 汎用識別子 (URL) のオブジェクト表現を提供します。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)などを指定できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## Remarks

HTMLを画像に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

画像変換

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTMLを画像に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカルHTMLファイルまたはリモートURLを変換ソースとして検出します。インラインHTMLコンテンツを変換ソースとして定義したり、任意の方法でHTMLドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)インターフェイス実装を出力データバッファとして使用します。必要な[`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/)を指定して新しい[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトを作成します。デフォルトでは、FormatプロパティはPNGです。オプションパラメータとして[`configuration`](../../../com.aspose.html/configuration/)を追加することもできます。ConverterクラスのConvertHTML()メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータでHTMLを画像として保存します。オンラインHTMLコンバータ

Aspose.HTMLは、高品質で簡単かつ高速にHTMLを画像に変換する無料のオンライン[HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png)を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像形式変換にも興味があるかもしれません

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 入力ファイルパスに基づいて Url を作成する
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// フォームの結果ファイルパス
   	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// 保存オプション オブジェクト インスタンスを定義する
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// 変換プロセスを開始する
	Converter.ConvertHTML(sourceUrl, options, resultPath);
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

## ConvertHTML(Url, Configuration, ImageSaveOptions, String) {#converthtml_14}

URLで提示されたHTMLソースを変換します。結果は、出力ファイルパスによって生成された画像ファイルです。

```java
public static void ConvertHTML(Url url, Configuration configuration, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | HTML ソース URL - 汎用識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | ImageSaveOptions | ImageSaveOptionsオブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)などを指定できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## Remarks

HTMLを画像に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

画像変換

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTMLを画像に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカルHTMLファイルまたはリモートURLを変換ソースとして検出します。インラインHTMLコンテンツを変換ソースとして定義したり、任意の方法でHTMLドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)インターフェイス実装を出力データバッファとして使用します。必要な[`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/)を指定して新しい[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトを作成します。デフォルトでは、FormatプロパティはPNGです。オプションパラメータとして[`configuration`](../../../com.aspose.html/configuration/)を追加することもできます。ConverterクラスのConvertHTML()メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータでHTMLを画像として保存します。オンラインHTMLコンバータ

Aspose.HTMLは、高品質で簡単かつ高速にHTMLを画像に変換する無料のオンライン[HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png)を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像形式変換にも興味があるかもしれません

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 入力ファイルパスに基づいて Url を作成する
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// フォームの結果ファイルパス
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// 保存オプション オブジェクト インスタンスを定義する
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// デフォルト構成で変換プロセスを開始する
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertHTML(String, ImageSaveOptions, String) {#converthtml_47}

完全なファイルパスで提示されたHTMLソースを画像に変換します。結果は、出力ファイルパスによって生成された画像ファイルです。

```java
public static void ConvertHTML(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | HTML ファイルのソース パスです。現在のディレクトリ パスと結合され、絶対 URL が形成されます。 |
| options | ImageSaveOptions | `[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)`クラスの詳細については、[Fine-Tuning Converters](https://docs.aspose.com/html/net/converting-between-formats/fine-tuning-converters/)記事をご覧ください。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## Remarks

HTMLを画像に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

画像変換

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTMLを画像に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカルHTMLファイルまたはリモートURLを変換ソースとして検出します。インラインHTMLコンテンツを変換ソースとして定義したり、任意の方法でHTMLドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)インターフェイス実装を出力データバッファとして使用します。必要な[`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/)を指定して新しい[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトを作成します。デフォルトでは、FormatプロパティはPNGです。オプションパラメータとして[`configuration`](../../../com.aspose.html/configuration/)を追加することもできます。ConverterクラスのConvertHTML()メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータでHTMLを画像として保存します。オンラインHTMLコンバータ

Aspose.HTMLは、高品質で簡単かつ高速にHTMLを画像に変換する無料のオンライン[HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png)を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像形式変換にも興味があるかもしれません

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// フォームのソースファイルパス
   	var sourcePath = Path.Combine(InputFolder, "source.html");

   	// フォームの結果ファイルパス
   	var resultPath = Path.Combine(OutputFolder, "result.png");
		
	// 保存オプションオブジェクトのインスタンスを定義します。デフォルトの画像形式はPNGです。
	var options = new ImageSaveOptions();

	// 変換プロセスを開始する
	Converter.ConvertHTML(sourcePath , options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, ImageSaveOptions, String) {#converthtml_36}

完全なファイルパスで提示されたHTMLソースを画像に変換します。結果は、出力ファイルパスによって生成された画像ファイルです。

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | HTML ファイルのソース パスです。現在のディレクトリ パスと結合され、絶対 URL が形成されます。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | ImageSaveOptions | `[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)`クラスの詳細については、[Fine-Tuning Converters](https://docs.aspose.com/html/net/converting-between-formats/fine-tuning-converters/)記事をご覧ください。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## Remarks

HTMLを画像に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

画像変換

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTMLを画像に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカルHTMLファイルまたはリモートURLを変換ソースとして検出します。インラインHTMLコンテンツを変換ソースとして定義したり、任意の方法でHTMLドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)インターフェイス実装を出力データバッファとして使用します。必要な[`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/)を指定して新しい[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトを作成します。デフォルトでは、FormatプロパティはPNGです。オプションパラメータとして[`configuration`](../../../com.aspose.html/configuration/)を追加することもできます。ConverterクラスのConvertHTML()メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータでHTMLを画像として保存します。オンラインHTMLコンバータ

Aspose.HTMLは、高品質で簡単かつ高速にHTMLを画像に変換する無料のオンライン[HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png)を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像形式変換にも興味があるかもしれません

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// フォームのソースファイルパス
  	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// フォームの結果ファイルパス
  	var resultPath = Path.Combine(OutputFolder, "result.png");
		
	// 保存オプションオブジェクトのインスタンスを定義します。デフォルトの画像形式はPNGです。
	var options = new ImageSaveOptions();

	// デフォルト構成で変換プロセスを開始する
	Converter.ConvertHTML(sourcePath, new Configuration(), options, resultPath);
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

## ConvertHTML(String, String, ImageSaveOptions, String) {#converthtml_69}

インライン コンテンツで提示された HTML ソースを画像に変換します。結果は出力ファイルパスで作成された画像ファイルです。

```java
public static void ConvertHTML(String content, String baseUri, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン HTML コンテンツとしての文字列。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| options | ImageSaveOptions | 新しく作成された画像オプション（形式、解像度など）をご確認ください。[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)クラスと[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers)をご参照ください。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## Remarks

HTMLを画像に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

画像変換

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTMLを画像に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカルHTMLファイルまたはリモートURLを変換ソースとして検出します。インラインHTMLコンテンツを変換ソースとして定義したり、任意の方法でHTMLドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)インターフェイス実装を出力データバッファとして使用します。必要な[`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/)を指定して新しい[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトを作成します。デフォルトでは、FormatプロパティはPNGです。オプションパラメータとして[`configuration`](../../../com.aspose.html/configuration/)を追加することもできます。ConverterクラスのConvertHTML()メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータでHTMLを画像として保存します。オンラインHTMLコンバータ

Aspose.HTMLは、高品質で簡単かつ高速にHTMLを画像に変換する無料のオンライン[HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png)を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像形式変換にも興味があるかもしれません

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// インライン HTML コンテンツを作成		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// デフォルトの保存オプション オブジェクトを定義する
  	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// 変換プロセスを開始する
	Converter.ConvertHTML(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### 関連項目

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, ImageSaveOptions, String) {#converthtml_58}

インライン コンテンツで提示された HTML ソースを画像に変換します。結果は出力ファイルパスで作成された画像ファイルです。

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン HTML コンテンツとしての文字列。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | ImageSaveOptions | 新しく作成された画像オプション（形式、解像度など）をご確認ください。[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)クラスと[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers)をご参照ください。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## Remarks

HTMLを画像に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

画像変換

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTMLを画像に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカルHTMLファイルまたはリモートURLを変換ソースとして検出します。インラインHTMLコンテンツを変換ソースとして定義したり、任意の方法でHTMLドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)インターフェイス実装を出力データバッファとして使用します。必要な[`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/)を指定して新しい[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトを作成します。デフォルトでは、FormatプロパティはPNGです。オプションパラメータとして[`configuration`](../../../com.aspose.html/configuration/)を追加することもできます。ConverterクラスのConvertHTML()メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータでHTMLを画像として保存します。オンラインHTMLコンバータ

Aspose.HTMLは、高品質で簡単かつ高速にHTMLを画像に変換する無料のオンライン[HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png)を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像形式変換にも興味があるかもしれません

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// インライン HTML コンテンツを作成		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// デフォルトの保存オプション オブジェクトを定義する
 	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// デフォルト構成で変換プロセスを開始する
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, ImageSaveOptions, ICreateStreamProvider) {#converthtml_2}

[`HTMLDocument`](../../../com.aspose.html/htmldocument/) によって提示された HTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertHTML(HTMLDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| document | HTMLDocument | [`HTMLDocument`](../../../com.aspose.html/htmldocument/) によって提示された変換ソースです。 |
| options | ImageSaveOptions | [`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトの使用により、レンダリングプロセスを調整できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

HTMLを画像に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

画像変換

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTMLを画像に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカルHTMLファイルまたはリモートURLを変換ソースとして検出します。インラインHTMLコンテンツを変換ソースとして定義したり、任意の方法でHTMLドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)インターフェイス実装を出力データバッファとして使用します。必要な[`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/)を指定して新しい[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトを作成します。デフォルトでは、FormatプロパティはPNGです。オプションパラメータとして[`configuration`](../../../com.aspose.html/configuration/)を追加することもできます。ConverterクラスのConvertHTML()メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータでHTMLを画像として保存します。オンラインHTMLコンバータ

Aspose.HTMLは、高品質で簡単かつ高速にHTMLを画像に変換する無料のオンライン[HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png)を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像形式変換にも興味があるかもしれません

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// フォームのソースファイルパス
	var sourcePath = Path.Combine(InputFolder, "source.html");

	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result");

	// 複数の方法のいずれかで HTML ドキュメントを作成
	using (HTMLDocument document = new HTMLDocument(sourcePath, new Configuration()))
	{
  		// 保存オプション オブジェクト インスタンスを定義する
  		var options = new ImageSaveOptions(ImageFormat.Jpeg);

  		// ICreateStreamProvider 実装のいずれかを使用
  		ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

  		// 変換プロセスを開始する
  		Converter.ConvertHTML(document, options, provider);
	}
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, ImageSaveOptions, ICreateStreamProvider) {#converthtml_24}

URL によって提示された HTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertHTML(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | HTML ソース URL - 汎用識別子 (URL) のオブジェクト表現を提供します。 |
| options | ImageSaveOptions | ImageSaveOptionsオブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)などを指定できます。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装。 |

## Remarks

HTMLを画像に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

画像変換

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTMLを画像に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカルHTMLファイルまたはリモートURLを変換ソースとして検出します。インラインHTMLコンテンツを変換ソースとして定義したり、任意の方法でHTMLドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)インターフェイス実装を出力データバッファとして使用します。必要な[`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/)を指定して新しい[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトを作成します。デフォルトでは、FormatプロパティはPNGです。オプションパラメータとして[`configuration`](../../../com.aspose.html/configuration/)を追加することもできます。ConverterクラスのConvertHTML()メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータでHTMLを画像として保存します。オンラインHTMLコンバータ

Aspose.HTMLは、高品質で簡単かつ高速にHTMLを画像に変換する無料のオンライン[HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png)を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像形式変換にも興味があるかもしれません

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 入力ファイルパスに基づいて Url を作成する
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

   	// フォームの結果ファイルパス
   	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// 保存オプション オブジェクト インスタンスを定義する
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// ICreateStreamProvider 実装のいずれかを使用
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// 変換プロセスを開始する
	Converter.ConvertHTML(sourceUrl, options, provider);
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

## ConvertHTML(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_13}

URL によって提示された HTML ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertHTML(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | HTML ソース URL - 汎用識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | ImageSaveOptions | ImageSaveOptionsオブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)などを指定できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用されるインターフェイスの実装です。プロバイダーに関する詳細は[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers)をご覧ください。 |

## Remarks

HTMLを画像に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

画像変換

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTMLを画像に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカルHTMLファイルまたはリモートURLを変換ソースとして検出します。インラインHTMLコンテンツを変換ソースとして定義したり、任意の方法でHTMLドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)インターフェイス実装を出力データバッファとして使用します。必要な[`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/)を指定して新しい[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトを作成します。デフォルトでは、FormatプロパティはPNGです。オプションパラメータとして[`configuration`](../../../com.aspose.html/configuration/)を追加することもできます。ConverterクラスのConvertHTML()メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータでHTMLを画像として保存します。オンラインHTMLコンバータ

Aspose.HTMLは、高品質で簡単かつ高速にHTMLを画像に変換する無料のオンライン[HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png)を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像形式変換にも興味があるかもしれません

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// 入力ファイルパスに基づいて Url を作成する
	var sourceUrl = new Url(Path.Combine(InputFolder, "source.html"));

  	// フォームの結果ファイルパス
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// 保存オプション オブジェクト インスタンスを定義する
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// ICreateStreamProvider 実装のいずれかを使用
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// デフォルト構成で変換プロセスを開始する
	Converter.ConvertHTML(sourceUrl, new Configuration(), options, provider);
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

---

## ConvertHTML(String, ImageSaveOptions, ICreateStreamProvider) {#converthtml_46}

フルファイルパスで提供されたHTMLソースを画像に変換します。結果は[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)インターフェイス実装によって生成された出力データです。

```java
public static void ConvertHTML(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | Html 完全ファイルソースパス。 |
| options | ImageSaveOptions | ImageSaveOptionsオブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)などを指定できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用されるインターフェイスの実装です。プロバイダーに関する詳細は[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers)をご覧ください。 |

## Remarks

HTMLを画像に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

画像変換

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTMLを画像に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカルHTMLファイルまたはリモートURLを変換ソースとして検出します。インラインHTMLコンテンツを変換ソースとして定義したり、任意の方法でHTMLドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)インターフェイス実装を出力データバッファとして使用します。必要な[`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/)を指定して新しい[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトを作成します。デフォルトでは、FormatプロパティはPNGです。オプションパラメータとして[`configuration`](../../../com.aspose.html/configuration/)を追加することもできます。ConverterクラスのConvertHTML()メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータでHTMLを画像として保存します。オンラインHTMLコンバータ

Aspose.HTMLは、高品質で簡単かつ高速にHTMLを画像に変換する無料のオンライン[HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png)を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像形式変換にも興味があるかもしれません

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// フォームのソースファイルパス
   	var sourcePath = Path.Combine(InputFolder, "source.html");

  	// フォームの結果ファイルパス
  	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// 保存オプション オブジェクト インスタンスを定義する
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// 既知の ICreateStreamProvider 実装のいずれかを使用する
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// 変換プロセスを開始する
	Converter.ConvertHTML(sourcePath, options, provider);
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

## ConvertHTML(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_35}

フルファイルパスで提供されたHTMLソースを画像に変換します。結果は[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)インターフェイス実装によって生成された出力データです。

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | HTML ファイルのソース パスです。現在のディレクトリ パスと結合され、絶対 URL が形成されます。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | ImageSaveOptions | ImageSaveOptionsオブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)などを指定できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用されるインターフェイスの実装です。プロバイダーに関する詳細は[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers)をご覧ください。 |

## Remarks

HTMLを画像に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

画像変換

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTMLを画像に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカルHTMLファイルまたはリモートURLを変換ソースとして検出します。インラインHTMLコンテンツを変換ソースとして定義したり、任意の方法でHTMLドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)インターフェイス実装を出力データバッファとして使用します。必要な[`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/)を指定して新しい[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトを作成します。デフォルトでは、FormatプロパティはPNGです。オプションパラメータとして[`configuration`](../../../com.aspose.html/configuration/)を追加することもできます。ConverterクラスのConvertHTML()メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータでHTMLを画像として保存します。オンラインHTMLコンバータ

Aspose.HTMLは、高品質で簡単かつ高速にHTMLを画像に変換する無料のオンライン[HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png)を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像形式変換にも興味があるかもしれません

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// フォームのソースファイルパス
  	var sourcePath = Path.Combine(InputFolder, "source.html");

 	// フォームの結果ファイルパス
 	var resultPath = Path.Combine(OutputFolder, "result.jpg");
		
	// 保存オプション オブジェクト インスタンスを定義する
	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// 既知の ICreateStreamProvider 実装のいずれかを使用する
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// デフォルト構成で変換プロセスを開始する
	Converter.ConvertHTML(sourcePath, new Configuration(), options, provider);
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

## ConvertHTML(String, String, ImageSaveOptions, ICreateStreamProvider) {#converthtml_68}

インラインコンテンツで提供されたHTMLソースを画像に変換します。結果は[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)インターフェイス実装によって生成された出力データです。

```java
public static void ConvertHTML(String content, String baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン HTML コンテンツとしての文字列。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| options | ImageSaveOptions | ImageSaveOptionsオブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)などを指定できます。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装。 |

## Remarks

HTMLを画像に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

画像変換

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTMLを画像に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカルHTMLファイルまたはリモートURLを変換ソースとして検出します。インラインHTMLコンテンツを変換ソースとして定義したり、任意の方法でHTMLドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)インターフェイス実装を出力データバッファとして使用します。必要な[`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/)を指定して新しい[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトを作成します。デフォルトでは、FormatプロパティはPNGです。オプションパラメータとして[`configuration`](../../../com.aspose.html/configuration/)を追加することもできます。ConverterクラスのConvertHTML()メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータでHTMLを画像として保存します。オンラインHTMLコンバータ

Aspose.HTMLは、高品質で簡単かつ高速にHTMLを画像に変換する無料のオンライン[HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png)を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像形式変換にも興味があるかもしれません

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// インライン HTML コンテンツを作成		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// デフォルトの保存オプション オブジェクトを定義する
  	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// 既知の ICreateStreamProvider 実装のいずれかを使用する
  	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// 変換プロセスを開始する
	Converter.ConvertHTML(content, String.Empty, options, provider);
```

*OutputFolder - user output file path.

### 関連項目

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#converthtml_57}

インラインコンテンツで提供されたHTMLソースを画像に変換します。結果は[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)インターフェイス実装によって生成された出力データです。

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン HTML コンテンツとしての文字列。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| configuration | Configuration | 環境構成です。アプリケーションの環境設定を行うために使用される[`configuration `](../../../com.aspose.html/configuration/)コンテキストオブジェクトを表します。 |
| options | ImageSaveOptions | ImageSaveOptionsオブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)などを指定できます。 |
| provider | ICreateStreamProvider | [`interface`](../../../com.aspose.html.io/icreatestreamprovider/)の実装で、出力ストリームを取得するために使用されます。プロバイダーに関する詳細は[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers)をご覧ください。 |

## Remarks

HTMLを画像に変換する方法

[HTML](https://docs.fileformat.com/web/html/) (HyperText Markup Language) is the standard markup language for documents created for display in browsers. Known as the language of the web, HTML has evolved with requirements of new information demands to be displayed as part of web pages. The latest variant is known as HTML 5 that gives a lot of flexibility for working with the language. HTML pages are either received from a server, where these are hosted or can be loaded from a local system as well.

Aspose.HTML の主なハイライトは変換機能です。さまざまな理由でフォーマット間の変換が必要です：慣れ親しんだ便利なフォーマットで作業したり、特定のタスクに適した別のフォーマットを活用したりするためです。com.aspose.html.converters パッケージは変換メソッドへの簡単なアクセスを実装しています。[PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/)、[MHTML](https://docs.fileformat.com/web/mhtml/)、および [MD](https://docs.fileformat.com/word-processing/md/) への幅広い HTML 変換を提供します。

この記事では、サポートされている HTML 変換の一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。HTML Converter ガイドでは、以下の記事が見つかります：

画像変換

[Convert HTML to JPG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/) - You learn how to convert HTML to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert HTML to PNG](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) - You learn how to convert HTML to PNG using the Aspose.HTML API and apply [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

[Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) - You learn how to convert HTML to BMP using the Aspose.HTML API and apply image save options.

[Convert HTML to TIFF](https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/) - You learn how to convert HTML to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert HTML to GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) - You find out the supported HTML to GIF conversion scenarios and consider examples to illustrate them.

他の人気のある形式変換

[Convert HTML to PDF](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) - You learn how to convert HTML document into a [Portable Document Format (PDF)](https://docs.fileformat.com/pdf/) file format.

[Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/) - You learn how to convert HTML to XPS - document storage and viewing format developed by Microsoft.

[Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/) - You learn how to convert HTML to Microsoft Word document (DOCX).

[Convert HTML to MHTML](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) - You learn how to convert HTML to MHTML which combines normal HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension.

[Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) - You learn how to convert HTML to MD as markup language with a plain-text-formatting syntax.

HTMLを画像に変換する

[`Converter`](../) class offers wide range of HTML specific conversions to images. To convert HTML to Image, you should follow one of simple scenarios consists of few steps:

変換ソース。既存のローカルHTMLファイルまたはリモートURLを変換ソースとして検出します。インラインHTMLコンテンツを変換ソースとして定義したり、任意の方法でHTMLドキュメント（HTMLDocument）を作成することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)インターフェイス実装を出力データバッファとして使用します。必要な[`ImageFormat`](../../../com.aspose.html.rendering.image/imageformat/)を指定して新しい[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトを作成します。デフォルトでは、FormatプロパティはPNGです。オプションパラメータとして[`configuration`](../../../com.aspose.html/configuration/)を追加することもできます。ConverterクラスのConvertHTML()メソッドを使用して、ユーザーシナリオに応じて3つ以上のパラメータでHTMLを画像として保存します。オンラインHTMLコンバータ

Aspose.HTMLは、高品質で簡単かつ高速にHTMLを画像に変換する無料のオンライン[HTML to PNG Converter](https://products.aspose.app/html/en/conversion/html-to-png)を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像形式変換にも興味があるかもしれません

[HTML to JPG](https://products.aspose.app/html/en/conversion/html-to-jpg)

[HTML to BMP](https://products.aspose.app/html/en/conversion/html-to-bmp)

[HTML to TIFF](https://products.aspose.app/html/en/conversion/html-to-tiff)

[HTML to GIF](https://products.aspose.app/html/en/conversion/html-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
	// インライン HTML コンテンツを作成		
	var content = @"<!DOCTYPE html><html><body><p style=""color:red;"">Hello, World!</p></body></html>";
	
	// フォームの結果ファイルパス
	var resultPath = Path.Combine(OutputFolder, "result.jpg");

	// デフォルトの保存オプション オブジェクトを定義する
 	var options = new ImageSaveOptions(ImageFormat.Jpeg);

	// 既知の ICreateStreamProvider 実装のいずれかを使用する
 	ICreateStreamProvider provider = new FileCreateStreamProvider(resultPath);

	// デフォルト構成で変換プロセスを開始する
	Converter.ConvertHTML(content, String.Empty, new Configuration(), options, provider);
```

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(HTMLDocument, TextSaveOptions, String) {#converthtml_8}

HTMLドキュメントをテキストに変換します。結果はTXTファイルです。

```java
public static void ConvertHTML(HTMLDocument document, TextSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| ドキュメント | HTMLDocument | 変換ソース。 |
| options | TextSaveOptions | 変換オプション。 |
| outputPath | 文字列 | 出力ファイルパス。 |

### 関連項目

* class [HTMLDocument](../../../com.aspose.html/htmldocument/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, TextSaveOptions, String) {#converthtml_30}

HTMLドキュメントをテキストに変換します。結果はTXTファイルです。

```java
public static void ConvertHTML(Url url, TextSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | ドキュメントの URL。 |
| options | TextSaveOptions | 変換オプション。 |
| outputPath | 文字列 | 出力ファイルパス。 |

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(Url, Configuration, TextSaveOptions, String) {#converthtml_19}

HTMLドキュメントをテキストに変換します。結果はTXTファイルです。

```java
public static void ConvertHTML(Url url, Configuration configuration, TextSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | ドキュメントの URL。 |
| 構成 | 構成 | 環境構成。 |
| options | TextSaveOptions | 変換オプション。 |
| outputPath | 文字列 | 出力ファイルパス。 |

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, TextSaveOptions, String) {#converthtml_52}

HTMLドキュメントをテキストに変換します。結果はTXTファイルです。

```java
public static void ConvertHTML(String sourcePath, TextSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | HTML ファイルのソース パスです。現在のディレクトリ パスと結合され、絶対 URL が形成されます。 |
| options | TextSaveOptions | 変換オプション。 |
| outputPath | 文字列 | 出力ファイルパス。 |

### 関連項目

* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, Configuration, TextSaveOptions, String) {#converthtml_41}

HTMLドキュメントをテキストに変換します。結果はTXTファイルです。

```java
public static void ConvertHTML(String sourcePath, Configuration configuration, 
    TextSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | HTML ファイルのソース パスです。現在のディレクトリ パスと結合され、絶対 URL が形成されます。 |
| 構成 | 構成 | 環境構成。 |
| options | TextSaveOptions | 変換オプション。 |
| outputPath | 文字列 | 出力ファイルパス。 |

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, TextSaveOptions, String) {#converthtml_74}

HTMLドキュメントをテキストに変換します。結果はTXTファイルです。

```java
public static void ConvertHTML(String content, String baseUri, TextSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン文字列 HTML コンテンツ。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| options | TextSaveOptions | 変換オプション。 |
| outputPath | 文字列 | 出力ファイルパス。 |

### 関連項目

* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertHTML(String, String, Configuration, TextSaveOptions, String) {#converthtml_63}

HTMLドキュメントをテキストに変換します。結果はTXTファイルです。

```java
public static void ConvertHTML(String content, String baseUri, Configuration configuration, 
    TextSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | インライン文字列 HTML コンテンツ。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| 構成 | 構成 | 環境構成。 |
| options | TextSaveOptions | 変換オプション。 |
| outputPath | 文字列 | 出力ファイルパス。 |

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [TextSaveOptions](../../../com.aspose.html.saving/textsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
