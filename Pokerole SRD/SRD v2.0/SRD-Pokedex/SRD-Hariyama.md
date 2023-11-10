---
Ability1: Thick Fat
Ability2: Guts
BookSprite: SRD-hariyama-BookSprite.png
BoxSprite: SRD-hariyama-BoxSprite.png
DexCategory: Arm Thrust Pokemon
DexDescription: They may appear fat, but they are pure muscle. Hariyamas have the
  habit of challenging big looking creatures to tests of strength, sometimes mistaking
  cars and machines for real Pokemon.
EventAbilities: ''
Evolutions:
- Evolves: From
  Kind: Level
  Pokemon: '[[SRD-Makuhita]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 7.5
  Meters: 2.3
HiddenAbility: Sheer Force
HomeSprite: SRD-hariyama-HomeSprite.png
Image: hariyama.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Focus Energy|Focus Energy]]'
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Arm Thrust|Arm Thrust]]'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Vital Throw|Vital Throw]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Brine|Brine]]'
- - Amateur
  - '[[SRD-Fake Out|Fake Out]]'
- - Amateur
  - '[[SRD-Whirlwind|Whirlwind]]'
- - Amateur
  - '[[SRD-Knock Off|Knock Off]]'
- - Amateur
  - '[[SRD-Smelling Salts|Smelling Salts]]'
- - Amateur
  - '[[SRD-Belly Drum|Belly Drum]]'
- - Amateur
  - '[[SRD-Force Palm|Force Palm]]'
- - Amateur
  - '[[SRD-Seismic Toss|Seismic Toss]]'
- - Amateur
  - '[[SRD-Wake-Up Slap|Wake-Up Slap]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Endure|Endure]]'
- - Ace
  - '[[SRD-Close Combat|Close Combat]]'
- - Ace
  - '[[SRD-Reversal|Reversal]]'
- - Ace
  - '[[SRD-Heavy Slam|Heavy Slam]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ice Punch|Ice Punch]]'
- - Pro
  - '[[SRD-Bullet Punch|Bullet Punch]]'
- - Pro
  - '[[SRD-Wide Guard|Wide Guard]]'
Number: 297
ShuffleToken: SRD-hariyama-ShuffleToken.png
Type1: Fighting
Type2: ''
Weight:
  Kilograms: 253.8
  Pounds: 559.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-hariyama-BookSprite.png|wsmall]]
> ![[SRD-hariyama-HomeSprite.png]]
> ![[SRD-hariyama-BoxSprite.png|htiny]]
> ![[SRD-hariyama-ShuffleToken.png|wsmall]]


*Arm Thrust Pokemon*
*They may appear fat, but they are pure muscle. Hariyamas have the habit of challenging big looking creatures to tests of strength, sometimes mistaking cars and machines for real Pokemon.*

**DexID**:: 0297
**Name**:: Hariyama
**Type**:: Fighting
**Abilities**:: [[SRD-Thick Fat|Thick Fat]] / [[SRD-Guts|Guts]] ([[SRD-Sheer Force|Sheer Force]])
**Base HP**:: 7

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::3)/(MaxStrength::7)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 7'5" / 2.3m
**Weight**: 559.5lbs / 253.8kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| From      | [[SRD-Makuhita]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Hariyama.md"
flatten moves as T
where file.path = this.file.path
```
