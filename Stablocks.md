```statblock
layout: Basic 5e Layout
name: Renata
size: Medium
type: Humanoid
subtype: "(Human)"
alignment: Neutral
ac: 13
hp: 16
hit_dice: 3d8 + 3
speed: 30 ft
stats: [11,14,12,11,13,11]
skillsaves:
  - Insight: 3
  - Nature: 4
  - Perception: 5
  - Persuasion: 2
  - Stealth: 6
  - Survival: 5
senses: Passive Perception 15
languages: Common and Draconic
cr: 1/2
traits:
  - name: Spellcasting
    desc: 1/rest guidance
actions:
  - name: Multiattack
    desc: Renata makes two attacks, using Shortsword and Longbow in any combination
  - name: Shortsword
    desc: "Melee Attack Roll: +4, reach 5 ft. Hit: 5 (1d6 + 2) Piercing damage."
  - name: Longbow
    desc: "Ranged Attack Roll: +4, range 150/600 ft. Hit: 6 (1d8 + 2) Piercing damage."
source: MTW
```
^RenataStatblock
```statblock
layout: Basic 5e Layout
name: Thania Schmidt
size: Medium
type: Humanoid
alignment: Neutral
ac: 15
hp: 52
hit_dice: 8d8 + 16
speed: 30 ft
stats: [15,16,14,14,18,14]
skillsaves:
  - Athletics: 4
  - Deception: 4
senses: Passive Perception 14
languages: Common, Thieves' cant
cr: 2
actions:
  - name: Multiattack
    desc: "The bandit makes two attacks, using Scimitar and Pistol in any combination."
  - name: Scimitar
    desc: "Melee Attack Roll: +5, reach 5 ft. Hit: 6 (1d6 + 3) Slashing damage."
  - name: Pistol
    desc: "Ranged Attack Roll: +5, range 30/90 ft. Hit: 8 (1d10 + 3) Piercing damage."
reactions:
  - name: Parry
    desc: "Trigger: The bandit is hit by a melee attack roll while holding a weapon. Response: The bandit adds 2 to its AC against that attack, possibly causing it to miss."
source: MTW
```
^ThaniaStatblock
```statblock
layout: Basic 5e Layout
name: Harann Nemonis
size: Huge
type: Dragon (Chromatic)
alignment: Chaotic Evil
ac: 18
hp: 200
hit_dice: 16d12 + 96
speed: 40 ft., Burrow 30 ft., Swim 40 ft
stats: [22,10,22,8,12,12]
saves:
  - DEX: 5
  - WIS: 6
skillsaves:
  - Perception: 11
  - Stealth: 5
damage_immunities: Cold
senses: Blindsight 60 ft., Darkvision 120 ft., Passive Perception 21
languages: common, draconic
cr: 13
traits:
  - name: Ice Walk 
    desc: "The dragon can move across and climb icy surfaces without needing to make an ability check. Additionally, Difficult Terrain composed of ice or snow doesn't cost it extra movement."
  - name: Legendary Resistance (3/Day, or 4/Day in Lair).
    desc: "If the dragon fails a saving throw, it can choose to succeed instead."
actions:
  - name: Multiattack 
    desc: The dragon makes three Rend attacks.
  - name: Rend
    desc: "Melee Attack Roll: +11, reach 10 ft. Hit: 13 (2d6 + 6) Slashing damage plus 4 (1d8) Cold damage."
  - name: Cold Breath (Recharge 5-6)
    desc: "Constitution Saving Throw: DC 19, each creature in a 60-foot Cone. Failure: 54 (12d8) Cold damage. Success: Half damage."
legendary_description: "Legendary Action Uses: 3 (20 in Lair). Immediately after another creature's turn, hanann can expend a use to take one of the following actions. Hanann regains all expended uses at the start of each of their turns."
legendary_actions:
  - name: Blizzard Veil
    desc: "Icy wind fills the chamber. All non-dragons must succeed on a Constitution Saving Throw: DC 15 or be blinded until the end of their next turn."
  - name: Frightful Presence
    desc: "The dragon casts Fear, requiring no Material components and using Charisma as the spellcasting ability (spell save DC 14). The dragon can't take this action again until the start of its next turn."
  - name: Shattering Ice
    desc: "An icicle falls from the ceiling, targeting a random player (+10 to hit, 2d10 piercing + 2d10 cold damage)."
  - name: Frozen Shackles
    desc: "Frozen Shackles. Frost creeps up from the floor, restraining one random creature (Strength Saving Throw: DC 16 to break)."
regional_effects:
  - name: "Header"
    desc: "The region containing an adult or ancient white dragon's lair is affected by its presence, creating the following effects:"
  - name: Frigid Cold
    desc: "The area within 1 mile of the lair is an area of extreme cold. Any water in that area is frigid water. See the Dungeon Master's Guide for rules on extreme cold and frigid water."
  - name: Glacial Gloom
    desc: "The area within 1 mile of the lair is Lightly Obscured by chilly fog. Whenever a creature other than the dragon or one of its allies finishes a Long Rest in that area, that creature must succeed on a DC 15 Constitution saving throw or have its Speed reduced by 10 feet for 1 hour."
  - name: "Footer"
    desc: "If the dragon dies or moves its lair elsewhere, these effects end immediately"
source: MTW
```
^HarannStatblock
```statblock
layout: Basic 5e Layout
name: Kaelen
size: Medium
type: Humanoid
alignment: Neutral
ac: 12
hp: 11
hit_dice: 2d8 + 2
speed: 30 ft
stats: [11,12,12,10,10,10]
skillsaves:
  - Intimidation: 2
senses: Passive Perception 10
languages: Common, Thieves' Cant
cr: 1/8
actions:
  - name: Scimitar
    desc: "Melee Attack Roll: +3, reach 5 ft. Hit: 4 (1d6 + 1) Slashing damage."
  - name: Light Crossbow
    desc: "Ranged Attack Roll: +3, range 80/320 ft. Hit: 5 (1d8 + 1) Piercing damage."
source: MTW
```
^KaelenStatblock

