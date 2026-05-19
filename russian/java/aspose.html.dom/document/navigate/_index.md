---
title: "Document.Navigate"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод Document. Загружает документ по указанному URL (Uniform Resource Locator) в текущий экземпляр, заменяя предыдущее содержимое."
type: docs

url: /ru/java/com.aspose.html.dom/document/navigate/
---
## Navigate(String) {#navigate_4}

Загружает документ по указанному универсальному указателю ресурса (URL) в текущий экземпляр, заменяя прежнее содержимое.

```java
public void Navigate(String address)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| адрес | String | Адрес документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |

### См. также

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

Загружает документ по указанному универсальному указателю ресурса (URL) в текущий экземпляр, заменяя прежнее содержимое.

```java
public void Navigate(Url url)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL документа. |

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, String) {#navigate_6}

Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя прежнее содержимое.

```java
public void Navigate(String content, String baseUri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Содержимое документа. |
| baseUri | String | Базовый URI для разрешения относительных ресурсов. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | `baseUri` равно `null`. |

### См. также

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, Url) {#navigate_5}

Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя прежнее содержимое.

```java
public void Navigate(String content, Url baseUri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | String | Содержимое документа. |
| baseUri | Url | Базовый URI для разрешения относительных ресурсов. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | `baseUri` равно `null`. |

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, String) {#navigate_3}

Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя прежнее содержимое. Загрузка документа начинается с текущей позиции в потоке.

```java
public void Navigate(Stream content, String baseUri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | Поток | Содержимое документа. |
| baseUri | String | Базовый URI для разрешения относительных ресурсов. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | `baseUri` равно `null`. |

### См. также

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя прежнее содержимое. Загрузка документа начинается с текущей позиции в потоке.

```java
public void Navigate(Stream content, Url baseUri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| содержимое | Поток | Содержимое документа. |
| baseUri | Url | Базовый URI для разрешения относительных ресурсов. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | `baseUri` равно `null`. |

### См. также

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

Загружает документ на основе указанного объекта запроса, заменяя предыдущее содержимое.

```java
public void Navigate(RequestMessage request)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| запрос | RequestMessage | Объект запроса, используемый для загрузки содержимого документа. |

### См. также

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
