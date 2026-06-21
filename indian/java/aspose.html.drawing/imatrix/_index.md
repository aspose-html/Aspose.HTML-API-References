---
title: "IMatrix इंटरफ़ेस"
second_title: "Aspose.HTML Java के लिए API संदर्भ"
description: "com.aspose.html.drawing.IMatrix इंटरफ़ेस। ट्रांसफ़ॉर्मेशन के लिए उपयोग किए जाने वाले मैट्रिक्स का प्रतिनिधित्व करता है"
type: docs

url: /hi/java/com.aspose.html.drawing/imatrix/
---
## IMatrix interface

रूपांतरणों के लिए उपयोग किए जाने वाले मैट्रिक्स का प्रतिनिधित्व करता है।

```java
public interface IMatrix
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [getIsIdentity](../../com.aspose.html.drawing/imatrix/isidentity/) एक मान प्राप्त करता है जो दर्शाता है कि यह मैट्रिक्स पहचान मैट्रिक्स है या नहीं। |
| [getIsInvertible](../../com.aspose.html.drawing/imatrix/isinvertible/) एक मान प्राप्त करता है जो दर्शाता है कि यह मैट्रिक्स उलटा (invertible) है या नहीं। |
[getM11]
[setM11] Gets or sets the value in the first row and first column of the matrix. |
[getM12]
[setM12] Gets or sets the value in the first row and second column of the matrix. |
[getM21]
[setM21] Gets or sets the value in the second row and first column of the matrix. |
[getM22]
[setM22] Gets or sets the value in the second row and second column of the matrix. |
[getM31]
[setM31] Gets or sets the value in the third row and first column of the matrix. |
[getM32]
[setM32] Gets or sets the value in the third row and second column of the matrix. |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [clone](../../com.aspose.html.drawing/imatrix/clone/)() | इस मैट्रिक्स की एक कॉपी बनाता है। |
| [getElements](../../com.aspose.html.drawing/imatrix/getelements/)() | मैट्रिक्स के तत्वों को एक एरे के रूप में प्राप्त करता है। |
| [invert](../../com.aspose.html.drawing/imatrix/invert/)() | इस मैट्रिक्स को उलटता है। |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply)(IMatrix) | इस मैट्रिक्स को दूसरे मैट्रिक्स से गुणा करता है। |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply_1)(IMatrix, WebMatrixOrder) | निर्दिष्ट क्रम में इस मैट्रिक्स को दूसरे मैट्रिक्स से गुणा करता है। |
| [reset](../../com.aspose.html.drawing/imatrix/reset/)() | मैट्रिक्स को पहचान (identity) मैट्रिक्स पर रीसेट करता है। |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate)(float) | निर्दिष्ट कोण द्वारा मैट्रिक्स को घुमाता है। |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate_1)(float, WebMatrixOrder) | निर्दिष्ट क्रम में निर्दिष्ट कोण द्वारा मैट्रिक्स को घुमाता है। |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat)(float, PointF) | निर्दिष्ट बिंदु के चारों ओर निर्दिष्ट कोण द्वारा मैट्रिक्स को घुमाता है। |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat_1)(float, PointF, WebMatrixOrder) | निर्दिष्ट क्रम में निर्दिष्ट बिंदु के चारों ओर निर्दिष्ट कोण द्वारा मैट्रिक्स को घुमाता है। |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale)(float, float) | निर्दिष्ट स्केल कारकों द्वारा मैट्रिक्स को समान रूप से स्केल करता है। |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale_1)(float, float, WebMatrixOrder) | निर्दिष्ट क्रम में निर्दिष्ट स्केल कारकों द्वारा मैट्रिक्स को स्केल करता है। |
| [skew](../../com.aspose.html.drawing/imatrix/skew/)(float, float) | मैट्रिक्स पर एक स्क्यू ट्रांसफ़ॉर्मेशन लागू करता है। |
| [transformPoint](../../com.aspose.html.drawing/imatrix/transformpoint/)(PointF) | इस मैट्रिक्स का उपयोग करके निर्दिष्ट बिंदु को ट्रांसफ़ॉर्म करता है। |
| [transformPoints](../../com.aspose.html.drawing/imatrix/transformpoints/)(PointF[]) | इस मैट्रिक्स का उपयोग करके बिंदुओं की एक एरे को ट्रांसफ़ॉर्म करता है। |
| [transformRectangle](../../com.aspose.html.drawing/imatrix/transformrectangle/)(RectangleF) | इस मैट्रिक्स का उपयोग करके निर्दिष्ट आयत को ट्रांसफ़ॉर्म करता है। |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate)(float, float) | निर्दिष्ट ऑफ़सेट मानों द्वारा मैट्रिक्स को ट्रांसलेट करता है। |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate_1)(float, float, WebMatrixOrder) | निर्दिष्ट क्रम में निर्दिष्ट ऑफ़सेट मानों द्वारा मैट्रिक्स को ट्रांसलेट करता है। |

### संबंधित देखें

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
