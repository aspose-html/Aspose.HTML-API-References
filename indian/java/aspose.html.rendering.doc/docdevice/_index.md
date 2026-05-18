---
title: "DocDevice Class"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.rendering.doc.DocDevice class. DOCX दस्तावेज़ में रेंडरिंग का प्रतिनिधित्व करता है"
type: docs

url: /hi/java/com.aspose.html.rendering.doc/docdevice/
---
## DocDevice class

DOCX दस्तावेज़ में रेंडरिंग का प्रतिनिधित्व करता है।

```java
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | `DocDevice` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [DocDevice](docdevice/#constructor_4)(Stream) | आउटपुट स्ट्रीम द्वारा `DocDevice` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [DocDevice](docdevice/#constructor_5)(String) | आउटपुट फ़ाइल नाम द्वारा `DocDevice` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | रेंडरिंग विकल्पों और स्ट्रीम प्रोवाइडर द्वारा `DocDevice` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | रेंडरिंग विकल्पों और आउटपुट स्ट्रीम द्वारा `DocDevice` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, String) | रेंडरिंग विकल्पों और आउटपुट फ़ाइल नाम द्वारा `DocDevice` क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [addRect](../../com.aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | वर्तमान पाथ में एक आयत को पूर्ण सबपाथ के रूप में जोड़ता है। |
| [beginDocument](../../com.aspose.html.rendering.doc/docdevice/begindocument/)(Document) | दस्तावेज़ की रेंडरिंग शुरू करता है। |
| [beginElement](../../com.aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | HTML नोड की रेंडरिंग शुरू करता है। |
| [beginPage](../../com.aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | नए पृष्ठ की रेंडरिंग शुरू करता है। |
| [clip](../../com.aspose.html.rendering.doc/docdevice/clip/)(FillRule) | वर्तमान क्लिपिंग पाथ को वर्तमान पाथ के साथ प्रतिच्छेद करके संशोधित करता है, FillMode नियम का उपयोग करके भरने के क्षेत्र को निर्धारित करता है। यह मेथड वर्तमान पाथ को समाप्त करता है। |
| [closePath](../../com.aspose.html.rendering.doc/docdevice/closepath/)() | वर्तमान बिंदु से सबपाथ के प्रारंभिक बिंदु तक एक सीधी रेखा खंड जोड़कर वर्तमान सबपाथ को बंद करता है। यदि वर्तमान सबपाथ पहले से बंद है, तो "ClosePath" कुछ नहीं करता। यह ऑपरेटर वर्तमान सबपाथ को समाप्त करता है। वर्तमान पाथ में एक और खंड जोड़ने से नया सबपाथ शुरू होता है, भले ही नया खंड "ClosePath" मेथड द्वारा पहुँचे अंतिम बिंदु से शुरू हो। |
| [cubicBezierTo](../../com.aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | वर्तमान पाथ में एक क्यूबिक Bézier कर्व जोड़ता है। कर्व वर्तमान बिंदु से बिंदु pt2 तक विस्तारित होता है, जहाँ pt1 और pt2 को Bézier नियंत्रण बिंदु के रूप में उपयोग किया जाता है। नया वर्तमान बिंदु pt3 है। |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() |  |
| [drawImage](../../com.aspose.html.rendering.doc/docdevice/drawimage/)(byte[], WebImageFormat, RectangleF) | निर्दिष्ट छवि को ड्रॉ करता है। |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() |  |
| [endElement](../../com.aspose.html.rendering.doc/docdevice/endelement/)(Element) | HTML नोड की रेंडरिंग समाप्त करता है। |
| [endPage](../../com.aspose.html.rendering.doc/docdevice/endpage/)() | वर्तमान पृष्ठ का रेंडरिंग समाप्त करता है। |
| [fill](../../com.aspose.html.rendering.doc/docdevice/fill/)(FillRule) | वर्तमान पथ द्वारा घिरे पूरे क्षेत्र को भरता है। यदि पथ में कई असंबद्ध उपपथ शामिल हों, तो यह सभी उपपथों के अंदरूनी हिस्सों को साथ में भरता है। यह विधि वर्तमान पथ को समाप्त करती है। |
| [fillText](../../com.aspose.html.rendering.doc/docdevice/filltext/)(String, PointF) | निर्दिष्ट स्थान पर निर्दिष्ट पाठ स्ट्रिंग को भरता है। |
| [flush](../../com.aspose.html.rendering.doc/docdevice/flush/)() | सभी डेटा को आउटपुट स्ट्रीम में फ्लश करता है। |
| [lineTo](../../com.aspose.html.rendering.doc/docdevice/lineto/)(PointF) | वर्तमान बिंदु से बिंदु (pt) तक एक सीधी रेखा खंड जोड़ता है। नया वर्तमान बिंदु pt है। |
| [moveTo](../../com.aspose.html.rendering.doc/docdevice/moveto/)(PointF) | वर्तमान बिंदु को पैरामीटर pt के निर्देशांक पर ले जाकर एक नया उपपथ शुरू करता है, किसी भी जोड़ने वाली रेखा खंड को छोड़ते हुए। यदि वर्तमान पथ में पिछली पथ निर्माण विधि भी "MoveTo" थी, तो नया "MoveTo" उसे अधिलेखित कर देता है; पथ में पिछले "MoveTo" ऑपरेशन का कोई अंश नहीं रहता। |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() |  |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| [stroke](../../com.aspose.html.rendering.doc/docdevice/stroke/)() | वर्तमान पथ के साथ एक रेखा स्ट्रोक करता है। स्ट्रोक की गई रेखा पथ के प्रत्येक सीधी या वक्र खंड का अनुसरण करती है, खंड के केंद्र में स्थित और उसके दोनों ओर समानांतर पक्षों के साथ। पथ के प्रत्येक उपपथ को अलग-अलग माना जाता है। यह विधि वर्तमान पथ को समाप्त करती है। |
| [strokeAndFill](../../com.aspose.html.rendering.doc/docdevice/strokeandfill/)(FillRule) | वर्तमान पथ को स्ट्रोक और भरता है। यह विधि वर्तमान पथ को समाप्त करती है। |
| [strokeText](../../com.aspose.html.rendering.doc/docdevice/stroketext/)(String, PointF) | निर्दिष्ट स्थान पर निर्दिष्ट पाठ स्ट्रिंग को स्ट्रोक करता है। |

## अन्य सदस्य

| नाम | विवरण |
| --- | --- |
| class [DocGraphicContext](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext) | DocDevice के लिए वर्तमान ग्राफ़िक्स नियंत्रण पैरामीटर रखता है। ये पैरामीटर वह वैश्विक ढांचा परिभाषित करते हैं जिसमें ग्राफ़िक्स ऑपरेटर निष्पादित होते हैं। |

### संबंधित देखें

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* package [com.aspose.html.rendering.doc](../../com.aspose.html.rendering.doc/)
* package [Aspose.HTML](../../)
