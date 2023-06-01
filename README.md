# Welcome on RobiniaDocs!

![Recording 2023-05-17 114929](https://github.com/NeuroXiq/RobiniaDocs/assets/19374897/f8fbe700-3ef6-4110-b19d-ce9a07248e01)

### RobiniaDocs is a simple documentation hosting platform for .NET Core projects

If You have a small or medium size .NET Core project and want to host API browser with documentation - try RobiniaDocs!

**[RobiniaDocs - Website](https://www.robiniadocs.com)**

**[RobiniaDocs - Tutorial](https://www.robiniadocs.com/robiniadocs/d/articles/intro.html)**

Adventages of using Robinia:
- Robinia generates [sitemap.xml](https://www.robiniadocs.com/sitemap.xml) to facilitate web crawlers index Your project more easily
- Centralized place for hosting API explorer/documentation online
- No need to maintain code for documents generation and publishing

RobiniaDocs tries to be as simple as possible, You can host API Explorer in 2 minutes (please see first video). Its 100% free.

Example: 
- [Youtube - Host Docfx API browser on RobiniaDocs](https://youtu.be/sfeM43I_KaU)
- [Youtube - Docfx editor on RobiniaDocs](https://youtu.be/5fSAA1hmpUo)

But if You want to:
- Add arbitrary HTML
- Execute custom Javascript
- Has full control over generated documents by docfx
- Use other generators instead of docfx

RobiniaDocs probably will not be the best option for now, consider other hosting platforms e.g. github pages/readthedocs

# Create Documentation from Pull Request
To host API documentation without registering on RobiniaDocs, please create a new pull request.
1. Edit 'projects.md' file and add a new row in the  table
2. In  commit  message please add following informations:

```
Project Name: project_name
Robinia Url Prefix: url_prefix
Github Url: github_url
Description: description
Nuget Package Name: package_name (Install-Package 'package_name')
(if project does not have nuget package please add link to binary files like line below)
Dll Xml files: <url to .dll and .xml files)
```

For Example:

```
Project Name: Arctium Crypto Library
Robinia Url Prefix: arctium
Github Url: https://github.com/NeuroXiq/Arctium
Description: Arctium is a simple crypto library. It provides various cryptographic functions, ciphers, connection protocols
Nuget Package Name: Arctium.Shared
```

---

### Example deployed projects:

|Name|Robinia Url|Github|
|-|-|-|
|Guard.Net|[RobiniaDocs - Guard.Net](https://www.robiniadocs.com/guardnet/d/index.html)| [Github](Guard.Net)|
|Algorithmia|[RobiniaDocs - Algorithmia](https://www.robiniadocs.com/algorithmi/d/index.html)| [Github](https://github.com/SolutionsDesign/Algorithmia)|
|Towel |[RobiniaDocs - Towel ](https://www.robiniadocs.com/towel/d/index.html)| [Github](https://github.com/ZacharyPatten/Towel)|
|Akade.IndexedSet|[RobiniaDocs - Akade.IndexedSet](https://www.robiniadocs.com/akadeinde/d/index.html)| [Github](https://github.com/akade/Akade.IndexedSet)|
|SliccDB|[RobiniaDocs - SliccDB](https://www.robiniadocs.com/sliccdb/d/index.html)| [Github](https://github.com/pmikstacki/SliccDB)|
|StringDB|[RobiniaDocs - StringDB](https://www.robiniadocs.com/stringdb/d/index.html)| [Github](https://github.com/SirJosh3917/StringDB)|
|Ninject|[RobiniaDocs - Ninject](https://www.robiniadocs.com/ninject/d/index.html)| [Github](https://github.com/ninject/ninject)|
|Spring.Core|[RobiniaDocs - Spring.Core](https://www.robiniadocs.com/springcor/d/index.html)| [Github](https://github.com/spring-projects/spring-net)|
|LightInject |[RobiniaDocs - LightInject ](https://www.robiniadocs.com/lightinjec/d/index.html)| [Github](https://github.com/seesharper/LightInject)|
|Stashbox |[RobiniaDocs - Stashbox ](https://www.robiniadocs.com/stashbox/d/index.html)| [Github](https://github.com/z4kn4fein/stashbox)|
|Markdig |[RobiniaDocs - Markdig ](https://www.robiniadocs.com/markdig/d/index.html)| [Github](https://github.com/xoofx/markdig)|
|PreMailer.Net|[RobiniaDocs - PreMailer.Net](https://www.robiniadocs.com/premailer/d/index.html)| [Github](https://github.com/milkshakesoftware/PreMailer.Net)|
|MimeKit |[RobiniaDocs - MimeKit ](https://www.robiniadocs.com/mimekit/d/index.html)| [Github](https://github.com/jstedfast/MimeKit)|
|StrongGrid |[RobiniaDocs - StrongGrid ](https://www.robiniadocs.com/stronggrid/d/index.html)| [Github](https://github.com/Jericho/StrongGrid)|
|Rationals|[RobiniaDocs - Rationals](https://www.robiniadocs.com/rationals/d/index.html)| [Github](https://github.com/tompazourek/Rationals)|
|Vim.Math3D |[RobiniaDocs - Vim.Math3D ](https://www.robiniadocs.com/vimmathd/d/index.html)| [Github](https://github.com/vimaec/math3d)|
|NAudio |[RobiniaDocs - NAudio ](https://www.robiniadocs.com/naudio/d/index.html)| [Github](https://github.com/naudio/NAudio)|
|TinyMapper |[RobiniaDocs - TinyMapper ](https://www.robiniadocs.com/tinymapper/d/index.html)| [Github](https://github.com/TinyMapper/TinyMapper)|
|AgileObjects.AgileMapper|[RobiniaDocs - AgileObjects.AgileMapper](https://www.robiniadocs.com/agileobjec/d/index.html)| [Github](https://github.com/agileobjects/AgileMapper)|
|DateTimeExtensions|[RobiniaDocs - DateTimeExtensions](https://www.robiniadocs.com/datetimeex/d/index.html)| [Github](https://github.com/joaomatossilva/DateTimeExtensions)|
|Exceptionless.DateTimeExtensions|[RobiniaDocs - Exceptionless.DateTimeExtensions](https://www.robiniadocs.com/exceptionl/d/index.html)| [Github](https://github.com/exceptionless/Exceptionless.DateTimeExtensions)|
|Tiny.RestClient|[RobiniaDocs - Tiny.RestClient](https://www.robiniadocs.com/tinyrestc/d/index.html)| [Github](https://github.com/jgiacomini/Tiny.RestClient)|
|Http.fs|[RobiniaDocs - Http.fs](https://www.robiniadocs.com/httpfs/d/index.html)| [Github](https://github.com/haf/Http.fs)|
|RestSharp |[RobiniaDocs - RestSharp ](https://www.robiniadocs.com/restsharp/d/index.html)| [Github](https://github.com/restsharp/RestSharp)|
|Refit |[RobiniaDocs - Refit ](https://www.robiniadocs.com/refit/d/index.html)| [Github](https://github.com/reactiveui/refit)|
|RestEase |[RobiniaDocs - RestEase ](https://www.robiniadocs.com/restease/d/index.html)| [Github](https://github.com/canton7/RestEase)|
|PhotoSauce.MagicScaler|[RobiniaDocs - PhotoSauce.MagicScaler](https://www.robiniadocs.com/photosauce/d/index.html)| [Github](https://github.com/saucecontrol/PhotoSauce)|
|Magick.NET|[RobiniaDocs - Magick.NET](https://www.robiniadocs.com/magicknet/d/index.html)| [Github](https://github.com/dlemstra/Magick.NET)|
|Colourful |[RobiniaDocs - Colourful ](https://www.robiniadocs.com/colourful/d/index.html)| [Github](https://github.com/tompazourek/Colourful)|
|SharpPcap |[RobiniaDocs - SharpPcap ](https://www.robiniadocs.com/sharppcap/d/index.html)| [Github](https://github.com/dotpcap/sharppcap)|
|Ceras |[RobiniaDocs - Ceras ](https://www.robiniadocs.com/ceras/d/index.html)| [Github](https://github.com/rikimaru0345/Ceras)|
|protobuf-net|[RobiniaDocs - protobuf-net](https://www.robiniadocs.com/protobufn/d/index.html)| [Github](https://github.com/protobuf-net/protobuf-net)|
|Stateless |[RobiniaDocs - Stateless ](https://www.robiniadocs.com/stateless/d/index.html)| [Github](https://github.com/dotnet-state-machine/stateless)|
|Downloader |[RobiniaDocs - Downloader ](https://www.robiniadocs.com/downloader/d/index.html)| [Github](https://github.com/bezzad/Downloader)|
|FluentSerializer.Json|[RobiniaDocs - FluentSerializer.Json](https://www.robiniadocs.com/fluentseri/d/index.html)| [Github](https://github.com/Marvin-Brouwer/FluentSerializer#readme)|
|ObjectDumper.NET|[RobiniaDocs - ObjectDumper.NET](https://www.robiniadocs.com/objectdump/d/index.html)| [Github](https://github.com/thomasgalliker/ObjectDumper)|
|FsPickler |[RobiniaDocs - FsPickler ](https://www.robiniadocs.com/fspickler/d/index.html)| [Github](https://github.com/mbraceproject/FsPickler)|
|FileHelpers |[RobiniaDocs - FileHelpers ](https://www.robiniadocs.com/filehelper/d/index.html)| [Github](https://www.nuget.org/packages/FileHelpers/)|
|dfghdfgh|[RobiniaDocs - dfghdfgh](https://www.robiniadocs.com/dfghdfgh/d/index.html)| [Github](dfgh)|
|Arctium - .NET Core crypto library|[RobiniaDocs - Arctium - .NET Core crypto library](https://www.robiniadocs.com/arctium/d/index.html)| [Github](https://github.com/NeuroXiq/Arctium)|
|Arctium.Shared|[RobiniaDocs - Arctium.Shared](https://www.robiniadocs.com/arctium-shared/d/index.html)| [Github](https://github.com/NeuroXiq/Arctium)|
|Arctium.Cryptography|[RobiniaDocs - Arctium.Cryptography](https://www.robiniadocs.com/arctium-cryptography/d/index.html)| [Github](https://github.com/NeuroXiq/Arctium)|
|Arctium.Standards|[RobiniaDocs - Arctium.Standards](https://www.robiniadocs.com/arctium-standards/d/index.html)| [Github](https://github.com/NeuroXiq/Arctium)|

