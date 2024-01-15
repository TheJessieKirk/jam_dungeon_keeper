# JAM: Dungeon Keeper
*JAM: Dungeon Keeper* is an unofficial modification of the game *[Dungeon Keeper (1997)](https://en.wikipedia.org/wiki/Dungeon_Keeper)*.

## Legal
© 2024 Jessie Kirk.

__*Dungeon Keeper* is a Trademark ™, Registered Trademark ®, and/or Copyright © 1997–1999, 2011–2012. 2016 Bullfrog Productions Ltd. and/or [Electronic Arts Inc.](https://www.ea.com/)__

## License
*JAM: Dungeon Keeper* is free software: you can redistribute it and/or modify it under the terms of the GNU Lesser General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

__*JAM: Dungeon Keeper* is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Lesser General Public License for more details.__

You should have received a copy of the GNU Lesser General Public License along with *JAM: Dungeon Keeper*. If not, see [<https://www.gnu.org/licenses/>](https://www.gnu.org/licenses/).

## Changes

### Creatures
* *Beetles* are now attracted by *Lairs* as their primary room, rather than as their secondary room. This makes them more likely to appear when the Keeper can attract more creatures.
* *Bile Demons* are now attracted by *Lairs* as their primary room and *Hatcheries* as their secondary room, rather than the other way around<sup>[1]</sup>.
* *Dark Mistresses* will not train in a *Training Room* as their primary job<sup>[2]</sup> (but will still train if dropped into one).
* *Demon Spawn*:
  * are now attracted by *Training Rooms* as their primary room, rather than as their secondary room. This makes them more likely to appear when the Keeper can attract more creatures;
  * will grow into lv 2. *Dragons*, rather than lv. 5<sup>[3]</sup>.
* *Flies* are now attracted by *Dungeon Hearts* as their primary room, rather than not being attracted by anything. This makes them more likely to appear when the Keeper can attract more creatures.
* *Ghosts* will now research in a *Library* as their primary job, and worship in the *Temple* as their secondary job, rather than the other way around<sup>[4]</sup>.
* *Hellhounds* will now guard at a *Guard Post* as their secondary job<sup>[5]</sup>.
* *Horned Reapers*:
  * are no longer attracted by *Temples*, and cannot be attracted at all.<sup>[6]</sup>. *Note: I actually set them to be attracted by 30 tiles of Dungeon Heart, which isn't possible.*
  * will fight *Lords of the Land* if one enters their *Lair*<sup>[7]</sup>.
* *Imps* now learn *Conceal Creature* at lv. 6<sup>[8]</sup>.
* *Skeletons* are now attracted by *Prisons* as their primary room and *Training Rooms* as their secondary room, rather than *Prisons* as their secondary room and *Training Room* as their tertiary room. This makes them more likely to appear when the Keeper can attract more creatures.
* *Spiders* are now attracted by *Lairs* as their primary room and *Hatcheries* as their secondary room, rather than *Hatcheries* as their secondary room and *Lairs* as their tertiary room. This makes them more likely to appear when the Keeper can attract more creatures.
* *Tentacles* are now attracted by *Lairs* as their primary room and *Temples* as their secondary room, rather than *Temples* as their secondary room and *Lairs* as their tertiary room. This makes them more likely to appear when the Keeper can attract more creatures.
* *Vampires*:
    * are now attracted by *Lairs* as their primary room and *Graveyards* as their secondary room, rather than the other way around<sup>[9]</sup>;
    * are now attracted by *Lairs* of a minimum size of 9 tiles, rather than 30 tiles;<sup>[9]</sup>;
    * will now research in the *Library* as their primary job, and scavenge in the scavenge in the *Scavenger Room* as their secondary job, rather than the other way around<sup>[9]</sup>.

### Heroes
* *Lords of the Land* will fight *Horned Reapers* if one enters their *Lair*<sup>[6]</sup>.
* *Tunnelers*:
  * now have *Hand to Hand (Swing Weapon)* instead of *Hand to Hand (Unarmed)*, because they are armed with axes.   
  * now have *Dig*. This can only be used by a Keeper that possesses them. It was strange that Tunnelers forgot how to dig once converted by a Keeper.
* *Witches* will fight *Vampires* if one enters their *Lair*<sup>[9]</sup>.
* *Wizards* will fight other *Wizards* if one enters their *Lair*<sup>[10]</sup>.

## Known Issues and Limitations

### Creatures
* *Bile Demons* can't be made to “fall asleep until food arrives” when they become angry<sup>[1]</sup>.
* *Dark Mistresses* can't be made to “watch a torture if one is in progress”; instead they go and get tortured themselves<sup>[2]</sup>.
* *Imps* *can* be given *Fly*, but this causes them to have severe path-finding problems and stops them using *Speed Monster*<sup>[8]</sup>.
* *Spiders* can't be made to fight Flies “when provoked”<sup>[12]</sup>.
* *Tentacles* can't be attracted by, or lurk in, water<sup>[13]</sup>.
* *Vampires* can't be made to “increase the number of creatures who enter your Dungeon”<sup>[9]</sup>.
* *Warlocks* can't be made to “lead a rebellion”<sup>[14]</sup>.

### Heroes
* *Barbarians* can't be made to “fight to the death”<sup>[15]</sup>, but can instead be captured and converted.
* *Dwarfs* do not *necessarily* “make a point of stealing any gold [they find] laying about”<sup>[16]</sup>; rather, some Heroes that spawn in a party can be given the task of stealing gold from their target Keeper's *Treasure Room*.
* *Thieves* do not *necessarily* “hunt out and steal gold”<sup>[17]</sup>; rather, some Heroes that spawn in a party can be given the task of stealing gold from their target Keeper's *Treasure Room*.
* *Tunnelers* *can* be given *Dig*, but cannot be given the same AI as *Imps*, as it causes them to have severe path-finding problems.
 
## Sources and Rationale
1. *Dungeon Keeper Manual*. Bullfrog, Guildford, UK, 1997, §24.3 Bile Demon.
2. *Dungeon Keeper Manual*. Bullfrog, Guildford, UK, 1997, §24.4 Dark Mistress.
3. *Dungeon Keeper Manual*. Bullfrog, Guildford, UK, 1997, §24.5 Demon Spawn.
4. *Dungeon Keeper Manual*. Bullfrog, Guildford, UK, 1997, §24.8 Ghost.
5. *Dungeon Keeper Manual*. Bullfrog, Guildford, UK, 1997, §24.11 Horned Reaper.
6. *Dungeon Keeper Manual*. Bullfrog, Guildford, UK, 1997, §24.10 Hellhound.
7. *Dungeon Keeper Manual*. Bullfrog, Guildford, UK, 1997, §29.12 Lord of the Land.<br>*Making the Horned Reaper and Lord of the Land attack each other in a Lair encounter is the closest I can get to “He is the sworn enemy of the Horned Reaper and they both immediately fight to the death if they encounter one another…”.*
8. *Dungeon Keeper Manual*. Bullfrog, Guildford, UK, 1997, §24.1 Imp.
9. *Dungeon Keeper Manual*. Bullfrog, Guildford, UK, 1997, §24.16 Vampire.
10. *Dungeon Keeper Manual*. Bullfrog, Guildford, UK, 1997, §29.12 Witch.<br>*Making the Witch attack Vampires in a Lair encounter is the closest I can get to “…has a near phobic aversion to Vampires.”.*
11. *Dungeon Keeper Manual*. Bullfrog, Guildford, UK, 1997, §29.6 Wizard.<br>*Making the Wizard attack other Wizards in a Lair encounter is the closest I can get to “Wizards are very vain and hate other Wizards.”.*
12. *Dungeon Keeper Manual*. Bullfrog, Guildford, UK, 1997, §24.14 Spider.
13. *Dungeon Keeper Manual*. Bullfrog, Guildford, UK, 1997, §24.15 Tentacle.
14. *Dungeon Keeper Manual*. Bullfrog, Guildford, UK, 1997, §24.17 Warlock.
15. *Dungeon Keeper Manual*. Bullfrog, Guildford, UK, 1997, §29.5 Barbarian.
16. *Dungeon Keeper Manual*. Bullfrog, Guildford, UK, 1997, §29.4 Dwarf.
17. *Dungeon Keeper Manual*. Bullfrog, Guildford, UK, 1997, §29.2 Thief.
 
## Credits
* Created using:
  * ENSLAVE Creature Editor by Brandon Sim;
  * [DOSBox](https://www.dosbox.com/) by the DOSBox team;
  * [Kate](https://kate-editor.org/) by [KDE e.V.](https://kde.org/).
