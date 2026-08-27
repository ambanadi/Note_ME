npm -v

https://nodejs.org/en/download

npm init -y  (Package.json ဖိုင် ဆောက်ရန်)

npm install @capacitor/core @capacitor/cli    (Capacitor Core များကို သွင်းရန်)

npx cap init  (Capacitor ကို စတင် Setup လုပ်ရန် - App Name နှင့် Package ID တို့ကို မေးပါလိမ့်မည်)

အရေးကြီးသော အချက်: npx cap init လုပ်သည့်အခါ web-dir (Web Asset Directory) နေရာတွင် မိမိ HTML ဖိုင်များရှိနေသည့် Folder အမည်ကို ထည့်ပေးရပါမည်။ ပုံမှန် HTML သီးသန့် ရေးထားခြင်းဖြစ်ပါက . (အစက်တစ်ခုတည်း) ဟု ရိုက်ထည့်ပါ။


Android SDK Platform ကို ထပ်မံ ထည့်သွင်း

npm install @capacitor/android

npx cap add android


npx cap open android (ဤ Command သည် Android Studio ကို အလိုအလျောက် ဖွင့်ပေးမည် ဖြစ်သည်)

Build > Build Bundle(s) / APK(s) > Build APK(s) ကို နှိပ်ပါ။

npx cap sync  (ကုတ်ရေးတိုင်းပြန်စ)


PWA (Progressive Web App) နည်းလမ်း

manifest.json

{
  "name": "Football Club App",
  "short_name": "FC App",
  "start_url": "/index.php",
  "display": "standalone",
  "background_color": "#ffffff",
  "theme_color": "#000000",
  "icons": [
    { "src": "icon.png", "sizes": "512x512", "type": "image/png" }
  ]
}

<link rel="manifest" href="manifest.json">
