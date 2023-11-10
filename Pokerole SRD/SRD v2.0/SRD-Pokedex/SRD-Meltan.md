---
Ability1: Magnet Pull
Ability2: ''
BookSprite: SRD-meltan-BookSprite.png
BoxSprite: SRD-meltan-BoxSprite.png
DexCategory: Hex Nut Pokemon
DexDescription: They are elusive as they can liquefy their body to move through small
  spaces. They live in groups, but when the time comes, one strong Meltan will absorb
  all the others and evolve.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Melmetal]]'
  Speed: Unknown
GenderType: N
Height:
  Feet: 0.7
  Meters: 0.2
HiddenAbility: ''
HomeSprite: SRD-meltan-HomeSprite.png
Image: meltan.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Thunder Shock|Thunder Shock]]'
- - Starter
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Beginner
  - '[[SRD-Headbutt|Headbutt]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Thunder Wave|Thunder Wave]]'
- - Amateur
  - '[[SRD-Acid Armor|Acid Armor]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Flash Cannon|Flash Cannon]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Protect|Protect]]'
- - Pro
  - '[[SRD-Gyro Ball|Gyro Ball]]'
- - Pro
  - '[[SRD-Steel Beam|Steel Beam]]'
Number: 808
ShuffleToken: SRD-meltan-ShuffleToken.png
Type1: Steel
Type2: ''
Weight:
  Kilograms: 8.0
  Pounds: 17.6
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-meltan-BookSprite.png|wsmall]]
> ![[SRD-meltan-HomeSprite.png]]
> ![[SRD-meltan-BoxSprite.png|htiny]]
> ![[SRD-meltan-ShuffleToken.png|wsmall]]


*Hex Nut Pokemon*
*They are elusive as they can liquefy their body to move through small spaces. They live in groups, but when the time comes, one strong Meltan will absorb all the others and evolve.*

**DexID**:: 0808
**Name**:: Meltan
**Type**:: Steel
**Abilities**:: [[SRD-Magnet Pull|Magnet Pull]]
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::4)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 0'7" / 0.2m
**Weight**: 17.6lbs / 8.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

| Evolves   | Pokemon          | Kind   | Speed   |
|:----------|:-----------------|:-------|:--------|
| To        | [[SRD-Melmetal]] | Level  | Unknown |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Meltan.md"
flatten moves as T
where file.path = this.file.path
```
