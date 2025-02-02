# LEGACY SPT RELEASES (3.9.8)
Legacy releases for people who wish to player older versions of SPT. This is not officially supported or endorsed by the SPT team. This does *NOT* bypass anti-piracy measures. This is simply a way for you to install legacy versions of SPT, current version target is `3.9.8`. I will not provide ways to install any other version of SPT or provide ways to bypass piracy measures. 

This provides a means of installation of `SPT 3.9.8` through means that doesn't include piracy, I simply used the SPT build process to build a release for SPT 3.9.8 and created the patcher to get you from `0.15.1.33420` to `0.14.9.30626`. The intermediate patch used will be what SPT uses when there are client updates, this minimizes maintenance for me while allowing this to exist. 

I am under no obligation to have done this and this took considerable time to setup, so if you would like to [buy me a coffee](https://ko-fi.com/dirtbikercj) for my time, it would be appreciated.

I've also created a [discord](https://discord.gg/XXeSBuKnHP) you can join for discussions around old versions of SPT. Please keep any and all discussions here rather than the official SPT discord out of respect of the wishes of SPT staff/developers who made this project possible in the first place. 

# Why trust this?

This is a safe means of installation, I am a well known [mod developer](https://hub.sp-tarkov.com/files/user-file-list/37201-dirtbikercj/) in the SPT community. I also develop the SPT assembly tool, and am listed as an offical SPT developer. Always do your due dilligence in researching what/who you download from on the internet. 

# Code of Conduct
- You are *NOT* to ask for support in the SPT discord while running this version of SPT.
  - Doing so can result in you losing your ability to particape in support channels.
- You are *NOT* to bother mod authors with issues with now outdated versions of their mods.
  - Even if it has not been updated to the current version of SPT.
- You are expected to be fully self sufficient and able to handle install directions provided below with no additional help provided. There will be none so don't ask.
- You are expected to find the versions of the mod for the version we are downgrading to here (3.9.8) as of 02/02/2025
- You are on your own when sourcing mods. Some mods are developed purely for new versions and thus only exist for newer versions.
  - Do not bother mod authors about backporting mods in these cases.

# Prerequisites
- Make sure you own a copy of Escape From Tarkov (Edition does not matter)
  - Piracy will *NOT* be tolerated. If found that people are using this for malicious purposes I will no longer provide this service. 
- Make sure your live EFT is fully up to date and the play button is visible.
- Make sure you have played atleast 1 live or PVE raid and that everything works as expected.

# Installation

These installation directions will assume the install path is `C:\SPT\3.9.8` use whatever path you want.

IMPORTANT: Make sure you are using 7zip for all extractions.

- Copy your live installation to a new folder EX: `C:\SPT\3.9.8`
- Download the SPT patcher from [here](https://slugma.waffle-lord.net/Patcher_16.1.0.34720_to_15.5.1.33420.7z) (Up to date as of 02/02/2025) this will get you from the current live version to the client 3.10.5 uses.
- Extract it to `C:\SPT\3.9.8\`
- Run `patcher.exe` and wait for it to complete
- Once complete, delete the `patcher.exe`
- Now download the legacy patcher from [here](https://pub-31e61bcf69804893b5f957a580307798.r2.dev/uploads/15.1.33420_to_14.9.30626.7z). This will get you from the client 3.10.5 uses to the client 3.9.8 uses.
  - I did not set up a domain for this, it may get rate limited depending on how many people have installed it that day. if the download fails you need to try again the next day, I will provide no work around for this as this is not something I plan on sinking money into.
- Extract it to `C:\SPT\3.9.8\` and run it as you did with the previous one.
- Delete the `patcher.exe` again
- Now download the SPT files from [here](https://github.com/CJ-SPT/LEGACY-SPT-RELEASES/releases/download/3.9.8/SPT-3.9.8-30626-a0c79ac.7z)
- Extract the spt release into `C:\SPT\3.9.8`.
- launch `SPT.Server.exe` and wait for the green `server is running...` text.
- launch `SPT.Launcher.exe` and create your profile and begin playing.