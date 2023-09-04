# RobiniaDocs! - Awesome .NET Core projects with documentation
### List of awesome .NET Core projects with documentation online

## **[RobiniaDocs - Website](https://www.robiniadocs.com)** | **[RobiniaDocs - Tutorial](https://www.robiniadocs.com/d/robiniadocs/articles/intro.html)**

![Recording 2023-05-17 114929](https://github.com/NeuroXiq/RobiniaDocs/assets/19374897/f8fbe700-3ef6-4110-b19d-ce9a07248e01)
![image](https://github.com/NeuroXiq/RobiniaDocs/assets/19374897/c5f849ed-2c78-4eca-98a1-adee82e2b329)

## Motivation
Looking on github C# repositories lots of them did  not have any documentation online. To take a look on basic project structure
and what methods are exposed I needed to open a code and open each .cs file just to simply look what functions and methods are there.
Also there was not any website that allows me to just simply generate and host documentation for my .NET Core project online.


## RobiniaDocs allows to generate and host Documentation in 1 minute

1. Open www.robiniadocs.com and signin with Github account
2. Create a project with Nuget Package Name
3. Rebuild Project

Docfx API explorer is hosted online

If You have a small or medium size .NET Core project - try RobiniaDocs!\
RobiniaDocs can be used as a *default project documentation* or *temporary documentation* for projects that does not have  any documentation yet.\
Only thing  needed is nuget package name.

---

Adventages of using Robinia:
- Robinia generates [sitemap.xml](https://www.robiniadocs.com/api/other/sitemaps/sitemap.xml)
- Very easy configuration - only nuget package needed
- No need to maintain code for documents generation and publishing

# Create Documentation from Pull Request
To host API explorer without registering on RobiniaDocs, please create a new pull request.
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

### Projects list:

|Name|Robinia Url|Github|
|-|-|-|
|Guard.Net|[RobiniaDocs - Guard.Net](https://www.robiniadocs.com/d/guardnet/api/index.html)| [Github](Guard.Net)|
|Algorithmia|[RobiniaDocs - Algorithmia](https://www.robiniadocs.com/d/algorithmi/api/index.html)| [Github](https://github.com/SolutionsDesign/Algorithmia)|
|Towel |[RobiniaDocs - Towel ](https://www.robiniadocs.com/d/towel/api/index.html)| [Github](https://github.com/ZacharyPatten/Towel)|
|Akade.IndexedSet|[RobiniaDocs - Akade.IndexedSet](https://www.robiniadocs.com/d/akadeinde/api/index.html)| [Github](https://github.com/akade/Akade.IndexedSet)|
|SliccDB|[RobiniaDocs - SliccDB](https://www.robiniadocs.com/d/sliccdb/api/index.html)| [Github](https://github.com/pmikstacki/SliccDB)|
|StringDB|[RobiniaDocs - StringDB](https://www.robiniadocs.com/d/stringdb/api/index.html)| [Github](https://github.com/SirJosh3917/StringDB)|
|Ninject|[RobiniaDocs - Ninject](https://www.robiniadocs.com/d/ninject/api/index.html)| [Github](https://github.com/ninject/ninject)|
|Spring.Core|[RobiniaDocs - Spring.Core](https://www.robiniadocs.com/d/springcor/api/index.html)| [Github](https://github.com/spring-projects/spring-net)|
|LightInject |[RobiniaDocs - LightInject ](https://www.robiniadocs.com/d/lightinjec/api/index.html)| [Github](https://github.com/seesharper/LightInject)|
|Stashbox |[RobiniaDocs - Stashbox ](https://www.robiniadocs.com/d/stashbox/api/index.html)| [Github](https://github.com/z4kn4fein/stashbox)|
|Markdig |[RobiniaDocs - Markdig ](https://www.robiniadocs.com/d/markdig/api/index.html)| [Github](https://github.com/xoofx/markdig)|
|PreMailer.Net|[RobiniaDocs - PreMailer.Net](https://www.robiniadocs.com/d/premailer/api/index.html)| [Github](https://github.com/milkshakesoftware/PreMailer.Net)|
|MimeKit |[RobiniaDocs - MimeKit ](https://www.robiniadocs.com/d/mimekit/api/index.html)| [Github](https://github.com/jstedfast/MimeKit)|
|StrongGrid |[RobiniaDocs - StrongGrid ](https://www.robiniadocs.com/d/stronggrid/api/index.html)| [Github](https://github.com/Jericho/StrongGrid)|
|Rationals|[RobiniaDocs - Rationals](https://www.robiniadocs.com/d/rationals/api/index.html)| [Github](https://github.com/tompazourek/Rationals)|
|Vim.Math3D |[RobiniaDocs - Vim.Math3D ](https://www.robiniadocs.com/d/vimmathd/api/index.html)| [Github](https://github.com/vimaec/math3d)|
|NAudio |[RobiniaDocs - NAudio ](https://www.robiniadocs.com/d/naudio/api/index.html)| [Github](https://github.com/naudio/NAudio)|
|TinyMapper |[RobiniaDocs - TinyMapper ](https://www.robiniadocs.com/d/tinymapper/api/index.html)| [Github](https://github.com/TinyMapper/TinyMapper)|
|AgileObjects.AgileMapper|[RobiniaDocs - AgileObjects.AgileMapper](https://www.robiniadocs.com/d/agileobjec/api/index.html)| [Github](https://github.com/agileobjects/AgileMapper)|
|DateTimeExtensions|[RobiniaDocs - DateTimeExtensions](https://www.robiniadocs.com/d/datetimeex/api/index.html)| [Github](https://github.com/joaomatossilva/DateTimeExtensions)|
|Exceptionless.DateTimeExtensions|[RobiniaDocs - Exceptionless.DateTimeExtensions](https://www.robiniadocs.com/d/exceptionl/api/index.html)| [Github](https://github.com/exceptionless/Exceptionless.DateTimeExtensions)|
|Tiny.RestClient|[RobiniaDocs - Tiny.RestClient](https://www.robiniadocs.com/d/tinyrestc/api/index.html)| [Github](https://github.com/jgiacomini/Tiny.RestClient)|
|Http.fs|[RobiniaDocs - Http.fs](https://www.robiniadocs.com/d/httpfs/api/index.html)| [Github](https://github.com/haf/Http.fs)|
|RestSharp |[RobiniaDocs - RestSharp ](https://www.robiniadocs.com/d/restsharp/api/index.html)| [Github](https://github.com/restsharp/RestSharp)|
|Refit |[RobiniaDocs - Refit ](https://www.robiniadocs.com/d/refit/api/index.html)| [Github](https://github.com/reactiveui/refit)|
|RestEase |[RobiniaDocs - RestEase ](https://www.robiniadocs.com/d/restease/api/index.html)| [Github](https://github.com/canton7/RestEase)|
|PhotoSauce.MagicScaler|[RobiniaDocs - PhotoSauce.MagicScaler](https://www.robiniadocs.com/d/photosauce/api/index.html)| [Github](https://github.com/saucecontrol/PhotoSauce)|
|Magick.NET|[RobiniaDocs - Magick.NET](https://www.robiniadocs.com/d/magicknet/api/index.html)| [Github](https://github.com/dlemstra/Magick.NET)|
|Colourful |[RobiniaDocs - Colourful ](https://www.robiniadocs.com/d/colourful/api/index.html)| [Github](https://github.com/tompazourek/Colourful)|
|SharpPcap |[RobiniaDocs - SharpPcap ](https://www.robiniadocs.com/d/sharppcap/api/index.html)| [Github](https://github.com/dotpcap/sharppcap)|
|Ceras |[RobiniaDocs - Ceras ](https://www.robiniadocs.com/d/ceras/api/index.html)| [Github](https://github.com/rikimaru0345/Ceras)|
|protobuf-net|[RobiniaDocs - protobuf-net](https://www.robiniadocs.com/d/protobufn/api/index.html)| [Github](https://github.com/protobuf-net/protobuf-net)|
|Stateless |[RobiniaDocs - Stateless ](https://www.robiniadocs.com/d/stateless/api/index.html)| [Github](https://github.com/dotnet-state-machine/stateless)|
|Downloader |[RobiniaDocs - Downloader ](https://www.robiniadocs.com/d/downloader/api/index.html)| [Github](https://github.com/bezzad/Downloader)|
|FluentSerializer.Json|[RobiniaDocs - FluentSerializer.Json](https://www.robiniadocs.com/d/fluentseri/api/index.html)| [Github](https://github.com/Marvin-Brouwer/FluentSerializer#readme)|
|ObjectDumper.NET|[RobiniaDocs - ObjectDumper.NET](https://www.robiniadocs.com/d/objectdump/api/index.html)| [Github](https://github.com/thomasgalliker/ObjectDumper)|
|FsPickler |[RobiniaDocs - FsPickler ](https://www.robiniadocs.com/d/fspickler/api/index.html)| [Github](https://github.com/mbraceproject/FsPickler)|
|FileHelpers |[RobiniaDocs - FileHelpers ](https://www.robiniadocs.com/d/filehelper/api/index.html)| [Github](https://www.nuget.org/packages/FileHelpers/)|
|dfghdfgh|[RobiniaDocs - dfghdfgh](https://www.robiniadocs.com/d/dfghdfgh/api/index.html)| [Github](dfgh)|
|Arctium - .NET Core crypto library|[RobiniaDocs - Arctium - .NET Core crypto library](https://www.robiniadocs.com/d/arctium/api/index.html)| [Github](https://github.com/NeuroXiq/Arctium)|
|Arctium.Shared|[RobiniaDocs - Arctium.Shared](https://www.robiniadocs.com/d/arctium-shared/api/index.html)| [Github](https://github.com/NeuroXiq/Arctium)|
|Arctium.Cryptography|[RobiniaDocs - Arctium.Cryptography](https://www.robiniadocs.com/d/arctium-cryptography/api/index.html)| [Github](https://github.com/NeuroXiq/Arctium)|
|Arctium.Standards|[RobiniaDocs - Arctium.Standards](https://www.robiniadocs.com/d/arctium-standards/api/index.html)| [Github](https://github.com/NeuroXiq/Arctium)|
