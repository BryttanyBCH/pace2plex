# pace2plex
pace2plex is a simple and somewhat jank script that can be used to organize various fan edits of anime series for your Plex library. It offers the ability to organize your files into season folders appropriately, apply respective metadata through the Plex API, assign custom season posters, curated episode thumbnails and more.

[Click here to download](https://github.com/TommyB123/pace2plex/archive/refs/heads/main.zip)

# What series are supported?
**One Piece**
* One Pace
* Onigashima Paced (companion edit seamlessly intergrated into One Pace)

**Bleach**
* Concentrated Bleach
* Hollowed Bleach (companion edit seamlessly integrated into Concentrated Bleach)
* Optional support for the Thousand Year Blood War arc is included to create a seamless experience for the entire series.

**Naruto**
* Naruto Resealed

# How to use
* Ensure the Python programming language is available on your system. If you don't have it, you can easily grab it through the [Microsoft Store](https://apps.microsoft.com/detail/9pnrbtzxmb4z)
* Install the Plex API library for Python. Enter `pip install plexapi` into your command prompt/terminal.
* Download the latest release [here](https://github.com/TommyB123/pace2plex/archive/refs/heads/main.zip).
* Extract the zip file to a folder.
    * If you intend to use the script to organize your One Pace episodes, you must place the script files in a directory that contains either the episodes or a child directory with the episodes.
* Select your desired option in the terminal window.
    * The first time the script attempts to use the Plex API, you will be prompted to submit your Plex account information alongside the name of the media server you have One Pace on. Fill out the information to proceed.

# Benefits of this script
* Very easy to update with new releases.
* Hardlinks files when organizing into season folders, avoiding needless file duplication while also keeping original downloads intact.
* Uses the Plex API to directly apply metadata to One Pace episode entries inside of Plex. This means that you can also use alternative One Pace-compatible edits like Muhn Pace if you're a dub watcher. Do note that this script is not written to organize other edits and can only apply metadata to edits that follow One Pace's episode structure. This also means that additional series parser plugins and etc not are needed.
* Offers the ability to add the original air dates of the anime to each edited episode. This is nice for having the context of when the episodes were originally animated and ensures proper playback between seasons.
* Avoids renaming files when possible.

# Data sources
**One Pace**

[Series Posters](https://imgur.com/a/one-pace-arc-wanted-posters-updated-2024-Dc5tTZN)  
[Episode Titles](https://github.com/one-pace/one-pace-public-subtitles/blob/main/main/title.properties)  
[Episode Descriptions](https://docs.google.com/spreadsheets/d/1M0Aa2p5x7NioaH9-u8FyHq6rH3t5s6Sccs8GoC6pHAM/)  
[Onigashima Paced Episode Titles](https://docs.google.com/spreadsheets/d/1HoYogAchoU5DWxVJzUy3eZcHMZk_hUmzUVnQm9KxeFI/)

**Concentrated Bleach**

[Concentrated Bleach Episode Names](https://docs.google.com/spreadsheets/d/1bz-Ye4yAXmX31K_abAV7kNUq3lwOBg6aiOxAHaFDRl8)  
[Concentrated Bleach Episode Descriptions](https://gablog520.wordpress.com/)  
[Concentrated Bleach Episode Thumbnails](https://drive.google.com/file/d/1GBQ3VMIPcpzyfH9bFfAZyFPlhv2XVrpX/view)  
[Hollowed Bleach Episode Names](https://docs.google.com/spreadsheets/d/1-ipC6DpZw4GlmMnUw4fOsIWXCbK0s0St2vbsMPr6WfI/edit?gid=0#gid=0)

**Naruto Resealed**

[Naruto Resealed Episode Titles](https://docs.google.com/spreadsheets/d/1mFsVCL7Jy5ZbZ3CrCZ-I6PAcJlNH06k9VG_vvSuK4H8/edit?gid=0#gid=0)  
Episode descriptions pulled from their Discord server.



