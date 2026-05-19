---
title: "Metered 클래스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.Metered 클래스. 메터링 키를 설정하는 메서드를 제공합니다."
type: docs

url: /ko/java/com.aspose.html/metered/
---
## Metered class

계량 키를 설정하는 메서드를 제공합니다.

```java
public class Metered
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Metered](metered/)() | 이 클래스의 새 인스턴스를 초기화합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [setMeteredKey](../../com.aspose.html/metered/setmeteredkey/)(String, String) | 메터링 공개 및 개인 키를 설정합니다. 메터링 라이선스를 구매한 경우 애플리케이션 시작 시 이 API를 호출해야 하며, 일반적으로 이것만으로 충분합니다. 그러나 사용량 데이터를 업로드하는 데 지속적으로 실패하고 24시간을 초과하면 라이선스가 평가 상태로 전환됩니다. 이러한 상황을 방지하려면 라이선스 상태를 정기적으로 확인하고, 평가 상태인 경우 이 API를 다시 호출해야 합니다. |
| static [GetConsumptionCredit](../../com.aspose.html/metered/getconsumptioncredit/)() | 소비 크레딧을 가져옵니다 |
| static [GetConsumptionQuantity](../../com.aspose.html/metered/getconsumptionquantity/)() | 소비 파일 크기를 가져옵니다 |
| static [IsMeteredLicensed](../../com.aspose.html/metered/ismeteredlicensed/)() | 계량형이 라이선스가 있는지 확인하십시오 |

## 예제

이 예제에서는 계량형 공개 키와 개인 키를 설정하려고 시도합니다

```java
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

구성 요소 jar 파일:

```java
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### 또 보기

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
