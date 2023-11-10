---
Ability1: Wimp Out
Ability2: ''
BookSprite: SRD-wimpod-BookSprite.png
BoxSprite: SRD-wimpod-BoxSprite.png
DexCategory: Turn Tail Pokemon
DexDescription: They are curious but incredibly cowardly Pokemon. They are easily
  startled and will shoot a stenchy liquid as a warning. Even so, they are highly
  valued due to their ability to eat and clean any garbage.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Level
  Pokemon: '[[SRD-Golisopod]]'
  Speed: Slow
GenderType: ''
Height:
  Feet: 1.6
  Meters: 0.5
HiddenAbility: ''
HomeSprite: SRD-wimpod-HomeSprite.png
Image: wimpod.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Struggle Bug|Struggle Bug]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Harden|Harden]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Aqua Jet|Aqua Jet]]'
- - Pro
  - '[[SRD-Spikes|Spikes]]'
Number: 767
ShuffleToken: SRD-wimpod-ShuffleToken.png
Type1: Bug
Type2: Water
Weight:
  Kilograms: 12.0
  Pounds: 26.5
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-wimpod-BookSprite.png|wsmall]]
> ![[SRD-wimpod-HomeSprite.png]]
> ![[SRD-wimpod-BoxSprite.png|htiny]]
> ![[SRD-wimpod-ShuffleToken.png|wsmall]]


*Turn Tail Pokemon*
*They are curious but incredibly cowardly Pokemon. They are easily startled and will shoot a stenchy liquid as a warning. Even so, they are highly valued due to their ability to eat and clean any garbage.*

**DexID**:: 0767
**Name**:: Wimpod
**Type**:: Bug / Water
**Abilities**:: [[SRD-Wimp Out|Wimp Out]]
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::1)/(MaxSpecial::3)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'6" / 0.5m
**Weight**: 26.5lbs / 12.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon           | Kind   | Speed   |
|:----------|:------------------|:-------|:--------|
| To        | [[SRD-Golisopod]] | Level  | Slow    |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Wimpod.md"
flatten moves as T
where file.path = this.file.path
```
