---
title: "HTMLDocument"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "HTMLDocument कंस्ट्रक्टर। HTMLDocument कंस्ट्रक्टर एक नया HTML Document ऑब्जेक्ट बनाता है जो ब्राउज़र में लोड किया गया वेब पेज है और पृष्ठ की सामग्री में प्रवेश बिंदु के रूप में कार्य करता है।"
type: docs

url: /hi/java/com.aspose.html/htmldocument/htmldocument/
---
## HTMLDocument() {#constructor}

HTMLDocument कंस्ट्रक्टर एक नया HTML Document ऑब्जेक्ट बनाता है जो ब्राउज़र में लोड किया गया वेब पेज है और पेज की सामग्री में प्रवेश बिंदु के रूप में कार्य करता है।

```java
public HTMLDocument()
```

## Remarks

नोट: दस्तावेज़ को base-url प्रॉपर्टी के लिए डिफ़ॉल्ट मान 'about:blank' के साथ बनाया गया है।

संदर्भ:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## उदाहरण

एक बार दस्तावेज़ ऑब्जेक्ट बन जाने के बाद, इसे बाद में HTML तत्वों से भरा जा सकता है। निम्नलिखित कोड स्निपेट डिफ़ॉल्ट HTMLDocument() कंस्ट्रक्टर के उपयोग को दिखाता है ताकि एक खाली HTML दस्तावेज़ बनाया जा सके और उसे फ़ाइल में सहेजा जा सके।

```java
import (var document = new HTMLDocument())
{
	// यहाँ दस्तावेज़ के साथ काम करें
	...	
	
	// दस्तावेज़ को फ़ाइल में सहेजें
	document.Save("document.html");
}
```

