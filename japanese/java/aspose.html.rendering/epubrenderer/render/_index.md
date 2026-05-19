---
title: "EpubRenderer.Render"
second_title: "Aspose.HTML for Java API リファレンス"
description: "EpubRenderer メソッド。複数の EPub ストリームを特定の IDevice にレンダリングするメソッドを定義します。リソースの読み込み、アクティブなタイマー、アニメーションタスクのネットワーク操作がなく、指定されたタイムアウトが経過したときにレンダリングが実行されます。"
type: docs

url: /ja/java/com.aspose.html.rendering/epubrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_10}

複数の EPub ストリームを特定の [`IDevice`](../../idevice/) にレンダリングするメソッドを定義します。リソースの読み込み、アクティブなタイマー、アニメーションタスクのネットワーク操作がなく、指定されたタイムアウトが経過したときにレンダリングが実行されます。

```java
public void Render(IDevice device, TimeSpan timeout, params Stream[] sources)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| デバイス | IDevice | 出力デバイスです。 |
| タイムアウト | TimeSpan | 待機するミリ秒数を表す TimeSpan、または無期限に待機することを示す -1 ミリ秒の TimeSpan です。 |
| ドキュメント | Stream[] | レンダリングするドキュメント。 |

### 関連項目

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Stream[]) {#render_9}

複数の EPub ドキュメントを特定の [`IDevice`](../../idevice/) にレンダリングするメソッドを定義します。操作のキャンセルを要求するためにキャンセルトークンを使用します。

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params Stream[] sources)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| デバイス | IDevice | 出力デバイスです。 |
| cancellationToken | CancellationToken | タスクの完了を待機中に監視するための CancellationToken。 |
| ソース | Stream[] | レンダリングする EPub ドキュメント。 |

### 関連項目

* interface [IDevice](../../idevice/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

指定された [`IDevice`](../../idevice/) に EPub ドキュメントをレンダリングします。

```java
public void Render(IDevice device, Stream source, Configuration configuration)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| デバイス | IDevice | デバイス。 |
| ドキュメント | ストリーム | ドキュメント。 |
| 構成 | 構成 | 設定です。 |

### 関連項目

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

指定された [`IDevice`](../../idevice/) に EPub ドキュメントをレンダリングします。リソースの読み込み、アクティブなタイマー、アニメーションタスクのネットワーク操作がなく、指定されたタイムアウトが経過したときにレンダリングが実行されます。

```java
public void Render(IDevice device, Stream source, Configuration configuration, TimeSpan timeout)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| デバイス | IDevice | デバイス。 |
| ドキュメント | ストリーム | ドキュメント。 |
| 構成 | 構成 | 設定です。 |
| タイムアウト | TimeSpan | 待機するミリ秒数を表す TimeSpan、または無期限に待機することを示す -1 ミリ秒の TimeSpan です。 |

### 関連項目

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

指定された [`IDevice`](../../idevice/) に複数の EPub ドキュメントをレンダリングします。

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| デバイス | IDevice | デバイス。 |
| ドキュメント | IList`1 | レンダリング対象のドキュメントの IList。 |
| 構成 | 構成 | 設定です。 |

### 関連項目

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

指定された [`IDevice`](../../idevice/) に複数の EPub ドキュメントをレンダリングします。リソースの読み込み、アクティブなタイマー、アニメーションタスクのネットワーク操作がなく、指定されたタイムアウトが経過したときにレンダリングが実行されます。

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration, 
    TimeSpan timeout)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| デバイス | IDevice | デバイス。 |
| ドキュメント | IList`1 | レンダリング対象のドキュメントの IList。 |
| 構成 | 構成 | 設定です。 |
| タイムアウト | TimeSpan | 待機するミリ秒数を表す TimeSpan、または無期限に待機することを示す -1 ミリ秒の TimeSpan です。 |

### 関連項目

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [EpubRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
