---
title: "MhtmlRenderer.Render"
second_title: "Aspose.HTML for Java API リファレンス"
description: "MhtmlRenderer メソッド。指定された IDevice に複数の MHTML ドキュメントをレンダリングします。リソースの読み込み、アクティブなタイマー、アニメーションタスクのネットワーク操作がなくなり、指定されたタイムアウトが経過した時にレンダリングが実行されます。"
type: docs

url: /ja/java/com.aspose.html.rendering/mhtmlrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_10}

指定された[`IDevice`](../../idevice/)に複数の MHTML ドキュメントをレンダリングします。リソースの読み込み、アクティブなタイマー、アニメーションタスクのネットワーク操作がなくなり、指定されたタイムアウトが経過した時にレンダリングが実行されます。

```java
public void Render(IDevice device, TimeSpan timeout, params Stream[] sources)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| デバイス | IDevice | デバイス。 |
| タイムアウト | TimeSpan | 待機するミリ秒数を表す TimeSpan、または無期限に待機することを示す -1 ミリ秒の TimeSpan です。 |
| ドキュメント | Stream[] | レンダリングするドキュメント。 |

### 関連項目

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Stream[]) {#render_9}

特定の[`IDevice`](../../idevice/)に複数のMHTMLドキュメントをレンダリングするメソッドを定義し、キャンセル トークンを使用して操作のキャンセルを要求します。

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params Stream[] sources)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| デバイス | IDevice | 出力デバイスです。 |
| cancellationToken | CancellationToken | タスクの完了を待機中に監視するための CancellationToken。 |
| ソース | Stream[] | レンダリングするMHTMLドキュメント。 |

### 関連項目

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

指定された[`IDevice`](../../idevice/)にMHTMLドキュメントをレンダリングします。

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
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

指定された[`IDevice`](../../idevice/)にMHTMLドキュメントをレンダリングします。リソースの読み込み、アクティブなタイマー、アニメーションタスク、または指定されたタイムアウトが経過するまで、ネットワーク操作が存在しない場合にレンダリングが実行されます。

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
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

指定された[`IDevice`](../../idevice/)に複数のMHTMLドキュメントをレンダリングします。

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
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

指定された[`IDevice`](../../idevice/)に複数の MHTML ドキュメントをレンダリングします。リソースの読み込み、アクティブなタイマー、アニメーションタスクのネットワーク操作がなくなり、指定されたタイムアウトが経過した時にレンダリングが実行されます。

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
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
