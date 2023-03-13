---
title: Document.Navigate
second_title: Справочник по Aspose.HTML для .NET API
description: Document метод. Загружает документ по указанному универсальному указателю ресурсов URL в текущий экземпляр заменяя предыдущее содержимое.
type: docs
weight: 1010
url: /ru/net/aspose.html.dom/document/navigate/
---
## Navigate(string) {#navigate_4}

Загружает документ по указанному универсальному указателю ресурсов (URL) в текущий экземпляр, заменяя предыдущее содержимое.

```csharp
public void Navigate(string address)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| address | String | Адрес документа. Он будет объединен с текущим путем к каталогу для формирования абсолютного URL-адреса. |

### Смотрите также

* class [Document](../)
* пространство имен [Aspose.Html.Dom](../../document/)
* сборка [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

Загружает документ по указанному универсальному указателю ресурсов (URL) в текущий экземпляр, заменяя предыдущее содержимое.

```csharp
public void Navigate(Url url)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL-адрес документа. |

### Смотрите также

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* пространство имен [Aspose.Html.Dom](../../document/)
* сборка [Aspose.HTML](../../../)

---

## Navigate(string, string) {#navigate_6}

Загружает документ из указанного содержимого и использует baseUri для разрешения относительных ресурсов, заменяя предыдущее содержимое.

```csharp
public void Navigate(string content, string baseUri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | String | Содержание документа. |
| baseUri | String | Базовый URI для разрешения относительных ресурсов. Он будет объединен с текущим путем к каталогу для формирования абсолютного URL-адреса. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | `baseUri` является`нулевой`. |

### Смотрите также

* class [Document](../)
* пространство имен [Aspose.Html.Dom](../../document/)
* сборка [Aspose.HTML](../../../)

---

## Navigate(string, Url) {#navigate_5}

Загружает документ из указанного содержимого и использует baseUri для разрешения относительных ресурсов, заменяя предыдущее содержимое.

```csharp
public void Navigate(string content, Url baseUri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | String | Содержание документа. |
| baseUri | Url | Базовый URI для разрешения относительных ресурсов. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | `baseUri` является`нулевой`. |

### Смотрите также

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* пространство имен [Aspose.Html.Dom](../../document/)
* сборка [Aspose.HTML](../../../)

---

## Navigate(Stream, string) {#navigate_3}

Загружает документ из указанного содержимого и использует baseUri для разрешения относительных ресурсов, заменяя предыдущее содержимое. Загрузка документа начинается с текущей позиции в потоке.

```csharp
public void Navigate(Stream content, string baseUri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | Stream | Содержание документа. |
| baseUri | String | Базовый URI для разрешения относительных ресурсов. Он будет объединен с текущим путем к каталогу для формирования абсолютного URL-адреса. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | `baseUri` является`нулевой`. |

### Смотрите также

* class [Document](../)
* пространство имен [Aspose.Html.Dom](../../document/)
* сборка [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

Загружает документ из указанного содержимого и использует baseUri для разрешения относительных ресурсов, заменяя предыдущее содержимое. Загрузка документа начинается с текущей позиции в потоке.

```csharp
public void Navigate(Stream content, Url baseUri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | Stream | Содержание документа. |
| baseUri | Url | Базовый URI для разрешения относительных ресурсов. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | `baseUri` является`нулевой`. |

### Смотрите также

* class [Url](../../../aspose.html/url/)
* class [Document](../)
* пространство имен [Aspose.Html.Dom](../../document/)
* сборка [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

Загружает документ на основе указанного объекта запроса, заменяя предыдущее содержимое.

```csharp
public void Navigate(RequestMessage request)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| request | RequestMessage | Объект запроса, который используется для загрузки содержимого документа. |

### Смотрите также

* class [RequestMessage](../../../aspose.html.net/requestmessage/)
* class [Document](../)
* пространство имен [Aspose.Html.Dom](../../document/)
* сборка [Aspose.HTML](../../../)


