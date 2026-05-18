---
title: "PdfPermissions एनम"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.rendering.pdf.encryption.PdfPermissions एनम। यह एनम PDF के लिए उपयोगकर्ता अनुमतियों को दर्शाता है।"
type: docs

url: /hi/java/com.aspose.html.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

यह enum pdf के लिए उपयोगकर्ता की अनुमतियों का प्रतिनिधित्व करता है।

```java
[Flags]
public enum PdfPermissions
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| PrintDocument | `4` | (Revision 2 के सुरक्षा हैंडलर) दस्तावेज़ प्रिंट करें। (Revision 3 या उससे अधिक के सुरक्षा हैंडलर) दस्तावेज़ प्रिंट करें (संभवतः उच्चतम गुणवत्ता स्तर पर नहीं, यह इस पर निर्भर करता है कि PrintingQuality भी सेट है या नहीं)। |
| ModifyContent | `8` | दस्तावेज़ की सामग्री को उन संचालन द्वारा संशोधित करें जो ModifyTextAnnotations, FillForm, और 11 द्वारा नियंत्रित नहीं हैं। |
| ExtractContent | `10` | (Revision 2 के सुरक्षा हैंडलर) दस्तावेज़ से टेक्स्ट और ग्राफ़िक्स को कॉपी या अन्यथा निकालें, जिसमें टेक्स्ट और ग्राफ़िक्स निकालना (विकलांग उपयोगकर्ताओं की पहुँच समर्थन या अन्य उद्देश्यों के लिए) शामिल है। (Revision 3 या उससे अधिक के सुरक्षा हैंडलर) दस्तावेज़ से टेक्स्ट और ग्राफ़िक्स को उन संचालन द्वारा कॉपी या अन्यथा निकालें जो ExtractContentWithDisabilities द्वारा नियंत्रित नहीं हैं। |
| ModifyTextAnnotations | `20` | टेक्स्ट एनोटेशन जोड़ें या संशोधित करें, इंटरैक्टिव फ़ॉर्म फ़ील्ड भरें, और यदि ModifyContent भी सेट है, तो इंटरैक्टिव फ़ॉर्म फ़ील्ड (सिग्नेचर फ़ील्ड सहित) बनाएं या संशोधित करें। |
| FillForm | `100` | (Revision 3 या उससे अधिक के सुरक्षा हैंडलर) मौजूदा इंटरैक्टिव फ़ॉर्म फ़ील्ड (सिग्नेचर फ़ील्ड सहित) भरें, भले ही ModifyTextAnnotations साफ़ हो। |
| ExtractContentWithDisabilities | `200` | (Revision 3 या उससे अधिक के सुरक्षा हैंडलर) टेक्स्ट और ग्राफ़िक्स निकालें (विकलांग उपयोगकर्ताओं की पहुँच समर्थन या अन्य उद्देश्यों के लिए)। |
| AssembleDocument | `400` | (Revision 3 या उससे अधिक के सुरक्षा हैंडलर) दस्तावेज़ को असेंबल करें (पृष्ठ जोड़ें, घुमाएँ, या हटाएँ और बुकमार्क या थंबनेल इमेज बनाएं), भले ही ModifyContent साफ़ हो। |
| PrintingQuality | `800` | (Revision 3 या उससे अधिक के सुरक्षा हैंडलर) दस्तावेज़ को ऐसी प्रस्तुति में प्रिंट करें जिससे PDF सामग्री की एक सटीक डिजिटल कॉपी बनाई जा सके। जब यह बिट साफ़ हो (और बिट 3 सेट हो), तो प्रिंटिंग को उपस्थिति के निम्न‑स्तरीय प्रतिनिधित्व तक सीमित किया जाता है, संभवतः घटी हुई गुणवत्ता के साथ। |

### संबंधित देखें

* package [com.aspose.html.rendering.pdf.encryption](../../com.aspose.html.rendering.pdf.encryption/)
* package [Aspose.HTML](../../)
