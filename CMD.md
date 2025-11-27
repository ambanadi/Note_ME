**သာလီစွပါ**

အမှားတိ ပါကောင်းပါနိုင်ပါရေ၊ ယကေလည်း မှတ်စုဖြစ်တွက်နန့် မှတ်စုလို့ရာ သဘောထားပီးပါ
<details>
<summary><b>🏗️Basic</b></summary>
  **Command > Sweitch > Arguments**

| CMD | DF |EX |
| --- | --- | --- |
|exit| ထွက် ||
|color| အရောင် |bg color,tex color|
|title| ဂေါင်းစိုင် ||
|runas| ခွင့်ပြုချက် |runas /user:administrator cmd|
|del /? (help)| အကူအညီ ||
|cd C:\ |C ထဲ| cd \(ဒေတိုင်လည်းလားနိုင်)|
|dir| ဖိုင်စစ် |dir /A (အကုန်စစ်)|
|dir **| ဖိုင်စစ်(Wild card) |dir *my_me*.* /s|
|dir *| ဖိုင်စစ်(Wild card) |dir*.pdf /s|
|find| စာရှာ |find "My" my.tex|
|cd (Users)| ထပ်ဝင်လိုဖိုင် ||
|cd ..| နောက်ပြန်ဆုတ်||
|md| ဖော်ဒါသစ် |md file1 file2|
|md "file me" | နာမည်နှစ်ပါရင် |" "|
|ren old new | နာမည်ပြောင်း ||
|rd me |ဖျက် ||
|re me /S|Dateရှိလျင်ဖျက် |Y/N အပြချင်ရင်( /q)|
|echo|ဖိုင်သစ် |echo my text > file.txt |
|more|အကုန်ဖတ်|more file.txt|
|edit|မှတ်စုရေး||
|del|ဖိုင်ဖျက်|del file.txt (eraseနန့်လေ့ဖျက်နိုင်)|
|erase|အပြီးဖျက်|erase /S file.txt /q|
|copy|ကူး| copy file.txt C:\ |
|xcopy|အကုန်ကူး|xcopy /S /I Myfoder C:\ User\MG|
|move|ပြောင်း| move file.txt C:\ |
|tree|ဖိုင်စစ်|tree /F|
|attrib|ဖိုင်ဝှက်|attrib +h +s file.txt|
</details>

<details>
<summary><b>🏗️Information</b></summary>
1.Serial Number

 wmic bios get serialnumber
 
2. Mac Address

wmic nic get macaddress
getmac

4. CPU

wmic cpu
wmic cpu get Name,NumberOfCores,NumberOfLogicalProcessors
systeminfo | findstr /I "Processor"
wmic cpu get caption, deviceid, name, numberofcores, maxclockspeed, status

6. RAM

wmic computersystem get totalphysicalmemory
wmic memorychip get capacity
wmic memorychip get speed
wmic memorychip list full
wmic Memphysical get MemoryDevices
wmic MemoryChip get BankLabel, DeviceLocator, Capacity

8. Partition

wmic partition get name,size,type

10. Process

wmic process list

12. Product

wmic product
wmic product get name,version

14. Window's Version

winver

16. Check Disk

chkdsk
systeminfo

18. Disk Details

  diskpart
  list disk
  select disk_name
  create partition primary
  format fs=ntfs label=Backup quick
  detail disk
  exit

20. hard disk
wmic diskdrive get name,model,size
    wmic diskdrive get model,index,firmwareRevision,status,interfaceType,totalHeads,totalTracks,totalCylinders,totalSectors,partitions
        fsutil fsinfo drives
        fsutil fsinfo volumelist
        fsutil fsinfo statistics C:

22. motherboard

wmic baseboard get product,manufacturer,version,serialnumber

24. graphics card

wmic path win32_VideoController get name

26. BIOS

wmic bios get smbiosbiosversion
wmic bios get serialnumber

28. OS
systeminfo
 systeminfo | findstr /B /C:"OS Name" /C:"OS Version"
ver
wmic os get Caption,Version,BuildNumber,OSArchitecture
systeminfo | find "System Boot Time"
driverquery

hostname
whoami

powercfg /batteryreport

29. licence os
slmgr /dlv
slmgr /xpr

30. driver list
driverquery /FO list /v
driverquery /FO list /v > "%USERPROFILE%\Desktop\drivers.txt"

32. system serial number
    wmic bios get serialnumber
    
34. system ip
ipconfig /all
ipconfig

36. system performance
    winsat formal
    netstat -n
    perfmon /res  (Launches Resource Monitor)
    perfmon /report (Generates a system diagnostics report)
    
38. Disk Performance and Health
    chkdsk C: /f
    defrag C:
    sfc /scannow
    
40. cpu load
    wmic cpu get loadpercentage /value

41. Netword
netstat (Active Connections)
netsh advfirewall show allprofiles (Firewall Status)
netsh wlan show interfaces
ipconfig /release
ipconfig /renew

Wi-Fi ON / OFF
netsh interface set interface name="Wi-Fi" admin=enabled

netsh interface set interface name="Wi-Fi" admin=disabled

Show All Network Interfaces
netsh interface show interface

Reset Network
netsh int ip reset
netsh winsock reset

Wi-Fi Password (Saved Networks)
netsh wlan show profiles
netsh wlan show profile name="WiFiName" key=clear 
 
42. ram free space
wmic ComputerSystem get TotalPhysicalMemory
wmic OS get FreePhysicalMemory
systeminfo | findstr /C:"Total Physical Memory"
</details>

<details>
<summary><b>🏗️Installation and Unistallation</b></summary>
Command > Sweitch > Arguments
</details>

<details>
<summary><b>🏗️Account</b></summary>
Command > Sweitch > Arguments
</details>

<details>
<summary><b>🏗️ Harddisk</b></summary>
Command > Sweitch > Arguments
</details>

<details>
<summary><b>🏗️Security</b></summary>
Command > Sweitch > Arguments
</details>

<details>
<summary><b>🏗️ Registry</b></summary>
Command > Sweitch > Arguments
</details>

<details>
<summary><b>🏗️ Syetem</b></summary>
Command > Sweitch > Arguments
</details>

<details>
<summary><b>🏗️Network</b></summary>
Command > Sweitch > Arguments
</details>

_  ```powershell

mkdir "%USERPROFILE%\Desktop\MyFolder"
--
rd /s /q "%USERPROFILE%\Desktop\MyFolder"
_
@echo off
rd /s /q "D:\Me"
echo Folder Deleted!
pause
---
@echo off
echo Computer will shutdown in 5 seconds...
shutdown /s /t 5
pause
-----------------
@echo off
C:
net user %username% jaiminpatel
