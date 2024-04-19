## 1.3.9d (2024-04-20)
- Minor improvements in terms of security;
- Removing old and no longer needed functions;
- “Wrapper” for new functions;
- Updated **Auto Follow** function:
  - In past all casters (+ hunter) have small distance ~ 10 yards. For now its have random value (distance from follow target to u), but  not less than 7-8 yards;
    - By enabling Is Melee now even casters (+hunter) will have distance 1-2 yards to follow target;
  - Same with melee classes. For now they have random follow distance which change time to time;
- Changing CR pause function;
- Add Key binding function for call GUI/enable profiles to any key (will expanded later);

## 1.3.9b (2024-03-20)
- New functional added;
- Safety update;

## 1.3.8 (2024-01-24)
- Support for the **Warmane Onyxia** server and its vanilla spells;
- All functions and some kind of interaction between them, which checked the current character spec - reworked, and will work more correctly with minimal load;
- Slightly fixed and improved the autofollow function. Now all rangers, aka hunters, healers, mages/warlocks, etc., will keep a distance of ~ 10 y from the target you are following, all melee will still run closely behind the target;
- Made some changes to quickly enable/disable some special/individual functions in the core remotely;
- The system for activating profiles in general has also changed slightly.
  - Made available the "Free Weekend" function - in which all classes will be available to everyone for a short period of time;
- Made system frames dynamic. When streamer mode is enabled, only chat text will be displayed;
- The check for using items, potions and the rest has been slightly changed. Now there will be a comparison of levels, effects and selection of the best available to you at the moment;

## 1.3.7d (2023-11-22)
- Minor optimizations and tweaks for Streamer Mode;
  - Fixed a bug when a noticeable strip of color was displayed in the GUI of profiles when the Class Colors mode was enabled;
- Minor security and protection improvements;
- Healing Forecast
  - Optimization of the function and counting;
    - Should have a positive impact on performance when playing as healers. Even if you haven't used this feature;

## 1.3.7c (2023-11-10)
- Minor optimizations and tweaks for Streamer Mode;
- Sound accompaniments have been added to all program elements. Now the entire interface and 99% of its components are WoW-Looklike;
- Minor changes to Healing Engine;
  - More accurate checks of some units;
- It seems like it should improve performance a little;
  - Most likely there will not be such strong drawdowns in FPS, or on the contrary, some FPS will even rise;

## 1.3.6 (2023-09-17)
- Improved security;
- Minor bugfix;
- Auto-update/download Core files when launcher starts.

## 1.3.5b (2023-08-16)
- Improved security;
- Minor bugfix;
- New functions for GUI profiles;
   - Will be used in profiles in future updates;
- Refinement of Healing/Members engine;
   - Allies in control will be automatically ignored and not healed / dispelled, etc.;

## 1.3.5a (2023-08-01)
- Improved security;
- Minor bugfix;

## 1.3.5 (2023-07-21)
**New:**
- Changed the design of MainUI (program window);
	- Some elements moved to other places;
	- The menu has become more understandable;
- Profiles can now load up to 3 (three) presets of settings;
- Added **"Custom Button #2"** (to be applied in new updates);
- Updated menu item **"Rotation settings"**;
- Updated design with ElvUI integration;
- Added buttons "Quick removal" nicknames of tanks;
- Added ability to ignore/reduce/increase stacks https://wotlk.evowow.com/?spell=70106 / https://wotlk.evowow.com/?spell=69766 ;

**Fixes**:
- Healing / Members Engine fixes;
- Minor bug fixes;
- Optimization of heavy code;

## 1.3.4d (2023-06-20)
- Small tweaks;
- Fixed an issue when CR could stop after loot from mobs/chests, etc.

## 1.3.4c (2023-06-05)
- Small tweaks;

## 1.3.4b (2023-05-26)
- Bypass + "protection" of a possible detection on WoW Circle dated 2023-05-26;

## 1.3.4a (2023-05-21)
- Fix typos;

## 1.3.4 (2023-05-21)
**New:**
- Completely new Healing / Members Engine - faster, more correct, with more functionality;
	- Program and profiles now have a 99% chance of identifying allied specializations
		- **IMPORTANT**: The function is quite tricky and recording and checking all this information happens when you are not in battle, that is, if you do some /reload in the middle of the battle, all information will be cleared and profiles and software will be work incorrectly;
		- **IMPORTANT #2**: With any profile enabled, viewing other characters may be lame, since the function uses a bypass to check for specializations. **THIS IS NOT A BUG, it should be so, until I managed to defeat it, but I think in a couple of days I will make a small release where I can get around it**;
- New method for loading profiles, getting settings, etc.;
	- In theory and in practice, it gives slightly faster loading and processing of all information and code in general;
	- Also allows you to update profiles and some core functionality almost seamlessly;
- All profiles AGAIN got a little smaller, on average by ~ 3-10% with more extensive functionality;
- A large number of optimizations for the core and profile code in general;
- **Warmane**: Added a trick to this server to make the profiles and core functionality do its job properly;

**Corrections:**
- Small bug fixes;
- Heavy code optimization;