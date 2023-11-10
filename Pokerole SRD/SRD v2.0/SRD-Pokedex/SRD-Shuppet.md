---
Ability1: Insomnia
Ability2: Frisk
BookSprite: SRD-shuppet-BookSprite.png
BoxSprite: SRD-shuppet-BoxSprite.png
DexCategory: Puppet Pokemon
DexDescription: "They feed on dark emotions such as envy, jealousy and vengefulness.\
  \ If they sting you, they\u2019ll fill you with a vindictive desire. They don\u2019\
  t have bodies under their blanket and they are looking for a body to possess"
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Banette]]'
  Speed: Medium
GenderType: ''
Height:
  Feet: 2.0
  Meters: 0.6
HiddenAbility: Cursed Body
HomeSprite: SRD-shuppet-HomeSprite.png
Image: shuppet.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Knock Off|Knock Off]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Screech|Screech]]'
- - Beginner
  - '[[SRD-Night Shade|Night Shade]]'
- - Beginner
  - '[[SRD-Spite|Spite]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Will-O-Wisp|Will-O-Wisp]]'
- - Amateur
  - '[[SRD-Shadow Sneak|Shadow Sneak]]'
- - Amateur
  - '[[SRD-Curse|Curse]]'
- - Amateur
  - '[[SRD-Feint Attack|Feint Attack]]'
- - Amateur
  - '[[SRD-Hex|Hex]]'
- - Amateur
  - '[[SRD-Shadow Ball|Shadow Ball]]'
- - Amateur
  - '[[SRD-Snatch|Snatch]]'
- - Amateur
  - '[[SRD-Embargo|Embargo]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Grudge|Grudge]]'
- - Ace
  - '[[SRD-Trick|Trick]]'
- - Ace
  - '[[SRD-Phantom Force|Phantom Force]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Icy Wind|Icy Wind]]'
- - Pro
  - '[[SRD-Role Play|Role Play]]'
- - Pro
  - '[[SRD-Destiny Bond|Destiny Bond]]'
Number: 353
ShuffleToken: SRD-shuppet-ShuffleToken.png
Type1: Ghost
Type2: ''
Weight:
  Kilograms: 2.3
  Pounds: 5.1
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-shuppet-BookSprite.png|wsmall]]
> ![[SRD-shuppet-HomeSprite.png]]
> ![[SRD-shuppet-BoxSprite.png|htiny]]
> ![[SRD-shuppet-ShuffleToken.png|wsmall]]


*Puppet Pokemon*
*They feed on dark emotions such as envy, jealousy and vengefulness. If they sting you, they’ll fill you with a vindictive desire. They don’t have bodies under their blanket and they are looking for a body to possess*

**DexID**:: 0353
**Name**:: Shuppet
**Type**:: Ghost
**Abilities**:: [[SRD-Insomnia|Insomnia]] / [[SRD-Frisk|Frisk]] ([[SRD-Cursed Body|Cursed Body]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::4) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 2'0" / 0.6m
**Weight**: 5.1lbs / 2.3kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon         | Kind   | Speed   |
|:----------|:----------------|:-------|:--------|
| To        | [[SRD-Banette]] | Level  | Medium  |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Shuppet.md"
flatten moves as T
where file.path = this.file.path
```
