**LootBT**

LootBT (or Loot Battle Text) is a lightweight addon that improves the loot / item notification experience, with a focus on clarity and customization. It was designed to work with WoW 12.0 and onwards after most combat text addons lost major functionality or died completely. It's been tested on MoP Classic and while not officially supported, should function OK.





To massively expand the font list, I highly recommend installing Lib: Shared Media and SharedMediaAdditionalFonts.

**What it does**

Provides text notifcation pop-ups on screen that show loot/currency/reputation/skill gains and losses in an easy to digest format. Provides totals for loot obtained so you know how many you now have at a glance. Shows you a customizable enter/exit combat state notification.  Allows you to turn each type of notification on/off for a clean, personalized UI. Allows you to customize the location, scale and color, and now also the fonts of your notifications, with built-in support for LibSharedMedia fonts.


**Configuration**

LootBT includes an in-game Options and toggleable minimap button (compatible with SexyMap's auto-hide). 


**Usage**

Type /lootbt or click the minimap icon to open options.


**Future Potential Features (WIP)**

Item whitelist/blacklist


All feedback is welcome, please use comment section on Curseforge, or hit me up on Discord - Grue#2612

Credit to the author/s of Mik's Scrolling Battle Text for the heavy inspiration for this mod. I couldn't play without these features once it stopped working on Midnight release.

I also highly recommend installing Lib: SharedMedia-3.0 and SharedMediaAdditionalFonts to enhace your experience with LootBT.


**Changelog**

v1.4.4

Updated UI on Layout tab to be cleaner.
Fixed bug with resize arrow and window snapping to wrong size.
Fixed bug where font drop-down would corrupt other drop-downs.


**Older**

- Added toggle to show/hide delve companion XP gains.
- Added toggle to show/hide item icons in notification.
- Added toggle to show/hide item totals.
- Updated anchor to reflect config changes live when unlocked rather than only refreshing on a lock/unlock.
- Changed profile save/deletion in UI to stop deletion Xs polluting other drop-downs.
- Fixed bug where LootBT was attempting to use a tainted value when gaining reputation from killing a boss.
- Added Padding sliders to Layout tab.
- Added Test notifications button to each tab.
- Added Max notifications sliders to Layout tab.
- Moved sliders around on Layout tab to make more sense.
- Improved reputation grouping to reduce notification spam.
- General anchor and options UI layout updates.
- Additional split of core into extra lua modules.
- Code tidied, old unused branches removed.
- Fixed bug where rapidly looting quest items would show the final total in each notificaiton. Also improved grouping so less notifications should be seen overall.
- Fixed bug where anchor titles would resize when moving Base font slider.
- Massive backend/code cleanse and update.
- Fixed bug causing red X buttons to appear in font dropdown menus after using the Profiles dropdown.
- Corrected quest and world quest progress handling to use shared internal logic.
- Tidied minimap button and font dropdown backend handling.
- Added toggle for quest items.
- Adjusted UI behaviour and look around arrow/coin toggles.
- Added font selection options on Customize tab, including per notification toggle.
- Updated anchors and Colors tab to reflect chosen font.
- Added support for LibSharedMedia fonts.
- Added toggle to remove uncommon symbols (such as [], +/-) to avoid graphical errors when chosen font doesn't include these.
- Corrected anchor behaviour on reload/login to be locked unless it's the first time using LootBT.
- Tested version on MoP Classic, most functionality seems OK. Added 5.3.5 to version load list.
- Grouped currency notifications that happen within a short period of time to one another.
- Updated combat start/stop notifications to cleanse duplicate notifications to prevent spam/confusion.
- Added option for upgrade arrow to show when looting type-appropriate equippable gear (only compares ilvl to what you have equipped).
- Added option to toggle money notifications between text (2g 33s) and coin icons.
- UI amended to center and tidy up options.
- Various backend updates to queuing of notifications and preservation of variables/profile states.
- Removed unnecessary Reset button from Profiles tab.
- Fixed bug causing currency totals to become out of sync and show incorrect values when quests were turned in rapidly. 
- Warnings added to options tabs when using Default profile advising that changes won't be saved between login sessions.
- Message added to options tabs when using custom profile to advise profile is saved automatically as changes are made.
- Added new Profiles tab, with ability to import/export.
- Added 'Reset to defaults' buttons.
- Fixed bug with minimap button occasionally not appearing on login despite option to show button being ticked.
- Removed some unnecessary hint text.
- Fixed bug with calculating totals for World Quest related items, espeically if the WQ was resumed after leaving or logging out/in.
- Fixed bug when obtaining final item for a World Quest, and the WQ completed before LootBT calculated progress.
- Separated notification toggles into categories based on which anchor they use.
- Adjusted positioning of items in options panel to be more dynamic based on window size.
- Renamed Loot Anchor to Stack Anchor for consistency. 
- Corrected a bug with handling of totals for items that are quest items at one point but become normal items after the quest is completed.
- Added filter for grey items on the Customize tab.
- Updated quest item loot total notification to show quest progress.
- Removed mentions of abandoned XP notification (unable to block Blizzard's XP so no point continuing this).
