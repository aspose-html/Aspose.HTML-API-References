---
title: "PdfPermissions 열거형"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.rendering.pdf.encryption.PdfPermissions 열거형. 이 열거형은 PDF에 대한 사용자 권한을 나타냅니다."
type: docs

url: /ko/java/com.aspose.html.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

이 열거형은 pdf에 대한 사용자의 권한을 나타냅니다.

```java
[Flags]
public enum PdfPermissions
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| PrintDocument | `4` | (리비전 2의 보안 핸들러) 문서를 인쇄합니다. (리비전 3 이상 보안 핸들러) 문서를 인쇄합니다(PrintingQuality가 설정된 경우에도 최고 품질이 아닐 수 있습니다). |
| ModifyContent | `8` | ModifyTextAnnotations, FillForm 및 11에 의해 제어되는 작업 외의 작업으로 문서 내용을 수정합니다. |
| ExtractContent | `10` | Security handlers of revision 2) 문서에서 텍스트와 그래픽을 복사하거나 추출합니다(접근성 지원을 위해 텍스트와 그래픽을 추출함). (Security handlers of revision 3 or greater) 문서에서 텍스트와 그래픽을 복사하거나 추출하는 작업을, ExtractContentWithDisabilities에 의해 제어되는 작업 이외의 방법으로 수행합니다. |
| ModifyTextAnnotations | `20` | 텍스트 주석을 추가하거나 수정하고, 대화형 양식 필드를 채우며, ModifyContent가 설정된 경우 대화형 양식 필드(서명 필드 포함)를 생성하거나 수정합니다. |
| FillForm | `100` | (Security handlers of revision 3 or greater) 기존 대화형 양식 필드(서명 필드 포함)를 채웁니다, 비록 ModifyTextAnnotations가 해제된 경우에도. |
| ExtractContentWithDisabilities | `200` | (Security handlers of revision 3 or greater) 텍스트와 그래픽을 추출합니다(장애인 접근성 지원 또는 기타 목적을 위해). |
| AssembleDocument | `400` | (Security handlers of revision 3 or greater) 문서를 조립합니다(페이지 삽입, 회전, 삭제 및 북마크 또는 썸네일 이미지 생성), 비록 ModifyContent가 해제된 경우에도. |
| PrintingQuality | `800` | (Security handlers of revision 3 or greater) 문서를 인쇄하여 PDF 내용의 정확한 디지털 복사본을 생성할 수 있는 표현으로 변환합니다. 이 비트가 해제되고(비트 3이 설정된 경우) 인쇄는 외관의 저수준 표현으로 제한되며, 품질이 저하될 수 있습니다. |

### 또 보기

* package [com.aspose.html.rendering.pdf.encryption](../../com.aspose.html.rendering.pdf.encryption/)
* package [Aspose.HTML](../../)
