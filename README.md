# Advanced Burglary 3.3 Release

<img width="3440" height="1440" alt="SK-BURGLARY (1)" src="https://github.com/user-attachments/assets/b8ab8cd6-f5ba-47f1-8422-c34be1bf1ee1" />

Welcome to the **Advanced Burglary 3.3** repository! This is the ultimate burglary/houserobbery script for FiveM, packed with exciting features and improvements.

## Major Update 3.3.6 Released - 12/07/2025
A wide range of QoL improvements, new features, fixes, and enhanced support for QBox have been added.

Some new changes:

- The heist axe item used to disable the T4 lockdown is now physically attached to the boss guard’s back. It must be looted by any group member after he’s killed.
- The Tier 4 setup ped is now a traitor guard wearing guard clothing. You’ll need to bribe him to get the T4 info/security item, if you refuse, there’s a good chance he’ll attack. You can still loot the required items from his body if he’s killed.
- All guards can now be looted by any group member.
- Guard peds now use randomised ped parents, hairstyles, face paint, and other variation attributes - so they no longer look like clones. All selections are made to avoid clipping issues with masks and accessories.
- Added persistent, tier-based job cooldowns (until server restart).
- Improved door enter/exit logic overall - prevents ox_target duplicate zones and warning spam.
- Ensure an animation is passed to ox_lib progress bars to prevent moving while interacting (searching, looting, etc.).
- Job request mails now include unique IDs and expiry timers (Config.MailExpiryTime) - prevents accepting expired jobs.
- Improved group cleanup logic when the leader/member disconnects, exits, or crashes.
- Interior peds now check for ownership transfer and retarget other players correctly.
- Fixed guard targeting, attributes, and relationship group resets on owner change.
- Switched to AddTargetEntity for networked peds - fixed qb-target errors and not being able to click the target when looting dead peds.
- New indoor burglar alarm using xsound for Tiers 2 & 3 (Config.OptionalSound) - fallback to the classic beep if disabled.
- Updated exterior alarm sound URL to a permanent xsound link.
  
There’s much more in this update - check out the full patch notes [GitHub.io](https://mknzz.github.io/burglary-docs/patchnotes.html#update-336---latest)!

## Explore the Brand New Version 3.3

### Ultimate Burglary/House Robbery Script for FiveM 🪛

**Update 3.3** marks the start of our journey to an all-in-one robbery resource. Take on **T4**, the challenge of a high-stakes, action-packed mission to rob a heavily guarded weapons cache. Navigate through layers of security: evade patrol guards, disable CCTV, crack the security keypad, and avoid triggering a lockdown that could spawn a formidable boss guard.

[🎥 Watch the 3.3 Release Video 🎥](https://youtu.be/h6XWSU4wIA8?si=cLtg9fOH3Bxguela)

### What's New in 3.3?

- **🔒 Lockdown Mechanic**: Triggered by CCTV, a boss guard may spawn. Disable it with the ‘heistaxe’ item and smash the correct power box.
- **🏠 Interior Overhaul**: Over 240 new objects and 35+ items, courtesy of Evelynn. All interiors are packed with detail!
- **📋 New Free Menu**: Introducing sk-menu, recommended for smooth auto-refreshing items in the sell menu, but optional [sk-menu](https://github.com/mknzz/sk-menu).
- **📈 Reworked Reputation System**: Easier configuration, rep rewarding, and new XP calculation.
- **🔐 Improved Safe Opening**: No more instantly spawning open safes. A proper opening safe scene will now play.
- **💰 New Sell Mechanic**: Items are randomly selected at resource start, with prices changing based on demand and rarity.
- **🛡️ Outdoor Security**: Guards, keypads, alarms, power box, and CCTV for Tier 4.
- **⚡ Enhanced Interactions**: Smoother animations for keypads, safes, and power boxes.
- **⚙️ Improved Setup and Loading**: Refactored SetupInterior for smoother loading and reduced blackscreen time.

There’s much more in this update! Check out the ⁠[#latest-version](https://discord.com/channels/902289486128496652/963917396287037471) channel in the Discord for detailed patch notes.

### Key Features

- **🎯 Tier System**: Expandable tiers with level scaling.
- **🔒 Expanded Interiors**: Explore an array of interiors with locked doors requiring appropriate tools for access.
- **🕶️ Stealth Mechanics**: Players must maintain stealth and reduce noise to prevent triggering alarms. Master the art of staying covert for a successful heist.
- **🤝 Group Play**: Experience the thrill of strategizing and executing a house robbery as a cohesive group! Manage groups in the Boss menu.
- **📋 Complete Daily Tasks**: Tackle random tasks from Config.TasksList during house robberies. Manage tasks in the Boss menu. Earn reputation points.

### Documentation

Find all the information you need to install and configure both the escrow and open-source versions of sk-burglary effectively.

- [GitHub.io Documentation](https://mknzz.github.io/burglary-docs/)

## QBox Supported
**QBox** has been tested and is working, tested server version [QBox txAdminRecipe](https://github.com/Qbox-project/txAdminRecipe/blob/main/qbox.yaml).

Make sure ox_lib, ox_target, and ox_inventory `enabled = true` in the main `config.lua.`

In your QBox server config: setr qbx:enableBridge "true" # When true, enables the qb-core bridge for qbx_core. This should be true by default.

---

This resource is unencrypted. 100% of the source code is available. 🔓