```statblock
layout: Basic 5e Layout
name: Thania's Crew
source: MTW
size: Medium
type: Humanoid (Human)
alignment: neutral
ac: 12 (leahter armor)
hp: 22
hit_dice: 5d8
speed: 30 ft
stats: [13,14,12,10,11,10]
saves:
  - DEX: 4
skillsaves:
  - Athletics: 3
  - Acrobatics: 4
  - Perception: 2
  - Survival: 2
senses: Passive Perception 12
languages: Common, Thieves' Cant
cr: 1/4
traits:
  - name: Sea-Hardened
    desc: "The crew member has advantage on checks or saves to resist being knocked prone, pushed, opr moved against their will while aboard a ship or near rought terrain"
  - name: Team Fighter
    desc: "When within 5ft of an ally, they gain +1 bonus to attack rolls (representing practiced coordination)"
  - name: Mariner's Instinct
    desc: "Can hold breath for 3 minutes and has advantage on ability checks related to climbing, swimming, or keeping balance on slick surfaces"
actions:
  - name: Cutlass
    desc: "Melee Weapon Attack: +4 to hit, 5ft. reach, one target. Hit: 6 (1d8+2) slashing damage."
  - name: Crossbow
    desc: "Ranged Weapon Attack: +4 to hit, rang 80/320ft., one target. Hit: 5 (1d8+1) piercing damage."
```
^ThaniaCrewStatblock

```statblock
layout: Basic 5e Layout
name: Frost-Cursed Mariner
size: Medium
type: Undead (Human)
alignment: Lawful Evil
ac: 12
hp: 16
hit_dice: 3d8 + 3
speed: 30 ft
stats: [13,12,12,10,10,10]
senses: Passive Perception 10
languages: Common, understands the commands of Harann Nemmonis
cr: 1/2
traits:
  - name: Icy Demise
    desc: "When the mariner is reduced to 0 hit points, its body shatters into shards of ice. All creatures within 5 feet must succeed on a DC 10 Dexterity saving throw or take 2 (1d4) cold damage."
actions:
  - name: Icy Cutlass
    desc: "Melee Weapon Attack: +3 to hit, reach 5 ft., one target. Hit: 5 (1d6 + 2) slashing damage plus 2 (1d4) cold damage."
source: MTW
```
^FrostCursedMarinerStatblock

```statblock
layout: Basic 5e Layout
name: Frost-Cursed Captain
size: Medium
type: Undead (Human)
alignment: Lawful Evil
ac: 16 (natural armor)
hp: 102
hit_dice: 12d8 + 48
speed: 30 ft,. Swim 40 ft.
stats:
  - 18
  - 15
  - 18
  - 14
  - 13
  - 16
skillsaves:
  - Perception: 4
senses: Darkvision 60 ft., Passive Perception 14
languages: Common, understands the commands of Harann Nemmonis
cr: 5
traits:
  - name: Icy Demise
    desc: "When the captain is reduced to 0 hit points, its body shatters into shards of ice. All creatures within 10 feet must succeed on a DC 10 Dexterity saving throw or take 9 (3d6) cold damage."
actions:
  - name: Multiattack
    desc: "The captain makes two attacks: one with its Icy Trident and one with its Bite."
  - name: Icy Trident
    desc: "Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 20/60 ft., one target. Hit: 11 (2d6 + 4) piercing damage plus 3 (1d6) cold damage."
  - name: Bite
    desc: "Melee Weapon Attack: +7 to hit, reach 5 ft., one target. Hit: 7 (1d6 + 4) piercing damage."
  - name: Chilling Roar (Recharge 5–6)
    desc: "The captain roars, releasing a wave of cold. Each creature within 15 feet of the captain must succeed on a DC 13 Constitution saving throw or be slowed until the end of its next turn."
source: MTW
```
^FrostCursedCaptainStatblock

