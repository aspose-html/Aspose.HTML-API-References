---
title: "Document.Navigate"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "طريقة Document. تُحمِّل المستند من عنوان URL المحدد (Uniform Resource Locator) إلى النسخة الحالية، مستبدلةً المحتوى السابق."
type: docs

url: /ar/java/com.aspose.html.dom/document/navigate/
---
## Navigate(String) {#navigate_4}

يقوم بتحميل المستند من عنوان الإنترنت (URL) المحدد إلى النسخة الحالية، مستبدلاً المحتوى السابق.

```java
public void Navigate(String address)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العنوان | String | عنوان المستند. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |

### انظر أيضًا

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Url) {#navigate_1}

يقوم بتحميل المستند من عنوان الإنترنت (URL) المحدد إلى النسخة الحالية، مستبدلاً المحتوى السابق.

```java
public void Navigate(Url url)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | Url | عنوان URL للمستند. |

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, String) {#navigate_6}

يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلاً المحتوى السابق.

```java
public void Navigate(String content, String baseUri)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | محتوى المستند. |
| baseUri | String | عنوان URI الأساسي لحل الموارد النسبية. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `baseUri` هو `null`. |

### انظر أيضًا

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(String, Url) {#navigate_5}

يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلاً المحتوى السابق.

```java
public void Navigate(String content, Url baseUri)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | String | محتوى المستند. |
| baseUri | Url | عنوان URI الأساسي لحل الموارد النسبية. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `baseUri` هو `null`. |

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, String) {#navigate_3}

يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلاً المحتوى السابق. يبدأ تحميل المستند من الموضع الحالي في الدفق.

```java
public void Navigate(Stream content, String baseUri)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | دفق | محتوى المستند. |
| baseUri | String | عنوان URI الأساسي لحل الموارد النسبية. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `baseUri` هو `null`. |

### انظر أيضًا

* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(Stream, Url) {#navigate_2}

يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلاً المحتوى السابق. يبدأ تحميل المستند من الموضع الحالي في الدفق.

```java
public void Navigate(Stream content, Url baseUri)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المحتوى | دفق | محتوى المستند. |
| baseUri | Url | عنوان URI الأساسي لحل الموارد النسبية. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `baseUri` هو `null`. |

### انظر أيضًا

* class [Url](../../../com.aspose.html/url/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## Navigate(RequestMessage) {#navigate}

يقوم بتحميل المستند بناءً على كائن الطلب المحدد، مستبدلًا المحتوى السابق.

```java
public void Navigate(RequestMessage request)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| طلب | RequestMessage | كائن الطلب المستخدم لتحميل محتوى المستند. |

### انظر أيضًا

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
