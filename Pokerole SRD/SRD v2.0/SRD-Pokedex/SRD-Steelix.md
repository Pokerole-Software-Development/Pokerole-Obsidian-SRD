---
Ability1: Rock Head
Ability2: Sturdy
BookSprite: SRD-steelix-BookSprite.png
BoxSprite: SRD-steelix-BoxSprite.png
DexCategory: Iron Snake Pokemon
DexDescription: "Some say that when an Onix lives underground for 100 years it\u2019\
  s body becomes hard as steel. Steelix lives deep underground, tempered by high pressure\
  \ and heat. It can see in the darkness."
EventAbilities: ''
Evolutions:
- Evolves: From
  Item: Metal Coat
  Kind: Trade
  Pokemon: '[[SRD-Onix]]'
- Evolves: To
  Item: Steelixite
  Kind: Mega
  Pokemon: '[[SRD-Steelix (Mega Form)]]'
GenderType: ''
Height:
  Feet: 30.2
  Meters: 9.2
HiddenAbility: Sheer Force
HomeSprite: SRD-steelix-HomeSprite.png
Image: steelix.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Bind|Bind]]'
- - Starter
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - Starter
  - '[[SRD-Ice Fang|Ice Fang]]'
- - Starter
  - '[[SRD-Mud Sport|Mud Sport]]'
- - Starter
  - '[[SRD-Thunder Fang|Thunder Fang]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Curse|Curse]]'
- - Beginner
  - '[[SRD-Rock Throw|Rock Throw]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Rock Tomb|Rock Tomb]]'
- - Amateur
  - '[[SRD-Rage|Rage]]'
- - Amateur
  - '[[SRD-Stealth Rock|Stealth Rock]]'
- - Amateur
  - '[[SRD-Autotomize|Autotomize]]'
- - Amateur
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - Amateur
  - '[[SRD-Smack Down|Smack Down]]'
- - Amateur
  - '[[SRD-Dragon Breath|Dragon Breath]]'
- - Amateur
  - '[[SRD-Slam|Slam]]'
- - Amateur
  - '[[SRD-Screech|Screech]]'
- - Amateur
  - '[[SRD-Rock Slide|Rock Slide]]'
- - Amateur
  - '[[SRD-Crunch|Crunch]]'
- - Amateur
  - '[[SRD-Iron Tail|Iron Tail]]'
- - Amateur
  - '[[SRD-Dig|Dig]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sandstorm|Sandstorm]]'
- - Ace
  - '[[SRD-Stone Edge|Stone Edge]]'
- - Ace
  - '[[SRD-Double-Edge|Double-Edge]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Ancient Power|Ancient Power]]'
- - Pro
  - '[[SRD-Aqua Tail|Aqua Tail]]'
- - Pro
  - '[[SRD-Twister|Twister]]'
Number: 208
ShuffleToken: SRD-steelix-ShuffleToken.png
Type1: Steel
Type2: Ground
Weight:
  Kilograms: 400.0
  Pounds: 881.8
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-steelix-BookSprite.png|wsmall]]
> ![[SRD-steelix-HomeSprite.png]]
> ![[SRD-steelix-BoxSprite.png|htiny]]
> ![[SRD-steelix-ShuffleToken.png|wsmall]]


*Iron Snake Pokemon*
*Some say that when an Onix lives underground for 100 years it’s body becomes hard as steel. Steelix lives deep underground, tempered by high pressure and heat. It can see in the darkness.*

**DexID**:: 0208
**Name**:: Steelix
**Type**:: Steel / Ground
**Abilities**:: [[SRD-Rock Head|Rock Head]] / [[SRD-Sturdy|Sturdy]] ([[SRD-Sheer Force|Sheer Force]])
**Base HP**:: 9

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::5)/(MaxVitality::10)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 30'2" / 9.2m
**Weight**: 881.8lbs / 400.0kg
**Good Starter**:: No
**Recommended Rank**:: Pro

| Evolves   | Pokemon                     | Kind   | Item       |
|:----------|:----------------------------|:-------|:-----------|
| From      | [[SRD-Onix]]                | Trade  | Metal Coat |
| To        | [[SRD-Steelix (Mega Form)]] | Mega   | Steelixite |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Steelix.md"
flatten moves as T
where file.path = this.file.path
```
