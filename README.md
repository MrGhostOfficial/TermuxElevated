## [+] Project InformatioN :
<p align="center"> <img src="https://github.com/MrGhostOfficial/Admin.Network/blob/master/snake.game.svg" alt="snake"> </center></p>

<div align="center" style="display: flex; justify-content: center; gap: 20px; align-items: center;">
  <img src="https://komarev.com/ghpvc/?username=MrGhostOfficial&label=Profile+Views&color=0e75b6&style=flat" />
  <img src="https://img.shields.io/github/repo-size/MrGhostOfficial/TermuxElevated.svg" />
</div>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=MrGhostOfficial&theme=github_dark" alt="GitHub Profile Summary" />

<table border="0" align="center"> <tr border="0"> <td width="50%" align="center"> <img align="center" src="https://github-readme-stats.vercel.app/api?username=MrGhostOfficial&show_icons=true&theme=dark" /></p>

<p> <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MrGhostOfficial&show_icons=true&theme=dark" /></p>
</tr>
</table>

<div align="center">
  <img src="https://raw.githubusercontent.com/MrGhostOfficial/Admin.Network/master/USDT_Binance.png" />
  <h3><b>Binance: BSC<br>BNB Smart Chain (BEP20)</b></h3>
</div>

```
0xdfb08fe456e54571445174e3822f226b11c1756c
```

<a href="https://t.me/NetCyberCoder">
  <img src="https://img.shields.io/badge/Chat-Telegram-blue?style=for-the-badge&logo=telegram" alt="Chat-Telegram">
</a>
<a href="https://m.youtube.com/@HackerFake424/" target="_blank">
  <img src="https://img.shields.io/badge/YOUTUBE-HackerFake424-red?style=flat-square&logo=youtube" alt="YouTube">
</a>
<a href="https://m.youtube.com/@HackerFake424/" target="_blank">
  <img src="https://img.shields.io/badge/Gitlab-MrGhostOfficial-green?style=for-the-badge&logo=gitlab)](https://gitlab.com/MrGhostOfficial" alt="Gitlab">
</a>
<p align="center">
  <img   src="https://github.com/MrGhostOfficial/Admin.Network/blob/master/Anonymous.png?raw=true" 
    width=""
    style="border: 4px solid red; border-radius: 15px;"
  />
</p>
<p align="center">
      ⚠ My All Tools & Tips Made Just For Educational Purpose Only, IAM Not Responsible Any Miss Use, Enjoy.👾
</p>

# [ Termux Elevated Setup🙂 ]

[INFO] First Download and install This 7 Application in your phone. You can see All Applications Link, Size and Name is Here.🐸

<p>1. Apk Name: MT Manager.apk
   <br>Apk Size: 21MB
   21MB<br>↪️: https://binmt.lanzouy.com/b01bivkzc/</p>
<p>2. Apk Name: Hacker's Keyboard.apk
   <br>Apk Size: 2.71MB
   <br>↪️: https://f-droid.org/packages/org.pocketworkstation.pckeyboard/</p>
<p>3. Apk Name: Termux.apk
   <br>Apk Size: 109.60MB
   <br>↪️: https://f-droid.org/en/packages/com.termux/</p>
<p>4. Apk Name: Termux:API.apk
   <br>Apk Size: 2.74MB
   <br>↪️: https://f-droid.org/en/packages/com.termux.api/</p>
<p>5. Apk Name: Termux:X11.apk
   <br>Apk Size: 13.66MB
   <br>↪️: https://github.com/termux/termux-x11/releases/tag/nightly/</p>
<p>6. Apk Name: Termux:Float.apk
   <br>Apk Size: 2.12MB
   <br>↪️: https://f-droid.org/en/packages/com.termux.window/</p>
<p>7. Apk Name: Termux:Styling.apk
   <br>Apk Size: 18.50MB
   <br>↪️: https://f-droid.org/en/packages/com.termux.styling/</p>

# [ Download com.termux.tar.gz File Copy Code paste in Termux☟ ]
![Screenshot](https://raw.githubusercontent.com/MrGhostOfficial/Admin.Network/refs/heads/master/Terminal.gif)
𝐍𝐨𝐭𝐞: You Need Internal storage 5GB space for Setup click here↪️: [𝐜𝐨𝐦.𝐭𝐞𝐫𝐦𝐮𝐱.𝐭𝐚𝐫.𝐠𝐳](https://mega.nz/file/5HVGTLpY#L_zXLvl7LF--XPPVl-sN9lgO3goOPa5v3i5JAv7TUvU)<br/>
download zip Size-: 2GB<br/> moved this file Internal storage: download folder, use chrome browser and copy paste in termux.👇
```
termux-setup-storage
```
<p align=center> 
《if need then install optional》<br/>
pkg install tar -y</a>
</p>

```
cp -rf /sdcard/download/com.termux.tar.gz /data/data/com.termux/files;cd ..;tar -xvzf com.termux.tar.gz;rm -rf com.termux.tar.gz;cd $HOME
```
# Termux phantom process kill disabled☟
![Screenshot](https://github.com/MrGhostOfficial/Admin.Network/blob/master/Signal_9_issue.jpg)
After Restore termux you need Install ↪️[Termux:Float.apk](https://f-droid.org/en/packages/com.termux.window/) to fix this termux phantom process kill, trun on wifi if you don't have wifi then you can use your friend mobile Hotspot connection after connected, go to your phone settings. Developer options/USB debugging/Wireless debugging/trun on.
![Screenshot](https://github.com/MrGhostOfficial/Admin.Network/blob/master/Pair_device.jpg)
(Click/Pair device with pairing code/look like this and paste in termux)<br/>
```
adb pair 172.19.0.1:36167
```
Enter pairing code: 406979

(Wireless debugging/IP address & Port/look like this and paste in termux)<br/>if you want stop connected then type<br/>[ adb disconnect 172.19.0.1:38943 ]<br/>
```
adb connect 172.19.0.1:38943
```

(See List of devices attached)
```
adb devices -l
```
Paste this command to Fix (signal 9) error closed problem👇.
```
adb shell "/system/bin/device_config set_sync_disabled_for_tests persistent";adb shell "/system/bin/device_config put activity_manager max_phantom_processes 2147483647";adb shell settings put global settings_enable_monitor_phantom_procs false;adb shell "/system/bin/dumpsys activity settings | grep max_phantom_processes";adb shell "/system/bin/device_config get activity_manager max_phantom_processes"
```
<img src=![Screenshot](https://github.com/MrGhostOfficial/Admin.Network/blob/master/Metasploit.jpg)

<img src=![Screenshot](https://github.com/MrGhostOfficial/Admin.Network/blob/master/Xfce4-desktop.jpg)

[[INFO](https://t.me/NetCyberCoder)] if you are facing any issues then Contact me telegram. And don't forget to Follow GitHub, Hope you Like it Enjoy.👾

# [License & copyright]
![IMG-Copyright-2023](https://github.com/MrGhostOfficial/Admin.Network/blob/master/License_copyright.jpg)
© [MrGhostOfficial](https://github.com/MrGhostOfficial), Algonquin College Graphic Design, Don't Copy My Script Or i Give You  Copyright Claim
Licensed under the [[MIT License](https://github.com/MrGhostOfficial/TermuxElevated/blob/master/LICENSE)] (LICENSE).
