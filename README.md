# TERA Novadrop Helper
Simple winforms application which serves an UI to use Novadrop CLI

![1](https://ss.archgeus.com/u/Oj8XcP.png)

![2](https://ss.archgeus.com/u/cpzSrV.png)

![3](https://i.ibb.co/sKpX3LK/Screenshot-139.png)

# Implemented Functionality**

- DataCenter pack / unpack / validate / verify UI
- Resources pack / unpack UI
- Schemas generation UI

# Requisites

1. Compiled binaries of [Novadrop](https://github.com/vezel-dev/novadrop)
2. [.Net SDK 9](https://dotnet.microsoft.com/es-es/download/dotnet/thank-you/sdk-9.0.101-windows-x64-installer)

Recommended: Precompiled [Novadrop binaries](https://www.mediafire.com/file/tightf0bvp1cegf/novadrop.zip/file)

# Pre-Configuration

Folders must follow this structure, place the binaries and their corresponding dlls into their respective folders.

novadrop\
  
├── dc
  
└── rc

The app automatically generates a DataCenter.xml file to persist certain configurations. You can also add more branches by following this structure.

BranchName Text="Branch Name" Value="KEY,IV"

Ex
BranchName Text="100.02 EUR" Value="1C01C904FF76FF06C211187E197B5716,396C342C52A0C12D511DD0209F90CA7D"

# CREDITS

[Novadrop](https://github.com/vezel-dev/novadrop)

[hsdn](https://forum.ragezone.com/members/hsdn.2000292876/)

# DISCLAIMER**

This app doesn't replace or perform the functionality of Novadrop, it simply facilitates its use.
