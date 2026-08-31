close minimize and maximize buttons

WPF Project အသစ်တစ်ခု ဖန်တီး

# Project Folder အသစ်ဆောက်ပါ

mkdir StoryApp

cd StoryApp

# WPF C# Project အသစ်ဖန်တီးပါ

dotnet new wpf

--------

#Packages (NuGet Libraries) သွင်းခြင်း

dotnet add package Wpf.Ui --version 3.0.5

dotnet add package Microsoft.Web.WebView2 --version 1.0.2903.40

dotnet add package Newtonsoft.Json --version 13.0.3

---

#ဖိုင်သို့သွား-

code .

---------

#ကုတ်ရေး

---
#Run ကြည့်ခြင်း

dotnet clean

dotnet run

----------

#.exe ဖိုင်တစ်ဖိုင်တည်း ပေါင်းထုတ်ယူခြင်း

dotnet publish -c Release -r win-x64 --self-contained true /p:PublishSingleFile=true /p:EnableCompressionInSingleFile=true

--------

#.exe ဖိုင် ရယူရန် လမ်းကြောင်း:

ProjectFolder\bin\Release\net8.0-windows\win-x64\publish\StoryAppApiDesktop.exe

----------

dotnet clean

dotnet restore

dotnet run

------------------------------------------------------------
# ၁။ Package အမှားကို ဖြုတ်ပါ

dotnet remove package WPF.UI

# ၂။ Package အမှန်ကို ပြန်သွင်းပါ (Wpf.Ui)

dotnet add package Wpf.Ui --version 3.0.5

# ၃။ WebView2 နှင့် Json Package များ စစ်ဆေးသွင်းယူပါ

dotnet add package Microsoft.Web.WebView2 --version 1.0.2903.40

dotnet add package Newtonsoft.Json --version 13.0.3
