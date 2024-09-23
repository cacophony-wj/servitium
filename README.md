# PLEASE DO NOT CLOSE THIS WINDOW. 

### THIS DOCUMENT MUST BE FOLLOWED FOR SERVITIUM TO WORK PROPERLY.

![Servitium Logo](images/Servitium_Splash_2.png)

# SERVITIUM

## "Sub, Dom, whichever you choose -- you're going to kill it."

## Preamble

**This Modlist contains mods with sexual content and you need to be of legal age in your country (most western countries: 18+, some eastern ones: 21+)**.

_SERVITIUM_ is a variant of _Licentia_, one of _Wabbajack's_ oldest and most well-regarded adult modlists. It emphasizes an accessible Power Fantasy design philosophy but spices things up a bit with the _SexLab_ Adult Framework and a host of intrusive fetish content. The list accomodates either female submissive gameplay or male, female, or futanari dominant gameplay via an easy-to-use Dropdown Menu.

**Prefer your sex abusive and intrusive?** Play this modlist -- _Servitium._

**Prefer your sex loving and optional?** Play its sister modlist -- _Licentia._

#### More Information

If you want to examine a complete list of the mods in this modlist, [go here.](https://loadorderlibrary.com/lists/servitium-1) 

### System Specifications

The recommended setup for an enjoyable experience **at 1080p** is at least

- intel i7 or AMD Ryzen 5600 or later
- NVIDIA RTX 2070 SUPER or AMD Radeon 5700 XT or later

### Requirements

- [Nexus Account](https://nexusmods.com/)
- [LoversLab Account](https://www.loverslab.com/)

These accounts are mandatory, they must be created before continuing. _Nexus Premium_ is strongly recommended or the installation will take many more hours (possibly days).

## Pre-Installation

Before you do anything with _Wabbajack,_ ensure that _Skyrim_ is installed in a non-protected folder (such as the root of your drive, like `D:\`). It **cannot** be located in _Program Files_ or the list will not function. Relocate the game as necessary.

The _Lover's Lab API_ (automatic download interface) is no longer available due to technical considerations, so it is recommended that all mods from there be downloaded from a normal web browser _before launching Wabbajack._ In addition, several files from other third-party hosts such as _MEGA_ and _Google Drive_ often have difficulty, so those must be downloaded as well. To do so, take the following steps.

Create a directory for your chosen modlist. Something in the root folder of a fast Solid State Drive, or -- ideally -- an M.2 NVME. (Something like `D:\Servitium`). You need at least **600GB** free for this modlist and a few GBs in the _Wabbajack_ and _OS_ drives for caches. About half of these GBs are mod downloads; the downloads folder can be deleted or relocated after installation.

Within that directory, create another directory called `downloads` -- in all lowercase. (`D:\Servitium\downloads`)

Refer to [this document](DOWNLOADS.md) for links to all the External Mods you need to download. Place all the files in the `downloads` directory you created above. **DO NOT EXTRACT THEM,** they need to be _exactly_ as downloaded from the website.

## Installation

For _Wabbajack_ to match its files,_Skyrim_ needs to be set to the English language. Other languages will not work.

_Servitium_ requires the additional _Creation Club Content_ from the _Skyrim Anniversary Edition Upgrade_ or the modlist will not install. The price is about $20. 

Ensure you have set antivirus exceptions for this folder, the _Skyrim_ vanilla game folder, and the _Wabbajack_ folder, or the installation will fail. Certain antivirus packages do not properly respect exceptions and cannot be fully disabled (_Webroot_ and _Bitdefender_ are examples of these). These tools must be uninstalled from your system.

Ensure that _OneDrive_ is **uninstalled** or **completely disabled.** This program locks some of _Skyrim_'s configuration files when in use and will cause the modlist to experience errors.

The _Microsoft Visual C++_ redistributable package is required for _Mod Organizer 2_ (as well as certain mods included with _SERVITIUM_) and you can download it from _Microsoft._ Download the x64 version of "Visual Studio 2015, 2017, 2019 and 2022" [here](https://aka.ms/vs/17/release/vc_redist.x64.exe).

You must set your Advanced Memory Pagefile to at least 40GB or the modlist will constantly crash. On _Windows 11_ you can find this setting in the About page for your PC. [Here](https://www.windowscentral.com/software-apps/windows-11/how-to-manage-virtual-memory-on-windows-11) is a document to find the specific option; other versions of Windows are similar. Setting the minimum and maximum pagefile size to `40,960` on one Solid State Drive is recommended. 

**UPDATE** Currently you no longer need to manually download the _Kaidan_ file. Unsure yet if this situation will change.

##  Using Wabbajack

Login to _Nexus_ with the _Wabbajack_ app. This login can be found by clicking the **GEAR** icon in the top right. It will toggle over to "logged in" when successful.

Depending on your system specs, the download and installation process can take a long time. 

##  Problems with Wabbajack

There are many different scenarios where _Wabbajack_ will produce an error. Re-run _Wabbajack_ before seeking assistance. _Wabbajack_ will only download and reinstall the minimum necessary to get the modlist working. 

**Various files beginning with "cc" and ending with "esl" or "esm" failed to download.**

You did not purchase the $20 upgrade to Skyrim, and this is not negotiable. Purchase it, verify it, delete it and re-download it if necessary, and try again.

**Could not download x:**

Some Internet providers have difficulty accessing the servers hosting the list's files. Use a VPN (Virtual Private Network) with a terminus set to the United States. Free options include _ProtonVPN_ and _Cloudflare WARP._ If a download gets interrupted, delete all corrupt local copies before trying again.

**Wabbajack could not find my game folder:**

_Servitium_ will not work with a GOG or pirated game version. If you own the game on _Steam,_ return to the Installation step. If this still doesn't work, ensure you are not running Wabbajack as an Administrator. **Asking for help with pirated copies of the game will get you banned from Discord Support.**

**MEGA download cap exceeded.**

This shouldn't happen unless you download the list multiple times or download multiple _Wabbajack_ lists. Sign up for an account or wait for the timeout to expire.

## Post-Installation

### Verifying the Modlist

_Licentia_ is over 500GB in size. Given the likelihood of corrupted files during installation, it is strongly recommended that files be checked after installation.

To verify the modlist, click the Gear icon in the upper right. Click the button along the middle left that reads "Launch Wabbajack CLI." Type the following commands:

`cd cli`

`wabbajack-cli verify-modlist-install -m "path to the Licentia.wabbajack file" -i "Licentia install folder path"`

You must replace the portions in quotations with the specific file locations on your system. The Command Line Interface will hash and verify every file in the list against a known signature.

I recognize that many people are unfamiliar with file paths and how to type in command-line commands. Most modern devices never require such knowledge. [Here](https://www.digitalcitizen.life/command-prompt-how-use-basic-commands/) is a comprehensive guide on how to use the command line. I realize this solution is not ideal, but until a Verify button is added to _Wabbajack_, this step will remain necessary for larger modlists. Note the location of your `Licentia.wabbajack` file and your `X:\Licentia` directory and do your best.

You must reinstall the list until every file returns as a 100% match. This may be much more difficult if your Internet connection is poor, or the _Wabbajack_ app is frequently interrupted. Do note that if you launch _Mod Organizer 2_, you just changed some files, so they will not verify. Do not touch anything before verifying.

## Post-Installation

### Tweaking the Modlist

If you wish to change your game's resolution, select the "INI Editor" from the _Tools_ menu along the icon bar of MO2 and change it via the `SkyrimPrefs.ini` file. Scroll down until you see the `[Display]` header and look for the `iSize` values. Note that the TYPICAL ORDER IS REVERSED, the HEIGHT is listed BEFORE the WIDTH.

If you are confident you meet the System Requirements but still experience severe performance drops, you may need to customize your `BIOS` settings to maximize your hardware. Refer to your motherboard's documentation. The most common failure point is too-low RAM speed, which can often be addressed by enabling the "XMP" or "DOCP" profiles.

### Launching the Modlist

Launch ModOrganizer.exe from the directory where you installed the list. 

If you direct your attention to the Dropdown Menu at the top of the left pane, you will find two Profiles to choose from: regular **SERVITIUM** and **SERVITIUM Male.** **SERVITIUM** is intended **ONLY** for female submissive characters and features a lot of intrusive exploitation. **SERVITIUM Male** is more about dominant content but can accomodate any gender and features far less intrusive gameplay. Choose wisely before you begin, because you **cannot switch in the middle of a game.**

Then, launch the game from the **SKSE** entry in the drop-down menu.

### MCM CONFIGURATION

### WHEN YOU SPAWN IN HELGEN'S INN, DO NOT TOUCH ANYTHING!

Wait for all of the messages in the upper left corner of the screen to appear and disappear. A warning will be issued that this readme is mandatory for proper installation. Click through and continue to wait.

**NEW!!** The first handful of levels in this modlist can be rough. I have included a small note in your starting inventory that grants you a little boost at the start of your adventure. If you wish to boost yourself to level 5, read the note that says, "Read Me for 1,000 Starting XP!" Once you have received the "Level Up" notification, open the stats menu and choose your skills and perks. You must choose your skills for each level followed by a primary stat (such as Health, Magicka, or Stamina). **CHOOSING THE PRIMARY STAT COMPLETES THE LEVEL UP.** Pick the skills FIRST. Then close the level up menu, wait for all the skill notifications to complete, and open it again to choose your Perks. As a little bonus, you can sell the note to a general goods vendor (like Lucan or Belethor) to clean them out of gold and grant yourself a little nest egg for buying gear.

When all of the messages have disappeared, open the Main Menu with the ESC key and find the entry labeled "SexLab." (They are in alphabetical order.) Click on it, and along the top right, click the option labeled "Install/Update SexLab." Now close the menu and wait for all messages to appear and disappear. 

Next is a rather controversial option. If you wish to experiment with non-humans, open the menu again and navigate to the "Animation Settings" entry on the left. On the top right, you will see a checkbox labeled "Enable Creature Animation." Select it if you wish non-humanoids, but remember that in Skyrim, "non-humanoids" includes fun races like Vampires, Werewolves, and Trolls. Then close the menus and wait for the message to appear indicating success.

It is very important at this stage to save and reload the game so SexLab will initialize properly and cache scenes and equipment, so please do so. (**NEW** All the saving and loading I had you do before seems to be overkill but you may wish to do so after every step if you get stuck.)

Just a few more steps. Open the MCM and find the _ZAZ_ entry at the bottom. Select the "SexLab" option on the left. Scroll to the top and select "Register." The entry will gray out. Touch nothing until this menu reads "Registered." It takes about 30 seconds. Now find the _SLAL Anim Loader_ entry. Click the "Enable all animations" option. Wait a couple of seconds. Click the "Register all animations" option. The process of registering the animations takes about two minutes. If it completes successfully, you should receive a message that over 900 animations are enabled. I recommend you close the menu and save now in case something goes wrong in the next step because registering animations is very time-consuming and boring.

Final step. Open Main Menu with the ESC key and find the entry labeled "MCM Recorder." Here, you will find an MCM "Recording" labeled simply "RUN ME." Click on it, answer "Yes," and use ESC to back out of all menus. You will receive a popup asking if you wish to play the recording; please do so.

Once again, please wait for all of the messages in the upper left corner of the screen to appear and disappear. **CLICK OK ON ANY DIALOG BOXES. IF YOU RECEIVE ANY ERRORS, CLICK CONTINUE.** At some point the game will configure several poses for you so the player will model them. Just let it go. The whole procedure takes about three minutes. 

That's it! Your modlist is configured. Good luck and may your game-breaking bugs be few in number. 

**NEW!!** _SERVITIUM_ now has an **OPTIONAL FUN ROLEPLAYING FEATURE** that I personally find compelling but may not be to most Players' tastes, so it is disabled by default. This is **ENFORCED NUDITY** via the _Licenses - Player Oppression_ Mod. The way it works is, if you go into a City wearing any clothing or armor, a Guard will stop you, strip you, and seize all clothing and armor on your person. This can be **DANGEROUS** because NPCs tend to get _HANDSY_ if you aren't clothed. You can purchase a License to wear clothing for a week's duration from any Guard for 650 Septims. You can purchase a License to wear armor for a week's duration from any Guard for 2,000 Septims. To enable this feature, you must **INITIALIZE LICENSES** via the MCM for it and **LOAD THE CONFIGURATION. _DO NOT ENABLE THIS FEATURE IF IT DOES NOT INTEREST YOU._**

## FINAL NOTES

When you reach your first exterior world location, you will be prompted to enable _Survival Mode_. This mod disables fast travel and requires eating, drinking, and staying warm to survive. The option can be changed later in the default "Gameplay" settings of _Skyrim_.

Depending on your race, you will also receive a prompt about which Divine and/or Daedra you wish to worship. Choose according to your preference.

## Updating the Modlist

Download the modlist's `.wabbajack` file again and specify the same directories. _Wabbajack_ will only update what has changed, it will not repeat the entire installation. It is rarely recommended to continue a save when you update a modlist.

## Removing the Modlist

You can just remove the _Servitium_ folder. 

## Contact

I am regularly available on [my discord server](https://discord.gg/jolly-coop).

For more information about me, as well as ways to show your appreciation for my work, visit https://cacophony.me

**cacophony's SubscribeStar:** [https://subscribestar.adult/cacophony](https://subscribestar.adult/cacophony)

**cacophony1979's Patreon:** [https://patreon.com/cacophony1979](https://patreon.com/cacophony1979)

**cacophony1979's Ko-Fi:** [https://ko-fi.com/cacophony1979](https://ko-fi.com/cacophony1979)

My _Servitium_ related email is cacophony-wj@outlook.com.
