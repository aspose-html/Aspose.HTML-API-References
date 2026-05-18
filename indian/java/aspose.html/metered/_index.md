---
title: "Metered क्लास"
second_title: "Aspose.HTML for Java API संदर्भ"
description: "com.aspose.html.Metered क्लास। मीटर की सेट करने के लिए मेथड्स प्रदान करता है।"
type: docs

url: /hi/java/com.aspose.html/metered/
---
## Metered class

मीटर की कुंजी सेट करने के लिए मेथड्स प्रदान करता है।

```java
public class Metered
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Metered](metered/)() | इस क्लास का एक नया उदाहरण प्रारंभ करता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [setMeteredKey](../../com.aspose.html/metered/setmeteredkey/)(String, String) | मीटर सार्वजनिक और निजी कुंजी सेट करता है। यदि आप मीटर लाइसेंस खरीदते हैं, तो एप्लिकेशन शुरू करने पर इस API को कॉल किया जाना चाहिए, सामान्यतः यह पर्याप्त है। हालांकि, यदि हमेशा उपभोग डेटा अपलोड करने में विफल रहता है और 24 घंटे से अधिक हो जाता है, तो लाइसेंस को मूल्यांकन स्थिति में सेट किया जाएगा; ऐसे मामले से बचने के लिए आपको नियमित रूप से लाइसेंस स्थिति जांचनी चाहिए, यदि यह मूल्यांकन स्थिति है, तो इस API को फिर से कॉल करें। |
| static [GetConsumptionCredit](../../com.aspose.html/metered/getconsumptioncredit/)() | उपभोग क्रेडिट प्राप्त करता है |
| static [GetConsumptionQuantity](../../com.aspose.html/metered/getconsumptionquantity/)() | उपभोग फ़ाइल आकार प्राप्त करता है |
| static [IsMeteredLicensed](../../com.aspose.html/metered/ismeteredlicensed/)() | जाँचें कि मीटर किया गया लाइसेंस प्राप्त है या नहीं |

## उदाहरण

इस उदाहरण में, मीटर किए गए सार्वजनिक और निजी कुंजी सेट करने का प्रयास किया जाएगा

```java
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

घटक jar फ़ाइल:

```java
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### संबंधित देखें

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
