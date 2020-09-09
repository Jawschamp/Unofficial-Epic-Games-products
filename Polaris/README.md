#  Polaris Setup guide

I've had people ask me if this is a virus as I said in https://github.com/Jawschamp/FortnitePrivateServersGuide/blob/master/Lawin/FortTimeMachine/LawinFortTimeMachine.md run this through virustotal.com

Credit https://discord.com/invite/gp56gvd

Note: joining that Discord server does not mean they will you help you set this up read below

**Since the Polaris Team can't tell you how to setup this up for risk of "distributing" violation of Epic's Fortnite Licence Agreement I will show you how to do it!** 

So most of this will be the same as [Lawin Setup](https://github.com/Jawschamp/FortnitePrivateServersGuide/tree/master/Lawin) look at that too
But I will just go through this again for the **Nubs**

# Download:
* **GameVersion** [Fortnite Season 1 (Client 1.8): https://drive.google.com/drive/folders/1e_yc76fATTxwNb69iixPIBpNrsmG7A4K] for more help look at [Fortnite_Installer.md](https://github.com/Jawschamp/FortnitePrivateServersGuide/blob/master/Lawin/Fortnite_Installer.md)
* **Launcher** [Season 1, 2, 3, 4, 5: https://drive.google.com/open?id=1jjRBNCHozE0ABBErKPOFEGYoazdpEnzQ] for more help look at [Launchers.md](https://github.com/Jawschamp/FortnitePrivateServersGuide/blob/master/Lawin/Launchers.md)
* **LawinServer.exe** [https://github.com/PsychoPast/LawinServer/releases] Download the most recent version (The Very Top One)
* **Dotnet-Runtime-3.1.5** [https://cdn.discordapp.com/attachments/679772336177545300/729408321769046026/dotnet-runtime-3.1.5-win-x64.exe]
* **any DLL injector is fine but this works too IGCSInjectorUI_v103.zip** [https://github.com/FransBouma/InjectableGenericCameraSystem/releases/download/IGCSInjectorUI_103/IGCSInjectorUI_v103.zip]
* **7Zip, WinRar** any of those are fine to extract ``IGCSInjectorUI_v103.zip``
* **Polaris** [Download DLL](https://github.com/Jawschamp/FortnitePrivateServersGuide/raw/master/Polaris/Polaris.zip/Polaris.dll)

# Extract
* Extract the content inside **Polaris [Download DLL]** into a folder and name it [**Polaris**]
* Extract the content inside **IGCSInjectorUI_v103.zip** into a folder and name it [**U Setup**]

# Install
* Install ``GameVersion`` (**If you need help with installing ``GameVersion`` for more help look at [Fortnite_Installer.md](https://github.com/Jawschamp/FortnitePrivateServersGuide/blob/master/Lawin/Fortnite_Installer.md)**)
* Install ``Dotnet-Runtime-3.1.5``

# Next
Drag ``Launcher.bat`` into ``\Fortnite\FortniteGame\Binaries\Win64``

# Launch
* Open ``LawinServer.exe`` If it says Proxy lisening on port 9999 then your good so far
* Open ``Launcher.bat`` and Fortnite should start up
* Open DLL Injector **Recommended** ``IGCSInjectorUI.exe``

# Login
* Put anything you want Email: ``sadsafdsejfgkdshjg@gmail.com``, Password: ``sdafkjsdfglsdjg`` just press login

# Inject DLL
* Open the folder I said to name to [**U Setup**] open ``IGCSInjectorUI.exe`` Where it says "Process to inject to": click ``Select`` and choose ``FortniteClient-Win64-Shipping.exe`` once you've selected that press ``select`` again to confirm then where it says "DLL to inject": click ``Browse`` select ``Polaris.dll`` and click ``Inject DLL`` once you see the image below in game press play

![See it?](https://cdn.discordapp.com/attachments/339138731501944842/753335147725586553/unknown.png)

If that's all correct press play and you'll be in!
