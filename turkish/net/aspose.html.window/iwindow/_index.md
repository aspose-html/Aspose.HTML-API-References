---
title: Interface IWindow
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Window.IWindow arayüz. Pencere nesnesi bir DOM belgesi içeren bir pencereyi temsil eder.
type: docs
weight: 5850
url: /tr/net/aspose.html.window/iwindow/
---
## IWindow interface

Pencere nesnesi, bir DOM belgesi içeren bir pencereyi temsil eder.

```csharp
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Document](../../aspose.html.window/iwindow/document/) { get; } | Document özniteliği, Window nesnesinin en yeni Document nesnesini döndürmelidir. |
| [FrameElement](../../aspose.html.window/iwindow/frameelement/) { get; } | Bir Belgenin frameElement nesnesi. |
| [Location](../../aspose.html.window/iwindow/location/) { get; } | Pencere arayüzünün konum özniteliği, o Pencere nesnesinin Document. için Konum nesnesini döndürmelidir. |
| [Name](../../aspose.html.window/iwindow/name/) { get; set; } | Window nesnesinin name özniteliği, alınırken tarama içeriğinin geçerli adını döndürmeli ve ayarlandığında, tarama içeriğinin adını yeni değere ayarlamalıdır. |
| [Opener](../../aspose.html.window/iwindow/opener/) { get; } | Window nesnesindeki açıcı IDL özniteliği, alınırken, mevcut gözatma bağlamının oluşturulduğu gözatma bağlamının (açıcı gözatma bağlamı) WindowProxy nesnesini, eğer varsa, hala mevcutsa ve varsa döndürmelidir. mevcut göz atma bağlamı, açıcısını reddetmedi; aksi halde null döndürmelidir. Ayarlama sırasında, yeni değer null ise, geçerli göz atma bağlamı açıcısını reddetmelidir; yeni değer başka bir şeyse, kullanıcı aracısı, özellik anahtarı olarak "opener" özellik adını ve Özellik Tanımlayıcı { [[Değer]] değerini ileterek Window nesnesinin [[DefineOwnProperty]] dahili yöntemini çağırmalıdır. , [[Yazılabilir]]: true, [[Enumerable]]: true, [[Configurable]]: true } özelliği tanımlayıcı olarak, burada değer yeni değerdir. |
| [Parent](../../aspose.html.window/iwindow/parent/) { get; } | Gözatma bağlamında b bir Belgenin Window nesnesindeki üst IDL özniteliği, varsa üst gözatma bağlamının WindowProxy nesnesini (yani, b bir alt gözatma bağlamıysa) veya gözatmanın WindowProxy nesnesini döndürmelidir. bağlam b'nin kendisi, aksi takdirde (yani, üst düzey bir göz atma bağlamı veya ayrılmış, iç içe geçmiş bir göz atma bağlamıysa). |
| [Self](../../aspose.html.window/iwindow/self/) { get; } | Window nesnesinin tarama içeriğinin WindowProxy nesnesini döndürür. |
| [Top](../../aspose.html.window/iwindow/top/) { get; } | Tarama bağlamındaki bir Belgenin Window nesnesindeki üst IDL özniteliği b, üst düzey tarama bağlamının WindowProxy nesnesini döndürmelidir (bu, kendisi bir üst düzey tarama bağlamı olsaydı kendi WindowProxy nesnesi olurdu), eğer bir veya kendi WindowProxy nesnesine sahiptir (örneğin, ayrılmış, iç içe geçmiş bir tarama bağlamıysa). |
| [Window](../../aspose.html.window/iwindow/window/) { get; } | Window nesnesinin tarama içeriğinin WindowProxy nesnesini döndürür. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Alert](../../aspose.html.window/iwindow/alert/)(string) | Verilen mesajla birlikte kalıcı bir uyarı görüntüler ve kullanıcının bunu kapatmasını bekler |
| [Confirm](../../aspose.html.window/iwindow/confirm/)(string) | Verilen mesajla birlikte kalıcı bir Tamam/İptal istemi görüntüler, kullanıcının bunu reddetmesini bekler ve kullanıcı Tamam'ı tıklarsa doğru, kullanıcı İptal'i tıklarsa yanlış döndürür. |
| [Prompt](../../aspose.html.window/iwindow/prompt/)(string, string) | Verilen mesajla birlikte kalıcı bir metin alanı istemi görüntüler, kullanıcının mesajı kapatmasını bekler ve kullanıcının girdiği değeri döndürür. Kullanıcı istemi iptal ederse, bunun yerine null değerini döndürür. İkinci bağımsız değişken mevcutsa, verilen değer varsayılan olarak kullanılır. |

### Ayrıca bakınız

* interface [IDocumentView](../../aspose.html.dom.views/idocumentview/)
* interface [IEventTarget](../../aspose.html.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../aspose.html.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* ad alanı [Aspose.Html.Window](../../aspose.html.window/)
* toplantı [Aspose.HTML](../../)


