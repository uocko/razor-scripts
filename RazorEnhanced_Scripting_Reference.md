# RazorEnhanced UOS Scripting Reference
> Source: https://razorenhanced.net/dokuwiki/ (fetched 2026-03-27)

## Table of Contents
- [Player Data and Functions](#player-data-and-functions)
- [Cast Functions](#cast-functions)
- [CUO Specific Functions](#cuo-specific-functions)
- [Mobile Type Structure](#mobile-type-structure)
- [Mobiles Data and Functions](#mobiles-data-and-functions)
- [Item Type Structure](#item-type-structure)
- [Item Functions](#item-functions)
- [Misc Functions](#misc-functions)
- [Gump Functions](#gump-functions)
- [Journal Functions](#journal-functions)
- [Statics Functions](#statics-functions)
- [Target Functions](#target-functions)
- [Timer Functions](#timer-functions)
- [Razor (markdwags) Scripting Commands](#razor-markdwags-scripting-commands)



---

# Player Data and Functions

player_data_and_function


- 

- 

- 

- 

- 

- 

- 

- 

- 

- 


### Table of Contents


- 
Scripting - Player data and function


- 
Stats


- 
Resistances


- 
Buff


- 
General


- 
Followers


- 
Weight


- 
Positioning


- 
Layers


- 
Skills


- 
Stats


- 
Chat


- 
Attack


- 
Party


- 
Virtue


- 
Move


- 
Attributes


- 
Properties


- 
Paperdoll Button


- 
Weapon Special Ability


- 
Gargoyle Flying


- 
Active Spells


- 
Toggle Always Run


- 
Corpse Tracking


# Scripting - Player data and function


Here can find some information about Enhanced Scripting function about player self data and related function


## Stats


 |  Player Hits


 | Syntax
 |  Player.Hits


 | Description:


 | Retrieves an integer value from self character hits.


 | Returns
 | Integer


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player HitsMax


 | Syntax
 |  Player.HitsMax


 | Description:


 | Retrieves an integer value from self character max hits.


 | Returns
 | Integer


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Strength


 | Syntax
 |  Player.Str


 | Description:


 | Retrieves an integer value from self character strength.


 | Returns
 | Integer


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Mana


 | Syntax
 |  Player.Mana


 | Description:


 | Retrieves an integer value from self character mana.


 | Returns
 | Integer


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player MaxMana


 | Syntax
 |  Player.ManaMax


 | Description:


 | Retrieves an integer value from self character max mana.


 | Returns
 | Integer


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Intelligence


 | Syntax
 |  Player.Int


 | Description:


 | Retrieves an integer value from self character intelligence.


 | Returns
 | Integer


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Stamina


 | Syntax
 |  Player.Stam


 | Description:


 | Retrieves an integer value from self character stamina.


 | Returns
 | Integer


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Max Stamina


 | Syntax
 |  Player.StamMax


 | Description:


 | Retrieves an integer value from self character max stamina.


 | Returns
 | Integer


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Dexterity


 | Syntax
 |  Player.Dex


 | Description:


 | Retrieves an integer value from self character dexterity.


 | Returns
 | Integer


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player StatCap


 | Syntax
 |  Player.StatCap


 | Description:


 | Retrieves an integer value from self character StatCap.


 | Returns
 | Integer


 | In Object:
 | Player


 | Parameters:
 | none


## Resistances


 |  Player Armor


 | Syntax
 |  Player.AR


 | Description:


 | Retrieves an integer value from self character armor.


 | Returns
 | Integer


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Fire Resistance


 | Syntax
 |  Player.FireResistance


 | Description:


 | Retrieves an integer value from self character fire resistance.


 | Returns
 | Integer


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Cold Resistance


 | Syntax
 |  Player.ColdResistance


 | Description:


 | Retrieves an integer value from self character cold resistance.


 | Returns
 | Integer


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Enery Resistance


 | Syntax
 |  Player.EnergyResistance


 | Description:


 | Retrieves an integer value from self character energy resistance.


 | Returns
 | Integer


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Poison Resistance


 | Syntax
 |  Player.PoisonResistance


 | Description:


 | Retrieves an integer value from self character poison resistance.


 | Returns
 | Integer


 | In Object:
 | Player


 | Parameters:
 | none


## Buff


 |  Player Buffs


 | Syntax
 |  Player Buffs


 | Description:


 | Get a string list with name of current buffs active on player.


 | Returns
 | string[]


 | In Object:
 | Player


 | Parameters:
 | none


 | Result list:
 | 


- 
 Meditation


- 
 Agility


- 
 Animal Form


- 
 Arcane Enpowerment


- 
 Arcane Enpowerment (new)


- 
 Arch Protection


- 
 Armor Pierce


- 
 Attunement


- 
 Aura of Nausea


- 
 Bleed


- 
 Bless


- 
 Block


- 
 Bload Oath (caster)


- 
 Bload Oath (curse)


- 
 BloodWorm Anemia


- 
 City Trade Deal


- 
 Clumsy


- 
 Confidence


- 
 Corpse Skin


- 
 Counter Attack


- 
 Criminal


- 
 Cunning


- 
 Curse


- 
 Curse Weapon


- 
 Death Strike


- 
 Defense Mastery


- 
 Despair


- 
 Despair (target)


- 
 Disarm (new)


- 
 Disguised


- 
 Dismount Prevention


- 
 Divine Fury


- 
 Dragon Slasher Fear


- 
 Enchant


- 
 Enemy Of One


- 
 Enemy Of One (Debuf)


- 
 Essence Of Wind


- 
 Ethereal Voyage


- 
 Evasion


- 
 Evil Omen


- 
 Faction Loss


- 
 Fan Dancer Fan Fire


- 
 Feeble Mind


- 
 Feint


- 
 Force Arrow


- 
 Berserk


- 
 Fly


- 
 Gaze Despair


- 
 Gift Of Life


- 
 Gift Of Renewal


- 
 Healing


- 
 Heat Of Battle


- 
 Hiding


- 
 Hiryu Physical Malus


- 
 Hit Dual Wield


- 
 Hit Lower Attack


- 
 Hit Lower Defense


- 
 Honorable Execution


- 
 Honored


- 
 Horrific Beast


- 
 Hawl Of Cacophony


- 
 Immolating Weapon


- 
 Incognito


- 
 Inspire


- 
 Invigorate


- 
 Invisibility


- 
 Lich Form


- 
 Lighting Strike


- 
 Magic Fish


- 
 Magic Reflection


- 
 Mana Phase


- 
 Mass Curse


- 
 Medusa Stone


- 
 Mind Rot


- 
 Momentum Strike


- 
 Mortal Strike


- 
 Night Sight


- 
 NoRearm


- 
 Orange Petals


- 
 Pain Spike


- 
 Paralyze


- 
 Perfection


- 
 Perseverance


- 
 Poison


- 
 Poison Resistance


- 
 Polymorph


- 
 Protection


- 
 Psychic Attack


- 
 Consecrate Weapon


- 
 Rage


- 
 Rage Focusing


- 
 Rage Focusing (target)


- 
 Reactive Armor


- 
 Reaper Form


- 
 Resilience


- 
 Rose Of Trinsic


- 
 Rotworm Blood Disease


- 
 Rune Beetle Corruption


- 
 Skill Use Delay


- 
 Sleep


- 
 Spell Focusing


- 
 Spell Focusing (target)


- 
 Spell Plague


- 
 Splintering Effect


- 
 Stone Form


- 
 Strangle


- 
 Strength


- 
 Surge


- 
 Swing Speed


- 
 Talon Strike


- 
 Vampiric Embrace


- 
 Weaken


- 
 Wraith Form


 |  Player Buffs Exist


 | Syntax
 |  Player.BuffsExist(string)


 | Description:


 |  Return a bool value if specific buff exist or not.


 | Returns
 | bool


 | In Object:
 | Player


 | Parameters:
 | none


 | Parameter list:
 | 


- 
 Meditation


- 
 Agility


- 
 Animal Form


- 
 Arcane Enpowerment


- 
 Arcane Enpowerment (new)


- 
 Arch Protection


- 
 Armor Pierce


- 
 Attunement


- 
 Aura of Nausea


- 
 Bleed


- 
 Bless


- 
 Block


- 
 Bloath Oath (caster)


- 
 Bload Oath (curse)


- 
 BloodWorm Anemia


- 
 City Trade Deal


- 
 Clumsy


- 
 Confidence


- 
 Corpse Skin


- 
 Counter Attack


- 
 Criminal


- 
 Cunning


- 
 Curse


- 
 Curse Weapon


- 
 Death Strike


- 
 Defense Mastery


- 
 Despair


- 
 Despair (target)


- 
 Disarm (new)


- 
 Disguised


- 
 Dismount Prevention


- 
 Divine Fury


- 
 Dragon Slasher Fear


- 
 Enchant


- 
 Enemy Of One


- 
 Enemy Of One (new)


- 
 Essence Of Wind


- 
 Ethereal Voyage


- 
 Evasion


- 
 Evil Omen


- 
 Faction Loss


- 
 Fan Dancer Fan Fire


- 
 Feeble Mind


- 
 Feint


- 
 Force Arrow


- 
 Berserk


- 
 Fly


- 
 Gaze Despair


- 
 Gift Of Life


- 
 Gift Of Renewal


- 
 Healing


- 
 Heat Of Battle


- 
 Hiding


- 
 Hiryu Physical Malus


- 
 Hit Dual Wield


- 
 Hit Lower Attack


- 
 Hit Lower Defense


- 
 Honorable Execution


- 
 Honored


- 
 Horrific Beast


- 
 Hawl Of Cacophony


- 
 Immolating Weapon


- 
 Incognito


- 
 Inspire


- 
 Invigorate


- 
 Invisibility


- 
 Lich Form


- 
 Lighting Strike


- 
 Magic Fish


- 
 Magic Reflection


- 
 Mana Phase


- 
 Mass Curse


- 
 Medusa Stone


- 
 Mind Rot


- 
 Momentum Strike


- 
 Mortal Strike


- 
 Night Sight


- 
 NoRearm


- 
 Orange Petals


- 
 Pain Spike


- 
 Paralyze


- 
 Perfection


- 
 Perseverance


- 
 Poison


- 
 Poison Resistance


- 
 Polymorph


- 
 Protection


- 
 Psychic Attack


- 
 Consecrate Weapon


- 
 Rage


- 
 Rage Focusing


- 
 Rage Focusing (target)


- 
 Reactive Armor


- 
 Reaper Form


- 
 Resilience


- 
 Rose Of Trinsic


- 
 Rotworm Blood Disease


- 
 Rune Beetle Corruption


- 
 Skill Use Delay


- 
 Sleep


- 
 Spell Focusing


- 
 Spell Focusing (target)


- 
 Spell Plague


- 
 Splintering Effect


- 
 Stone Form


- 
 Strangle


- 
 Strength


- 
 Surge


- 
 Swing Speed


- 
 Talon Strike


- 
 Vampiric Embrace


- 
 Weaken


- 
 Wraith Form


 |  Player Ghost


 | Syntax
 |  Player.IsGhost


 | Description:


 | Retrieves an bool value from self character ghost status. True character is dead, False character is alive


 | Returns
 | bool


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Poisoned


 | Syntax
 |  Player.Poisoned


 | Description:


 | Retrieves an bool value from self character poison status. True character is poisoned, False character is not poisoned


 | Returns
 | bool


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player YellowHits


 | Syntax
 |  Player.YellowHits


 | Description:


 | Retrieves an bool value from self character YellowHits status.


 | Returns
 | bool


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Hidden


 | Syntax
 |  Player.Visible


 | Description:


 | Retrieves an bool value from self character hidden status. True character is visible, False character is hidded


 | Returns
 | bool


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player War Mode


 | Syntax
 |  Player.WarMode


 | Description:


 | Retrieves an bool value from self character war status. True character is in warmode, False character is in peace


 | Returns
 | bool


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Paralized


 | Syntax
 |  Player.Paralized


 | Description:


 | Retrieves an bool value from self character paral status. True character is in paralized, False character is not paralized


 | Returns
 | bool


 | In Object:
 | Player


 | Parameters:
 | none


## General


 |  Player Sex


 | Syntax
 |  Player.Female


 | Description:


 | Retrieves an bool value from self character sex. True character is woman, False character is male


 | Returns
 | bool


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Name


 | Syntax
 |  Player.Name


 | Description:


 | Retrieves a string with self character name.


 | Returns
 | string


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Backpack


 | Syntax
 |  Player.Backpack


 | Description:


 | Retrieves an item with self character backpack.


 | Returns
 | item


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Backpack Serial


 | Syntax
 |  Player.Backpack.Serial


 | Description:


 | Retrieves a int with self character backpack serial.


 | Returns
 | int


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Backpack Color


 | Syntax
 |  Player.Backpack.Hue


 | Description:


 | Retrieves a int with self character backpack color.


 | Returns
 | int


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Bank


 | Syntax
 |  Player.Bank


 | Description:


 | Retrieves a item with self character bankbox.


 | Returns
 | item


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Quiver


 | Syntax
 |  Player.Quiver


 | Description:


 | Retrieves a item with self character quiver.


 | Returns
 | item


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Quiver Serial


 | Syntax
 |  Player.Quiver.Serial


 | Description:


 | Retrieves a int with self character quiver serial.


 | Returns
 | int


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Quiver Color


 | Syntax
 |  Player.Quiver.Hue


 | Description:


 | Retrieves a int with self character quiver color.


 | Returns
 | int


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Mount


 | Syntax
 |  Player.Mount


 | Description:


 | Retrieves a item with self character mount. You must be mounted for retrieve this information


 | Returns
 | item


 | In Object:
 | Player


 | Parameters:
 | none


 |  Gui Static Mount


 | Syntax
 |  Player.StaticMount


 | Description:


 | Retrieves serial of mount set in Filter/Mount GUI.


 | Returns
 | int


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Mount Serial


 | Syntax
 |  Player.Mount.Serial


 | Description:


 | Retrieves a int with self character mount serial.You must be mounted for retrieve this information


 | Returns
 | int


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Mount Color


 | Syntax
 |  Player.Mount.Hue


 | Description:


 | Retrieves a int with self character mount color. You must be mounted for retrieve this information


 | Returns
 | int


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Mount Name


 | Syntax
 |  Player.Mount.Name


 | Description:


 | Retrieves a string with self character mount name. You must be mounted for retrieve this information


 | Returns
 | string


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Gold in Backpack


 | Syntax
 |  Player.Gold


 | Description:


 | Retrieves a int with self character gold amount in backpack.


 | Returns
 | int


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Luck


 | Syntax
 |  Player.Luck


 | Description:


 | Retrieves a int with self character luck value.


 | Returns
 | int


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Body Graphycs


 | Syntax
 |  Player.Body


 | Description:


 | Retrieves a int with self character body graphics value.


 | Returns
 | int


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Serial


 | Syntax
 |  Player.Serial


 | Description:


 | Retrieves a int with self character serial.


 | Returns
 | int


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Head Message


 | Syntax
 |  Player.HeadMessage(int, string)


 | Description:


 | Display a message over self character with color.


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Notoriety


 | Syntax
 |  Player.Notoriety


 | Description:


 | Read byte of Notoriety color.


 | Returns
 | byte


 | In Object:
 | Player


 | Parameters:
 | none


## Followers


 |  Player Current Followers


 | Syntax
 |  Player.Followers( )


 | Description:


 | Retrieves an int value from self character current followers.


 | Returns
 | int


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Max Followers


 | Syntax
 |  Player.FollowersMax( )


 | Description:


 | Retrieves an int value from self character max followers allowed.


 | Returns
 | int


 | In Object:
 | Player


 | Parameters:
 | none


## Weight


 |  Player Current Weight


 | Syntax
 |  Player.Weight


 | Description:


 | Retrieves an int value from self character current weight.


 | Returns
 | int


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Max Weight


 | Syntax
 |  Player.MaxWeight


 | Description:


 | Retrieves an int value from self character max weight can carry.


 | Returns
 | int


 | In Object:
 | Player


 | Parameters:
 | none


## Positioning


 |  Player Position


 | Syntax
 |  Player.Position


 | Description:


 | Retrieves an Point3D value from self character current position.


 | Returns
 | point3d


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Position X Coord


 | Syntax
 |  Player.Position.X


 | Description:


 | Retrieves an int value from self character position X coord.


 | Returns
 | int


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Position Y Coord


 | Syntax
 |  Player.Position.Y


 | Description:


 | Retrieves an int value from self character position Y coord.


 | Returns
 | int


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Position Z Level


 | Syntax
 |  Player.Position.Z


 | Description:


 | Retrieves an int value from self character position Z level.


 | Returns
 | int


 | In Object:
 | Player


 | Parameters:
 | none


 |  Check Mobile Range


 | Syntax
 |  Player.InRangeMobile(Mobile or Int, int)


 | Description:


 | Retrieves a bool value if specific mobile is in specific range.


 | Returns
 | bool


 | In Object:
 | Player


 | Parameters:
 | none


 |  Check Item Range


 | Syntax
 |  Player.InRangeItem(Item or Int, int)


 | Description:


 | Retrieves a bool value if specific item is in specific range.


 | Returns
 | bool


 | In Object:
 | Player


 | Parameters:
 | none


 |  Get Player Direction


 | Syntax
 |  Player.Direction


 | Description:


 | Contain player direction in string: North, South, West, East, Right, Left, Up, Down.


 | Returns
 | string


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Map


 | Syntax
 |  Player.Map


 | Description:


 | Retrieves current player map number.


 | Returns
 | int


 | In Object:
 | Player


 | Parameters:
 | none


## Layers


 |  Player Get Item on Layer


 | Syntax
 |  Player.GetItemOnLayer(string)


 | Description:


 | Retrieves a item value of item equipped on specific layer.


 | Returns
 | item


 | In Object:
 | Player


 | Parameters:
 | String Layername


 | Parameters list:
 | 


- 
 RightHand


- 
 LeftHand


- 
 Shoes


- 
 Pants


- 
 Shirt


- 
 Head


- 
 Gloves


- 
 Ring


- 
 Neck


- 
 Waist


- 
 InnerTorso


- 
 Bracelet


- 
 MiddleTorso


- 
 Earrings


- 
 Arms


- 
 Cloak


- 
 OuterTorso


- 
 OuterLegs


- 
 InnerLegs


- 
 Talisman


 |  Player UnEquip Item on Layer


 | Syntax
 |  Player.UnEquipItemByLayer(string)


 | Description:


 | Unequip item equipped on specific layer.


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | String Layername


 | Parameters list:
 | 


- 
 RightHand


- 
 LeftHand


- 
 Shoes


- 
 Pants


- 
 Shirt


- 
 Head


- 
 Gloves


- 
 Ring


- 
 Neck


- 
 Hair


- 
 Waist


- 
 InnerTorso


- 
 Bracelet


- 
 FacialHair


- 
 MiddleTorso


- 
 Earrings


- 
 Arms


- 
 Cloak


- 
 OuterTorso


- 
 OuterLegs


- 
 InnerLegs


- 
 Talisman


 |  Player Equip Item on Layer


 | Syntax
 |  Player.EquipItem(Int or Item)


 | Description:


 | Equip item on specific layer. Can use item or serial for parameters.


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | Int item serial, Item reference


 |  Player Check Layer


 | Syntax
 |  Player.CheckLayer(String)


 | Description:


 | Get a bool value if layer is busy whit item or not. True: Layer busy, False: Layer free


 | Returns
 | bool


 | In Object:
 | Player


 | Parameters:
 | String Layername


 | Parameters list:
 | 


- 
 RightHand


- 
 LeftHand


- 
 Shoes


- 
 Pants


- 
 Shirt


- 
 Head


- 
 Gloves


- 
 Ring


- 
 Neck


- 
 Hair


- 
 Waist


- 
 InnerTorso


- 
 Bracelet


- 
 FacialHair


- 
 MiddleTorso


- 
 Earrings


- 
 Arms


- 
 Cloak


- 
 OuterTorso


- 
 OuterLegs


- 
 InnerLegs


- 
 Talisman


 |  Player Get Assistant Layer


 | Syntax
 |  Player.GetAssistantLayer(string)


 | Description:


 | Get the Layer&#039;s name in Hex.


 | Returns
 | layer


 | In Object:
 | Player


 | Parameters:
 | string Layer&#039;s name


 |  Player Equip UO3D


 | Syntax
 |  Player.EquipUO3D(List(Int))


 | Description:


 | Equip a list of item by using UO3D packet.


 | Returns
 | layer


 | In Object:
 | Player


 | Parameters:
 | List(Int) Serialtoequip


## Skills


 |  Player Get Skill Value


 | Syntax
 |  Player.GetSkillValue(String)


 | Description:


 | Get value of specific skill.


 | Returns
 | double


 | In Object:
 | Player


 | Parameters:
 | String Skillname


 | Parameters list:
 | 


- 
 Alchemy


- 
 Anatomy


- 
 Animal Lore


- 
 Item ID


- 
 Arms Lore


- 
 Parry


- 
 Begging


- 
 Blacksmith


- 
 Fletching


- 
 Peacemaking


- 
 Camping


- 
 Carpentry


- 
 Cartography


- 
 Cooking


- 
 Detect Hidden


- 
 Discordance


- 
 EvalInt


- 
 Healing


- 
 Fishing


- 
 Forensics


- 
 Herding


- 
 Hiding


- 
 Provocation


- 
 Inscribe


- 
 Lockpicking


- 
 Magery


- 
 Magic Resist


- 
 Mysticism


- 
 Tactics


- 
 Snooping


- 
 Musicianship


- 
 Poisoning


- 
 Archery


- 
 Spirit Speak


- 
 Stealing


- 
 Tailoring


- 
 Animal Taming


- 
 Taste ID


- 
 Tinkering


- 
 Tracking


- 
 Veterinary


- 
 Swords


- 
 Macing


- 
 Fencing


- 
 Wrestling


- 
 Lumberjacking


- 
 Mining


- 
 Meditation


- 
 Stealth


- 
 Remove Trap


- 
 Necromancy


- 
 Focus


- 
 Chivalry


- 
 Bushido


- 
 Ninjitsu


- 
 Spell Weaving


- 
 Imbuing


 |  Player Get Real Skill Value


 | Syntax
 |  Player.GetRealSkillValue(String)


 | Description:


 | Get real value of specific skill.


 | Returns
 | double


 | In Object:
 | Player


 | Parameters:
 | String Skillname


 | Parameters list:
 | 
%SEVEN


- 
 Alchemy


- 
 Anatomy


- 
 Animal Lore


- 
 Item ID


- 
 Arms Lore


- 
 Parry


- 
 Begging


- 
 Blacksmith


- 
 Fletching


- 
 Peacemaking


- 
 Camping


- 
 Carpentry


- 
 Cartography


- 
 Cooking


- 
 Detect Hidden


- 
 Discordance


- 
 EvalInt


- 
 Healing


- 
 Fishing


- 
 Forensics


- 
 Herding


- 
 Hiding


- 
 Provocation


- 
 Inscribe


- 
 Lockpicking


- 
 Magery


- 
 Magic Resist


- 
 Mysticism


- 
 Tactics


- 
 Snooping


- 
 Musicianship


- 
 Poisoning


- 
 Archery


- 
 Spirit Speak


- 
 Stealing


- 
 Tailoring


- 
 Animal Taming


- 
 Taste ID


- 
 Tinkering


- 
 Tracking


- 
 Veterinary


- 
 Swords


- 
 Macing


- 
 Fencing


- 
 Wrestling


- 
 Lumberjacking


- 
 Mining


- 
 Meditation


- 
 Stealth


- 
 Remove Trap


- 
 Necromancy


- 
 Focus


- 
 Chivalry


- 
 Bushido


- 
 Ninjitsu


- 
 Spell Weaving


- 
 Imbuing


- 


 |  Player Get SkillCap Value


 | Syntax
 |  Player.GetSkillCap(String)


 | Description:


 | Get value of specific skillcap.


 | Returns
 | double


 | In Object:
 | Player


 | Parameters:
 | String Skillname


 | Parameters list:
 | 


- 
 Alchemy


- 
 Anatomy


- 
 Animal Lore


- 
 Item ID


- 
 Arms Lore


- 
 Parry


- 
 Begging


- 
 Blacksmith


- 
 Fletching


- 
 Peacemaking


- 
 Camping


- 
 Carpentry


- 
 Cartography


- 
 Cooking


- 
 Detect Hidden


- 
 Discordance


- 
 EvalInt


- 
 Healing


- 
 Fishing


- 
 Forensics


- 
 Herding


- 
 Hiding


- 
 Provocation


- 
 Inscribe


- 
 Lockpicking


- 
 Magery


- 
 Magic Resist


- 
 Mysticism


- 
 Tactics


- 
 Snooping


- 
 Musicianship


- 
 Poisoning


- 
 Archery


- 
 Spirit Speak


- 
 Stealing


- 
 Tailoring


- 
 Animal Taming


- 
 Taste ID


- 
 Tinkering


- 
 Tracking


- 
 Veterinary


- 
 Swords


- 
 Macing


- 
 Fencing


- 
 Wrestling


- 
 Lumberjacking


- 
 Mining


- 
 Meditation


- 
 Stealth


- 
 Remove Trap


- 
 Necromancy


- 
 Focus


- 
 Chivalry


- 
 Bushido


- 
 Ninjitsu


- 
 Spell Weaving


- 
 Imbuing


- 


 |  Player Get Skill Status (Up/Down/Lock)


 | Syntax
 |  Player.GetSkillStatus(String)


 | Description:


 | Get status lock for a specific skill. UP: 0, DOWN: 1, LOCKED: 2


 | Returns
 | int


 | In Object:
 | Player


 | Parameters:
 | String Skillname


 | Parameters list:
 | 


- 
 Alchemy


- 
 Anatomy


- 
 Animal Lore


- 
 Item ID


- 
 Arms Lore


- 
 Parry


- 
 Begging


- 
 Blacksmith


- 
 Fletching


- 
 Peacemaking


- 
 Camping


- 
 Carpentry


- 
 Cartography


- 
 Cooking


- 
 Detect Hidden


- 
 Discordance


- 
 EvalInt


- 
 Healing


- 
 Fishing


- 
 Forensics


- 
 Herding


- 
 Hiding


- 
 Provocation


- 
 Inscribe


- 
 Lockpicking


- 
 Magery


- 
 Magic Resist


- 
 Mysticism


- 
 Tactics


- 
 Snooping


- 
 Musicianship


- 
 Poisoning


- 
 Archery


- 
 Spirit Speak


- 
 Stealing


- 
 Tailoring


- 
 Animal Taming


- 
 Taste ID


- 
 Tinkering


- 
 Tracking


- 
 Veterinary


- 
 Swords


- 
 Macing


- 
 Fencing


- 
 Wrestling


- 
 Lumberjacking


- 
 Mining


- 
 Meditation


- 
 Stealth


- 
 Remove Trap


- 
 Necromancy


- 
 Focus


- 
 Chivalry


- 
 Bushido


- 
 Ninjitsu


- 
 Spell Weaving


- 
 Imbuing


- 


 |  Player Set Skill Status (Up/Down/Lock)


 | Syntax
 |  Player.SetSkillStatus(String, int)


 | Description:


 | Set status for a specific skill. UP: 0, DOWN: 1, LOCKED: 2


 | Returns
 | int


 | In Object:
 | Player


 | Parameters:
 | String Skillname, int status


 | Parameters list:
 | 


- 
 Alchemy


- 
 Anatomy


- 
 Animal Lore


- 
 Item ID


- 
 Arms Lore


- 
 Parry


- 
 Begging


- 
 Blacksmith


- 
 Fletching


- 
 Peacemaking


- 
 Camping


- 
 Carpentry


- 
 Cartography


- 
 Cooking


- 
 Detect Hidden


- 
 Discordance


- 
 EvalInt


- 
 Healing


- 
 Fishing


- 
 Forensics


- 
 Herding


- 
 Hiding


- 
 Provocation


- 
 Inscribe


- 
 Lockpicking


- 
 Magery


- 
 Magic Resist


- 
 Mysticism


- 
 Tactics


- 
 Snooping


- 
 Musicianship


- 
 Poisoning


- 
 Archery


- 
 Spirit Speak


- 
 Stealing


- 
 Tailoring


- 
 Animal Taming


- 
 Taste ID


- 
 Tinkering


- 
 Tracking


- 
 Veterinary


- 
 Swords


- 
 Macing


- 
 Fencing


- 
 Wrestling


- 
 Lumberjacking


- 
 Mining


- 
 Meditation


- 
 Stealth


- 
 Remove Trap


- 
 Necromancy


- 
 Focus


- 
 Chivalry


- 
 Bushido


- 
 Ninjitsu


- 
 Spell Weaving


- 
 Imbuing


- 


 |  Player Use Skill


 | Syntax
 |  Player.UseSkill(String [, Target])


 | Description:


 | Use a specific skill, and optionally apply that skill to the target specified.


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | String Skillname, optional Mobile/Item


 | Parameters list:
 | 


- 
 Animal Lore


- 
 Item ID


- 
 Arms Lore


- 
 Begging


- 
 Peacemaking


- 
 Cartography


- 
 Detect Hidden


- 
 Discordance


- 
 Eval Int


- 
 Forensics


- 
 Hiding


- 
 Provocation


- 
 Poisoning


- 
 Spirit Speak


- 
 Stealing


- 
 Animal Taming


- 
 Taste ID


- 
 Tracking


- 
 Meditation


- 
 Stealth


- 
 Remove Trap


- 
 Inscribe


- 
 Anatomy


- 
 Imbuing


## Stats


 |  Player Set Stat Status (Up/Down/Lock)


 | Syntax
 |  Player.SetStatStatus(String, int)


 | Description:


 | Set status for a specific skill. UP: 0, DOWN: 1, LOCKED: 2


 | Returns
 | int


 | In Object:
 | Player


 | Parameters:
 | String Skillname, int status


 | Parameters list:
 | 


- 
 Strength


- 
 Dexterity  


- 
 Intelligence


## Chat


 |  Player Chat Say


 | Syntax
 |  Player.ChatSay(int, string or int)


 | Description:


 | Send a message in say whit specific color and message.


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | Int Color, String Message or int number


 |  Player Chat Emote


 | Syntax
 |  Player.ChatEmote(int, string or int)


 | Description:


 | Send a emote message whit specific color and message.


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | Int Color, String Message or int number


 |  Player Chat Whisper


 | Syntax
 |  Player.ChatWhisper(int, string or int)


 | Description:


 | Send a message in whisper whit specific color and message.


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | Int Color, String Message or int number


 |  Player Chat Yell


 | Syntax
 |  Player.ChatYell(int, string or int)


 | Description:


 | Send a message in yell whit specific color and message.


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | Int Color, String Message or int number


 |  Player Chat Guild


 | Syntax
 |  Player.ChatGuild(string or int)


 | Description:


 | Send a message in guild chat.


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | String Message or int number


 |  Player Chat Alliance


 | Syntax
 |  Player.ChatAlliance(string or int)


 | Description:


 | Send a message in alliance chat.


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | String Message or int number


 |  Player Chat Channel


 | Syntax
 |  Player.ChatChannel(string or int)


 | Description:


 | Send a message in chat channel.


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | String Message or int number


 |  Player EmoteAction


 | Syntax
 |  Player.EmoteAction(string)


 | Description:


 | Tell server to perform an emote action


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 |  “salute”)


## Attack


 |  Player Set Warmode


 | Syntax
 |  Player.SetWarMode(bool)


 | Description:


 | Set character warmode status. True: Set warmode ON, False: Set warmode OFF


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | bool warstatus


 |  Player Attack


 | Syntax
 |  Player.Attack(int or mobile)


 | Description:


 | Force character to attack specific serial or mobile


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | int targetserial or mobile targetmobile


 |  Player Attack Last


 | Syntax
 |  Player.AttackLast()


 | Description:


 | Force character to attack last attack


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | none


## Party


 |  Player Party Check


 | Syntax
 |  Player.InParty()


 | Description:


 | Check if character is in party. True: Is in party, False: Is not party


 | Returns
 | bool


 | In Object:
 | Player


 | Parameters:
 | void


 |  Player Party Send Message


 | Syntax
 |  Player.ChatParty(string, optional int)


 | Description:


 | Send a message to party chat, if specific a serial send private message.


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | string Message, optional int SerialtoPrivate


 |  Player Party Set Loot


 | Syntax
 |  Player.PartyCanLoot(bool)


 | Description:


 | Set player party canloot flags. True: Member can loot me, False: Member can&#039;t me


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | bool


 |  Player Party Invite


 | Syntax
 |  Player.PartyInvite( )


 | Description:


 | Open a target prompt for invite new member


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Party Leave


 | Syntax
 |  Player.PartyLeave( )


 | Description:


 | Leave from party.


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | none


 |  Player Party Kick Member


 | Syntax
 |  Player.KickMember(int)


 | Description:


 | Kick a member from party by serial. Only for party leader


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | int SerialPersontokick


## Virtue


 |  Player Invoke Virtue


 | Syntax
 |  Player.InvokeVirtue(string)


 | Description:


 | Invoke a character virtue by specific name.


 | Returns
 | none


 | In Object:
 | Player


 | Parameters:
 | String Virtuename


 | Parameters list:
 | 


- 
 Honor


- 
 Sacrifice


- 
 Valor


- 
 Compassion


- 
 Honesty


- 
 Humility


- 
 Justice


## Move


 |  Player Walk


 | Syntax
 |  Player.Walk(string)


 | Description:


 | Move char in specific direction. Return true for success move, false if fail.


 | Returns
 | bool


 | In Object:
 | Player


 | Parameters:
 | String Direction


 | Parameters list:
 | 


- 
 North


- 
 South


- 
 East


- 
 West


- 
 Up


- 
 Down


- 
 Left


- 
 Right


 |  Player Run


 | Syntax
 |  Player.Run(string)


 | Description:


 | Move (run speed) char in specific direction. Return true for success move, false if fail.


 | Returns
 | bool


 | In Object:
 | Player


 | Parameters:
 | String Direction


 | Parameters list:
 | 


- 
 North


- 
 South


- 
 East


- 
 West


- 
 Up


- 
 Down


- 
 Left


- 
 Right


 |  Player Pathfind


 | Syntax
 |  Player.PathFindTo(int x, int y, int z)


 | Description:


 | Force a client pathfind to specific location XYZ coords.


 | Returns
 | none


 | In Object:
 | Player


 | Parameters:
 | int X Y Z


## Attributes


 |  Sum Attributes


 | Syntax
 |  Player.SumAttribute(string)


 | Description:


 | Note: <SLOW> Scan all the players layers and sum the values of the requested attribute


 | Returns
 | float


 | In Object:
 | Player


 | Parameters:
 | String AttributeName


 | Example
 | 


lrc = Player.SumAttribute("Lower Reagent Cost")
Misc.SendMessage("Current Lower Reagent Cost is {}".format(lrc))


## Properties


 |  Get Proprerties


 | Syntax
 |  Player.GetPropValue(string)


 | Description:


 | Get value self (player) propriety


 | Returns
 | integer


 | In Object:
 | Player


 | Parameters:
 | String PropName


 |  Get Proprerties String


 | Syntax
 |  Player.GetPropStringByIndex(int)


 | Description:


 | Get string name of prop by index, if no prop in selected index return empty.


 | Returns
 | string


 | In Object:
 | Player


 | Parameters:
 | Int PropIndex


 |  Get Proprerties String List


 | Syntax
 |  Items.GetPropStringList()


 | Description:


 | Get string list of all props name, if no props list is empty.


 | Returns
 | list (String)


 | In Object:
 | Player


 | Parameters:
 | none


## Paperdoll Button


 |  Open PaperDoll


 | Syntax
 |  Player.OpenPaperDoll( int )


 | Description:


 | Open the paperdoll.


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | serial of mobile to open paper doll, if not specified opens the players own paperdoll


 |  Open quest Menu


 | Syntax
 |  Player.QuestButton( )


 | Description:


 | Open a quest menu linked to paperdool quest button.


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | none


 |  Open guild Menu


 | Syntax
 |  Player.GuildButton( )


 | Description:


 | Open a guild menu linked to paperdool quest button.


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | none


## Weapon Special Ability


 |  Weapon Primary Ability


 | Syntax
 |  Player.WeaponPrimarySA( )


 | Description:


 | Set on Weapon Primary Ability.


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | none


 |  Weapon Secondary Ability


 | Syntax
 |  Player.WeaponSecondarySA( )


 | Description:


 | Set on Weapon Secondary Ability.


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | none


 |  Weapon Clear Ability


 | Syntax
 |  Player.WeaponClearSA( )


 | Description:


 | Clear ability if active.


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | none


 |  On Weapon Stun Ability


 | Syntax
 |  Player.WeaponStunSA( )


 | Description:


 | Set on No Weapon Stun.


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | none


 |  On Weapon Disarm Ability


 | Syntax
 |  Player.WeaponDisarmSA( )


 | Description:


 | Set on No Weapon Disarm.


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | none


 |  Check if have Ability ON


 | Syntax
 |  Player.HasSpecial


 | Description:


 | Check if player have a special abiliti ON.


 | Returns
 | bool


 | In Object:
 | Player


 | Parameters:
 | none


## Gargoyle Flying


 |  Gargoyle Flying


 | Syntax
 |  Player.Fly( bool )


 | Description:


 | Enable or disable Gargoyle Flying.


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | bool EnableFly


## Active Spells


 |  Check Active spells


 | Syntax
 |  Player.SpellIsEnabled( string )


 | Description:


 | Check Active spell whit spell name (for spell have this function).


 | Returns
 | bool


 | In Object:
 | Player


 | Parameters:
 | string SpellName


## Toggle Always Run


 |  Check Active spells


 | Syntax
 |  Player.ToggleAlwaysRun()


 | Description:


 | Uses the EasyUO dll to toggle the AlwaysRun setting.


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | None


 |  Returns a string with the name of the area


 | Syntax
 |  Player.Area()


 | Description:


 | Returns the area defined in Config/regions.json.


 | Returns
 | Name of City/Dungeon or whatever defined in regions.json


 | In Object:
 | Player


 | Parameters:
 | None


 |  Returns a string with the name of the zone


 | Syntax
 |  Player.Zone()


 | Description:


 | Returns the area defined in Config/regions.json.


 | Returns
 | Towns/Dungeons/Forest/Guarded


 | In Object:
 | Player


 | Parameters:
 | None


## Corpse Tracking


 |  Clear Corpse list


 | Syntax
 |  Player.ClearCorpseList()


 | Description:


 | Empties all the tracked corpses from the corpse list.


 | Returns
 | void


 | In Object:
 | Player


 | Parameters:
 | None


 |  Track Corpses


 | Syntax
 |  Player.Corpses()


 | Description:


 | Each time you die, the corpse information is copied here


 | Returns
 | List of corpse items containing serial and position


 | In Object:
 | Player


 | Parameters:
 | None


---

# Cast Functions

cast_function


- 

- 

- 

- 

- 

- 

- 

- 

- 

- 


### Table of Contents


- 
Scripting - Cast function


- 
Magery


- 
Necro


- 
Chivalry


- 
Bushido


- 
Ninjitsu


- 
Spellweaving


- 
Mysticism


- 
Mastery


- 
Druid


- 
Cleric


# Scripting - Cast function


Here can find some information about Enhanced Scripting function about cast spell and ability. Note that the optional targeted form is not available on all servers. If the optional targeted form DOES work on your server, you still have to wait after casting with Misc.Pause(…) for whatever the cast time should be. The server wont accept other commands until the cast time has completed.


## Magery


 |  Cast Spell


 | Syntax
 |  Spells.Cast(string SpellName [,item or int target])


 | Description:


 | Cast the spell specified, the spellname doesn&#039;t have to be spelled exactly. The target is optional and not available on all servers, but if specified the cast spell will be applied to the specified target. Note that this form can cast any of the classes of spell (Necro Mage…).


 | Returns
 | none


 | In Object:
 | Items


 | Parameters:
 | String SpellName, optionally Item or Int for a target


 |  Player Cast Magery Spell


 | Syntax
 |  Spells.CastMagery(string SpellName [,item or int target])


 | Description:


 | Player cast a magery spell by spellname. The target is optional and not available on all servers, but if specified the cast spell will be applied to the specified target.


 | Returns
 | void


 | In Object:
 | Spells


 | Parameters:
 | String Spellname


 | Parameters list:
 | 


- 
 Clumsy


- 
 Create Food


- 
 Feeblemind


- 
 Heal


- 
 Magic Arrow


- 
 Night Sight


- 
 Reactive Armor


- 
 Weaken


- 
 Agility


- 
 Cunning


- 
 Cure


- 
 Harm


- 
 Magic Trap


- 
 Magic Untrap


- 
 Protection


- 
 Strength


- 
 Bless


- 
 Fireball


- 
 Magic Lock


- 
 Poison


- 
 Telekinesis


- 
 Teleport


- 
 Unlock


- 
 Wall of Stone


- 
 Arch Cure


- 
 Arch Protection


- 
 Curse


- 
 Fire Field


- 
 Greater Heal


- 
 Lightning


- 
 Mana Drain


- 
 Recall


- 
 Blade Spirits


- 
 Dispel Field


- 
 Incognito


- 
 Magic Reflection


- 
 Mind Blast


- 
 Paralyze


- 
 Poison Field


- 
 Summon Creature


- 
 Dispel


- 
 Energy Bolt


- 
 Explosion


- 
 Invisibility


- 
 Mark


- 
 Mass Curse


- 
 Paralyze Field


- 
 Reveal


- 
 Chain Lightning


- 
 Energy Field


- 
 Flamestrike


- 
 Gate Travel


- 
 Mana Vampire


- 
 Mass Dispel


- 
 Meteor Swarm


- 
 Polymorph


- 
 Earthquake


- 
 Energy Vortex


- 
 Resurrection


- 
 Summon Air Elemental


- 
 Summon Daemon


- 
 Summon Earth Elemental


- 
 Summon Fire Elemental


- 
 Summon Water Elemental


## Necro


 |  Player Cast Necro Spell


 | Syntax
 |  Spells.CastNecro(string SpellName [,item or int target])


 | Description:


 | Player cast a necro spell by spellname. The target is optional and not available on all servers, but if specified the cast spell will be applied to the specified target.


 | Returns
 | void


 | In Object:
 | Spells


 | Parameters:
 | String Spellname


 | Parameters list:
 | 


- 
 Curse Weapon


- 
 Pain Spike


- 
 Corpse Skin


- 
 Evil Omen


- 
 Blood Oath


- 
 Wraith Form


- 
 Mind Rot


- 
 Summon Familiar


- 
 Horrific Beast


- 
 Animate Dead


- 
 Poison Strike


- 
 Wither


- 
 Strangle


- 
 Lich Form


- 
 Exorcism


- 
 Vengeful Spirit


- 
 Vampiric Embrace


## Chivalry


 |  Player Cast Chivalry Spell


 | Syntax
 |  Spells.CastChivalry(string SpellName [,item or int target])


 | Description:


 | Player cast a chivalry spell by spellname. The target is optional and not available on all servers, but if specified the cast spell will be applied to the specified target.


 | Returns
 | void


 | In Object:
 | Spells


 | Parameters:
 | String Spellname


 | Parameters list:
 | 


- 
 Close Wounds


- 
 Remove Curse


- 
 Cleanse By Fire


- 
 Consecrate Weapon


- 
 Sacred Journey


- 
 Divine Fury


- 
 Dispel Evil


- 
 Enemy Of One


- 
 Holy Light


- 
 Noble Sacrifice


## Bushido


 |  Player Cast Bushido Spell


 | Syntax
 |  Spells.CastBushido(string SpellName [,item or int target])


 | Description:


 | Player cast a bushido spell by spellname. The target is optional and not available on all servers, but if specified the cast spell will be applied to the specified target.


 | Returns
 | void


 | In Object:
 | Spells


 | Parameters:
 | String Spellname


 | Parameters list:
 | 


- 
 Honorable Execution


- 
 Confidence


- 
 Counter Attack


- 
 Lightning Strike


- 
 Evasion


- 
 Momentum Strike


## Ninjitsu


 |  Player Cast Ninjitsu Spell


 | Syntax
 |  Spells.CastNinjitsu(string SpellName [,item or int target])


 | Description:


 | Player cast a ninjitsu spell by spellname. The target is optional and not available on all servers, but if specified the cast spell will be applied to the specified target.


 | Returns
 | void


 | In Object:
 | Spells


 | Parameters:
 | String Spellname


 | Parameters list:
 | 


- 
 Animal Form


- 
 Backstab


- 
 Surprise Attack


- 
 Mirror Image


- 
 Shadow jump


- 
 Focus Attack


- 
 Ki Attack


## Spellweaving


 |  Player Cast Spellweaving Spell


 | Syntax
 |  Spells.CastSpellweaving(string SpellName [,item or int target])


 | Description:


 | Player cast a spellweaving spell by spellname. The target is optional and not available on all servers, but if specified the cast spell will be applied to the specified target.


 | Returns
 | void


 | In Object:
 | Spells


 | Parameters:
 | String Spellname


 | Parameters list:
 | 


- 
 Arcane Circle


- 
 Gift Of Renewal


- 
 Immolating Weapon


- 
 Attune Weapon


- 
 Thunderstorm


- 
 Natures Fury


- 
 Summon Fey


- 
 Summoniend


- 
 Reaper Form


- 
 Wildfire


- 
 Essence Of Wind


- 
 Dryad Allure


- 
 Ethereal Voyage


- 
 Word Of Death


- 
 Gift Of Life


- 
 Arcane Empowerment


## Mysticism


 |  Player Cast Mysticism Spell


 | Syntax
 |  Spells.CastMysticism(string SpellName [,item or int target])


 | Description:


 | Player cast a mysticism spell by spellname. The target is optional and not available on all servers, but if specified the cast spell will be applied to the specified target.


 | Returns
 | void


 | In Object:
 | Spells


 | Parameters:
 | String Spellname


 | Parameters list:
 | 


- 
 Animated Weapon


- 
 Healing Stone


- 
 Purge


- 
 Enchant


- 
 Sleep


- 
 Eagle Strike


- 
 Stone Form


- 
 SpellTrigger


- 
 Mass Sleep


- 
 Cleansing Winds


- 
 Bombard


- 
 Spell Plague


- 
 Hail Storm


- 
 Nether Cyclone


- 
 Rising Colossus


## Mastery


 |  Player Cast Mastery Spell


 | Syntax
 |  Spells.CastMastery(string SpellName [,item or int target])


 | Description:


 | Player cast a mastery spell by spellname. The target is optional and not available on all servers, but if specified the cast spell will be applied to the specified target.


 | Returns
 | void


 | In Object:
 | Spells


 | Parameters:
 | String Spellname


 | Parameters list:
 | 


- 
 Inspire


- 
 Invigorate


- 
 Resilience


- 
 Perseverance


- 
 Tribulation


- 
 Despair


- 
 Death Ray


- 
 Ethereal Blast


- 
 Nether Blast


- 
 Mystic Weapon


- 
 Command Undead


- 
 Conduit


- 
 Mana Shield


- 
 Summon Reaper


- 
 Enchanted Summoning


- 
 Anticipate Hit


- 
 Warcry


- 
 Intuition


- 
 Rejuvenate


- 
 Holy Fist


- 
 Shadow


- 
 White Tiger Form


- 
 Flaming Shot


- 
 Playing The Odds


- 
 Thrust


- 
 Pierce


- 
 Stagger


- 
 Toughness


- 
 Onslaught


- 
 Focused Eye


- 
 Elemental Fury


- 
 Called Shot


- 
 Saving Throw


- 
 Shield Bash


- 
 Bodyguard


- 
 Heighten Senses


- 
 Tolerance


- 
 Injected Strike


- 
 Potency


- 
 Rampage


- 
 Fists Of Fury


- 
 Knockout


- 
 Whispering


- 
 Combat Training


- 
 Boarding


- 


## Druid


 |  Player Cast Druid Spell


 | Syntax
 |  Spells.CastDruid(string SpellName [,item or int target])


 | Description:


 | Player cast a druid spell by spellname. Few servers support this and it must be enabled in options panel. The target is optional and not available on all servers, but if specified the cast spell will be applied to the specified target.


 | Returns
 | void


 | In Object:
 | Spells


 | Parameters:
 | String Spellname


 | Parameters list:
 | 


- 
 Bark Skin : Turns the druid&#039;s skin to bark, increasing physical, poison and energy resistence while reducing fire resistence.


- 
 Circle Of Thorns : Creates a ring of thorns preventing an enemy from moving.


- 
 Deadly Spores : The enemy is afflicted by poisonous spores.


- 
 Enchanted Grove : Causes a grove of magical trees to grow, hiding the player for a short time.


- 
 Firefly : Summons a tiny firefly to light the Druid&#039;s path. The Firefly is a weak creature with little or no combat skills.


- 
 Forest Kin : Summons from a list of woodland spirits that will fight for the druid and assist him in different ways.


- 
 Grasping Roots : Summons roots from the ground to entangle a single target.


- 
 Hibernate : Causes the target to go to sleep.


- 
 Hollow Reed : Increases both the strength and the intelligence of the Druid.


- 
 Hurricane : Calls forth a violent hurricane that damages any enemies within range.


- 
 Lure Stone : Creates a magical stone that calls all nearby animals to it.


- 
 Mana Spring : Creates a magical spring that restores mana to the druid and any party members within range.


- 
 Mushroom Gateway : A magical circle of mushrooms opens, allowing the Druid to step through it to another location.


- 
 Pack Of Beasts : Summons a pack of beasts to fight for the Druid. Spell length increases with skill.


- 
 Restorative Soil : Saturates a patch of land with power, causing healing mud to seep through . The mud can restore the dead to life.


- 
 Shield Of Earth : A quick-growing wall of foliage springs up at the bidding of the Druid.


- 
 Spring Of Life : Creates a magical spring that heals the Druid and their party.


- 
 Swarm Of Insects : Summons a swarm of insects that bite and sting the Druid&#039;s enemies.


- 
 Treefellow : Summons a powerful woodland spirit to fight for the Druid.


- 
 Volcanic Eruption : A blast of molten lava bursts from the ground, hitting every enemy nearby.


## Cleric


 |  Player Cast Cleric Spell


 | Syntax
 |  Spells.CastCleric(string SpellName [,item or int target])


 | Description:


 | Player cast a cleric spell by spellname. Few servers support this, and it must be enabled in options panel. The target is optional and not available on all servers, but if specified the cast spell will be applied to the specified target.


 | Returns
 | void


 | In Object:
 | Spells


 | Parameters:
 | String Spellname


 | Parameters list:
 | 


- 
 Angelic Faith : Turns you into an angel, boosting your stats. At 100 Spirit Speak you get +20 Str/Dex/Int. Every 5 points of SS = +1 point to each stat, at a max of +24. Will also boost your Anatomy, Mace Fighting and Healing, following the same formula.


- 
 Banish Evil : Banishes Undead targets. Auto kills rotting corpses, lich lords, etc. Works well at Doom Champ. Does not produce a corpse however


- 
 Dampen Spirit : Drains the stamina of your target, according to the description


- 
 Divine Focus : Heal for more, but may be broken.


- 
 Hammer of Faith : Summons a War Hammer with Undead Slayer on it for you


- 
 Purge : Cleanses Poison. Better than Cure


- 
 Restoration : Resurrection. Brings the target back with 100% HP/Mana


- 
 Sacred Boon : A HoT, heal over time spell, that heals 10-15 every few seconds


- 
 Sacrifice : Heals your party members when you take damage. Sort of like thorns, but it heals instead of hurts


- 
 Smite : Causes energy damage


- 
 Touch of Life : Heals even if Mortal Strike or poison are active on the target


- 
 Trial by Fire : Attackers receive damage when they strike you, sort of like a temporary RPD buff


---

# CUO Specific Functions

cuo_func


- 

- 

- 

- 

- 

- 

- 

- 

- 

- 


### Table of Contents


- 
Scripting - CUO Specific Functions


- 
Map Related


- 
CUO Profile Option Changes


- 
CUO Container Gump Functions


- 
Player Status Gump Functions


- 
CUO Macro Function


# Scripting - CUO Specific Functions


Here can find some information about Scripting functions that work with CUO


## Map Related


 |  Load Map Markers


 | Syntax
 |  CUO.LoadMarkers()


 | Description:


 |  Calls the LoadMarkers function on the CUO world map. The map must be open for this to work.
use in your code like:


#
CUO.LoadMarkers()
#


 | Returns
 | nothing


 | In Object:
 | CUO


 | Parameters:


 |  Go to Map Marker


 | Syntax
 |  CUO.GoToMarker(x, y)


 | Description:


 |  Executes the GoToMarker function on the CUO world map passing the x and y you provided. The map must be open for this to work.
use in your code like:


#
CUO.GoToMarker(100, 200)
#


 | Returns
 | nothing


 | In Object:
 | CUO


 | Parameters:


 |  FreeView for CUO Map


 | Syntax
 |  CUO.FreeView(bool)


 | Description:


 |  Executes the FreeView function on the CUO world map passing the bool you provided. The map must be open for this to work.
use in your code like:


#
CUO.FreeView(True)
#


 | Returns
 | nothing


 | In Object:
 | CUO


 | Parameters:


 |  Close Treasure Map


 | Syntax
 |  CUO.CloseTMap()


 | Description:


 |  Finds the first Treasure Map gump on your screen and closes it. If a Treasure Map gump was found returns True, otherwise returns False.
use in your code like:


#
CUO.CloseTMap()
#


 | Returns
 | True if a Treasure map was closed, otherwise False


 | In Object:
 | CUO


 | Parameters:


## CUO Profile Option Changes


 |  Sets an option in the CUO Profile


 | Syntax
 |  CUO.ProfilePropertySet(string propertyName, bool enable)


 | Description:


 |  This was just an experiment to see if I could automate the changing of CUO properties. 
use in your code like:


#
CUO.ProfilePropertySet("fps", "80")
#


 | Returns
 | Nothing


 | In Object:
 | CUO


 | Parameters:


## CUO Container Gump Functions


 |  Opens a Container at a specific location


 | Syntax
 |  CUO.OpenContainerAt(Item bag, int x, int y)


 | Description:


 |  Opens the specified container with the gump at the x, y provided. If already open nothing is done. 
use in your code like:


#
CUO.ProfilePropertySet("fps", "80")
#


 | Returns
 | Nothing


 | In Object:
 | CUO


 | Parameters:


 |  Sets the location the specified gump will open at


 | Syntax
 |  CUO.SetGumpOpenLocation(uint gumpserial, int x, int y)


 | Description:


 |  Changes the location the gump will open at 
use in your code like:


#
CUO.SetGumpOpenLocation(0x456789, 100, 200)
#


 | Returns
 | Nothing


 | In Object:
 | CUO


 | Parameters:
 |  gumpserial - the Serial id of the container
 |  x - x coordinate on screen
 |  y - y coordinate on screen


 |  Moves a gump to a specified location


 | Syntax
 |  CUO.MoveGump(uint serial, int x, int y)


 | Description:


 |  Moves a gump on the screen.. Note: I dont think this is working.
use in your code like:


#
CUO.MoveGump(0x456789, 100, 200)
#


 | Returns
 | Nothing


 | In Object:
 | CUO


 | Parameters:
 |  serial - the Serial id of the container
 |  x - x coordinate on screen
 |  y - y coordinate on screen


## Player Status Gump Functions


 |  Show the player status bar at a specific location


 | Syntax
 |  CUO.OpenMyStatusBar(int x, int y)


 | Description:


 |  Opens the player status bar at the specified location.
use in your code like:


#
CUO.OpenMyStatusBar(100, 200)
#


 | Returns
 | Nothing


 | In Object:
 | CUO


 | Parameters:
 |  x - x coordinate on screen
 |  y - y coordinate on screen


 |  Remove the player status bar


 | Syntax
 |  CUO.CloseMyStatusBar()


 | Description:


 |  Closes the player status bar.
use in your code like:


#
CUO.CloseMyStatusBar()
#


 | Returns
 | Nothing


 | In Object:
 | CUO


 | Parameters:


 |  Open the health bar of a mobile at a specified screen location


 | Syntax
 |  CUO.OpenMobileHealthBar(uint mobileserial, int x, int y, bool custom)


 | Description:


 |  Opens a health bar for a mobile and places the gump at the specified location.
use in your code like:


#
CUO.OpenMobileHealthBar(0x345678, 100, 200, False)
#


 | Returns
 | Nothing


 | In Object:
 | CUO


 | Parameters:
 |  uint mobileserial
 |  int x
 |  int y
 |  bool custom - True - the CUO square “minimalist” gump vs False - the standard UO gump


 |  Close the health bar of a mobile


 | Syntax
 |  CUO.CloseMobileHealthBar(uint mobileserial)


 | Description:


 |  Closes a health bar for a mobile.
use in your code like:


#
CUO.CloseMobileHealthBar(0x345678)
#


 | Returns
 | Nothing


 | In Object:
 | CUO


 | Parameters:
 |  uint mobileserial


## CUO Macro Function


 |  Play a CUO macro by name


 | Syntax
 |  CUO.PlayMacro(string macroName)


 | Description:


 |  WARNING Limited Testing: Attempts to play a CUO macro given its name.
use in your code like:


#
CUO.PlayMacro("MyMacro")
#


 | Returns
 | Nothing


 | In Object:
 | CUO


 | Parameters:
 |  string macroName


---

# Mobile Type Structure

mobile_struct


- 

- 

- 

- 

- 

- 

- 

- 

- 

- 


# Scripting - Mobile type structure


Here can find some information about Enhanced Scripting function about Mobile type structure data and related function!


 |  Mobile name


 | Syntax
 |  Mobile.Name


 | Description:


 | Read mobile name..


 | Returns
 | String


 | In Object:
 | Mobile


 | Parameters:
 | none


 |  Mobile body


 | Syntax
 |  Mobile.Body


 | Description:


 |  Read mobile body.


 | Returns
 | Integer


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile color


 | Syntax
 |  Mobile color


 | Description:


 |  Read mobile color.


 | Returns
 | Integer


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile Direction


 | Syntax
 |  Mobile.Direction


 | Description:


 |  Read mobile Direction.


 | Returns
 | String


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile Visible


 | Syntax
 |  Mobile.Visible


 | Description:


 |  Read mobile visible flag.


 | Returns
 | Bool


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile Poisoned


 | Syntax
 |  Mobile.Poisoned


 | Description:


 |  Read mobile poisoned flag.


 | Returns
 | Bool


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile Flying


 | Syntax
 |  Mobile.Flying


 | Description:


 |  Read mobile Flying flag.


 | Returns
 | Bool


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile YellowHits


 | Syntax
 |  Mobile.YellowHits


 | Description:


 |  Read mobile YellowHits flag.


 | Returns
 | Bool


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile YellowHits


 | Syntax
 |  Mobile.Paralized


 | Description:


 |  Read mobile Paralized flag.


 | Returns
 | Bool


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile Human


 | Syntax
 |  Mobile.IsHuman


 | Description:


 |  Read mobile human flag.


 | Returns
 | Bool


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile WarMode


 | Syntax
 |  Mobile.WarMode


 | Description:


 |  Read mobile warmode flag.


 | Returns
 | Bool


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile Female


 | Syntax
 |  Mobile.Female


 | Description:


 |  Read mobile gender.


 | Returns
 | Bool


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile Hits


 | Syntax
 |  Mobile.Hits


 | Description:


 |  Read mobile hits.


 | Returns
 | Integer


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile HitsMax


 | Syntax
 |  Mobile.HitsMax


 | Description:


 |  Read mobile maxhits.


 | Returns
 | Integer


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile Stamina


 | Syntax
 |  Mobile.Stam


 | Description:


 |  Read mobile stamina.


 | Returns
 | Integer


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile MaxStamina


 | Syntax
 |  Mobile.StamMax


 | Description:


 |  Read mobile max stamina.


 | Returns
 | Integer


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile Mana


 | Syntax
 |  Mobile.Mana


 | Description:


 |  Read mobile Mana.


 | Returns
 | Integer


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile ManaMax


 | Syntax
 |  Mobile.ManaMax


 | Description:


 |  Read mobile ManaMax.


 | Returns
 | Integer


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile Backpack


 | Syntax
 |  Mobile.Backpack


 | Description:


 |  Get item object for mobile backpack.


 | Returns
 | Item


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile Mount


 | Syntax
 |  Mobile.Mount


 | Description:


 |  Get item object for mobile Mount.


 | Returns
 | Mobile


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile Position


 | Syntax
 |  Mobile.Position


 | Description:


 |  Get Point3D about mobile position.


 | Returns
 | Point3D


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile Quiver


 | Syntax
 |  Mobile.Quiver


 | Description:


 |  Get item object for mobile quiver.


 | Returns
 | Item


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile Layer


 | Syntax
 |  GetItemOnLayer(string)


 | Description:


 |  Retrieves a item object of item equipped on specific layer.


 | Returns
 | Item


 | In Object:
 |  Mobile


 | Parameters:
 |  String Layername
RightHand
LeftHand
Shoes
Pants
Shirt
Head
Gloves
Ring
Neck
Waist
InnerTorso
Bracelet
MiddleTorso
Earrings
Arms
Cloak
OuterTorso
OuterLegs
InnerLegs


 | Exception
 |  If wrong layer name or layer empty function return null!


 |  Get Assistant Layer


 | Syntax
 |  Mobile.GetAssistantLayer(string)


 | Description:


 |  Get the Layer in Hex.


 | Returns
 | Item


 | In Object:
 |  Mobile


 | Parameters:
 |  String Layername


 |  Mobile Notoriety


 | Syntax
 |  Mobile.Notoriety


 | Description:


 |  Read byte of Notoriety color.


 | Returns
 | Byte


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile Map


 | Syntax
 |  Mobile.Map


 | Description:


 |  Read the facet of mobile.


 | Returns
 | Byte


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile Party


 | Syntax
 |  Mobile.InParty


 | Description:


 |  Get if mobile is in party.


 | Returns
 | Byte


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile Contains


 | Syntax
 |  Mobile.Contains


 | Description:


 |  Get a list of all items into the backpack.


 | Returns
 | List of Item


 | In Object:
 |  Mobile


 | Parameters:
 |  None


 |  Mobile Properties


 | Syntax
 |  Mobile.Properties


 | Description:


 |  Get a list of all properties of a mobile.


 | Returns
 | List of Property


 | In Object:
 |  Mobile


 | Parameters:
 |  None


---

# Mobiles Data and Functions

mobile_func


- 

- 

- 

- 

- 

- 

- 

- 

- 

- 


### Table of Contents


- 
Scripting - Mobiles data and function


- 
Find


- 
Use


- 
Filter Type


- 
Message


- 
ApplyFilter


- 
Properties


- 
Context


# Scripting - Mobiles data and function


Here can find some information about Enhanced Scripting function and data about Mobiles!


## Find


 |  Find Mobile by Serial


 | Syntax
 |  Mobiles.FindBySerial(int)


 | Description:


 | Find Mobile and get mobile object by specific serial


 | Returns
 | mobile


 | In Object:
 | Mobiles


 | Parameters:
 | Int serialnumber


## Use


 |  Use Mobile


 | Syntax
 |  Mobiles.UseMobile(mobile or int)


 | Description:


 | Use (double click) specific mobile, can insert mobile object or serial


 | Returns
 | none


 | In Object:
 | Mobiles


 | Parameters:
 | Mobile mobiletouse or Int serialmobiletouse


 |  Single Click


 | Syntax
 |  Mobiles.SingleClick(mobile or int)


 | Description:


 | Perform a single click on specific mobile, can insert mobile object or serial


 | Returns
 | none


 | In Object:
 | Mobiles


 | Parameters:
 | Mobile mobiletoclick or Int serialmobiletoclick


## Filter Type


 |  Enable Filter


 | Syntax
 |  Mobiles.Filter.Enabled


 | Description:


 | Enable or not filter in ApplyFilter function.


 | Returns
 | bool


 | In Object:
 | Mobiles


 | Parameters:
 | 


 |  Serial Filter


 | Syntax
 |  Mobiles.Filter.Serials


 | Description:


 | Set a list of serial to filter in ApplyFilter function.


 | Returns
 | list


 | In Object:
 | Mobiles


 | Parameters:
 | 


 |  CheckLineOfSite


 | Syntax
 |  Mobiles.Filter.CheckLineOfSite


 | Description:


 | Will check that a mobile is within your line of site.


 | Returns
 | list


 | In Object:
 | Mobiles


 | Parameters:

 | 


 |  Bodies Filter


 | Syntax
 |  Mobiles.Filter.Bodies


 | Description:


 | Set a list of body to filter in ApplyFilter function.


 | Returns
 | list


 | In Object:
 | Mobiles


 | Parameters:


 |  Name Filter


 | Syntax
 |  Mobiles.Filter.Name


 | Description:


 | Set a name to filter in ApplyFilter function, blank no filter by name


 | Returns
 | string


 | In Object:
 | Mobiles


 | Parameters:
 | 


 |  Range Min Filter


 | Syntax
 |  Mobiles.Filter.RangeMin


 | Description:


 | Set a value of minimum range in ApplyFilter function


 | Returns
 | int


 | In Object:
 | Mobiles


 | Parameters:
 | 


 |  Range Max Filter


 | Syntax
 |  Mobiles.Filter.RangeMax


 | Description:


 | Set a value of maximum range in ApplyFilter function


 | Returns
 | int


 | In Object:
 | Mobiles


 | Parameters:
 | 


 |  Z Range Min Filter


 | Syntax
 |  Mobiles.Filter.ZRangeMin


 | Description:


 | Set a value of minimum Z range in ApplyFilter function


 | Returns
 | int


 | In Object:
 | Mobiles


 | Parameters:
 | 


 |  Z Range Max Filter


 | Syntax
 |  Mobiles.Filter.ZRangeMax


 | Description:


 | Set a value of maximum Z range in ApplyFilter function


 | Returns
 | int


 | In Object:
 | Mobiles


 | Parameters:
 | 


 |  Color Filter


 | Syntax
 |  Mobiles.Filter.Hues


 | Description:


 | Set a list of color to filter in ApplyFilter function.


 | Returns
 | list


 | In Object:
 | Mobiles


 | Parameters:
 | 


 |  Poisoned Filter


 | Syntax
 |  Mobiles.Filter.Poisoned


 | Description:


 | Set a filter by poisoned flag for ApplyFilter function. 1 On, 0 Off, -1 Both


 | Returns
 | int


 | In Object:
 | Mobiles


 | Parameters:
 | 


 |  Human Filter


 | Syntax
 |  Mobiles.Filter.IsHuman


 | Description:


 | Set a filter by Human flag for ApplyFilter function. 1 On, 0 Off, -1 Both


 | Returns
 | int


 | In Object:
 | Mobiles


 | Parameters:
 | 


 |  Ghost Filter


 | Syntax
 |  Mobiles.Filter.IsGhost


 | Description:


 | Set a filter by Ghost flag for ApplyFilter function. 1 On, 0 Off, -1 Both


 | Returns
 | int


 | In Object:
 | Mobiles


 | Parameters:
 | 


 |  Sex Filter


 | Syntax
 |  Mobiles.Filter.Female


 | Description:


 | Set a filter by sex for ApplyFilter function. 1 Female, 0 Male, -1 Both


 | Returns
 | int


 | In Object:
 | Mobiles


 | Parameters:
 | 


 |  Warmode Filter


 | Syntax
 |  Mobiles.Filter.Warmode


 | Description:


 | Set a filter by warmode flag for ApplyFilter function. 1 On, 0 Off, -1 Both


 | Returns
 | int


 | In Object:
 | Mobiles


 | Parameters:
 | 


 |  Friend Filter


 | Syntax
 |  Mobiles.Filter.Friend


 | Description:


 | Set a filter by friend list for ApplyFilter function. 1 On, 0 Off, -1 Both


 | Returns
 | int


 | In Object:
 | Mobiles


 | Parameters:
 | 


 |  Notorieties color Filter


 | Syntax
 |  Mobiles.Filter.Notorieties


 | Description:


 | Set a filter by byte list for notorieties color for ApplyFilter function.            blue = 1, green = 2, gray = 3, gray crim = 4, orange = 5, red = 6, yellow = 7


 | Returns
 | list


 | In Object:
 | Mobiles


 | Parameters:
 | 


 |  Ignore list Filter


 | Syntax
 |  Mobiles.Filter.CheckIgnoreObject


 | Description:


 | Set search parameter True or false for remove IgnoreObject from result.


 | Returns
 | bool


 | In Object:
 | Mobiles


 | Parameters:
 | 


 |  Ignore Pets list Filter


 | Syntax
 |  Mobiles.Filter.IgnorePets


 | Description:


 |  Remove any of your pets from the returned filter list.


 | Returns
 | bool


 | In Object:
 | Mobiles


 | Parameters:
 | 


## Message


 |  Mobile Message


 | Syntax
 |  Mobiles.Message(mobile or int, int, string)


 | Description:


 | Display a message over specific mobile whit color.


 | Returns
 | void


 | In Object:
 | Mobiles


 | Parameters:
 | Int MobileSerial or Mobile SelectedMobile, Int MessageColor, String Message


## ApplyFilter


 |  Search Mobile with a filter


 | Syntax
 |  Mobiles.ApplyFilter(filter)


 | Description:


 | Seatch a mobile by filter


 | Returns
 | list(mobile)


 | In Object:
 | Mobiles


 | Parameters:
 | filter


 |  Apply a selector on mobile list


 | Syntax
 |  Mobiles.Select( List<Mobile>, string)


 | Description:


 | Apply a selector on mobile list.


 | Returns
 | Mobile


 | In Object:
 | Mobiles


 | Parameters:
 | List<Mobile>, string


 | Possible selector:
 | 


- 
 Random


- 
 Nearest


- 
 Farthest


- 
 Weakest


- 
 Strongest


- 
 Next


## Properties


 |  Mobile WaitforProps


 | Syntax
 |  Mobiles.WaitForProps(mobile or int, int)


 | Description:


 | Retrive Propriety of specific mobile.


 | Returns
 | none


 | In Object:
 | Mobiles


 | Parameters:
 | Mobile mobiletocheck, int serialmobiletocheck, Int delay of props wait (ms)


 |  Get Item Proprerties


 | Syntax
 |  Mobiles.GetPropValue(int or mobile, string)


 | Description:


 | Get value of item propriety


 | Returns
 | int


 | In Object:
 | Mobiles


 | Parameters:
 | Int serialtoinspect or mobile mobiletoinspect, String PropName


 |  Get Mobile Proprerties String


 | Syntax
 |  Mobiles.GetPropStringByIndex(int or mobile, int)


 | Description:


 | Get string name of prop by index, if no prop in selected index return empty.


 | Returns
 | string


 | In Object:
 | Mobiles


 | Parameters:
 | Int serialtoinspect or mobile mobiletoinspect, Int PropIndex


 |  Get Mobile Proprerties String List


 | Syntax
 |  Mobiles.GetPropStringList(int or mobile)


 | Description:


 | Get string list of all props name on specific mobile, if item no props list is empty.


 | Returns
 | List (String)


 | In Object:
 | Mobiles


 | Parameters:
 | Int serialtoinspect or mobile mobiletoinspect


 |  Mobile WaitForStats


 | Syntax
 |  Mobiles.WaitForStats (mobile or int, int)


 | Description:


 | Retrive stat value of specific mobile. This is for OSI or server not send stats if no open bars.


 | Returns
 | none


 | In Object:
 | Mobiles


 | Parameters:
 | Mobile mobiletocheck, int serialmobiletocheck, Int delay of props wait (ms)


## Context


 |  Context Exist


 | Syntax
 |  Mobiles.ContextExist(int or mobile, string)


 | Description:


 | Check on specific mobile if context menu by string exist. Return context id if exist, -1 if not present.


 | Returns
 | string


 | In Object:
 | Mobiles


 | Parameters:
 | Int mobserial or item mobiletocheck, string contextstring


 |  Get the last tracking information


 | Syntax
 |  Mobiles.GetTrackingInfo( )


 | Description:


 | returns a structure of the last tracking info


 | use in your code like:


#
tracking = Mobiles.GetTrackingInfo()
Misc.SendMessage("serial: 0x{:x} at x:{} y:{} ts: {}".format(tracking.serial, tracking.x, tracking.y, tracking.lastUpdate))
#


 | Returns
 |         public struct LastTrackingInfo


      {
          public UInt16 x;
          public UInt16 y;
          public UInt32 serial;
          public DateTime lastUpdate;
      }


 | In Object:
 | Misc


 | Parameters:
 | none


---

# Item Type Structure

item_struct


- 

- 

- 

- 

- 

- 

- 

- 

- 

- 


# Scripting - Item type structure


Here can find some information about Enhanced Scripting about Item type structure.


 |  Item Amount


 | Syntax
 |  item.Amount


 | Description:


 | Read amount from item type object.


 | Returns
 | Int


 | In Object:
 | Item


 | Parameters:
 | 


 |  Item Color


 | Syntax
 |  item.Hue


 | Description:


 | Read color number from item type object.


 | Returns
 | Int


 | In Object:
 | Item


 | Parameters:
 | 


 |  Item Bag of Sending


 | Syntax
 |  item.IsBagOfSending


 | Description:


 | Return a bool if item object is a Bag of Sending. True: Is a Bag of Sending, False: Isn&#039;t a Bag of Sending


 | Returns
 | Bool


 | In Object:
 | Item


 | Parameters:
 | 


 |  Item Container


 | Syntax
 |  item.IsContainer


 | Description:


 | Return a bool if item object is a container. True: Is a container, False: Isn&#039;t a container


 | Returns
 | Bool


 | In Object:
 | Item


 | Parameters:
 | 


 |  Item Corpse


 | Syntax
 |  item.IsCorpse


 | Description:


 | Return a bool if item object is a corpse. True: Is a corpse, False: Isn&#039;t a corpse


 | Returns
 | Bool


 | In Object:
 | Item


 | Parameters:
 | 


 |  Item Door


 | Syntax
 |  item.IsDoor


 | Description:


 | Return a bool if item object is a door. True: Is a door, False: Isn&#039;t a door


 | Returns
 | Bool


 | In Object:
 | Item


 | Parameters:
 | 


 |  Item is In Bank


 | Syntax
 |  item.IsInBank


 | Description:


 | Return a bool if item object is inside a bank. True: Is in bankbox, False: Isn&#039;t in bankbox


 | Returns
 | Bool


 | In Object:
 | Item


 | Parameters:
 | 


 |  Item is Movable


 | Syntax
 |  item.Movable


 | Description:


 | Return a bool if item object is movable. True: Can move, False: Can&#039;t move


 | Returns
 | Bool


 | In Object:
 | Item


 | Parameters:
 | 


 |  Item is o Ground


 | Syntax
 |  item.OnGround


 | Description:


 | Return a bool if item object is on ground. True: Item is on ground, False: Item isn&#039;t on ground


 | Returns
 | Bool


 | In Object:
 | Item


 | Parameters:
 | 


 |  Item Name


 | Syntax
 |  item.Name


 | Description:


 | Get name of item.


 | Returns
 | String


 | In Object:
 | Item


 | Parameters:
 | 


 |  Item Serial


 | Syntax
 |  item.Serial


 | Description:


 | Get serial number of item.


 | Returns
 | Int


 | In Object:
 | Item


 | Parameters:
 | 


 |  Item Graphycs


 | Syntax
 |  item.ItemID


 | Description:


 | Get graphycs of item.


 | Returns
 | Int


 | In Object:
 | Item


 | Parameters:
 | 


 |  Item Root Container


 | Syntax
 |  item.RootContainer


 | Description:


 | Get serial of root container of item.


 | Returns
 | int


 | In Object:
 | Item


 | Parameters:
 | 


 |  Item Container


 | Syntax
 |  item.Container


 | Description:


 | Get serial of container of item.


 | Returns
 | int


 | In Object:
 | Item


 | Parameters:
 | 


 |  Item Position


 | Syntax
 |  item.Position


 | Description:


 | Get Point3D coords of item.


 | Returns
 | Point3D


 | In Object:
 | Item


 | Parameters:
 | 


 |  Item Position X coord


 | Syntax
 |  item.Position.X


 | Description:


 | Get X coord of item.


 | Returns
 | Int


 | In Object:
 | Item


 | Parameters:
 | 


 |  Item Position Y coord


 | Syntax
 |  item.Position.Y


 | Description:


 | Get Y coord of item.


 | Returns
 | Int


 | In Object:
 | Item


 | Parameters:
 | 


 |  Item Position Z level


 | Syntax
 |  item.Position.Z


 | Description:


 | Get Z level of item.


 | Returns
 | Int


 | In Object:
 | Item


 | Parameters:
 | 


 |  Item Weight


 | Syntax
 |  item.Weight


 | Description:


 | Get Weight value.


 | Returns
 | Int


 | In Object:
 | Item


 | Parameters:
 | 


 |  Item Durability


 | Syntax
 |  item.Durability


 | Description:


 | Get Durability value.


 | Returns
 | Int


 | In Object:
 | Item


 | Parameters:
 | 


 |  Item Maximum Durability


 | Syntax
 |  item.MaxDurability


 | Description:


 | Get maximum durability value.


 | Returns
 | Int


 | In Object:
 | Item


 | Parameters:
 | 


 |  Item In container


 | Syntax
 |  item.Contains


 | Description:


 | Return a list of item inside a container.


 | Returns
 | list


 | In Object:
 | Item


 | Parameters:
 | 


 |  Item Distance


 | Syntax
 |  item.DistanceTo(mobile)


 | Description:


 | Return a int of tile distance from item to mobile.


 | Returns
 | int


 | In Object:
 | Item


 | Parameters:
 | mobile


---

# Item Functions

item_func


- 

- 

- 

- 

- 

- 

- 

- 

- 

- 


### Table of Contents


- 
Scripting - Items data and function


- 
Find


- 
Move


- 
Drop


- 
Use


- 
Properties


- 
WaitForContent


- 
Message


- 
Filter Type


- 
Apply Filter


- 
Count


- 
Hide


- 
Context


- 
Device Specific


# Scripting - Items data and function


Here can find some information about Enhanced Scripting function and data about Mobiles!


## Find


 |  Find item by Serial


 | Syntax
 |  Items.FindBySerial(int)


 | Description:


 | Find item and get item object by specific serial


 | Returns
 | Item


 | In Object:
 | Items


 | Parameters:
 | Int serialnumber


 | Exception:
 | If item not found function return null!


 |  Find item by ItemID


 | Syntax
 |  Items.FindByID(int, int, int [, int=0])


 | Description:


 | Find item serial by specific item ID, color and Container (optional container depth). Can use -1 on color for no chose color, can use -1 on container for search in all item in memory. The depth defaults to only the top but can search for # of sub containers.


 | Returns
 | Item


 | In Object:
 | Items


 | Parameters:
 | Int itemid, int color, int serialcontainer


 | Exception:
 | If item not found function return null!


 |  Find all items by ItemID


 | Syntax
 |  Items.FindAllByID(int, int, int [, int=0])


 | Description:


 | Find item serial by specific item ID, color and Container (optional container depth). Can use -1 on color for no chose color, can use -1 on container for search in all item in memory. The depth defaults to only the top but can search for # of sub containers.


 | Returns
 | python list of Items


 | In Object:
 | Items


 | Parameters:
 | Int itemid, int color, int serialcontainer


 | Exception:
 | If item not found function return empty list


 |  Find all items by ItemID


 | Syntax
 |  Items.FindAllByID(list of int, int, int [, int=0])


 | Description:


 | Find items that are any of the item ID specified in the list, color and Container (optional container depth). Can use -1 on color for no chose color, can use -1 on container for search in all item in memory. The depth defaults to only the top but can search for # of sub containers.


 | Returns
 | python list of Items


 | In Object:
 | Items


 | Parameters:
 | Int itemid, int color, int serialcontainer


 | Exception:
 | If item not found function return empty list


## Move


 |  Move item


 | Syntax
 |  Items.Move(int or item source, item or mobile or int dest, int amount, [int X, int Y] optional)


 | Description:


 | Move specific item with amount to specific destination allow also move item on mobile, if set amount 0 move all item stack, if ask to move amount major stack move all stack. Also can specify coords for move item in x y on container grid. All parameters can be int (for serial), or object item and mobile.


 | Returns
 | none


 | In Object:
 | Items


 | Parameters:
 | Item source, Item destination, Int amount or Item source, Mobile destination, Int amount or Item source, Item destination, Int amount, Int XGridPosition, Int YGridPosition


 |  Move item on Ground


 | Syntax
 |  Items.MoveOnGround(item, int, int, int, int)


 | Description:


 | Move specific item with amount to specific destination on ground by coords (X, Y, Z).


 | Returns
 | none


 | In Object:
 | Items


 | Parameters:
 | Item source, Int amount, Int XPosition, Int YPosition, Int ZPosition


## Drop


 |  Drop Item on ground


 | Syntax
 |  Items.DropItemGroundSelf(item, int)


 | Description:


 | Drop on character feet specific item with amount, if set amount 0 move all item stack, if ask to drop amount major stack drop all stack


 | Returns
 | none


 | In Object:
 | Items


 | Parameters:
 | Item source, Int amount


## Use


 |  Use item


 | Syntax
 |  Items.UseItem(item or int [,item or int target])


 | Description:


 | Use (double click) specific item, can insert item object or serial. The target is optional, but if specified the used item will be applied to the specified target.


 | Returns
 | none


 | In Object:
 | Items


 | Parameters:
 | Item itemToUse or Int serialItemToUse, optionally Item or Int for a target


 |  Single Click


 | Syntax
 |  Items.SingleClick(item or int)


 | Description:


 | Perform a single click specific item, can insert item object ot serial


 | Returns
 | none


 | In Object:
 | Items


 | Parameters:
 | Item itemtoclick or Int serialitemtoclick


 |  Use item By ItemID


 | Syntax
 |  Items.UseItemByID(int, int)


 | Description:


 | Use (double click) specific item owned by player by ItemID and Color (-1 all color).


 | Returns
 | none


 | In Object:
 | Items


 | Parameters:
 | int itemid, int color


 |  Use item on Mobile


 | Syntax
 |  Items.UseItemOnMobile(int or item, int or mobile)


 | Description:


 | Use and autotarget whit 0xBF.2C packet a item on specific mobile (whit out iterruption or target lost).


 | Returns
 | none


 | In Object:
 | Items


 | Parameters:
 | int itemserial or item itemtouse, int mobielserial or mobile mobiletarget


 |  Use item on Mobile or Item


 | Syntax
 |  Items.UseItemOn(int or item, int or mobile or item)


 | Description:


 | Use and autotarget with 0xBF.2C packet an item on specific mobile or item (whithout interruption or target lost).
Appears to only work on OSI servers


 | Returns
 | none


 | In Object:
 | Items


 | Parameters:
 | int itemSerial or item itemToUse, int serial (item or mobile) or mobile or item object


## Properties


 |  Item WaitforProps


 | Syntax
 |  Items.WaitForProps(item or int, int)


 | Description:


 | Retrive Propriety of specific item.


 | Returns
 | none


 | In Object:
 | Items


 | Parameters:
 | Item itemtocheck, int serialitemtocheck, Int delay of props wait (ms)


 |  Get Item Proprerties


 | Syntax
 |  Items.GetPropValue(int or item, string)


 | Description:


 |  Looks up the property by name on left side of &#039;:&#039; parses the numeric value on the right side of the : into a float number and returns the number


 | Returns
 | float


 | In Object:
 | Items


 | Parameters:
 | Int serialtoinspect or Item itemtoinspect, Int PropIndex


 |  Get Item Proprerties


 | Syntax
 |  Items.GetPropValueString(int serial, string propname)


 | Description:


 |  Looks up the property with the name provided on the left side of a : and returns the string on the right side or the :. Note: partial property name matchs work e.g. “loc” will match to “location”, but “ocation” will not match “location”


 | Returns
 | string


 | In Object:
 | Items


 | Parameters:
 | Int serialtoinspect or Item itemtoinspect, string PropName


 |  Get Item Proprerties String


 | Syntax
 |  Items.GetPropStringByIndex(int or item, int)


 | Description:


 | Get string name of prop by index, if no prop in selected index return empty


 | Returns
 | string


 | In Object:
 | Items


 | Parameters:
 | Int serialtoinspect or Item itemtoinspect, Int PropIndex


 |  Get Item Proprerties String List


 | Syntax
 |  Items.GetPropStringList(int or item)


 | Description:


 | Get string list of all props name on specific item, if item no props list is empty.


 | Returns
 | List(string)


 | In Object:
 | Items


 | Parameters:
 | Int serialtoinspect or Item itemtoinspect


## WaitForContent


 |  Item container WaitforContents


 | Syntax
 |  Items.WaitForContents(item or int, int)


 | Description:


 | Force a item to open and automatic wait response for item inside


 | Returns
 | none


 | In Object:
 | Items


 | Parameters:
 | Item itemtouse, int serialitemtouse, Int delay of content wait (ms)


## Message


 |  Item Message


 | Syntax
 |  Items.Message(item or int, int, string)


 | Description:


 | Display a message over specific item whit color.


 | Returns
 | void


 | In Object:
 | Items


 | Parameters:
 | Int ItemSerial or Item SelectedItem, Int MessageColor, String Message


## Filter Type


 |  Enable Filter


 | Syntax
 |  Items.Filter.Enabled


 | Description:


 | Enable or not filter in ApplyFilter function.


 | Returns
 | bool


 | In Object:
 | Items


 | Parameters:
 | 


 |  Serials Filter


 | Syntax
 |  Items.Filter.Serials


 | Description:


 | Set a list of serial to filter in ApplyFilter function.


 | Returns
 | list(int)


 | In Object:
 | Items


 | Parameters:
 | 


 |  Graphics Filter


 | Syntax
 |  Items.Filter.Graphics


 | Description:


 | Set a list of Graphics to filter in ApplyFilter function.


 | Returns
 | list(int)


 | In Object:
 | Items


 | Parameters:
 | 


 |  Color Filter


 | Syntax
 |  Items.Filter.Hues


 | Description:


 | Set a list of color to filter in ApplyFilter function.


 | Returns
 | list(int)


 | In Object:
 | Items


 | Parameters:
 | 


 |  Name Filter


 | Syntax
 |  Items.Filter.Name


 | Description:


 | Set a name to filter in ApplyFilter function, blank no filter by name


 | Returns
 | string


 | In Object:
 | Items


 | Parameters:
 | 


 |  Range Min Filter


 | Syntax
 |  Items.Filter.RangeMin


 | Description:


 | Set a value of minimum range in ApplyFilter function


 | Returns
 | int


 | In Object:
 | Items


 | Parameters:
 | 


 |  Range Max Filter


 | Syntax
 |  Items.Filter.RangeMax


 | Description:


 | Set a value of maximum range in ApplyFilter function


 | Returns
 | int


 | In Object:
 | Items


 | Parameters:
 | 


 |  Movable Filter


 | Syntax
 |  Items.Filter.Movable


 | Description:


 | Set search parameter movable for ApplyFilter function


 | Returns
 | bool


 | In Object:
 | Items


 | Parameters:
 | 


 |  Layers Filter


 | Syntax
 |  Items.Filter.Layers


 | Description:


 | Set search list by layer for ApplyFilter function


 | Returns
 | list


 | In Object:
 | Items


 | Parameters:
 | 


 |  Ground Filter


 | Syntax
 |  Items.Filter.OnGround


 | Description:


 | Set search parameter if item is on ground for ApplyFilter function. (1=Only OnGround, 0=Skipp OnGround, -1= Both


 | Returns
 | Int


 | In Object:
 | Items


 | Parameters:
 | 


 |  Corpse Filter


 | Syntax
 |  Items.Filter.IsCorpse


 | Description:


 | Set search parameter if item is a corpse for ApplyFilter function. (1=Only Corpse, 0=Skipp Corpse, -1= Both


 | Returns
 | Int


 | In Object:
 | Items


 | Parameters:
 | 


 |  Container Filter


 | Syntax
 |  Items.Filter.IsContainer


 | Description:


 | Set search parameter if item is a container for ApplyFilter function. (1=Only container, 0=Skipp Container, -1= Both).


 | Returns
 | Int


 | In Object:
 | Items


 | Parameters:
 | 


 |  Ignore list Filter


 | Syntax
 |  Items.Filter.CheckIgnoreObject


 | Description:


 | Set search parameter True or false for remove IgnoreObject from result.


 | Returns
 | bool


 | In Object:
 | Items


 | Parameters:
 | 


## Apply Filter


 |  Seach an item with a filter


 | Syntax
 |  Items.ApplyFilter(filter)


 | Description:


 | Search an item by filter


 | Returns
 | list(item)


 | In Object:
 | Items


 | Parameters:
 | filter


 |  Apply a selector on item list


 | Syntax
 |  Items.Select((List)Item, string)


 | Description:


 | Apply a selector on mobile list.


 | Returns
 | Item


 | In Object:
 | Items


 | Parameters:
 | (List)Item, string


 | Possible selector:
 | 


- 
 Random


- 
 Nearest


- 
 Farthest


- 
 Less


- 
 Most


- 
 Weakest


- 
 Strongest


## Count


 |  Count Type in Backpack


 | Syntax
 |  Items.BackpackCount(int, int)


 | Description:


 | Return amount of specific item (By ItemID) and color in backpack and subcontainer, Color -1 is WildCard for all color.


 | Returns
 | Int


 | In Object:
 | Items


 | Parameters:
 | int itemID, int color


 |  Count Type in Container


 | Syntax
 |  Items.ContainerCount(int or item, int, int, bool)


 | Description:


 | Return amount of specific item (By ItemID) and color in specific container, Color -1 is WildCard for all color.


 | Returns
 | Int


 | In Object:
 | Items


 | Parameters:
 | Int containerserial or Item container, Int itemid, Int color, bool recurse


## Hide


 |  Hide item


 | Syntax
 |  Items.Hide(int or item)


 | Description:


 | Hide an item.


 | Returns
 |  none


 | In Object:
 | Items


 | Parameters:
 |  itemId or Item


## Context


 |  Context Exist


 | Syntax
 |  Items.ContextExist(int or item, string)


 | Description:


 | Check on specific item if context menu by string exist. Return context id if exist, -1 if not present.


 | Returns
 | int


 | In Object:
 | Items


 | Parameters:
 | Int itemserial or item itemtocheck, string contextstring


## Device Specific


 |  GetImage


 | Syntax
 |  Items.GetImage(itemID, int hue)


 | Description:


 | Return the internal bitmap associated with an itemid


 | Returns
 | System.Drawing.Bitmap


 | In Object:
 | Items


 | Parameters:
 | int itemID, int hue


---

# Misc Functions

misc_func


- 

- 

- 

- 

- 

- 

- 

- 

- 

- 


### Table of Contents


- 
Scripting - Misc data and function


- 
Message


- 
File


- 
System


- 
Misc


- 
Mouse


- 
Disconnect


- 
Context Menu


- 
Share Data for Script


- 
Old Menu


- 
Query String


- 
Script Function


- 
Maps


- 
Pets


- 
String Prompt Response


- 
Ignore List


# Scripting - Misc data and function


Here can find some infomation about Enhanced Scripting function and data misc!


## Message


 |  Player Sysmessage


 | Syntax
 |  Misc.SendMessage(string or int or bool)


 | Description:


 | Send a sysmessage.


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | string Message, int Value, bool Status


 |  Player Sysmessage colored


 | Syntax
 |  Misc.SendMessage(string or int or bool, color)


 | Description:


 | Send a sysmessage whit specific color


 | Returns
 |  none


 | In Object:
 | Misc


 | Parameters:
 | string Message or int Value or bool Status, int color


 |  Player SendToClient


 | Syntax
 |  Misc.SendToClient(string)


 | Description:


 | Send a string to the UO client window. Can contain control characters by prefixing the character with ^ (e.g. ctrl-u is “^u”)


 | Returns
 |  none


 | In Object:
 | Misc


 | Parameters:
 | string to send to client window


## File


The file operations are limited, because I am paranoid of bad actors.
The file to be written to MUST be in the RE directory tree, or if your running CUO it can be in the CUO directory tree. Further, the file suffix has to be one of {data, xml, map, csv}. The file suffixes list could be extended, but the main thing I didn&#039;t want someone to do damage to files needed for execution. 


 |  Append a line to a file


 | Syntax
 |  Misc.AppendToFile(string FileName, string LineToAppend)


 | Description:


 | Appends a single line to a file.


 | Returns
 | bool True - success False - Fail


 | In Object:
 | Misc


 | Parameters:
 | string FileName, string LineToInsert


 |  Append a line to a file IF it doesn&#039;t already exist


 | Syntax
 |  Misc.AppendNotDupToFile(string FileName, string LineToAppend)


 | Description:


 |  Appends a single line to a file if that line does not already exist in the file.
use in your code like:


#
result = Misc.AppendNotDupToFile("C:/CUO/Data/Client/TreasureMaps.csv", "1111, 2222, map,desc,I forget")
#


 | Returns
 | bool


 | In Object:
 | Misc


 | Parameters:
 | string FileName, string LineToInsert


 |  Remove a line from a file


 | Syntax
 |  Misc.DeleteFile(string FileName)


 | Description:


 | Deletes a file


 | Returns
 | bool True - success False - Fail


 | In Object:
 | Misc


 | Parameters:
 | string FileName


 |  Remove a line from a file


 | Syntax
 |  Misc.RemoveLineInFile(string FileName, string LineToAppend)


 | Description:


 | Removes a single line from a file if it exists


 | Returns
 | bool True - success False - Fail


 | In Object:
 | Misc


 | Parameters:
 | string FileName, string LineToInsert


## System


 |  Resync Game Data


 | Syntax
 |  Misc.Resync( )


 | Description:


 | Resync game data.


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | none


 |  Pause on Script


 | Syntax
 |  Misc.Pause(int)


 | Description:


 | Pause script for X millisecond.


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | MSpause


 |  Focus on UoClient window


 | Syntax
 |  Misc.FocusUOWindow()


 | Description:


 | Set UoClient window in focus or restore if minimized.


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | none


 |  Screen Capture the UoClient window


 | Syntax
 |  Misc.CaptureNow()


 | Description:


 | Creates a snapshot of the current UO window


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | none


## Misc


 |  Beep


 | Syntax
 |  Misc.Beep( )


 | Description:


 | Play beep system sound.


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | none


 |  Shard Name


 | Syntax
 |  Misc.ShardName( )


 | Description:


 | Get string with shard name you play.


 | Returns
 | string


 | In Object:
 | Misc


 | Parameters:
 | none


 |  Inspect Items


 | Syntax
 |  Misc.Inspect( )


 | Description:


 | Prompts for a target, then displays info for that item


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | none


 |  NextContPosition


 | Syntax
 |  Misc.NextContPosition(x, y)


 | Description:


 | Sets the x,y co-ordinates of where the next gump will be openned. You must have cascading containers enabled


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | int x, int y window position


 |  GetContPosition


 | Syntax
 |  Misc.GetContPosition()


 | Description:


 | Returns the x,y co-ordinates of where the current gumpis positioned.


 | Returns
 | point(x, y)


 | In Object:
 | Misc


 | Parameters:
 | 


## Mouse


 |  Get Current Mouse Location


 | Syntax
 |  Misc.MouseLocation()


 | Description:


 | Returns a point with the X and Y coordinates of the mouse relative to the UO Window


 | Returns
 | point


 | In Object:
 | Misc


 | Parameters:
 | none


 | Example:


p = Misc.MouseLocation()


 |  Set Mouse Location


 | Syntax
 |  Misc.MouseMove()


 | Description:


 | Moves the mouse pointer to the position X,Y relative to the UO window


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | int X, int Y


 | Example:


Misc.MouseMove(p.X+10, p.Y+20)


## Disconnect


 |  Disconnect


 | Syntax
 |  Misc.Disconnect( )


 | Description: Immediate logout


 | Force client to disconnect.


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | none


## Context Menu


 |  Wait Context Menu


 | Syntax
 |  Misc.WaitForContext(int or mobile or item, int)


 | Description:


 | Wait server response a context menu request.


 | Returns
 | List < Context > - Context { int reply, string text in menu }


 | In Object:
 | Misc


 | Parameters:
 | timeout


 |  Context Menu Reply


 | Syntax
 |  Misc.ContextReply(int or mobile or item, int or string)


 | Description:


 | Respond to a context menu on mobile or item. Menu ID is base zero, or can use string of menu text


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | Menuname


## Share Data for Script


 |  Read Shared Value


 | Syntax
 |  Misc.ReadSharedValue(string)


 | Description:


 | Read a shared value, if value not exist return null.


 | Returns
 | obj


 | In Object:
 | Misc


 | Parameters:
 | nameofvalue


 |  Remove Shared Value


 | Syntax
 |  Misc.RemoveSharedValue(string)


 | Description:


 | Remove a shared value,


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | nameofvalue


 |  Check Shared Value


 | Syntax
 |  Misc.CheckSharedValue(string)


 | Description:


 | Get a true o flase if value exist.


 | Returns
 | bool


 | In Object:
 | Misc


 | Parameters:
 | nameofvalue


 |  Set Shared Value


 | Syntax
 |  Misc.SetSharedValue(string, obj)


 | Description:


 | Set a value by specific name, if value exist he repalce value.


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | value


## Old Menu


 |  Has Menu


 | Syntax
 |  Misc.HasMenu()


 | Description:


 | Return bool if have or not a menu opened.


 | Returns
 | bool


 | In Object:
 | Misc


 | Parameters:
 | none


 |  Close Menu


 | Syntax
 |  Misc.CloseMenu()


 | Description:


 | Close opened menu.


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | none


 |  Menu Contain


 | Syntax
 |  Misc.MenuContain(string)


 | Description:


 | Search in opened menu if contains a specific string, return true or false.


 | Returns
 | bool


 | In Object:
 | Misc


 | Parameters:
 | texttosearch


 |  Menu Title


 | Syntax
 |  Misc.GetMenuTitile()


 | Description:


 | Return a string of title for opene menu.


 | Returns
 | string


 | In Object:
 | Misc


 | Parameters:
 | none


 |  Wait For Menu


 | Syntax
 |  Misc.WaitForMenu(int)


 | Description:


 | Pause script until server send menu, delay is in ms.


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | delayinms


 |  Menu Response


 | Syntax
 |  Misc.MenuResponse(string)


 | Description:


 | Perform a menu response by subitem name. If item not exist close menu


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | subitemname


## Query String


 |  Has Has QueryString


 | Syntax
 |  Misc.HasQueryString( )


 | Description:


 | Check if a have a query string menu opened, return true or false.


 | Returns
 | bool


 | In Object:
 | Misc


 | Parameters:
 | none


 |  Wait For Query String


 | Syntax
 |  Misc.WaitForQueryString(int)


 | Description:


 | Pause script until server send query string request, delay is in ms.


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | delayinms


 |  Query String Response


 | Syntax
 |  Misc.QueryStringResponse(bool, string)


 | Description:


 | Perform a query string response by ok or cancel button and specific response string.


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | stringtoresponse


## Script Function


 |  Run a Script


 | Syntax
 |  Misc.ScriptRun(string)


 | Description:


 | Run a script by file name, Script must be present in script grid.


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | scriptfilename


 |  Stop a Script


 | Syntax
 |  Misc.ScriptStop(string)


 | Description:


 | Stop a script by file name, Script must be present in script grid.


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | scriptfilename


 |  Stop all Script


 | Syntax
 |  Misc.ScriptStopAll( )


 | Description:


 | Stop all script running.


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | none


 |  Script Status


 | Syntax
 |  Misc.ScriptStatus(string)


 | Description:


 | Get status of script if running or not, Script must be present in script grid.


 | Returns
 | bool


 | In Object:
 | Misc


 | Parameters:
 | scriptfilename


## Maps


 |  Co-Ordinates of a Decoded Map


 | Syntax
 |  Misc.GetMapInfo(serial)


 | Description:


 |  Retrieve the co-ordinates of a decoded t-map. Your code would look like:


#
mapInfo = Misc.GetMapInfo(0x400BFD6C)
print("Treasure at ({}, {}), Origin ({}, {}), pin at ({}, {})"
    .format(mapInfo.MapOrigin.X+mapInfo.PinPosition.X, mapInfo.MapOrigin.Y+mapInfo.PinPosition.Y,
            mapInfo.MapOrigin.X, mapInfo.MapOrigin.Y, mapInfo.PinPosition.X, mapInfo.PinPosition.Y))
#


 | Note:
 | The pin position is an offset from the origin, so you have to add them to get absolute location


 | Returns
 | MapInfo{ PinPosition, MapOrigin, MapEnd }


 | In Object:
 | Misc


 | Parameters:
 | serial - Serial of the t-map


## Pets


 |  Rename Pet


 | Syntax
 |  Misc.PetRename(int or mobile, string )


 | Description:


 | Rename a specific pet.


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | newname


## String Prompt Response


 |  Reset Prompt response


 | Syntax
 |  Misc.ResetPrompt()


 | Description:


 | Reset a prompt response.


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | none


 |  Reset Prompt response


 | Syntax
 |  Misc.HasPrompt()


 | Description:


 | Check if have a prompt request.


 | Returns
 | bool


 | In Object:
 | Misc


 | Parameters:
 | none


 |  Wait Prompt


 | Syntax
 |  Misc.WaitForPrompt(int)


 | Description:


 | Wait a prompt response.


 | Returns
 | bool


 | In Object:
 | Misc


 | Parameters:
 | delaytowait


 |  Cancel Prompt


 | Syntax
 |  Misc.CancelPrompt()


 | Description:


 | Cancel a prompt request.


 | Returns
 | bool


 | In Object:
 | Misc


 | Parameters:
 | none


 |  Prompt Response


 | Syntax
 |  Misc.ResponsePrompt( string )


 | Description:


 | Response a prompt request.


 | Returns
 | bool


 | In Object:
 | Misc


 | Parameters:
 | reponsetosend


## Ignore List


 |  Add object to Ignore List


 | Syntax
 |  Misc.IgnoreObject( )


 | Description:


 | Add an object to ignore list. Can add serial, items or mobiles


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | mobtoignore


 |  Remove object from Ignore List


 | Syntax
 |  Misc.UnIgnoreObject( )


 | Description:


 | Remove object from ignore list. Can remove serial, items or mobiles


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | mobtounignore


 |  Check object if present in Ignore List


 | Syntax
 |  Misc.CheckIgnoreObject( )


 | Description:


 | Check object from ignore list, return true if present. Can check serial, items or mobiles


 | Returns
 | bool


 | In Object:
 | Misc


 | Parameters:
 | mobtocheck


 |  Clear ignore list


 | Syntax
 |  Misc.ClearIgnore( )


 | Description:


 | Clear ignore list from all object


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | none


 |  Change the current active profile


 | Syntax
 |  Misc.ChangeProfile(profileName )


 | Description:


 | CHanges the current active profile
use in your code like:


#
Misc.ChangeProfile("profileName")
#


 | Returns
 | void


 | In Object:
 | Misc


 | Parameters:
 | newProfileName


 |  Distance between 2 places using UO algorithm


 | Syntax
 |  Misc.Distance(X1, Y1, X2, Y2)


 | Description:


 |  Compute the distance between 2 places using UO algorithm for distance
use in your code like:


#
d = Misc.Distance(10, 10, 20, 20)
#


 | Returns
 | int


 | In Object:
 | Misc


 | Parameters:
 | X1 - x origin
 | Y1 - y origin
 | X2 - x dest
 | Y2 - y dest


---

# Gump Functions

gump_func [RazorEnhanced Wiki]

    


- 

- 

- 

- 

- 

- 

- 

- 

- 


    
- 

- 


    


            
- skip to content


#  RazorEnhanced Wiki


                    


### User Tools


                    
- Log In

            


        


### Site Tools


Search


ToolsShow pagesourceOld revisionsBacklinksRecent ChangesMedia ManagerSitemapLog In>


                
- Recent Changes
- Media Manager
- Sitemap            


            


Trace:


    


            


                
gump_func


                    

# This topic does not exist yet


You&#039;ve followed a link to a topic that doesn&#039;t exist yet. If permissions allow, you may create it by clicking on Create this page.


                                    


                


            


### Page Tools


                        
- Show pagesource

- Old revisions

- Backlinks

- Back to top

                


Except where otherwise noted, content on this wiki is licensed under the following license: GNU Free Documentation License 1.3


        

        

    


Exception: Git command failed to perform periodic pull: hint: Pulling without specifying how to reconcile divergent branches is
hint: discouraged. You can squelch this message by running one of the following
hint: commands sometime before your next pull:
hint: 
hint:   git config pull.rebase false  # merge (the default strategy)
hint:   git config pull.rebase true   # rebase
hint:   git config pull.ff only       # fast-forward only
hint: 
hint: You can replace "git config" with "git config --global" to set a default
hint: preference for all repositories. You can also pass --rebase, --no-rebase,
hint: or --ff-only on the command line to override the configured default per
hint: invocation.
Warning: Permanently added &#039;github.com,140.82.113.4&#039; (ECDSA) to the list of known hosts.
From github.com:RazorEnhanced/razorenhanced.github.io
 * branch            main       -> FETCH_HEAD
error: Your local changes to the following files would be overwritten by merge:
	doc/api/CUO.html
	doc/api/Gumps.html
	doc/api/Item.html
	doc/api/Items.html
	doc/api/Journal.html
	doc/api/Misc.html
	doc/api/Mobile.html
	doc/api/PacketLogger.html
	doc/api/PathFinding.html
	doc/api/Player.html
	doc/api/Spells.html
	doc/api/Target.html
	doc/api/Trade.html
	doc/api/Vendor.html
Please commit your changes or stash them before you merge.
Aborting


# Exception: Git command failed to perform periodic pull: hint: Pulling without specifying how to reconcile divergent branches is
hint: discouraged. You can squelch this message by running one of the following
hint: commands sometime before your next pull:
hint: 
hint:   git config pull.rebase false  # merge (the default strategy)
hint:   git config pull.rebase true   # rebase
hint:   git config pull.ff only       # fast-forward only
hint: 
hint: You can replace "git config" with "git config --global" to set a default
hint: preference for all repositories. You can also pass --rebase, --no-rebase,
hint: or --ff-only on the command line to override the configured default per
hint: invocation.
Warning: Permanently added &#039;github.com,140.82.113.4&#039; (ECDSA) to the list of known hosts.
From github.com:RazorEnhanced/razorenhanced.github.io
 * branch            main       -> FETCH_HEAD
error: Your local changes to the following files would be overwritten by merge:
	doc/api/CUO.html
	doc/api/Gumps.html
	doc/api/Item.html
	doc/api/Items.html
	doc/api/Journal.html
	doc/api/Misc.html
	doc/api/Mobile.html
	doc/api/PacketLogger.html
	doc/api/PathFinding.html
	doc/api/Player.html
	doc/api/Spells.html
	doc/api/Target.html
	doc/api/Trade.html
	doc/api/Vendor.html
Please commit your changes or stash them before you merge.
Aborting


An unforeseen error has occured. This is most likely a bug somewhere. It might be a problem in the gitbacked plugin.


More info has been written to the DokuWiki error log.


---

# Journal Functions

journal_func


- 

- 

- 

- 

- 

- 

- 

- 

- 

- 


### Table of Contents


- 
Scripting - Journal data and function


- 
Clear


- 
Search


- 
Get Data


- 
Wait for Journal


# Scripting - Journal data and function


Here can find some information about Enhanced Scripting function and data for journal operation!


## Clear


 |  Clear Journal


 | Syntax
 |  Journal.Clear( )


 | Description:


 | Clear data in journal buffer.


 | Returns
 | void


 | In Object:
 | Journal


 | Parameters:
 | none


## Search


 |  Search Journal


 | Syntax
 |  Journal.Search(string)


 | Description:


 | Search a string in all journal buffer, if present get true. String is case sensitive.


 | Returns
 | bool


 | In Object:
 | Journal


 | Parameters:
 | TextToSearch


 |  Search Journal by name


 | Syntax
 |  Journal.SearchByName(stringToLookFor, PlayerName)


 | Description:


 | Search for stringToLookFor in all journal buffer by sender name, if present get true. String and name is case sensitive.


 | Returns
 | bool


 | In Object:
 | Journal


 | Parameters:
 | stringToLookFor, senderName


 | Example
 | 


Journal.Clear()
while not Journal.SearchByName("Hello", "Credzba"):
    Misc.Pause(1000)


 |  Search Journal by color


 | Syntax
 |  Journal.SearchByColor(string, string)


 | Description:


 | Search a string in all journal buffer by font color, if present get true. String is case sensitive.


 | Returns
 | bool


 | In Object:
 | Journal


 | Parameters:
 | ColorToSearch


 |  Search Journal by message type


 | Syntax
 |  Journal.SearchByType(string, string)


 | Description:


 |  Search a string in all journal buffer by message type, if present get true. String and Type is case sensitive.


 | Returns
 | bool


 | In Object:
 | Journal


 | Parameters:
 | string TextToSearch, string MessageType


 | Parameters type list:
 | 


- 
 Regular


- 
 System


- 
 Emote


- 
 Label


- 
 Focus


- 
 Whisper


- 
 Yell


- 
 Spell


- 
 Guild


- 
 Alliance


- 
 Party


- 
 Encoded


- 
 Special


## Get Data


 |  Search and Get text line


 | Syntax
 |  Journal.GetLineText(string, optional bool)


 | Description:


 | Search and get last line whit searched string, if present return a string whit all text in line. String is case sensitive. Use optional bool true for add name of mobile or item send text.


 | Returns
 | string


 | In Object:
 | Journal


 | Parameters:
 | bool


 |  Get Speech Name


 | Syntax
 |  Journal.GetSpeechName()


 | Description:


 | Get a list of all name of player and object speech.


 | Returns
 | list (string)


 | In Object:
 | Journal


 | Parameters:
 | none


 |  Get Text by Type


 | Syntax
 |  Journal.GetTextByType(string, optional bool)


 | Description:


 | Get a list of all speech by specific type. Use optional bool true for add name of mobile or item send text.


 | Returns
 | list (string)


 | In Object:
 | Journal


 | Parameters:
 | string textType, optional bool addMobileId


 | TextTypes:
 | 


- 
 System


- 
 Emote


- 
 Label


- 
 Focus


- 
 Whisper


- 
 Yell


- 
 Spell


- 
 Guild


- 
 Alliance


 |  Get Text by Name


 | Syntax
 |  Journal.GetTextByName(string)


 | Description:


 | Get a list of all speech by specific player name.


 | Returns
 | list (string)


 | In Object:
 | Journal


 | Parameters:
 | name


 |  Get Text by Color


 | Syntax
 |  Journal.GetTextByColor(int, optional bool)


 | Description:


 | Get a list of all speech by specific color. Use optional bool true for add name of mobile or item send text.


 | Returns
 | list (string)


 | In Object:
 | Journal


 | Parameters:
 | bool


 |  Get Text by Serial


 | Syntax
 |  Journal.GetTextBySerial(int)


 | Description:


 | Get a list of all speech by specific serial.


 | Returns
 | list (string)


 | In Object:
 | Journal


 | Parameters:
 | serial


## Wait for Journal


 |  Wait for journal to have Text String


 | Syntax
 |  Journal.WaitJournal(string, int)


 | Description:


 | Pause script and wait when a text is present in journal. Text is case sensitive and max wait delay is in ms.


 | Returns
 | bool - True if string found, False - timeout


 | In Object:
 | Journal


 | Parameters:
 | MaxWaitTime


 | Example
 | 


Journal.WaitJournal("Hello", 20000)


 |  Wait for journal to have text from Name


 | Syntax
 |  Journal.WaitByName(Player/Mobile Name, int)


 | Description:


 | Pause script and wait for when a name sends text in journal. Text is case sensitive and max wait delay is in ms.


 | Returns
 | bool


 | In Object:
 | Journal


 | Parameters:
 | MaxWaitTime


 | Example
 | 


if Journal.WaitByName(Player.Name, 20000):
    Misc.SendMessage("FOUND IT")
else:
    Misc.SendMessage("TIME OUT")


---

# Statics Functions

statics_func


- 

- 

- 

- 

- 

- 

- 

- 

- 

- 


### Table of Contents


- 
Scripting - Statics data and function


- 
Land Information


- 
Statics Information


- 
Deed Information


# Scripting - Statics data and function


Here can find some information about Enhanced Scripting function and data for Statics and Map Information.


## Land Information


 |  Get Land ID


 | Syntax
 |  Statics.GetLandID(int, int, int)


 | Description:


 | Get ID of tile in X, Y coordinates and specific map.


 | Returns
 | Int


 | In Object:
 | Statics


 | Parameters:
 | mapID


 |  Get Land Name


 | Syntax
 |  Statics.GetLandName(int LandID)


 | Description:


 | Get Name of the land identified by LandID.


 | Returns
 | Int


 | In Object:
 | Statics


 | Parameters:
 | LandID


 |  Get Land X Level


 | Syntax
 |  Statics.GetLandZ(int, int, int)


 | Description:


 | Get Z Level of tile in X, Y coordinates and specific map.


 | Returns
 | Int


 | In Object:
 | Statics


 | Parameters:
 | mapID


 |  Get Land tile flag information


 | Syntax
 |  Statics.GetLandFlag(int, string)


 | Description:


 | Get true or false if flag is present for specific land itemID.


 | Returns
 | bool


 | In Object:
 | Statics


 | Parameters:
 | int itemid, string flagname


 | Possible flag to check:
 | 


- 
 None


- 
 Translucent


- 
 Wall


- 
 Damaging


- 
 Impassable


- 
 Surface


- 
 Bridge


- 
 Window


- 
 NoShoot


- 
 Foliage


- 
 HoverOver


- 
 Roof


- 
 Door


- 
 Wet


## Statics Information


 |  Get Static information on tile


 | Syntax
 |  Statics.GetStaticsTileInfo(int, int, int)


 | Description:


 | Get tiles info in a certain map at X, Y coordinates.
Tileinfo list contain all static item in specific tile whit this information: StaticID (Static item Grapics), StaticHue (Static item color), StaticZ (Static item Z Level).


 | Returns
 | List(TileInfo)


 | In Object:
 | Statics


 | Parameters:
 | int coordX, int coordY, int mapID


 |  Get Static tile name


 | Syntax
 |  Statics.GetTileName(int)


 | Description:


 | Get a tile name.
Tileinfo list contain all static item in specific tile with this information: StaticID (Static item Graphics), StaticHue (Static item color), StaticZ (Static item Z Level).


 | Returns
 | string


 | In Object:
 | Statics


 | Parameters:
 | int TileID


 |  Get Static tile flag information


 | Syntax
 |  Statics.GetTileFlag(int, string)


 | Description:


 | Get true or false if flag is present for specific itemID.


 | Returns
 | bool


 | In Object:
 | Statics


 | Parameters:
 | int itemid, string flagname


 | Possible flag to check:
 | 


- 
 None


- 
 Translucent


- 
 Wall


- 
 Damaging


- 
 Impassable


- 
 Surface


- 
 Bridge


- 
 Window


- 
 NoShoot


- 
 Foliage


- 
 HoverOver


- 
 Roof


- 
 Door


- 
 Wet


## Deed Information


 |  Check if exist deed house


 | Syntax
 |  Statics.CheckDeedHouse(int, int)


 | Description:


 | Get true or false if exist deed house in specific X, Y.


 | Returns
 | Bool


 | In Object:
 | Statics


 | Parameters:
 | coordY


---

# Target Functions

target_func


- 

- 

- 

- 

- 

- 

- 

- 

- 

- 


### Table of Contents


- 
Scripting - Targets data and function


- 
Target Status


- 
Wait Target


- 
Target Action


- 
Target Filter


# Scripting - Targets data and function


Here can find some information about Enhanced Scripting function and data for Target operation!


## Target Status


 |  Check Target


 | Syntax
 |  Target.HasTarget( )


 | Description:


 | Get status if have target cursor in game or not


 | Returns
 | bool


 | In Object:
 | Target


 | Parameters:
 | none


 |  Get Last Target Serial


 | Syntax
 |  Target.GetLast( )


 | Description:


 | Get serial number of last target


 | Returns
 | int


 | In Object:
 | Target


 | Parameters:
 | none


 |  Get Last Attack Serial


 | Syntax
 |  Target.GetLastAttack( )


 | Description:


 | Get serial number of last attack target


 | Returns
 | int


 | In Object:
 | Target


 | Parameters:
 | none


## Wait Target


 |  Wait For Target


 | Syntax
 |  Target.WaitForTarget(int, optional bool)


 | Description:


 | Pause script for wait server send target request. Must set a pause limit in ms. and optional flag True or False. True Not show cursor, false show it


 | Returns
 | void


 | In Object:
 | Target


 | Parameters:
 | int Pause, bool BlockCursor


## Target Action


 |  Target Relative


 | Syntax
 |  Target.TargetExecuteRelative(int or mobile, int)


 | Description:


 | Send target execute to specific land point whit offset distance from mobile. Distance is calculated by target mobile direction.


 | Returns
 | void


 | In Object:
 | Target


 | Parameters:
 | int Serial or Mobile Mobiletarget, int offset


 |  Target Execute


 | Syntax
 |  Target.TargetExecute(int or item or mobile or int, int, int)


 | Description:


 | Send target execute to specific serial, item, mobile, X Y Z point.


 | Returns
 | void


 | In Object:
 | Target


 | Parameters:
 | int Serial or Item ItemtoTarget or Mobile Mobile to target or Point3D StaticCoords or int XCoord, int YCoord, int ZLevel


 |  Target Resource


 | Syntax
 |  Target.TargetResource(serial or item, string)


 | Description:


 | Find and target a resource using the item specified as first parameter.


 | Returns
 | void


 | In Object:
 | Target


 | Parameters:
 | int Serial or Item Itemt to use, string resourceName to target can be one of &#039;ore&#039;, &#039;sand&#039;, &#039;wood&#039;, &#039;graves&#039;, &#039;red mushrooms&#039; or possibly some server based extensions


 | Example:


Target.TargetResource(0x123456, "ore")


 |  Prompt Target


 | Syntax
 |  Target.PromptTarget(none or string)


 | Description:


 | Pick the serial from item or mobile. Can also specific a text message for prompt


 | Returns
 | int


 | In Object:
 | Target


 | Parameters:
 | none or string stringmessage


 |  Prompt Target Ground Position


 | Syntax
 |  Target.PromptGroundTarget(none or string)


 | Description:


 | Pick the coords from ground target. Can also specific a text message for prompt


 | Returns
 | point3d


 | In Object:
 | Target


 | Parameters:
 | none or string stringmessage


 |  Cancel Target


 | Syntax
 |  Target.Cancel( )


 | Description:


 | Cancel target cursor.


 | Returns
 | void


 | In Object:
 | Target


 | Parameters:
 | none


 |  Last Target


 | Syntax
 |  Target.Last( )


 | Description:


 | Target last object or mobile targetted.


 | Returns
 | void


 | In Object:
 | Target


 | Parameters:
 | none


 |  Last Target Queued


 | Syntax
 |  Target.LastQueued( )


 | Description:


 | Queue next target to Last.


 | Returns
 | void


 | In Object:
 | Target


 | Parameters:
 | none


 |  Last Self


 | Syntax
 |  Target.Self( )


 | Description:


 | Target Self.


 | Returns
 | void


 | In Object:
 | Target


 | Parameters:
 | none


 |  Last Self Queued


 | Syntax
 |  Target.SelfQueued( )


 | Description:


 | Queue Next target to Self.


 | Returns
 | void


 | In Object:
 | Target


 | Parameters:
 | none


 |  Set Last Target


 | Syntax
 |  Target.SetLast(mobile or int)


 | Description:


 | Force set last target to specific mobile, by mobile type or serial.


 | Returns
 | void


 | In Object:
 | Target


 | Parameters:
 | mobile MobileTarget or int SerialTarget


 |  Clear Last Attack Target


 | Syntax
 |  Target.ClearLastAttack( )


 | Description:


 | Clear Last Attacked Target.


 | Returns
 | void


 | In Object:
 | Target


 | Parameters:
 | none


 |  Clear Last Target


 | Syntax
 |  Target.ClearLast( )


 | Description:


 | Clear Last Target.


 | Returns
 | void


 | In Object:
 | Target


 | Parameters:
 | none


 |  Clear Queue Target


 | Syntax
 |  Target.ClearQueue( )


 | Description:


 | Clear Queue Target.


 | Returns
 | void


 | In Object:
 | Target


 | Parameters:
 | none


 |  Clear Last and Queue Target


 | Syntax
 |  Target.ClearLastandQueue( )


 | Description:


 | Clear Last and Queue Target.


 | Returns
 | void


 | In Object:
 | Target


 | Parameters:
 | none


## Target Filter


 |  Set last Target Filter


 | Syntax
 |  Target.SetLastTargetFromList(String)


 | Description:


 | Set Last Target from gui filter selector.


 | Returns
 | void


 | In Object:
 | Target


 | Parameters:
 | String TargetFilterName


 |  Perform Target Filter


 | Syntax
 |  Target.PerformTargetFromList(string)


 | Description:


 | Execute Target from gui filter selector.


 | Returns
 | void


 | In Object:
 | Target


 | Parameters:
 | String TargetFilterName


 |  Attack Target Filter


 | Syntax
 |  Target.AttackTargetFromList(string)


 | Description:


 | Attack Target from gui filter selector.


 | Returns
 | void


 | In Object:
 | Target


 | Parameters:
 | String TargetFilterName


 |  Get Target from Filter


 | Syntax
 |  Target.GetTargetFromList(string)


 | Description:


 | Get Mobile object from GUI Filter selector. If no mobile found return null


 | Returns
 | mobile


 | In Object:
 | Target


 | Parameters:
 | String TargetFilterName


---

# Timer Functions

timer_func


- 

- 

- 

- 

- 

- 

- 

- 

- 

- 


### Table of Contents


- 
Scripting - Timer control function


- 
Timer Create


- 
Timer Check


# Scripting - Timer control function


## Timer Create


 |  Create a Named Timer


 | Syntax
 |  Timer.Create(string TimerName, int ms_timer )


 | Description:


 | Create a timer with the provided name that will expire in ms_timer time (in milliseconds)


 | Returns
 | void


 | In Object:
 | Timer


 | Parameters:
 | none


 | Example:


Timer.Create("Test", 5000)


## Timer Check


 |  Get remaining time for a named timer


 | Syntax
 |  Timer.Remaining(string TimerName)


 | Description:


 |  Returns the milliseconds remaining for a timer


 | Returns
 |  int ms_time


 | In Object:
 | Timer


 | Parameters:
 | string TimerName


 | Example:


Timer.Create("Test", 5000)
#
while Timer.Check("Test"):
    remain = Timer.Remaining("Test")
    Misc.SendMessage("TimeLeft: {}".format(remain))
    Misc.Pause(500


 |  Check if a timer is expired or not


 | Syntax
 |  Timer.Check(string TimerName)


 | Description:


 | Check if a timer object is expired or not,


 | Returns
 | bool - True if not expired, false if expired


 | In Object:
 | Timer


 | Parameters:
 | string TimerName


---

# Razor (markdwags) Scripting Commands

> Source: https://github.com/markdwags/Razor (fetched 2026-03-27)


## Commands (`razor_Commands.cs`)

```csharp
﻿#region license
// Razor: An Ultima Online Assistant
// Copyright (c) 2022 Razor Development Community on GitHub <https://github.com/markdwags/Razor>
// 
// This program is free software: you can redistribute it and/or modify
// it under the terms of the GNU General Public License as published by
// the Free Software Foundation, either version 3 of the License, or
// (at your option) any later version.
// 
// This program is distributed in the hope that it will be useful,
// but WITHOUT ANY WARRANTY; without even the implied warranty of
// MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
// GNU General Public License for more details.
// 
// You should have received a copy of the GNU General Public License
// along with this program.  If not, see <http://www.gnu.org/licenses/>.
#endregion

using System;
using System.Collections.Generic;
using System.Drawing;
using System.Linq;
using System.Text;
using Assistant.Core;
using Assistant.HotKeys;
using Assistant.Scripts.Engine;
using Assistant.Scripts.Helpers;
using Ultima;

namespace Assistant.Scripts
{
    public static class Commands
    {
        public static void Register()
        {
            // Commands based on Actions.cs
            Interpreter.RegisterCommandHandler("attack", Attack); //Attack by serial
            Interpreter.RegisterCommandHandler("cast", Cast); //BookcastAction, etc

            // Dress
            Interpreter.RegisterCommandHandler("dress", DressCommand); //DressAction
            Interpreter.RegisterCommandHandler("undress", UnDressCommand); //UndressAction

            // Using stuff
            Interpreter.RegisterCommandHandler("dclicktype", DClickType); // DoubleClickTypeAction
            Interpreter.RegisterCommandHandler("dclick", DClick); //DoubleClickAction

            Interpreter.RegisterCommandHandler("usetype", DClickType); // DoubleClickTypeAction
            Interpreter.RegisterCommandHandler("useobject", DClick); //DoubleClickAction

            // Moving stuff
            Interpreter.RegisterCommandHandler("drop", DropItem); //DropAction
            Interpreter.RegisterCommandHandler("droprelloc", DropRelLoc); //DropAction
            Interpreter.RegisterCommandHandler("lift", LiftItem); //LiftAction
            Interpreter.RegisterCommandHandler("lifttype", LiftType); //LiftTypeAction

            // Gump
            Interpreter.RegisterCommandHandler("waitforgump", WaitForGump); // WaitForGumpAction
            Interpreter.RegisterCommandHandler("gumpresponse", GumpResponse); // GumpResponseAction
            Interpreter.RegisterCommandHandler("gumpclose", GumpClose); // GumpResponseAction

            // Menu
            Interpreter.RegisterCommandHandler("menu", ContextMenu); //ContextMenuAction
            Interpreter.RegisterCommandHandler("menuresponse", MenuResponse); //MenuResponseAction
            Interpreter.RegisterCommandHandler("waitformenu", WaitForMenu); //WaitForMenuAction

            // Prompt
            Interpreter.RegisterCommandHandler("promptresponse", PromptResponse); //PromptAction
            Interpreter.RegisterCommandHandler("waitforprompt", WaitForPrompt); //WaitForPromptAction

            // Hotkey execution
            Interpreter.RegisterCommandHandler("hotkey", Hotkey); //HotKeyAction

            

            Interpreter.RegisterCommandHandler("overhead", OverheadMessage); //OverheadMessageAction
            Interpreter.RegisterCommandHandler("headmsg", OverheadMessage); //OverheadMessageAction
            Interpreter.RegisterCommandHandler("sysmsg", SystemMessage); //SystemMessageAction
            Interpreter.RegisterCommandHandler("clearsysmsg", ClearSysMsg); //SystemMessageAction
            Interpreter.RegisterCommandHandler("clearjournal", ClearSysMsg); //SystemMessageAction

            // General Waits/Pauses
            Interpreter.RegisterCommandHandler("wait", Pause); //PauseAction
            Interpreter.RegisterCommandHandler("pause", Pause); //PauseAction
            Interpreter.RegisterCommandHandler("waitforsysmsg", WaitForSysMsg);
            Interpreter.RegisterCommandHandler("wfsysmsg", WaitForSysMsg);

            // Misc
            Interpreter.RegisterCommandHandler("setability", SetAbility); //SetAbilityAction
            Interpreter.RegisterCommandHandler("setlasttarget", SetLastTarget); //SetLastTargetAction
            Interpreter.RegisterCommandHandler("lasttarget", LastTarget); //LastTargetAction
            Interpreter.RegisterCommandHandler("skill", UseSkill); //SkillAction
            Interpreter.RegisterCommandHandler("useskill", UseSkill); //SkillAction
            Interpreter.RegisterCommandHandler("walk", Walk); //Move/WalkAction
            Interpreter.RegisterCommandHandler("potion", Potion);

            // Script related
            Interpreter.RegisterCommandHandler("script", PlayScript);
            Interpreter.RegisterCommandHandler("setvar", SetVar);
            Interpreter.RegisterCommandHandler("setvariable", SetVar);
            Interpreter.RegisterCommandHandler("unsetvar", UnsetVar);
            Interpreter.RegisterCommandHandler("unsetvariable", UnsetVar);

            Interpreter.RegisterCommandHandler("stop", Stop);

            Interpreter.RegisterCommandHandler("clearall", ClearAll);

            Interpreter.RegisterCommandHandler("clearhands", ClearHands);

            Interpreter.RegisterCommandHandler("virtue", Virtue);

            Interpreter.RegisterCommandHandler("random", Random);

            Interpreter.RegisterCommandHandler("cleardragdrop", ClearDragDrop);
            Interpreter.RegisterCommandHandler("interrupt", Interrupt);

            Interpreter.RegisterCommandHandler("sound", Sound);
            Interpreter.RegisterCommandHandler("music", Music);

            Interpreter.RegisterCommandHandler("classicuo", ClassicUOProfile);
            Interpreter.RegisterCommandHandler("cuo", ClassicUOProfile);
            
            Interpreter.RegisterCommandHandler("rename", Rename);
            
            Interpreter.RegisterCommandHandler("getlabel", GetLabel);
            
            Interpreter.RegisterCommandHandler("ignore", AddIgnore);
            Interpreter.RegisterCommandHandler("unignore", RemoveIgnore);
            Interpreter.RegisterCommandHandler("clearignore", ClearIgnore);
            
            Interpreter.RegisterCommandHandler("cooldown", Cooldown);
            
            Interpreter.RegisterCommandHandler("poplist", PopList);
            Interpreter.RegisterCommandHandler("pushlist", PushList);
            Interpreter.RegisterCommandHandler("removelist", RemoveList);
            Interpreter.RegisterCommandHandler("createlist", CreateList);
            Interpreter.RegisterCommandHandler("clearlist", ClearList);
            
            Interpreter.RegisterCommandHandler("settimer", SetTimer);
            Interpreter.RegisterCommandHandler("removetimer", RemoveTimer);
            Interpreter.RegisterCommandHandler("createtimer", CreateTimer);
        }
        
        private static bool PopList(string command, Variable[] args, bool quiet, bool force)
        {
            if (args.Length != 2)
                throw new RunTimeError("Usage: poplist ('list name') ('element value'/'front'/'back')");

            if (args[1].AsString() == "front")
            {
                if (force)
                    while (Interpreter.PopList(args[0].AsString(), true, out _)) { }
                else
                    Interpreter.PopList(args[0].AsString(), true, out _);
            }
            else if (args[1].AsString() == "back")
            {
                if (force)
                    while (Interpreter.PopList(args[0].AsString(), false, out _)) { }
                else
                    Interpreter.PopList(args[0].AsString(), false, out _);
            }
            else
            {
                var evaluatedVar = new Variable(args[1].AsString());
                if (force)
                {
                    while (Interpreter.PopList(args[0].AsString(), evaluatedVar)) { }
                }
                else
                    Interpreter.PopList(args[0].AsString(), evaluatedVar);
            }

            return true;
        }

        private static bool PushList(string command, Variable[] args, bool quiet, bool force)
        {
            if (args.Length < 2 || args.Length > 3)
                throw new RunTimeError("Usage: pushlist ('list name') ('element value') ['front'/'back']");

            bool front = false;
            if (args.Length == 3)
            {
                if (args[2].AsString() == "front")
                    front = true;
            }

            Interpreter.PushList(args[0].AsString(), new Variable(args[1].AsString()), front, force);

            return true;
        }

        private static bool RemoveList(string command, Variable[] args, bool quiet, bool force)
        {
            if (args.Length != 1)
                throw new RunTimeError("Usage: removelist ('list name')");

            Interpreter.DestroyList(args[0].AsString());

            return true;
        }

        private static bool CreateList(string command, Variable[] args, bool quiet, bool force)
        {
            if (args.Length != 1)
                throw new RunTimeError("Usage: createlist ('list name')");

            Interpreter.CreateList(args[0].AsString());

            return true;
        }

        private static bool ClearList(string command, Variable[] args, bool quiet, bool force)
        {
            if (args.Length != 1)
                throw new RunTimeError("Usage: clearlist ('list name')");

            Interpreter.ClearList(args[0].AsString());

            return true;
        }

        private static bool SetTimer(string command, Variable[] args, bool quiet, bool force)
        {
            if (args.Length != 2)
                throw new RunTimeError("Usage: settimer (timer name) (value)");


            Interpreter.SetTimer(args[0].AsString(), args[1].AsInt());
            return true;
        }

        private static bool RemoveTimer(string command, Variable[] args, bool quiet, bool force)
        {
            if (args.Length != 1)
                throw new RunTimeError("Usage: removetimer (timer name)");

            Interpreter.RemoveTimer(args[0].AsString());
            return true;
        }

        private static bool CreateTimer(string command, Variable[] args, bool quiet, bool force)
        {
            if (args.Length != 1)
                throw new RunTimeError("Usage: createtimer (timer name)");

            Interpreter.CreateTimer(args[0].AsString());
            return true;
        }

        private static bool Cooldown(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 2)
            {
                throw new RunTimeError("Usage: cooldown ('name') ('seconds') ['hue'] ['icon'] ['sound'] ['stay visible'] ['foreground color'] ['background color']");
            }

            string name = vars[0].AsString();
            int seconds = vars[1].AsInt();
            
            int hue = 0, sound = 0;
            string icon = "none";
            bool stay = false;
            
            Color foreColor = Color.Empty;
            Color backColor = Color.Empty;
            
            switch (vars.Length)
            {
                case 3:
                    hue = vars[2].AsInt();

                    break;
                case 4:
                    hue = vars[2].AsInt();
                    icon = vars[3].AsString();

                    break;
                case 5:
                    hue = vars[2].AsInt();
                    icon = vars[3].AsString();
                    sound = vars[4].AsInt();

                    break;
                case 6:
                    hue = vars[2].AsInt();
                    icon = vars[3].AsString();
                    sound = vars[4].AsInt();
                    stay = vars[5].AsBool();

                    break;
                case 7:
                    hue = vars[2].AsInt();
                    icon = vars[3].AsString();
                    sound = vars[4].AsInt();
                    stay = vars[5].AsBool();

                    foreColor = Color.FromName(vars[6].AsString());

                    break;
                case 8:
                    hue = vars[2].AsInt();
                    icon = vars[3].AsString();
                    sound = vars[4].AsInt();
                    stay = vars[5].AsBool();

                    foreColor = Color.FromName(vars[6].AsString());
                    backColor = Color.FromName(vars[7].AsString());

                    break;
            }
            
            CooldownManager.AddCooldown(new Cooldown
            {
                Name = name,
                EndTime = DateTime.UtcNow.AddSeconds(seconds),
                Hue = hue,
                Icon = icon.Equals("0") ? 0 : BuffDebuffManager.GetGraphicId(icon),
                Seconds = seconds,
                SoundId = sound,
                StayVisible = stay,
                ForegroundColor = foreColor,
                BackgroundColor = backColor
            });

            return true;
        }
        
        private enum GetLabelState
        {
            None,
            WaitingForFirstLabel,
            WaitingForRemainingLabels
        };
        
        private static GetLabelState _getLabelState = GetLabelState.None;
        private static Action<Packet, PacketHandlerEventArgs, Serial, ushort, MessageType, ushort, ushort, string, string, string> _onLabelMessage;
        private static Action _onStop;
        
        private static bool GetLabel(string command, Variable[] args, bool quiet, bool force)
        {
            if (args.Length != 2)
                throw new RunTimeError("Usage: getlabel (serial) (name)");

            var serial = args[0].AsSerial();
            var name = args[1].AsString(false);

            var mobile = World.FindMobile(serial);
            if (mobile != null)
            {
                if (mobile.IsHuman)
                {
                    return false;
                }
            }

            switch (_getLabelState)
            {
                case GetLabelState.None:
                    _getLabelState = GetLabelState.WaitingForFirstLabel;
                    Interpreter.Timeout(2000, () =>
                    {
                        MessageManager.OnLabelMessage -= _onLabelMessage;
                        _onLabelMessage = null;
                        Interpreter.OnStop -= _onStop;
                        _getLabelState = GetLabelState.None;
                        MessageManager.GetLabelCommand = false;
                        return true;
                    });

                    // Single click the object
                    Client.Instance.SendToServer(new SingleClick((Serial)args[0].AsSerial()));

                    // Capture all message responses
                    StringBuilder label = new StringBuilder();
                    
                    // Some messages from Outlands server are send in sequence of LabelType and RegularType
                    // so we want to invoke that _onLabelMessage in both cases with delays
                    MessageManager.GetLabelCommand = true;

                    // Reset the state when script is stopped
                    _onStop = () =>
                    {
                        if (_onLabelMessage != null)
                        {
                            MessageManager.OnLabelMessage -= _onLabelMessage;
                            _onLabelMessage = null;
                        }
                        _getLabelState = GetLabelState.None;
                        
                        Interpreter.OnStop -= _onStop;
                        MessageManager.GetLabelCommand = false;
                    };

                    _onLabelMessage = (p, a, source, graphic, type, hue, font, lang, sourceName, text) =>
                    {
                        if (source != serial)
                            return;

                        a.Block = true;

                        if (_getLabelState == GetLabelState.WaitingForFirstLabel)
                        {
                            // After the first message, switch to a pause instead of a timeout.
                            _getLabelState = GetLabelState.WaitingForRemainingLabels;
                            Interpreter.Pause(500);
                        }

                        label.Append(" " + text);

                        Interpreter.SetVariable(name, label.ToString().Trim());
                    };

                    Interpreter.OnStop += _onStop;
                    MessageManager.OnLabelMessage += _onLabelMessage;
                    
                    break;
                case GetLabelState.WaitingForFirstLabel:
                    break;
                case GetLabelState.WaitingForRemainingLabels:
                    // We get here after the pause has expired.
                    Interpreter.OnStop -= _onStop;
                    MessageManager.OnLabelMessage -= _onLabelMessage;
                    
                    _onLabelMessage = null;
                    _getLabelState = GetLabelState.None;
                    
                    MessageManager.GetLabelCommand = false;
                    
                    return true;
            }

            return false;
        }

        private static bool Rename(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 2)
            {
                throw new RunTimeError("Usage: rename (serial) (new_name)");
            }

            string newName = vars[1].AsString();
            
            if (newName.Length < 1)
            {
                throw new RunTimeError("Mobile name must be longer than one character");
            }

            if (World.Mobiles.TryGetValue(vars[0].AsSerial(), out var follower))
            {
                if (follower.CanRename)
                {
                    PlayerData.RenameMobile(follower.Serial, newName);
                }
                else
                {
                    CommandHelper.SendMessage("Unable to rename mobile", quiet);
                }
            }
            
            return true;
        }

        private static bool ClassicUOProfile(string commands, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length != 2)
            {
                throw new RunTimeError("Usage: cuo (setting) (value)");
            }

            string property = ClassicUOManager.IsValidProperty(vars[0].AsString());

            if (string.IsNullOrEmpty(property))
            {
                throw new RunTimeError("Unknown ClassicUO setting/property. Type `>cuo list` for a list of valid settings.");
            }

            bool isNumeric = int.TryParse(vars[0].AsString(), out var value);

            if (isNumeric)
            {
                ClassicUOManager.ProfilePropertySet(property, value);
            }
            else
            {
                switch (vars[1].AsString())
                {
                    case "true":
                        ClassicUOManager.ProfilePropertySet(property, true);
                        break;
                    case "false":
                        ClassicUOManager.ProfilePropertySet(property, false);
                        break;
                    default:
                        ClassicUOManager.ProfilePropertySet(property, vars[1].AsString());
                        break;
                }
            }

            CommandHelper.SendMessage($"ClassicUO Setting: '{property}' set to '{vars[1].AsString()}'", quiet);

            return true;
        }

        private static bool Sound(string commands, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length != 1)
            {
                throw new RunTimeError("Usage: sound (serial)");
            }

            Client.Instance.SendToClient(new PlaySound(vars[0].AsInt()));

            return true;
        }

        private static bool Music(string commands, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length != 1)
            {
                throw new RunTimeError("Usage: music (id)");
            }

            Client.Instance.SendToClient(new PlayMusic(vars[0].AsUShort()));

            return true;
        }

        private static bool AddIgnore(string commands, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length != 1)
                throw new RunTimeError("Usage: ignore (serial)");

            Variable toIgnore = vars[0];
            string ignoreListName = vars[0].AsString();
            
            if (Interpreter.ListExists(ignoreListName))
            {
                List<Serial> list = Interpreter.GetList(ignoreListName).Select(v => (Serial)v.AsSerial()).ToList();
                Interpreter.AddIgnoreRange(list);
                CommandHelper.SendMessage($"Added {list.Count} entries to ignore list", quiet);
            }
            else
            {
                uint serial = toIgnore.AsSerial();
                Interpreter.AddIgnore(serial);
                CommandHelper.SendMessage($"Added {serial} to ignore list", quiet);
            }
            
            return true;
        }
        
        private static bool RemoveIgnore(string commands, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length != 1)
                throw new RunTimeError("Usage: unignore (serial or list)");
            
            Variable toIgnore = vars[0];
            string ignoreListName = toIgnore.AsString();
            
            if (Interpreter.ListExists(ignoreListName))
            {
                List<Serial> list = Interpreter.GetList(ignoreListName).Select(v => (Serial)v.AsSerial()).ToList();
                Interpreter.RemoveIgnoreRange(list);
                CommandHelper.SendMessage($"Removed {list.Count} entries from ignore list", quiet);
            }
            else
            {
                uint serial = toIgnore.AsSerial();
                Interpreter.RemoveIgnore(serial);
                CommandHelper.SendMessage($"Removed {serial} from ignore list", quiet);
            }
            
            return true;
        }

        private static bool ClearIgnore(string commands, Variable[] vars, bool quiet, bool force)
        {
            Interpreter.ClearIgnore();

            CommandHelper.SendMessage("Ignore List cleared", quiet);

            return true;
        }

        private static readonly string[] Virtues = { "honor", "sacrifice", "valor" };

        private static bool Virtue(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length == 0 || !Virtues.Contains(vars[0].AsString()))
            {
                throw new RunTimeError("Usage: virtue ('honor'/'sacrifice'/'valor')");
            }

            switch (vars[0].AsString())
            {
                case "honor":
                    PlayerData.InvokeVirtue(PlayerData.InvokeVirtues.Honor);
                    break;
                case "sacrifice":
                    PlayerData.InvokeVirtue(PlayerData.InvokeVirtues.Sacrifice);
                    break;
                case "valor":
                    PlayerData.InvokeVirtue(PlayerData.InvokeVirtues.Valor);
                    break;
            }

            return true;
        }

        private static bool ClearAll(string command, Variable[] vars, bool quiet, bool force)
        {

            DragDropManager.GracefulStop(); // clear drag/drop queue
            Targeting.CancelTarget(); // clear target queue & cancel current target
            DragDropManager.DropCurrent(); // drop what you are currently holding

            return true;
        }

        private static bool SetLastTarget(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length == 0)
            {
                throw new RunTimeError("Usage: setlasttarget ('serial')");
            }
            
            Serial serial = vars[0].AsSerial();

            if (serial != Serial.Zero)
            {
                Mobile mobile = World.FindMobile(serial);

                if (mobile != null)
                {
                    Targeting.SetLastTarget(mobile);
                    return true;
                }
                    
                Item item = World.FindItem(serial);

                if (item != null)
                {
                    Targeting.SetLastTarget(item);
                    return true;
                }

                Targeting.SetLastTarget(serial);
            }

            return true;
        }
        
        private enum SetVarState
        {
            INITIAL_PROMPT,
            WAIT_FOR_TARGET,
            COMPLETE,
        };

        private static SetVarState _setVarState = SetVarState.INITIAL_PROMPT;

        private static bool SetVar(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 1 || vars.Length > 2)
            {
                throw new RunTimeError("Usage: setvar ('variable') [serial] [timeout]");
            }

            string name = vars[0].AsString(false);

            if (vars.Length == 2)
            {
                // No need to target anything. We have the serial.
                var serial = vars[1].AsSerial();

                if (force)
                {
                    Interpreter.SetVariable(name, serial.ToString(), true);
                    return true;
                }

                if (ScriptVariables.GetVariable(name) == Serial.MinusOne && !quiet)
                {
                    CommandHelper.SendMessage($"'{name}' not found, creating new variable", quiet);
                }

                ScriptVariables.RegisterVariable(name, serial);
                CommandHelper.SendMessage($"'{name}' script variable updated to '{serial}'", quiet);

                Assistant.Engine.MainWindow.SaveScriptVariables();

                return true;
            }

            Interpreter.Timeout(vars.Length == 2 ? vars[1].AsUInt() : 30000, () => { _setVarState = SetVarState.INITIAL_PROMPT; return true; } );

            switch (_setVarState)
            {
                case SetVarState.INITIAL_PROMPT:
                    if (ScriptVariables.GetVariable(name) == Serial.MinusOne)
                    {
                        CommandHelper.SendMessage($"'{name}' not found, creating new variable", quiet);
                    }
                    World.Player.SendMessage(MsgLevel.Force, $"Select target for variable '{name}'");

                    _setVarState = SetVarState.WAIT_FOR_TARGET;

                    Targeting.OneTimeTarget((ground, serial, pt, gfx) =>
                    {
                        ScriptVariables.RegisterVariable(name, serial);
                        CommandHelper.SendMessage($"'{name}' script variable updated to '{serial}'", quiet);

                        Assistant.Engine.MainWindow.SaveScriptVariables();
                        _setVarState = SetVarState.COMPLETE;
                    },
                    () =>
                    {
                        _setVarState = SetVarState.COMPLETE;
                    });
                    break;
                case SetVarState.WAIT_FOR_TARGET:
                    break;
                case SetVarState.COMPLETE:
                    _setVarState = SetVarState.INITIAL_PROMPT;
                    return true;
            }

            return false;
        }
        
        private static bool UnsetVar(string expression, Variable[] args, bool quiet, bool force)
        {
            if (args.Length != 1)
                throw new RunTimeError("Usage: unsetvar ('name')");

            var name = args[0].AsString(false);

            if (force)
            {
                if (quiet)
                {
                    Interpreter.ClearVariable(name);
                }
                else
                {
                    Interpreter.ClearAlias(name);
                }
            }
            else
            {
                ScriptVariables.UnregisterVariable(name);
                ScriptManager.RedrawScripts();
            }

            return true;
        }


        private static bool Stop(string command, Variable[] vars, bool quiet, bool force)
        {
            ScriptManager.StopScript();

            return true;
        }

        private static bool Hotkey(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 1)
            {
                throw new RunTimeError("Usage: hotkey ('name of hotkey') OR (hotkeyId)");
            }

            string query = vars[0].AsString();

            KeyData hk = HotKey.GetByNameOrId(query);

            if (hk == null)
            {
                throw new RunTimeError($"{command} - Hotkey '{query}' not found");
            }

            hk.Callback();

            return true;
        }

        private static bool WaitForGump(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 1)
            {
                throw new RunTimeError("Usage: waitforgump (gumpId/'any') [timeout]");
            }

            uint gumpId = 0;
            bool strict = false;

            if (vars[0].AsString().IndexOf("any", StringComparison.OrdinalIgnoreCase) != -1)
            {
                strict = false;
            }
            else
            {
                gumpId = Utility.ToUInt32(vars[0].AsString(), 0);

                if (gumpId > 0)
                {
                    strict = true;
                }
            }

            Interpreter.Timeout(vars.Length == 2 ? vars[1].AsUInt() : 30000, () => { return true; });

            if ((World.Player.HasGump || World.Player.HasCompressedGump) &&
                (World.Player.CurrentGumpI == gumpId || !strict || gumpId == 0))
            {
                Interpreter.ClearTimeout();
                return true;
            }

            return false;
        }

        private static bool WaitForMenu(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 1)
            {
                throw new RunTimeError("Usage: waitformenu (menuId/'any') [timeout]");
            }

            uint menuId = 0;

            // Look for a specific menu
            menuId = vars[0].AsString().IndexOf("any", StringComparison.OrdinalIgnoreCase) != -1
                ? 0
                : Utility.ToUInt32(vars[0].AsString(), 0);

            Interpreter.Timeout(vars.Length == 2 ? vars[1].AsUInt() : 30000, () => { return true; });

            if (World.Player.HasMenu && (World.Player.CurrentGumpI == menuId || menuId == 0))
            {
                Interpreter.ClearTimeout();
                return true;
            }

            return false;
        }

        private static bool WaitForPrompt(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 1)
            {
                throw new RunTimeError("Usage: waitforprompt (promptId/'any') [timeout]");
            }

            uint promptId = 0;
            bool strict = false;

            // Look for a specific prompt
            if (vars[0].AsString().IndexOf("any", StringComparison.OrdinalIgnoreCase) != -1)
            {
                strict = false;
            }
            else
            {
                promptId = Utility.ToUInt32(vars[0].AsString(), 0);

                if (promptId > 0)
                {
                    strict = true;
                }
            }

            Interpreter.Timeout(vars.Length == 2 ? vars[1].AsUInt() : 30000, () => { return true; });

            if (World.Player.HasPrompt && (World.Player.PromptID == promptId || !strict || promptId == 0))
            {
                Interpreter.ClearTimeout();
                return true;
            }

            return false;
        }

        private static readonly string[] Abilities = {"primary", "secondary", "stun", "disarm"};

        private static bool SetAbility(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 1 || !Abilities.Contains(vars[0].AsString()))
            {
                throw new RunTimeError("Usage: setability ('primary'/'secondary'/'stun'/'disarm') ['on'/'off']");
            }

            if (vars.Length == 2 && vars[1].AsString() == "on" || vars.Length == 1)
            {
                switch (vars[0].AsString())
                {
                    case "primary":
                        SpecialMoves.SetPrimaryAbility();
                        break;
                    case "secondary":
                        SpecialMoves.SetSecondaryAbility();
                        break;
                    case "stun":
                        Client.Instance.SendToServer(new StunRequest());
                        break;
                    case "disarm":
                        Client.Instance.SendToServer(new DisarmRequest());
                        break;
                }
            }
            else if (vars.Length == 2 && vars[1].AsString() == "off")
            {
                Client.Instance.SendToServer(new UseAbility(AOSAbility.Clear));
                Client.Instance.SendToClient(ClearAbility.Instance);
            }

            return true;
        }

        private static readonly string[] Hands = {"left", "right", "both", "hands"};

        private static bool ClearHands(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length == 0 || !Hands.Contains(vars[0].AsString()))
            {
                throw new RunTimeError("Usage: clearhands ('left'/'right'/'both')");
            }

            switch (vars[0].AsString())
            {
                case "left":
                    Dress.Unequip(Layer.LeftHand);
                    break;
                case "right":
                    Dress.Unequip(Layer.RightHand);
                    break;
                default:
                    Dress.Unequip(Layer.LeftHand);
                    Dress.Unequip(Layer.RightHand);
                    break;
            }

            return true;
        }

        private static bool DClickType(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length == 0)
            {
                throw new RunTimeError("Usage: dclicktype ('name of item'/'graphicID') [inrangecheck (true/false)/backpack] [hue]");
            }

            string gfxStr = vars[0].AsString();
            Serial gfx = Utility.ToUInt16(gfxStr, 0);
            List<Item> items;
            List<Mobile> mobiles = new List<Mobile>();

            bool inRangeCheck = false;
            bool backpack = false;
            int hue = -1;

            if (vars.Length > 1)
            {
                if (vars.Length == 3)
                {
                    hue = vars[2].AsInt();
                }

                if (vars[1].AsString().IndexOf("pack", StringComparison.OrdinalIgnoreCase) > 0)
                {
                    backpack = true;
                }
                else
                {
                    inRangeCheck = vars[1].AsBool();
                }
            }

            // No graphic id, maybe searching by name?
            if (gfx == 0)
            {
                items = CommandHelper.GetItemsByName(gfxStr, backpack, inRangeCheck, hue);

                if (items.Count == 0) // no item found, search mobile by name
                {
                    mobiles = CommandHelper.GetMobilesByName(gfxStr, inRangeCheck);
                }
            }
            else // Provided graphic id for type, check backpack first (same behavior as DoubleClickAction in macros
            {
                ushort id = Utility.ToUInt16(gfxStr, 0);

                items = CommandHelper.GetItemsById(id, backpack, inRangeCheck, hue);
                
                // Still no item? Mobile check!
                if (items.Count == 0)
                {
                    mobiles = CommandHelper.GetMobilesById(id, inRangeCheck);
                }
            }

            if (items.Count > 0)
            {
                PlayerData.DoubleClick(items[Utility.Random(items.Count)].Serial);
            }
            else if (mobiles.Count > 0)
            {
                PlayerData.DoubleClick(mobiles[Utility.Random(mobiles.Count)].Serial);
            }
            else
            {
                CommandHelper.SendWarning(command, $"Item or mobile type '{gfxStr}' not found", quiet);
            }

            return true;
        }

        private static bool DClick(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length == 0)
            {
                throw new RunTimeError("Usage: dclick (serial) or dclick ('left'/'right'/'hands')");
            }

            if (Hands.Contains(vars[0].AsString()))
            {
                Item item;

                switch (vars[0].AsString())
                {
                    case "left":
                        item = World.Player.GetItemOnLayer(Layer.LeftHand);
                        break;
                    case "right":
                        item = World.Player.GetItemOnLayer(Layer.RightHand);
                        break;
                    default:
                        item = World.Player.GetItemOnLayer(Layer.RightHand) ?? World.Player.GetItemOnLayer(Layer.LeftHand);
                        break;
                }

                if (item != null)
                {
                    PlayerData.DoubleClick(item);
                }
                else
                {
                    CommandHelper.SendWarning(command, $"Item not found in '{vars[0].AsString()}'", quiet);
                }
            }
            else
            {
                Serial serial = vars[0].AsSerial();

                if (!serial.IsValid)
                {
                    throw new RunTimeError("dclick - invalid serial");
                }

                PlayerData.DoubleClick(serial);
            }

            return true;
        }

        private static bool DropItem(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 1)
            {
                throw new RunTimeError("Usage: drop (serial) (x y z/layername)");
            }

            Serial serial = vars[0].AsString().IndexOf("ground", StringComparison.OrdinalIgnoreCase) > 0
                ? uint.MaxValue
                : vars[0].AsSerial();

            Point3D to = new Point3D(0, 0, 0);
            Layer layer = Layer.Invalid;

            switch (vars.Length)
            {
                case 1: // drop at feet if only serial is provided
                    to = new Point3D(World.Player.Position.X, World.Player.Position.Y, World.Player.Position.Z);
                    break;
                case 2: // dropping on a layer
                    layer = (Layer) Enum.Parse(typeof(Layer), vars[1].AsString(), true);
                    break;
                case 3: // x y
                    to = new Point3D(Utility.ToInt32(vars[1].AsString(), 0), Utility.ToInt32(vars[2].AsString(), 0), 0);
                    break;
                case 4: // x y z
                    to = new Point3D(Utility.ToInt32(vars[1].AsString(), 0), Utility.ToInt32(vars[2].AsString(), 0),
                        Utility.ToInt32(vars[3].AsString(), 0));
                    break;
            }

            if (DragDropManager.Holding != null)
            {
                if (layer > Layer.Invalid && layer <= Layer.LastUserValid)
                {
                    Mobile m = World.FindMobile(serial);
                    if (m != null)
                        DragDropManager.Drop(DragDropManager.Holding, m, layer);
                }
                else
                {
                    DragDropManager.Drop(DragDropManager.Holding, serial, to);
                }
            }
            else
            {
                CommandHelper.SendWarning(command, "Not holding anything", quiet);
            }

            return true;
        }

        private static bool DropRelLoc(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 2)
            {
                throw new RunTimeError("Usage: droprelloc (x) (y)");
            }

            int x = vars[0].AsInt();
            int y = vars[1].AsInt();

            if (DragDropManager.Holding != null)
            {
                DragDropManager.Drop(DragDropManager.Holding, null,
                    new Point3D((ushort) (World.Player.Position.X + x),
                        (ushort) (World.Player.Position.Y + y), World.Player.Position.Z));
            }
            else
            {
                CommandHelper.SendWarning(command, "Not holding anything", quiet);
            }

            return true;
        }

        private static int _lastLiftId;

        private static bool LiftItem(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 1)
            {
                throw new RunTimeError("Usage: lift (serial) [amount] [timeout]");
            }

            Serial serial = vars[0].AsSerial();

            if (!serial.IsValid)
            {
                throw new RunTimeError($"{command} - Invalid serial");
            }

            ushort amount = 1;

            if (vars.Length == 2)
            {
                amount = Utility.ToUInt16(vars[1].AsString(), 1);
            }

            long timeout = 30000;
            
            if (vars.Length == 3)
            {
                timeout = Utility.ToLong(vars[2].AsString(), 30000);
            }

            if (_lastLiftId > 0)
            {
                if (DragDropManager.LastIDLifted == _lastLiftId)
                {
                    _lastLiftId = 0;
                    Interpreter.ClearTimeout();
                    return true;
                }

                Interpreter.Timeout(timeout, () =>
                {
                    _lastLiftId = 0;
                    return true;
                });
            }
            else
            {
                Item item = World.FindItem(serial);

                if (item != null)
                {
                    _lastLiftId = DragDropManager.Drag(item, amount <= item.Amount ? amount : item.Amount);
                }
                else
                {
                    CommandHelper.SendWarning(command, "Item not found or out of range", quiet);
                    return true;
                }
            }

            return false;
        }

        private static int _lastLiftTypeId;

        private static bool LiftType(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 1)
            {
                throw new RunTimeError("Usage: lifttype (gfx/'name of item') [amount] [hue]");
            }

            string gfxStr = vars[0].AsString();
            ushort gfx = Utility.ToUInt16(gfxStr, 0);
            ushort amount = 1;
            int hue = -1;

            if (vars.Length > 1)
            {
                if (vars.Length >= 2)
                {
                    amount = Utility.ToUInt16(vars[1].AsString(), 1);
                }

                if (vars.Length == 3)
                {
                    hue = Utility.ToUInt16(vars[2].AsString(), 0);
                }
            }

            if (_lastLiftTypeId > 0)
            {
                if (DragDropManager.LastIDLifted == _lastLiftTypeId)
                {
                    _lastLiftTypeId = 0;
                    Interpreter.ClearTimeout();
                    return true;
                }

                Interpreter.Timeout(30000, () =>
                {
                    _lastLiftTypeId = 0;
                    return true;
                });
            }
            else
            {
                List<Item> items = new List<Item>();

                // No graphic id, maybe searching by name?
                if (gfx == 0)
                {
                    items = World.Player.Backpack.FindItemsByName(gfxStr, true);

                    if (items.Count == 0)
                    {
                        CommandHelper.SendWarning(command, $"Item '{gfxStr}' not found", quiet);
                        return true;
                    }
                }
                else
                {
                    items = World.Player.Backpack.FindItemsById(gfx);
                }

                if (hue > -1)
                {
                    items.RemoveAll(item => item.Hue != hue);
                }

                if (items.Count > 0)
                {
                    Item item = items[Utility.Random(items.Count)];

                    if (item.Amount < amount)
                        amount = item.Amount;

                    _lastLiftTypeId = DragDropManager.Drag(item, amount);
                }
                else
                {
                    CommandHelper.SendWarning(command, Language.Format(LocString.NoItemOfType, (ItemID)gfx), quiet);
                    return true;
                }
            }

            return false;
        }

        private static bool Walk(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 1)
            {
                throw new RunTimeError("Usage: walk ('direction')");
            }

            if (ScriptManager.LastWalk + TimeSpan.FromSeconds(0.4) >= DateTime.UtcNow)
            {
                return false;
            }

            ScriptManager.LastWalk = DateTime.UtcNow;

            Direction dir = (Direction) Enum.Parse(typeof(Direction), vars[0].AsString(), true);
            Client.Instance.RequestMove(dir);

            return true;
        }

        private static bool UseSkill(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length == 0)
            {
                throw new RunTimeError("Usage: skill ('skill name'/'last')");
            }

            int skillId = 0;

            if (World.Player.LastSkill != -1)
            {
                skillId = World.Player.LastSkill;
            }

            if (vars[0].AsString() == "last")
            {
                Client.Instance.SendToServer(new UseSkill(World.Player.LastSkill));
            }
            else if (Skills.SkillsByName.TryGetValue(vars[0].AsString(), out SkillInfo skill))
            {
                if (skill.IsAction)
                {
                    Client.Instance.SendToServer(new UseSkill(skill.Index));

                    World.Player.LastSkill = skill.Index;
                }
                else
                {
                    CommandHelper.SendWarning(command, $"Skill '{vars[0].AsString()}' is not usable. Available usable skills: {string.Join(", ", Skills.GetUsableSkillNames())}", quiet);
                }
            }
            else
            {
                CommandHelper.SendWarning(command, $"Skill '{vars[0].AsString()}' not found. Available usable skills: {string.Join(", ", Skills.GetUsableSkillNames())}", quiet);
            }

            if (skillId == Skills.StealthIndex && !World.Player.Visible)
            {
                StealthSteps.Hide();
            }

            return true;
        }
        
        private static bool Pause(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length == 0)
                throw new RunTimeError("Usage: wait (timeout) [shorthand]");

            uint timeout = vars[0].AsUInt();

            if (vars.Length == 2)
            {
                switch (vars[1].AsString())
                {
                    case "s":
                    case "sec":
                    case "secs":
                    case "second":
                    case "seconds":
                        timeout *= 1000;
                        break;
                    case "m":
                    case "min":
                    case "mins":
                    case "minute":
                    case "minutes":
                        timeout *= 60000;
                        break;
                }
            }

            Interpreter.Pause(timeout);

            return true;
        }

        private static bool Attack(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length == 0)
            {
                throw new RunTimeError("Usage: attack (serial)");
            }

            Serial serial = vars[0].AsSerial();

            if (!serial.IsValid)
            {
                throw new RunTimeError($"{command} - Invalid serial");
            }

            if (serial == Targeting.LastTargetInfo.Serial)
            {
                Targeting.AttackLastTarg();
            }
            else
            {
                if (serial.IsMobile)
                    Client.Instance.SendToServer(new AttackReq(serial));
            }

            return true;
        }

        private static bool Cast(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 1)
            {
                throw new RunTimeError("Usage: cast 'name of spell'");
            }

            Spell spell = int.TryParse(vars[0].AsString(), out int spellnum)
                ? Spell.Get(spellnum)
                : Spell.GetByName(vars[0].AsString());

            if (spell != null)
            {
                spell.OnCast(new CastSpellFromMacro((ushort) spell.GetID()));
            }
            else
            {
                throw new RunTimeError($"{command} - Spell name or number not valid");
            }

            return true;
        }

        private static bool OverheadMessage(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length == 0)
            {
                throw new RunTimeError("Usage: overhead ('text') [color] [serial]");
            }
            
            string overheadMessage = vars[0].AsString();
            overheadMessage = CommandHelper.ReplaceStringInterpolations(overheadMessage);

            if (vars.Length == 1)
            {
                World.Player.OverheadMessage(Config.GetInt("SysColor"), overheadMessage);
            }
            else if (vars.Length == 2)
            {
                int hue = Utility.ToInt32(vars[1].AsString(), 0);

                if (vars.Length == 3)
                {
                    uint serial = vars[2].AsSerial();

                    Mobile m = World.FindMobile(serial);
                    m?.OverheadMessage(hue, overheadMessage);
                }
                else
                {
                    World.Player.OverheadMessage(hue, overheadMessage);
                }
            }

            return true;
        }

        private static bool SystemMessage(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length == 0)
            {
                throw new RunTimeError("Usage: sysmsg ('text') [color]");
            }
            
            var sysMessage = vars[0].AsString();
            sysMessage = CommandHelper.ReplaceStringInterpolations(sysMessage);

            if (vars.Length == 1)
            {
                World.Player.SendMessage(Config.GetInt("SysColor"), sysMessage);
            }
            else if (vars.Length == 2)
            {
                World.Player.SendMessage(Utility.ToInt32(vars[1].AsString(), 0), sysMessage);
            }

            return true;
        }

        private static bool ClearSysMsg(string command, Variable[] vars, bool quiet, bool force)
        {
            SystemMessages.Messages.Clear();

            return true;
        }

        private static DressList _lastDressList;

        private static bool DressCommand(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length == 0)
            {
                throw new RunTimeError("Usage: dress ('name of dress list')");
            }

            if (_lastDressList == null)
            {
                _lastDressList = DressList.Find(vars[0].AsString());
                
                if (_lastDressList != null)
                {
                    _lastDressList.Dress();
                }
                else
                {
                    Serial serial = vars[0].AsSerial();
                    Item item = World.FindItem(serial);

                    if (item != null)
                    {
                        DressList dressList = new DressList("temp");
                        dressList.Items.Add(serial);
                        dressList.Dress();

                        _lastDressList = dressList;
                    }
                    else
                    {
                        CommandHelper.SendWarning(command, $"'{vars[0].AsString()}' not found", quiet);
                        return true;
                    }
                }
            }
            else if (ActionQueue.Empty)
            {
                _lastDressList = null;
                return true;
            }

            return false;
        }

        private static DressList _lastUndressList;
        private static bool _undressAll;
        private static bool _undressLayer;

        private static bool UnDressCommand(string command, Variable[] vars, bool quiet, bool force)
        {

            if (vars.Length == 0 && !_undressAll) // full naked!
            {
                _undressAll = true;
                UndressHotKeys.OnUndressAll();
            }
            else if (vars.Length == 1 && _lastUndressList == null && !_undressLayer) // either a dress list item or a layer
            {
                _lastUndressList = DressList.Find(vars[0].AsString());

                if (_lastUndressList != null)
                {
                    _lastUndressList.Undress();
                }
                else // lets find the layer
                {
                    if (Enum.TryParse(vars[0].AsString(), true, out Layer layer))
                    {
                        Dress.Unequip(layer);
                        _undressLayer = true;
                    }
                    else
                    {
                        Serial serial = vars[0].AsSerial();
                        Item item = World.FindItem(serial);

                        if (item != null)
                        {
                            DressList undressList = new DressList("temp");
                            undressList.Items.Add(serial);
                            undressList.Undress();

                            _lastUndressList = undressList;
                        }
                        else
                        {
                            CommandHelper.SendWarning(command, $"'{vars[0].AsString()}' not found", quiet);
                            return true;
                        }
                    }
                }
            }
            else if (ActionQueue.Empty)
            {
                _undressAll = false;
                _undressLayer = false;
                _lastUndressList = null;
                return true;
            }

            return false;
        }

        private static bool GumpResponse(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 1)
            {
                throw new RunTimeError("Usage: gumpresponse (buttondId)");
                //throw new RunTimeError("Usage: gumpresponse (buttondId) [option] ['text1'|fieldId] ['text2'|fieldId]");
            }

            int buttonId = vars[0].AsInt();

            /*private int m_ButtonID;
                    private int[] m_Switches;
                    private GumpTextEntry[] m_TextEntries;*/

            //Assistant.Macros.GumpResponseAction|9|0|0
            //Assistant.Macros.GumpResponseAction|1|0|1|0&Hello How are you?
            //Assistant.Macros.GumpResponseAction|501|0|2|1&box2|0&box1

            Client.Instance.SendToClient(new CloseGump(World.Player.CurrentGumpI));
            Client.Instance.SendToServer(new GumpResponse(World.Player.CurrentGumpS, World.Player.CurrentGumpI,
                buttonId, new int[] { }, new GumpTextEntry[] { }));

            World.Player.HasGump = false;
            World.Player.HasCompressedGump = false;

            return true;
        }

        private static bool GumpClose(string command, Variable[] vars, bool quiet, bool force)
        {
            uint gumpI = World.Player.CurrentGumpI;

            if (vars.Length > 0)
            {
                gumpI = vars[0].AsUInt();
            }

            if (!World.Player.GumpList.ContainsKey(gumpI))
            {
                CommandHelper.SendWarning(command, $"'{gumpI}' unknown gump id", quiet);
                return true;
            }

            uint gumpS = World.Player.GumpList[gumpI].GumpSerial;

            Client.Instance.SendToClient(new CloseGump(gumpI));
            Client.Instance.SendToServer(new GumpResponse(gumpS, gumpI, 0, new int[] { }, new GumpTextEntry[] { }));

            World.Player.HasGump = false;
            World.Player.HasCompressedGump = false;

            return true;
        }

        private static bool ContextMenu(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 2)
            {
                throw new RunTimeError("Usage: menu (serial) (index)");
            }

            Serial s = vars[0].AsSerial();
            ushort index = vars[1].AsUShort();
            bool blockPopup = true;

            if (vars.Length > 2)
            {
                blockPopup = vars[2].AsBool();
            }

            if (s == Serial.Zero && World.Player != null)
                s = World.Player.Serial;
            
            ScriptManager.BlockPopupMenu = blockPopup;

            Client.Instance.SendToServer(new ContextMenuRequest(s));
            Client.Instance.SendToServer(new ContextMenuResponse(s, index));
            return true;
        }

        private static bool MenuResponse(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 2)
            {
                throw new RunTimeError("Usage: menuresponse (index) (menuId) [hue]");
            }

            ushort index = vars[0].AsUShort();
            ushort menuId = vars[1].AsUShort();
            ushort hue = 0;

            if (vars.Length == 3)
                hue = vars[2].AsUShort();

            Client.Instance.SendToServer(new MenuResponse(World.Player.CurrentMenuS, World.Player.CurrentMenuI, index,
                menuId, hue));
            World.Player.HasMenu = false;
            return true;
        }

        private static bool PromptResponse(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 1)
            {
                throw new RunTimeError("Usage: promptresponse ('response to the prompt')");
            }

            World.Player.ResponsePrompt(vars[0].AsString());
            return true;
        }

        private static bool LastTarget(string command, Variable[] vars, bool quiet, bool force)
        {
            if (!Targeting.DoLastTarget())
                Targeting.ResendTarget();

            return true;
        }

        private static bool PlayScript(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 1)
            {
                throw new RunTimeError("Usage: script 'name of script'");
            }

            ScriptManager.PlayScript(vars[0].AsString());

            return true;
        }

        private static readonly Dictionary<string, ushort> PotionList = new Dictionary<string, ushort>()
        {
            {"heal", 3852},
            {"cure", 3847},
            {"refresh", 3851},
            {"nightsight", 3846},
            {"ns", 3846},
            {"explosion", 3853},
            {"strength", 3849},
            {"str", 3849},
            {"agility", 3848}
        };

        private static bool Potion(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length == 0)
            {
                throw new RunTimeError("Usage: potion ('type')");
            }

            Item pack = World.Player.Backpack;
            if (pack == null)
                return true;

            if (PotionList.TryGetValue(vars[0].AsString().ToLower(), out ushort potionId))
            {
                if (potionId == 3852 && World.Player.Poisoned && Config.GetBool("BlockHealPoison") &&
                    Client.Instance.AllowBit(FeatureBit.BlockHealPoisoned))
                {
                    World.Player.SendMessage(MsgLevel.Force, LocString.HealPoisonBlocked);
                    return true;
                }

                if (!World.Player.UseItem(pack, potionId))
                {
                    CommandHelper.SendWarning(command, Language.Format(LocString.NoItemOfType, (ItemID)potionId), quiet);
                }
            }
            else
            {
                throw new RunTimeError($"{command} - Unknown potion type");
            }

            return true;
        }

        private static bool WaitForSysMsg(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 1)
            {
                throw new RunTimeError("Usage: waitforsysmsg 'message to wait for' [timeout]");
            }
            
            if (SystemMessages.Exists(vars[0].AsString()))
            {
                Interpreter.ClearTimeout();
                return true;
            }

            Interpreter.Timeout(vars.Length > 1 ? vars[1].AsUInt() : 30000, () => { return true; });

            return false;
        }

        private static bool Random(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 1)
            {
                throw new RunTimeError("Usage: random 'max value'");
            }

            int max = vars[0].AsInt();

            World.Player.SendMessage(MsgLevel.Info, $"Random: {Utility.Random(1, max)}");

            return true;
        }

        private static bool ClearDragDrop(string command, Variable[] vars, bool quiet, bool force)
        {
            DragDropManager.GracefulStop();

            return true;
        }
        
        private static bool Interrupt(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length == 1)
            {
                Layer layer = (Layer) Enum.Parse(typeof(Layer), vars[0].AsString(), true);

                if (layer > Layer.Invalid && layer <= Layer.LastUserValid)
                {
                    Spell.Interrupt(layer);
                }
                else
                {
                    throw new RunTimeError($"{command} - Invalid layer");
                }
            }
            else
            {
                Spell.Interrupt();    
            }

            return true;
        }
    }
}
```

## Expressions (`razor_Expressions.cs`)

```csharp
﻿#region license
// Razor: An Ultima Online Assistant
// Copyright (c) 2022 Razor Development Community on GitHub <https://github.com/markdwags/Razor>
// 
// This program is free software: you can redistribute it and/or modify
// it under the terms of the GNU General Public License as published by
// the Free Software Foundation, either version 3 of the License, or
// (at your option) any later version.
// 
// This program is distributed in the hope that it will be useful,
// but WITHOUT ANY WARRANTY; without even the implied warranty of
// MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
// GNU General Public License for more details.
// 
// You should have received a copy of the GNU General Public License
// along with this program.  If not, see <http://www.gnu.org/licenses/>.
#endregion

using System;
using System.Collections.Generic;
using Assistant.Core;
using Assistant.Scripts.Engine;
using Assistant.Scripts.Helpers;
using Ultima;

namespace Assistant.Scripts
{
    public static class Expressions
    {
        public static void Register()
        {
            Interpreter.RegisterExpressionHandler("stam", Stam);
            Interpreter.RegisterExpressionHandler("maxstam", MaxStam);
            Interpreter.RegisterExpressionHandler("hp", Hp);
            Interpreter.RegisterExpressionHandler("hits", Hp);
            Interpreter.RegisterExpressionHandler("maxhp", MaxHp);
            Interpreter.RegisterExpressionHandler("maxhits", MaxHp);
            Interpreter.RegisterExpressionHandler("mana", Mana);
            Interpreter.RegisterExpressionHandler("maxmana", MaxMana);
            Interpreter.RegisterExpressionHandler("poisoned", Poisoned);
            Interpreter.RegisterExpressionHandler("hidden", Hidden);

            Interpreter.RegisterExpressionHandler("mounted", Mounted);
            Interpreter.RegisterExpressionHandler("rhandempty", RHandEmpty);
            Interpreter.RegisterExpressionHandler("lhandempty", LHandEmpty);

            Interpreter.RegisterExpressionHandler("dead", Dead);

            Interpreter.RegisterExpressionHandler("str", Str);
            Interpreter.RegisterExpressionHandler("int", Int);
            Interpreter.RegisterExpressionHandler("dex", Dex);

            Interpreter.RegisterExpressionHandler("weight", Weight);
            Interpreter.RegisterExpressionHandler("maxweight", MaxWeight);

            Interpreter.RegisterExpressionHandler("skill", SkillExpression);
            Interpreter.RegisterExpressionHandler("count", CountExpression);
            Interpreter.RegisterExpressionHandler("counter", CountExpression);

            Interpreter.RegisterExpressionHandler("insysmsg", InSysMessage);
            Interpreter.RegisterExpressionHandler("insysmessage", InSysMessage);

            Interpreter.RegisterExpressionHandler("findtype", FindType);

            Interpreter.RegisterExpressionHandler("findbuff", FindBuffDebuff);
            Interpreter.RegisterExpressionHandler("finddebuff", FindBuffDebuff);

            Interpreter.RegisterExpressionHandler("position", Position);

            Interpreter.RegisterExpressionHandler("queued", Queued);

            Interpreter.RegisterExpressionHandler("varexist", VarExist);
            Interpreter.RegisterExpressionHandler("varexists", VarExist);

            Interpreter.RegisterExpressionHandler("followers", Followers);
            Interpreter.RegisterExpressionHandler("maxfollowers", MaxFollowers);

            Interpreter.RegisterExpressionHandler("targetexists", TargetExists);

            Interpreter.RegisterExpressionHandler("diffweight", DiffWeight);
            Interpreter.RegisterExpressionHandler("diffhits", DiffHits);
            Interpreter.RegisterExpressionHandler("diffhp", DiffHits);
            Interpreter.RegisterExpressionHandler("diffstam", DiffStam);
            Interpreter.RegisterExpressionHandler("diffmana", DiffMana);

            Interpreter.RegisterExpressionHandler("name", Name);
            Interpreter.RegisterExpressionHandler("paralyzed", Paralyzed);
            Interpreter.RegisterExpressionHandler("invuln", Invulnerable);
            Interpreter.RegisterExpressionHandler("invul", Invulnerable);
            Interpreter.RegisterExpressionHandler("blessed", Invulnerable);
            Interpreter.RegisterExpressionHandler("warmode", Warmode);
            
            Interpreter.RegisterExpressionHandler("itemcount", ItemCount);
            
            Interpreter.RegisterExpressionHandler("poplist", PopListExp);
            Interpreter.RegisterExpressionHandler("listexists", ListExists);
            Interpreter.RegisterExpressionHandler("list", ListLength);
            Interpreter.RegisterExpressionHandler("inlist", InList);
            
            Interpreter.RegisterExpressionHandler("timer", TimerValue);
            Interpreter.RegisterExpressionHandler("timerexists", TimerExists);
        }
        
        private static int TimerValue(string expression, Variable[] args, bool quiet, bool force)
        {
            if (args.Length != 1)
                throw new RunTimeError("Usage: timer ('timer name')");

            var ts = Interpreter.GetTimer(args[0].AsString());

            return (int)ts.TotalMilliseconds;
        }

        private static bool TimerExists(string expression, Variable[] args, bool quiet, bool force)
        {
            if (args.Length != 1)
                throw new RunTimeError("Usage: timerexists ('timer name')");

            return Interpreter.TimerExists(args[0].AsString());
        }
        
        private static bool ListExists(string expression, Variable[] args, bool quiet, bool force)
        {
            if (args.Length != 1)
                throw new RunTimeError("Usage: listexists ('list name')");

            if (Interpreter.ListExists(args[0].AsString()))
                return true;

            return false;
        }

        private static int ListLength(string expression, Variable[] args, bool quiet, bool force)
        {
            if (args.Length != 1)
                throw new RunTimeError("Usage: list (list name) (operator) (value)");

            return Interpreter.ListLength(args[0].AsString());
        }

        private static bool InList(string expression, Variable[] args, bool quiet, bool force)
        {
            if (args.Length != 2)
                throw new RunTimeError("Usage: inlist (list name) (element)");

            if (Interpreter.ListContains(args[0].AsString(), args[1]))
                return true;

            return false;
        }
        
        private static uint PopListExp(string command, Variable[] args, bool quiet, bool force)
        {
            if (args.Length != 2)
                throw new RunTimeError("Usage: poplist ('list name') ('element value'/'front'/'back')");

            var listName = args[0].AsString();
            var frontBackOrElementVar = args[1];
            var isFrontOrBack = frontBackOrElementVar.AsString() == "front" || frontBackOrElementVar.AsString() == "back";

            if (isFrontOrBack)
            {
                var isFront = frontBackOrElementVar.AsString() == "front";
                if (force)
                {
                    while (Interpreter.PopList(listName, isFront, out _)) { }
                    return Serial.Zero;
                }

                Interpreter.PopList(listName, isFront, out var popped);
                return popped.AsSerial();
            }

            var evaluatedVar = new Variable(frontBackOrElementVar.AsString());

            if (force)
            {
                while (Interpreter.PopList(listName, evaluatedVar)) { }
                return Serial.Zero;
            }

            Interpreter.PopList(listName, evaluatedVar);
            return evaluatedVar.AsSerial();
        }
        
        private static int ItemCount(string expression, Variable[] args, bool quiet, bool force)
        {
            return World.Player == null ? 0 : World.Player.Backpack.GetTotalCount();
        }
        
        private static string Name(string expression, Variable[] args, bool quiet, bool force)
        {
            return World.Player == null ? string.Empty : World.Player.Name;
        }

        private static bool Paralyzed(string expression, Variable[] args, bool quiet, bool force)
        {
            return World.Player != null && World.Player.Paralyzed;
        }

        private static bool Invulnerable(string expression, Variable[] args, bool quiet, bool force)
        {
            return World.Player != null && World.Player.Blessed;
        }

        private static bool Warmode(string expression, Variable[] args, bool quiet, bool force)
        {
            return World.Player != null && World.Player.Warmode;
        }

        private static int MaxFollowers(string expression, Variable[] args, bool quiet, bool force)
        {
            return World.Player == null ? 0 : World.Player.FollowersMax;
        }

        private static int Followers(string expression, Variable[] args, bool quiet, bool force)
        {
            return World.Player == null ? 0 : World.Player.Followers;
        }

        private static bool VarExist(string expression, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length != 1)
            {
                throw new RunTimeError("Usage: varexist ('name')");
            }

            string varName = vars[0].AsString(false);

            return quiet ? Interpreter.ExistVariable(varName) : Interpreter.ExistAlias(varName);
        }

        private static bool Queued(string expression, Variable[] vars, bool quiet, bool force)
        {
            return !ActionQueue.Empty;
        }

        private static bool FindBuffDebuff(string expression, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length == 0)
            {
                throw new RunTimeError("Usage: findbuff/finddebuff ('name of buff')");
            }

            string name = vars[0].AsString();

            foreach (BuffDebuff buff in World.Player.BuffsDebuffs)
            {
                if (buff.ClilocMessage1.IndexOf(name, StringComparison.OrdinalIgnoreCase) != -1)
                {
                    return true;
                }
            }

            return false;
        }

        private static uint FindType(string expression, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length == 0)
            {
                throw new RunTimeError("Usage: findtype ('name of item'/'graphicID) [inrangecheck (true/false)/backpack] [hue]");
            }

            string gfxStr = vars[0].AsString();
            Serial gfx = Utility.ToUInt16(gfxStr, 0);
            List<Item> items;
            List<Mobile> mobiles;

            bool inRangeCheck = false;
            bool backpack = false;
            int hue = -1;

            if (vars.Length > 1)
            {
                if (vars.Length == 3)
                {
                    hue = vars[2].AsInt();
                }

                if (vars[1].AsString().IndexOf("pack", StringComparison.OrdinalIgnoreCase) > 0)
                {
                    backpack = true;
                }
                else
                {
                    inRangeCheck = vars[1].AsBool();
                }
            }

            // No graphic id, maybe searching by name?
            if (gfx == 0)
            {
                items = CommandHelper.GetItemsByName(gfxStr, backpack, inRangeCheck, hue);

                if (items.Count == 0) // no item found, search mobile by name
                {
                    mobiles = CommandHelper.GetMobilesByName(gfxStr, inRangeCheck);

                    if (mobiles.Count > 0)
                    {
                        return mobiles[Utility.Random(mobiles.Count)].Serial;
                    }
                }
                else
                {
                    return items[Utility.Random(items.Count)].Serial;
                }
            }
            else // Provided graphic id for type, check backpack first (same behavior as DoubleClickAction in macros
            {
                ushort id = Utility.ToUInt16(gfxStr, 0);

                items = CommandHelper.GetItemsById(id, backpack, inRangeCheck, hue);

                // Still no item? Mobile check!
                if (items.Count == 0)
                {
                    mobiles = CommandHelper.GetMobilesById(id, inRangeCheck);

                    if (mobiles.Count > 0)
                    {
                        return mobiles[Utility.Random(mobiles.Count)].Serial;
                    }
                }
                else
                {
                    return items[Utility.Random(items.Count)].Serial;
                }
            }

            return Serial.Zero;
        }

        private static bool Mounted(string expression, Variable[] vars, bool quiet, bool force)
        {
            return World.Player != null && World.Player.GetItemOnLayer(Layer.Mount) != null;
        }

        private static bool RHandEmpty(string expression, Variable[] vars, bool quiet, bool force)
        {
            return World.Player != null && World.Player.GetItemOnLayer(Layer.RightHand) == null;
        }

        private static bool LHandEmpty(string expression, Variable[] vars, bool quiet, bool force)
        {
            return World.Player != null && World.Player.GetItemOnLayer(Layer.LeftHand) == null;
        }

        private static bool Dead(string expression, Variable[] vars, bool quiet, bool force)
        {
            return World.Player != null && World.Player.IsGhost;
        }

        private static bool InSysMessage(string expression, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length == 0)
            {
                throw new RunTimeError("Usage: insysmsg ('text')");
            }

            string text = vars[0].AsString();

            return SystemMessages.Exists(text);
        }

        private static int Mana(string expression, Variable[] vars, bool quiet, bool force)
        {
            if (World.Player == null)
                return 0;

            return World.Player.Mana;
        }

        private static int MaxMana(string expression, Variable[] vars, bool quiet, bool force)
        {
            if (World.Player == null)
                return 0;

            return World.Player.ManaMax;
        }

        private static bool Poisoned(string expression, Variable[] vars, bool quiet, bool force)
        {
            return World.Player != null && Client.Instance.AllowBit(FeatureBit.BlockHealPoisoned) &&
                   World.Player.Poisoned;
        }

        private static bool Hidden(string expression, Variable[] vars, bool quiet, bool force)
        {
            return World.Player != null && !World.Player.Visible;
        }

        private static int Hp(string expression, Variable[] vars, bool quiet, bool force)
        {
            if (World.Player == null)
                return 0;

            return World.Player.Hits;
        }

        private static int MaxHp(string expression, Variable[] vars, bool quiet, bool force)
        {
            if (World.Player == null)
                return 0;

            return World.Player.HitsMax;
        }

        private static int Stam(string expression, Variable[] vars, bool quiet, bool force)
        {
            if (World.Player == null)
                return 0;

            return World.Player.Stam;
        }

        private static int MaxStam(string expression, Variable[] vars, bool quiet, bool force)
        {
            if (World.Player == null)
                return 0;

            return World.Player.StamMax;
        }

        private static int Str(string expression, Variable[] vars, bool quiet, bool force)
        {
            if (World.Player == null)
                return 0;

            return World.Player.Str;
        }

        private static int Dex(string expression, Variable[] vars, bool quiet, bool force)
        {
            if (World.Player == null)
                return 0;

            return World.Player.Dex;
        }

        private static int Int(string expression, Variable[] vars, bool quiet, bool force)
        {
            if (World.Player == null)
                return 0;

            return World.Player.Int;
        }

        private static int Weight(string expression, Variable[] vars, bool quiet, bool force)
        {
            if (World.Player == null)
                return 0;

            return World.Player.Weight;
        }

        private static int MaxWeight(string expression, Variable[] vars, bool quiet, bool force)
        {
            if (World.Player == null)
                return 0;

            return World.Player.MaxWeight;
        }

        private static double SkillExpression(string expression, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 1)
                throw new RunTimeError("Usage: skill ('name of skill')");

            if (World.Player == null)
                return 0;

            if (Skills.SkillsByName.TryGetValue(vars[0].AsString(), out var skill))
            {
                return force ? World.Player.Skills[skill.Index].Base : World.Player.Skills[skill.Index].Value;
            }

            CommandHelper.SendWarning(expression, $"Skill '{vars[0].AsString()}' not found", quiet);

            return 0;
        }

        private static int CountExpression(string expression, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 1)
                throw new RunTimeError("Usage: count ('name of counter') OR count ('name of item' OR graphicID) [hue]");

            if (World.Player == null)
                return 0;

            var counter = Counter.FindCounter(vars[0].AsString());
            if (counter != null)
            {
                return counter.Amount;
            }

            string gfxStr = vars[0].AsString();
            Serial gfx = Utility.ToUInt16(gfxStr, 0);
            ushort hue = 0xFFFF;

            if (vars.Length == 2)
            {
                hue = Utility.ToUInt16(vars[1].AsString(), 0xFFFF);
            }

            // No graphic id, maybe searching by name?
            if (gfx == 0)
            {
                var items = CommandHelper.GetItemsByName(gfxStr, true, false, -1);
                
                return items.Count == 0 ? 0 : Counter.GetCount(items[0].ItemID, hue);
            }

            return Counter.GetCount(new ItemID((ushort)gfx.Value), hue);
        }

        private static bool Position(string expression, Variable[] vars, bool quiet, bool force)
        {
            if (World.Player == null)
                return false;

            if (vars.Length < 2)
            {
                throw new RunTimeError("Usage: position (x, y) or position (x, y, z)");
            } 

            int x = vars[0].AsInt();
            int y = vars[1].AsInt();
            int z = (vars.Length > 2) 
                ? vars[2].AsInt() 
                : World.Player.Position.Z;

            return World.Player.Position.X == x
                && World.Player.Position.Y == y
                && World.Player.Position.Z == z;
        }

        private static readonly Dictionary<string, byte> TargetMap = new Dictionary<string, byte>
        {
            {"neutral", 0},
            {"harmful", 1},
            {"beneficial", 2},
            {"any", 3}
        };

        private static bool TargetExists(string expression, Variable[] args, bool quiet, bool force)
        {
            byte type = 3;

            if (args.Length > 0)
            {
                if (!TargetMap.TryGetValue(args[0].AsString().ToLower(), out type))
                {
                    throw new RunTimeError("Invalid target type: 0 = neutral, 1 = harmful, 2 = beneficial, any = 3");
                }
            }

            if (!Targeting.HasTarget)
                return false;

            if (type == 3)
                return true;

            return Targeting.CursorType == type;
        }

        private static int DiffWeight(string expression, Variable[] args, bool quiet, bool force)
        {
            if (World.Player == null)
                return 0;

            return World.Player.MaxWeight - World.Player.Weight;
        }

        private static int DiffHits(string expression, Variable[] args, bool quiet, bool force)
        {
            if (World.Player == null)
                return 0;

            return World.Player.HitsMax - World.Player.Hits;
        }

        private static int DiffStam(string expression, Variable[] args, bool quiet, bool force)
        {
            if (World.Player == null)
                return 0;

            return World.Player.StamMax - World.Player.Stam;
        }

        private static int DiffMana(string expression, Variable[] args, bool quiet, bool force)
        {
            if (World.Player == null)
                return 0;

            return World.Player.ManaMax - World.Player.Mana;
        }
    }
}
```

## Agent Commands (`razor_AgentCommands.cs`)

```csharp
﻿#region license
// Razor: An Ultima Online Assistant
// Copyright (c) 2022 Razor Development Community on GitHub <https://github.com/markdwags/Razor>
// 
// This program is free software: you can redistribute it and/or modify
// it under the terms of the GNU General Public License as published by
// the Free Software Foundation, either version 3 of the License, or
// (at your option) any later version.
// 
// This program is distributed in the hope that it will be useful,
// but WITHOUT ANY WARRANTY; without even the implied warranty of
// MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
// GNU General Public License for more details.
// 
// You should have received a copy of the GNU General Public License
// along with this program.  If not, see <http://www.gnu.org/licenses/>.
#endregion

using System;
using Assistant.Agents;
using Assistant.Scripts.Engine;

namespace Assistant.Scripts
{
    public static class AgentCommands
    {
        public static void Register()
        {
            // "useonce", "organizer", "org", "restock", "scav", "scavenger"
            Interpreter.RegisterCommandHandler("useonce", UseOnceCommand);
            Interpreter.RegisterCommandHandler("organizer", OrganizerAgentCommand);
            Interpreter.RegisterCommandHandler("organize", OrganizerAgentCommand);
            Interpreter.RegisterCommandHandler("org", OrganizerAgentCommand);
            Interpreter.RegisterCommandHandler("restock", RestockAgentCommand);
            Interpreter.RegisterCommandHandler("scav", ScavAgentCommand);
            Interpreter.RegisterCommandHandler("scavenger", ScavAgentCommand);
            Interpreter.RegisterCommandHandler("sell", SellAgentCommand);
        }

        private static bool RestockAgentCommand(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 1)
            {
                throw new RunTimeError( "Usage: restock (number) ['set']");
            }
            
            bool setBag = false;

            if (vars.Length == 2)
            {
                if (vars[1].AsString().IndexOf("set", StringComparison.OrdinalIgnoreCase) != -1)
                {
                    setBag = true;
                }
            }

            if (!int.TryParse(vars[0].AsString(), out var agentNum))
            {
                string alias = vars[0].AsString();

                foreach (RestockAgent agent in RestockAgent.Agents)
                {
                    if (agent.Alias.IndexOf(alias, StringComparison.OrdinalIgnoreCase) != -1)
                    {
                        agentNum = agent.Number;
                        break;
                    }
                }
            }

            if (setBag)
            {
                RestockAgent.Agents[agentNum - 1].SetHB();
            }
            else
            {
                RestockAgent.Agents[agentNum - 1].OnHotKey();
            }

            return true;
        }

        private static bool UseOnceCommand(string command, Variable[] vars, bool quiet, bool force)
        {
            bool add = false;
            bool container = false;

            if (vars.Length == 1)
            {
                if (vars[0].AsString().IndexOf("add", StringComparison.OrdinalIgnoreCase) != -1)
                {
                    add = true;
                }
                else if (vars[0].AsString().IndexOf("addcontainer", StringComparison.OrdinalIgnoreCase) != -1)
                {
                    container = true;
                }
            }

            if (add)
            {
                UseOnceAgent.Instance.OnAdd();
            }
            else if (container)
            {
                UseOnceAgent.Instance.OnAddContainer();
            }
            else
            {
                UseOnceAgent.Instance.OnHotKey();
            }

            return true;
        }

        private static bool OrganizerAgentCommand(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 1)
            {
                throw new RunTimeError("Usage: organizer (number) ['set']");
            }

            bool setBag = false;

            if (vars.Length == 2)
            {
                if (vars[1].AsString().IndexOf("set", StringComparison.OrdinalIgnoreCase) != -1)
                {
                    setBag = true;
                }
            }

            if (!int.TryParse(vars[0].AsString(), out var agentNum))
            {
                string alias = vars[0].AsString();

                foreach (OrganizerAgent agent in OrganizerAgent.Agents)
                {
                    if (agent.Alias.IndexOf(alias, StringComparison.OrdinalIgnoreCase) != -1)
                    {
                        agentNum = agent.Number;
                        break;
                    }
                }
            }

            if (setBag)
            {
                OrganizerAgent.Agents[agentNum - 1].SetHotBag();
            }
            else
            {
                OrganizerAgent.Agents[agentNum - 1].Organize();
            }

            return true;
        }

        private static bool ScavAgentCommand(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 1)
            {
                throw new RunTimeError("Usage: scavenger ['clear'/'add'/'on'/'off'/'set']");
            }

            bool clear = false;
            bool add = false;
            bool set = false;

            bool status = false;
            bool enabled = true;

            if (vars.Length == 1)
            {
                if (vars[0].AsString().IndexOf("clear", StringComparison.OrdinalIgnoreCase) != -1)
                {
                    clear = true;
                }
                else if (vars[0].AsString().IndexOf("add", StringComparison.OrdinalIgnoreCase) != -1)
                {
                    add = true;
                }
                else if (vars[0].AsString().IndexOf("on", StringComparison.OrdinalIgnoreCase) != -1)
                {
                    status = true;
                }
                else if (vars[0].AsString().IndexOf("off", StringComparison.OrdinalIgnoreCase) != -1)
                {
                    status = true;
                    enabled = false;
                }
                else if (vars[0].AsString().IndexOf("set", StringComparison.OrdinalIgnoreCase) != -1)
                {
                    set = true;
                }
            }

            if (clear)
            {
                ScavengerAgent.Instance.ClearCache();
            }
            else if (add)
            {
                ScavengerAgent.Instance.OnAddToHotBag();
            }
            else if (status)
            {
                if (enabled)
                {
                    ScavengerAgent.Instance.Enable();
                }
                else
                {
                    ScavengerAgent.Instance.Disable();
                }
            }
            else if (set)
            {
                ScavengerAgent.Instance.OnSetHotBag();
            }

            return true;
        }

        private static bool SellAgentCommand(string command, Variable[] vars, bool quiet, bool force)
        {
            SellAgent.Instance.SetHotBag();

            return true;
        }
    }
}
```

## Target Commands (`razor_TargetCommands.cs`)

```csharp
﻿#region license
// Razor: An Ultima Online Assistant
// Copyright (c) 2022 Razor Development Community on GitHub <https://github.com/markdwags/Razor>
// 
// This program is free software: you can redistribute it and/or modify
// it under the terms of the GNU General Public License as published by
// the Free Software Foundation, either version 3 of the License, or
// (at your option) any later version.
// 
// This program is distributed in the hope that it will be useful,
// but WITHOUT ANY WARRANTY; without even the implied warranty of
// MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
// GNU General Public License for more details.
// 
// You should have received a copy of the GNU General Public License
// along with this program.  If not, see <http://www.gnu.org/licenses/>.
#endregion

using System;
using System.Collections.Generic;
using Assistant.Scripts.Engine;
using Assistant.Scripts.Helpers;

namespace Assistant.Scripts
{
    public static class TargetCommands
    {
        public static void Register()
        {
            // Targets
            Interpreter.RegisterCommandHandler("target", Target); //Absolute Target

            Interpreter.RegisterCommandHandler("targettype", TargetType); //TargetTypeAction
            Interpreter.RegisterCommandHandler("targetrelloc", TargetRelLoc); //TargetRelLocAction
            Interpreter.RegisterCommandHandler("targetloc", TargetLocation);

            Interpreter.RegisterCommandHandler("waitfortarget", WaitForTarget); //WaitForTargetAction
            Interpreter.RegisterCommandHandler("wft", WaitForTarget); //WaitForTargetAction
        }

        private static bool Target(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 1)
            {
                throw new RunTimeError("Usage: target (serial) OR target (closest/random/next/prev [noto] [type]");
            }

            switch (vars[0].AsString())
            {
                case "close":
                case "closest":
                    CommandHelper.FindTarget(vars, true);

                    break;

                case "rand":
                case "random":
                    CommandHelper.FindTarget(vars, false, true);

                    break;

                case "next":
                    CommandHelper.FindTarget(vars, false, false, true);

                    break;

                case "prev":
                case "previous":
                    CommandHelper.FindTarget(vars, false, false, false, true);

                    break;

                case "cancel":
                    Targeting.CancelTarget();

                    break;

                case "clear":
                    Targeting.OnClearQueue();

                    break;

                default:
                    Serial serial = vars[0].AsSerial();

                    if (serial != Serial.Zero) // Target a specific item or mobile
                    {
                        Item item = World.FindItem(serial);

                        if (item != null)
                        {
                            Targeting.Target(item);
                            return true;
                        }

                        Mobile mobile = World.FindMobile(serial);

                        if (mobile != null)
                        {
                            Targeting.Target(mobile);
                        }
                    }

                    break;
            }

            return true;
        }

        private static bool TargetType(string command, Variable[] vars, bool quiet, bool force)
        {
            if (Targeting.FromGrabHotKey)
                return false;

            if (vars.Length < 1)
            {
                throw new RunTimeError("Usage: targettype ('name of item or mobile type'/'graphicId') [inrangecheck (true/false)/backpack] [hue]");
            }

            string gfxStr = vars[0].AsString();
            Serial gfx = Utility.ToUInt16(gfxStr, 0);
            List<Item> items;
            List<Mobile> mobiles = new List<Mobile>();

            bool inRangeCheck = false;
            bool backpack = false;
            int hue = -1;

            if (vars.Length > 1)
            {
                if (vars.Length == 3)
                {
                    hue = vars[2].AsInt();
                }

                if (vars[1].AsString().IndexOf("pack", StringComparison.OrdinalIgnoreCase) != -1)
                {
                    backpack = true;
                }
                else
                {
                    inRangeCheck = vars[1].AsBool();
                }
            }

            // No graphic id, maybe searching by name?
            if (gfx == 0)
            {
                items = CommandHelper.GetItemsByName(gfxStr, backpack, inRangeCheck, hue);

                if (items.Count == 0) // no item found, search mobile by name
                {
                    mobiles = CommandHelper.GetMobilesByName(gfxStr, inRangeCheck);
                }
            }
            else // Provided graphic id for type, check backpack first (same behavior as DoubleClickAction in macros
            {
                ushort id = Utility.ToUInt16(gfxStr, 0);

                items = CommandHelper.GetItemsById(id, backpack, inRangeCheck, hue);

                // Still no item? Mobile check!
                if (items.Count == 0)
                {
                    mobiles = CommandHelper.GetMobilesById(id, inRangeCheck);
                }
            }

            if (items.Count > 0)
            {
                Targeting.Target(items[Utility.Random(items.Count)]);
            }
            else if (mobiles.Count > 0)
            {
                Targeting.Target(mobiles[Utility.Random(mobiles.Count)]);
            }
            else
            {
                CommandHelper.SendWarning(command, $"Item or mobile type '{gfxStr}' not found", quiet);
            }

            return true;
        }

        private static bool TargetRelLoc(string command, Variable[] vars, bool quiet, bool force)
        {
            if (Targeting.FromGrabHotKey)
                return false;

            if (vars.Length < 2)
            {
                throw new RunTimeError("Usage: targetrelloc (x-offset) (y-offset)");
            }

            int xoffset = Utility.ToInt32(vars[0].AsString(), 0);
            int yoffset = Utility.ToInt32(vars[1].AsString(), 0);

            ushort x = (ushort) (World.Player.Position.X + xoffset);
            ushort y = (ushort) (World.Player.Position.Y + yoffset);
            short z = (short) World.Player.Position.Z;

            try
            {
                Ultima.HuedTile tile = Map.GetTileNear(World.Player.Map, x, y, z);
                Targeting.Target(new Point3D(x, y, tile.Z), tile.ID);
            }
            catch (Exception e)
            {
                throw new RunTimeError($"{command} - Error Executing: {e.Message}");
            }

            return true;
        }

        private static bool TargetLocation(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length < 2)
            {
                throw new RunTimeError("Usage: targetloc (x) (y) (z)");
            }

            Targeting.Target(new TargetInfo
            {
                Type = 1,
                Flags = 0,
                Serial = Serial.Zero,
                X = vars[0].AsInt(),
                Y = vars[1].AsInt(),
                Z = vars.Length == 3 ? vars[2].AsInt() : 0,
                Gfx = 0
            });

            return true;
        }

        private static bool WaitForTarget(string command, Variable[] vars, bool quiet, bool force)
        {
            if (Targeting.HasTarget)
            {
                Interpreter.ClearTimeout();
                return true;
            }

            Interpreter.Timeout(vars.Length > 0 ? vars[0].AsUInt() : 30000, () => { return true; });

            return false;
        }
    }
}
```

## Speech Commands (`razor_SpeechCommands.cs`)

```csharp
﻿#region license
// Razor: An Ultima Online Assistant
// Copyright (c) 2022 Razor Development Community on GitHub <https://github.com/markdwags/Razor>
// 
// This program is free software: you can redistribute it and/or modify
// it under the terms of the GNU General Public License as published by
// the Free Software Foundation, either version 3 of the License, or
// (at your option) any later version.
// 
// This program is distributed in the hope that it will be useful,
// but WITHOUT ANY WARRANTY; without even the implied warranty of
// MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
// GNU General Public License for more details.
// 
// You should have received a copy of the GNU General Public License
// along with this program.  If not, see <http://www.gnu.org/licenses/>.
#endregion

using Assistant.Scripts.Engine;

namespace Assistant.Scripts
{
    public static class SpeechCommands
    {
        public static void Register()
        {
            // Messages
            Interpreter.RegisterCommandHandler("say", Say);
            Interpreter.RegisterCommandHandler("msg", Say);
            Interpreter.RegisterCommandHandler("yell", Yell);
            Interpreter.RegisterCommandHandler("whisper", Whisper);
            Interpreter.RegisterCommandHandler("emote", Emote);
            Interpreter.RegisterCommandHandler("guild", Guild);
            Interpreter.RegisterCommandHandler("alliance", Alliance);
        }

        private static bool Say(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length == 0)
            {
                throw new RunTimeError("Usage: say ('text') [color]");
            }

            if (vars.Length == 1)
                World.Player.Say(Config.GetInt("SysColor"), vars[0].AsString());
            else
                World.Player.Say(Utility.ToInt32(vars[1].AsString(), 0), vars[0].AsString());

            return true;
        }

        private static bool Whisper(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length == 0)
            {
                throw new RunTimeError("Usage: whisper ('text') [color]");
            }

            MessageType type = MessageType.Whisper & ~MessageType.Encoded;

            if (vars.Length == 1)
                World.Player.Whisper(vars[0].AsString(), World.Player.SpeechHue);
            else
                World.Player.Whisper(vars[0].AsString(), Utility.ToInt32(vars[1].AsString(), 0));

            return true;
        }

        private static bool Yell(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length == 0)
            {
                throw new RunTimeError("Usage: yell ('text') [color]");
            }

            if (vars.Length == 1)
                World.Player.Yell(vars[0].AsString(), World.Player.SpeechHue);
            else
                World.Player.Yell(vars[0].AsString(), Utility.ToInt32(vars[1].AsString(), 0));

            return true;
        }

        private static bool Emote(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length == 0)
            {
                throw new RunTimeError("Usage: emote ('text') [color]");
            }

            if (vars.Length == 1)
                World.Player.Emote(vars[0].AsString(), World.Player.SpeechHue);
            else
                World.Player.Emote(vars[0].AsString(), Utility.ToInt32(vars[1].AsString(), 0));

            return true;
        }

        private static bool Guild(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length == 0)
            {
                throw new RunTimeError("Usage: guild ('text')");
            }

            if (vars.Length == 1)
                World.Player.Guild(vars[0].AsString(), World.Player.SpeechHue);
            else
                World.Player.Guild(vars[0].AsString(), Utility.ToInt32(vars[1].AsString(), 0));

            return true;
        }

        private static bool Alliance(string command, Variable[] vars, bool quiet, bool force)
        {
            if (vars.Length == 0)
            {
                throw new RunTimeError("Usage: alliance ('text')");
            }

            if (vars.Length == 1)
                World.Player.Alliance(vars[0].AsString(), World.Player.SpeechHue);
            else
                World.Player.Alliance(vars[0].AsString(), Utility.ToInt32(vars[1].AsString(), 0));

            return true;
        }
    }
}

```
