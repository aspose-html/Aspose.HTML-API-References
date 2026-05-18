---
title: "SVGDocument.Save"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "SVGDocument मेथड। दस्तावेज़ को स्थानीय फ़ाइल में सहेजता है जो url द्वारा निर्दिष्ट है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधन निकटवर्ती फ़ोल्डर में सहेजे जाएंगे जिसका नाम output_file_name _files के रूप में निर्मित होगा"
type: docs

url: /hi/java/com.aspose.html.dom.svg/svgdocument/save/
---
## Save(Url) {#save_3}

`url` द्वारा निर्दिष्ट स्थानीय फ़ाइल में दस्तावेज़ को सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधन एक सन्निहित फ़ोल्डर में सहेजे जाएंगे, जिसका नाम इस प्रकार बनाया जाएगा: output_file_name + "_files"।

```java
public void Save(Url url)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | आउटपुट फ़ाइल के लिए स्थानीय URL। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | यदि निर्दिष्ट `url` एक वैध स्थानीय फ़ाइल URL नहीं है तो यह उत्पन्न होता है। |

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String) {#save_6}

`path` द्वारा निर्दिष्ट स्थानीय फ़ाइल में दस्तावेज़ को सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधन एक सन्निहित फ़ोल्डर में सहेजे जाएंगे, जिसका नाम इस प्रकार बनाया जाएगा: output_file_name + "_files"।

```java
public void Save(String path)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| पथ | String | आउटपुट फ़ाइल का स्थानीय पथ। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | यदि निर्दिष्ट `path` एक वैध स्थानीय फ़ाइल पथ नहीं है तो यह उत्पन्न होता है। |

### संबंधित देखें

* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler) {#save}

दस्तावेज़ की सामग्री और संसाधनों को [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/) का उपयोग करके सहेजता है।

```java
public void Save(ResourceHandler resourceHandler)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| resourceHandler | ResourceHandler | संसाधन हैंडलर [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)। |

### संबंधित देखें

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String, SVGSaveFormat) {#save_7}

`path` द्वारा निर्दिष्ट स्थानीय फ़ाइल में दस्तावेज़ को सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधन एक सन्निहित फ़ोल्डर में सहेजे जाएंगे, जिसका नाम इस प्रकार बनाया जाएगा: output_file_name + "_files"।

```java
public void Save(String path, SVGSaveFormat saveFormat)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| पथ | String | आउटपुट फ़ाइल का स्थानीय पथ। |
| saveFormat | SVGSaveFormat | दस्तावेज़ जिस प्रारूप में सहेजा जाता है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | यदि निर्दिष्ट `path` एक वैध स्थानीय फ़ाइल पथ नहीं है तो यह उत्पन्न होता है। |

### संबंधित देखें

* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, SVGSaveFormat) {#save_1}

दस्तावेज़ की सामग्री और संसाधनों को [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/) का उपयोग करके सहेजता है।

```java
public void Save(ResourceHandler resourceHandler, SVGSaveFormat saveFormat)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| resourceHandler | ResourceHandler | संसाधन हैंडलर [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)। |
| saveFormat | SVGSaveFormat | दस्तावेज़ जिस प्रारूप में सहेजा जाता है। |

### संबंधित देखें

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(String, SVGSaveOptions) {#save_8}

`path` द्वारा निर्दिष्ट स्थानीय फ़ाइल में दस्तावेज़ को सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधन एक सन्निहित फ़ोल्डर में सहेजे जाएंगे, जिसका नाम इस प्रकार बनाया जाएगा: output_file_name + "_files"।

```java
public void Save(String path, SVGSaveOptions saveOptions)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| पथ | String | आउटपुट फ़ाइल का स्थानीय पथ। |
| saveOptions | SVGSaveOptions | SVG सहेजने के विकल्प। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | यदि निर्दिष्ट `path` एक वैध स्थानीय फ़ाइल पथ नहीं है तो यह उत्पन्न होता है। |

### संबंधित देखें

* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(ResourceHandler, SVGSaveOptions) {#save_2}

दस्तावेज़ की सामग्री और संसाधनों को [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/) का उपयोग करके सहेजता है।

```java
public void Save(ResourceHandler resourceHandler, SVGSaveOptions saveOptions)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| resourceHandler | ResourceHandler | संसाधन हैंडलर [`ResourceHandler`](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)। |
| saveOptions | SVGSaveOptions | SVG सहेजने के विकल्प। |

### संबंधित देखें

* class [ResourceHandler](../../../com.aspose.html.saving.resourcehandlers/resourcehandler/)
* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveFormat) {#save_4}

`url` द्वारा निर्दिष्ट स्थानीय फ़ाइल में दस्तावेज़ को सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधन एक सन्निहित फ़ोल्डर में सहेजे जाएंगे, जिसका नाम इस प्रकार बनाया जाएगा: output_file_name + "_files"।

```java
public void Save(Url url, SVGSaveFormat saveFormat)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | आउटपुट फ़ाइल के लिए स्थानीय URL। |
| saveFormat | SVGSaveFormat | दस्तावेज़ जिस प्रारूप में सहेजा जाता है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | यदि निर्दिष्ट `url` एक वैध स्थानीय फ़ाइल URL नहीं है तो यह उत्पन्न होता है। |

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* enum [SVGSaveFormat](../../../com.aspose.html.dom.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)

---

## Save(Url, SVGSaveOptions) {#save_5}

`url` द्वारा निर्दिष्ट स्थानीय फ़ाइल में दस्तावेज़ को सहेजता है। इस दस्तावेज़ में उपयोग किए गए सभी संसाधन एक सन्निहित फ़ोल्डर में सहेजे जाएंगे, जिसका नाम इस प्रकार बनाया जाएगा: output_file_name + "_files"।

```java
public void Save(Url url, SVGSaveOptions saveOptions)
```

| Parameter | Type | विवरण |
| --- | --- | --- |
| url | Url | आउटपुट फ़ाइल के लिए स्थानीय URL। |
| saveOptions | SVGSaveOptions | SVG सहेजने के विकल्प। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentException | यदि निर्दिष्ट `url` एक वैध स्थानीय फ़ाइल URL नहीं है तो यह उत्पन्न होता है। |

### संबंधित देखें

* class [Url](../../../com.aspose.html/url/)
* class [SVGSaveOptions](../../../com.aspose.html.dom.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
