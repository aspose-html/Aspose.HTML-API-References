---
title: "RendererTSource क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.rendering.Renderer1TSource क्लास। सभी रेंडरर्स के लिए एक एब्स्ट्रैक्ट क्लास का प्रतिनिधित्व करता है।"
type: docs

url: /hi/java/com.aspose.html.rendering/renderer-1/
---
## Renderer&lt;TSource&gt; class

सभी रेंडरर्स के लिए एक एब्स्ट्रैक्ट क्लास का प्रतिनिधित्व करता है।

```java
public abstract class Renderer<TSource> : Renderer
```

| Parameter | विवरण |
| --- | --- |
| TDocument | दस्तावेज़ का प्रकार। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [dispose](../../com.aspose.html.rendering/renderer/dispose/)() | अप्रबंधित और - वैकल्पिक रूप से - प्रबंधित संसाधनों को रिलीज़ करता है। |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_3)(IDevice, TSource) | निर्दिष्ट [`IDevice`](../idevice/) में !:TDocument को रेंडर करने के लिए मेथड को परिभाषित करता है। |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_6)(IDevice, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_1)(IDevice, CancellationToken, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render)(IDevice, int, params TSource[]) |  |
| abstract [Render](../../com.aspose.html.rendering/renderer-1/render/#render_2)(IDevice, TimeSpan, params TSource[]) |  |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_4)(IDevice, TSource, int) | निर्दिष्ट [`IDevice`](../idevice/) में !:TDocument को रेंडर करने के लिए मेथड को परिभाषित करता है। रेंडरिंग तब की जाएगी जब संसाधनों को लोड करने के लिए कोई नेटवर्क ऑपरेशन, सक्रिय टाइमर, एनीमेशन टास्क न हों या निर्दिष्ट टाइमआउट समाप्त हो गया हो। |
| [render](../../com.aspose.html.rendering/renderer-1/render/#render_5)(IDevice, TSource, TimeSpan) | निर्दिष्ट [`IDevice`](../idevice/) में !:TDocument को रेंडर करने के लिए मेथड को परिभाषित करता है। रेंडरिंग तब की जाएगी जब संसाधनों को लोड करने के लिए कोई नेटवर्क ऑपरेशन, सक्रिय टाइमर, एनीमेशन टास्क न हों या निर्दिष्ट टाइमआउट समाप्त हो गया हो। |

### संबंधित देखें

* class [Renderer](../renderer/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
