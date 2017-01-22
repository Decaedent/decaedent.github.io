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

### [B](#b_start)
* [Backdrop](#backdrop)
* [Bag Status Meter](#bag_status_meter)
* [Bagnon](#bagnon)
* [Bagnon Core](#bagnon_core)
* [Bagnon Forever](#bagnon_forever)
* [Bagnon Options](#bagnon_options)
* [Bank Items](#bankitems)
* [Banknon](#banknon)
* [Banzai Alert](#banzaialert)
* [BanzaiLib](#banzailib)
* [Bartender2](#bartender2)
* [Bartender2 Dream Layout](#bartender2_dreamlayout)
* [BC Ammo Warning](#bc_ammowarning)
* [BC Aspect Menu](#bc_aspectmenu)
* [BC Auto Mail Subject](#bc_automailsubject)
* [BC Tracking Menu](#bc_trackingmenu)
* [Beastmaster](#beastmaster)
* [Basic Experience Bar](#beb)
* [Basic Experience Bar Options](#beboptions)
* [BestBuff](#bestbuff)
* [BGBuddy](#bgbuddy)
* [BGInvite](#bginvite)
* [BigWigs](#bigwigs)
* [Blind Flash Count](#blindflashcount)
* [Block Salvation](#blocksalvation)
* [Bhaldie's Recommended Level](#bmreclevel)
* [Bongos Core](#bongos)
* [Bongos Action Bars](#bongos_actionbar)
* [Bongos Minimap](#bongos_mapbar)
* [Bongos Options](#bongos_options)
* [Bongos Rollbar](#bongos_rollbar)
* [Bonus Scanner](#bonusscanner)
* [Buddy Sync](#buddysync)
* [Buff Ahoy](#buffahoy)
* [Buffalo](#buffalo)
* [BuffWatch](#buffwatch)
* [Buttonhole Advanced](#buttonholead)
* [BuyEmAll](#buyemall)

### <a name="autosave"></a>!AutoSave
![!AutoSave tooltip](./img/autosavett.png)

![!AutoSave ui](./img/autosave1.png)

Commands:

`/autosave`
`/as`

Summary:  
Helps to save progress, by periodically sending ".save" command. This would only work on servers that allow to manually save.

[Download](./addons/!AutoSave.rar)

### <a name="abehfs"></a>ABHelper Estimated Final Score Redux 
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

[Download](./addons/Ace2.rar)

### <a name="ace2"></a> Ace 2
![Ace 2 tooltip](./img/ace2tt.png)

Summary:    
An updated version of Ace 2. This cannot be used as a replacement for addons that depend on Ace 1.

[Download](./addons/ace2.rar)

### <a name="aceaccept"></a> AceAccept
![AceAccept tooltip](./img/AceAccepttt.png)

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
span style="color: F00">Broken</span>
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

<a href="http://www.youtube.com/watch?feature=player_embedded&v=hR4AfG8paB0
" target="_blank"><img src="http://img.youtube.com/vi/hR4AfG8paB0/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

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
When you open your mailbox AH_MailCollect will scan through and automatically retreive any mail that has cash from a successful auction, from being outbid, or from an auction you bid on that was cancelled. You can also choose to see each amount as it's looted, or only a Summary at the end.

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

<a href="http://www.youtube.com/watch?feature=player_embedded&v=HsfBggTMACo
" target="_blank"><img src="http://img.youtube.com/vi/HsfBggTMACo/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

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

<a href="http://www.youtube.com/watch?feature=player_embedded&v=ctRgE-LxSFM
" target="_blank"><img src="http://img.youtube.com/vi/ctRgE-LxSFM/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

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

### <a name="backdrop"></a> Backdrop
![Backdrop tooltip](./img/backdroptt.png)

![](./img/backdrop1.png)

Commands:

`Frame:SetBackdropBorderColor(r,g,b)`

`Frame:SetBackdropColor(r,g,b) `

Summary:    
Creates background, most likely for making UI prettier. Left click drags them around. Shift left click will size the top, shift right click will size the bottom. Ctrl left click will size the left, crtl right click will size the right

[Download](./addons/backdrop.rar)

### <a name="bag_status_meter"></a> Bag Status Meter
![Bag Status Meter tooltip](./img/bag_status_metertt.png)

![](./img/bag_status_meter1.png)

![](./img/bag_status_meter2.png)


Commands:

`/bsm`

Summary:  
A simple addon to summarize the number of slots used within the bags.

[Download](./addons/bag_status_meter.rar)

### <a name="bagnon"></a> Bagnon
![Bagnon tooltip](./img/bagnontt.png)

![](./img/bagnon1.png)

![](./img/bagnon2.png)


Commands:

`/bagnon` `/bgn`

Summary:    
Depends on [Bagnon Core](#bagnon_core)

A bag manager, that collects the contents of all bags into a single window. Has a lot customization options. Allows searching the bags, adding borders to item based on rarity level.

[/r/LegacyAddons](https://www.reddit.com/r/LegacyAddons/comments/5dmgdb/updated_bagnon_addon_for_1121/)  
[Download](./addons/bagnon.rar)

### <a name="bagnon_core"></a> Bagnon Core
![Bagnon Core tooltip](./img/bagnon_corett.png)

Summary:  
Core addon, that all other bagnon addons depend on.

[Download](./addons/bagnon_core.rar)

### <a name="bagnon_forever"></a> Bagnon Forever
![Bagnon Forever tooltip](./img/bagnon_forevertt.png)

![](./img/bagnon_forever1.png)

Summary:  
Extension to bagnon. Allows to view if other characters in the account have the same item, or if the item exists in the bank.

[Download](./addons/bagnon_forever.rar)

### <a name="bagnon_options"></a> Bagnon Options
![Bagnon Options tooltip](./img/bagnon_optionstt.png)

![](./img/bagnon_options1.png)

Commands:

`/bgn` `/bagnon`

Summary:  
Adds more options to bagnong, as well as a GUI for interaction with the addon.

[Download](./addons/bagnon_options.rar)

### <a name="bankitems"></a> BankItems
![BankItems tooltip](./img/bankitemstt.png)

![](./img/bankitems1.png)

Commands:

`/bankitems` `/bi`

Summary:    
Type /bi or /bankitems to see what is currently in your bank.  You must visit your bank one time to initialize.


[comment]: # (TODO: add images from the bank)

[Download](./addons/bankitems.rar)

### <a name="banknon"></a> Banknon
![Banknon tooltip](./img/banknontt.png)

Summary:  
Same as [Bagnon](#bagnon) but for the bank.

[comment]: # (TODO: add images from the bank)


[Download](./addons/banknon.rar)

### <a name="banzaialert"></a> Banzai Alert
![Banzai Alert tooltip](./img/banzaialerttt.png)

![](./img/banzaialert1.png)

![](./img/banzaialert1.png)


Commands:

`/banzaialert` `/banzai`

Summary:  
Can be configured to display a message when you get aggro, start flashing the screen red, and play a sound. Can set to only work when in party.

[Download](./addons/banzaialert.rar)

### <a name="banzailib"></a> BanzaiLib
![BanzaiLib tooltip](./img/banzailibtt.png)

Summary:  
A library that can be used by other addons to facilitate development.Though, it does not seem that Banzai Alert has a dependency on this library

[Download](./addons/banzailib.rar)

### <a name="bartender2"></a> Bartender2
![Bartender2 tooltip](./img/bartender2tt.png)

![](./img/bartender21.png)

![](./img/bartender22.png)

<a href="http://www.youtube.com/watch?feature=player_embedded&v=HsfBggTMACo
  " target="_blank"><img src="http://img.youtube.com/vi/HsfBggTMACo/0.jpg" 
  alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>  

Commands:

`/bartender` `/bar`

Summary:    
Bartender2 is an AddOn to move Blizzards default buttons. It has several
frames which can be moved around screen and locked into the place you wan't.
There is also a feature to hide the frames you don't need.


[comment]: # (TODO: video)

[Download](./addons/bartender2.rar)

### <a name="bartender2_dreamlayout"></a> Bartender2 Dream Layout
![Bartender2 Dream Layout tooltip](./img/bartender2_dreamlayouttt.png)

Summary:  
This should be a skin for [Bartender 2](#bartender2), but I did not manage to get it to work.

[Download](./addons/bartender2_dreamlayout.rar)

### <a name="beb"></a> Basic Experience Bar
![Basic Experience Bar tooltip](./img/bebtt.png)

![](./img/beb1.png)

Summary:  
A simple, modular, experience bar. For customization [Basic Experience Bar Options](#bebOptions) should be enabled.

[Download](./addons/beb.rar)

### <a name="beboptions"></a> Basic Experience Bar Option
![Basic Experience Bar Option tooltip](./img/beboptionstt.png)

![](./img/beboptions1.png)

Commands:

`/basicexperiencebar` `/beb`

Summary:  
A configuration menu for [Basic Experience Bar](#beb)

[Download](./addons/beboptions.rar)

### <a name="bc_ammowarning"></a> BC Ammo Warning
![BC Ammo Warning tooltip](./img/bc_ammowarningtt.png)

Summary:    
Displays warning messages when the ammo type you have equiped in your ammo slot
reaches configurable levels.  Initial values are set to warn you when your ammo
reaches 200, and then every 50 shots after that until your ammo reaches the
critical limit.  Then, you recieve warnings every shot until you run out of ammo.

Setup has to be done through editing the source code of the addon.


[comment]: # (TODO: Add picture of the warning)

[Download](./addons/bc_ammowarning.rar)

### <a name="bc_aspectmenu"></a> Aspect Menu
![Aspect Menu tooltip](./img/bc_aspectmenutt.png)

Commands:  
`/bcam_report`  
`/bcam_showmenu`  
`/bcam_hidemenu`  
`/bcam_getloc`  
`/bcam_showoptions`  
`/bcam_hideoptions`  

Summary:  
Adds an icon to the minimap cluster that provides a popup menu of currently available aspect abilities.


[comment]: # (TODO: hunter image)

[Download](./addons/bc_aspectmenu.rar)

### <a name="bc_automailsubject"></a> BC - Auto Mail Subject
![BC - Auto Mail Subject tooltip](./img/bc_automailsubjecttt.png)


Summary:    
Automatically populates the subject of a mail message with the name and quantity of the item you drag into the attachment box.  Will only work if the subject line is currently empty, so it won't erase what you've already typed there.

### <a name="bc_trackingmenu"></a> BC Tracking Menu
![Tracking Menu tooltip](./img/bc_trackingmenutt.png)

![](./img/bc_trackingmenu1.png)

Commands:  
`/bctm_report`  
`/bctm_showmenu`  
`/bctm_hidemenu`  
`/bctm_getloc`  
`/bctm_showoptions`  
`/bctm_hideoptions`  
`/run bcTM_ShowMenu(x, y, anchor);`  


Summary:  
Replaces the tracking icon on the minimap with an icon that has a popup menu that allows you to choose which tracking ability to activate. The menu is displayed when you mouse over the icon and is hidden when your mouse is no longer over the icon or the menu. The list of abilities in the menu is automatically populated* with the tracking abilities available to your character, and should update when you aquire new tracking abilities

[Download](./addons/bc_trackingmenu.rar)


[comment]: # (TODO: add picture at mailbox)

[Download](./addons/bc_automailsubject.rar)

### <a name="beastmaster"></a> Beastmaster
![Beastmaster tooltip](./img/beastmastertt.png)

Summary:    
Another 'short and sweet' addon, Beastmaster changes the way that beast training abilities are sorted.  Rather than displaying in order of rank, they're now grouped by abilities (ie dive, growl, etc). This way it is easier to find the ability you want, or look up what the highest rank known to you.



[comment]: # (TODO: hunter example)
[Download](./addons/beastmaster.rar)

### <a name="bestbuff"></a> BestBuff
![BestBuff tooltip](./img/bestbufftt.png)

![](./img/bestbuff1.png)

Commands:

`/bestbuff`

Summary:    
Casts the best rank possible of various buffs on caster's target,irregardless of caster or target level.

/bestbuff will bring up a window to set options and define buffs. Generally you will only need to do this once or very seldom. There are now two ways to use BestBuff:
Old way: /script BestBuff(buff_name)
    ie: /script BestBuff("Power Word: Fortitude")

New way: Go into /bestbuff config panel and check Enabled. Any buff defined there on your action bars will automatically BestBuff.


[Download](./addons/bestbuff.rar)

### <a name="bgbuddy"></a> BGBuddy
![BGBuddy tooltip](./img/bgbuddytt.png)

![](./img/bgbuddy1.png)

Commands:

`/bgbuddy` `/bgb`

Summary:    
BGBuddy is a simple addon which tracks your progress in 
the battlegrounds and provides helpful features such as
Auto-Join, Auto-Resurrect and Auto-Release.

[Download](./addons/bgbuddy.rar)

### <a name="bginvite"></a> BGInvite
![BGInvite tooltip](./img/bginvitett.png)

![](./img/bginvite1.png)

Commands:

`/bginvite`

Summary:  
Seems to be an addon, that will automatically invite players to party / raid. Can be configured to a specifc "magic word", and blacklist players to be ignored by the addon.

[Download](./addons/bginvite.rar)

### <a name="bmreclevel"></a> Bhaldie Recommended Level
![Bhaldie Recommended Level tooltip](./img/bmrecleveltt.png)

![](./img/bmreclevel1.png)

Commands:

`/brlconfig`

Summary:  
Displays a small panel, that displays the recommended level for the current zone. Can also show other zones, that are similar to the player's level.

[Download](./addons/bmreclevel.rar)

### <a name="bigwigs"></a> Big Wigs
![Big Wigs tooltip](./img/bigwigstt.png)

![](./img/bigwigs1.png)

![](./img/bigwigs3.png)

![](./img/bigwigs2.png)


Commands:

`/bigwigs` `/bw`

Summary:  
A huge addon, that includes majority of the bosses in game. Provides shout outs, and timers for boss skills. Nearly a mandatory addon for raiding.


[comment]: # (TODO: video review)

[Download](./addons/bigwigs.rar)

### <a name="blindflashcount"></a> Blind Flash Count
![Blind Flash Count tooltip](./img/blindflashcounttt.png)


Summary:  
Sgiws Vkubd abd Fkasg oiwder count in the ability icon itself.


[comment]: # (TODO: rogue picture)

[Download](./addons/blindflashcount.rar)

### <a name="blocksalvation"></a> Block Salvation
![Block Salvation tooltip](./img/blocksalvationtt.png)

![](./img/blocksalvation1.png)

Commands:

`/bs`

Summary:  
Can be toggled, to automatically block [Blessing of Salvation](http://db.vanillagaming.org/?spell=1038)


[Download](./addons/blocksalvation.rar)

### <a name="bongos"></a> Bongos
![Bongos tooltip](./img/bongostt.png)

![](./img/bongos1.png)

<a href="http://www.youtube.com/watch?feature=player_embedded&v=qtfpinmBifU
" target="_blank"><img src="http://img.youtube.com/vi/qtfpinmBifU/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

Commands:

`/bongos` `/bob`

Summary:
A framework, that other Bongos addons use.

[Download](./addons/bongos.rar)

### <a name="bongos_actionbar"></a> Bongos Action Bar
![Bongos Action Bar tooltip](./img/bongos_actionbartt.png)

![](./img/bongos_actionbar1.png)

Summary:  
Adds custom action bars, that replaces Blizzard's.

[Download](./addons/bongos_actionbar.rar)

### <a name="bongos_mapbar"></a> Bonbos Minimap
![Bonbos Minimap tooltip](./img/bongos_mapbartt.png)


Summary:  
Seems to be a Bongos implementation of a custom minimap. Did not manage to get this to work.

[Download](./addons/bongos_mapbar.rar)

### <a name="bongos_options"></a> Bongos Options
![Bongos Options tooltip](./img/bongos_optionstt.png)

![](./img/bongos_options1.png)

Commands:

`/bongos` `/bob`

Summary:  
Adds a GUI to Bongos options.


[Download](./addons/bongos_options.rar)

### <a name="bongos_roll"></a> Bongos RollBar
![Bongos RollBar tooltip](./img/bongos_rollbartt.png)

![](./img/bongos_rollbar1.png)

Commands:  
`/bongos`

Summary:  
A movable frame for rolling on items

[Download](./addons/bongos_rollbar.rar)

### <a name="bonusscanner"></a> Bonus Scanner
![Bonus Scanner tooltip](./img/bonusscannertt.png)

![](./img/bonusscanner1.png)

Commands:  
`/bonusscanner` `/bscan`

Summary:  
Summarizes the bonuses from equipped. Can show bonuses even from linked items. Is sometimes used by other addons. 

[Download](./addons/bonusscanner.rar)

### <a name="buddysync"></a> BuddySync
![BuddySync tooltip](./img/buddysynctt.png)

![](./img/buddysync1.png)

Commands:  
`/buddysync` `/bs`

Summary:  
Used to sync the friend list between all characters in the same realm, that belong to the same account.

[Download](./addons/buddysync.rar)

### <a name="buffahoy"></a> Buff Ahoy
![Buff Ahoy tooltip](./img/buffahoytt.png)

![](./img/buffahoy1.png)

Commands:  
`/buffahoy help` `/ba help`

Summary:  

A Passive Party Targetting (PPT) system, which allows spells to be cast on party members passively (i.e. without explicitly targetting them)  
A SmartCast algorithm, which allows you to use the SHIFT, ALT, or CTRL key to make spells target yourself  
A buff sequencer, so that one button (pressed repeatedly) will buff the entire party or raid group, including pets, with a customizable set of buffs using the PPT system (so you can buff during combat without having to break your combat target).  
Heal, Cleanse, and Protect slots that use the PPT system to cast spells on party members during combat  
A spell sequencer, so that one button can be pressed repeatedly to cast a series of spells on a hostile or friendly target.  
4 ShoutCast slots, which automatically announce to the party (or raid group) which spell is being cast and who the target is.  
All functions now automatically get the name of the spell being cast and use it in the party messages (if set to verbose mode)  


[comment]: # (TODO: maybe video? )

[Curse Forge](https://wow.curseforge.com/projects/project-201)
[Download](./addons/buffahoy.rar)

### <a name="buffalo"></a> Buffalo
![Buffalo tooltip](./img/buffalott.png)

![](./img/buffalo1.png)

![](./img/buffalo2.png)

<a href="http://www.youtube.com/watch?feature=player_embedded&v=rRZAYpkotwQ
" target="_blank"><img src="http://img.youtube.com/vi/rRZAYpkotwQ/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

Commands:  
`/buffalo`

Summary:  
A highly customizeable buff display.

[Download](./addons/buffalo.rar)

### <a name="buffwatch"></a> Buff Watch
![Buff Watch tooltip](./img/buffwatchtt.png)

![](./img/buffwatch1.png)

![](./img/buffwatch2.png)


Commands:  
`/buffwatch` `/bw`

Summary:  
BuffWatch is a powerful buff manager that lets you easily and clearly keep
track of active and inactive buffs, as well as allowing you to rebuff players
with a single click.

Simply setup the buffs you want to monitor for each player in your party/raid,
and buffwatch will notify you if the buff expires. You can then click the
highlighted buff to automatically recast the buff on that player, if you have
the ability to do so.

[Download](./addons/buffwatch.rar)

### <a name="buttonholead"></a> ButtonholeAd
![ButtonholeAd tooltip](./img/buttonholeadtt.png)

![](./img/buttonholead1.png)

![](./img/buttonholead2.png)


Commands:  
`/buttonholead` `/bha`

Summary:  
Gathers all minimap buttons to a single frame, that can be expanded
[Download](./addons/buttonholead.rar)

### <a name="buyemall"></a> BuyEmAll
![BuyEmAll tooltip](./img/buyemalltt.png)

![](./img/buyemall1.png)

Summary:  
BuyEmAll enhances the shift-click interface at vendors.

[Download](./addons/buyemall.rar)

