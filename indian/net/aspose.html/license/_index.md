---
title: Class License
second_title: .NET API संदर्भ के लिए Aspose.HTML
description: Aspose.Html.License कक्ष. घटक क लइसेंस देने के तरके प्रदन करत है
type: docs
weight: 3810
url: /hi/net/aspose.html/license/
---
## License class

घटक को लाइसेंस देने के तरीके प्रदान करता है।

```csharp
public class License
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [License](license/)() | इस वर्ग का एक नया उदाहरण आरंभ करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [SetLicense](../../aspose.html/license/setlicense/#setlicense)(Stream) | घटक को लाइसेंस देता है। |
| [SetLicense](../../aspose.html/license/setlicense/#setlicense_1)(string) | घटक को लाइसेंस देता है। |

### उदाहरण

इस उदाहरण में, MyLicense.lic नामक एक लाइसेंस फ़ाइल को फ़ोल्डर में खोजने का प्रयास किया जाएगा जिसमें है घटक, कॉलिंग असेंबली वाले फ़ोल्डर में, एंट्री असेंबली के फ़ोल्डर में और फिर कॉलिंग असेंबली के एम्बेडेड संसाधनों में।

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

घटक जार फ़ाइल:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### यह सभी देखें

* नाम स्थान [Aspose.Html](../../aspose.html/)
* सभा [Aspose.HTML](../../)