```statblock
layout: Basic 5e Layout
name: Frost-Cursed Kobold
size: Small
type: Aberration
alignment: Lawful Evil
ac: 12
hp: 5
hit_dice: 2d6 - 2
speed: 30 ft
stats: [7,15,9,8,7,8]
senses: Darkvision 60 ft., Passive Perception 8
languages: Common, understands the commands of Harann Nemmonis
cr: 1/8
traits:
  - name: Icy Demise
    desc: "When the kobold is reduced to 0 hit points, its body explodes into shards of ice. All creatures within 5 feet must succeed on a DC 10 Dexterity saving throw or take 3 (1d6) cold damage."
  - name: Pack Tactics
    desc: "The kobold has advantage on an attack roll against a creature if at least one of the kobold's allies is within 5 feet of the creature and the ally isn't incapacitated."
actions:
  - name: Icy Javelin
    desc: "Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 30/120 ft., one target. Hit: 5 (1d4 + 2) piercing damage plus 2 (1d4) cold damage."
source: MTW
```
^FrostCursedKoboldStatblock

```statblock
layout: Basic 5e Layout
source: MTW
name: Frost-Cursed Chieftain
size: Small
type: Aberration
alignment: Lawful Evil
ac: 12 (leather armor)
hp: 21
hit_dice: 6d6
speed: 30 ft
stats: [7,15,10,14,10,8]
senses: Senses Darkvision 60 ft., Passive Perception 10
languages: Common, understands the commands of Harann Nemmonis
cr: 1
traits:
  - name: Icy Demise
    desc: "When the chieftain is reduced to 0 hit points, its body explodes into shards of ice. All creatures within 5 feet must succeed on a DC 12 Dexterity saving throw or take 4 (1d8) cold damage."
  - name: Inventions
    desc: "The chieftain has a bag of tricks, allowing it to use one of the following abilities each turn as a bonus action.\n- Glacial Glue: The chieftain throws a small container that explodes into a sticky, icy substance. One creature within 20 feet must succeed on a DC 12 Dexterity saving throw or be restrained. A creature can use its action to make a DC 12 Strength check to end the effect.\n- Frost Bomb: The chieftain throws a small orb that explodes in a 10-foot radius. Each creature in the area must succeed on a DC 12 Constitution saving throw or take 6 (2d6) cold damage."
actions:
  - name: Icy Dagger
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft., one target. Hit: 4 (1d4 + 2) piercing damage plus 2 (1d4) cold damage" 
```
^FrostCursedChieftainStatblock

```statblock
layout: Basic 5e Layout
source: MTW
name: Frost-Cursed Ogre
size: Large
type: Giant
alignment: Chaotic Evil
ac: 11
hp: 59
hit_dice: 7d10 + 21
speed: 40 ft.
stats: [19,8,16,5,7,7]
damage_immunities: Cold
senses: Darkvision 60 ft., Passive Perception 8
languages: Giant, understands the commands of Harann Nemmonis
cr: 2
traits:
  - name: Icy Demise
    desc: "When the ogre is reduced to 0 hit points, its body shatters into shards of ice. All creatures within 10 feet must succeed on a DC 10 Dexterity saving throw or take 6 (2d6) cold damage."
actions:
  - name: Greatclub
    desc: "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 13 (2d8 + 4) Bludgeoning damage"
```
^FrostCursedOgreStatblock

```statblock
layout: Basic 5e Layout
source: MTW
name: Azriel
size: Medium
type: Fiend (Tiefling)
alignment: Chaotic Neutral
ac: 14 (natural armor, layered cloak)
hp: 75
hit_dice: 10d8 + 30
speed: 30ft
stats: [12,16,16,14,12,16]
saves:
  - DEX: 5
  - CHA: 5
skillsaves:
  - Deception: 5
  - Insight: 3
  - Perception: 3
  - Stealth: 7
  - Survival: 3
senses: Darkvision 60 ft., Passive Perception 13
languages: Common, Infernal, Abyssal
cr: 3
traits:
  - name: Evasive Survivalist
    desc: "Azriel has advantage on Stealth checks made in snow, mist, or low light.\nWhen he takes damage from an attack he can see, he may use his reaction to halve it (once per round)."
  - name: Infernal Resistance
    desc: "Resistant to fire and cold damage; immune to poison"
  - name: Keen Observer
    desc: "Advantage on checks to recall symbols, uniforms, or heraldry."
actions:
  - name: Shortsword (Infernal Steel)
    desc: "Melee Weapon Attack: +5 to hit, 5 ft. reach, one target. Hit: 7 (1d8 + 3) slashing plus 4 (1d8) fire damage."
  - name: Scorching Sigil (Recharge 5–6)
    desc: "Azriel marks the ground or air within 30 ft.; a rune flares, releasing a 15-ft. cone of heat.\nEach creature in the cone must make a DC 13 Dexterity saving throw, taking 14 (4d6) fire damage on a failed save, or half as much on a success."
  - name: Shadow Step (Recharge 6)
    desc: "As a bonus action, Azriel teleports up to 30 ft. between areas of dim light or shadow he can see."
bonus_actions:
  - name: Cunning Dash
    desc: "Azriel takes the Dash, Disengage, or Hide action.\nFlicker of Flame. For 1 minute, faint embers dance over his body; ranged weapon attacks against him have disadvantage as heat distortion bends the air."
```

