---
title: "License.SetLicense"
second_title: "Java용 Aspose.HTML API 참조"
description: "License 메서드. 구성 요소에 라이선스를 적용합니다."
type: docs

url: /ko/java/com.aspose.html/license/setlicense/
---
## SetLicense(String) {#setlicense_1}

구성 요소에 라이선스를 부여합니다.

```java
public void SetLicense(String licenseName)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| licenseName | String | 전체 파일 이름이거나 짧은 파일 이름, 또는 포함된 리소스의 이름일 수 있습니다. 빈 문자열을 사용하면 평가 모드로 전환됩니다. |

## 비고

다음 위치에서 라이선스를 찾으려고 시도합니다:

1. 명시적 경로.

2. Aspose 구성 요소 어셈블리가 포함된 폴더.

3. 클라이언트 호출 어셈블리가 포함된 폴더.

4. 엔트리(시작) 어셈블리가 포함된 폴더.

5. 클라이언트 호출 어셈블리의 포함된 리소스.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. 명시적 경로.

2. 클라이언트 호출 어셈블리의 포함된 리소스.

2. Aspose 구성 요소 JAR 파일이 포함된 폴더.

3. 클라이언트 호출 JAR 파일이 포함된 폴더.

## 예제

이 예제에서는 구성 요소가 포함된 폴더, 호출 어셈블리가 포함된 폴더, 엔트리 어셈블리 폴더, 그리고 호출 어셈블리의 임베디드 리소스에서 MyLicense.lic이라는 라이선스 파일을 찾으려고 시도합니다.

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

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## SetLicense(Stream) {#setlicense}

구성 요소에 라이선스를 부여합니다.

```java
public void SetLicense(Stream stream)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 라이선스를 포함하는 스트림. |

## 비고

이 메서드를 사용하여 스트림에서 라이선스를 로드합니다.

## 예제

```java
[C#]

License license = new License();
license.SetLicense(myStream);
```

### 또 보기

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
