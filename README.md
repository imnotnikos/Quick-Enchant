<p align="center"><img src="assets/social-preview.png" alt="Quick Enchant banner" width="100%"></p>

# Quick Enchant
Quick Enchant is a lightweight **Paper, Spigot, & Bukkit** plugin for 1.21+ that speeds up the enchanting and disenchanting process. It allows players to right-click an enchanting table to instantly enchant their held item, or right-click a grindstone to instantly wipe an item clean. No lapis is required, and it completely bypasses the vanilla GUIs.

<img src="assets/icon.png" width="250" height="250" alt="Quick Enchant icon" />

***
### Plugin made by imNikos.
 
[![Discord](https://img.shields.io/badge/Discord-Nikos'%20Wasteland-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/9xJgzNqEaJ)
[![Instagram](https://img.shields.io/badge/Instagram-imNikos_-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/imnikos_)
[![YouTube](https://img.shields.io/badge/YouTube-imNikoss-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://youtube.com/@imnikoss)
[![TikTok](https://img.shields.io/badge/TikTok-imNikos_-000000?style=flat-square&logo=tiktok&logoColor=white)](https://tiktok.com/@imnikos_)
[![GitHub](https://img.shields.io/badge/GitHub-imnotnikos-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/imnotnikos)
[![Modrinth](https://img.shields.io/badge/Modrinth-imNikos-1bd96a?style=flat-square&logo=modrinth&logoColor=white)](https://modrinth.com/user/imNikos)
[![CurseForge](https://img.shields.io/badge/CurseForge-imnotnikos-F16436?style=flat-square&logo=curseforge&logoColor=white)](https://www.curseforge.com/members/imnotnikos/projects)

***

## Features
**Instant Enchanting**: Right-click an enchanting table with an enchantable item to instantly consume EXP and apply enchantments.

**Instant Disenchanting**: Right-click a grindstone with an enchanted item to instantly strip all enchantments off of it, skipping the menu entirely.

**Custom Item Pools**: Configure specific enchantments and levels for any item. Set specific enchantment(s) for an item, or make it randomly pick from a list of customized options.

**Table Profiles**: Link physical enchanting tables in your world to specific profiles. You can have a standard table at your spawn and an "Overpowered" table that applies completely different enchantments.

**In-Game Configuration**: Add new enchantment configurations directly from the game using commands. 

**Vanilla Exclusions**: If an item is not in your custom config, it pulls a random level-appropriate enchant from the vanilla pool. You can easily blacklist specific vanilla enchantments like Curse of Vanishing or Mending so they never roll.

## Commands

**Setup & Table Linking**

/qe link [profile] – Link the table you are looking at to a profile (e.g., default or vip).

/qe unlink – Makes the table you are looking at use the standard default settings again.

/qe reload – Refreshes the configuration file.

**Managing Enchantments**

/qe add [enchant] [level] to [item] [profile]

Example: /qe add sharpness 5 to diamond_sword

Grouped Example: /qe add [sharpness,unbreaking] [5,3] to diamond_sword (These will always roll together).

/qe remove [enchant] to [item] [profile] – Removes a specific enchantment from an item's possible pool. 

/qe exclude [enchant] to [item] [profile] – Blacklists a vanilla enchantment so it never appears on that item.

/qe reset [profile] – Clears all enchantments from a specific profile.

**Viewing Info**

/qe list profile [name] – See all enchants set up for a specific profile.

/qe list item [item] – See every profile that has special settings for that item.

_Available aliases:_ /qe, /quickenc

## Permissions
quickenchant.admin : Required to use any of the setup or reload commands. Regular players do not need any permissions to right-click and use the tables or grindstones.

## Requirements
A Minecraft server running **Paper, Spigot, or Bukkit 1.21 or newer**.

Java 21.

# Installation
## For Server Owners
Navigate to the Releases page.

Download the latest QuickEnchant.jar.

Place the file into your server's /plugins/ directory.

Restart your server or use a plugin loader to enable it.