### संबंधित देखें

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Configuration) {#constructor_1}

HTMLDocument कंस्ट्रक्टर एक नया HTML Document ऑब्जेक्ट बनाता है जो ब्राउज़र में लोड किया गया वेब पेज है और पेज की सामग्री में प्रवेश बिंदु के रूप में कार्य करता है।

```java
public HTMLDocument(Configuration configuration)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| कॉन्फ़िगरेशन | कॉन्फ़िगरेशन | पर्यावरण कॉन्फ़िगरेशन जैसे स्क्रिप्ट नीति, कस्टम उपयोगकर्ता स्टाइलशीट, आदि। |

## Remarks

नोट: दस्तावेज़ को base-url प्रॉपर्टी के लिए डिफ़ॉल्ट मान 'about:blank' के साथ बनाया गया है।

संदर्भ:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## उदाहरण

निम्नलिखित उदाहरण दिखाता है कि स्क्रिप्ट को निष्क्रिय करने के लिए कॉन्फ़िगरेशन ऑब्जेक्ट का उपयोग कैसे किया जाए:

```java
// HTML कोड तैयार करें और इसे फ़ाइल में सहेजें
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Configuration का एक उदाहरण बनाएं
import (var configuration = new Configuration())
{
	// 'scripts' को एक अविश्वसनीय संसाधन के रूप में चिह्नित करें
	configuration.Security |= Sandbox.Scripts;

	// निर्दिष्ट कॉन्फ़िगरेशन के साथ एक HTML दस्तावेज़ प्रारंभ करें
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// HTML को PDF में परिवर्तित करें
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### संबंधित देखें

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url) {#constructor_4}

एक URL से HTML दस्तावेज़ लोड करता है।

नोट: यदि आप कोई गलत URL पास करते हैं जो इस क्षण पहुँच योग्य नहीं है, तो लाइब्रेरी [`DOMException`](../../../com.aspose.html.dom/domexception/) को विशेष कोड ‘NetworkError’ के साथ थ्रो करती है ताकि आपको सूचित किया जा सके कि चयनित संसाधन नहीं मिला।

```java
public HTMLDocument(Url url)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| url | Url | खोलने के लिए HTML दस्तावेज़ URL। |

## Remarks

संदर्भ:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## उदाहरण

‘https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html’ वेब पेज से दस्तावेज़ लोड करें:

```java
import (var document = new HTMLDocument("https://docs.aspose.com/html/net/working-with-documents/creating-a-document/document.html"))
{
	// दस्तावेज़ की सामग्री को आउटपुट स्ट्रीम में लिखें
	Console.WriteLine(document.DocumentElement.OuterHTML);
}
```

### संबंधित देखें

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Url, Configuration) {#constructor_5}

निर्दिष्ट पर्यावरण कॉन्फ़िगरेशन सेटिंग्स के साथ एक URL से HTML दस्तावेज़ लोड करता है।

नोट: यदि आप कोई गलत URL पास करते हैं जो इस क्षण पहुँच योग्य नहीं है, तो लाइब्रेरी [DOMException](T:com.aspose.html.dom.DOMException) को विशेष कोड ‘NetworkError’ के साथ थ्रो करती है ताकि आपको सूचित किया जा सके कि चयनित संसाधन नहीं मिला।

```java
public HTMLDocument(Url url, Configuration configuration)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| url | Url | खोलने के लिए HTML दस्तावेज़ URL। |
| कॉन्फ़िगरेशन | कॉन्फ़िगरेशन | पर्यावरण कॉन्फ़िगरेशन जैसे स्क्रिप्ट नीति, कस्टम उपयोगकर्ता स्टाइलशीट, आदि। |

## Remarks

संदर्भ:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## उदाहरण

```java
The following example demonstrates how to use the configuration object to disable scripts:

// HTML कोड तैयार करें और इसे फ़ाइल में सहेजें
var code = "<span>Hello World!!</span> " +
		   "<script>document.write('Have a nice day!');</script>";

File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

// Configuration का एक उदाहरण बनाएं
import (var configuration = new Configuration())
{
	// 'scripts' को एक अविश्वसनीय संसाधन के रूप में चिह्नित करें
	configuration.Security |= Sandbox.Scripts;

	// निर्दिष्ट कॉन्फ़िगरेशन के साथ एक HTML दस्तावेज़ प्रारंभ करें
	using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
	{
		// HTML को PDF में परिवर्तित करें
		Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
	}
}
```

### संबंधित देखें

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String) {#constructor_10}

एक पते से HTML दस्तावेज़ लोड करता है।

नोट: यदि आप कोई गलत URL पास करते हैं जो इस क्षण पहुँच योग्य नहीं है, तो लाइब्रेरी [`DOMException`](../../../com.aspose.html.dom/domexception/) को विशेष कोड ‘NetworkError’ के साथ थ्रो करती है ताकि आपको सूचित किया जा सके कि चयनित संसाधन नहीं मिला।

```java
public HTMLDocument(String address)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| पता | String | खोलने के लिए HTML दस्तावेज़ पता। |

## Remarks

संदर्भ:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## उदाहरण

पते से एक HTML दस्तावेज़ प्रारंभ करें।

```java
import (var document = new HTMLDocument("./my-folder/document.html")))
{
	...
}
```

### संबंधित देखें

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Configuration) {#constructor_11}

निर्दिष्ट पर्यावरण कॉन्फ़िगरेशन सेटिंग्स के साथ एक पते से HTML दस्तावेज़ लोड करता है।

नोट: यदि आप कोई गलत URL पास करते हैं जो इस क्षण पहुँच योग्य नहीं है, तो लाइब्रेरी [`DOMException`](../../../com.aspose.html.dom/domexception/) को विशेष कोड ‘NetworkError’ के साथ थ्रो करती है ताकि आपको सूचित किया जा सके कि चयनित संसाधन नहीं मिला।

```java
public HTMLDocument(String address, Configuration configuration)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| पता | String | खोलने के लिए HTML दस्तावेज़ पता। |
| कॉन्फ़िगरेशन | कॉन्फ़िगरेशन | पर्यावरण कॉन्फ़िगरेशन जैसे स्क्रिप्ट नीति, कस्टम उपयोगकर्ता स्टाइलशीट, आदि। |

## Remarks

संदर्भ:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## उदाहरण

```java
// Configuration का एक उदाहरण बनाएं
import (var configuration = new Configuration())
{
	// 'scripts' को एक अविश्वसनीय संसाधन के रूप में चिह्नित करें
	configuration.Security |= Sandbox.Scripts;
	
	using (var document = new HTMLDocument("./my-folder/document.html", configuration)))
	{
		...
	}
}
```

### संबंधित देखें

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String) {#constructor_14}

निर्दिष्ट base-uri के साथ एक String सामग्री से HTML दस्तावेज़ बनाता है।

```java
public HTMLDocument(String content, String baseUri)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| सामग्री | String | दस्तावेज़ लोड करने के लिए String सामग्री। |
| baseUri | String | दस्तावेज़ का बेस URI। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | यदि base-uri पैरामीटर null है तो थ्रो करता है। |

## Remarks

संदर्भ:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## उदाहरण

```java
// HTML कोड तैयार करें
var html_code = "<p>Hello World!</p>";

// String वेरिएबल से दस्तावेज़ को इनिशियलाइज़ करें
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### संबंधित देखें

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, String, Configuration) {#constructor_15}

निर्दिष्ट base-uri और पर्यावरण कॉन्फ़िगरेशन सेटिंग्स के साथ एक String सामग्री से HTML दस्तावेज़ बनाता है।

```java
public HTMLDocument(String content, String baseUri, Configuration configuration)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| सामग्री | String | दस्तावेज़ लोड करने के लिए String सामग्री। |
| baseUri | String | दस्तावेज़ का बेस URI। |
| कॉन्फ़िगरेशन | कॉन्फ़िगरेशन | पर्यावरण कॉन्फ़िगरेशन जैसे स्क्रिप्ट नीति, कस्टम उपयोगकर्ता स्टाइलशीट, आदि। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | यदि base-uri पैरामीटर null है तो थ्रो करता है। |

## Remarks

संदर्भ:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## उदाहरण

```java
// HTML कोड तैयार करें
var html_code = "<p>Hello World!</p>";

// String वेरिएबल से दस्तावेज़ को इनिशियलाइज़ करें
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### संबंधित देखें

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url) {#constructor_12}

निर्दिष्ट base-uri के साथ एक String सामग्री से HTML दस्तावेज़ बनाता है।

```java
public HTMLDocument(String content, Url baseUri)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| सामग्री | String | दस्तावेज़ लोड करने के लिए String सामग्री। |
| baseUri | Url | दस्तावेज़ का बेस URI। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | यदि base-uri पैरामीटर null है तो थ्रो करता है। |

## Remarks

संदर्भ:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## उदाहरण

```java
// HTML कोड तैयार करें
var html_code = "<p>Hello World!</p>";

// String वेरिएबल से दस्तावेज़ को इनिशियलाइज़ करें
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### संबंधित देखें

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(String, Url, Configuration) {#constructor_13}

निर्दिष्ट base-uri और पर्यावरण कॉन्फ़िगरेशन सेटिंग्स के साथ एक String सामग्री से HTML दस्तावेज़ बनाता है।

```java
public HTMLDocument(String content, Url baseUri, Configuration configuration)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| सामग्री | String | दस्तावेज़ लोड करने के लिए String सामग्री। |
| baseUri | Url | दस्तावेज़ का बेस URI। |
| कॉन्फ़िगरेशन | कॉन्फ़िगरेशन | पर्यावरण कॉन्फ़िगरेशन जैसे स्क्रिप्ट नीति, कस्टम उपयोगकर्ता स्टाइलशीट, आदि। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | यदि base-uri पैरामीटर null है तो थ्रो करता है। |

## Remarks

संदर्भ:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## उदाहरण

```java
// HTML कोड तैयार करें
var html_code = "<p>Hello World!</p>";

// String वेरिएबल से दस्तावेज़ को इनिशियलाइज़ करें
import (var document = new HTMLDocument(html_code, "."))
{
	...
}
```

### संबंधित देखें

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String) {#constructor_8}

[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) सामग्री से एक HTML दस्तावेज़ बनाता है, जिसमें निर्दिष्ट base-uri का उपयोग सापेक्ष संसाधनों के पथ को हल करने के लिए किया जाता है।

```java
public HTMLDocument(Stream content, String baseUri)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| content | Stream | दस्तावेज़ लोड करने के लिए [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) सामग्री। |
| baseUri | String | दस्तावेज़ का बेस URI। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | यदि base-uri पैरामीटर null है तो थ्रो करता है। |

## Remarks

संदर्भ:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## उदाहरण

```java
// एक मेमोरी स्ट्रीम ऑब्जेक्ट बनाएं
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// HTML कोड को मेमोरी ऑब्जेक्ट में लिखें
	sw.Write("<p>Hello World! I love HTML!</p>");

	// It is important to set the position to the beginning since HTMLDocument starts the reading exactly from the current position within the stream
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// String वेरिएबल से दस्तावेज़ को इनिशियलाइज़ करें
	using (var document = new HTMLDocument(mem, "."))
	{
		// Save the document to a disk
		document.Save("load-from-stream.html");
	}
}
```

### संबंधित देखें

* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, String, Configuration) {#constructor_9}

[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) सामग्री से एक HTML दस्तावेज़ बनाता है, जिसमें निर्दिष्ट base-uri और पर्यावरण कॉन्फ़िगरेशन सेटिंग्स शामिल हैं।

```java
public HTMLDocument(Stream content, String baseUri, Configuration configuration)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| content | Stream | दस्तावेज़ लोड करने के लिए [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) सामग्री। |
| baseUri | String | दस्तावेज़ का बेस URI। |
| कॉन्फ़िगरेशन | कॉन्फ़िगरेशन | पर्यावरण कॉन्फ़िगरेशन जैसे स्क्रिप्ट नीति, कस्टम उपयोगकर्ता स्टाइलशीट, आदि। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | यदि base-uri पैरामीटर null है तो थ्रो करता है। |

## Remarks

संदर्भ:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## उदाहरण

```java
// एक मेमोरी स्ट्रीम ऑब्जेक्ट बनाएं
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// HTML कोड को मेमोरी ऑब्जेक्ट में लिखें
	sw.Write("<p>Hello World! I love HTML!</p>");

	// It is important to set the position to the beginning since HTMLDocument starts the reading exactly from the current position within the stream
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// String वेरिएबल से दस्तावेज़ को इनिशियलाइज़ करें
	using (var document = new HTMLDocument(mem, "."))
	{
		// Save the document to a disk
		document.Save("load-from-stream.html");
	}
}
```

### संबंधित देखें

* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url) {#constructor_6}

[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) सामग्री से एक HTML दस्तावेज़ बनाता है, जिसमें निर्दिष्ट base-uri का उपयोग सापेक्ष संसाधनों के पथ को हल करने के लिए किया जाता है।

```java
public HTMLDocument(Stream content, Url baseUri)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| content | Stream | दस्तावेज़ लोड करने के लिए [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) सामग्री। |
| baseUri | Url | दस्तावेज़ का बेस URI। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | यदि base-uri पैरामीटर null है तो थ्रो करता है। |

## Remarks

संदर्भ:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## उदाहरण

```java
// एक मेमोरी स्ट्रीम ऑब्जेक्ट बनाएं
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// HTML कोड को मेमोरी ऑब्जेक्ट में लिखें
	sw.Write("<p>Hello World! I love HTML!</p>");

	// It is important to set the position to the beginning since HTMLDocument starts the reading exactly from the current position within the stream
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// String वेरिएबल से दस्तावेज़ को इनिशियलाइज़ करें
	using (var document = new HTMLDocument(mem, "."))
	{
		// Save the document to a disk
		document.Save("load-from-stream.html");
	}
}
```

### संबंधित देखें

* class [Url](../../url/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(Stream, Url, Configuration) {#constructor_7}

[Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) सामग्री से एक HTML दस्तावेज़ बनाता है, जिसमें निर्दिष्ट base-uri और पर्यावरण कॉन्फ़िगरेशन सेटिंग्स शामिल हैं।

```java
public HTMLDocument(Stream content, Url baseUri, Configuration configuration)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| content | Stream | दस्तावेज़ लोड करने के लिए [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) सामग्री। |
| baseUri | Url | दस्तावेज़ का बेस URI। |
| कॉन्फ़िगरेशन | कॉन्फ़िगरेशन | पर्यावरण कॉन्फ़िगरेशन जैसे स्क्रिप्ट नीति, कस्टम उपयोगकर्ता स्टाइलशीट, आदि। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | यदि base-uri पैरामीटर null है तो थ्रो करता है। |

## Remarks

संदर्भ:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## उदाहरण

```java
// एक मेमोरी स्ट्रीम ऑब्जेक्ट बनाएं
import (var mem = new MemoryStream())
import (var sw = new StreamWriter(mem))
{
	// HTML कोड को मेमोरी ऑब्जेक्ट में लिखें
	sw.Write("<p>Hello World! I love HTML!</p>");

	// It is important to set the position to the beginning since HTMLDocument starts the reading exactly from the current position within the stream
	sw.Flush();
	mem.Seek(0, SeekOrigin.Begin);

	// String वेरिएबल से दस्तावेज़ को इनिशियलाइज़ करें
	using (var document = new HTMLDocument(mem, "."))
	{
		// Save the document to a disk
		document.Save("load-from-stream.html");
	}
}
```

### संबंधित देखें

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage) {#constructor_2}

Creates an HTML document from the [`RequestMessage`](../../../com.aspose.html.net/requestmessage/) object.

```java
public HTMLDocument(RequestMessage request)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| request | RequestMessage | The request message that contains a [`body`](../../../com.aspose.html.net/requestmessage/content/) with document content. |

## Remarks

By definition, a message handler is a class that receives a Web request and returns a Web response. In other words, a message handler is used to process a Web service request during input and/or to process the response during output.

Please, visit our [docs site](https://docs.aspose.com/html/net/message-handlers/) to see more scenarios on how to use this constructor.

संदर्भ:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### संबंधित देखें

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## HTMLDocument(RequestMessage, Configuration) {#constructor_3}

[RequestMessage](T:com.aspose.html.net.RequestMessage) ऑब्जेक्ट से एक HTML दस्तावेज़ बनाता है।

```java
public HTMLDocument(RequestMessage request, Configuration configuration)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| request | RequestMessage | The request message that contains a [body](P:com.aspose.html.net.RequestMessage.Content) with document content. |
| कॉन्फ़िगरेशन | कॉन्फ़िगरेशन | पर्यावरण कॉन्फ़िगरेशन जैसे स्क्रिप्ट नीति, कस्टम उपयोगकर्ता स्टाइलशीट, आदि। |

## Remarks

By definition, a message handler is a class that receives a Web request and returns a Web response. In other words, a message handler is used to process a Web service request during input and/or to process the response during output.

Please, visit our [docs site](https://docs.aspose.com/html/net/message-handlers/) to see more scenarios on how to use this constructor.

संदर्भ:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### संबंधित देखें

* class [RequestMessage](../../../com.aspose.html.net/requestmessage/)
* class [Configuration](../../configuration/)
* class [HTMLDocument](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
