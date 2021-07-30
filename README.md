# Better Morrowind Sorting Names v2.0.1
### Rename Armor/Potions/etc for better inventory ordering

Find this mod on Nexus as [Better Sorting Names MWSE](https://www.nexusmods.com/morrowind/mods/50018).

This is a MWSE script that renames some items in Morrowind so that they sort together in your inventory and in your containers. Bethesda's insistence on naming everything with a quality/material adjective FIRST means that it's a bit difficult sometimes to ascertain which items you have, because items of the same kind are spread around.

Better Sorting Names tries to help with that. It tries to keep sets together, as per default Morrowind (like all Glass Armor in a group), but also tries to put same-kind items together, like all Longswords together, and all Axes together, etc. Some obvious candidates for renaming are the bracers and pauldrons, which are named `Left Pauldron` and `Right Pauldron` in Morrowind, meaning they are not together in your inventory. To fix this, Better Sorting Names renames them to `Pauldron Left` and `Pauldron Right` so that they group. Other obvious candidates are Potions, which now group by Effect and not by Quality (if you decide to enable this). Soulgems, and Clothing, especially from [Clothiers of Vvardenfell](https://www.nexusmods.com/morrowind/mods/50007), also benefit greatly.

Keys and Propylon indexes are other items in dire need of renaming, but  they are not included in Better Sorting Names, since there's a mod for  that already, see [Consistent Keys](https://www.nexusmods.com/morrowind/mods/47954) and[ Propylon Index Renamer](https://www.nexusmods.com/morrowind/mods/49941) by Necrolesian.

### Renamed Items:

Better Sorting Names will rename the following categories of items, and each category can be turned Off/On in the Mod Config Menu:

- Armor (*Left Pauldron -> Pauldron Left*)
- Clothing (*Common Pants -> Pants Common*)
- Potions using `Effect Quality` (*Exclusive Potion of Fortify Luck > Fortify Luck Exclusive*)
- **or** Potions using `Potion Effect Quality` (*Potion of Fortify Luck > Potion Fortify Luck Exclsv*) [31 Chars]
- Weapons (*Silver Longsword -> Longsword Silver*)
- Souldgems (*Greater Soulgem -> Soulgem Greater*)

### Additionally, you can:

- Give MW/Trib/BM potions an inventory icon badge (same as [Labeled_Potions-44374](https://www.nexusmods.com/morrowind/mods/44374) by r0)
- Give custom potions an icon badge (this is decided **when installing** Better Sorting Names)
- Rename books that give a skill with "+Skill#" (*e.g. 36 Vivec Lessons +14*) [+1 Mysticism]
- Give Higher Quality Tools (e.g. Lockpicks) more uses than cheaper ones (makes sense no?)

### The mod supports items from:

- Morrowind, Tribunal and Bloodmoon.
- [PFP](https://www.nexusmods.com/morrowind/mods/45096) corrections to item names are included.
- [Tamriel-Data](https://www.nexusmods.com/morrowind/mods/44537) items (that's a lot of extra items).
- [OAAB-Data](https://www.nexusmods.com/morrowind/mods/49042) (another source of items).
- [Clothiers of Vvardenfell](https://www.nexusmods.com/morrowind/mods/50007) (a lot of items here too).
- [Morrowind Public Library](https://www.nexusmods.com/morrowind/mods/17379) (the Tea's [potions]).
- [Abot's Water Life](https://www.nexusmods.com/morrowind/mods/42417) (A few items).
- [Hunter's Mark - A Marksman Mod](https://www.nexusmods.com/morrowind/mods/46656).
- [Area Effect Arrows](https://www.nexusmods.com/morrowind/mods/42989) (from Bethesda).
- [An Issue Of Thrust](https://www.nexusmods.com/morrowind/mods/44650).
- [Crossbows Enhanced](https://www.nexusmods.com/morrowind/mods/48586).
- And any other mod I use...

## Opening a Github Request/Issue

Since I do not use a lot of "New Items" mods, there is a lot that is not covered by Better Sorting Names, so I setup a Github where you can make **Pull Requests** to rename other mod items. I am stressing this point, **I expect Pull Requests** on the items files, i.e. the LUA tables that define the new names. If you guys open an issue that only states "Please support MOD X" I am unlikely to do so, unless a lot of people vote for it or I decide to use the mod myself.

Requirements
------------

You need MWSE with LUA installed, which comes with MGE-XE, see:

* https://www.nexusmods.com/morrowind/mods/41102
* https://www.nexusmods.com/morrowind/mods/45468

INSTALLATION
------------

- **00 Better Names Core**
  - This is the MWSE Better Sorting Names script and the badges for the regular potions.
- **01 Custom Potions Badge**
  - This is an extra badge for OTHER potions. This CANNOT be toggled in the Mod Config menu, so if you install the 01 folder, your custom potions will have the badge, and if you do not enable the badges in the Mod Config Menu, then ALL potions will have the custom badge.

Thanks
------

* Greatness7 for help and for the potion badge code
* Merlord for help and for the MCM and config controller code
* Necrolesian for help and for Consistent Keys code
* r0 for permission to use the potion badges.

License
-------

Creative Commons Attribution 4.0

