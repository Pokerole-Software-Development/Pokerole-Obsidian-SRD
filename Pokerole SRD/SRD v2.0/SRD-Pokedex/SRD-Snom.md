---
Ability1: Shield Dust
Ability2: ''
BookSprite: SRD-snom-BookSprite.png
BoxSprite: SRD-snom-BoxSprite.png
DexCategory: Worm Pokemon
DexDescription: It spits out thread imbued with a frigid energy and uses it to tie
  its body to branches, disguising itself as an icicle while it sleeps. It feeds only
  of snow, if it melts it will freeze it again to continue eating.
EventAbilities: ''
Evolutions:
- Evolves: To
  Kind: Stat
  Pokemon: '[[SRD-Frosmoth]]'
  Stat: Happiness
  Value: 5
GenderType: ''
Height:
  Feet: 1.0
  Meters: 0.3
HiddenAbility: Ice Scales
HomeSprite: SRD-snom-HomeSprite.png
Image: snom.png
Legendary: 'No'
Moves:
- - Starter
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Powder Snow|Powder Snow]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Struggle Bug|Struggle Bug]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Rest|Rest]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Snore|Snore]]'
- - Pro
  - '[[Pokerole SRD/SRD v2.0/SRD-Moves/SRD-Bug Bite|Bug Bite]]'
Number: 872
ShuffleToken: SRD-snom-ShuffleToken.png
Type1: Ice
Type2: Bug
Weight:
  Kilograms: 3.8
  Pounds: 8.4
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-snom-BookSprite.png|wsmall]]
> ![[SRD-snom-HomeSprite.png]]
> ![[SRD-snom-BoxSprite.png|htiny]]
> ![[SRD-snom-ShuffleToken.png|wsmall]]


*Worm Pokemon*
*It spits out thread imbued with a frigid energy and uses it to tie its body to branches, disguising itself as an icicle while it sleeps. It feeds only of snow, if it melts it will freeze it again to continue eating.*

**DexID**:: 0872
**Name**:: Snom
**Type**:: Ice / Bug
**Abilities**:: [[SRD-Shield Dust|Shield Dust]] ([[SRD-Ice Scales|Ice Scales]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::1)/(MaxStrength::3)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 1)/(MaxDexterity::3) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::1)/(MaxVitality::3)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::1)/(MaxInsight::3)     |

**Height**: 1'0" / 0.3m
**Weight**: 8.4lbs / 3.8kg
**Good Starter**:: Yes
**Recommended Rank**:: Starter

| Evolves   | Pokemon          | Kind   | Stat      |   Value |
|:----------|:-----------------|:-------|:----------|--------:|
| To        | [[SRD-Frosmoth]] | Stat   | Happiness |       5 |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Snom.md"
flatten moves as T
where file.path = this.file.path
```
