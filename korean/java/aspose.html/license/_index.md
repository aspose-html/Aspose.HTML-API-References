---
title: "License 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.License 클래스. 구성 요소에 라이선스를 적용하는 메서드를 제공합니다."
type: docs

url: /ko/java/com.aspose.html/license/
---
## License class

구성 요소에 대한 라이선스를 부여하는 메서드를 제공합니다.

```java
public class License
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [License](license/)() | 이 클래스의 새 인스턴스를 초기화합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense)(Stream) | 구성 요소에 라이선스를 적용합니다. |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense_1)(String) | 구성 요소에 라이선스를 적용합니다. |

## 예제

이 예제에서는 구성 요소가 포함된 폴더, 호출 어셈블리가 포함된 폴더, 진입 어셈블리 폴더, 그리고 호출 어셈블리의 임베디드 리소스에서 MyLicense.lic이라는 라이선스 파일을 찾으려고 시도합니다.

```java
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

구성 요소 jar 파일:

```java
License license = new License();
license.setLicense("MyLicense.lic");
```

### 또 보기

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
