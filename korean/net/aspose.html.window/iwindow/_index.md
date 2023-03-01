---
title: Interface IWindow
second_title: .NET API 참조용 Aspose.HTML
description: Aspose.Html.Window.IWindow 상호 작용. 창 개체는 DOM 문서를 포함하는 창을 나타냅니다.
type: docs
weight: 5850
url: /ko/net/aspose.html.window/iwindow/
---
## IWindow interface

창 개체는 DOM 문서를 포함하는 창을 나타냅니다.

```csharp
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Document](../../aspose.html.window/iwindow/document/) { get; } | 문서 특성은 Window 개체의 최신 문서 개체를 반환해야 합니다. |
| [FrameElement](../../aspose.html.window/iwindow/frameelement/) { get; } | Document. 의 frameElement 객체 |
| [Location](../../aspose.html.window/iwindow/location/) { get; } | Window 인터페이스의 위치 특성은 해당 Window 개체의 Document. 에 대한 Location 개체를 반환해야 합니다. |
| [Name](../../aspose.html.window/iwindow/name/) { get; set; } | Window 개체의 이름 특성은 가져올 때 브라우징 컨텍스트의 현재 이름을 반환하고 설정할 때 브라우징 컨텍스트의 이름을 새 값으로 설정해야 합니다. |
| [Opener](../../aspose.html.window/iwindow/opener/) { get; } | Window 개체의 오프너 IDL 속성은 가져올 때 현재 브라우징 컨텍스트가 생성된 브라우징 컨텍스트(오프너 브라우징 컨텍스트)의 WindowProxy 개체를 반환해야 합니다. 현재 브라우징 컨텍스트는 오프너를 소유하지 않았습니다. 그렇지 않으면 null을 반환해야 합니다. 설정 시 새 값이 null이면 현재 브라우징 컨텍스트는 오프너를 부인해야 합니다. 새 값이 다른 값이면 사용자 에이전트는 Window 객체의 [[DefineOwnProperty]] 내부 메서드를 호출하고 속성 이름 "opener"를 속성 키로 전달하고 속성 설명자 { [[Value]]: value , [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } 속성 설명자로, 여기서 value는 새 값입니다. |
| [Parent](../../aspose.html.window/iwindow/parent/) { get; } | 브라우징 컨텍스트 b에 있는 문서의 Window 객체에 대한 부모 IDL 속성은 부모 브라우징 컨텍스트의 WindowProxy 객체가 있는 경우(즉, b가 자식 브라우징 컨텍스트인 경우) 또는 브라우징의 WindowProxy 객체를 반환해야 합니다. 컨텍스트 b 자체, 그렇지 않은 경우(예: 최상위 브라우징 컨텍스트 또는 분리된 중첩 브라우징 컨텍스트인 경우). |
| [Self](../../aspose.html.window/iwindow/self/) { get; } | Window 개체의 브라우징 컨텍스트의 WindowProxy 개체를 반환합니다. |
| [Top](../../aspose.html.window/iwindow/top/) { get; } | 브라우징 컨텍스트 b에 있는 Document의 Window 객체에 대한 최상위 IDL 속성은 최상위 브라우징 컨텍스트의 WindowProxy 객체(최상위 브라우징 컨텍스트 자체인 경우 자체 WindowProxy 객체)를 반환해야 합니다. 그렇지 않으면 하나 또는 자체 WindowProxy 객체를 갖습니다(예: 분리된 중첩 브라우징 컨텍스트인 경우). |
| [Window](../../aspose.html.window/iwindow/window/) { get; } | Window 개체의 브라우징 컨텍스트의 WindowProxy 개체를 반환합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Alert](../../aspose.html.window/iwindow/alert/)(string) | 지정된 메시지와 함께 모달 경고를 표시하고 사용자가 it 를 해제할 때까지 기다립니다. |
| [Confirm](../../aspose.html.window/iwindow/confirm/)(string) | 지정된 메시지와 함께 모달 확인/취소 프롬프트를 표시하고 사용자가 메시지를 닫을 때까지 기다렸다가 사용자가 확인을 클릭하면 true를 반환하고 사용자가 취소를 클릭하면 false를 반환합니다. |
| [Prompt](../../aspose.html.window/iwindow/prompt/)(string, string) | 지정된 메시지와 함께 모달 텍스트 필드 프롬프트를 표시하고 사용자가 메시지를 닫을 때까지 기다린 다음 사용자가 입력한 값을 반환합니다. 사용자가 프롬프트를 취소하면 대신 null을 반환합니다. 두 번째 인수가 있으면 주어진 값이 기본값으로 사용됩니다. |

### 또한보십시오

* interface [IDocumentView](../../aspose.html.dom.views/idocumentview/)
* interface [IEventTarget](../../aspose.html.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../aspose.html.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* 네임스페이스 [Aspose.Html.Window](../../aspose.html.window/)
* 집회 [Aspose.HTML](../../)


