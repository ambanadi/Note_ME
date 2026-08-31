**သာလီစွပါ**

အမှားတိ ပါကောင်းပါနိုင်ပါရေ၊ ယကေလည်း မှတ်စုဖြစ်တွက်နန့် မှတ်စုလို့ရာ သဘောထားပီးပါ


# Windows CMD Commands အပြည့်အစုံလမ်းညွှန်

## ၁။ စနစ်အခြေခံ Command များ (System Commands)

| အမိန့် | ရှင်းလင်းချက် | ဥပမာ |
|--------|---------------|--------|
| `systeminfo` | ကွန်ပျူတာ၏ OS နှင့် hardware အချက်အလက်အားလုံးကို ကြည့်ရန် | `systeminfo` |
| `hostname` | မိမိကွန်ပျူတာ၏ အမည်ကို ကြည့်ရန် | `hostname` |
| `ver` | အသုံးပြုနေသော Windows Version ကို ကြည့်ရန် | `ver` |
| `whoami` | လက်ရှိအသုံးပြုနေသော User အကောင့်အမည်ကို ကြည့်ရန် | `whoami` |
| `whoami /priv` | လက်ရှိ User အကောင့်၏ လုပ်ပိုင်ခွင့်များကို စစ်ဆေးရန် | `whoami /priv` |
| `whoami /groups` | User အကောင့်ပါဝင်သော Groups များကို စစ်ဆေးရန် | `whoami /groups` |
| `date` | လက်ရှိရက်စွဲကို ကြည့်ရန်/ပြင်ရန် | `date` |
| `time` | လက်ရှိအချိန်ကို ကြည့်ရန်/ပြင်ရန် | `time` |
| `cls` | CMD screen ပေါ်ရှိ စာဟောင်းများကို ရှင်းလင်းရန် | `cls` |
| `exit` | CMD window ကို ပိတ်ရန် | `exit` |
| `help` | အသုံးပြုနိုင်သော command များစာရင်းကို ကြည့်ရန် | `help` |
| `prompt` | CMD ၏ ရှေ့ဆုံးစာသား (Prompt) ကို ပြောင်းလဲရန် | `prompt $g` |
| `title [စာသား]` | CMD Window ၏ ခေါင်းစဉ် (Title bar) ကို ပြောင်းရန် | `title My Command` |
| `color [ကုဒ်]` | CMD စာသားနှင့် နောက်ခံအရောင် ပြောင်းရန် | `color 0a` |
| `cmd /k [Command]` | Command Run ပြီး CMD ဆက်ဖွင့်ထားရန် | `cmd /k ipconfig` |
| `cmd /c [Command]` | Command Run ပြီး CMD အလိုအလျောက်ပိတ်ရန် | `cmd /c dir` |

## ၂။ ဖိုင်/ဖိုဒါ စီမံခန့်ခွဲမှု (File/Folder Management)

