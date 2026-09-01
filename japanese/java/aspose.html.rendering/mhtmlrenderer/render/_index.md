---
title: "MhtmlRenderer.Render"
second_title: "Aspose.HTML for Java API リファレンス"
description: "MhtmlRenderer メソッド。複数の MHTML ドキュメントを指定された IDevice にレンダリングします。リソースの読み込み、アクティブなタイマー、アニメーションタスクのネットワーク操作がなくなり、指定されたタイムアウトが経過した時点でレンダリングが実行されます。"
type: docs

url: /ja/java/com.aspose.html.rendering/mhtmlrenderer/render/
---
## Render(IDevice, TimeSpan, params Stream[]) {#render_10}

複数の MHTML ドキュメントを指定された[`IDevice`](../../idevice/)にレンダリングします。リソースの読み込み、アクティブなタイマー、アニメーションタスクのネットワーク操作がなくなり、指定されたタイムアウトが経過した時点でレンダリングが実行されます。

```java
public void Render(IDevice device, TimeSpan timeout, params Stream[] sources)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| デバイス | IDevice | デバイスです。 |
| タイムアウト | TimeSpan | 待機するミリ秒数を表す TimeSpan、または無期限に待機することを表す -1 ミリ秒の TimeSpan を表します。 |
| ドキュメント | Stream[] | レンダリングするドキュメント。 |

### 関連項目

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params Stream[]) {#render_9}

特定の[`IDevice`](../../idevice/)に複数の MHTML ドキュメントをレンダリングするメソッドを定義し、キャンセル トークンを使用して操作のキャンセルを要求します。

```java
public void Render(IDevice device, CancellationToken cancellationToken, 
    params Stream[] sources)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| デバイス | IDevice | 出力デバイスです。 |
| cancellationToken | CancellationToken | タスクの完了を待機中に監視するための CancellationToken。 |
| ソース | Stream[] | レンダリングする MHTML ドキュメント。 |

### 関連項目

* interface [IDevice](../../idevice/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration) {#render_4}

指定された[`IDevice`](../../idevice/)に MHTML ドキュメントをレンダリングします。

```java
public void Render(IDevice device, Stream source, Configuration configuration)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| デバイス | IDevice | デバイスです。 |
| ドキュメント | ストリーム | ドキュメントです。 |
| 構成 | 構成 | 設定です。 |

### 関連項目

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, Stream, Configuration, TimeSpan) {#render_5}

指定された[`IDevice`](../../idevice/)に MHTML ドキュメントをレンダリングします。リソースの読み込み、アクティブなタイマー、アニメーション タスクのネットワーク操作がなくなり、指定されたタイムアウトが経過した時点でレンダリングが実行されます。

```java
public void Render(IDevice device, Stream source, Configuration configuration, TimeSpan timeout)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| デバイス | IDevice | デバイスです。 |
| ドキュメント | ストリーム | ドキュメントです。 |
| 構成 | 構成 | 設定です。 |
| タイムアウト | TimeSpan | 待機するミリ秒数を表す TimeSpan、または無期限に待機することを表す -1 ミリ秒の TimeSpan を表します。 |

### 関連項目

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration) {#render_1}

指定された[`IDevice`](../../idevice/)に複数の MHTML ドキュメントをレンダリングします。

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| デバイス | IDevice | デバイスです。 |
| ドキュメント | IList`1 | レンダリングするドキュメントの IList。 |
| 構成 | 構成 | 設定です。 |

### 関連項目

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, IList&lt;Stream&gt;, Configuration, TimeSpan) {#render_2}

複数の MHTML ドキュメントを指定された[`IDevice`](../../idevice/)にレンダリングします。リソースの読み込み、アクティブなタイマー、アニメーションタスクのネットワーク操作がなくなり、指定されたタイムアウトが経過した時点でレンダリングが実行されます。

```java
public void Render(IDevice device, IList<Stream> sources, Configuration configuration, 
    TimeSpan timeout)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| デバイス | IDevice | デバイスです。 |
| ドキュメント | IList`1 | レンダリングするドキュメントの IList。 |
| 構成 | 構成 | 設定です。 |
| タイムアウト | TimeSpan | 待機するミリ秒数を表す TimeSpan、または無期限に待機することを表す -1 ミリ秒の TimeSpan を表します。 |

### 関連項目

* interface [IDevice](../../idevice/)
* class [Configuration](../../../com.aspose.html/configuration/)
* class [MhtmlRenderer](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
