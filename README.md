#   ![ico](/readme-assets/favicon.png) Browserium 

#### Browserium is a simple and secure Web Browser

# New Features!

  - Browserium is based on Chromium
  - Added function on:
```csharp
private void urlbx_KeyDown(object sender, KeyEventArgs e)
        {
            if (e.KeyCode == Keys.Enter)
            {
                browser.Load(urlbx.Text);
            }
        }
```
# You can now:
##### use the enter key to load the url on ``` urlbx ``` or
##### use the search "🔍" button

### Get Browserium
#### No installation required

    Note: important application files are stored in the folder, Do not delete the folder. 
    For better experience store the folder in the C:\ Drive in your System
    
1. Download the latest .zip release from the releases tab and unzip it

2. Unzip and run ``Browserium.exe``

3. Right-Click the ``Browserium.exe`` file > and send to > Desktop(Create Shortcut)........(optional)

### Development
    Note: You need a x64 architecture PC
Want to build for yourself or contribute? Great!

Get Visual Studio from "https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Community&rel=16"
While installing Visual Studio Community 2019 select these individual components:
```
.NET 5.0 Runtime
.NET Core 2.1 Runtime (LTS)
.NET Core 3.1 Runtime (LTS)
.NET Framework 4 targeting pack
.NET Framework 4.5 targeting pack
.NET Framework 4.5.1 targeting pack
.NET Framework 4.5.2 targeting pack
.NET Framework 4.6 targeting pack
.NET Framework 4.6.1 targeting pack
.NET Framework 4.7.2 targeting pack
.NET Framework 4.8 SDK
.NET Native
.NET SDK
MLNET Model Builder (Preview)
Developer Analytics tools
Git for Winodws (Optional)
GitHub extension for Vidual Studio (Optional)
NuGet Package Manager
Text template Transformation
C# and Visual Basic Roslyn compilers
C++ 2019 Redistributable Update
C++ Make tools for Windows
C++ Universal Windows Platform support for v142 build tools (ARM64)
C++/CLI support for v142 build tools (14.28)
MSBuild
MSVC v142 -VS 2019 C++ ARM build Tools (v14.28)
MSVC v142 - VS 2019 C++ ARM64 build tools (v14.28
MSVC v142 - VS 2019 C++ x64/x86 build tools (v14.28)
.NET profiling tools
C++ AddressSanitizer (Experimental)
C++ profiling tools
JavaScript diagnostics
Just-In-Time debugger
Test Adapter for Boost.Test
Test Adapter for Google Test
C# and Visual Basic
C++ and Core features
F# Languafe Support
IntelliCode
LiveShare
Graphics debugger and GPU profiler for DirectX
Image and 3D model editors 
C++ ATL for latest v142 build tools (x86 & x64)
C++ MFC for latest v142 build tools (x86 & x64)
Entity Framework 6 tools
Windows 10 SDK (10.0.18362.0)
Windows 10 SDK (10.0.19041.0)
```
Get the project Source code from This link and unzip it : https://drive.google.com/drive/folders/1fy1RdKtiRb-r6TAz5N7ThurVVO8jMtaI?usp=sharing

- Open your Visual Studio and complete the setup process.
- Click on open a project or solution, Navigate to the unzipped folder and select .sln file
- You should see a window named Form1.cs[Design], if you dont see it then Double-Click on the Form1.cs in the Soulution Explorer Under TBrowser
- To add components to the from, click on the toolbox tab on the left.
- Then Drag And Drop Components.
esign] tab.
- To run the browser, click start
- -If errors show up, then check if you have installed all the above components. If all are installed and you still get the errors post the error code and error description in the issues tab of this repository.

# To Make your own Browser

Refer to this .docx file: The link will be here soon
