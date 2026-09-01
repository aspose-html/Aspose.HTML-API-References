---
title: "Renderer-1.Render"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Renderer メソッド。TDocument を指定された IDevice にレンダリングするメソッドを定義します"
type: docs

url: /ja/java/com.aspose.html.rendering/renderer-1/render/
---
## Render(IDevice, TSource) {#render_3}

指定された[`IDevice`](../../idevice/)に !:TDocument をレンダリングするメソッドを定義します。

```java
public void Render(IDevice device, TSource source)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| デバイス | IDevice | 出力デバイスです。 |
| ドキュメント | TSource | ドキュメントです。 |

### 関連項目

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, TimeSpan) {#render_5}

指定された[`IDevice`](../../idevice/)に !:TDocument をレンダリングするメソッドを定義します。リソースの読み込み、アクティブなタイマー、アニメーションタスクのネットワーク操作がなくなり、指定されたタイムアウトが経過した時点でレンダリングが実行されます。

```java
public void Render(IDevice device, TSource source, TimeSpan timeout)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| デバイス | IDevice | 出力デバイスです。 |
| ドキュメント | TSource | ドキュメントです。 |
| タイムアウト | TimeSpan | 待機するミリ秒数を表す TimeSpan、または無期限に待機することを表す -1 ミリ秒の TimeSpan を表します。 |

### 関連項目

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TSource, int) {#render_4}

指定された[`IDevice`](../../idevice/)に !:TDocument をレンダリングするメソッドを定義します。リソースの読み込み、アクティブなタイマー、アニメーションタスクのネットワーク操作がなくなり、指定されたタイムアウトが経過した時点でレンダリングが実行されます。

```java
public void Render(IDevice device, TSource source, int timeout)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| デバイス | IDevice | 出力デバイスです。 |
| ドキュメント | TSource | ドキュメントです。 |
| タイムアウト | Int32 | 待機するミリ秒数を表す数値、または無期限に待機することを表す -1 ミリ秒です。 |

### 関連項目

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, params TSource[]) {#render_6}

```java
public void Render(IDevice device, params TSource[] sources)
```

### 関連項目

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, int, params TSource[]) {#render}

```java
public void Render(IDevice device, int timeout, params TSource[] sources)
```

### 関連項目

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, TimeSpan, params TSource[]) {#render_2}

```java
public abstract void Render(IDevice device, TimeSpan timeout, params TSource[] sources)
```

### 関連項目

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)

---

## Render(IDevice, CancellationToken, params TSource[]) {#render_1}

```java
public abstract void Render(IDevice device, CancellationToken cancellationToken, 
    params TSource[] sources)
```

### 関連項目

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* package [com.aspose.html.rendering](../../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../../)
