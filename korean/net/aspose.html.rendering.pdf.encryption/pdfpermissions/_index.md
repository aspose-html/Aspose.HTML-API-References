---
title: Enum PdfPermissions
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Rendering.Pdf.Encryption.PdfPermissions 열거형. 이 열거형은 pdf. 에 대한 사용자의 권한을 나타냅니다.
type: docs
weight: 4420
url: /ko/net/aspose.html.rendering.pdf.encryption/pdfpermissions/
---
## PdfPermissions enumeration

이 열거형은 pdf. 에 대한 사용자의 권한을 나타냅니다.

```csharp
[Flags]
public enum PdfPermissions
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| PrintDocument | `4` | (개정 2의 보안 처리기) 문서를 인쇄합니다. (개정 3 이상의 보안 처리기) 문서를 인쇄합니다(PrintingQuality도 설정되었는지 여부에 따라 최고 품질 수준이 아닐 수 있음). |
| ModifyContent | `8` | ModifyTextAnnotations, FillForm 및 11. 에 의해 제어되는 작업 이외의 작업으로 문서의 내용을 수정합니다. |
| ExtractContent | `10` | 수정 버전 2의 보안 처리기 텍스트 및 그래픽 추출을 포함하여 문서에서 텍스트 및 그래픽을 복사하거나 추출합니다(장애가 있는 사용자의 접근성 지원 또는 기타 목적). (수정 버전 3 이상의 보안 처리기) 복사 그렇지 않으면 ExtractContentWithDisabilities. 에 의해 제어되는 작업 이외의 작업으로 문서에서 텍스트 및 그래픽을 추출합니다. |
| ModifyTextAnnotations | `20` | 텍스트 주석을 추가 또는 수정하고, 대화형 양식 필드를 채우고, ModifyContent도 설정된 경우 대화형 양식 필드(서명 필드 포함)를 생성하거나 수정합니다. |
| FillForm | `100` | (개정 3 이상의 보안 처리기) ModifyTextAnnotations가 명확한 경우에도 기존 대화형 양식 필드(서명 필드 포함)를 채웁니다. |
| ExtractContentWithDisabilities | `200` | (개정 3 이상의 보안 처리기) 텍스트 및 그래픽 추출(장애가 있는 사용자의 접근성 지원 또는 기타 목적). |
| AssembleDocument | `400` | (개정 3 이상의 보안 처리기) ModifyContent가 명확한 경우에도 문서를 어셈블합니다(페이지 삽입, 회전 또는 삭제 및 책갈피 또는 축소판 이미지 생성). |
| PrintingQuality | `800` | (개정 3 이상의 보안 처리기) PDF 콘텐츠의 충실한 디지털 사본을 생성할 수 있는 표현으로 문서를 인쇄합니다. 이 비트가 지워지면(비트 3이 설정됨) 인쇄가 낮은 -품질이 저하될 수 있는 외관의 수준 표현. |

### 또한보십시오

* 네임스페이스 [Aspose.Html.Rendering.Pdf.Encryption](../../aspose.html.rendering.pdf.encryption/)
* 집회 [Aspose.HTML](../../)


