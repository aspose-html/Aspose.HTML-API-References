---
title: "Converter.ConvertEPUB"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Converter メソッド。データ入力ストリームで提示された EPUB ソースを変換します。結果は出力ファイルパスで生成されたファイルです。"
type: docs

url: /ja/java/com.aspose.html.converters/converter/convertepub/
---
## ConvertEPUB(Stream, ImageSaveOptions, String) {#convertepub_27}

データ入力ストリームで提供された EPUB ソースを変換します。結果は出力ファイルパスによって生成されたファイルです。

```java
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | 入力ストリームを変換元として使用します。 |
| options | ImageSaveOptions | 新しく作成された画像オプションとしてフォーマット、解像度などがあります。[`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) クラスと [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## 備考

EPUB を画像に変換する方法

EPUB は、標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。International Digital Publishing Forum (IDPF) によって作成され、現在は多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。

EPUB ファイルを PNG 形式に変換すると、PowerPoint プレゼンテーションにファイルを組み込んだり、メールで送信したりする際に便利です。画像形式に変換して好きなようにご利用ください。目的の結果を得るために、追加の変換パラメータを使用することもできます。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする Converter クラスを使用してそれらを実行する方法についての情報を提供します。EPUB コンバータガイドでは、以下の記事が掲載されています。

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB を画像に変換

EPUB を画像ファイル形式に変換するには、いくつかの手順に従う必要があります。

指定されたパスにある既存の EPUB ファイルに基づいて Url を定義します。結果の出力ファイルパスを定義します。必要な ImageFormat を指定して新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトでは、Format プロパティは PNG です。Converter クラスの ConvertEPUB() メソッドを使用して EPUB を画像として保存します。画像変換には ImageSaveOptions と Configuration オブジェクトも渡す必要があります。オンライン EPUB コンバータ

Aspose.HTML は、EPUB を高品質で簡単かつ高速に PNG 画像に変換する無料のオンライン [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像フォーマット変換にも興味があるかもしれません

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// 既存のファイルをストリームとして読み取り用に開く
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// 出力ファイルパスを定義する
var resultPath = Path.Combine(OutputFolder, "sample.png");

// デフォルトオプションのインスタンスを定義する
var options = new ImageSaveOptions();

// 変換プロセスを開始する
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, ImageSaveOptions, String) {#convertepub_43}

フルファイルパスで提供されるEPUBソースを変換します。結果は出力ファイルパスで生成された画像ファイルです。画像形式はImageSaveOptionsオブジェクトで指定されます。

```java
public static void ConvertEPUB(String sourcePath, ImageSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | 入力パラメータとして EPUB ソースファイルパスを指定します。 |
| options | ImageSaveOptions | ImageSaveOptions オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## 備考

EPUB を画像に変換する方法

EPUB は、標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。International Digital Publishing Forum (IDPF) によって作成され、現在は多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。

EPUB ファイルを PNG 形式に変換すると、PowerPoint プレゼンテーションにファイルを組み込んだり、メールで送信したりする際に便利です。画像形式に変換して好きなようにご利用ください。目的の結果を得るために、追加の変換パラメータを使用することもできます。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする Converter クラスを使用してそれらを実行する方法についての情報を提供します。EPUB コンバータガイドでは、以下の記事が掲載されています。

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB を画像に変換

EPUB を画像ファイル形式に変換するには、いくつかの手順に従う必要があります。

指定されたパスにある既存の EPUB ファイルに基づいて Url を定義します。結果の出力ファイルパスを定義します。必要な ImageFormat を指定して新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトでは、Format プロパティは PNG です。Converter クラスの ConvertEPUB() メソッドを使用して EPUB を画像として保存します。画像変換には ImageSaveOptions と Configuration オブジェクトも渡す必要があります。オンライン EPUB コンバータ

Aspose.HTML は、EPUB を高品質で簡単かつ高速に PNG 画像に変換する無料のオンライン [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像フォーマット変換にも興味があるかもしれません

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// フォームのソースファイルパス
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// 出力結果ファイルパスを作成する
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// デフォルトの ImageSaveOptions オブジェクトインスタンスを定義する
var options = new ImageSaveOptions(); 

// 変換プロセスを開始する
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - custom output folder path.

### 関連項目

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, String) {#convertepub_11}

URLで定義されたEPUBソースを変換します。結果は出力ファイルパスで生成された画像ファイルです。画像形式はImageSaveOptionsオブジェクトで指定されます。

```java
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | EPUB ソース URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| options | ImageSaveOptions | ImageSaveOptions オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。[`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) クラスをご参照ください。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## 備考

EPUB を画像に変換する方法

EPUB は、標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。International Digital Publishing Forum (IDPF) によって作成され、現在は多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。

EPUB ファイルを PNG 形式に変換すると、PowerPoint プレゼンテーションにファイルを組み込んだり、メールで送信したりする際に便利です。画像形式に変換して好きなようにご利用ください。目的の結果を得るために、追加の変換パラメータを使用することもできます。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする Converter クラスを使用してそれらを実行する方法についての情報を提供します。EPUB コンバータガイドでは、以下の記事が掲載されています。

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB を画像に変換

EPUB を画像ファイル形式に変換するには、いくつかの手順に従う必要があります。

指定されたパスにある既存の EPUB ファイルに基づいて Url を定義します。結果の出力ファイルパスを定義します。必要な ImageFormat を指定して新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトでは、Format プロパティは PNG です。Converter クラスの ConvertEPUB() メソッドを使用して EPUB を画像として保存します。画像変換には ImageSaveOptions と Configuration オブジェクトも渡す必要があります。オンライン EPUB コンバータ

Aspose.HTML は、EPUB を高品質で簡単かつ高速に PNG 画像に変換する無料のオンライン [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像フォーマット変換にも興味があるかもしれません

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// 入力ファイルパスに基づいて Url を作成する
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// 出力結果ファイルパスを作成する
var resultPath = Path.Combine(OutputFolder, "sample.png");

// デフォルトオプションのインスタンスを定義する
var options = new ImageSaveOptions();

// 変換プロセスを開始する
Converter.ConvertEPUB(sourceUrl, options, resultPath);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, String) {#convertepub_19}

データ入力ストリームで提供されるEPUBソースを変換します。結果は出力ファイルパスで生成された画像ファイルです。画像形式はImageSaveOptionsオブジェクトで指定されます。

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | 入力ストリームを変換元として使用します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | ImageSaveOptions | ImageSaveOptions オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## 備考

EPUB を画像に変換する方法

EPUB は、標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。International Digital Publishing Forum (IDPF) によって作成され、現在は多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。

EPUB ファイルを PNG 形式に変換すると、PowerPoint プレゼンテーションにファイルを組み込んだり、メールで送信したりする際に便利です。画像形式に変換して好きなようにご利用ください。目的の結果を得るために、追加の変換パラメータを使用することもできます。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする Converter クラスを使用してそれらを実行する方法についての情報を提供します。EPUB コンバータガイドでは、以下の記事が掲載されています。

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB を画像に変換

EPUB を画像ファイル形式に変換するには、いくつかの手順に従う必要があります。

指定されたパスにある既存の EPUB ファイルに基づいて Url を定義します。結果の出力ファイルパスを定義します。必要な ImageFormat を指定して新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトでは、Format プロパティは PNG です。Converter クラスの ConvertEPUB() メソッドを使用して EPUB を画像として保存します。画像変換には ImageSaveOptions と Configuration オブジェクトも渡す必要があります。オンライン EPUB コンバータ

Aspose.HTML は、EPUB を高品質で簡単かつ高速に PNG 画像に変換する無料のオンライン [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像フォーマット変換にも興味があるかもしれません

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// 既存のファイルをストリームとして読み取り用に開く
var inputStream = System.IO.File.OpenRead(Path.Combine(InputFolder, "sample.epub"));

// 出力ファイルパスを定義する
var resultPath = Path.Combine(OutputFolder, "sample.png");

// デフォルトオプションのインスタンスを定義する
var options = new ImageSaveOptions();

// デフォルトの構成オブジェクトで変換プロセスを開始する
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
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

## ConvertEPUB(String, Configuration, ImageSaveOptions, String) {#convertepub_35}

フルファイルパスで提供されるEPUBソースを変換します。結果は出力ファイルパスで生成された画像ファイルです。画像形式はImageSaveOptionsオブジェクトで指定されます。

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | 入力パラメータとして EPUB ソースファイルパスを指定します。 |
| configuration | Configuration | 環境構成です。[configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) コンテキストオブジェクトを表し、アプリケーションの環境設定を構成するために使用されます。 |
| options | ImageSaveOptions | ImageSaveOptions オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。[`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) クラスをご参照ください。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## 備考

EPUB を画像に変換する方法

EPUB は、標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。International Digital Publishing Forum (IDPF) によって作成され、現在は多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。

EPUB ファイルを PNG 形式に変換すると、PowerPoint プレゼンテーションにファイルを組み込んだり、メールで送信したりする際に便利です。画像形式に変換して好きなようにご利用ください。目的の結果を得るために、追加の変換パラメータを使用することもできます。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする Converter クラスを使用してそれらを実行する方法についての情報を提供します。EPUB コンバータガイドでは、以下の記事が掲載されています。

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB を画像に変換

EPUB を画像ファイル形式に変換するには、いくつかの手順に従う必要があります。

指定されたパスにある既存の EPUB ファイルに基づいて Url を定義します。結果の出力ファイルパスを定義します。必要な ImageFormat を指定して新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトでは、Format プロパティは PNG です。Converter クラスの ConvertEPUB() メソッドを使用して EPUB を画像として保存します。画像変換には ImageSaveOptions と Configuration オブジェクトも渡す必要があります。オンライン EPUB コンバータ

Aspose.HTML は、EPUB を高品質で簡単かつ高速に PNG 画像に変換する無料のオンライン [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像フォーマット変換にも興味があるかもしれません

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// フォームのソースファイルパス
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// 出力結果ファイルパスを作成する
var resultPath = Path.Combine(OutputFolder, "sample.png"); 

// デフォルトの ImageSaveOptions オブジェクトインスタンスを定義する
var options = new ImageSaveOptions(); 

// デフォルトの構成オブジェクトで変換プロセスを開始する
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
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

## ConvertEPUB(Url, Configuration, ImageSaveOptions, String) {#convertepub_3}

URLで定義されたEPUBソースを変換します。結果は出力ファイルパスで生成された画像ファイルです。画像形式はImageSaveOptionsオブジェクトで指定されます。

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | EPUB ソース URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | ImageSaveOptions | ImageSaveOptions オブジェクトの使用により、レンダリングプロセスを調整できます。[page size](https://apireference.aspose.com/html/net/aspose.html.rendering/renderingoptions/properties/pagesetup)、[margins](https://apireference.aspose.com/html/net/aspose.html.drawing/page/properties/margin)、[CSS media-type](https://apireference.aspose.com/html/net/aspose.html.rendering/mediatype) などを指定できます。[ImageSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions) クラスをご参照ください。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## 備考

EPUB を画像に変換する方法

EPUB は、標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。International Digital Publishing Forum (IDPF) によって作成され、現在は多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。

EPUB ファイルを PNG 形式に変換すると、PowerPoint プレゼンテーションにファイルを組み込んだり、メールで送信したりする際に便利です。画像形式に変換して好きなようにご利用ください。目的の結果を得るために、追加の変換パラメータを使用することもできます。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする Converter クラスを使用してそれらを実行する方法についての情報を提供します。EPUB コンバータガイドでは、以下の記事が掲載されています。

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB を画像に変換

EPUB を画像ファイル形式に変換するには、いくつかの手順に従う必要があります。

指定されたパスにある既存の EPUB ファイルに基づいて Url を定義します。結果の出力ファイルパスを定義します。必要な ImageFormat を指定して新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトでは、Format プロパティは PNG です。Converter クラスの ConvertEPUB() メソッドを使用して EPUB を画像として保存します。画像変換には ImageSaveOptions と Configuration オブジェクトも渡す必要があります。オンライン EPUB コンバータ

Aspose.HTML は、EPUB を高品質で簡単かつ高速に PNG 画像に変換する無料のオンライン [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像フォーマット変換にも興味があるかもしれません

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
// 入力ファイルパスに基づいて Url を作成する
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));  

// 出力ファイルパスを定義する
var resultPath = Path.Combine(OutputFolder, "sample.png"); 
 
// デフォルトオプションのインスタンスを定義する
var options = new ImageSaveOptions(); 

// デフォルトの構成オブジェクトで変換プロセスを開始する
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);  
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

## ConvertEPUB(Stream, ImageSaveOptions, ICreateStreamProvider) {#convertepub_26}

入力された [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) によって提示された epub ソースを画像に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイスの実装によって生成された画像ファイルです。

```java
public static void ConvertEPUB(Stream stream, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | 入力ストリームを変換元として使用します。 |
| options | ImageSaveOptions | ImageSaveOptions オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。[`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) クラスをご参照ください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイスの実装です。詳細なサンプルは [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers) をご覧ください。 |

## 備考

EPUB を画像に変換する方法

EPUB は、標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。International Digital Publishing Forum (IDPF) によって作成され、現在は多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。

EPUB ファイルを PNG 形式に変換すると、PowerPoint プレゼンテーションにファイルを組み込んだり、メールで送信したりする際に便利です。画像形式に変換して好きなようにご利用ください。目的の結果を得るために、追加の変換パラメータを使用することもできます。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする Converter クラスを使用してそれらを実行する方法についての情報を提供します。EPUB コンバータガイドでは、以下の記事が掲載されています。

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB を画像に変換

EPUB を画像ファイル形式に変換するには、いくつかの手順に従う必要があります。

既存の EPUB ファイルを開きます。例では、指定されたパスのファイルシステムから EPUB ファイルを開いて読み取るために System.IO.FileStream クラスの OpenRead() メソッドを使用します。既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。必要な ImageFormat を指定して新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトでは、Format プロパティは PNG です。Converter クラスの ConvertEPUB() メソッドを使用して EPUB を画像として保存します。EPUB の inputStream、ImageSaveOptions、出力ストリームを ConvertEPUB() メソッドに渡す必要があります。オンライン EPUB コンバータ

Aspose.HTML は、EPUB を高品質で簡単かつ高速に PNG 画像に変換する無料のオンライン [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像フォーマット変換にも興味があるかもしれません

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 既存のファイルをストリームとして読み取り用に開く
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// ICreateStreamProvider インターフェイスの実装を参照してください
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// デフォルトオプションのインスタンスを作成する
var options = new ImageSaveOptions();    

// 変換プロセスを開始する
Converter.ConvertEPUB(inputStream, options, sp);
```

*InputFolder - user input folder path.

*OutputFolder - user output folder path.

### 関連項目

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, ImageSaveOptions, ICreateStreamProvider) {#convertepub_42}

ファイルパスで指定された EPUB ソースを画像に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイスの実装によって生成された画像ファイルです。

```java
public static void ConvertEPUB(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | EPUB ソースファイルパスです。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |
| options | ImageSaveOptions | 新しく作成された画像オプションとしてフォーマット、解像度などがあります。[`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) クラスと [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用されるインターフェイスの実装です。プロバイダーに関する詳細情報は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers) をご覧ください。 |

## 備考

EPUB を画像に変換する方法

EPUB は、標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。International Digital Publishing Forum (IDPF) によって作成され、現在は多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。

EPUB ファイルを PNG 形式に変換すると、PowerPoint プレゼンテーションにファイルを組み込んだり、メールで送信したりする際に便利です。画像形式に変換して好きなようにご利用ください。目的の結果を得るために、追加の変換パラメータを使用することもできます。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする Converter クラスを使用してそれらを実行する方法についての情報を提供します。EPUB コンバータガイドでは、以下の記事が掲載されています。

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB を画像に変換

EPUB を画像ファイル形式に変換するには、いくつかの手順に従う必要があります。

既存の EPUB ファイルを開きます。例では、指定されたパスのファイルシステムから EPUB ファイルを開いて読み取るために System.IO.FileStream クラスの OpenRead() メソッドを使用します。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。必要な ImageFormat を指定して新しい ImageSaveOptions オブジェクトを作成します。デフォルトでは、Format プロパティは PNG です。Converter クラスの ConvertEPUB() メソッドを使用して EPUB を画像として保存します。EPUB の inputStream、ImageSaveOptions、出力ストリームを ConvertEPUB() メソッドに渡す必要があります。オンライン EPUB コンバータ

Aspose.HTML は、EPUB を高品質で簡単かつ高速に PNG 画像に変換する無料のオンライン [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像フォーマット変換にも興味があるかもしれません

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

2 行のコードで EPUB を JPG に変換

```java
import System.IO;
import com.aspose.html.converters;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
// 既存の EPUB ファイルを読み取り用に開く。
import var stream = File.OpenRead(DataDir + "input.epub");

// ConvertEPUB メソッドを呼び出して、EPUB コードを JPG 画像に変換します。
Converter.ConvertEPUB(stream, new ImageSaveOptions(ImageFormat.Jpeg), Path.Combine(OutputDir, "convert-by-two-lines.jpg"));
```

*DataDir - user source file path.

*OutputDir - user output file path.

### 関連項目

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, ImageSaveOptions, ICreateStreamProvider) {#convertepub_10}

URL で提示された EPUB ソースを画像に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイスの実装によって生成された画像ファイルです。

```java
public static void ConvertEPUB(Url sourceUrl, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | EPUB ソース URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| options | ImageSaveOptions | ImageSaveOptions オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。[`ImageSaveOptions `](../../../com.aspose.html.saving/imagesaveoptions/) クラスをご参照ください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用されるインターフェイスの実装です。プロバイダーに関する詳細情報は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers) をご覧ください。 |

## 備考

EPUB を画像に変換する方法

EPUB は、標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。International Digital Publishing Forum (IDPF) によって作成され、現在は多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。

EPUB ファイルを PNG 形式に変換すると、PowerPoint プレゼンテーションにファイルを組み込んだり、メールで送信したりする際に便利です。画像形式に変換して好きなようにご利用ください。目的の結果を得るために、追加の変換パラメータを使用することもできます。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする Converter クラスを使用してそれらを実行する方法についての情報を提供します。EPUB コンバータガイドでは、以下の記事が掲載されています。

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB を画像に変換

EPUB を画像ファイル形式に変換するには、いくつかの手順に従う必要があります。

既存の EPUB ファイルを開きます。例では、指定されたパスのファイルシステムから EPUB ファイルを開いて読み取るために System.IO.FileStream クラスの OpenRead() メソッドを使用します。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。必要な ImageFormat を指定して新しい ImageSaveOptions オブジェクトを作成します。デフォルトでは、Format プロパティは PNG です。Converter クラスの ConvertEPUB() メソッドを使用して EPUB を画像として保存します。EPUB の inputStream、ImageSaveOptions、出力ストリームを ConvertEPUB() メソッドに渡す必要があります。オンライン EPUB コンバータ

Aspose.HTML は、EPUB を高品質で簡単かつ高速に PNG 画像に変換する無料のオンライン [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像フォーマット変換にも興味があるかもしれません

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

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
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// ICreateStreamProvider インターフェイスの実装を参照してください
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// デフォルトオプションのインスタンスを作成する
var options = new ImageSaveOptions();

// 変換プロセスを開始する
Converter.ConvertEPUB(sourceUrl, options, sp);
```

*InputFolder - user input folder.

*OutputFolder - user output folder.

*ImageSaveOptions supposes PNG format of new formed image.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_18}

入力された [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) によって提示された epub ソースを画像に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイスの実装によって生成された画像ファイルです。

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | 入力ストリームを変換元として使用します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | ImageSaveOptions | ImageSaveOptions オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。 |
| プロバイダー | ICreateStreamProvider | 出力ストリームを取得するために使用されるインターフェイスの実装です。 |

## 備考

EPUB を画像に変換する方法

EPUB は、標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。International Digital Publishing Forum (IDPF) によって作成され、現在は多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。

EPUB ファイルを PNG 形式に変換すると、PowerPoint プレゼンテーションにファイルを組み込んだり、メールで送信したりする際に便利です。画像形式に変換して好きなようにご利用ください。目的の結果を得るために、追加の変換パラメータを使用することもできます。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする Converter クラスを使用してそれらを実行する方法についての情報を提供します。EPUB コンバータガイドでは、以下の記事が掲載されています。

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB を画像に変換

EPUB を画像ファイル形式に変換するには、いくつかの手順に従う必要があります。

既存の EPUB ファイルを開きます。例では、指定されたパスのファイルシステムから EPUB ファイルを開いて読み取るために System.IO.FileStream クラスの OpenRead() メソッドを使用します。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。必要な ImageFormat を指定して新しい ImageSaveOptions オブジェクトを作成します。デフォルトでは、Format プロパティは PNG です。Converter クラスの ConvertEPUB() メソッドを使用して EPUB を画像として保存します。EPUB の inputStream、ImageSaveOptions、出力ストリームを ConvertEPUB() メソッドに渡す必要があります。オンライン EPUB コンバータ

Aspose.HTML は、EPUB を高品質で簡単かつ高速に PNG 画像に変換する無料のオンライン [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像フォーマット変換にも興味があるかもしれません

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 既存のファイルをストリームとして読み取り用に開く
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  


// ICreateStreamProvider インターフェイスの実装を参照してください
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  


// デフォルトオプションのインスタンスを作成する
var options = new ImageSaveOptions();    


// デフォルト設定で変換プロセスを開始します。
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_34}

ファイルパスで指定された EPUB ソースを画像に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイスの実装によって生成された画像ファイルです。

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | ファイルパスで定義された EPUB ソースです。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | ImageSaveOptions | ImageSaveOptions オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用されるインターフェイスの実装です。[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers) にある ICreateStreamProvider 実装サンプルをご覧ください。 |

## 備考

EPUB を画像に変換する方法

EPUB は、標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。International Digital Publishing Forum (IDPF) によって作成され、現在は多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。

EPUB ファイルを PNG 形式に変換すると、PowerPoint プレゼンテーションにファイルを組み込んだり、メールで送信したりする際に便利です。画像形式に変換して好きなようにご利用ください。目的の結果を得るために、追加の変換パラメータを使用することもできます。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする Converter クラスを使用してそれらを実行する方法についての情報を提供します。EPUB コンバータガイドでは、以下の記事が掲載されています。

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB を画像に変換

EPUB を画像ファイル形式に変換するには、いくつかの手順に従う必要があります。

既存の EPUB ファイルを開きます。例では、指定されたパスのファイルシステムから EPUB ファイルを開いて読み取るために System.IO.FileStream クラスの OpenRead() メソッドを使用します。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。必要な ImageFormat を指定して新しい ImageSaveOptions オブジェクトを作成します。デフォルトでは、Format プロパティは PNG です。Converter クラスの ConvertEPUB() メソッドを使用して EPUB を画像として保存します。EPUB の inputStream、ImageSaveOptions、出力ストリームを ConvertEPUB() メソッドに渡す必要があります。オンライン EPUB コンバータ

Aspose.HTML は、EPUB を高品質で簡単かつ高速に PNG 画像に変換する無料のオンライン [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像フォーマット変換にも興味があるかもしれません

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// フォームのソースファイルパス
var sourcePath = Path.Combine(InputFolder, "sample.epub"); 

// ICreateStreamProvider インターフェイスの実装を参照してください
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// デフォルトの ImageSaveOptions オブジェクトインスタンスを定義する
var options = new ImageSaveOptions(); 

// デフォルトの構成オブジェクトで変換プロセスを開始する
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertepub_2}

URLで提供されたepubソースを画像に変換します。結果は[ICreateStreamProvider](https://apireference.aspose.com/html/net/aspose.html.io/icreatestreamprovider)インターフェイスの実装によって生成された画像ファイルです。

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | EPUB ソース URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | ImageSaveOptions | ImageSaveOptions オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/), [`margins`](../../../com.aspose.html.drawing/page/margin/), [`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用されるインターフェイスの実装です。[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers) にある ICreateStreamProvider 実装サンプルをご覧ください。 |

## 備考

EPUB を画像に変換する方法

EPUB は、標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。International Digital Publishing Forum (IDPF) によって作成され、現在は多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。

EPUB ファイルを PNG 形式に変換すると、PowerPoint プレゼンテーションにファイルを組み込んだり、メールで送信したりする際に便利です。画像形式に変換して好きなようにご利用ください。目的の結果を得るために、追加の変換パラメータを使用することもできます。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめ、快適で使いやすくする Converter クラスを使用してそれらを実行する方法についての情報を提供します。EPUB コンバータガイドでは、以下の記事が掲載されています。

[Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) - You learn how to convert EPUB to JPEG image using the Aspose.HTML API and consider examples to illustrate them.

[Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/) - You learn how to convert EPUB to PNG using the Aspose.HTML API and apply ImageSaveOptions and ICreateStreamProvider parameters.

[Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/) - You learn how to convert EPUB to BMP using the Aspose.HTML API and apply image save options.

[Convert EPUB to TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) - You learn how to convert EPUB to TIFF using the Aspose.HTML API and consider examples to illustrate the conversion.

[Convert EPUB to GIF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/) - You find out the supported EPUB to GIFconversion scenarios and consider examples to illustrate them.

EPUB を画像に変換

EPUB を画像ファイル形式に変換するには、いくつかの手順に従う必要があります。

既存の EPUB ファイルを開きます。例では、指定されたパスのファイルシステムから EPUB ファイルを開いて読み取るために System.IO.FileStream クラスの OpenRead() メソッドを使用します。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。必要な ImageFormat を指定して新しい ImageSaveOptions オブジェクトを作成します。デフォルトでは、Format プロパティは PNG です。Converter クラスの ConvertEPUB() メソッドを使用して EPUB を画像として保存します。EPUB の inputStream、ImageSaveOptions、出力ストリームを ConvertEPUB() メソッドに渡す必要があります。オンライン EPUB コンバータ

Aspose.HTML は、EPUB を高品質で簡単かつ高速に PNG 画像に変換する無料のオンライン [EPUB to PNG](https://products.aspose.app/html/en/conversion/epub-to-png) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

特定の画像フォーマット変換にも興味があるかもしれません

[EPUB to JPG](https://products.aspose.app/html/en/conversion/epub-to-jpg)

[EPUB to BMP](https://products.aspose.app/html/en/conversion/epub-to-bmp)

[EPUB to TIFF](https://products.aspose.app/html/en/conversion/epub-to-tiff)

[EPUB to GIF](https://products.aspose.app/html/en/conversion/epub-to-gif)

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...
// 入力ファイルパスからソース URL を作成します
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// ICreateStreamProvider インターフェイスの実装を参照してください
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.png"));  

// デフォルトオプションのインスタンスを作成する
var options = new ImageSaveOptions();

// デフォルト構成で変換プロセスを開始する
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);

```

*InputFolder - user source file path.

*OutputFolder - user output file path.

*ImageSaveOptions supposes PNG format of new formed image.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, XpsSaveOptions, String) {#convertepub_31}

入力ストリームで提供されるepubソースをxpsに変換します。結果はフルパスで定義されたxpsファイルです。

```java
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | Stream | 変換ソースとして入力ストリームを使用します。[official source](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) のストリーム仕様をご参照ください。 |
| options | XpsSaveOptions | 変換オプション。[`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを使用すると、レンダリングプロセスを調整できます。ページサイズ、余白、CSS などを指定できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な .xps ファイルパスです。 |

## 備考

EPUB を XPS に変換する方法

XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。EMF ファイル形式の代替として開発され、PDF ファイル形式に似ていますが、文書のレイアウト、外観、印刷情報に XML を使用します。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめて使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。EPUB Converter XPS の特定ガイドでは、次の記事が掲載されています。

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB を XPS に変換する

EPUB を XPS ファイル形式に変換するには、いくつかの手順に従う必要があります。

既存の EPUB ファイルを開きます。例として、ConvertEPUB メソッドの最初のパラメータとしてソースファイルパスを定義できます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスというよりシンプルな代替手段を使用することもできます。ページサイズ、余白、CSS などの好みのパラメータを指定した新しい XpsSaveOptions オブジェクトを作成します。XpsSaveOptions クラスの既定インスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を XPS ファイルとして保存します。変換プロセスを開始するために、EPUB ソースデータ、XpsSaveOptions、そして任意の形態の出力データバッファを渡す必要があります。オンライン EPUB to XPS コンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に XPS ファイルに変換する無料のオンライン [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System.Drawing;
import com.aspose.html.drawing;
...
  // 既存の EPUB ファイルを読み取り用に開きます
  using var stream = File.OpenRead(DataDir + "input.epub");

  // 変換されたファイルを保存するパスを準備します
  String savePath = Path.Combine(OutputDir, "input-options.xps");
   
  // XpsSaveOptions のインスタンスを作成します。ページサイズを設定し、背景色を LightGray に変更します
  var options = new XpsSaveOptions()
  {
    PageSetup =
      {
        AnyPage = new Page()
        {
          Size = new com.aspose.html.drawing.Size(Length.FromPixels(500), Length.FromPixels(500))
        }
      },
    BackgroundColor = Color.LightGray
  };
   
  // ConvertEPUB メソッドを呼び出して EPUB を XPS に変換します
  Converter.ConvertEPUB(stream, options, savePath); 
```

*DataDir - some user input folder.

*OutputDir - user output folder.

### 関連項目

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, XpsSaveOptions, String) {#convertepub_47}

入力EPUBファイルパスで提供されるepubソースをxpsに変換します。結果はフルパスで定義されたxpsファイルです。

```java
public static void ConvertEPUB(String sourcePath, XpsSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | EPUB ソースファイルパスです。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |
| options | XpsSaveOptions | 変換オプション。[`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを使用すると、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な .xps ファイルパスです。 |

## 備考

EPUB を XPS に変換する方法

XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。EMF ファイル形式の代替として開発され、PDF ファイル形式に似ていますが、文書のレイアウト、外観、印刷情報に XML を使用します。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめて使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。EPUB Converter XPS の特定ガイドでは、次の記事が掲載されています。

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB を XPS に変換する

EPUB を XPS ファイル形式に変換するには、いくつかの手順に従う必要があります。

既存の EPUB ファイルを開きます。例として、ConvertEPUB メソッドの最初のパラメータにソースファイルパスを設定できます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスというシンプルな代替手段も利用可能です。ページサイズ、余白、CSS などの好みのパラメータを指定した新しい XpsSaveOptions オブジェクトを作成します。XpsSaveOptions クラスの既定インスタンスを使用することもできます。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を XPS ファイルとして保存します。変換プロセスを開始するために、EPUB ソースデータ、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/)、および任意の形態の出力データバッファを渡す必要があります。オンライン EPUB to XPS コンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に XPS ファイルに変換する無料のオンライン [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// フォームのソースファイルパス
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// 出力結果ファイルパスを作成する
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// デフォルトオプションのインスタンスを作成する
var options = new XpsSaveOptions();

// デフォルト構成で変換プロセスを開始する
Converter.ConvertEPUB(sourcePath, options, resultPath);  
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, XpsSaveOptions, String) {#convertepub_15}

URLで提供されるepubソースをフルパスで定義されたxpsファイルに変換します。詳細は[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/)をご覧ください。

```java
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | EPUB ソース URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| options | XpsSaveOptions | 変換オプション。[`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを使用すると、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な .xps ファイルパスです。 |

## 備考

EPUB を XPS に変換する方法

XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。EMF ファイル形式の代替として開発され、PDF ファイル形式に似ていますが、文書のレイアウト、外観、印刷情報に XML を使用します。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめて使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。EPUB Converter XPS の特定ガイドでは、次の記事が掲載されています。

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB を XPS に変換する

EPUB を XPS ファイル形式に変換するには、いくつかの手順に従う必要があります。

既存の EPUB ファイルを開きます。例として、ConvertEPUB メソッドの最初のパラメータにソースファイルパスを定義できます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスというよりシンプルな代替手段を使用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定して新しい XpsSaveOptions オブジェクトを作成します。XpsSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を XPS ファイルとして保存します。変換プロセスを開始するには、EPUB ソースデータ、XpsSaveOptions、そして出力データバッファを任意の形で渡す必要があります。

オンライン EPUB から XPS へのコンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に XPS ファイルに変換する無料のオンライン [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...
// 入力ファイルパスからソース URL を作成します
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// 出力結果ファイルパスを作成する
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// デフォルトオプションのインスタンスを作成する
var options = new XpsSaveOptions();

// 変換プロセスを開始する
Converter.ConvertEPUB(sourceUrl, options, resultPath);





*InputFolder - user input directory.

```

*OutputFolder - user output directory.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, String) {#convertepub_23}

入力[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0)で提供されるepubソースをxpsに変換します。結果はフルパスで定義されたxpsファイルです。

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | 入力ストリームを変換元として使用します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | XpsSaveOptions | 変換オプション。[`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを使用すると、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な .xps ファイルパスです。 |

## 備考

EPUB を XPS に変換する方法

XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。EMF ファイル形式の代替として開発され、PDF ファイル形式に似ていますが、文書のレイアウト、外観、印刷情報に XML を使用します。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめて使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。EPUB Converter XPS の特定ガイドでは、次の記事が掲載されています。

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB を XPS に変換する

EPUB を XPS ファイル形式に変換するには、いくつかの手順に従う必要があります。

既存の EPUB ファイルを開きます。例として、ConvertEPUB メソッドの最初のパラメータにソースファイルパスを定義できます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスというよりシンプルな代替手段を使用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定して新しい XpsSaveOptions オブジェクトを作成します。XpsSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を XPS ファイルとして保存します。変換プロセスを開始するには、EPUB ソースデータ、XpsSaveOptions、そして出力データバッファを任意の形で渡す必要があります。設定として、アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを使用できます。オンライン EPUB から XPS へのコンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に XPS ファイルに変換する無料のオンライン [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;
...

// 既存の EPUB ファイルを読み取り用に開きます
import var stream = File.OpenRead(DataDir + "input.epub");

// 変換後のファイル保存用パスを準備する
String savePath = Path.Combine(OutputDir, "input-output.xps");       
   
// XpsSaveOptions を初期化する
var options = new XpsSaveOptions();
   
// ConvertEPUB メソッドを呼び出して EPUB を XPS に変換します
Converter.ConvertEPUB(stream, new Configuration(), options, savePath);





*DataDir - user input folder.

```

*OutputDir - user output folder.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, XpsSaveOptions, String) {#convertepub_39}

入力EPUBファイルパスで提供されるepubソースをxpsに変換します。結果はフルパスで定義されたxpsファイルです。

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | EPUB ソースファイルパスです。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |
| configuration | Configuration | 環境構成です。[configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) コンテキストオブジェクトを表し、アプリケーションの環境設定を構成するために使用されます。 |
| options | XpsSaveOptions | 変換オプション。 [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) オブジェクトの使用により、レンダリングプロセスを調整できます。ページサイズ、余白、CSS などを指定できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な .xps ファイルパスです。 |

## 備考

EPUB を XPS に変換する方法

XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。EMF ファイル形式の代替として開発され、PDF ファイル形式に似ていますが、文書のレイアウト、外観、印刷情報に XML を使用します。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめて使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。EPUB Converter XPS の特定ガイドでは、次の記事が掲載されています。

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB を XPS に変換する

EPUB を XPS ファイル形式に変換するには、いくつかの手順に従う必要があります。

既存の EPUB ファイルを開きます。例として、ConvertEPUB メソッドの最初のパラメータにソースファイルパスを定義できます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスというよりシンプルな代替手段を使用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定して新しい XpsSaveOptions オブジェクトを作成します。XpsSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を XPS ファイルとして保存します。変換プロセスを開始するには、EPUB ソースデータ、XpsSaveOptions、そして出力データバッファを任意の形で渡す必要があります。設定として、アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを使用できます。オンライン EPUB から XPS へのコンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に XPS ファイルに変換する無料のオンライン [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// フォームのソースファイルパス
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// 出力結果ファイルパスを作成する
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// デフォルトオプションのインスタンスを作成する
var options = new XpsSaveOptions();

// デフォルト構成で変換プロセスを開始する
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);  
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

## ConvertEPUB(Url, Configuration, XpsSaveOptions, String) {#convertepub_7}

URLで提供されるepubソースをフルパスで定義されたxpsファイルに変換します。詳細は[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/)をご覧ください。

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | EPUB ソース URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成です。[configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) コンテキストオブジェクトを表し、アプリケーションの環境設定を構成するために使用されます。 |
| options | XpsSaveOptions | 変換オプション。 [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) オブジェクトの使用により、レンダリングプロセスを調整できます。ページサイズ、余白、CSS などを指定できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な .xps ファイルパスです。 |

## 備考

EPUB を XPS に変換する方法

XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。EMF ファイル形式の代替として開発され、PDF ファイル形式に似ていますが、文書のレイアウト、外観、印刷情報に XML を使用します。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめて使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。EPUB Converter XPS の特定ガイドでは、次の記事が掲載されています。

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB を XPS に変換する

EPUB を XPS ファイル形式に変換するには、いくつかの手順に従う必要があります。

既存の EPUB ファイルを開きます。例として、ConvertEPUB メソッドの最初のパラメータにソースファイルパスを定義できます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスというよりシンプルな代替手段を使用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定して新しい XpsSaveOptions オブジェクトを作成します。XpsSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を XPS ファイルとして保存します。変換プロセスを開始するには、EPUB ソースデータ、XpsSaveOptions、そして出力データバッファを任意の形で渡す必要があります。設定として、アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを使用できます。オンライン EPUB から XPS へのコンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に XPS ファイルに変換する無料のオンライン [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import com.aspose.html.saving;
import com.aspose.html.converters;
...
// 入力ファイルパスからソース URL を作成します
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// 出力結果ファイルパスを作成する
var resultPath = Path.Combine(OutputFolder, "sample.xps");

// デフォルトオプションのインスタンスを作成する
var options = new XpsSaveOptions();

// デフォルト設定で変換プロセスを開始する
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, XpsSaveOptions, ICreateStreamProvider) {#convertepub_30}

入力された [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) によって提示された EPUB ソースを XPS に変換します。結果は、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装で定義された XPS 出力データです。

```java
public static void ConvertEPUB(Stream stream, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | 入力ストリームを変換元として使用します。 |
| options | XpsSaveOptions | 変換オプション。 [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用されるインターフェイスの実装です。[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers) にある ICreateStreamProvider 実装サンプルをご覧ください。 |

## 備考

EPUB を XPS に変換する方法

XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。EMF ファイル形式の代替として開発され、PDF ファイル形式に似ていますが、文書のレイアウト、外観、印刷情報に XML を使用します。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめて使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。EPUB Converter XPS の特定ガイドでは、次の記事が掲載されています。

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB を XPS に変換する

EPUB を XPS ファイル形式に変換するには、いくつかの手順に従う必要があります。

既存の EPUB ファイルを開きます。例として、ConvertEPUB メソッドの最初のパラメータにソースファイルパスを定義できます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスというよりシンプルな代替手段を使用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定して新しい XpsSaveOptions オブジェクトを作成します。XpsSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を XPS ファイルとして保存します。変換プロセスを開始するには、EPUB ソースデータ、XpsSaveOptions、そして出力データバッファを任意の形で渡す必要があります。設定として、アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを使用できます。オンライン EPUB から XPS へのコンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に XPS ファイルに変換する無料のオンライン [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import Aspose.Html;
import System.Linq;
import com.aspose.html.converters;
import com.aspose.html.saving;
...
 // MemoryStreamProvider のインスタンスを作成する
 using var streamProvider = new MemoryStreamProvider();

 // 既存の EPUB ファイルを読み取り用に開きます
 using var stream = File.OpenRead(DataDir + "input.epub");
  
 // 変換されたファイルを保存するパスを準備します
 String savePath = Path.Combine(OutputDir, "stream-provider.xps");
  
 // MemoryStreamProvider クラスを使用して EPUB を XPS に変換する
 Converter.ConvertEPUB(stream, new XpsSaveOptions(), streamProvider);
  
 // 結果データを含むメモリストリームへのアクセスを取得する
 var memory = streamProvider.Streams.First();
 memory.Seek(0, SeekOrigin.Begin);

 // 結果データを出力ファイルにフラッシュする
 using (FileStream fs = File.Create(savePath))
 {
  memory.CopyTo(fs);
 }
```

*DataDir - user source file path.

*OutputDir- user output file path.

*See MemoryStreamProvider class as ICreateStreamProvider implementation in [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers).

### 関連項目

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, XpsSaveOptions, ICreateStreamProvider) {#convertepub_46}

入力された EPUB ファイルパスで提示された EPUB ソースを XPS に変換します。結果は、既知またはカスタムの [`ICreateStreamProvider `](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装で定義された XPS 出力データです。

```java
public static void ConvertEPUB(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | EPUB ソースファイルパスです。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |
| options | XpsSaveOptions | 変換オプション。 [XpsSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions) オブジェクトの使用により、レンダリングプロセスを調整できます。ページサイズ、余白、CSS などを指定できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用されるインターフェイスの実装です。[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers) にある高度なサンプルをご覧ください。 |

## 備考

EPUB を XPS に変換する方法

XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。EMF ファイル形式の代替として開発され、PDF ファイル形式に似ていますが、文書のレイアウト、外観、印刷情報に XML を使用します。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめて使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。EPUB Converter XPS の特定ガイドでは、次の記事が掲載されています。

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB を XPS に変換する

EPUB を XPS ファイル形式に変換するには、いくつかの手順に従う必要があります。

既存の EPUB ファイルを開きます。例として、ConvertEPUB メソッドの最初のパラメータとしてソースファイルパスを定義できます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスというよりシンプルな代替手段を使用することもできます。ページサイズ、余白、CSS などの好みのパラメータを指定した新しい XpsSaveOptions オブジェクトを作成します。XpsSaveOptions クラスの既定インスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を XPS ファイルとして保存します。変換プロセスを開始するために、EPUB ソースデータ、XpsSaveOptions、そして任意の形態の出力データバッファを渡す必要があります。オンライン EPUB to XPS コンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に XPS ファイルに変換する無料のオンライン [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// フォームのソースファイルパス
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// ICreateStreamProvider インターフェイスの実装を参照してください
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// デフォルトオプションのインスタンスを作成する
var options = new XpsSaveOptions();

// デフォルト構成で変換プロセスを開始する
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, XpsSaveOptions, ICreateStreamProvider) {#convertepub_14}

URL で提示された EPUB ソースをフルパスで定義された XPS ファイルに変換します。結果は、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装で定義された XPS 出力データです。

```java
public static void ConvertEPUB(Url sourceUrl, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | EPUB ソース URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| options | XpsSaveOptions | 変換オプション。 [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。ページサイズ、余白、CSS などを指定できます。[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers) にある高度なサンプルをご覧ください。 |

## 備考

EPUB を XPS に変換する方法

XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。EMF ファイル形式の代替として開発され、PDF ファイル形式に似ていますが、文書のレイアウト、外観、印刷情報に XML を使用します。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめて使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。EPUB Converter XPS の特定ガイドでは、次の記事が掲載されています。

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB を XPS に変換する

EPUB を XPS ファイル形式に変換するには、いくつかの手順に従う必要があります。

既存の EPUB ファイルを開きます。例として、ConvertEPUB メソッドの最初のパラメータにソースファイルパスを定義できます。既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスというよりシンプルな代替手段を使用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定して新しい XpsSaveOptions オブジェクトを作成します。XpsSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を XPS ファイルとして保存します。変換プロセスを開始するには、EPUB ソースデータ、XpsSaveOptions、そして出力データバッファを任意の形で渡す必要があります。オンライン EPUB から XPS へのコンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に XPS ファイルに変換する無料のオンライン [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// 入力ファイルパスからソース URL を作成します
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// ICreateStreamProvider インターフェイスの実装を参照してください
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// デフォルトオプションのインスタンスを作成する
var options = new XpsSaveOptions();

// 変換プロセスを開始する
Converter.ConvertEPUB(sourceUrl, options, sp);
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

## ConvertEPUB(Stream, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_22}

入力された [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) によって提示された EPUB ソースを XPS に変換します。結果は、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装で定義された XPS 出力データです。

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | 入力ストリームを変換元として使用します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | XpsSaveOptions | 変換オプション。 [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイスの実装です。[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers) にある高度なサンプルをご覧ください。 |

## 備考

EPUB を XPS に変換する方法

XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。EMF ファイル形式の代替として開発され、PDF ファイル形式に似ていますが、文書のレイアウト、外観、印刷情報に XML を使用します。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめて使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。EPUB Converter XPS の特定ガイドでは、次の記事が掲載されています。

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB を XPS に変換する

EPUB を XPS ファイル形式に変換するには、いくつかの手順に従う必要があります。

既存の EPUB ファイルを開きます。例として、ConvertEPUB メソッドの最初のパラメータにソースファイルパスを定義できます。既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスというよりシンプルな代替手段を使用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定して新しい XpsSaveOptions オブジェクトを作成します。XpsSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を XPS ファイルとして保存します。変換プロセスを開始するには、EPUB ソースデータ、XpsSaveOptions、そして出力データバッファを任意の形で渡す必要があります。設定として、アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを使用できます。オンライン EPUB から XPS へのコンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に XPS ファイルに変換する無料のオンライン [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// 既存のファイルをストリームとして読み取り用に開く
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// ICreateStreamProvider インターフェイスの実装を参照してください
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// デフォルトオプションのインスタンスを作成する
var options = new XpsSaveOptions();

// デフォルト構成で変換プロセスを開始する
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
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

## ConvertEPUB(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_38}

入力された EPUB ファイルパスで提示された EPUB ソースを XPS に変換します。結果は、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装で定義された XPS 出力データです。

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | EPUB ソースファイルパスです。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | XpsSaveOptions | 変換オプション。[`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを使用すると、レンダリングプロセスを調整できます。ページサイズ、余白、CSS などを指定できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイスの実装です。[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers) にある高度なサンプルをご覧ください。 |

## 備考

EPUB を XPS に変換する方法

XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。EMF ファイル形式の代替として開発され、PDF ファイル形式に似ていますが、文書のレイアウト、外観、印刷情報に XML を使用します。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめて使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。EPUB Converter XPS の特定ガイドでは、次の記事が掲載されています。

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB を XPS に変換する

EPUB を XPS ファイル形式に変換するには、いくつかの手順に従う必要があります。

既存の EPUB ファイルを開きます。例として、ConvertEPUB メソッドの最初のパラメータにソースファイルパスを定義できます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスというよりシンプルな代替手段を使用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定して新しい XpsSaveOptions オブジェクトを作成します。XpsSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を XPS ファイルとして保存します。変換プロセスを開始するには、EPUB ソースデータ、XpsSaveOptions、そして出力データバッファを任意の形で渡す必要があります。設定として、アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを使用できます。オンライン EPUB から XPS へのコンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に XPS ファイルに変換する無料のオンライン [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// フォームのソースファイルパス
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// ICreateStreamProvider インターフェイスの実装を参照してください
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.xps"));  

// デフォルトオプションのインスタンスを作成する
var options = new XpsSaveOptions();

// デフォルト構成で変換プロセスを開始する
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertepub_6}

URL で提示された EPUB ソースをフルパスで定義された XPS ファイルに変換します。結果は、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装で定義された XPS 出力データです。

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | EPUB ソース URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | XpsSaveOptions | 変換オプション。 [`XpsSaveOptions `](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイスの実装です。[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers) にある高度なサンプルをご覧ください。 |

## 備考

EPUB を XPS に変換する方法

XPS ファイルは、Microsoft が作成した XML Paper Specification に基づくページレイアウトファイルを表します。EMF ファイル形式の代替として開発され、PDF ファイル形式に似ていますが、文書のレイアウト、外観、印刷情報に XML を使用します。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめて使いやすくする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。EPUB Converter XPS の特定ガイドでは、次の記事が掲載されています。

[Convert EPUB to XPS](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) - You learn how to convert an EPUB document into XML Paper Specification ([XPS](https://docs.fileformat.com/page-description-language/xps/)) file format, use save options and ICreateStreamProvider parameters.

EPUB を XPS に変換する

EPUB を XPS ファイル形式に変換するには、いくつかの手順に従う必要があります。

既存の EPUB ファイルを開きます。例として、ConvertEPUB メソッドの最初のパラメータにソースファイルパスを定義できます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスというよりシンプルな代替手段を使用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定して新しい XpsSaveOptions オブジェクトを作成します。XpsSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を XPS ファイルとして保存します。変換プロセスを開始するには、EPUB ソースデータ、XpsSaveOptions、そして出力データバッファを任意の形で渡す必要があります。設定として、アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを使用できます。オンライン EPUB から XPS へのコンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に XPS ファイルに変換する無料のオンライン [EPUB to XPS](https://products.aspose.app/html/en/conversion/epub-to-xps) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters;

// 入力ファイルパスからソース URL を作成します
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// 出力結果ファイルパスを作成する
var resultPath = Path.Combine(OutputFolder, " sample.xps");

// デフォルトオプションのインスタンスを作成する
var options = new XpsSaveOptions();

// デフォルト構成で変換プロセスを開始する
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, DocSaveOptions, String) {#convertepub_25}

完全パスで指定された EPUB ソースファイルを DOCX に変換します。結果は完全パスで定義された docx ファイルです。

```java
public static void ConvertEPUB(Stream stream, DocSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | Stream | 入力された [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream?view=net-5.0) によって提示された変換ソース。 |
| options | DocSaveOptions | 変換オプション。[`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/) 、[`margins`](../../../com.aspose.html.drawing/page/margin/) 、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な .docx ファイルパス。 |

## 備考

EPUB を DOCX に変換する方法

DOCX は Microsoft Word 文書のよく知られたフォーマットです。このフォーマットは、幅広い書式設定機能をサポートし、あらゆる種類の文書を作成するためのさまざまなオプションをユーザーに提供するため、人気があります。DOCX ファイルは Word 2007 以降のバージョンで開くことができますが、DOC ファイル拡張子をサポートする旧バージョンの MS Word では開けません。EPUB から DOCX への変換は、特定のユーザータスクで DOCX フォーマットを活用するためにしばしば必要とされます。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめ、使いやすく快適にする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。EPUB Converter の DOCX 固有ガイドでは、次の記事が掲載されています。

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB を DOCX に変換する

EPUB を DOCX ファイル形式に変換するには、以下の手順に従ってください：

既存の EPUB ファイルを開きます。例として、ソースファイルパスを ConvertEPUB メソッドの最初のパラメータとして定義できます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスを使用するという、よりシンプルな代替手段も利用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定した新しい DocSaveOptions オブジェクトを作成します。DocSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を docx ファイルとして保存します。変換プロセスを開始するには、EPUB ソースをファイルパスまたは入力ストリームとして、さらに Url、DocSaveOptions インスタンス、および任意の形態の出力データバッファを渡す必要があります。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表す configuration を使用できます。オンライン EPUB to DOCX コンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に DOCX ファイルに変換する無料のオンライン [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 既存のファイルをストリームとして読み取り用に開く
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// 出力結果ファイルパスを作成する
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// デフォルトオプションのインスタンスを作成する
var options = new DocSaveOptions();   

// 変換プロセスを開始する
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, DocSaveOptions, String) {#convertepub_41}

フルファイルパスで提供されるEPUBソースをDOCXに変換します。結果は出力ファイルパスで生成されたdocxファイルです。

```java
public static void ConvertEPUB(String sourcePath, DocSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | 入力パラメータとして EPUB ソースファイルパスを指定します。 |
| options | DocSaveOptions | 変換オプション。[`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](...),[` margins`](...),[`CSS media-type`](...) などを指定できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な .docx ファイルパス。 |

## 備考

EPUB を DOCX に変換する方法

DOCX は Microsoft Word 文書のよく知られたフォーマットです。このフォーマットは、幅広い書式設定機能をサポートし、あらゆる種類の文書を作成するためのさまざまなオプションをユーザーに提供するため、人気があります。DOCX ファイルは Word 2007 以降のバージョンで開くことができますが、DOC ファイル拡張子をサポートする旧バージョンの MS Word では開けません。EPUB から DOCX への変換は、特定のユーザータスクで DOCX フォーマットを活用するためにしばしば必要とされます。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめ、使いやすく快適にする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。EPUB Converter の DOCX 固有ガイドでは、次の記事が掲載されています。

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB を DOCX に変換する

EPUB を DOCX ファイル形式に変換するには、以下の手順に従ってください：

既存の EPUB ファイルを開きます。例として、ソースファイルパスを ConvertEPUB メソッドの最初のパラメータとして定義できます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスを使用するという、よりシンプルな代替手段も利用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定した新しい DocSaveOptions オブジェクトを作成します。DocSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を docx ファイルとして保存します。変換プロセスを開始するには、EPUB ソースをファイルパスまたは入力ストリームとして、さらに Url、DocSaveOptions インスタンス、および任意の形態の出力データバッファを渡す必要があります。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表す configuration を使用できます。オンライン EPUB to DOCX コンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に DOCX ファイルに変換する無料のオンライン [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// フォームのソースファイルパス
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// 出力結果ファイルパスを作成する
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// デフォルトオプションのインスタンスを定義する
var options = new DocSaveOptions();

// 変換プロセスを開始する
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, DocSaveOptions, String) {#convertepub_9}

URLで提供されるEPUBソースを変換します。結果は出力ファイルパスで生成されたdocxファイルです。

```java
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | EPUB ソース URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)` の使用により、レンダリングプロセスを調整できます。[`page size`](...), [`margins`](...), [`resolutions`](...), [`CSS media-type`](...) などを指定できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な .docx ファイルパス。 |

## 備考

EPUB を DOCX に変換する方法

DOCX は Microsoft Word 文書のよく知られたフォーマットです。このフォーマットは、幅広い書式設定機能をサポートし、あらゆる種類の文書を作成するためのさまざまなオプションをユーザーに提供するため、人気があります。DOCX ファイルは Word 2007 以降のバージョンで開くことができますが、DOC ファイル拡張子をサポートする旧バージョンの MS Word では開けません。EPUB から DOCX への変換は、特定のユーザータスクで DOCX フォーマットを活用するためにしばしば必要とされます。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめ、使いやすく快適にする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。EPUB Converter の DOCX 固有ガイドでは、次の記事が掲載されています。

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB を DOCX に変換する

EPUB を DOCX ファイル形式に変換するには、以下の手順に従ってください：

既存の EPUB ファイルを開きます。例として、ソースファイルパスを ConvertEPUB メソッドの最初のパラメータとして定義できます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスを使用するという、よりシンプルな代替手段も利用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定した新しい DocSaveOptions オブジェクトを作成します。DocSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を docx ファイルとして保存します。変換プロセスを開始するには、EPUB ソースをファイルパスまたは入力ストリームとして、さらに Url、DocSaveOptions インスタンス、および任意の形態の出力データバッファを渡す必要があります。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表す configuration を使用できます。オンライン EPUB to DOCX コンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に DOCX ファイルに変換する無料のオンライン [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 入力ファイルパスからソース URL を作成します
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// 出力結果ファイルパスを作成する
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// デフォルトオプションのインスタンスを定義する
var options = new DocSaveOptions();

// 変換プロセスを開始する
Converter.ConvertEPUB(sourceUrl, options, resultPath);
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

## ConvertEPUB(Stream, Configuration, DocSaveOptions, String) {#convertepub_17}

データ入力ストリームで提供されるEPUBソースを変換します。結果は出力ファイルパスで生成されたdocxファイルです。

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | 入力ストリームを変換元として使用します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | DocSaveOptions | 変換オプション。[`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/) 、[`margins`](../../../com.aspose.html.drawing/page/margin/) 、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な .docx ファイルパス。 |

## 備考

EPUB を DOCX に変換する方法

DOCX は Microsoft Word 文書のよく知られたフォーマットです。このフォーマットは、幅広い書式設定機能をサポートし、あらゆる種類の文書を作成するためのさまざまなオプションをユーザーに提供するため、人気があります。DOCX ファイルは Word 2007 以降のバージョンで開くことができますが、DOC ファイル拡張子をサポートする旧バージョンの MS Word では開けません。EPUB から DOCX への変換は、特定のユーザータスクで DOCX フォーマットを活用するためにしばしば必要とされます。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめ、使いやすく快適にする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。EPUB Converter の DOCX 固有ガイドでは、次の記事が掲載されています。

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB を DOCX に変換する

EPUB を DOCX ファイル形式に変換するには、以下の手順に従ってください：

既存の EPUB ファイルを開きます。例として、ソースファイルパスを ConvertEPUB メソッドの最初のパラメータとして定義できます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスを使用するという、よりシンプルな代替手段も利用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定した新しい DocSaveOptions オブジェクトを作成します。DocSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を docx ファイルとして保存します。変換プロセスを開始するには、EPUB ソースをファイルパスまたは入力ストリームとして、さらに Url、DocSaveOptions インスタンス、および任意の形態の出力データバッファを渡す必要があります。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表す configuration を使用できます。オンライン EPUB to DOCX コンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に DOCX ファイルに変換する無料のオンライン [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 既存のファイルをストリームとして読み取り用に開く
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// 出力結果ファイルパスを作成する
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// デフォルトオプションのインスタンスを作成する
var options = new DocSaveOptions();   

// デフォルト設定で変換プロセスを開始する
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);
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

## ConvertEPUB(String, Configuration, DocSaveOptions, String) {#convertepub_33}

フルファイルパスで提供されるEPUBソースをDOCXに変換します。結果は出力ファイルパスで生成されたdocxファイルです。

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | EPUB ソースファイルパスです。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | DocSaveOptions | 変換オプション。[DocSaveOptions ](https://apireference.aspose.com/html/net/aspose.html.saving/docsaveoptions) オブジェクトの使用により、レンダリングプロセスを調整できます。ページサイズ、余白、CSS などを指定できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な .docx ファイルパス。 |

## 備考

EPUB を DOCX に変換する方法

DOCX は Microsoft Word 文書のよく知られたフォーマットです。このフォーマットは、幅広い書式設定機能をサポートし、あらゆる種類の文書を作成するためのさまざまなオプションをユーザーに提供するため、人気があります。DOCX ファイルは Word 2007 以降のバージョンで開くことができますが、DOC ファイル拡張子をサポートする旧バージョンの MS Word では開けません。EPUB から DOCX への変換は、特定のユーザータスクで DOCX フォーマットを活用するためにしばしば必要とされます。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめ、使いやすく快適にする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。EPUB Converter の DOCX 固有ガイドでは、次の記事が掲載されています。

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB を DOCX に変換する

EPUB を DOCX ファイル形式に変換するには、以下の手順に従ってください：

既存の EPUB ファイルを開きます。例として、ソースファイルパスを ConvertEPUB メソッドの最初のパラメータとして定義できます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスを使用するという、よりシンプルな代替手段も利用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定した新しい DocSaveOptions オブジェクトを作成します。DocSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を docx ファイルとして保存します。変換プロセスを開始するには、EPUB ソースをファイルパスまたは入力ストリームとして、さらに Url、DocSaveOptions インスタンス、および任意の形態の出力データバッファを渡す必要があります。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表す configuration を使用できます。オンライン EPUB to DOCX コンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に DOCX ファイルに変換する無料のオンライン [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// フォームのソースファイルパス
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// 出力結果ファイルパスを作成する
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// デフォルトオプションのインスタンスを定義する
var options = new DocSaveOptions();

// デフォルト構成で変換プロセスを開始する
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);
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

## ConvertEPUB(Url, Configuration, DocSaveOptions, String) {#convertepub_1}

URLで提供されるEPUBソースを変換します。結果は出力ファイルパスで生成されたdocxファイルです。

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | EPUB ソース URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)` の使用により、レンダリングプロセスを調整できます。[`page size`](...), [`margins`](...), [`resolutions`](...), [`CSS media-type`](...) などを指定できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な .docx ファイルパス。 |

## 備考

EPUB を DOCX に変換する方法

DOCX は Microsoft Word 文書のよく知られたフォーマットです。このフォーマットは、幅広い書式設定機能をサポートし、あらゆる種類の文書を作成するためのさまざまなオプションをユーザーに提供するため、人気があります。DOCX ファイルは Word 2007 以降のバージョンで開くことができますが、DOC ファイル拡張子をサポートする旧バージョンの MS Word では開けません。EPUB から DOCX への変換は、特定のユーザータスクで DOCX フォーマットを活用するためにしばしば必要とされます。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめ、使いやすく快適にする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。EPUB Converter の DOCX 固有ガイドでは、次の記事が掲載されています。

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB を DOCX に変換する

EPUB を DOCX ファイル形式に変換するには、以下の手順に従ってください：

既存の EPUB ファイルを開きます。例として、ソースファイルパスを ConvertEPUB メソッドの最初のパラメータとして定義できます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスを使用するという、よりシンプルな代替手段も利用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定した新しい DocSaveOptions オブジェクトを作成します。DocSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を docx ファイルとして保存します。変換プロセスを開始するには、EPUB ソースをファイルパスまたは入力ストリームとして、さらに Url、DocSaveOptions インスタンス、および任意の形態の出力データバッファを渡す必要があります。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表す configuration を使用できます。オンライン EPUB to DOCX コンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に DOCX ファイルに変換する無料のオンライン [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 入力ファイルパスからソース URL を作成します
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// 変換結果ファイルパスの形式
var resultPath = Path.Combine(OutputFolder, "sample.docx");

// デフォルトオプションのインスタンスを作成する
var options = new DocSaveOptions();

// デフォルト設定で変換プロセスを開始します。
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertEPUB(Stream, DocSaveOptions, ICreateStreamProvider) {#convertepub_24}

EPUB ソースを入力ストリームとして DOCX に変換します。結果は ICreateStreamProvider 実装によって生成された docx ファイルです。

```java
public static void ConvertEPUB(Stream stream, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | 入力ストリームを変換元として使用します。 |
| options | DocSaveOptions | 変換オプション。[`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/) 、[`margins`](../../../com.aspose.html.drawing/page/margin/) 、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | `[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)` インターフェイスの実装で、出力ストリームを取得するために使用されます。詳細なサンプルは [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers) を参照してください。 |

## 備考

EPUB を DOCX に変換する方法

DOCX は Microsoft Word 文書のよく知られたフォーマットです。このフォーマットは、幅広い書式設定機能をサポートし、あらゆる種類の文書を作成するためのさまざまなオプションをユーザーに提供するため、人気があります。DOCX ファイルは Word 2007 以降のバージョンで開くことができますが、DOC ファイル拡張子をサポートする旧バージョンの MS Word では開けません。EPUB から DOCX への変換は、特定のユーザータスクで DOCX フォーマットを活用するためにしばしば必要とされます。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめ、使いやすく快適にする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。EPUB Converter の DOCX 固有ガイドでは、次の記事が掲載されています。

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB を DOCX に変換する

EPUB を DOCX ファイル形式に変換するには、以下の手順に従ってください：

既存の EPUB ファイルを開きます。例として、ソースファイルパスを ConvertEPUB メソッドの最初のパラメータとして定義できます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスを使用するという、よりシンプルな代替手段も利用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定した新しい DocSaveOptions オブジェクトを作成します。DocSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を docx ファイルとして保存します。変換プロセスを開始するには、EPUB ソースをファイルパスまたは入力ストリームとして、さらに Url、DocSaveOptions インスタンス、および任意の形態の出力データバッファを渡す必要があります。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表す configuration を使用できます。オンライン EPUB to DOCX コンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に DOCX ファイルに変換する無料のオンライン [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 既存のファイルをストリームとして読み取り用に開く
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// ICreateStreamProvider インターフェイスの実装を参照してください
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// デフォルトオプションのインスタンスを作成する
var options = new DocSaveOptions();   

// 変換プロセスを開始する
Converter.ConvertEPUB(inputStream, options, sp);
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

## ConvertEPUB(String, DocSaveOptions, ICreateStreamProvider) {#convertepub_40}

完全なファイルパスで指定された EPUB ソースを DOCX に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) 実装によって生成された出力データです。

```java
public static void ConvertEPUB(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | EPUB ソースファイルパスです。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |
| options | DocSaveOptions | 変換オプション。[`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/) 、[`margins`](../../../com.aspose.html.drawing/page/margin/) 、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | `[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)` インターフェイスの実装で、出力ストリームを取得するために使用されます。詳細なサンプルは [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers) を参照してください。 |

## 備考

EPUB を DOCX に変換する方法

DOCX は Microsoft Word 文書のよく知られたフォーマットです。このフォーマットは、幅広い書式設定機能をサポートし、あらゆる種類の文書を作成するためのさまざまなオプションをユーザーに提供するため、人気があります。DOCX ファイルは Word 2007 以降のバージョンで開くことができますが、DOC ファイル拡張子をサポートする旧バージョンの MS Word では開けません。EPUB から DOCX への変換は、特定のユーザータスクで DOCX フォーマットを活用するためにしばしば必要とされます。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめ、使いやすく快適にする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。EPUB Converter の DOCX 固有ガイドでは、次の記事が掲載されています。

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB を DOCX に変換する

EPUB を DOCX ファイル形式に変換するには、以下の手順に従ってください：

既存の EPUB ファイルを開きます。例として、ソースファイルパスを ConvertEPUB メソッドの最初のパラメータとして定義できます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスを使用するという、よりシンプルな代替手段も利用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定した新しい DocSaveOptions オブジェクトを作成します。DocSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を docx ファイルとして保存します。変換プロセスを開始するには、EPUB ソースをファイルパスまたは入力ストリームとして、さらに Url、DocSaveOptions インスタンス、および任意の形態の出力データバッファを渡す必要があります。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表す configuration を使用できます。オンライン EPUB to DOCX コンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に DOCX ファイルに変換する無料のオンライン [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

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
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// ICreateStreamProvider インターフェイスの実装を参照してください
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// デフォルトオプションのインスタンスを作成する
var options = new DocSaveOptions ();   

// 変換プロセスを開始する
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, DocSaveOptions, ICreateStreamProvider) {#convertepub_8}

URLで提供されるEPUBソースを変換します。結果はICreateStreamProviderインターフェイス実装によって生成された出力データです。

```java
public static void ConvertEPUB(Url sourceUrl, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | EPUB ソース URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)` の使用により、レンダリングプロセスを調整できます。ページサイズ、余白、解像度、CSS などを指定できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | `[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)` インターフェイスの実装で、出力ストリームを取得するために使用されます。詳細なサンプルは [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers) を参照してください。 |

## 備考

EPUB を DOCX に変換する方法

DOCX は Microsoft Word 文書のよく知られたフォーマットです。このフォーマットは、幅広い書式設定機能をサポートし、あらゆる種類の文書を作成するためのさまざまなオプションをユーザーに提供するため、人気があります。DOCX ファイルは Word 2007 以降のバージョンで開くことができますが、DOC ファイル拡張子をサポートする旧バージョンの MS Word では開けません。EPUB から DOCX への変換は、特定のユーザータスクで DOCX フォーマットを活用するためにしばしば必要とされます。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめ、使いやすく快適にする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。EPUB Converter の DOCX 固有ガイドでは、次の記事が掲載されています。

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB を DOCX に変換する

EPUB を DOCX ファイル形式に変換するには、以下の手順に従ってください：

既存の EPUB ファイルを開きます。例として、ソースファイルパスを ConvertEPUB メソッドの最初のパラメータとして定義できます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスを使用するという、よりシンプルな代替手段も利用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定した新しい DocSaveOptions オブジェクトを作成します。DocSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を docx ファイルとして保存します。変換プロセスを開始するには、EPUB ソースをファイルパスまたは入力ストリームとして、さらに Url、DocSaveOptions インスタンス、および任意の形態の出力データバッファを渡す必要があります。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表す configuration を使用できます。オンライン EPUB to DOCX コンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に DOCX ファイルに変換する無料のオンライン [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 入力ファイルパスからソース URL を作成します
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// ICreateStreamProvider インターフェイスの実装を参照してください
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// デフォルトオプションのインスタンスを作成する
var options = new DocSaveOptions ();   

// 変換プロセスを開始する
Converter.ConvertEPUB(sourceUrl, options, sp);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_16}

データ入力ストリームで提供されるEPUBソースを変換します。結果はICreateStreamProviderインターフェイス実装によって生成された出力データです。

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | 入力ストリームを変換元として使用します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)` の使用により、レンダリングプロセスを調整できます。[`page size`](...), [`margins`](...), [`resolutions`](...), [`CSS media-type`](...) などを指定できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | `[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)` インターフェイスの実装で、出力ストリームを取得するために使用されます。詳細なサンプルは [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers) を参照してください。 |

## 備考

EPUB を DOCX に変換する方法

DOCX は Microsoft Word 文書のよく知られたフォーマットです。このフォーマットは、幅広い書式設定機能をサポートし、あらゆる種類の文書を作成するためのさまざまなオプションをユーザーに提供するため、人気があります。DOCX ファイルは Word 2007 以降のバージョンで開くことができますが、DOC ファイル拡張子をサポートする旧バージョンの MS Word では開けません。EPUB から DOCX への変換は、特定のユーザータスクで DOCX フォーマットを活用するためにしばしば必要とされます。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめ、使いやすく快適にする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。EPUB Converter の DOCX 固有ガイドでは、次の記事が掲載されています。

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB を DOCX に変換する

EPUB を DOCX ファイル形式に変換するには、以下の手順に従ってください：

既存の EPUB ファイルを開きます。例として、ソースファイルパスを ConvertEPUB メソッドの最初のパラメータとして定義できます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスを使用するという、よりシンプルな代替手段も利用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定した新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。DocSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を docx ファイルとして保存します。変換プロセスを開始するには、EPUB ソースをファイルパスまたは入力ストリームとして、さらに Url、DocSaveOptions インスタンス、および任意の形態の出力データバッファを渡す必要があります。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表す configuration を使用できます。オンライン EPUB to DOCX コンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に DOCX ファイルに変換する無料のオンライン [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 既存のファイルをストリームとして読み取り用に開く
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// ICreateStreamProvider インターフェイスの実装を参照してください
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// デフォルトオプションのインスタンスを作成する
var options = new DocSaveOptions();   

// デフォルト設定で変換プロセスを開始する
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);





*InputFolder - user source file path.

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

## ConvertEPUB(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub_32}

完全なファイルパスで指定された EPUB ソースを DOCX に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | EPUB ソースファイルパスです。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | DocSaveOptions | 変換オプション。[`DocSaveOptions `](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/) 、[`margins`](../../../com.aspose.html.drawing/page/margin/) 、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | `[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)` インターフェイスの実装で、出力ストリームを取得するために使用されます。詳細なサンプルは [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers) を参照してください。 |

## 備考

EPUB を DOCX に変換する方法

DOCX は Microsoft Word 文書のよく知られたフォーマットです。このフォーマットは、幅広い書式設定機能をサポートし、あらゆる種類の文書を作成するためのさまざまなオプションをユーザーに提供するため、人気があります。DOCX ファイルは Word 2007 以降のバージョンで開くことができますが、DOC ファイル拡張子をサポートする旧バージョンの MS Word では開けません。EPUB から DOCX への変換は、特定のユーザータスクで DOCX フォーマットを活用するためにしばしば必要とされます。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめ、使いやすく快適にする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。EPUB Converter の DOCX 固有ガイドでは、次の記事が掲載されています。

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB を DOCX に変換する

EPUB を DOCX ファイル形式に変換するには、以下の手順に従ってください：

既存の EPUB ファイルを開きます。例として、ソースファイルパスを ConvertEPUB メソッドの最初のパラメータとして定義できます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスを使用するという、よりシンプルな代替手段も利用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定した新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。DocSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を docx ファイルとして保存します。変換プロセスを開始するには、EPUB ソースをファイルパスまたは入力ストリームとして、さらに Url、DocSaveOptions インスタンス、および任意の形態の出力データバッファを渡す必要があります。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表す configuration を使用できます。オンライン EPUB to DOCX コンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に DOCX ファイルに変換する無料のオンライン [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

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
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// ICreateStreamProvider インターフェイスの実装を参照してください
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// デフォルトオプションのインスタンスを作成する
var options = new DocSaveOptions ();   

// 変換プロセスを開始する
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);
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

## ConvertEPUB(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertepub}

URL で指定された EPUB ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | EPUB ソース URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成です。[configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) コンテキストオブジェクトを表し、アプリケーションの環境設定を構成するために使用されます。 |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)` の使用により、レンダリングプロセスを調整できます。[`page size`](...), [`margins`](...), [`resolutions`](...), [`CSS media-type`](...) などを指定できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | `[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/)` インターフェイスの実装で、出力ストリームを取得するために使用されます。詳細なサンプルは [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers) を参照してください。 |

## 備考

EPUB を DOCX に変換する方法

DOCX は Microsoft Word 文書のよく知られたフォーマットです。このフォーマットは、幅広い書式設定機能をサポートし、あらゆる種類の文書を作成するためのさまざまなオプションをユーザーに提供するため、人気があります。DOCX ファイルは Word 2007 以降のバージョンで開くことができますが、DOC ファイル拡張子をサポートする旧バージョンの MS Word では開けません。EPUB から DOCX への変換は、特定のユーザータスクで DOCX フォーマットを活用するためにしばしば必要とされます。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、すべての低レベル変換操作を単一のクラスにまとめ、使いやすく快適にする [`Converter`](../) クラスを使用してそれらを実行する方法について説明します。EPUB Converter の DOCX 固有ガイドでは、次の記事が掲載されています。

[Convert EPUB to DOCX ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [DOCX](https://docs.fileformat.com/word-processing/docx/) document using ConvertEPUB() methods of the Converter class and how to apply [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB を DOCX に変換する

EPUB を DOCX ファイル形式に変換するには、以下の手順に従ってください：

既存の EPUB ファイルを開きます。例として、ソースファイルパスを ConvertEPUB メソッドの最初のパラメータとして定義できます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスを使用するという、よりシンプルな代替手段も利用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定した新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。DocSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を docx ファイルとして保存します。変換プロセスを開始するには、EPUB ソースをファイルパスまたは入力ストリームとして、さらに Url、DocSaveOptions インスタンス、および任意の形態の出力データバッファを渡す必要があります。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表す configuration を使用できます。オンライン EPUB to DOCX コンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に DOCX ファイルに変換する無料のオンライン [EPUB to DOC](https://products.aspose.app/html/en/conversion/epub-to-docx)[X](https://products.aspose.app/html/en/conversion/epub-to-xps) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

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
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// ICreateStreamProvider インターフェイスの実装を参照してください
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.docx"));  

// デフォルトオプションのインスタンスを作成する
var options = new DocSaveOptions();   

// デフォルト設定で変換プロセスを開始する
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);





*InputFolder - user source file path.



```

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

## ConvertEPUB(Stream, PdfSaveOptions, String) {#convertepub_29}

データ入力ストリームで提供された EPUB ソースを変換します。結果は出力ファイルパスによって生成された pdf ファイルです。

```java
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | 入力パラメータとして EPUB ソースファイルパスを指定します。 |
| options | PdfSaveOptions | 変換オプション。[`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](...), [`margins`](...), [`CSS media-type`](...) などを指定できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な .pdf ファイルパス。 |

## 備考

EPUB を PDF に変換する方法

EPUB は、標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。International Digital Publishing Forum（[IDPF](http://idpf.org/)）によって作成され、現在では多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。EPUB から PDF への変換は、PDF フォーマットを活用するためにしばしば必要とされます。PDF ファイル形式は、テキスト、画像、ハイパーリンク、フォームフィールド、リッチメディア、メタデータなどの情報を完全に格納できる能力を持っています。PDF ファイルは Adobe Acrobat Reader/Writer や Chrome、Safari、Firefox などの最新ブラウザで開くことができます。印刷に最適化されており、文書の紙媒体作成に理想的です。また、PDF のセキュリティ設定を構成することも可能です。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、それらを単一のクラスにすべての低レベル変換操作をまとめた [`Converter`](../) クラスを使用して快適かつ簡単に実行する方法についての情報を提供します。EPUB コンバータ PDF の特定ガイドでは、以下の記事が見つかります:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB を PDF に変換

EPUB を PDF ファイル形式に変換するには、いくつかの手順に従う必要があります:

既存の EPUB ファイルを開きます。例として、ConvertEPUB メソッドの最初のパラメータとしてソースファイルパスを定義できます。代替手段として、入力ストリームまたは Url オブジェクト インスタンスを使用することもできます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスを使用する、よりシンプルな代替手段も利用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定した新しい PdfSaveOptions オブジェクトを作成します。PdfSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を PDF ファイルとして保存します。変換プロセスを開始するために、EPUB のソースデータをファイルパスまたは入力ストリームとして、さらに Url、PdfSaveOptions インスタンス、および任意の形式の出力データバッファを渡す必要があります。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表す構成を使用できます。オンライン EPUB から PDF へのコンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に PDF ファイルへ変換する無料のオンライン [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 既存のファイルをストリームとして読み取り用に開く
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// 結果ファイルパスを設定  
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// デフォルトオプションのインスタンスを作成する
var options = new PdfSaveOptions();   

// 変換プロセスを開始する
Converter.ConvertEPUB(inputStream, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, PdfSaveOptions, String) {#convertepub_45}

フルファイルパスで提供されるEPUBソースをPDFに変換します。結果は出力ファイルパスで生成されたpdfファイルです。

```java
public static void ConvertEPUB(String sourcePath, PdfSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | EPUB ソースファイルパスです。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |
| options | PdfSaveOptions | 変換オプション。[`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](...), [`margins`](...), [`CSS media-type`](...) などを指定できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な .pdf ファイルパス。 |

## 備考

EPUB を PDF に変換する方法

EPUB は、標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。International Digital Publishing Forum（[IDPF](http://idpf.org/)）によって作成され、現在では多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。EPUB から PDF への変換は、PDF フォーマットを活用するためにしばしば必要とされます。PDF ファイル形式は、テキスト、画像、ハイパーリンク、フォームフィールド、リッチメディア、メタデータなどの情報を完全に格納できる能力を持っています。PDF ファイルは Adobe Acrobat Reader/Writer や Chrome、Safari、Firefox などの最新ブラウザで開くことができます。印刷に最適化されており、文書の紙媒体作成に理想的です。また、PDF のセキュリティ設定を構成することも可能です。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、それらを単一のクラスにすべての低レベル変換操作をまとめた [`Converter`](../) クラスを使用して快適かつ簡単に実行する方法についての情報を提供します。EPUB コンバータ PDF の特定ガイドでは、以下の記事が見つかります:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB を PDF に変換

EPUB を PDF ファイル形式に変換するには、いくつかの手順に従う必要があります:

既存の EPUB ファイルを開きます。例として、ConvertEPUB メソッドの最初のパラメータとしてソースファイルパスを定義できます。代替手段として、入力ストリームまたは Url オブジェクト インスタンスを使用することもできます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスを使用する、よりシンプルな代替手段も利用できます。新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成し、ページサイズ、余白、CSS などの好みのパラメータを多数指定します。PdfSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を PDF ファイルとして保存します。変換プロセスを開始するために、EPUB のソースデータをファイルパスまたは入力ストリームとして、さらに Url、PdfSaveOptions インスタンス、および任意の形式の出力データバッファを渡す必要があります。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表す構成を使用できます。オンライン EPUB から PDF へのコンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に PDF ファイルへ変換する無料のオンライン [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// フォームのソースファイルパス
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// 出力結果ファイルパスを作成する
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// デフォルトオプションのインスタンスを定義する
var options = new PdfSaveOptions();

// 変換プロセスを開始する
Converter.ConvertEPUB(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, PdfSaveOptions, String) {#convertepub_13}

URLで提供されるEPUBソースを変換します。結果は出力ファイルパスで生成されたpdfファイルです。

```java
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | EPUB ソース URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) の使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な .pdf ファイルパス。 |

## 備考

EPUB を PDF に変換する方法

EPUB は、標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。International Digital Publishing Forum（[IDPF](http://idpf.org/)）によって作成され、現在では多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。EPUB から PDF への変換は、PDF フォーマットを活用するためにしばしば必要とされます。PDF ファイル形式は、テキスト、画像、ハイパーリンク、フォームフィールド、リッチメディア、メタデータなどの情報を完全に格納できる能力を持っています。PDF ファイルは Adobe Acrobat Reader/Writer や Chrome、Safari、Firefox などの最新ブラウザで開くことができます。印刷に最適化されており、文書の紙媒体作成に理想的です。また、PDF のセキュリティ設定を構成することも可能です。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、それらを単一のクラスにすべての低レベル変換操作をまとめた [`Converter`](../) クラスを使用して快適かつ簡単に実行する方法についての情報を提供します。EPUB コンバータ PDF の特定ガイドでは、以下の記事が見つかります:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB を PDF に変換

EPUB を PDF ファイル形式に変換するには、いくつかの手順に従う必要があります:

既存の EPUB ファイルを開きます。例として、ConvertEPUB メソッドの最初のパラメータとしてソースファイルパスを定義できます。代替手段として、入力ストリームまたは Url オブジェクト インスタンスを使用することもできます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスを使用する、よりシンプルな代替手段も利用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定した新しい PdfSaveOptions オブジェクトを作成します。PdfSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を PDF ファイルとして保存します。変換プロセスを開始するために、EPUB のソースデータをファイルパスまたは入力ストリームとして、さらに Url、PdfSaveOptions インスタンス、および任意の形式の出力データバッファを渡す必要があります。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表す構成を使用できます。オンライン EPUB から PDF へのコンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に PDF ファイルへ変換する無料のオンライン [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import com.aspose.html.saving;  
import com.aspose.html.converters; 

// 入力ファイルパスに基づいて Url を作成する
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// 出力結果ファイルパスを作成する
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// デフォルトオプションのインスタンスを定義する
var options = new com.aspose.html.saving.PdfSaveOptions();

// 変換プロセスを開始する
Converter.ConvertEPUB(sourceUrl, options, resultPath);
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

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, String) {#convertepub_21}

データ入力ストリームで提供された EPUB ソースを変換します。結果は出力ファイルパスによって生成された pdf ファイルです。

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | 入力ストリームを変換元として使用します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | PdfSaveOptions | 変換オプション。[`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](...), [`margins`](...), [`CSS media-type`](...) などを指定できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な .pdf ファイルパス。 |

## 備考

EPUB を PDF に変換する方法

EPUB は、標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。International Digital Publishing Forum（[IDPF](http://idpf.org/)）によって作成され、現在では多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。EPUB から PDF への変換は、PDF フォーマットを活用するためにしばしば必要とされます。PDF ファイル形式は、テキスト、画像、ハイパーリンク、フォームフィールド、リッチメディア、メタデータなどの情報を完全に格納できる能力を持っています。PDF ファイルは Adobe Acrobat Reader/Writer や Chrome、Safari、Firefox などの最新ブラウザで開くことができます。印刷に最適化されており、文書の紙媒体作成に理想的です。また、PDF のセキュリティ設定を構成することも可能です。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、それらを単一のクラスにすべての低レベル変換操作をまとめた [`Converter`](../) クラスを使用して快適かつ簡単に実行する方法についての情報を提供します。EPUB コンバータ PDF の特定ガイドでは、以下の記事が見つかります:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB を PDF に変換

EPUB を PDF ファイル形式に変換するには、いくつかの手順に従う必要があります:

既存の EPUB ファイルを開きます。例として、ConvertEPUB メソッドの最初のパラメータとしてソースファイルパスを定義できます。代替手段として、入力ストリームまたは Url オブジェクト インスタンスを使用することもできます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスを使用する、よりシンプルな代替手段も利用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定した新しい PdfSaveOptions オブジェクトを作成します。PdfSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を PDF ファイルとして保存します。変換プロセスを開始するために、EPUB のソースデータをファイルパスまたは入力ストリームとして、さらに Url、PdfSaveOptions インスタンス、および任意の形式の出力データバッファを渡す必要があります。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表す構成を使用できます。オンライン EPUB から PDF へのコンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に PDF ファイルへ変換する無料のオンライン [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 既存のファイルをストリームとして読み取り用に開く
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// 結果ファイルパスを設定  
var resultPath = Path.Combine(OutputFolder, "sample.pdf"));  

// デフォルトオプションのインスタンスを作成する
var options = new PdfSaveOptions();   

// デフォルト設定で変換プロセスを開始する
Converter.ConvertEPUB(inputStream, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(String, Configuration, PdfSaveOptions, String) {#convertepub_37}

データ入力ストリームで提供された EPUB ソースを変換します。結果は出力ファイルパスによって生成された pdf ファイルです。

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | EPUB ソースファイルパスです。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | PdfSaveOptions | 変換オプション。[`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](...), [`margins`](...), [`CSS media-type`](...) などを指定できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な .pdf ファイルパス。 |

## 備考

EPUB を PDF に変換する方法

EPUB は、標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。International Digital Publishing Forum（[IDPF](http://idpf.org/)）によって作成され、現在では多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。EPUB から PDF への変換は、PDF フォーマットを活用するためにしばしば必要とされます。PDF ファイル形式は、テキスト、画像、ハイパーリンク、フォームフィールド、リッチメディア、メタデータなどの情報を完全に格納できる能力を持っています。PDF ファイルは Adobe Acrobat Reader/Writer や Chrome、Safari、Firefox などの最新ブラウザで開くことができます。印刷に最適化されており、文書の紙媒体作成に理想的です。また、PDF のセキュリティ設定を構成することも可能です。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、それらを単一のクラスにすべての低レベル変換操作をまとめた [`Converter`](../) クラスを使用して快適かつ簡単に実行する方法についての情報を提供します。EPUB コンバータ PDF の特定ガイドでは、以下の記事が見つかります:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB を PDF に変換

EPUB を PDF ファイル形式に変換するには、いくつかの手順に従う必要があります:

既存の EPUB ファイルを開きます。例として、ConvertEPUB メソッドの最初のパラメータとしてソースファイルパスを定義できます。代替手段として、入力ストリームまたは Url オブジェクト インスタンスを使用することもできます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスを使用する、よりシンプルな代替手段も利用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定した新しい PdfSaveOptions オブジェクトを作成します。PdfSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を PDF ファイルとして保存します。変換プロセスを開始するために、EPUB のソースデータをファイルパスまたは入力ストリームとして、さらに Url、PdfSaveOptions インスタンス、および任意の形式の出力データバッファを渡す必要があります。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表す構成を使用できます。オンライン EPUB から PDF へのコンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に PDF ファイルへ変換する無料のオンライン [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// フォームのソースファイルパス
var sourcePath = Path.Combine(InputFolder, "sample.epub");

// 出力結果ファイルパスを作成する
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// デフォルトオプションのインスタンスを定義する
var options = new PdfSaveOptions();

// デフォルト構成で変換プロセスを開始する
Converter.ConvertEPUB(sourcePath, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Url, Configuration, PdfSaveOptions, String) {#convertepub_5}

URLで提供されるEPUBソースを変換します。結果は出力ファイルパスで生成されたpdfファイルです。

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | EPUB ソース URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成です。[configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) コンテキストオブジェクトを表し、アプリケーションの環境設定を構成するために使用されます。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) の使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な .pdf ファイルパス。 |

## 備考

EPUB を PDF に変換する方法

EPUB は、標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。International Digital Publishing Forum（[IDPF](http://idpf.org/)）によって作成され、現在では多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。EPUB から PDF への変換は、PDF フォーマットを活用するためにしばしば必要とされます。PDF ファイル形式は、テキスト、画像、ハイパーリンク、フォームフィールド、リッチメディア、メタデータなどの情報を完全に格納できる能力を持っています。PDF ファイルは Adobe Acrobat Reader/Writer や Chrome、Safari、Firefox などの最新ブラウザで開くことができます。印刷に最適化されており、文書の紙媒体作成に理想的です。また、PDF のセキュリティ設定を構成することも可能です。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、それらを単一のクラスにすべての低レベル変換操作をまとめた [`Converter`](../) クラスを使用して快適かつ簡単に実行する方法についての情報を提供します。EPUB コンバータ PDF の特定ガイドでは、以下の記事が見つかります:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB を PDF に変換

EPUB を PDF ファイル形式に変換するには、いくつかの手順に従う必要があります:

既存の EPUB ファイルを開きます。例として、ConvertEPUB メソッドの最初のパラメータとしてソースファイルパスを定義できます。代替手段として、入力ストリームまたは Url オブジェクト インスタンスを使用することもできます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスを使用する、よりシンプルな代替手段も利用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定した新しい PdfSaveOptions オブジェクトを作成します。PdfSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を PDF ファイルとして保存します。変換プロセスを開始するために、EPUB のソースデータをファイルパスまたは入力ストリームとして、さらに Url、PdfSaveOptions インスタンス、および任意の形式の出力データバッファを渡す必要があります。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表す構成を使用できます。オンライン EPUB から PDF へのコンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に PDF ファイルへ変換する無料のオンライン [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

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
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// 出力結果ファイルパスを作成する
var resultPath = Path.Combine(OutputFolder, "sample.pdf");

// デフォルトオプションのインスタンスを定義する
var options = new PdfSaveOptions();

// デフォルト構成で変換プロセスを開始する
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.



```

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertEPUB(Stream, PdfSaveOptions, ICreateStreamProvider) {#convertepub_28}

データ入力ストリームで提供される EPUB ソースを変換します。結果は、[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertEPUB(Stream stream, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | 入力ストリームを変換元として使用します。 |
| options | PdfSaveOptions | 変換オプション。[`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](...), [`margins`](...), [`CSS media-type`](...) などを指定できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装。 |

## 備考

EPUB を PDF に変換する方法

EPUB は、標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。International Digital Publishing Forum（[IDPF](http://idpf.org/)）によって作成され、現在では多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。EPUB から PDF への変換は、PDF フォーマットを活用するためにしばしば必要とされます。PDF ファイル形式は、テキスト、画像、ハイパーリンク、フォームフィールド、リッチメディア、メタデータなどの情報を完全に格納できる能力を持っています。PDF ファイルは Adobe Acrobat Reader/Writer や Chrome、Safari、Firefox などの最新ブラウザで開くことができます。印刷に最適化されており、文書の紙媒体作成に理想的です。また、PDF のセキュリティ設定を構成することも可能です。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、それらを単一のクラスにすべての低レベル変換操作をまとめた [`Converter`](../) クラスを使用して快適かつ簡単に実行する方法についての情報を提供します。EPUB コンバータ PDF の特定ガイドでは、以下の記事が見つかります:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB を PDF に変換

EPUB を PDF ファイル形式に変換するには、いくつかの手順に従う必要があります:

既存の EPUB ファイルを開きます。例として、ConvertEPUB メソッドの最初のパラメータとしてソースファイルパスを定義できます。代替手段として、入力ストリームまたは Url オブジェクト インスタンスを使用することもできます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスを使用する、よりシンプルな代替手段も利用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定した新しい PdfSaveOptions オブジェクトを作成します。PdfSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を PDF ファイルとして保存します。変換プロセスを開始するために、EPUB のソースデータをファイルパスまたは入力ストリームとして、さらに Url、PdfSaveOptions インスタンス、および任意の形式の出力データバッファを渡す必要があります。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表す構成を使用できます。オンライン EPUB から PDF へのコンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に PDF ファイルへ変換する無料のオンライン [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 既存のファイルをストリームとして読み取り用に開く
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// ICreateStreamProvider インターフェイスの実装を参照してください
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// デフォルトオプションのインスタンスを作成する
var options = new PdfSaveOptions ();   

// 変換プロセスを開始する
Converter.ConvertEPUB(inputStream, options, sp);
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

## ConvertEPUB(String, PdfSaveOptions, ICreateStreamProvider) {#convertepub_44}

完全なファイルパスで提供される EPUB ソースを PDF に変換します。結果は、[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertEPUB(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | EPUB ソースファイルパスです。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |
| options | PdfSaveOptions | 変換オプション。[`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](...), [`margins`](...), [`CSS media-type`](...) などを指定できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイスの実装です。詳細なサンプルは [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers) を参照してください。 |

## 備考

EPUB を PDF に変換する方法

EPUB は、標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。International Digital Publishing Forum（[IDPF](http://idpf.org/)）によって作成され、現在では多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。EPUB から PDF への変換は、PDF フォーマットを活用するためにしばしば必要とされます。PDF ファイル形式は、テキスト、画像、ハイパーリンク、フォームフィールド、リッチメディア、メタデータなどの情報を完全に格納できる能力を持っています。PDF ファイルは Adobe Acrobat Reader/Writer や Chrome、Safari、Firefox などの最新ブラウザで開くことができます。印刷に最適化されており、文書の紙媒体作成に理想的です。また、PDF のセキュリティ設定を構成することも可能です。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、それらを単一のクラスにすべての低レベル変換操作をまとめた [`Converter`](../) クラスを使用して快適かつ簡単に実行する方法についての情報を提供します。EPUB コンバータ PDF の特定ガイドでは、以下の記事が見つかります:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB を PDF に変換

EPUB を PDF ファイル形式に変換するには、いくつかの手順に従う必要があります:

既存の EPUB ファイルを開きます。例として、ConvertEPUB メソッドの最初のパラメータとしてソースファイルパスを定義できます。代替手段として、入力ストリームまたは Url オブジェクト インスタンスを使用することもできます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスを使用する、よりシンプルな代替手段も利用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定した新しい PdfSaveOptions オブジェクトを作成します。PdfSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を PDF ファイルとして保存します。変換プロセスを開始するために、EPUB のソースデータをファイルパスまたは入力ストリームとして、さらに Url、PdfSaveOptions インスタンス、および任意の形式の出力データバッファを渡す必要があります。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表す構成を使用できます。オンライン EPUB から PDF へのコンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に PDF ファイルへ変換する無料のオンライン [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

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
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// ICreateStreamProvider インターフェイスの実装を参照してください
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// デフォルトオプションのインスタンスを作成する
var options = new PdfSaveOptions();   

// 変換プロセスを開始する
Converter.ConvertEPUB(sourcePath, options, sp);
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

## ConvertEPUB(Url, PdfSaveOptions, ICreateStreamProvider) {#convertepub_12}

URL で指定された EPUB ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertEPUB(Url sourceUrl, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | EPUB ソース URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) の使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider) インターフェイスの実装です。詳細なサンプルは [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers) を参照してください。 |

## 備考

EPUB を PDF に変換する方法

EPUB は、標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。International Digital Publishing Forum（[IDPF](http://idpf.org/)）によって作成され、現在では多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。EPUB から PDF への変換は、PDF フォーマットを活用するためにしばしば必要とされます。PDF ファイル形式は、テキスト、画像、ハイパーリンク、フォームフィールド、リッチメディア、メタデータなどの情報を完全に格納できる能力を持っています。PDF ファイルは Adobe Acrobat Reader/Writer や Chrome、Safari、Firefox などの最新ブラウザで開くことができます。印刷に最適化されており、文書の紙媒体作成に理想的です。また、PDF のセキュリティ設定を構成することも可能です。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、それらを単一のクラスにすべての低レベル変換操作をまとめた [`Converter`](../) クラスを使用して快適かつ簡単に実行する方法についての情報を提供します。EPUB コンバータ PDF の特定ガイドでは、以下の記事が見つかります:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB を PDF に変換

EPUB を PDF ファイル形式に変換するには、いくつかの手順に従う必要があります:

既存の EPUB ファイルを開きます。例として、ConvertEPUB メソッドの最初のパラメータとしてソースファイルパスを定義できます。代替手段として、入力ストリームまたは Url オブジェクト インスタンスを使用することもできます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスを使用する、よりシンプルな代替手段も利用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定した新しい PdfSaveOptions オブジェクトを作成します。PdfSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を PDF ファイルとして保存します。変換プロセスを開始するために、EPUB のソースデータをファイルパスまたは入力ストリームとして、さらに Url、PdfSaveOptions インスタンス、および任意の形式の出力データバッファを渡す必要があります。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表す構成を使用できます。オンライン EPUB から PDF へのコンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に PDF ファイルへ変換する無料のオンライン [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

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
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// ICreateStreamProvider インターフェイスの実装を参照してください
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// デフォルトオプションのインスタンスを定義する
var options = new PdfSaveOptions();

// 変換プロセスを開始する
Converter.ConvertEPUB(sourceUrl, options, sp);





*InputFolder - user source file path.

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

## ConvertEPUB(Stream, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_20}

データ入力ストリームで提供される EPUB ソースを変換します。結果は、[`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertEPUB(Stream stream, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | 入力ストリームを変換元として使用します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | PdfSaveOptions | 変換オプション。[`PdfSaveOption`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](...), [`margins`](...), [`CSS media-type`](...) などを指定できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイスの実装です。詳細なサンプルは [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers) を参照してください。 |

## 備考

EPUB を PDF に変換する方法

EPUB は、標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。International Digital Publishing Forum（[IDPF](http://idpf.org/)）によって作成され、現在では多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。EPUB から PDF への変換は、PDF フォーマットを活用するためにしばしば必要とされます。PDF ファイル形式は、テキスト、画像、ハイパーリンク、フォームフィールド、リッチメディア、メタデータなどの情報を完全に格納できる能力を持っています。PDF ファイルは Adobe Acrobat Reader/Writer や Chrome、Safari、Firefox などの最新ブラウザで開くことができます。印刷に最適化されており、文書の紙媒体作成に理想的です。また、PDF のセキュリティ設定を構成することも可能です。

Aspose.HTML の主なハイライトは変換機能です。EPUB はデジタル書籍や出版物向けのオープンな XML ベース形式で、スマートフォン、タブレット、コンピュータで閲覧・読書が可能です。[`com.aspose.html.converters`](../) パッケージは変換メソッドへの簡単なアクセスを実装しています。[EPUB](https://docs.fileformat.com/ebook/epub/) から人気のあるフォーマットへの幅広い変換を提供し、例えば [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などがあります。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、それらを単一のクラスにすべての低レベル変換操作をまとめた [`Converter`](../) クラスを使用して快適かつ簡単に実行する方法についての情報を提供します。EPUB コンバータ PDF の特定ガイドでは、以下の記事が見つかります:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB を PDF に変換

EPUB を PDF ファイル形式に変換するには、いくつかの手順に従う必要があります:

既存の EPUB ファイルを開きます。例として、ConvertEPUB メソッドの最初のパラメータとしてソースファイルパスを定義できます。代替手段として、入力ストリームまたは Url オブジェクト インスタンスを使用することもできます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスを使用する、よりシンプルな代替手段も利用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定した新しい PdfSaveOptions オブジェクトを作成します。PdfSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を PDF ファイルとして保存します。変換プロセスを開始するために、EPUB のソースデータをファイルパスまたは入力ストリームとして、さらに Url、PdfSaveOptions インスタンス、および任意の形式の出力データバッファを渡す必要があります。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表す構成を使用できます。オンライン EPUB から PDF へのコンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に PDF ファイルへ変換する無料のオンライン [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO; 
import com.aspose.html.io; 
import com.aspose.html.saving; 
import com.aspose.html.converters; 
...  
// 既存のファイルをストリームとして読み取り用に開く
var inputStream = File.OpenRead(Path.Combine(InputFolder, "sample.epub"));  

// ICreateStreamProvider インターフェイスの実装を参照してください
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// デフォルトオプションのインスタンスを作成する
var options = new PdfSaveOptions ();   

// デフォルト構成オブジェクトで変換プロセスを開始  
Converter.ConvertEPUB(inputStream, new Configuration(), options, sp);
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

## ConvertEPUB(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_36}

フルファイルパスで提供されるEPUBソースをPDFに変換します。結果はICreateStreamProviderインターフェイス実装によって生成された出力データです。

```java
public static void ConvertEPUB(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | EPUB ソースファイルパスです。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |
| configuration | Configuration | 環境構成です。[configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) コンテキストオブジェクトを表し、アプリケーションの環境設定を構成するために使用されます。 |
| options | PdfSaveOptions | 変換オプション。[PdfSaveOption](https://apireference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions) オブジェクトの使用により、レンダリングプロセスを調整できます。ページサイズ、余白、CSS などを指定できます。[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider) インターフェイスの実装です。詳細なサンプルは [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers) を参照してください。 |

## 備考

EPUB を PDF に変換する方法

EPUB は、標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。International Digital Publishing Forum（[IDPF](http://idpf.org/)）によって作成され、現在では多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。EPUB から PDF への変換は、PDF フォーマットを活用するためにしばしば必要とされます。PDF ファイル形式は、テキスト、画像、ハイパーリンク、フォームフィールド、リッチメディア、メタデータなどの情報を完全に格納できる能力を持っています。PDF ファイルは Adobe Acrobat Reader/Writer や Chrome、Safari、Firefox などの最新ブラウザで開くことができます。印刷に最適化されており、文書の紙媒体作成に理想的です。また、PDF のセキュリティ設定を構成することも可能です。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、それらを単一のクラスにすべての低レベル変換操作をまとめた [`Converter`](../) クラスを使用して快適かつ簡単に実行する方法についての情報を提供します。EPUB コンバータ PDF の特定ガイドでは、以下の記事が見つかります:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB を PDF に変換

EPUB を PDF ファイル形式に変換するには、いくつかの手順に従う必要があります:

既存の EPUB ファイルを開きます。例として、ConvertEPUB メソッドの最初のパラメータとしてソースファイルパスを定義できます。代替手段として、入力ストリームまたは Url オブジェクト インスタンスを使用することもできます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスを使用する、よりシンプルな代替手段も利用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定した新しい PdfSaveOptions オブジェクトを作成します。PdfSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を PDF ファイルとして保存します。変換プロセスを開始するために、EPUB のソースデータをファイルパスまたは入力ストリームとして、さらに Url、PdfSaveOptions インスタンス、および任意の形式の出力データバッファを渡す必要があります。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表す構成を使用できます。オンライン EPUB から PDF へのコンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に PDF ファイルへ変換する無料のオンライン [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

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
var sourcePath = Path.Combine(InputFolder, "sample.epub");  

// ICreateStreamProvider インターフェイスの実装を参照してください
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));  

// デフォルトオプションのインスタンスを作成する
var options = new PdfSaveOptions();   

// デフォルト構成オブジェクトで変換プロセスを開始 
Converter.ConvertEPUB(sourcePath, new Configuration(), options, sp);





*InputFolder - user source file path.

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

## ConvertEPUB(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertepub_4}

URL で指定された EPUB ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertEPUB(Url sourceUrl, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceUrl | Url | EPUB ソース URL - ユニバーサル識別子 (URL) のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成です。[configuration](https://apireference.aspose.com/html/net/aspose.html/configuration) コンテキストオブジェクトを表し、アプリケーションの環境設定を構成するために使用されます。 |
| options | PdfSaveOptions | [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) の使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`file permissions`](../../../com.aspose.html.rendering.pdf.encryption/pdfencryptioninfo/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/) などを指定できます。[Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [ICreateStreamProvider](https://apireference.aspose.com/svg/net/aspose.svg.io/icreatestreamprovider) インターフェイスの実装です。詳細なサンプルは [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers) を参照してください。 |

## 備考

EPUB を PDF に変換する方法

EPUB は、標準的なデジタル出版フォーマットを提供する電子書籍ファイル形式です。International Digital Publishing Forum（[IDPF](http://idpf.org/)）によって作成され、現在では多くの電子書籍リーダーやソフトウェアアプリケーションでサポートされています。EPUB から PDF への変換は、PDF フォーマットを活用するためにしばしば必要とされます。PDF ファイル形式は、テキスト、画像、ハイパーリンク、フォームフィールド、リッチメディア、メタデータなどの情報を完全に格納できる能力を持っています。PDF ファイルは Adobe Acrobat Reader/Writer や Chrome、Safari、Firefox などの最新ブラウザで開くことができます。印刷に最適化されており、文書の紙媒体作成に理想的です。また、PDF のセキュリティ設定を構成することも可能です。

Aspose.HTML の主なハイライトは変換機能です。EPUB は、スマートフォン、タブレット、コンピュータで閲覧・読書できるデジタル書籍および出版物向けのオープン XML ベース形式です。com.aspose.html.converters パッケージは、変換メソッドへの簡単なアクセスを実装しています。これにより、[EPUB](https://docs.fileformat.com/ebook/epub/) を [PDF](https://docs.fileformat.com/pdf/)、[XPS](https://docs.fileformat.com/page-description-language/xps/)、[DOCX](https://docs.fileformat.com/word-processing/docx/)、[JPEG](https://docs.fileformat.com/image/jpeg/)、[PNG](https://docs.fileformat.com/image/png/)、[BMP](https://docs.fileformat.com/image/bmp/)、[TIFF](https://docs.fileformat.com/image/tiff/)、[GIF](https://docs.fileformat.com/image/gif/) などの一般的な形式に変換する幅広い機能を提供します。

このセクションでは、サポートされている EPUB 変換シナリオの一覧と、それらを単一のクラスにすべての低レベル変換操作をまとめた [`Converter`](../) クラスを使用して快適かつ簡単に実行する方法についての情報を提供します。EPUB コンバータ PDF の特定ガイドでは、以下の記事が見つかります:

[Convert EPUB to PDF ](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) - You learn how to convert an [EPUB](https://docs.fileformat.com/ebook/epub/) to [PDF](https://docs.fileformat.com/pdf/) document using ConvertEPUB() methods of the Converter class and how to apply [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) and [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) parameters.

EPUB を PDF に変換

EPUB を PDF ファイル形式に変換するには、いくつかの手順に従う必要があります:

既存の EPUB ファイルを開きます。例として、ConvertEPUB メソッドの最初のパラメータとしてソースファイルパスを定義できます。代替手段として、入力ストリームまたは Url オブジェクト インスタンスを使用することもできます。既知またはカスタムの ICreateStreamProvider インターフェイス実装を出力データバッファとして使用します。結果の出力ファイルパスを使用する、よりシンプルな代替手段も利用できます。ページサイズ、余白、CSS などの好みのパラメータを多数指定した新しい PdfSaveOptions オブジェクトを作成します。PdfSaveOptions クラスのデフォルトインスタンスを使用することも可能です。静的 Converter クラスの ConvertEPUB() メソッドを使用して EPUB を PDF ファイルとして保存します。変換プロセスを開始するために、EPUB のソースデータをファイルパスまたは入力ストリームとして、さらに Url、PdfSaveOptions インスタンス、および任意の形式の出力データバッファを渡す必要があります。アプリケーションの環境設定を構成するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表す構成を使用できます。オンライン EPUB から PDF へのコンバータ

Aspose.HTML は、EPUB を高品質かつ簡単・高速に PDF ファイルへ変換する無料のオンライン [EPUB to PDF](https://products.aspose.app/html/en/conversion/epub-to-pdf) コンバータを提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## サンプル

```java
import System.IO;  
import com.aspose.html.saving;  
import com.aspose.html.converters; 
...
// 入力ファイルパスに基づいて Url を作成する
var sourceUrl = new Url(Path.Combine(InputFolder, "sample.epub"));

// ICreateStreamProvider インターフェイスの実装を参照してください
var sp = new FileCreateStreamProvider(Path.Combine(OutputFolder, "sample.pdf"));

// デフォルトオプションのインスタンスを定義する
var options = new PdfSaveOptions();

// デフォルトの構成オブジェクトで変換プロセスを開始する
Converter.ConvertEPUB(sourceUrl, new Configuration(), options, sp);
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
