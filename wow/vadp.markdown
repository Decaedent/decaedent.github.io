---
layout: post
title: Vanilla Addon Documentation Project
date:   2017-01-21 19:14:42 +0100
categories: wow
---


### [A](#a_start)
* [!AutoSave](#autosave)
* [ABHelper Estimated Final Score Redux](#abehfs)
* [ACE](#ace)
* [Ace 2](#ace2)
* [AceAccept](#aceaccept)
* [AceGUI](#acegui)
* [AceLoot](#aceloot)
* [AcePlayerMenu](#apm)
* [Ace Timer](#acetimer)
* [Advanced Weapon Stats](#adws)
* [Advanced Trade Skill Window](#atsw)
* [AF Tooltip](#aft)
* [ag_UnitFrames](#aguf)
* [Aggro Alert](#aggroaler)
* [AH MailCollect](#ahmc)
* [AH Favorites](#ahf)
* [Align](#align)
* [Alkitron Honor Tab](#aht)
* [All In One Inventory](#aioi)
* [Answering Machine](#am)
* [Archaelogist](#arch)
* [Arc HUD 2](#archud2)
* [AsmoMOD](#asmomod)
* [Atlas](#atlas)
* [Atlas Loot](#atlasloot)
* [Atlas Quest](#atlasqiest)
* [Auctioneer](#auctioneer)
* [Auction Filter Plus](#afp)
* [AutoBar](#autobar)
* [AutoBuff](#autobuff)
* [AutoDecline](#autodecline)
* [AutoDing](#autoding)
* [Autograts](#autograts)
* [AutoInvite](#autoinvite)
* [AutoProfit](#autoprofit)
* [AutoRepair](#autorepair)
* [AutoShoutOut](#autoshoutout)
* [Available Only](#availableonly)

###[B](#b_start)

##<a name="a_start"></a>A

###<a name="autosave"></a>!AutoSave
![!AutoSave tooltip](./img/autosavett.png)

![!AutoSave ui](./img/autosave1.png)

Commands:

`/autosave`
`/as`

Summary:
Helps to save progress, by periodically sending ".save" command. This would only work on servers that allow to manually save.

[Download](./addons/!Autosave.rar)

###<a name="abehfs"></a>ABHelper Estimated Final Score Redux 
![ABHEFS tooltip](./img/abhefstt.png)

![ABHEFS usage](./img/abhefs1.png)

Commands:

`/abehfs`

Summary:
Helps to estimate points needed to win Arathi Basin
Hello, this is a snippet.

[Download](./addons/ABHEFS.rar)

[comment]: # (TODO: In game image)

### <a name="ace"></a> ACE
![ACE tooltip](./img/acett.png)

![](./img/ace1.png)

Commands:

`/ace`

Summary:

A third-party library, that is used to make addon development easier. Other addons might have a dependency on ACE

[Download](./addons/{2}.rar)

### <a name="ace2"></a> Ace 2
![Ace 2 tooltip](./img/ace2tt.png)

Summary:

An updated version of Ace 2. This cannot be used as a replacement for addons that depend on Ace 1.

[Download](./addons/ace2.rar)

### <a name="aceaccept"></a> AceAccept
![AceAccept tooltip](./img/aceaccepttt.png)

Summary:
Automatically accepts summons and ressurections

[Download](./addons/aceaccept.rar)

### <a name="acegui"></a> AceGUI
![AceGUI tooltip](./img/aceguitt.png)

Summary:
AceGUI is a toolkit for creating and working with GUI components.

[Download](./addons/acegui.rar)

### <a name="aceloot"></a> AceLoot
![AceLoot tooltip](./img/aceloottt.png)

![](./img/aceloot1.png)

Summary:
Automatically position the loot window under the mouse cursor.

[Download](./addons/aceloot.rar)


[comment]: # (TODO: autoloot similar addons)

### <a name="apm"></a> AcePlayerMenu
![AcePlayerMenu tooltip](./img/aceplayermenutt.png)

![](./img/aceplayermenu1.png)

Commands:

`/aceplayermenu`

`/apm`

Summary:
<span style="color: F00">Broken</span>
Should add options such as "Ignore", "Invite to guild", "Add to friends", when right clicking on a player's frame. Doesn't seem to work.

The developer said that this has been discontinued, because SetItemRes got broken due to Blizzard's update

[Download](./addons/aceplayermenu.rar)

### <a name="acetimer"></a> Ace Timer
![Ace Timer tooltip](./img/acetimertt.png)

![](./img/acetimer1.png)

![](./img/acetimer2.png)
Commands:

`/acetimer`

`/at`
`/run AceTimerAnchor:Show()`

Summary:

Depends on Ace, and Timex.
Shows buff duration and cooldown timers. Allows to cast the relevant skill, when clicking on its icon in the timer.


[comment]: # (TODO: change picture that has more cooldowns, debuffs and buffs)


[Download](./addons/acetimer.rar)

### <a name="adws"></a> Advanced Weapon Stats
![Advanced Weapon Stats tooltip](./img/adwstt.png)

![](./img/adws1.png)
![](./img/adws2.png)


Commands:

`/adws`

Summary:
This addon calculates weapon damage (white damage, instant skills, on next melee skills using different formulas) adjusted by character's stats, armor class reduction (few presets), custom attack power buffs, and damage buffs. It can help you determine certain weapon's worthness before you equip it (so you can check weapon damage before you spend your dkp). Advanced Weapon Stats is mainly for 60 lvl warriors, rogues and (partially) shamans (more in 1.12 patch). It displays Mortal Strike, Bloodthirst, Overpower, Whirlwind, Heroic Strike stats (if character is a warrior) and Sinister Strike, Riposte, Ghostly Strike, Eviscerate, Hemorrhage stats (for rogues) and Ambush, Backstab (if character is rogue and weapon is dagger), Rockbiter, Windfury Weapon stats (for Shamans).

Advanced Weapon Stats also shows some additional info like:
- weapon flurry speed (warrior)
- weapon blade flurry + slice & dice speed (rogue)
- amount of attack power needed for +10 dmg
- +damage bonus received from 10 ap 
- average seconds needed for sword spec to proc (warrior)

[Download](./addons/adws.rar)

### <a name="atsw"></a> Advanced Trade Skill Window
![Advanced Trade Skill Window tooltip](./img/atswtt.png)

Commands:

`/atsw [disable/enable]` while tradeskill window is open, to disable ATSW for that tradeskill

Summary:
An improved tradeskill window. Can count the resource cost for recipes, queue production, automatically buy reagents from NPC. For more information check the readme.txt in the addon folder 

[comment]: # (TODO: Add a tradeskill example)

[Download](./addons/advancedtradeskillwindow.rar)

### <a name="aft"></a> AF Tooltip
![AF Tooltip tooltip](./img/af_tooltiptt.png)

![](./img/af_tooltip1.png)
![](./img/af_tooltip2.png)


Commands:

`/aftt`

Summary:
Allows to move the Blizzard default tooltip to other locations, allows to show more information inside the tooltip, such as Guild or PvP rank.

[Download](./addons/af_tooltip.rar)

### <a name="aguf"></a> ag_UnitFrames
![ag_UnitFrames tooltip](./img/ag_unitframestt.png)

![](./img/ag_unitframes1.png)
![](./img/ag_unitframes2.png)


![](./img/ag_unitframes3.png)
![](./img/ag_unitframes4.png)



Commands:

`/aguf`

Summary:
A unit frame addon. Changes the default Blizzard frames (Player, Target, Pet, party, raid, etc). Has many different styles and layouts.


[comment]: # (TODO: Video)

[Download](./addons/ag_unitframes.rar)

### <a name="aggroaler"></a> Aggro Alert
![Aggro Alert tooltip](./img/aggroalerttt.png)

![](./img/agroalert1.png)

![](./img/agroalert2.png)


Commands:

`/agg`


Summary:
Creates a movable frame that will display the target's target (if any), and allow for visible warning on player gaining aggro. To move the AggroAlert bubble, use Shift+Left Button and drag it to a new position. Clicking on the AggroAlert bubble will target the unit named in the bubble

[Download](./addons/agroalert.rar)

### <a name="ahmc"></a> AH MailCollect
![AH MailCollect tooltip](./img/ahmctt.png)55555

Summary:

When you open your mailbox AH_MailCollect will scan through and automatically retreive any mail that has cash from a successful auction, from being outbid, or from an auction you bid on that was cancelled. You can also choose to see each amount as it's looted, or only a summary at the end.

You can also automatically retrieve all items in emails from winning or expired auctions. If you don't want to do this automatically you can turn that option off, and instead you can right-click on an email and it will automatically take that item to your inventory, and delete the message. It will only delete auction messages, if someone sends you an item in the mail it will take the item, but leave the message. I don't like the idea of automatically deleting messages that may have other text in them.


[comment]: # (TODO: get picture examples when next to mailbox)

[Download](./addons/AH_MailCollect.rar)

### <a name="ahf"></a> AH Favorites
![AH Favorites tooltip](./img/ahfavoritestt.png)


Summary:
Auction House Favorites can save your current search criteria in a favorites list, and it will automatically repopulate all the fields when selected. 

Auction House Favorites adds a pulldown menu called "Favorites" to the Name field in the Browse tab at the auction house.


[comment]: # (TODO: get picture in AH)

[Download](./addons/ahfavorites.rar)

### <a name="align"></a> Align
![Align tooltip](./img/aligntt.png)

![](./img/align1.png)

Commands:

`/align`

Summary:
Draws a grid on the screen. This helps to align UI elements.

[Download](./addons/align.rar)

### <a name="aht"></a> Alkitron Honor Tab
![Alkitron Honor Tab tooltip](./img/ahttt.png)

![](./img/aht1.png)

Summary:
An improved honor tab. Shows more informations, such as kills today, yesterday, this week, last week, last time.

[Download](./addons/alkitron_honortab.rar)

### <a name="aioi"></a> All In One Inventory
![All In One Inventory tooltip](./img/allinoneinventorytt.png)

![](./img/allinoneinventory1.png)

![](./img/allinoneinventory2.png)


Commands:

`/allinoneinventory`

`/aioi`

Summary:
Combines all bags into a single window


[Download](./addons/allinoneinventory.rar)

### <a name="am"></a> Answering Machine
![Answering Machine tooltip](./img/answeringmachinett.png)

![](./img/answeringmachine1.png)

Commands:

`/answer`

Summary:
Stores messages for you while you are AFK. Also, can auto reply to messages.

[Download](./addons/answeringmachine.rar)

### <a name="arch"></a> Archaelogist
![Archaelogist tooltip](./img/archaelogisttt.png)

Commands:

`/archaelogist` `/arch`

Summary:

<span style="color: F00">Broken</span>

Depends on: Sea, MCom

Is supposed to be an extension to some other addon. Seems to use a deprecated function call.

[Download](./addons/archaelogist.rar)

### <a name="archud2"></a> Arc HUD 2
![Arc HUD 2 tooltip](./img/archud2tt.png)

![](./img/archud22.png)


![](./img/archud21.png)

Commands:

`/archud`

`/ah`

Summary:
This addon adds a combat HUD to your UI, showing player/target/pet hp and mana/rage/whatever as rings centered on your screen. It uses the StatRings code originally made by Iriel but later modified by Antiarc. It also shows a small target frame with textual hp/mana as well as a 3D target model for other players.

It has support for FlightMap destination timers and also have a casting bar with spell text and timer. If the casting bar is enabled it will hide the default Blizzard casting bar.


[comment]: # (TODO: Video)

[Download](./addons/archud2.rar)

### <a name="asmomod"></a> AsmoMOD
![AsmoMOD tooltip](./img/asmomodtt.png)

![](./img/asmomod1.png)

Commands:

`/asmo`

Summary:
Automatically use WotF / trinket on stuns, accepts ressurects, summon, release in BG, cast Overpower, Ripost, cancel heals when target is above certain HP%.

[Download](./addons/asmomod.rar)

### <a name="atlas"></a> Atlas
![Atlas tooltip](./img/Atlastt.png)

![](./img/Atlas1.png)

Commands:

`/atlas`

Summary:

Atlas is a user interface addon for World of Warcraft that provides a number of additional maps as well as an in-game map browser. Typing the command '/atlas' or clicking the mini-map icon will open the Atlas window. The options panel allows you to disable the icon, toggle the Auto Select feature, toggle the Replace World Map feature, toggle the Right-Click feature, change the icon's position, or adjust the transparency of the main window. If the Auto Select feature is enabled, Atlas will automatically open to the map of the instance you're in. If the Replace World Map feature is enabled, Atlas will open instead of the world map when you're in an instance. If the Right-Click feature is enabled, you can Right-Click on Atlas to open the World Map. You can move Atlas around by left-clicking and dragging. Use the small padlock icon in the upper-right corner to lock the window in place.


[comment]: # (TODO: video with all extensions")

[Download](./addons/Atlas.rar)

### <a name="atlasloot"></a> Atlas Loot
![Atlas Loot tooltip](./img/atlasloottt.png)

![](./img/atlasloot1.png)

Commands:

`/atlasloot`

Summary:
Extension to Atlas addon. Adds ability see drop tables from various dungeons, as well as check out different tiers of armors.

[Download](./addons/atlasloot.rar)

### <a name="atlasquest"></a> Atlas Quest
![Atlas Quest tooltip](./img/atlasquesttt.png)

![](./img/atlasquest1.png)

Commands:

`/atlasquest`

`/aq`

Summary:
Extension to Atlas addon. Adds ability to see dungeon related quest, quest gives, and rewards.

[Download](./addons/atlasquest.rar)

### <a name="auctioneer"></a> Auctioneer
![Auctioneer tooltip](./img/auctioneertt.png)

![](./img/auctioneer1.png)

![](./img/auctioneer2.png)


Commands:

`/auctioneer`

Summary:
Depends on EnhTooltip and Stubby
A huge addon that enhances the use of auction house.


[comment]: # (TODO: video, screenshots from AH)

[Download](./addons/auctioneer.rar)

### <a name="afp"></a> Auction Filter Plus
![Auction Filter Plus tooltip](./img/auctionfilterplustt.png)

![](./img/auctionfilterplus1.png)

Commands:

`/auctionfilterplus`

`/afp`

Summary:

* Adds a Filter button and a Reset button to the AuctionHouse frame.
* Pressing the Filter button will cause a Flyout menu to appear.
* The filter checkboxes on the flyout allow you to limit your AH results or change the display of certain information.
* You can clear your filter settings with a single click.
* You can clear your Auction House search boxes with a single click.
* You can save your filter settings as your default setup, which will persist across sessions, characters, and servers.
* You can clear your settings temporarily and then reload them without relogging.
* Each of the filter checkboxes has an explanatory tooltip.
* Ready for localization (please help do so, if you are German- or French-speaking). You will be credited!
* Compatible with Auctioneer.


[comment]: # (TODO: picture in AH)

[Download](./addons/auctionfilterplus.rar)

### <a name="autobar"></a> AutoBar
![AutoBar tooltip](./img/autobartt.png)

![](./img/autobar1.png)

Commands:

`/autobar`

Summary:

Configurable set of 12 buttons that seeks out configured items in your pack for use. Intended primarily for consumables. Not for use with spells, skills, trinkets, or powers.

[Download](./addons/autobar.rar)

### <a name="autobuff"></a> AutoBuff
![AutoBuff tooltip](./img/autobufftt.png)

![](./img/autobuff1.png)

![](./img/autobuff2.png)


Commands:

`/autobuff`
`/ab`

`/autobuff help`
`/ab help`

Summary:

Can be configured to cast buffs automatically, when moving the scroll wheel, switching targets, activating a slash command, or through a keybind

[Download](./addons/autobuff.rar)

### <a name="autodecline"></a> AutoDecline
![AutoDecline tooltip](./img/autodeclinett.png)

![](./img/autodecline1.png)

Commands:

`/ad`
`/autod`
`/autodecline`

Summary:

This modification to the WoW interface allows a player to automatically decline (block) incoming guild invites, party invites, duel invitations, and guild charters.

[Download](./addons/autodecline.rar)

### <a name="autoding"></a> AutoDing
![AutoDing tooltip](./img/autodingtt.png)

![](./img/autoding1.png)

Commands:

`/autoding` `/ad`

Summary:
Sends a preformatted level up message to a specified channel, when the player levels up.

[Download](./addons/autoding.rar)   

### <a name="autograts"></a> Autograts
![Autograts tooltip](./img/autogratstt.png)

![](./img/autograts1.png)

Commands:

`/grats`

Summary:

Sends congratulatory messages to guild members who "ding". Has high level customization. Check the help file in the folder for more information.

[Download](./addons/autograts.rar)

### <a name="autoinvite"></a> AutoInvite
![AutoInvite tooltip](./img/autoinvitett.png)

![](./img/autoinvite1.png)

Commands:

`/autoinvite` `ai`

Summary:

Essentially, whenever someone whispers you and that whisper contains a customizable keyword (it can be mixed in among other things), you'll automatically issue a group or raid invite to them [if you're allowed to].
AutoInvite loads defaulted to on, party invites, using the keyword "invite me".

[Download](./addons/autoinvite.rar)

### <a name="autoprofit"></a> AutoProfit
![AutoProfit tooltip](./img/autoprofittt.png)

![](./img/autoprofit1.png)

Commands:

`/autoprofit` `/ap`

Summary:

Automatically sell gray items when you talk to a vendor

[Download](./addons/autoprofit.rar)

### <a name="autorepair"></a> AutoRepair
![AutoRepair tooltip](./img/autorepairtt.png)

![](./img/autorepair1.png)

Commands:

`/autorepair` `/ar`

Summary:

This Mod automatically Kicks in when you visit a vendor who can repair items.

[Download](./addons/autorepair.rar)

### <a name="autoshoutout"></a> AutoShoutOut
![AutoShoutOut tooltip](./img/autoshoutouttt.png)

![](./img/autoshoutout1.png)

Commands:

`/autoshoutout` `/ash`

Summary:

Does automated notifications, based on user-defined settings.  Can be used by any player who wishes to notify others as to the status of their character.  For example, I use AutoShoutOut when playing my priest character, in instances, so that other people in the group know when I'm about to die or running out of mana.  Will also notify others of the player's pet health status,as well as if the player loses a "Soulstone Resurrection" buff.


[Download](./addons/autoshoutout.rar)

### <a name="availableonly"></a> Available Only
![Available Only tooltip](./img/availableonlytt.png)

Summary:

Only shows available items from Trainers

[Download](./addons/availableonly.rar)

## <a name="b_start"></a>B

### <a name=""></a> 
![ tooltip](./img/tt.png)

![](./img/1.png)

Commands:

``

Summary:


[Download](./addons/.rar)