| အမိန့် | ရှင်းလင်းချက် | ဥပမာ |
|--------|---------------|--------|
| `dir` | လက်ရှိ Folder ထဲရှိ ဖိုင်နှင့် folder စာရင်းကို ကြည့်ရန် | `dir` |
| `dir /p` | စာရင်းရှည်နေပါက တစ်မျက်နှာချင်းစီ ကြည့်ရန် | `dir /p` |
| `dir /w` | စာရင်းကို အကျဉ်းချုံးပြီး ဘေးတိုက်ကြည့်ရန် | `dir /w` |
| `dir /a` | ဖျောက်ထားသော (Hidden) ဖိုင်များအပါအဝင် အားလုံးကို စစ်ဆေးရန် | `dir /a` |
| `dir /s` | Folder အခွဲများနှင့် ဖိုင်အားလုံးကို ရှာဖွေစစ်ဆေးရန် | `dir /s` |
| `dir /od` | ဖိုင်များကို ရက်စွဲအလိုက် အစဉ်လိုက် စစ်ဆေးရန် | `dir /od` |
| `dir /ah` | ဖျောက်ထားသော (Hidden) ဖိုင်များကိုသာ သီးသန့် ကြည့်ရန် | `dir /ah` |
| `dir /as` | Windows System ဖိုင်များကိုသာ သီးသန့် ကြည့်ရန် | `dir /as` |
| `cd [လမ်းကြောင်း]` | သတ်မှတ်ထားသော Folder ထဲသို့ ဝင်ရန် | `cd C:\Windows` |
| `cd ..` | လက်ရှိ Folder ၏ အပြင်ဘက်သို့ ထွက်ရန် | `cd ..` |
| `cd \` | Drive တစ်ခုလုံး၏ Root Directory သို့ သွားရန် | `cd \` |
| `[Drive အက္ခရា]:` | Drive ပြောင်းရန် | `D:` |
| `tree` | Folder တည်ဆောက်ပုံကို သစ်ပင်ပုံစံဖြင့် ကြည့်ရန် | `tree` |
| `tree /f` | Folder ဖွဲ့စည်းပုံနှင့်အတူ ဖိုင်များကိုပါ တွဲကြည့်ရန် | `tree /f` |
| `tree /a` | ASCII စာသားများဖြင့် သစ်ပင်ပုံစံ ပြသရန် | `tree /a` |
| `path` | Windows က ရှာဖွေအလုပ်လုပ်သော လမ်းကြောင်းများကို ကြည့်ရန် | `path` |
| `pushd [လမ်းကြောင်း]` | လက်ရှိလမ်းကြောင်းကို မှတ်သားပြီး လမ်းကြောင်းအသစ်သို့ သွားရန် | `pushd C:\Temp` |
| `popd` | pushd ဖြင့် မှတ်သားခဲ့သော မူလလမ်းကြောင်းသို့ ပြန်သွားရန် | `popd` |
| `mkdir [အမည်]` (md) | Folder အသစ်တစ်ခု တည်ဆောက်ရန် | `mkdir NewFolder` |
| `rmdir [အမည်]` (rd) | Folder တစ်ခုကို ဖျက်ပစ်ရန် | `rmdir OldFolder` |
| `rd /s /q [အမည်]` | Folder နှင့် အထဲရှိဖိုင်အားလုံးကို မေးခွန်းမမေးဘဲ ဖျက်ရန် | `rd /s /q Temp` |
| `echo [စာသား] > file.txt` | စာသားပါဝင်သော Text ဖိုင်အသစ်တစ်ခု တည်ဆောက်ရန် | `echo Hello > hello.txt` |
| `type [ဖိုင်အမည်]` | Text ဖိုင်တစ်ခုထဲက စာသားများကို CMD ထဲမှာတင် ဖတ်ရန် | `type hello.txt` |
| `type NUL > file.txt` | ၀ Bytes ရှိသော ဖိုင်အလွတ်တစ်ခုကို ချက်ချင်းတည်ဆောက်ရန် | `type NUL > empty.txt` |
| `del [ဖိုင်အမည်]` | ဖိုင်တစ်ခုကို ဖျက်ရန် | `del test.txt` |
| `del *.txt` | လက်ရှိ Folder ထဲရှိ .txt ဖိုင်အားလုံးကို တစ်ပြိုင်နက်ဖျက်ရန် | `del *.txt` |
| `copy [မူရင်း] [အသစ်]` | ဖိုင်တစ်ခုကို တခြားနေရာသို့ ကူးယူ (Copy) ရန် | `copy file.txt D:\Backup\` |
| `move [မူရင်း] [အသစ်]` | ဖိုင်ကို တခြားနေရာသို့ ရွှေ့ရန် သို့မဟုတ် အမည်ပြောင်းရန် | `move file.txt D:\New\` |
| `ren [မူရင်းအမည်] [အမည်သစ်]` | ဖိုင် သို့မဟုတ် Folder အမည်ပြောင်းရန် | `ren old.txt new.txt` |
| `attrib [ဖိုင်လမ်းကြောင်း]` | ဖိုင်၏ ဂုဏ်သတ္တိ (Hidden, Read-only) ကို စစ်ဆေးရန် | `attrib file.txt` |
| `attrib +h [ဖိုင်အမည်]` | ဖိုင် သို့မဟုတ် Folder ကို ဖျောက်ထားရန် (Hidden) | `attrib +h secret` |
| `attrib -h [ဖိုင်အမည်]` | ဖျောက်ထားသော ဖိုင် သို့မဟုတ် Folder ကို ပြန်ဖော်ရန် | `attrib -h secret` |
| `attrib +r [ဖိုင်အမည်]` | ဖိုင်ကို Read-only (ဖတ်ရုံသာရပြီး ပြင်မရအောင်) လုပ်ရန် | `attrib +r important.txt` |
| `where [ဖိုင်အမည်]` | ရှာဖွေနေသောဖိုင် မည်သည့်လမ်းကြောင်းမှာ ရှိကြောင်း ရှာရန် | `where notepad.exe` |
| `where /r [လမ်းကြောင်း] *.dll` | Folder တစ်ခုလုံးနှင့် အခွဲများထဲရှိ .dll ဖိုင်အားလုံးကို ရှာဖွေရန် | `where /r C:\Windows *.dll` |
| `comp` | ဖိုင်နှစ်ခု၏ ပါဝင်မှုကို နှိုင်းယှဉ်ကြည့်ရန် | `comp file1.txt file2.txt` |
| `fc [ဖိုင်၁] [ဖိုင်၂]` | ဖိုင်နှစ်ခု၏ ကွာခြားချက်ကို ဖော်ပြရန် (File Compare) | `fc file1.txt file2.txt` |
| `sort` | စာသားများကို အက္ခရာစဉ်အလိုက် စီရန် | `sort list.txt` |
| `find "[စာသား]" [ဖိုင်အမည်]` | ဖိုင်တစ်ခုထဲက မိမိလိုချင်သော စာသားကို ရှာဖွေရန် | `find "error" log.txt` |
| `clip` | CMD မှ ထွက်လာသော စာသားများကို Clipboard ထဲသို့ Copy ကူးထည့်ရန် | `ipconfig \| clip` |
| `[Command] > output.txt` | ထွက်လာမယ့် စာသားများကို .txt ဖိုင်ထဲ သိမ်းရန် | `dir > list.txt` |
| `[Command] >> output.txt` | ထွက်လာမယ့် စာသားများကို ရှိပြီးသား ဖိုင်ထဲ ထပ်တိုးသိမ်းရန် | `echo Hello >> log.txt` |
| `[Command] 2> error.log` | Command Error မက်ဆေ့ခ်ျများကိုသာ ဖိုင်ထဲထုတ်ရေးရန် | `dir xyz 2> error.log` |

## ၃။ Robocopy နှင့် အဆင့်မြင့်ဖိုင်စီမံခန့်ခွဲမှု (Advanced File Management)

| အမိန့် | ရှင်းလင်းချက် | ဥပမာ |
|--------|---------------|--------|
| `robocopy [မူရင်း] [နေရာသစ်]` | ဖိုင်အမြောက်အမြားကို မြန်ဆန်စိတ်ချစွာ Copy ကူးရန် | `robocopy C:\Data D:\Backup` |
| `robocopy [မူရင်း] [နေရာသစ်] /E /ZB /R:5 /W:5` | လိုင်းပြတ်သွားရင်တောင် ဆက်ကူးပေးမယ့် စိတ်ချရဆုံး ဖိုင်ကူးယူနည်း | `robocopy C:\Data D:\Backup /E /ZB /R:5 /W:5` |
| `robocopy [မူရင်း] [နေရာသစ်] /MIR` | မူရင်း Folder အတိုင်း နေရာသစ်မှာ ထပ်တူကျအောင် ပြုလုပ်ခြင်း (Mirroring) | `robocopy C:\Data D:\Backup /MIR` |
| `robocopy [မူရင်း] [နေရာသစ်] /MOV` | ဖိုင်များကို Copy မဟုတ်ဘဲ ရွှေ့ (Move) ပစ်ရန် | `robocopy C:\Data D:\Backup /MOV` |
| `robocopy [မူရင်း] [နေရာသစ်] /Z` | လိုင်းပြတ်သွားရင် ပြန်ဆက်ကူးနိုင်အောင် သုံးရန် | `robocopy C:\Data D:\Backup /Z` |
| `replace [မူရင်းဖိုင်] [ပစ်မှတ်လမ်းကြောင်း]` | ပစ်မှတ်လမ်းကြောင်းထဲက ဖိုင်ဟောင်းတွေကို ဖိုင်အသစ်နဲ့ အစားထိုးရန် | `replace new.txt D:\Folder` |
| `replace [မူရင်းဖိုင်] [ပစ်မှတ်လမ်းကြောင်း] /A` | ပစ်မှတ်လမ်းကြောင်းထဲမှာ မရှိသေးတဲ့ ဖိုင်အသစ်တွေကိုပဲ ရွေးထည့်ရန် | `replace new.txt D:\Folder /A` |
| `xcopy [မူရင်း] [နေရာသစ်] /O /X` | ဖိုင်များ၏ ပိုင်ဆိုင်ခွင့် (Ownership) နှင့် လုံခြုံရေးခွင့်ပြုချက် (ACL) ပါတွဲပြီး Copy ကူးရန် | `xcopy C:\Data D:\Backup /O /X` |
| `takeown /f [ဖိုင်လမ်းကြောင်း]` | စနစ်က ပိတ်ထားသောဖိုင်၏ ပိုင်ဆိုင်ခွင့် (Ownership) ကို သိမ်းပိုက်ရန် | `takeown /f C:\Windows\System32\file.dll` |
| `icacls [ဖိုင်လမ်းကြောင်း] /grant [User]:F` | ဖိုင်တစ်ခုကို အပြည့်အဝ ထိန်းချုပ်ခွင့် (Full Control) ပေးရန် | `icacls file.txt /grant User:F` |
| `icacls [ဖိုင်လမ်းကြောင်း] /deny [User]:R` | သတ်မှတ်ထားသော User ကို ဖိုင်ဖတ်ခွင့် ပိတ်ပင်ရန် | `icacls file.txt /deny User:R` |
| `mklink [အမည်သစ်] [မူရင်းဖိုင်]` | ဖိုင်တစ်ခုအတွက် Hard Link တည်ဆောက်ရန် | `mklink link.txt original.txt` |
| `mklink /d [အမည်သစ်] [မူရင်းဖိုဒါ]` | Folder များအတွက် Directory Symbolic Link တည်ဆောက်ရန် | `mklink /d link D:\Original` |
| `mklink /j [အမည်သစ်] [မူရင်းဖိုဒါ]` | Directory Junction ချိတ်ဆက်ရန် | `mklink /j link D:\Original` |
| `compact /c /s:[လမ်းကြောင်း]` | ဖိုင်နှင့် Folder များကို ချုံ့ (Compress) ပစ်ရန် | `compact /c /s:C:\Data` |
| `compact /u /s:[လမ်းကြောင်း]` | ချုံ့ထားသော ဖိုင်နှင့် Folder များကို မူလအတိုင်း ပြန်ဖြည်ရန် | `compact /u /s:C:\Data` |
| `expand [ဖိုင်အမည်].cab [ပစ်မှတ်နေရာ]` | Windows ၏ .CAB ဖိုင်များကို ပြန်ဖြည်ထုတ်ရန် | `expand file.cab D:\Extract` |
| `makecab [ဖိုင်အမည်]` | ဖိုင်တစ်ခုကို .CAB ဖိုင်အဖြစ် ပြောင်းလဲချုံ့ပစ်ရန် | `makecab file.txt file.cab` |
| `cipher /e [Folder လမ်းကြောင်း]` | Folder တစ်ခုလုံးကို စာဝှက် (Encrypt) ထားရန် | `cipher /e C:\Secret` |
| `cipher /d [Folder လမ်းကြောင်း]` | စာဝှက်ထားသော Folder ကို ပြန်ဖြည် (Decrypt) ရန် | `cipher /d C:\Secret` |
| `cipher /c [ဖိုင်လမ်းကြောင်း]` | ဖိုင် သို့မဟုတ် Folder တစ်ခု စာဝှက်ထားခြင်း ရှိမရှိ စစ်ဆေးရန် | `cipher /c file.txt` |
| `cipher /w:[လမ်းကြောင်း]` | ဖျက်ပြီးသားဖိုင်များကို ဆယ်မရအောင် အပြီးတိုင် ဖျက်ဆီးပစ်ရန် | `cipher /w:C:\` |
| `cipher /r:[ဖိုင်အမည်]` | Cipher စနစ်အတွက် Encryption Key နှင့် Certificate များ ထုတ်လုပ်ရန် | `cipher /r:mykey` |

## ၄။ ကွန်ရက် (Network) Command များ

| အမိန့် | ရှင်းလင်းချက် | ဥပမာ |
|--------|---------------|--------|
| `ipconfig` | ကွန်ပျူတာ၏ IP Address နှင့် Network အချက်အလက်များကို ကြည့်ရန် | `ipconfig` |
| `ipconfig /all` | MAC Address, DNS, DHCP အပါအဝင် Network အသေးစိတ်ကို ကြည့်ရန် | `ipconfig /all` |
| `ipconfig /release` | လက်ရှိ IP address ကို ချိတ်ဆက်မှုမှ ဖြုတ်ချရန် | `ipconfig /release` |
| `ipconfig /renew` | IP Address အသစ်တစ်ခု ပြန်လည်တောင်းခံရန် | `ipconfig /renew` |
| `ipconfig /release6` | IPv6 လိပ်စာကို ဖြုတ်ချရန် | `ipconfig /release6` |
| `ipconfig /renew6` | IPv6 လိပ်စာအသစ် ပြန်လည်တောင်းခံရန် | `ipconfig /renew6` |
| `ipconfig /flushdns` | DNS Cache များကို ရှင်းလင်းရန် | `ipconfig /flushdns` |
| `ipconfig /displaydns` | DNS Cache စာရင်းကို စစ်ဆေးရန် | `ipconfig /displaydns` |
| `ipconfig /registerdns` | DNS Settings များကို ဆာဗာတွင် ပြန်လည်မှတ်ပုံတင်ရန် | `ipconfig /registerdns` |
| `ping [IP/Domain]` | တစ်ဖက်စက် သို့မဟုတ် ဝဘ်ဆိုက်နှင့် အင်တာနက်ချိတ်ဆက်မှု စစ်ဆေးရန် | `ping google.com` |
| `ping [IP] -t` | အင်တာနက်လိုင်းကို မရပ်မနား ဆက်တိုက်စစ်ဆေးရန် | `ping 8.8.8.8 -t` |
| `ping [IP] -n [အရေအတွက်]` | သတ်မှတ်ထားသော အကြိမ်ရေအလိုက်သာ Ping စစ်ရန် | `ping google.com -n 5` |
| `ping -4 google.com` | IPv4 စနစ်တစ်ခုတည်းဖြင့်သာ Ping စစ်ရန် | `ping -4 google.com` |
| `ping -6 google.com` | IPv6 စနစ်တစ်ခုတည်းဖြင့်သာ Ping စစ်ရန် | `ping -6 google.com` |
| `ping -l 65500 [IP]` | ဒေတာပမာဏ အအုပ်လိုက်ကြီး ပေးပို့ပြီး Network ခံနိုင်ရည် စစ်ရန် | `ping -l 65500 192.168.1.1` |
| `tracert [Domain]` | ဒေတာသွားသော လမ်းကြောင်းကို ခြေရာခံရန် | `tracert google.com` |
| `pathping [Domain]` | Ping နှင့် Tracert ပေါင်းစပ်ပြီး Packet ကျပျောက်မှုကို စစ်ဆေးရန် | `pathping google.com` |
| `nslookup [Domain]` | ဝဘ်ဆိုက်တစ်ခု၏ IP Address ကို ရှာဖွေရန် | `nslookup google.com` |
| `netstat` | လက်ရှိပွင့်နေသော Network ချိတ်ဆက်မှုအားလုံးကို ကြည့်ရန် | `netstat` |
| `netstat -a` | ပွင့်နေသော Port အားလုံးနှင့် အဝင်/အထွက် ချိတ်ဆက်မှုများကို စစ်ဆေးရန် | `netstat -a` |
| `netstat -an` | IP နံပါတ်များဖြင့် ချိတ်ဆက်မှုများကို စစ်ဆေးရန် | `netstat -an` |
| `netstat -o` | ချိတ်ဆက်မှုတစ်ခုချင်းစီကို မည်သည့် Process (PID) က သုံးနေလဲ စစ်ဆေးရန် | `netstat -o` |
| `netstat -e` | ဒေတာအဝင်အထွက် ပမာဏ (Bytes) အခြေအနေကို စစ်ဆေးရန် | `netstat -e` |
| `getmac` | Network ကတ်၏ MAC Address ကို ကြည့်ရန် | `getmac` |
| `arp -a` | Network ထဲတွင် ချိတ်ဆက်ထားသော အခြားစက်များ၏ IP နှင့် MAC ကိုကြည့်ရန် | `arp -a` |
| `arp -d *` | ARP cache ထဲတွင် မှတ်သားထားသော IP နှင့် MAC အဟောင်းများကို ရှင်းလင်းရန် | `arp -d *` |
| `route print` | ဒေတာသွားရာ လမ်းကြောင်းပြဇယား (Routing Table) ကို ကြည့်ရန် | `route print` |
| `route add 192.168.1.0 mask 255.255.255.0 192.168.1.1` | Routing Table ထဲသို့ လမ်းကြောင်းအသစ်တစ်ခု ထည့်သွင်းရန် | `route add 192.168.1.0 mask 255.255.255.0 192.168.1.1` |
| `route delete 192.168.1.0` | ထည့်ထားသော လမ်းကြောင်းကို ပြန်ဖျက်ရန် | `route delete 192.168.1.0` |
| `net view` | Network အတွင်း ရှိနေကြသော အခြားသော ကွန်ပျူတာများနှင့် Share Folder များကို စစ်ဆေးရန် | `net view` |
| `net view \\[ကွန်ပျူတာအမည်]` | Network ထဲက တခြားစက်တစ်ခုက Share လုပ်ထားတဲ့ ဖိုင်/ဖိုဒါတွေကို ကြည့်ရန် | `net view \\PC-Name` |
| `net share [အမည်]=[လမ်းကြောင်း]` | Folder တစ်ခုကို Network ပေါ်ရှိ အခြားသူများ သုံးနိုင်အောင် Share ပေးရန် | `net share Shared=D:\Shared` |
| `net share [အမည်] /delete` | Share ပေးထားသော Folder ကို ပြန်ပိတ်ရန် | `net share Shared /delete` |
| `net use Z: \\ComputerName\ShareName` | Network ပေါ်က Share Folder ကို Z Drive အဖြစ် ချိတ်ဆက်ရန် | `net use Z: \\PC\Shared` |
| `net use Z: /delete` | ချိတ်ထားသော Network Drive ကို ပြန်ဖြုတ်ရန် | `net use Z: /delete` |
| `netsh int ip reset` | TCP/IP settings များကို မူလအတိုင်း Reset ချရန် | `netsh int ip reset` |
| `netsh winsock reset` | Winsock Catalog ကို Reset ချရန် | `netsh winsock reset` |
| `netsh int tcp set global autotuninglevel=normal` | Internet Speed ကို အလိုအလျောက် မြှင့်တင်ပေးရန် | `netsh int tcp set global autotuninglevel=normal` |
| `netsh interface show interface` | Network ကတ်များ အလုပ်လုပ်မလုပ် စစ်ရန် | `netsh interface show interface` |

## ၅။ Wi-Fi ဆိုင်ရာ Command များ

| အမိန့် | ရှင်းလင်းချက် | ဥပမာ |
|--------|---------------|--------|
| `netsh wlan show profiles` | ချိတ်ဖူးသမျှ Wi-Fi အမည်များစာရင်းကို ကြည့်ရန် | `netsh wlan show profiles` |
| `netsh wlan show profile [Wi-Fiအမည်] key=clear` | ချိတ်ဖူးသော Wi-Fi ၏ Password ကို ပြန်ကြည့်ရန် | `netsh wlan show profile MyWiFi key=clear` |
| `netsh wlan show interfaces` | လက်ရှိချိတ်ထားသော Wi-Fi ၏ Signal နှင့် အမြန်နှုန်းကို စစ်ဆေးရန် | `netsh wlan show interfaces` |
| `netsh wlan show networks` | ပတ်ဝန်းကျင်တွင် ဖမ်းယူရရှိနိုင်သော Wi-Fi လိုင်းများကို စစ်ဆေးရန် | `netsh wlan show networks` |
| `netsh wlan show drivers` | Wi-Fi Driver အမျိုးအစားနှင့် ၎င်းထောက်ပံ့ပေးသော စနစ်များကို စစ်ဆေးရန် | `netsh wlan show drivers` |
| `netsh wlan delete profile name=[Wi-Fiအမည်]` | ချိတ်ဖူးတဲ့ Wi-Fi အကောင့်ကို အပြီးဖျက်ထုတ်ရန် | `netsh wlan delete profile name=MyWiFi` |
| `netsh wlan connect name=[Wi-Fi အမည်]` | CMD မှနေ၍ သတ်မှတ်ထားသော Wi-Fi သို့ ချိတ်ရန် | `netsh wlan connect name=MyWiFi` |
| `netsh wlan disconnect` | လက်ရှိချိတ်ထားသော Wi-Fi ကို ဖြတ်တောက်ရန် | `netsh wlan disconnect` |
| `netsh wlan set hostednetwork mode=allow ssid=[အမည်] key=[Password]` | Wi-Fi Hotspot လွှင့်ရန် စနစ်ထည့်သွင်းရန် | `netsh wlan set hostednetwork mode=allow ssid=MyHotspot key=password123` |
| `netsh wlan start hostednetwork` | Wi-Fi Hotspot ကို စတင်လွှင့်ရန် | `netsh wlan start hostednetwork` |
| `netsh wlan stop hostednetwork` | Wi-Fi Hotspot ကို ပြန်ပိတ်ရန် | `netsh wlan stop hostednetwork` |
| `netsh wlan export profile folder=[လမ်းကြောင်း] key=clear` | Wi-Fi Password အားလုံးကို .XML ဖိုင်များအဖြစ် သိမ်းဆည်းထုတ်ယူရန် | `netsh wlan export profile folder=C:\Backup key=clear` |

## ၆။ Firewall ဆိုင်ရာ Command များ

| အမိန့် | ရှင်းလင်းချက် | ဥပမာ |
|--------|---------------|--------|
| `netsh advfirewall set allprofiles state on` | Windows Firewall ကို အားလုံးအတွက် ဖွင့်ရန် | `netsh advfirewall set allprofiles state on` |
| `netsh advfirewall set allprofiles state off` | Windows Firewall ကို ပိတ်ပစ်ရန် | `netsh advfirewall set allprofiles state off` |
| `netsh advfirewall firewall show rule name=all` | Firewall ထဲက စည်းကမ်းချက် (Rules) အားလုံးကို စစ်ရန် | `netsh advfirewall firewall show rule name=all` |
| `netsh advfirewall reset` | Firewall Settings များကို မူလအတိုင်း Reset ချရန် | `netsh advfirewall reset` |
| `netsh advfirewall firewall add rule name="Block Port 80" protocol=TCP localport=80 action=block dir=IN` | Port 80 ကို ပိတ်ဆို့ရန် Firewall စည်းမျဉ်းအသစ် ထည့်သွင်းခြင်း | `netsh advfirewall firewall add rule name="Block Port 80" protocol=TCP localport=80 action=block dir=IN` |

## ၇။ စက်ပိတ်/ပြန်ဖွင့် (Shutdown/Restart) Command များ

| အမိန့် | ရှင်းလင်းချက် | ဥပမာ |
|--------|---------------|--------|
| `shutdown /s` | ကွန်ပျူတာကို ပိတ် (Shutdown) ရန် | `shutdown /s` |
| `shutdown /r` | ကွန်ပျူတာကို ပြန်ဖွင့် (Restart) ရန် | `shutdown /r` |
| `shutdown /g` | စက်ပိတ်ပြီး ပြန်ပွင့်လာလျှင် ယခင်ပွင့်နေသော application များကို ပြန်ဖွင့်ရန် | `shutdown /g` |
| `shutdown /l` | လက်ရှိ User အကောင့်မှ ထွက်ရန် (Log off) | `shutdown /l` |
| `shutdown /a` | စက်ပိတ်ရန် အချိန်ပေးထားမှုကို Cancel ရန် | `shutdown /a` |
| `shutdown /s /t [စက္ကန့်]` | အချိန်သတ်မှတ်ပြီး စက်ပိတ်ရန် | `shutdown /s /t 60` |
| `shutdown /i` | GUI box ဖြင့် Network ထဲက စက်များကို ပိတ်ရန် | `shutdown /i` |

## ၈။ Process နှင့် Service စီမံခန့်ခွဲမှု (Process & Service Management)

| အမိန့် | ရှင်းလင်းချက် | ဥပမာ |
|--------|---------------|--------|
| `tasklist` | လက်ရှိ အလုပ်လုပ်နေသော Software/Process အားလုံးကို ကြည့်ရန် | `tasklist` |
| `tasklist /svc` | Process တစ်ခုချင်းစီနှင့် သက်ဆိုင်သော Windows Services များကို တွဲဖက်စစ်ဆေးရန် | `tasklist /svc` |
| `tasklist /m` | Processes များသည် မည်သည့် .dll ဖိုင်များကို အသုံးပြုနေလဲ စစ်ဆေးရန် | `tasklist /m` |
| `tasklist /apps` | Windows Store Apps များကို သီးသန့် စစ်ဆေးရန် | `tasklist /apps` |
| `tasklist /fi "memusage gt 50000"` | RAM 50MB ထက်ပိုသုံးနေသော Processes များကို စစ်ထုတ်ရန် | `tasklist /fi "memusage gt 50000"` |
| `wmic process list brief` | Processes များ၏ အခြေခံ အချက်အလက်များကို စစ်ဆေးရန် | `wmic process list brief` |
| `wmic process get name,processid,executablepath` | Processes များ၏ အမည်၊ ID နှင့် ဖိုင်လမ်းကြောင်းကို စစ်ဆေးရန် | `wmic process get name,processid,executablepath` |
| `taskkill /im [process_name].exe` | ဟန်းနေသော software ကို အတင်းပိတ်ရန် | `taskkill /im chrome.exe` |
| `taskkill /pid [နံပါတ်] /f` | Process ID နံပါတ်ကို သုံးပြီး Software ကို အပြီးပိတ်ရန် | `taskkill /pid 1234 /f` |
| `wmic process where name="chrome.exe" call setpriority 128` | Software ကို High Priority သတ်မှတ်ရန် | `wmic process where name="chrome.exe" call setpriority 128` |
| `wmic process where name="ဆော့ဖ်ဝဲလ်" delete` | Software ကို အတင်းပိတ်ရန် | `wmic process where name="notepad.exe" delete` |
| `wmic startup list brief` | Startup ဆော့ဖ်ဝဲလ်များကို စစ်ဆေးရန် | `wmic startup list brief` |
| `wmic startup where name="[အမည်]" call delete` | Startup စာရင်းထဲမှ ဖယ်ထုတ်ရန် | `wmic startup where name="Skype" call delete` |
| `sc query` | Background Services စာရင်းကို ကြည့်ရန် | `sc query` |
| `sc query type= driver` | Hardware Drivers Services များကို သီးသန့် စစ်ဆေးရန် | `sc query type= driver` |
| `sc query [Service အမည်]` | ဝန်ဆောင်မှုတစ်ခု၏ လက်ရှိအခြေအနေကို စစ်ဆေးရန် | `sc query Spooler` |
| `net start` | လက်ရှိ စတင်အလုပ်လုပ်နေသော ဝန်ဆောင်မှုများကို စစ်ဆေးရန် | `net start` |
| `net start [ဝန်ဆောင်မှုအမည်]` | ရပ်တန့်နေသော Service ကို ပြန်ဖွင့်ရန် | `net start Spooler` |
| `net stop [ဝန်ဆောင်မှုအမည်]` | အလုပ်လုပ်နေသော Service ကို ပိတ်ရန် | `net stop Spooler` |

## ၉။ Hard Disk နှင့် Storage စီမံခန့်ခွဲမှု

| အမိန့် | ရှင်းလင်းချက် | ဥပမာ |
|--------|---------------|--------|
| `fsutil fsinfo drives` | ကွန်ပျူတာတွင် စိုက်ထားသော Drive အားလုံးကို စာရင်းထုတ်ကြည့်ရန် | `fsutil fsinfo drives` |
| `fsutil fsinfo drivetype C:` | Drive အမျိုးအစားကို စစ်ဆေးရန် | `fsutil fsinfo drivetype C:` |
| `fsutil volume diskfree C:` | C Drive တွင် ကျန်ရှိသော ပမာဏကို စစ်ဆေးရန် | `fsutil volume diskfree C:` |
| `vol` | Disk ၏ Volume Label နှင့် Serial Number ကို ကြည့်ရန် | `vol` |
| `vol C:` | C Drive ၏ Volume Label နှင့် Serial Number ကို စစ်ဆေးရန် | `vol C:` |
| `label [Drive အက္ခရာ]: [အမည်သစ်]` | Drive ၏ အမည်ကို ပြောင်းလဲရန် | `label D: MyDrive` |
| `wmic logicaldisk get caption,description,filesystem` | Drive များ၏ အမျိုးအစားနှင့် File System ကို စစ်ရန် | `wmic logicaldisk get caption,description,filesystem` |
| `wmic diskdrive get model,size,status` | Hard Disk အမျိုးအစား၊ ပမာဏနှင့် ကျန်းမာရေး (Status) ကို စစ်ဆေးရန် | `wmic diskdrive get model,size,status` |
| `wmic diskdrive get status` | Hard Disk သည် အဆင်ပြေပြေ အလုပ်လုပ်နေခြင်း ရှိမရှိ စစ်ဆေးရန် | `wmic diskdrive get status` |
| `chkdsk` | Hard Disk ထဲတွင် Error များ၊ ဖိုင်အပျက်အစီးများ ရှိမရှိ စစ်ဆေးရန် | `chkdsk` |
| `chkdsk C: /f` | C Drive ထဲတွင် Error တွေ့ပါက ပြုပြင်ရန် | `chkdsk C: /f` |
| `chkdsk C: /r` | Bad Sectors များကို ရှာဖွေပြီး ဒေတာများ ဆယ်ယူရန် | `chkdsk C: /r` |
| `chkntfs C:` | NTFS ပြဿနာ စစ်ဆေးမည့်စနစ် ပါမပါ စစ်ဆေးရန် | `chkntfs C:` |
| `defrag C: /a` | Defragmentation လိုအပ်ခြင်း ရှိမရှိ အကဲဖြတ် စစ်ဆေးရန် | `defrag C: /a` |
| `defrag C:` | Hard Disk ကို Defragment လုပ်ရန် | `defrag C:` |
| `cleanmgr` | Windows Disk Cleanup Tool ကို ဖွင့်ရန် | `cleanmgr` |
| `diskpart` | Partition ပိုင်းခြင်း၊ Format ချခြင်းများအတွက် Disk tool ကို ဖွင့်ရန် | `diskpart` |
| `format [Drive အက္ခရာ]:` | Drive တစ်ခုလုံးကို Format ချရန် | `format D:` |
| `powercfg /h on` | Hibernate စနစ်ကို ဖွင့်ရန် | `powercfg /h on` |
| `powercfg /h off` | Hibernate ကို ပိတ်ပြီး Storage နေရာချန်ရန် | `powercfg /h off` |

### Diskpart Command များ

| အမိန့် | ရှင်းလင်းချက် | ဥပမာ |
|--------|---------------|--------|
| `list disk` | Hard Disk အရေအတွက်နှင့် ပမာဏကို စစ်ဆေးရန် | `list disk` |
| `select disk [နံပါတ်]` | အလုပ်လုပ်မည့် Hard Disk ကို ရွေးချယ်ရန် | `select disk 0` |
| `list volume` | Partition အားလုံး၏ စာရင်းနှင့် ဖိုင်စနစ်ကို စစ်ဆေးရန် | `list volume` |
| `list partition` | သတ်မှတ်ထားသော Disk ထဲရှိ Partition ခွဲထားမှုများကို စစ်ဆေးရန် | `list partition` |
| `detail disk` | ရွေးချယ်ထားသော Disk ၏ အသေးစိတ် အချက်အလက်များကို စစ်ဆေးရန် | `detail disk` |
| `clean` | Hard Disk ထဲရှိ Partition များနှင့် ဒေတာအားလုံးကို ရှင်းလင်းပစ်ရန် | `clean` |
| `convert gpt` | Disk ကို MBR မှ GPT Format သို့ ပြောင်းရန် | `convert gpt` |
| `convert mbr` | Disk ကို GPT မှ MBR Format သို့ ပြောင်းရန် | `convert mbr` |
| `create partition primary size=[ပမာဏ-MB]` | Partition အသစ်တစ်ခု ဆောက်ရန် | `create partition primary size=50000` |
| `format fs=ntfs quick` | NTFS စနစ်ဖြင့် လျင်မြန်စွာ Format ချရန် | `format fs=ntfs quick` |
| `format fs=fat32 quick` | FAT32 စနစ်ဖြင့် Format ချရန် | `format fs=fat32 quick` |
| `assign letter=[အက္ခရာ]` | Drive အတွက် နံပါတ်သတ်မှတ်ပေးရန် | `assign letter=G` |
| `active` | Partition ကို Bootable Drive အဖြစ် သတ်မှတ်ရန် | `active` |
| `shrink desired=[ပမာဏ-MB]` | နေရာလွတ်ကို ဖဲ့ထုတ်ပြီး Partition အသစ်ခွဲရန် | `shrink desired=10000` |
| `extend` | နေရာလွတ်ကို ပေါင်းစပ်ပြီး Drive ပမာဏကို တိုးချဲ့ရန် | `extend` |
| `online disk` | Offline ဖြစ်နေသော Hard Disk ကို ပြန်လည် နိုးထစေရန် | `online disk` |
| `offline disk` | Hard Disk ကို ခေတ္တ Offline ဖြစ်အောင် လုပ်ထားရန် | `offline disk` |

## ၁၀။ System Maintenance နှင့် Repair Command များ

| အမိန့် | ရှင်းလင်းချက် | ဥပမာ |
|--------|---------------|--------|
| `sfc /verifyonly` | System ဖိုင်များ ပျက်စီးနေမှု ရှိမရှိကိုသာ စစ်ဆေးရန် | `sfc /verifyonly` |
| `sfc /scannow` | System ဖိုင်များကို စစ်ဆေးပြီး ပျက်စီးနေပါက ပြန်ပြင်ရန် | `sfc /scannow` |
| `dism /online /cleanup-image /checkhealth` | Windows Image ဖိုင်များတွင် Error ရှိမရှိ အမြန် စစ်ဆေးရန် | `dism /online /cleanup-image /checkhealth` |
| `dism /online /cleanup-image /scanhealth` | Windows Image ဖိုင်များ ပျက်စီးနေမှုကို အသေးစိတ် စစ်ဆေးရန် | `dism /online /cleanup-image /scanhealth` |
| `dism /online /cleanup-image /restorehealth` | Windows Image အပျက်များကို အင်တာနက်မှတစ်ဆင့် ပြန်ပြင်ရန် | `dism /online /cleanup-image /restorehealth` |
| `dism /online /cleanup-image /analyzecomponentstore` | WinSxS folder ထဲက အမှိုက်တွေ နေရာမည်မျှ ယူနေလဲ ဆန်းစစ်ရန် | `dism /online /cleanup-image /analyzecomponentstore` |
| `dism /online /cleanup-image /startcomponentcleanup` | စနစ်အမှိုက်ဟောင်းများကို ရှင်းလင်းရန် | `dism /online /cleanup-image /startcomponentcleanup` |
| `bootrec /fixmbr` | Master Boot Record ကို ပြန်ပြင်ရန် | `bootrec /fixmbr` |
| `bootrec /fixboot` | Boot အပိုင်းကို ပြန်လည်တည်ဆောက်ရန် | `bootrec /fixboot` |
| `bootrec /rebuildbcd` | Boot Configuration Data ကို အစမှပြန်တည်ဆောက်ရန် | `bootrec /rebuildbcd` |
| `bcdedit` | Windows Boot Loader ၏ settings များကို ကြည့်ရန် | `bcdedit` |
| `bcdedit /set {current} description "Windows 11 PRO"` | Windows အမည်ကို ပြောင်းလဲရန် | `bcdedit /set {current} description "Windows 11 PRO"` |
| `bcdedit /timeout 5` | ရွေးချယ်ရမည့်အချိန်ကို ၅ စက္ကန့်ဟု သတ်မှတ်ရန် | `bcdedit /timeout 5` |
| `reagentc /info` | Windows Recovery Environment အခြေအနေကို စစ်ရန် | `reagentc /info` |
| `reagentc /enable` | Windows Recovery ကို ဖွင့်ရန် | `reagentc /enable` |
| `gpupdate /force` | Group Policy ပြောင်းလဲမှုများကို ချက်ချင်း သက်ရောက်စေရန် | `gpupdate /force` |
| `gpresult /r` | မည်သည့် Group Policy များ သက်ရောက်နေကြောင်း ကြည့်ရန် | `gpresult /r` |
| `driverquery` | Device Driver အားလုံးကို စာရင်းကြည့်ရန် | `driverquery` |
| `driverquery /v` | Drivers များ၏ အသေးစိတ် အချက်အလက်များကို စစ်ဆေးရန် | `driverquery /v` |

## ၁၁။ User နှင့် အကောင့် စီမံခန့်ခွဲမှု (User & Account Management)

| အမိန့် | ရှင်းလင်းချက် | ဥပမာ |
|--------|---------------|--------|
| `net user` | User အကောင့်အားလုံးကို စစ်ဆေးရန် | `net user` |
| `net user [အကောင့်အမည်]` | သတ်မှတ်ထားသော User အကောင့်၏ အသေးစိတ်ကို စစ်ဆေးရန် | `net user John` |
| `net user [အကောင့်အမည်] [စကားဝှက်အသစ်]` | Windows Password ကို အသစ်ပြောင်းရန် | `net user John NewPass123` |
| `net user [အကောင့်အမည်] /active:no` | User အကောင့်ကို ခေတ္တပိတ်ရန် | `net user John /active:no` |
| `net user [အကောင့်အမည်] /active:yes` | ပိတ်ထားသော User အကောင့်ကို ပြန်ဖွင့်ရန် | `net user John /active:yes` |
| `net user Administrator /active:yes` | Built-in Administrator အကောင့်ကို ဖော်ရန် | `net user Administrator /active:yes` |
| `net localgroup` | Local Groups အားလုံးကို စစ်ဆေးရန် | `net localgroup` |
| `net localgroup administrators` | Administrator အဖြစ် ရထားသူများကို စစ်ဆေးရန် | `net localgroup administrators` |
| `net localgroup Administrators [အကောင့်အမည်] /add` | User ကို Admin အဆင့်သို့ မြှင့်တင်ရန် | `net localgroup Administrators John /add` |
| `net localgroup Administrators [အကောင့်အမည်] /delete` | Admin အဆင့်မှ ပြန်ချရန် | `net localgroup Administrators John /delete` |
| `net accounts` | Password စည်းကမ်းချက်များကို စစ်ရန် | `net accounts` |
| `net accounts /minpwlen:8` | အနည်းဆုံး ၈ လုံး ရှိရမည်ဟု ကန့်သတ်ရန် | `net accounts /minpwlen:8` |
| `net accounts /maxpwage:30` | ရက်ပေါင်း ၃၀ ပြည့်လျှင် Password ပြောင်းရမည်ဟု ကန့်သတ်ရန် | `net accounts /maxpwage:30` |
| `runas /user:Administrator cmd.exe` | Admin လုပ်ပိုင်ခွင့်ဖြင့် CMD ဖွင့်ရန် | `runas /user:Administrator cmd.exe` |
| `query user` | စက်ထဲမှာ လာသုံးနေတဲ့ User စာရင်းကို ကြည့်ရန် | `query user` |
| `logoff` | လက်ရှိ အသုံးပြုသူကို Sign out လုပ်ပစ်ရန် | `logoff` |
| `msg [အကောင့်အမည်] "မင်္ဂလာပါ"` | အခြား user စခရင်ပေါ်သို့ Pop-up Message ပို့ရန် | `msg John "မင်္ဂလာပါ"` |

## ၁၂။ Scheduled Tasks စီမံခန့်ခွဲမှု

| အမိန့် | ရှင်းလင်းချက် | ဥပမာ |
|--------|---------------|--------|
| `schtasks /query` | Scheduled Tasks များကို စစ်ဆေးရန် | `schtasks /query` |
| `schtasks /create /tn "Backup" /tr "notepad.exe" /sc daily /st 12:00` | Task အသစ်တည်ဆောက်ရန် | `schtasks /create /tn "Backup" /tr "notepad.exe" /sc daily /st 12:00` |
| `schtasks /delete /tn "Backup" /f` | Task ကို အပြီးဖျက်ရန် | `schtasks /delete /tn "Backup" /f` |
| `schtasks /run /tn "Backup"` | Task ကို ချက်ချင်း အတင်းခိုင်းစေရန် | `schtasks /run /tn "Backup"` |
| `schtasks /end /tn "Backup"` | လက်ရှိ Run နေသော Task ကို ရပ်တန့်ပစ်ရန် | `schtasks /end /tn "Backup"` |
| `at` | သတ်မှတ်ထားခဲ့သော အလိုအလျောက် အလုပ်စာရင်းများကို စစ်ဆေးရန် | `at` |

## ၁၃။ Registry နှင့် System Configuration များ

| အမိန့် | ရှင်းလင်းချက် | ဥပမာ |
|--------|---------------|--------|
| `regedit` | Windows Registry Editor ကို ဖွင့်ရန် | `regedit` |
| `reg export [HKEY_လမ်းကြောင်း] [ဖိုင်အမည်.reg]` | Registry အပိုင်းကို Backup ထုတ်သိမ်းရန် | `reg export HKEY_CURRENT_USER\Software backup.reg` |
| `reg import [ဖိုင်အမည်.reg]` | Registry ဖိုင်ကို ပြန်ထည့်ရန် | `reg import backup.reg` |
| `reg add [HKEY_လမ်းကြောင်း] /v [အမည်] /t REG_SZ /d [ဒေတာ]` | Registry ထဲသို့ တန်ဖိုးအသစ်ထည့်ရန် | `reg add HKEY_CURRENT_USER\Software /v MyApp /t REG_SZ /d "Hello"` |
| `reg delete [HKEY_လမ်းကြောင်း] /f` | Registry ထဲက Key တစ်ခုကို ဖျက်ရန် | `reg delete HKEY_CURRENT_USER\Software\MyApp /f` |
| `assoc` | ဖိုင်အမျိုးအစားများကို မည်သည့် Software နှင့် တွဲဖွင့်ရမည်ကို ကြည့်ရန် | `assoc` |
| `assoc .txt=txtfile` | ဖိုင် extension ချိတ်ဆက်မှုကို မူလအတိုင်း ပြန်သတ်မှတ်ရန် | `assoc .txt=txtfile` |
| `ftype` | ဖိုင်အမျိုးအစားများနှင့် ဖွင့်ရမည့် Application Paths ကို စစ်ဆေးရန် | `ftype` |
| `set` | Environment Variables စာရင်းအားလုံးကို ကြည့်ရန် | `set` |
| `setx [Variable အမည်] "[တန်ဖိုး]"` | Environment Variable အသစ် အပြီးတိုင် သတ်မှတ်ရန် | `setx MY_PATH "C:\MyFolder"` |
| `path` | Executable ရှာဖွေလမ်းကြောင်းများကို ကြည့်ရန် | `path` |

## ၁၄။ System Information နှင့် Hardware စစ်ဆေးရေး

| အမိန့် | ရှင်းလင်းချက် | ဥပမာ |
|--------|---------------|--------|
| `msinfo32` | System အချက်အလက်များကို Window ပုံစံဖြင့် ကြည့်ရန် | `msinfo32` |
| `dxdiag` | Graphics နှင့် Sound ဆိုင်ရာ DirectX အချက်အလက်များကို ကြည့်ရန် | `dxdiag` |
| `wmic baseboard get product,Manufacturer` | Motherboard အမျိုးအစားနှင့် ထုတ်လုပ်သူကို စစ်ဆေးရန် | `wmic baseboard get product,Manufacturer` |
| `wmic bios get smbiosbiosversion` | BIOS ဗားရှင်းကို စစ်ဆေးရန် | `wmic bios get smbiosbiosversion` |
| `wmic bios get serialnumber` | စက်၏ Serial Number ကို သီးသန့်ထုတ်ကြည့်ရန် | `wmic bios get serialnumber` |
| `wmic cpu get name, NumberOfCores, MaxClockSpeed` | CPU အမျိုးအစား၊ Core အရေအတွက်နှင့် အမြန်နှုန်းကို စစ်ဆေးရန် | `wmic cpu get name, NumberOfCores, MaxClockSpeed` |
| `wmic memorychip get capacity, speed` | RAM ချောင်းတစ်ချောင်းချင်းစီ၏ ပမာဏနှင့် Bus Speed ကို စစ်ဆေးရန် | `wmic memorychip get capacity, speed` |
| `wmic memorychip get devicelocator, memorytype` | RAM Slot နေရာနှင့် အမျိုးအစားကို စစ်ဆေးရန် | `wmic memorychip get devicelocator, memorytype` |
| `wmic path win32_videocontroller get name` | Graphics Card (GPU) အမျိုးအစားကို စစ်ဆေးရန် | `wmic path win32_videocontroller get name` |
| `wmic sounddev get name` | Sound Card/Audio Device များကို စစ်ဆေးရန် | `wmic sounddev get name` |
| `wmic computersystem get model, manufacturer` | ကွန်ပျူတာ၏ မော်ဒယ်နှင့် ထုတ်လုပ်သူကို စစ်ဆေးရန် | `wmic computersystem get model, manufacturer` |
| `wmic csproduct get identifyingnumber` | စက်၏ Serial Number ကို စစ်ဆေးရန် | `wmic csproduct get identifyingnumber` |
| `wmic qfe list` | Windows Update မှတ်တမ်းများကို စစ်ဆေးရန် | `wmic qfe list` |
| `wmic path win32_physicalmedia get serialnumber` | Hard Disk တစ်လုံးချင်းစီ၏ Serial Number ကို ကြည့်ရန် | `wmic path win32_physicalmedia get serialnumber` |
| `wmic pagefile list /format:list` | Virtual Memory (Pagefile) အခြေအနေကို စစ်ရန် | `wmic pagefile list /format:list` |
| `powercfg /batteryreport` | Laptop ဘက်ထရီ ကျန်းမာရေးနှင့် သက်တမ်းကို စစ်ဆေးရန် | `powercfg /batteryreport` |
| `powercfg /energy` | ပါဝါသုံးစွဲမှုနှင့် စွမ်းအင်ဖြုန်းတီးမှုများကို စစ်ဆေးရန် | `powercfg /energy` |
| `powercfg /availablesleepstates` | Sleep/Hibernate စနစ်များကို ထောက်ပံ့လဲ စစ်ဆေးရန် | `powercfg /availablesleepstates` |
| `powercfg /lastwake` | Sleep ဖြစ်နေစဉ် မည်သည့်အရာက နှိုးလိုက်သလဲ စစ်ရန် | `powercfg /lastwake` |

## ၁၅။ Application Launcher များ

| အမိန့် | ရှင်းလင်းချက် | ဥပမာ |
|--------|---------------|--------|
| `notepad` | Notepad ကို ဖွင့်ရန် | `notepad` |
| `calc` | Calculator ကို ဖွင့်ရန် | `calc` |
| `control` | Control Panel ကို ဖွင့်ရန် | `control` |
| `eventvwr` | Event Viewer ကို ဖွင့်ရန် | `eventvwr` |
| `perfmon` | Performance Monitor ကို ဖွင့်ရန် | `perfmon` |
| `resmon` | Resource Monitor ကို ဖွင့်ရန် | `resmon` |
| `winget search [ဆော့ဖ်ဝဲလ်အမည်]` | Software ကို CMD မှ ရှာရန် | `winget search vlc` |
| `winget install [ဆော့ဖ်ဝဲလ်အမည်]` | Software ကို CMD မှ တိုက်ရိုက် သွင်းရန် | `winget install Google.Chrome` |
| `winget upgrade --all` | Software အားလုံးကို Update တင်ရန် | `winget upgrade --all` |
| `winget uninstall [ဆော့ဖ်ဝဲလ်အမည်]` | Software ကို CMD ကနေ ဖြုတ်ရန် | `winget uninstall VLC.VLC` |

## ၁၆။ Time Zone နှင့် အချိန်ဆိုင်ရာ

| အမိန့် | ရှင်းလင်းချက် | ဥပမာ |
|--------|---------------|--------|
| `tzutil /g` | လက်ရှိ Time Zone ကို ကြည့်ရန် | `tzutil /g` |
| `tzutil /l` | Time Zone စာရင်းအားလုံးကို ကြည့်ရန် | `tzutil /l` |
| `tzutil /s "Myanmar Standard Time"` | Time Zone ကို မြန်မာစံတော်ချိန်သို့ ပြောင်းရန် | `tzutil /s "Myanmar Standard Time"` |
| `net time \\localhost` | ဆာဗာနှင့် အချိန်ကို တိုက်ဆိုင်ညှိနှိုင်းရန် | `net time \\localhost` |

## ၁၇။ Scripting နှင့် Utility Command များ

| အမိန့် | ရှင်းလင်းချက် | ဥပမာ |
|--------|---------------|--------|
| `choice /c YNC /M "အလုပ်ဆက်လုပ်မလား"` | Yes, No, Cancel ရွေးချယ်စရာ Dialog ပေါ်လာအောင် လုပ်ဆောင်ရန် | `choice /c YNC /M "အလုပ်ဆက်လုပ်မလား"` |
| `timeout /t 10` | ၁၀ စက္ကန့် စောင့်ခိုင်းရန် | `timeout /t 10` |
| `timeout /t 10 /nobreak` | မည်သည့် ခလုတ်နှိပ်နှိပ် ကျော်သွားလို့မရဘဲ စောင့်ခိုင်းရန် | `timeout /t 10 /nobreak` |
| `pause` | "Press any key to continue..." ဆိုပြီး ခလုတ်နှိပ်မှ ရှေ့ဆက်သွားရန် | `pause` |
| `doskey /history` | ရိုက်ခဲ့သမျှ Command ရာဇဝင်ကို ပြန်ကြည့်ရန် | `doskey /history` |
| `doskey [အတိုကောက်]=[Command အရှည်]` | Command အတိုကောက် (Macro) သတ်မှတ်ရန် | `doskey ip=ipconfig /all` |
| `set /a [တွက်ချက်မှု]` | CMD ထဲမှာတင် သင်္ချာဂဏန်းများ တွက်ချက်ရန် | `set /a 5+10` |
| `[Command 1] && [Command 2]` | ပထမ Command အောင်မြင်မှ ဒုတိယ Command ကို ဆက် Run ရန် | `dir && echo Done` |
| `[Command 1] \|\| [Command 2]` | ပထမ Command Error တက်မှသာ ဒုတိယ Command ကို Run ရန် | `dir xyz \|\| echo Error` |
| `[Command 1] \| [Command 2]` | ပထမ Command မှ ရလဒ်ကို ဒုတိယ Command ထဲသို့ ပေးပို့ရန် (Piping) | `dir \| find ".txt"` |
| `mode con: cols=80 lines=25` | CMD Window အရွယ်အစားကို သတ်မှတ်ရန် | `mode con: cols=80 lines=25` |
| `break` | စနစ်တစ်ခုကို အတင်းအဓမ္မ ရပ်တန့်ခြင်း | `break` |
| `certutil -hashfile [ဖိုင်လမ်းကြောင်း] MD5` | ဖိုင်၏ MD5 Checksum စစ်ဆေးရန် | `certutil -hashfile file.txt MD5` |
| `certutil -encode [မူရင်းဖိုင်] [output.txt]` | ဖိုင်ကို Base64 Encoding ပြောင်းရန် | `certutil -encode file.exe output.txt` |
| `certutil -decode [စာသားဖိုင်] [output.exe]` | Base64 ကို မူရင်းဖိုင်အဖြစ် ပြန်ပြောင်းရန် | `certutil -decode output.txt file.exe` |

## ၁၈။ လုံခြုံရေးဆိုင်ရာ Command များ

| အမိန့် | ရှင်းလင်းချက် | ဥပမာ |
|--------|---------------|--------|
| `klist` | Kerberos လုံခြုံရေး လက်မှတ်များကို ကြည့်ရန် | `klist` |
| `klist purge` | Kerberos Tickets များကို ဖျက်ဆီးရန် | `klist purge` |
| `manage-bde -status` | BitLocker အခြေအနေကို စစ်ဆေးရန် | `manage-bde -status` |
| `manage-bde -lock C:` | C Drive ကို BitLocker ဖြင့် Lock လိုက်ရန် | `manage-bde -lock C:` |
| `manage-bde -unlock C: -Password` | Drive ကို Password ဖြင့် ပြန်ဖွင့်ရန် | `manage-bde -unlock C: -Password` |
| `cmdkey /list` | မှတ်သားထားသော Credentials စာရင်းကို ကြည့်ရန် | `cmdkey /list` |
| `cmdkey /delete:[TargetName]` | မှတ်ထားသော Password တစ်ခုကို ဖျက်ရန် | `cmdkey /delete:MicrosoftAccount` |

---

> 
