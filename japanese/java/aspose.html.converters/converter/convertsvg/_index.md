---
title: "Converter.ConvertSVG"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Converter メソッド。SVGDocument で提示された SVG ソースを変換します。結果は ICreateStreamProvider インターフェイス実装によって生成された出力データです"
type: docs

url: /ja/java/com.aspose.html.converters/converter/convertsvg/
---
## ConvertSVG(SVGDocument, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_6}

[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) で提示された SVG ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertSVG(SVGDocument document, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| document | SVGDocument | [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) で提示された変換ソースです。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

SVG を XPS に変換する

Converter クラスは、SVG を XPS に変換する複数の専用変換を提供します。SVG を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります：

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義することも、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。また、オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加できます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を XPS 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に XPS に変換する無料のオンライン [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの XpsSaveOptions オブジェクトを定義する
      var options = new XpsSaveOptions();

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // SVG ドキュメントを変換ソースとして形成する
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
			// デフォルト構成で変換プロセスを開始する
			Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_22}

[`URL`](../../../com.aspose.html/url/) で提示された SVG ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | SVG ソースドキュメント [`URL`](../../../com.aspose.html/url/) - ユニバーサル識別子（URL）のオブジェクト表現を提供します。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

SVG を XPS に変換する

Converter クラスは、SVG を XPS に変換する複数の専用変換を提供します。SVG を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります：

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義することも、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。また、オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加できます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を XPS 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に XPS に変換する無料のオンライン [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // フォームのソースファイルパス
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの XpsSaveOptions オブジェクトを定義する
      var options = new XpsSaveOptions();

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 変換プロセスを開始する
      Converter.ConvertSVG(sourceUrl, options, sp);
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

## ConvertSVG(Url, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_14}

[`URL`](../../../com.aspose.html/url/) で提示された SVG ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | SVG ソースドキュメント [`URL`](../../../com.aspose.html/url/) - ユニバーサル識別子（URL）のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

SVG を XPS に変換する

Converter クラスは、SVG を XPS に変換する複数の専用変換を提供します。SVG を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります：

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義することも、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。また、オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加できます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を XPS 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に XPS に変換する無料のオンライン [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // フォームのソースファイルパス
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの XpsSaveOptions オブジェクトを定義する
      var options = new XpsSaveOptions();

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

## ConvertSVG(String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_38}

完全なファイルパスで提示された SVG ソースを XPS に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | SVG ソースの完全なファイルパスです。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

SVG を XPS に変換する

Converter クラスは、SVG を XPS に変換する複数の専用変換を提供します。SVG を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります：

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義することも、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。また、オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加できます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を XPS 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に XPS に変換する無料のオンライン [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの XpsSaveOptions オブジェクトを定義する
      var options = new XpsSaveOptions();

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 変換プロセスを開始する
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_30}

完全なファイルパスで提示された SVG ソースを XPS に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | SVG ソースの完全なファイルパスです。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

SVG を XPS に変換する

Converter クラスは、SVG を XPS に変換する複数の専用変換を提供します。SVG を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります：

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義することも、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。また、オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加できます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を XPS 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に XPS に変換する無料のオンライン [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの XpsSaveOptions オブジェクトを定義する
      var options = new XpsSaveOptions();

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_54}

インラインコンテンツで提供された SVG ソースを XPS に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | 文字列としてインライン SVG コンテンツ。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

SVG を XPS に変換する

Converter クラスは、SVG を XPS に変換する複数の専用変換を提供します。SVG を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります：

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義することも、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。また、オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加できます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を XPS 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に XPS に変換する無料のオンライン [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルトの XpsSaveOptions オブジェクトを定義する
      var options = new XpsSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### 関連項目

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, ICreateStreamProvider) {#convertsvg_46}

インラインコンテンツで提供された SVG ソースを XPS に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | 文字列としてインライン SVG コンテンツ。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

SVG を XPS に変換する

Converter クラスは、SVG を XPS に変換する複数の専用変換を提供します。SVG を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります：

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義することも、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。また、オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加できます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を XPS 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に XPS に変換する無料のオンライン [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルトの XpsSaveOptions オブジェクトを定義する
      var options = new XpsSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, DocSaveOptions, String) {#convertsvg_1}

`[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)` で提供された SVG ソースを変換します。結果は出力ファイルパスによって生成された docx ファイルです。

```java
public static void ConvertSVG(SVGDocument source, DocSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| source | SVGDocument | [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) で提示された変換ソースです。 |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な docx ファイルパス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) を参照してください。ここでは、Converter クラスの ConvertSVG() メソッドを使用して SVG を [DOCX](https://docs.fileformat.com/word-processing/docx/) に変換する方法や、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が見つかります。

SVG を DOCX に変換

Converter クラスは SVG を DOCX に変換する複数の専用シナリオを提供します。SVG を DOCX に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を DOCX 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // SVG ドキュメントを変換ソースとして形成する
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // デフォルト構成で変換プロセスを開始する
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, String) {#convertsvg_17}

`[`URL`](../../../com.aspose.html/url/)` で提供された SVG ソースを変換します。結果は出力ファイルパスによって生成された docx ファイルです。

```java
public static void ConvertSVG(Url url, DocSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | SVG ソースドキュメント [`URL`](../../../com.aspose.html/url/) - ユニバーサル識別子（URL）のオブジェクト表現を提供します。 |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な docx ファイルパス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) を参照してください。ここでは、Converter クラスの ConvertSVG() メソッドを使用して SVG を [DOCX](https://docs.fileformat.com/word-processing/docx/) に変換する方法や、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が見つかります。

SVG を DOCX に変換

Converter クラスは SVG を DOCX に変換する複数の専用シナリオを提供します。SVG を DOCX に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を DOCX 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertSVG(sourceUrl, options, resultPath);





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

## ConvertSVG(Url, Configuration, DocSaveOptions, String) {#convertsvg_9}

`[`URL`](../../../com.aspose.html/url/)` で提供された SVG ソースを変換します。結果は出力ファイルパスによって生成された docx ファイルです。

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | SVG ソースドキュメント [`URL`](../../../com.aspose.html/url/) - ユニバーサル識別子（URL）のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な docx ファイルパス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) を参照してください。ここでは、Converter クラスの ConvertSVG() メソッドを使用して SVG を [DOCX](https://docs.fileformat.com/word-processing/docx/) に変換する方法や、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が見つかります。

SVG を DOCX に変換

Converter クラスは SVG を DOCX に変換する複数の専用シナリオを提供します。SVG を DOCX に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を DOCX 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, DocSaveOptions, String) {#convertsvg_33}

フルファイルパスで指定された SVG ソースを DOCX に変換します。結果は、出力ファイルパスで生成された docx ファイルです。

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | SVG ソースの完全なファイルパスです。 |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な docx ファイルパス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) を参照してください。ここでは、Converter クラスの ConvertSVG() メソッドを使用して SVG を [DOCX](https://docs.fileformat.com/word-processing/docx/) に変換する方法や、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が見つかります。

SVG を DOCX に変換

Converter クラスは SVG を DOCX に変換する複数の専用シナリオを提供します。SVG を DOCX に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を DOCX 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertSVG(sourcePath, options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 関連項目

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, DocSaveOptions, String) {#convertsvg_25}

フルファイルパスで指定された SVG ソースを DOCX に変換します。結果は、出力ファイルパスで生成された docx ファイルです。

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | SVG ソースの完全なファイルパスです。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な docx ファイルパス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) を参照してください。ここでは、Converter クラスの ConvertSVG() メソッドを使用して SVG を [DOCX](https://docs.fileformat.com/word-processing/docx/) に変換する方法や、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が見つかります。

SVG を DOCX に変換

Converter クラスは SVG を DOCX に変換する複数の専用シナリオを提供します。SVG を DOCX に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を DOCX 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, DocSaveOptions, String) {#convertsvg_49}

インラインコンテンツで提示されたSVGソースを変換します。結果は出力ファイルパスで作成されたdocxファイルです。

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | 文字列としてインライン SVG コンテンツ。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な docx ファイルパス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) を参照してください。ここでは、Converter クラスの ConvertSVG() メソッドを使用して SVG を [DOCX](https://docs.fileformat.com/word-processing/docx/) に変換する方法や、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が見つかります。

SVG を DOCX に変換

Converter クラスは SVG を DOCX に変換する複数の専用シナリオを提供します。SVG を DOCX に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を DOCX 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // インライン SVG コンテンツを作成
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### 関連項目

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, String) {#convertsvg_41}

インラインコンテンツで提示されたSVGソースを変換します。結果は出力ファイルパスで作成されたdocxファイルです。

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | 文字列としてインライン SVG コンテンツ。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な docx ファイルパス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) を参照してください。ここでは、Converter クラスの ConvertSVG() メソッドを使用して SVG を [DOCX](https://docs.fileformat.com/word-processing/docx/) に変換する方法や、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が見つかります。

SVG を DOCX に変換

Converter クラスは SVG を DOCX に変換する複数の専用シナリオを提供します。SVG を DOCX に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を DOCX 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // インライン SVG コンテンツを作成
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.docx");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, DocSaveOptions, ICreateStreamProvider) {#convertsvg}

[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) で提示された SVG ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertSVG(SVGDocument document, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| document | SVGDocument | [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) で提示された変換ソースです。 |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions) を参照してください。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) を参照してください。ここでは、Converter クラスの ConvertSVG() メソッドを使用して SVG を [DOCX](https://docs.fileformat.com/word-processing/docx/) に変換する方法や、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が見つかります。

SVG を DOCX に変換

Converter クラスは SVG を DOCX に変換する複数の専用シナリオを提供します。SVG を DOCX に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を DOCX 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // SVG ドキュメントを変換ソースとして形成する
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // デフォルト構成で変換プロセスを開始する
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, DocSaveOptions, ICreateStreamProvider) {#convertsvg_16}

[`URL`](../../../com.aspose.html/url/) で提示された SVG ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertSVG(Url url, DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | SVG ソースドキュメント [`URL`](../../../com.aspose.html/url/) - ユニバーサル識別子（URL）のオブジェクト表現を提供します。 |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) を参照してください。ここでは、Converter クラスの ConvertSVG() メソッドを使用して SVG を [DOCX](https://docs.fileformat.com/word-processing/docx/) に変換する方法や、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が見つかります。

SVG を DOCX に変換

Converter クラスは SVG を DOCX に変換する複数の専用シナリオを提供します。SVG を DOCX に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を DOCX 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 変換プロセスを開始する
      Converter.ConvertSVG(sourceUrl, options, sp);





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

## ConvertSVG(Url, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_8}

`[`URL`](../../../com.aspose.html/url/)` で提供された SVG ソースを変換します。結果は出力ファイルパスによって生成された docx ファイルです。

```java
public static void ConvertSVG(Url url, Configuration configuration, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | SVG ソースドキュメント [`URL`](../../../com.aspose.html/url/) - ユニバーサル識別子（URL）のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions) を参照してください。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) を参照してください。ここでは、Converter クラスの ConvertSVG() メソッドを使用して SVG を [DOCX](https://docs.fileformat.com/word-processing/docx/) に変換する方法や、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が見つかります。

SVG を DOCX に変換

Converter クラスは SVG を DOCX に変換する複数の専用シナリオを提供します。SVG を DOCX に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を DOCX 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);





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

## ConvertSVG(String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_32}

完全なファイルパスで提供された SVG ソースを DOCX に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertSVG(String sourcePath, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | SVG ソースの完全なファイルパスです。 |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions) を参照してください。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) を参照してください。ここでは、Converter クラスの ConvertSVG() メソッドを使用して SVG を [DOCX](https://docs.fileformat.com/word-processing/docx/) に変換する方法や、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が見つかります。

SVG を DOCX に変換

Converter クラスは SVG を DOCX に変換する複数の専用シナリオを提供します。SVG を DOCX に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を DOCX 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 変換プロセスを開始する
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_24}

完全なファイルパスで提供された SVG ソースを DOCX に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | SVG ソースの完全なファイルパスです。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) を参照してください。ここでは、Converter クラスの ConvertSVG() メソッドを使用して SVG を [DOCX](https://docs.fileformat.com/word-processing/docx/) に変換する方法や、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が見つかります。

SVG を DOCX に変換

Converter クラスは SVG を DOCX に変換する複数の専用シナリオを提供します。SVG を DOCX に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を DOCX 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, DocSaveOptions, ICreateStreamProvider) {#convertsvg_48}

インラインコンテンツで提供された SVG ソースを DOCX に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertSVG(String content, String baseUri, DocSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | 文字列としてインライン SVG コンテンツ。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) を参照してください。ここでは、Converter クラスの ConvertSVG() メソッドを使用して SVG を [DOCX](https://docs.fileformat.com/word-processing/docx/) に変換する方法や、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が見つかります。

SVG を DOCX に変換

Converter クラスは SVG を DOCX に変換する複数の専用シナリオを提供します。SVG を DOCX に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を DOCX 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### 関連項目

* class [DocSaveOptions](../../../com.aspose.html.saving/docsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, DocSaveOptions, ICreateStreamProvider) {#convertsvg_40}

インラインコンテンツで提供された SVG ソースを DOCX に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    DocSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | 文字列としてインライン SVG コンテンツ。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | DocSaveOptions | `[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/#convert-svg-to-docx-using-docsaveoptions) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-docx/) を参照してください。ここでは、Converter クラスの ConvertSVG() メソッドを使用して SVG を [DOCX](https://docs.fileformat.com/word-processing/docx/) に変換する方法や、[`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が見つかります。

SVG を DOCX に変換

Converter クラスは SVG を DOCX に変換する複数の専用シナリオを提供します。SVG を DOCX に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`DocSaveOptions`](../../../com.aspose.html.saving/docsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を DOCX 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に DOCX に変換する無料のオンライン [SVG to DOCX Converter](https://products.aspose.app/svg/en/conversion/svg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルトの DocSaveOptions オブジェクトを定義する
      var options = new DocSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, PdfSaveOptions, String) {#convertsvg_5}

`[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)` で提供された SVG ソースを PDF に変換します。結果は出力ファイルパスによって生成された pdf ファイルです。

```java
public static void ConvertSVG(SVGDocument source, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| source | SVGDocument | [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) で提示された変換ソースです。 |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な pdf ファイルパス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が得られます。

SVG を PDF に変換

Converter クラスは SVG を PDF に変換する複数の専用シナリオを提供します。SVG を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を PDF 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に PDF に変換する無料のオンライン [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // SVG ドキュメントを変換ソースとして形成する
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // デフォルト構成で変換プロセスを開始する
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, String) {#convertsvg_21}

`[`URL`](../../../com.aspose.html/url/)` で提供された SVG ソースを変換します。結果は出力ファイルパスによって生成された pdf ファイルです。

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | SVG ソースドキュメント [`URL`](../../../com.aspose.html/url/) - ユニバーサル識別子（URL）のオブジェクト表現を提供します。 |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な pdf ファイルパス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が得られます。

SVG を PDF に変換

Converter クラスは SVG を PDF に変換する複数の専用シナリオを提供します。SVG を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を PDF 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に PDF に変換する無料のオンライン [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, PdfSaveOptions, String) {#convertsvg_13}

`[`URL`](../../../com.aspose.html/url/)` で提供された SVG ソースを変換します。結果は出力ファイルパスによって生成された pdf ファイルです。

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | SVG ソースドキュメント [`URL`](../../../com.aspose.html/url/) - ユニバーサル識別子（URL）のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な pdf ファイルパス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が得られます。

SVG を PDF に変換

Converter クラスは SVG を PDF に変換する複数の専用シナリオを提供します。SVG を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を PDF 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に PDF に変換する無料のオンライン [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertSVG(String, PdfSaveOptions, String) {#convertsvg_37}

フルファイルパスで指定された SVG ソースを PDF に変換します。結果は、出力ファイルパスで生成された pdf ファイルです。

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | SVG ソースの完全なファイルパスです。 |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な pdf ファイルパス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が得られます。

SVG を PDF に変換

Converter クラスは SVG を PDF に変換する複数の専用シナリオを提供します。SVG を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を PDF 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に PDF に変換する無料のオンライン [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, PdfSaveOptions, String) {#convertsvg_29}

フルファイルパスで指定された SVG ソースを PDF に変換します。結果は、出力ファイルパスで生成された pdf ファイルです。

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | SVG ソースの完全なファイルパスです。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な pdf ファイルパス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が得られます。

SVG を PDF に変換

Converter クラスは SVG を PDF に変換する複数の専用シナリオを提供します。SVG を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を PDF 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に PDF に変換する無料のオンライン [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, PdfSaveOptions, String) {#convertsvg_53}

インラインコンテンツで提示されたSVGソースをPDFに変換します。結果は出力ファイルパスで作成されたpdfファイルです。

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | 文字列としてインライン SVG コンテンツ。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な pdf ファイルパス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が得られます。

SVG を PDF に変換

Converter クラスは SVG を PDF に変換する複数の専用シナリオを提供します。SVG を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を PDF 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に PDF に変換する無料のオンライン [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // インライン SVG コンテンツを作成
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### 関連項目

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, String) {#convertsvg_45}

インラインコンテンツで提示されたSVGソースをPDFに変換します。結果は出力ファイルパスで作成されたpdfファイルです。

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | 文字列としてインライン SVG コンテンツ。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な pdf ファイルパス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が得られます。

SVG を PDF に変換

Converter クラスは SVG を PDF に変換する複数の専用シナリオを提供します。SVG を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を PDF 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に PDF に変換する無料のオンライン [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // インライン SVG コンテンツを作成
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.pdf");

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_4}

`[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)` で提供された SVG ソースを PDF に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertSVG(SVGDocument document, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| document | SVGDocument | [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) で提示された変換ソースです。 |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が得られます。

SVG を PDF に変換

Converter クラスは SVG を PDF に変換する複数の専用シナリオを提供します。SVG を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を PDF 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に PDF に変換する無料のオンライン [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // SVG ドキュメントを変換ソースとして形成する
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // デフォルト構成で変換プロセスを開始する
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_20}

[`URL`](../../../com.aspose.html/url/) で提示された SVG ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertSVG(Url url, PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | SVG ソースドキュメント [`URL`](../../../com.aspose.html/url/) - ユニバーサル識別子（URL）のオブジェクト表現を提供します。 |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が得られます。

SVG を PDF に変換

Converter クラスは SVG を PDF に変換する複数の専用シナリオを提供します。SVG を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を PDF 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に PDF に変換する無料のオンライン [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 変換プロセスを開始する
      Converter.ConvertSVG(sourceUrl, options, sp);
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

## ConvertSVG(Url, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_12}

[`URL`](../../../com.aspose.html/url/) で提示された SVG ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertSVG(Url url, Configuration configuration, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | SVG ソースドキュメント [`URL`](../../../com.aspose.html/url/) - ユニバーサル識別子（URL）のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が得られます。

SVG を PDF に変換

Converter クラスは SVG を PDF に変換する複数の専用シナリオを提供します。SVG を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を PDF 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に PDF に変換する無料のオンライン [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

## ConvertSVG(String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_36}

完全なファイルパスで提供された SVG ソースを PDF に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertSVG(String sourcePath, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | SVG ソースの完全なファイルパスです。 |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が得られます。

SVG を PDF に変換

Converter クラスは SVG を PDF に変換する複数の専用シナリオを提供します。SVG を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を PDF 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に PDF に変換する無料のオンライン [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 変換プロセスを開始する
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_28}

完全なファイルパスで提供された SVG ソースを PDF に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | SVG ソースの完全なファイルパスです。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が得られます。

SVG を PDF に変換

Converter クラスは SVG を PDF に変換する複数の専用シナリオを提供します。SVG を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を PDF 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に PDF に変換する無料のオンライン [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_52}

インラインコンテンツで提供された SVG ソースを PDF に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertSVG(String content, String baseUri, PdfSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | 文字列としてインライン SVG コンテンツ。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が得られます。

SVG を PDF に変換

Converter クラスは SVG を PDF に変換する複数の専用シナリオを提供します。SVG を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を PDF 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に PDF に変換する無料のオンライン [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### 関連項目

* class [PdfSaveOptions](../../../com.aspose.html.saving/pdfsaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, PdfSaveOptions, ICreateStreamProvider) {#convertsvg_44}

インラインコンテンツで提供された SVG ソースを PDF に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    PdfSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | 文字列としてインライン SVG コンテンツ。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | PdfSaveOptions | `[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/)` オブジェクトの使用により、レンダリングプロセスを調整できます。詳細は [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#save-options) を参照してください。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を PDF に変換する方法や、[`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が得られます。

SVG を PDF に変換

Converter クラスは SVG を PDF に変換する複数の専用シナリオを提供します。SVG を PDF に変換するには、いくつかの手順で構成されるシンプルなシナリオのいずれかに従う必要があります。

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義したり、文字列ソースで提供されるインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`PdfSaveOptions`](../../../com.aspose.html.saving/pdfsaveoptions/) オブジェクトを作成します。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を PDF 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に PDF に変換する無料のオンライン [SVG to PDF Converter](https://products.aspose.app/svg/en/conversion/svg-to-pdf) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルトの PdfSaveOptions オブジェクトを定義
      var options = new PdfSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, ImageSaveOptions, String) {#convertsvg_3}

[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) によって提示された SVG ソースを変換します。結果は出力ファイルパスで作成された画像ファイルです。

```java
public static void ConvertSVG(SVGDocument source, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| source | SVGDocument | [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) で提示された変換ソースです。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)などを指定できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を JPG に変換する方法や、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。他の一般的な画像フォーマットに関する記事: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) および [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

SVG を画像に変換する

Converter クラスは、一般的なフォーマットでの SVG 固有の画像変換を複数提供します。SVG を画像に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換元として定義したり、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG であることに注意してください。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を画像として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に JPG に変換する無料のオンライン [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の一般的な画像フォーマット用のコンバータは、こちらで見つけられます: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) および [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions();

      // SVG ドキュメントを変換ソースとして形成する
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // デフォルト構成で変換プロセスを開始する
        Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, String) {#convertsvg_19}

`[`URL`](../../../com.aspose.html/url/)` によって提示された SVG ソースを変換します。結果は出力ファイルパスで作成された画像ファイルです。

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | SVG ソースドキュメント [`URL`](../../../com.aspose.html/url/) - ユニバーサル識別子（URL）のオブジェクト表現を提供します。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)などを指定できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を JPG に変換する方法や、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。他の一般的な画像フォーマットに関する記事: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) および [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

SVG を画像に変換する

Converter クラスは、一般的なフォーマットでの SVG 固有の画像変換を複数提供します。SVG を画像に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換元として定義したり、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG であることに注意してください。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を画像として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に JPG に変換する無料のオンライン [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の一般的な画像フォーマット用のコンバータは、こちらで見つけられます: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) および [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // 変換プロセスを開始する
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, ImageSaveOptions, String) {#convertsvg_11}

`[`URL`](../../../com.aspose.html/url/)` によって提示された SVG ソースを変換します。結果は出力ファイルパスで作成された画像ファイルです。

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | SVG ソースドキュメント [`URL`](../../../com.aspose.html/url/) - ユニバーサル識別子（URL）のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)などを指定できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を JPG に変換する方法や、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。他の一般的な画像フォーマットに関する記事: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) および [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

SVG を画像に変換する

Converter クラスは、一般的なフォーマットでの SVG 固有の画像変換を複数提供します。SVG を画像に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換元として定義したり、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG であることに注意してください。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を画像として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に JPG に変換する無料のオンライン [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の一般的な画像フォーマット用のコンバータは、こちらで見つけられます: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) および [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);
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

## ConvertSVG(String, ImageSaveOptions, String) {#convertsvg_35}

フルファイルパスで指定された SVG ソースを画像に変換します。結果は、出力ファイルパスで生成された画像ファイルです。

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | SVG ソースの完全なファイルパスです。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)などを指定できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を JPG に変換する方法や、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。他の一般的な画像フォーマットに関する記事: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) および [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

SVG を画像に変換する

Converter クラスは、一般的なフォーマットでの SVG 固有の画像変換を複数提供します。SVG を画像に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換元として定義したり、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG であることに注意してください。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を画像として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に JPG に変換する無料のオンライン [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の一般的な画像フォーマット用のコンバータは、こちらで見つけられます: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) および [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // 変換プロセスを開始する
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, ImageSaveOptions, String) {#convertsvg_27}

フルファイルパスで指定された SVG ソースを画像に変換します。結果は、出力ファイルパスで生成された画像ファイルです。

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | SVG ソースの完全なファイルパスです。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)などを指定できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を JPG に変換する方法や、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。他の一般的な画像フォーマットに関する記事: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) および [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

SVG を画像に変換する

Converter クラスは、一般的なフォーマットでの SVG 固有の画像変換を複数提供します。SVG を画像に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換元として定義したり、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG であることに注意してください。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を画像として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に JPG に変換する無料のオンライン [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の一般的な画像フォーマット用のコンバータは、こちらで見つけられます: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) および [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, ImageSaveOptions, String) {#convertsvg_51}

インラインコンテンツで提示されたSVGソースを画像に変換します。結果は出力ファイルパスで作成された画像ファイルです。

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | 文字列としてインライン SVG コンテンツ。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)などを指定できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を JPG に変換する方法や、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。他の一般的な画像フォーマットに関する記事: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) および [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

SVG を画像に変換する

Converter クラスは、一般的なフォーマットでの SVG 固有の画像変換を複数提供します。SVG を画像に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換元として定義したり、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG であることに注意してください。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を画像として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に JPG に変換する無料のオンライン [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の一般的な画像フォーマット用のコンバータは、こちらで見つけられます: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) および [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // インライン SVG コンテンツを作成
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.png");

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### 関連項目

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, String) {#convertsvg_43}

インラインコンテンツで提示されたSVGソースを画像に変換します。結果は出力ファイルパスで作成された画像ファイルです。

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | 文字列としてインライン SVG コンテンツ。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)などを指定できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な画像ファイルパス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を JPG に変換する方法や、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。他の一般的な画像フォーマットに関する記事: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) および [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

SVG を画像に変換する

Converter クラスは、一般的なフォーマットでの SVG 固有の画像変換を複数提供します。SVG を画像に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換元として定義したり、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG であることに注意してください。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を画像として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に JPG に変換する無料のオンライン [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の一般的な画像フォーマット用のコンバータは、こちらで見つけられます: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) および [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // インライン SVG コンテンツを作成
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.jpg");

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions(ImageFormat.Jpeg);

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(SVGDocument, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_2}

[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) で提示された SVG ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertSVG(SVGDocument document, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| document | SVGDocument | [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) で提示された変換ソースです。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)などを指定できます。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を JPG に変換する方法や、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。他の一般的な画像フォーマットに関する記事: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) および [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

SVG を画像に変換する

Converter クラスは、一般的なフォーマットでの SVG 固有の画像変換を複数提供します。SVG を画像に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換元として定義したり、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG であることに注意してください。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を画像として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に JPG に変換する無料のオンライン [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の一般的な画像フォーマット用のコンバータは、こちらで見つけられます: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) および [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions();

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // SVG ドキュメントを変換ソースとして形成する
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
        // 変換プロセスを開始する
        Converter.ConvertSVG(document, options, sp);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_18}

[`URL`](../../../com.aspose.html/url/) で提示された SVG ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertSVG(Url url, ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | SVG ソースドキュメント [`URL`](../../../com.aspose.html/url/) - ユニバーサル識別子（URL）のオブジェクト表現を提供します。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)などを指定できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を JPG に変換する方法や、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。他の一般的な画像フォーマットに関する記事: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) および [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

SVG を画像に変換する

Converter クラスは、一般的なフォーマットでの SVG 固有の画像変換を複数提供します。SVG を画像に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換元として定義したり、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG であることに注意してください。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を画像として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に JPG に変換する無料のオンライン [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の一般的な画像フォーマット用のコンバータは、こちらで見つけられます: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) および [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions(ImageFormat.Bmp);

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 変換プロセスを開始する
      Converter.ConvertSVG(sourceUrl, options, sp);
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

## ConvertSVG(Url, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_10}

[`URL`](../../../com.aspose.html/url/) で提示された SVG ソースを変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって生成された出力データです。

```java
public static void ConvertSVG(Url url, Configuration configuration, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | SVG ソースドキュメント [`URL`](../../../com.aspose.html/url/) - ユニバーサル識別子（URL）のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)などを指定できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を JPG に変換する方法や、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。他の一般的な画像フォーマットに関する記事: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) および [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

SVG を画像に変換する

Converter クラスは、一般的なフォーマットでの SVG 固有の画像変換を複数提供します。SVG を画像に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換元として定義したり、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG であることに注意してください。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を画像として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に JPG に変換する無料のオンライン [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の一般的な画像フォーマット用のコンバータは、こちらで見つけられます: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) および [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions();

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, sp);
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

## ConvertSVG(String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_34}

完全なファイルパスで提示された SVG ソースを画像に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertSVG(String sourcePath, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | SVG ソースの完全なファイルパスです。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)などを指定できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を JPG に変換する方法や、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。他の一般的な画像フォーマットに関する記事: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) および [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

SVG を画像に変換する

Converter クラスは、一般的なフォーマットでの SVG 固有の画像変換を複数提供します。SVG を画像に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換元として定義したり、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG であることに注意してください。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を画像として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に JPG に変換する無料のオンライン [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の一般的な画像フォーマット用のコンバータは、こちらで見つけられます: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) および [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions();

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // 変換プロセスを開始する
      Converter.ConvertSVG(sourcePath, options, sp);
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

## ConvertSVG(String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_26}

完全なファイルパスで提示された SVG ソースを画像に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | SVG ソースの完全なファイルパスです。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)などを指定できます。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を JPG に変換する方法や、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。他の一般的な画像フォーマットに関する記事: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) および [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

SVG を画像に変換する

Converter クラスは、一般的なフォーマットでの SVG 固有の画像変換を複数提供します。SVG を画像に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換元として定義したり、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG であることに注意してください。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を画像として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に JPG に変換する無料のオンライン [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の一般的な画像フォーマット用のコンバータは、こちらで見つけられます: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) および [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions(ImageFormat.Tiff);

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertSVG(sourcePath, new Configuration(), options, sp);
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

## ConvertSVG(String, String, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_50}

インラインコンテンツで提示された SVG ソースを画像に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertSVG(String content, String baseUri, ImageSaveOptions options, 
    ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | 文字列としてインライン SVG コンテンツ。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)などを指定できます。 |
| provider | ICreateStreamProvider | 既知（[`FileCreateStreamProvider`](../../../com.aspose.html.io/filecreatestreamprovider/) を参照）またはカスタムの [`ICreateStreamP﻿rovider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を JPG に変換する方法や、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。他の一般的な画像フォーマットに関する記事: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) および [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

SVG を画像に変換する

Converter クラスは、一般的なフォーマットでの SVG 固有の画像変換を複数提供します。SVG を画像に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換元として定義したり、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG であることに注意してください。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を画像として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に JPG に変換する無料のオンライン [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の一般的な画像フォーマット用のコンバータは、こちらで見つけられます: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) および [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertSVG(content, String.Empty, options, sp);
```

*OutputFolder - user output file path.

### 関連項目

* class [ImageSaveOptions](../../../com.aspose.html.saving/imagesaveoptions/)
* interface [ICreateStreamProvider](../../../com.aspose.html.io/icreatestreamprovider/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, ImageSaveOptions, ICreateStreamProvider) {#convertsvg_42}

インラインコンテンツで提示された SVG ソースを画像に変換します。結果は [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装によって形成された出力データです。

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    ImageSaveOptions options, ICreateStreamProvider provider)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | 文字列としてインライン SVG コンテンツ。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | ImageSaveOptions | [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/)オブジェクトの使用により、レンダリングプロセスを調整できます。[`page size`](../../../com.aspose.html.rendering/renderingoptions/pagesetup/)、[`margins`](../../../com.aspose.html.drawing/page/margin/)、[`CSS media-type`](../../../com.aspose.html.rendering/mediatype/)などを指定できます。 |
| provider | ICreateStreamProvider | 出力ストリームを取得するために使用される [`interface`](../../../com.aspose.html.io/icreatestreamprovider/) の実装です。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/) を参照してください。そこでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を JPG に変換する方法や、[`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法が記載されています。他の一般的な画像フォーマットに関する記事: [SVG to PNG conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/)、[SVG to BMP conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/)、[SVG to GIF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/) および [SVG to TIFF conversion](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/)。

SVG を画像に変換する

Converter クラスは、一般的なフォーマットでの SVG 固有の画像変換を複数提供します。SVG を画像に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります。

変換元。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換元として検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換元として定義したり、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`ImageSaveOptions`](../../../com.aspose.html.saving/imagesaveoptions/) オブジェクトを作成します。デフォルトの画像形式は PNG であることに注意してください。オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加することもできます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を画像として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に JPG に変換する無料のオンライン [SVG to JPG Converter](https://products.aspose.app/svg/en/conversion/svg-to-jpg) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

他の一般的な画像フォーマット用のコンバータは、こちらで見つけられます: [SVG to PNG Converter](https://products.aspose.app/svg/en/conversion/svg-to-png)、[SVG to BMP Converter](https://products.aspose.app/svg/en/conversion/svg-to-bmp)、[SVG to GIF Converter](https://products.aspose.app/svg/en/conversion/svg-to-gif) および [SVG to TIFF Converter](https://products.aspose.app/svg/en/conversion/svg-to-tiff)。

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO; 
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // ICreateStreamProvider 実装のいずれかを使用
      ICreateStreamProvider sp = new FileCreateStreamProvider(resultPath);

      // デフォルトの ImageSaveOptions オブジェクトを定義する
      var options = new ImageSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, sp);
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

## ConvertSVG(SVGDocument, XpsSaveOptions, String) {#convertsvg_7}

`[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/)` によって提示された SVG ソースを変換します。結果は出力ファイルパスで作成された XPS ファイルです。

```java
public static void ConvertSVG(SVGDocument source, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| source | SVGDocument | [`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) で提示された変換ソースです。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な xps ファイル パス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

SVG を XPS に変換する

Converter クラスは、SVG を XPS に変換する複数の専用変換を提供します。SVG を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります：

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義することも、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。また、オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加できます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を XPS 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に XPS に変換する無料のオンライン [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "simple.svg");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result");

      // デフォルトの XpsSaveOptions オブジェクトを定義する
      var options = new XpsSaveOptions();

      // SVG ドキュメントを変換ソースとして形成する
      using (var document = new SVGDocument(sourcePath, new Configuration()))
      {
		// デフォルト構成で変換プロセスを開始する
		Converter.ConvertSVG(document, options, resultPath);
      }
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [SVGDocument](../../../com.aspose.html.dom.svg/svgdocument/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(Url, XpsSaveOptions, String) {#convertsvg_23}

`[`URL`](../../../com.aspose.html/url/)` によって提示された SVG ソースを変換します。結果は出力ファイルパスで作成された XPS ファイルです。

```java
public static void ConvertSVG(Url url, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | SVG ソースドキュメント [`URL`](../../../com.aspose.html/url/) - ユニバーサル識別子（URL）のオブジェクト表現を提供します。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な xps ファイル パス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

SVG を XPS に変換する

Converter クラスは、SVG を XPS に変換する複数の専用変換を提供します。SVG を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります：

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義することも、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。また、オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加できます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を XPS 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に XPS に変換する無料のオンライン [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // デフォルトの XpsSaveOptions オブジェクトを定義する
      var options = new XpsSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertSVG(sourceUrl, options, resultPath);
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

## ConvertSVG(Url, Configuration, XpsSaveOptions, String) {#convertsvg_15}

`[`URL`](../../../com.aspose.html/url/)` によって提示された SVG ソースを変換します。結果は出力ファイルパスで作成された XPS ファイルです。

```java
public static void ConvertSVG(Url url, Configuration configuration, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| url | Url | SVG ソースドキュメント [`URL`](../../../com.aspose.html/url/) - ユニバーサル識別子（URL）のオブジェクト表現を提供します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な xps ファイル パス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

SVG を XPS に変換する

Converter クラスは、SVG を XPS に変換する複数の専用変換を提供します。SVG を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります：

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義することも、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。また、オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加できます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を XPS 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に XPS に変換する無料のオンライン [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
...
      // 入力ファイルパスに基づいて Url を作成する
      var sourceUrl = new Url(Path.Combine(InputFolder, "sample.svg"));

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // デフォルトの XpsSaveOptions オブジェクトを定義する
      var options = new XpsSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertSVG(sourceUrl, new Configuration(), options, resultPath);





*InputFolder - user source file path.

```

*OutputFolder - user output file path.

### 関連項目

* class [Url](../../../com.aspose.html/url/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, XpsSaveOptions, String) {#convertsvg_39}

フルファイルパスで指定された SVG ソースを XPS に変換します。結果は、出力ファイルパスで生成された xps ファイルです。

```java
public static void ConvertSVG(String sourcePath, XpsSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | SVG ソースの完全なファイルパスです。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な xps ファイル パス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

SVG を XPS に変換する

Converter クラスは、SVG を XPS に変換する複数の専用変換を提供します。SVG を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります：

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義することも、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。また、オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加できます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を XPS 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に XPS に変換する無料のオンライン [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // デフォルトの XpsSaveOptions オブジェクトを定義する
      var options = new XpsSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertSVG(sourcePath, options, resultPath);
```

*InputFolder - user source file path.

*OutputFolder - user output file path.

### 関連項目

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, Configuration, XpsSaveOptions, String) {#convertsvg_31}

フルファイルパスで指定された SVG ソースを XPS に変換します。結果は、出力ファイルパスで生成された xps ファイルです。

```java
public static void ConvertSVG(String sourcePath, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| sourcePath | 文字列 | SVG ソースの完全なファイルパスです。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な xps ファイル パス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

SVG を XPS に変換する

Converter クラスは、SVG を XPS に変換する複数の専用変換を提供します。SVG を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります：

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義することも、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。また、オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加できます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を XPS 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に XPS に変換する無料のオンライン [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // フォームのソースファイルパス
      var sourcePath = Path.Combine(InputFolder, "sample.svg");

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // デフォルトの XpsSaveOptions オブジェクトを定義する
      var options = new XpsSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertSVG(sourcePath, new Configuration(), options, resultPath);
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

## ConvertSVG(String, String, XpsSaveOptions, String) {#convertsvg_55}

インラインコンテンツで提示されたSVGソースをXPSに変換します。結果は出力ファイルパスで作成されたxpsファイルです。

```java
public static void ConvertSVG(String content, String baseUri, XpsSaveOptions options, 
    String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | 文字列としてインライン SVG コンテンツ。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリング プロセスを調整できます。 |
| outputPath | 文字列 | 出力変換結果としての完全な xps ファイル パス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

SVG を XPS に変換する

Converter クラスは、SVG を XPS に変換する複数の専用変換を提供します。SVG を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります：

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義することも、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。また、オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加できます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を XPS 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に XPS に変換する無料のオンライン [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // インライン SVG コンテンツを作成
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // デフォルトの XpsSaveOptions オブジェクトを定義する
      var options = new XpsSaveOptions();

      // 変換プロセスを開始する
      Converter.ConvertSVG(content, String.Empty, options, resultPath);
```

*OutputFolder - user output file path.

### 関連項目

* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)

---

## ConvertSVG(String, String, Configuration, XpsSaveOptions, String) {#convertsvg_47}

インラインコンテンツで提示されたSVGソースをXPSに変換します。結果は出力ファイルパスで作成されたxpsファイルです。

```java
public static void ConvertSVG(String content, String baseUri, Configuration configuration, 
    XpsSaveOptions options, String outputPath)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| コンテンツ | 文字列 | 文字列としてインライン SVG コンテンツ。 |
| baseUri | 文字列 | ドキュメントのベース URI です。現在のディレクトリパスと組み合わせて絶対 URL を形成します。 |
| configuration | Configuration | 環境構成。アプリケーションの環境設定を設定するために使用される [`configuration`](../../../com.aspose.html/configuration/) コンテキストオブジェクトを表します。 |
| options | XpsSaveOptions | [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトの使用により、レンダリングプロセスを調整できます。詳細については [Aspose Documentation](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#save-options) を参照してください。 |
| outputPath | 文字列 | 出力変換結果としての完全な xps ファイル パス。 |

## Remarks

SVG コンバータ

[SVG](https://docs.fileformat.com/page-description-language/svg/) files are Scalable Vector Graphics Files that use XML based text format for describing the appearance of an image. The word Scalable refers to the fact that SVG can be scaled to different sizes without losing any quality. A text-based description of such files makes them independent of resolution. It is one of the most used formats for website building and print graphics to achieve scalability.

[XPS](https://docs.fileformat.com/page-description-language/xps/) is a document storage and viewing format developed by Microsoft. An XPS file has a set of advantages that support security features, such as digital signatures to provide greater document security and more.

[article](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/) を参照してください。ここでは、[`Converter`](../) クラスの ConvertSVG() メソッドを使用して SVG を XPS に変換する方法や、[`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) と [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) パラメータの適用方法についての情報が掲載されています。

SVG を XPS に変換する

Converter クラスは、SVG を XPS に変換する複数の専用変換を提供します。SVG を XPS に変換するには、いくつかの手順からなるシンプルなシナリオのいずれかに従う必要があります：

変換ソース。既存のローカル SVG ファイルまたはリモート [`Url`](../../../com.aspose.html/url/) を変換ソースとして検出します。[`SVGDocument`](../../../com.aspose.html.dom.svg/svgdocument/) を変換ソースとして定義することも、文字列ソースで提示されたインライン SVG コンテンツを使用することもできます。変換結果。結果の出力ファイルパスを定義するか、既知またはカスタムの [`ICreateStreamProvider`](../../../com.aspose.html.io/icreatestreamprovider/) インターフェイス実装を出力データバッファとして使用します。特定またはデフォルト設定で新しい [`XpsSaveOptions`](../../../com.aspose.html.saving/xpssaveoptions/) オブジェクトを作成します。また、オプションパラメータとして [`configuration`](../../../com.aspose.html/configuration/) を追加できます。Converter クラスの ConvertSVG() メソッドを使用して、ユーザーシナリオに応じて 3 つ以上のパラメータで SVG を XPS 結果として保存します。オンライン SVG コンバータ

Aspose.HTML は、SVG を高品質かつ簡単・高速に XPS に変換する無料のオンライン [SVG to XPS Converter](https://products.aspose.app/svg/en/conversion/svg-to-xps) を提供しています。ファイルをアップロードして変換するだけで、数秒で結果が得られます！

ソースコード

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import System.IO;
import com.aspose.html.io;
import com.aspose.html.saving;  
import com.aspose.html.converters;  
... 
      // インライン SVG コンテンツを作成
      var content = @"<svg xmlns=""http://www.w3.org/2000/svg"" width=""100"" height=""100"">
        <circle cx=""50"" cy=""50"" r=""40"" stroke=""green"" stroke-width=""4"" fill=""yellow"" />
        </svg>";

      // フォームの結果ファイルパス
      var resultPath = Path.Combine(OutputFolder, "result.xps");

      // デフォルトの XpsSaveOptions オブジェクトを定義する
      var options = new XpsSaveOptions();

      // デフォルト構成で変換プロセスを開始する
      Converter.ConvertSVG(content, String.Empty, new Configuration(), options, resultPath);
```

*OutputFolder - user output file path.

### 関連項目

* class [Configuration](../../../com.aspose.html/configuration/)
* class [XpsSaveOptions](../../../com.aspose.html.saving/xpssaveoptions/)
* class [Converter](../)
* package [com.aspose.html.converters](../../../com.aspose.html.converters/)
* package [Aspose.HTML](../../../)
