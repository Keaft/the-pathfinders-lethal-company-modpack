# The Pathfinders Lethal Company Modpack
 A fantastic multiplayer modpack that tries to stay true to the original feel with some minor content additions and quality of life adjustments.
 
 An update to this pack requires recreating your r2modman profile only in the case where a mod is removed. Mod additions or configuration changes shouldn't require recreating your profile.
 - In the case of recreation, you will lose your personalizations like cosmetics and player made profiles, unless you go into the profile and take a backup of your personalized files.
 
 If available, you should always update every mod after opening the pack in r2modman.
 
 If you have saves that you wish to maintain, take a backup before installing this modpack.
 
 I'm inept at versioning. The date doesn't have to precisely measure the scope of my updates. :D 
 
## Changelog
### 24.2.1501
#### Mod(s) Added:
- **PathfindingLagFix** to hopefully address some lag while in the facility.

### 24.2.1500
#### Mod(s) Added:
- **CullFactory** stops the client from rendering the map that isn't currently visible to the player improving performance.
- **OpenBodyCams** in hopes of having a more performant body/head cam on the monitor from selected player. Good compatibility with GeneralImprovements.

#### Mod(s) Removed:
- **HelmetCameras** woops this should have been removed a while ago. :D

#### configurations:
- Lowered the total number of suits rendered on the rack at a time to improve performance.
- Changed monitor layout slightly to allow external camera to be shown.

### 24.2.1400
#### Mod(s) Updated:
- **AdvancedCompany** to 1.1.1.

### 24.2.1301
#### Configurations:
- Change Scrap Insurance cost to 200 bringing the pack into a decent position for singleplayer as well as multiplayer.

### 24.2.1300
#### Mod(s) Added:
- **GeneralImprovements** which fixes bugs and replaces a bunch of other mods functionality.

#### Mod(s) Removed:
- **Corporate Restructure** now handled by GeneralImprovements.
- **FastSwitchPlayerViewInRadar** now handled by GeneralImprovements.
- **IntroTweaks** now handled by GeneralImprovements.
- **LetMeLookDown** now handled by GeneralImprovements.

#### Configurations:
- Established the layout of the new in ship monitor setup.
- Removed Controller scrap from Pathfinders Standard Preset. Doom is a huge departure from vanilla even if it is a cool concept. :D
- Finalized GeneralImprovements configurations to properly replace mods and be compatible with existing mods.

### 24.2.1202
#### Mod(s) Added:
- **Quick Drop** in replacement of ItemDropCycler.

#### Mod(s) Removed:
- **ItemDropCycler** didn't cycle quite as nicely as Quick Drop does.

### 24.2.1201
#### Configurations:
- Fixed typo in suit removal.

### 24.2.1200
#### Mod(s) Added:
- **IntroTweaks** skips the intro and various menu tweaks. Time is money! Get in there!
- **AdvancedCompany** gives greater control over lobby as well as replacing several other mods!
- **EmoteWhileInMotion** in replacement of AllwaysCanDance to fix the inability to crouch while emoting.
- **TooManySuits** adds pages to suits.
- **5andwiches_Closet** adds suits and cosmetics.
- **MoreMaterials** library for cosmetics.
- **ItemDropCycler** restore the item drop cycling from the HotbarPlus removal.

#### Mod(s) Removed:
- **AllwaysCanDance** now covered by EmoteWhileInMotion.
- **HotbarPlus** now covered by AdvancedCompany.
- **LateCompany** now covered by AdvancedCompany.
- **MoreItems** now covered by AdvancedCompany.
- **ItemQuickSwitch** now covered by AdvancedCompany.
- **MoreMonsters** now covered by AdvancedCompany.

#### Configurations:
- Remove HotbarPlus configs.
- Added a Pathfinders Standard preset for AdvancedCompany.
- Disabled some suits.
- Adjusted BetterItemScan to only show ship total while in the ship.

### 24.2.1100
#### Mod(s) Added:
- **HotbarPlus** to dispell the confusion from other games in the first person genre.
- **Corporate Restructure** for QoL information displayed in the ship.
- **LethalConfig** for easier configuration changes for the future.
- **HideChat** to fade chat out after a while increasing immersion.
- **DiscountAlert** for a little message if there are discounts.
- **FastSwitchPlayerViewInRadar** for tighter control over who you are viewing on the terminal monitor.
- **BetterSprayPaint** to bring spray paint into focus as a useful tool by making it continuous and infinite.
- **EmployeeAssignments** minor content addition allowing additional tasks to be performed to gain more scrap.
- **MoreMonsters** as an administrative tool for balancing difficulty depending on party size.
- **AllwaysCanDance** minor change to emotes allowing movement. Now you can point and ~~chew gum~~ point at the same time! Will need to monitor to see if it's obnoxious.
- **LethalCompany InputUtils** as a library for other mods to work.

#### Configurations:
- Removed Utility belt. 4 items max! Or at least until the company decides to increase it :D
- Removed Remote Radar.
- Fatalities sign now costs 20. It should be company standard issue, but you know how they are some times...
- Dart Board is cheaper. It's not a pizza party but...
- Established configs to make sure ItemQuickSwitch and HotbarPlus play nicely.

#### Known issue(s):
- On startup **EmployeeAssignments** says it's out of date, but it's not. :D

### 24.2.901
- Removed Custom Boombox Music mod.
- Alphabetized the mod list by mod name.
- Updated readme.
- Added configuration file which removes the portable teleporter items.
- Added LCBetterSaves 1.7.3 for a nicer save system.