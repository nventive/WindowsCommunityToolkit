# Uno Platform port of Windows Community Toolkit

This port allows for [Uno-based](https://github.com/unoplatform/Uno) apps to use [Windows Community Toolkit](https://github.com/Microsoft/WindowsCommunityToolkit)
on Windows, iOS, Android and WebAssembly.

The following packages are available:
- [Uno.Microsoft.Toolkit](https://www.nuget.org/packages/Uno.Microsoft.Toolkit )
- [Uno.Microsoft.Toolkit.Parsers](https://www.nuget.org/packages/Uno.Microsoft.Toolkit.Parsers)
- [Uno.Microsoft.Toolkit.Services](https://www.nuget.org/packages/Uno.Microsoft.Toolkit.Services)
- [Uno.Microsoft.Toolkit.UWP.Notifications](https://www.nuget.org/packages/Uno.Microsoft.Toolkit.Uwp.Notifications)
- [Uno.Microsoft.Toolkit.UWP.Notifications.JavaScript](https://www.nuget.org/packages/Uno.Microsoft.Toolkit.Uwp.Notifications.JavaScript)
- [Uno.Microsoft.Toolkit.UWP](https://www.nuget.org/packages/Uno.Microsoft.Toolkit.UWP)
- [Uno.Microsoft.Toolkit.Uwp.Services](https://www.nuget.org/packages/Uno.Microsoft.Toolkit.Uwp.Services)
- [Uno.Microsoft.Toolkit.Uwp.UI](https://www.nuget.org/packages/Uno.Microsoft.Toolkit.UWP.UI)
- [Uno.Microsoft.Toolkit.Uwp.UI.Animations](https://www.nuget.org/packages/Uno.Microsoft.Toolkit.Uwp.UI.Animations)
- [Uno.Microsoft.Toolkit.Uwp.UI.Controls](https://www.nuget.org/packages/Uno.Microsoft.Toolkit.Uwp.UI.Controls)
- [Uno.Microsoft.Toolkit.Uwp.UI.Controls.Graph](https://www.nuget.org/packages/Uno.Microsoft.Toolkit.UWP.UI.Controls.Graph)
- [Uno.Microsoft.Toolkit.Uwp.Connectivity](https://www.nuget.org/packages/Uno.Microsoft.Toolkit.Uwp.Connectivity)

# Windows Community Toolkit :toolbox:
The Windows Community Toolkit is a collection of helper functions, custom controls, and app services. It simplifies and demonstrates common developer patterns when building experiences for Windows 10.

| Target | Branch | Status | Recommended package version |
| ------ | ------ | ------ | ------ |
| Production | rel/6.1.0 | [![Build Status](https://dev.azure.com/dotnet/WindowsCommunityToolkit/_apis/build/status/Toolkit-CI?branchName=rel/6.1.0)](https://dev.azure.com/dotnet/WindowsCommunityToolkit/_build/latest?definitionId=10&branchName=rel/6.1.0) | [![NuGet](https://img.shields.io/nuget/v/Microsoft.Toolkit.Uwp.svg)](https://www.nuget.org/profiles/Microsoft.Toolkit) | 
| Pre-release beta testing | master | [![Build Status](https://dev.azure.com/dotnet/WindowsCommunityToolkit/_apis/build/status/Toolkit-CI?branchName=master)](https://dev.azure.com/dotnet/WindowsCommunityToolkit/_build/latest?definitionId=10) | [![DevOps](https://vsrm.dev.azure.com/dotnet/_apis/public/Release/badge/696bc9fd-f160-4e97-a1bd-7cbbb3b58f66/1/1)](https://dev.azure.com/dotnet/WindowsCommunityToolkit/_packaging?_a=feed&feed=WindowsCommunityToolkit-MainLatest) |

## Getting Started :raised_hands:
Please read the [Getting Started with the Windows Community Toolkit](https://docs.microsoft.com/windows/communitytoolkit/getting-started) page for more detailed information about using the toolkit.

## Documentation :pencil:
All documentation for the toolkit is hosted on [Microsoft Docs](https://docs.microsoft.com/windows/communitytoolkit/). All API documentation can be found at the [.NET API Browser](https://docs.microsoft.com/dotnet/api/?view=win-comm-toolkit-dotnet-stable).

## Windows Community Toolkit Sample App :iphone:
Want to see the toolkit in action before jumping into the code? Download and play with the [Windows Community Toolkit Sample App](https://www.microsoft.com/store/apps/9nblggh4tlcq) from the Store.

## Contribution :rocket:
Do you want to contribute? Check out our [Windows Community Toolkit Wiki](https://aka.ms/wct/wiki) page to learn more about contribution and guidelines.

## NuGet Packages :package:
NuGet is a standard package manager for .NET applications which is built into Visual Studio. When you open solution in Visual Studio, choose the *Tools* menu > *NuGet Package Manager* > *Manage NuGet packages for solution...* Enter one of the package names mentioned in [Windows Community Toolkit Nuget Packages](https://docs.microsoft.com/en-us/windows/communitytoolkit/nuget-packages) table to search for it online.

## <a name="supported"></a> Features :mailbox:
The [Features list](https://github.com/MicrosoftDocs/WindowsCommunityToolkitDocs/blob/master/docs/toc.md#controls) refers to all the currently available features that can be found in the Windows Community Toolkit. Most features should work with the October 2018 Update (1809) SDK 17763 and above; however, refer to specific documentation on each feature for more information.

## Principles :ballot_box_with_check:
* Principle **#1**: The toolkit will be kept simple.
* Principle **#2**: As soon as a comparable feature is available in the Windows SDK for Windows 10, it will be marked as deprecated.
* Principle **#3**: All features will be supported for two Windows SDK for Windows 10 release cycles or until another principle supersedes it.

## Roadmap :earth_americas:
Read what we [plan for next iterations](https://github.com/windows-toolkit/WindowsCommunityToolkit/milestones), and feel free to ask questions.

Check out our [Preview Packages Wiki Page](https://github.com/windows-toolkit/WindowsCommunityToolkit/wiki/Preview-Packages) to learn more about updating your NuGet sources in Visual Studio, then you can also get pre-release packages of upcoming versions to try.

## Code of Conduct :page_facing_up:
This project has adopted the code of conduct defined by the [Contributor Covenant](http://contributor-covenant.org/)
to clarify expected behavior in our community.
For more information see the [.NET Foundation Code of Conduct](CODE_OF_CONDUCT.md).

## .NET Foundation
This project is supported by the [.NET Foundation](http://dotnetfoundation.org).
