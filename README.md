# mctoolbox-versions
Version codes for the Toolbox for Minecraft application developed by MCMrARM

Table of contents
=================

   * [File Structure](#file-structure)
   * [Using Version Codes](#using-version-codes)
   * [Additional Resources](#additional-resources)

# File Structure
This is a small repository, containing only a few JSON files. However, it still is important to know the contents of these files if you intend to use them.

| Filename | Package Name | Notes |
| - | - | - |
| mcversion.json | com.mojang.minecraftpe | [Minecraft (for Android)](//play.google.com/store/apps/details?id=com.mojang.minecraftpe) version codes supported by the latest Toolbox version |
| tbversion.json | io.mrarm.mctoolbox | Version history for [Toolbox for Minecraft](//play.google.com/store/apps/details?id=io.mrarm.mctoolbox), an app by [MCMrARM](//github.com/MCMrARM) |

# Using Version Codes
Google Play Store works by fetching the latest version code of an application, then using that version code to generate a temporary download link for the app or game you are trying to install. Since this is the case, you are able to send requests to Google Play API directly while using an outdated version code to download older versions, though it is best to use tools which do this at your own risk.

# Additional Resources

   * [Plaintext Version List](//mcv.kee7702.tk/toolbox)
   * [Toolbox for Minecraft Discord Server](//discord.gg/toolbox)
