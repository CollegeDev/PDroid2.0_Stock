<p align="center">
  <img src="http://www.privilege-car.de/xda/PDroid-banner.png" alt="PDroid2.0"/>
</p>
## PDroid2.0 Stock Support
### What is PDroid2.0?
PDroid2.0 is a Manager Application for the well known **PDroid2.0 Framework (recommended)** or the new OpenPDroid. The OpenPDroid Framework is a fork of 'my' Framework and only ported to Android 4.2.1 with some little changings. In future there will be only the OpenPdroid framework, because we're working all together on it. PDroid2.0 allows blocking access for any installed application to the following data separately:

* Device ID (IMEI/MEID/ESN)
* Subscriber ID (IMSI)
* SIM serial (ICCID)
* Phone and mailbox number
* Incoming call number
* Outgoing call number
* GPS location
* Network location
* List of accounts (including your google e-mail address)
* Account auth tokens
* Contacts
* Call logs
* Calendar
* SMS
* MMS
* Browser bookmarks and history
* System logs
* SIM info (operator, country)
* Network info (operator, country)
* IP Tables(until now only for Java process)
* Android ID
* Call Phone
* Send SMS
* Send MMS
* Record Audio
* Access Camera
* Force online state (fake online state to permanent online)
* Wifi Info
* ICC Access (integrated circuit-card access, for reading/writing sms on ICC)
* Switch network state (e.g. mobile network)
* Switch Wifi State
* Start on Boot (prevents that application gets the INTENT_BOOT_COMPLETE Broadcast)

### How to install/deinstall?
For install PDroid2.0 on your Stock ROM you have to follow these steps:

1. Download the right patch (install.zip, deinstall.zip) for your device. Look at *'Which branch should I use?'* if you don't know which files you have to download.
2. Copy the *install.zip* and *deinstall.zip* to your internal sdCard
3. Boot in recovery menu and flash the *install.zip* (or use mobile odin to flash the *install.zip*), then reboot
4. Have fun!

If something went wrong during the installation process or you want to deinstall PDroid2.0 you have to follow these steps:

1. Boot in recovery menu and flash the *deinstall.zip* (or use mobile odin to flash the *deinstall.zip*), then reboot
2. Deinstall PDroid2.0 **and** PDroidAgent with e.g. TitaniumBackup
3. Ready

### Can I update via OTA? Will the patches remain?
Good question! You **CAN'T** update via OTA or any other way you're using to upgrade your Stock ROM. If you update your ROM, PDroid2.0 will be deinstalled! You have to wait until I update the patches for the right branch. Then you can update via OTA or Odin and flash the patches again.

### Requirements
* Rooted Phone
* Deodexed Stock Rom
* Custom Recovery (e.g. TWRP, ClockWorkMod, ..) **or** Mobile Odin *(not tested)*

### Which branch should I use?
Please choose the branch for your device. All branches are following this pattern:

`Device_monthReleaseDate_YearReleaseDate`

One quick example. You own the device *N7100* and you're currently running the OTA release from *February 2013* then you have to choose the branch: **N7100_FEB_13**

### Which ROMs will be supported in future?
Yeah, good question at all! I can only support ROMs for devices which I own. I'm currently own following devices:

* N7100
* GT9100

Please don't ask for other Stock ROMs, because it needs a lot of testing until it works on the device. If you want to see PDroid2.0 on your phone, you can buy me one :-D (Joke).


### Why should I use this application?
* It is developed by the main core developer CollegeDev who knows a lot about the features PDroid2.0 supports especially the new ones, because he wrotes them
* Only ~300Kb filesize of the application (very small)
* Really small battery consumption -> it is not listed in the battery statistics
* In future it will provide **FULL 256bit AES encryption technology** -> nobody except you can access your private data
* You will get support for application AND framework if something went wrong
* NO background service needed
* NO permission required for the app to run and that will NEVER change
* No performance impacts
* **FULL STOCK ROM SUPPORT**

### Bug Report
If you've found any Bug in PDroid2.0 you can open a new Issue here on GitHub. Please describe the bug as precise as you can, this will help me a lot. If you're a German native speaker, you can provide a Bug Report in German too. It is recommended to attach a Logcat too (best would be one with verbose filter and one with error filter).

### Is there any manual for this Application?
Yes it is. I will upload it in the next few days.

### Disclaimer
    /*
     * Your warranty is now void.
     *
     * I am not responsible for bricked devices, dead SD cards,
     * thermonuclear war, or you getting fired because the alarm app failed. 
     * Please do some research if you have any concerns about features 
     * included in this Patch and/or Application before flashing or installing it! YOU are 
     * choosing to make these modifications by installing the Application or flashing the Patch, and if you point the finger 
     * at me for messing up your device, I will laugh at you.
     *
     */ 