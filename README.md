# TERA Novadrop Helper
Simple winforms application which serves an UI to use Novadrop CLI

![1](https://i.ibb.co/SmGkqxx/Screenshot-137.png)

![2](https://i.ibb.co/1K8xbbD/Screenshot-138.png)

![3](https://i.ibb.co/sKpX3LK/Screenshot-139.png)

# Implemented Functionality**

- DataCenter pack / unpack UI
- Resources pack / unpack UI
- Schemas generation UI

# Requisites

1. Compiled binaries of [Novadrop](https://github.com/vezel-dev/novadrop)
2. [.Net Runtime Desktop](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.14-windows-x64-installer)

Recommended: Precompiled [Novadrop binaries](https://www.mediafire.com/file/mxsu22uixhya0q7/novadrop.zip/file)

# Pre-Configuration

Folders must follow this structure, place the binaries and their corresponding dlls into their respective folders.

novadrop
  
├── novadrop-dc-x64
  
├── novadrop-dc-x86
  
└── novadrop-rc

The app automatically generates a DataCenter.xml file to persist certain configurations. You can also add more branches by following this structure.

BranchName Text="Branch Name" Value="KEY,IV"

Ex
BranchName Text="100.02 EUR" Value="1C01C904FF76FF06C211187E197B5716,396C342C52A0C12D511DD0209F90CA7D"

# CREDITS

[Novadrop](https://github.com/vezel-dev/novadrop)

[hsdn](https://forum.ragezone.com/members/hsdn.2000292876/)

# DISCLAIMER**

This app doesn't replace or perform the functionality of Novadrop, it simply facilitates its use.
