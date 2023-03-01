---
title: Class Metered
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Metered 수업. 측정 키를 설정하는 방법을 제공합니다.
type: docs
weight: 3830
url: /ko/net/aspose.html/metered/
---
## Metered class

측정 키를 설정하는 방법을 제공합니다.

```csharp
public class Metered
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Metered](metered/)() | 이 클래스의 새 인스턴스를 초기화합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [SetMeteredKey](../../aspose.html/metered/setmeteredkey/)(string, string) | 미터링된 공개 및 개인 키를 설정합니다. 미터링된 라이센스를 구입하면 응용 프로그램을 시작할 때 이 API를 호출해야 하며 일반적으로 이 정도면 충분합니다. 단, 항상 소비 데이터 업로드에 실패하고 24시간을 초과하면 라이센스가 평가 상태로 설정됩니다. 이러한 경우를 방지하려면 라이센스 상태를 정기적으로 확인해야 하며 평가 상태이면 이 API를 다시 호출하십시오. |
| static [GetConsumptionCredit](../../aspose.html/metered/getconsumptioncredit/)() | 소비 credit 가져오기 |
| static [GetConsumptionQuantity](../../aspose.html/metered/getconsumptionquantity/)() | 소비 파일 크기 가져오기 |

### 예

이 예에서는 측정된 공용 및 개인 키 를 설정하려고 시도합니다.

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

구성 요소 jar 파일:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### 또한보십시오

* 네임스페이스 [Aspose.Html](../../aspose.html/)
* 집회 [Aspose.HTML](../../)


