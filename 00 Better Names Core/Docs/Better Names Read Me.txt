# Better Morrowind Sorting Names v2.2
### Rename Armor/Potions/etc for better inventory ordering

By Booze (B00ze64) 2021-08

1. B00ze64@zoho.com (best)
2. B00ze64@hotmail.com (if you must)
   Note that hotmail spam filters suck mail like a blackhole...



Find this mod on Nexus as [Better Sorting Names MWSE](https://www.nexusmods.com/morrowind/mods/50018).

This is a MWSE script that renames some items in Morrowind so that they sort together in your inventory and in your containers. It is a very simple script that runs when the game starts, then exits. Bethesda's insistence on naming everything with a quality/material adjective FIRST means that it's a bit difficult sometimes to ascertain which items you have, because items of the same kind are spread around.

Better Sorting Names tries to help with that. It tries to keep sets together, as per default Morrowind (like all Glass Armor in a group), but also tries to put same-kind items together, like all Longswords together, and all Axes together, etc. Some obvious candidates for renaming are the bracers and pauldrons, which are named `Left Pauldron` and `Right Pauldron` in Morrowind, meaning they are not together in your inventory. To fix this, Better Sorting Names renames them to `Pauldron Left` and `Pauldron Right` so that they group. Other obvious candidates are Potions, which now group by Effect and not by Quality (if you decide to enable this). Soulgems, and Clothing, especially from [Clothiers of Vvardenfell](https://www.nexusmods.com/morrowind/mods/50007), also benefit greatly.

Keys and Propylon indexes are other items in dire need of renaming, but  they are not included in Better Sorting Names, since there's a mod for  that already, see [Consistent Keys](https://www.nexusmods.com/morrowind/mods/47954) and[ Propylon Index Renamer](https://www.nexusmods.com/morrowind/mods/49941) by Necrolesian.

### Version 2.1

- Corrected some copy/paste mistakes.
- Added a few more mods (listed below).
- Added a numerical index to Soulgems (I,II,III,IV,V) so they sort by quality.

- Added Tools (Lockpicks, probes, repair, alchemist's) sorted by increasing quality.


- I redid potion quality adjectives, inspired by BTB, so now they sort by quality (Bargain, Cheap, Normal, Quality, Select). I also prefixed pretty much everything else in Alchemy with Bottle of, Bottled and Mug of, so that if you use the "Potion-Potion" scheme, the potions will all group after everything else. There are also a few potions that always use the "Potion of" prefix, so you can find them easily since they group together (e.g. Mark and Recall).


- In general, I was a bit more aggressive in trying to group items together - I still group armors by set, as I think that makes the most sense, but several uniques (clothing) received a prefix (e.g. Ring) so that they sort with their kind.


- And I was extremely aggressive with weapon prefixes; now only a few uniques will not sort together: Short blades now have the Blade prefix, Long blades have the Sword prefix, Two-Handed blades have the TwoHanded prefix when the 31 char limit permitted, i.e. Claymores and Scythes (enchanted) could not accommodate the prefix. Axes have the Axe prefix, Two-Handed axes have the Battle Axe prefix (which should place them right after one-handed axes). Blunt one-handed weapons have the Blunt prefix (e.g. Blunt Mace Steel) and blunt two-handed weapons are Warhammers, War Maces and War Mauls, so they should sort together. Bows are all prefixed with Bow and crossbows with Crossbow, which should make them group together. Throwing weapons all have the Thrown prefix (some of those enchanted ones could not accommodate the Throwing prefix) but I had to drop the "of" on a number of them to fit the 31 characters limit (e.g. Thrown Star of Cruel PoisonBloom is too long). Finally, Spears all have the Spear prefix, including Halberds (not ideal, but this way they all group together). Bound weapons still retain the Bound prefix. It's not perfect, but all the weapons sort by kind a lot better now.

### Version 2.2

- Added a few more mods.

- And while I liked prefixing daggers with "Blade," I think "Short" is a better prefix for shot blades in general. It does not work super-well with daggers since a short dagger would be nothing more than a toothpick, but if we abstract the prefix as a weapon-type in our minds, it's not so bad. And Short Sword is far better than Blade Sword. So I've changed the prefix for short blades to Short. This means I've switched some of those enchanted ones (e.g. Viperblade) from Daggers back to Blades, which respects the original name better (e.g. Short Blade of Viper).


### Renamed Items:

Better Sorting Names will rename the following categories of items, and each category can be turned Off/On in the Mod Config Menu:

- Armor (*Steel Left Pauldron -> Steel Pauldron Left*)
- Clothing (*Common Pants -> Pants Common*)
- Potions using `Effect Quality` (*Exclusive Potion of Fortify Luck > Fortify Luck Select*)
- **or** `Potion Effect Quality` (*Potion of Fortify Luck Exclusive > Potion Fortify Luck Select*) [31 Chars]
- Soulgems (*Greater Soulgem -> Soulgem IV Greater*)
- Tools (Journeyman's Lockpick -> Lockpick Journeyman's)
- Weapons (*Silver Longsword -> Sword Long Silver*)

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
- [Abot's Water Life](https://www.nexusmods.com/morrowind/mods/42417) (A few items).
- [Area Effect Arrows](https://www.nexusmods.com/morrowind/mods/42989) (from Bethesda).
- [An Issue Of Thrust](https://www.nexusmods.com/morrowind/mods/44650).
- [Ancient Foes](https://www.nexusmods.com/morrowind/mods/44705).
- [Beautiful Cities of Morrowind](https://www.nexusmods.com/morrowind/mods/49231).
- [Clothiers of Vvardenfell](https://www.nexusmods.com/morrowind/mods/50007) (a lot of items here too).
- [Constance Thief Companion](https://www.nexusmods.com/morrowind/mods/1457).
- [Crossbows Enhanced](https://www.nexusmods.com/morrowind/mods/48586).
- [Frozen in Time-50077](https://www.nexusmods.com/morrowind/mods/50077).
- [Hunter's Mark - A Marksman Mod](https://www.nexusmods.com/morrowind/mods/46656).
- [Mage Robes](https://www.nexusmods.com/morrowind/mods/45739).
- [Moonlight on the Odai River](https://www.nexusmods.com/morrowind/mods/46822).
- [More Useful Spears](https://www.nexusmods.com/morrowind/mods/42450).
- [Morrowind Public Library](https://www.nexusmods.com/morrowind/mods/17379) (the Tea's [potions]).
- [Necessities of Morrowind](https://mw.modhistory.com/download-p1-iAll-37) (Potions).
- [OAAB Grazelands](https://www.nexusmods.com/morrowind/mods/49075).
- [OAAB Tel Mora](https://www.nexusmods.com/morrowind/mods/46177).
- [Of justice and innocence](https://www.nexusmods.com/morrowind/mods/34046).
- [White Wolf Of The Lokken Mountain](https://www.nexusmods.com/morrowind/mods/27306).
- And any other mod I use...

## Opening a Github Request/Issue

Since I do not use a lot of "New Items" mods, there is a lot that is not covered by Better Sorting Names, so I setup a Github where you can open issues to ask that other mod items be included.

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

