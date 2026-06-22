---
title: "PdfPermissions 열거형"
second_title: "Java용 Aspose.HTML API 참조"
description: "com.aspose.html.rendering.pdf.encryption.PdfPermissions 열거형. 이 열거형은 PDF에 대한 사용자 권한을 나타냅니다."
type: docs

url: /ko/java/com.aspose.html.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

이 열거형은 PDF에 대한 사용자의 권한을 나타냅니다.

```java
[Flags]
public enum PdfPermissions
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| PrintDocument | `4` | (Security handlers of revision 2) 문서를 인쇄합니다. (Security handlers of revision 3 or greater) 문서를 인쇄합니다(PrintingQuality가 설정된 경우에도 최고 품질이 아닐 수 있습니다). |
| ModifyContent | `8` | ModifyTextAnnotations, FillForm 및 11에 의해 제어되는 작업을 제외한 다른 작업으로 문서 내용을 수정합니다. |
| ExtractContent | `10` | (Security handlers of revision 2) 문서에서 텍스트와 그래픽을 복사하거나 추출합니다(장애가 있는 사용자의 접근성을 지원하거나 기타 목적을 위해 텍스트와 그래픽을 추출하는 것을 포함). (Security handlers of revision 3 or greater) ExtractContentWithDisabilities에 의해 제어되지 않는 작업으로 문서에서 텍스트와 그래픽을 복사하거나 추출합니다. |
| ModifyTextAnnotations | `20` | 텍스트 주석을 추가하거나 수정하고, 인터랙티브 양식 필드를 채우며, ModifyContent가 설정된 경우 인터랙티브 양식 필드(서명 필드 포함)를 생성하거나 수정합니다. |
| FillForm | `100` | (Security handlers of revision 3 or greater) ModifyTextAnnotations가 해제된 경우에도 기존 인터랙티브 양식 필드(서명 필드 포함)를 채웁니다. |
| ExtractContentWithDisabilities | `200` | (Security handlers of revision 3 or greater) 텍스트와 그래픽을 추출합니다(장애가 있는 사용자의 접근성을 지원하거나 기타 목적을 위해). |
| AssembleDocument | `400` | (Security handlers of revision 3 or greater) ModifyContent가 해제된 경우에도 문서를 조립합니다(페이지 삽입, 회전, 삭제 및 북마크 또는 썸네일 이미지 생성). |
| PrintingQuality | `800` | (Security handlers of revision 3 or greater) PDF 콘텐츠의 정확한 디지털 사본을 생성할 수 있는 표현으로 문서를 인쇄합니다. 이 비트가 해제되고(비트 3이 설정된 경우) 인쇄는 외관의 저수준 표현으로 제한되며, 품질이 저하될 수 있습니다. |

### 또 보기

* package [com.aspose.html.rendering.pdf.encryption](../../com.aspose.html.rendering.pdf.encryption/)
* package [Aspose.HTML](../../)
