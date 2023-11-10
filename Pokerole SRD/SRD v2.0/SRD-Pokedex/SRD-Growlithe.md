---
Ability1: Intimidate
Ability2: Flash Fire
BookSprite: SRD-growlithe-BookSprite.png
BoxSprite: SRD-growlithe-BoxSprite.png
DexCategory: Puppy Pokemon
DexDescription: Friendly, loyal and fearless to defend its trainer. These traits have
  gained them a place working as police Pokemon. They are uncommon in the wild but
  some packs can be seen in hot environments.
EventAbilities: ''
Evolutions:
- Evolves: To
  Item: Fire Stone
  Kind: Stone
  Pokemon: '[[SRD-Arcanine]]'
GenderType: ''
Height:
  Feet: 2.3
  Meters: 0.7
HiddenAbility: Justified
HomeSprite: SRD-growlithe-HomeSprite.png
Image: growlithe.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Roar|Roar]]'
- - Starter
  - '[[SRD-Bite|Bite]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Ember|Ember]]'
- - Beginner
  - '[[SRD-Leer|Leer]]'
- - Beginner
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Beginner
  - '[[SRD-Helping Hand|Helping Hand]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Flame Wheel|Flame Wheel]]'
- - Amateur
  - '[[SRD-Reversal|Reversal]]'
- - Amateur
  - '[[SRD-Fire Fang|Fire Fang]]'
- - Amateur
  - '[[SRD-Take Down|Take Down]]'
- - Amateur
  - '[[SRD-Flame Burst|Flame Burst]]'
- - Amateur
  - '[[SRD-Agility|Agility]]'
- - Amateur
  - '[[SRD-Retaliate|Retaliate]]'
- - Amateur
  - '[[SRD-Flamethrower|Flamethrower]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Crunch|Crunch]]'
- - Ace
  - '[[SRD-Heat Wave|Heat Wave]]'
- - Ace
  - '[[SRD-Outrage|Outrage]]'
- - Ace
  - '[[SRD-Flare Blitz|Flare Blitz]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Howl|Howl]]'
- - Pro
  - '[[SRD-Close Combat|Close Combat]]'
- - Pro
  - '[[SRD-Charm|Charm]]'
Number: 58
ShuffleToken: SRD-growlithe-ShuffleToken.png
Type1: Fire
Type2: ''
Weight:
  Kilograms: 19.0
  Pounds: 41.9
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-growlithe-BookSprite.png|wsmall]]
> ![[SRD-growlithe-HomeSprite.png]]
> ![[SRD-growlithe-BoxSprite.png|htiny]]
> ![[SRD-growlithe-ShuffleToken.png|wsmall]]


*Puppy Pokemon*
*Friendly, loyal and fearless to defend its trainer. These traits have gained them a place working as police Pokemon. They are uncommon in the wild but some packs can be seen in hot environments.*

**DexID**:: 0058
**Name**:: Growlithe
**Type**:: Fire
**Abilities**:: [[SRD-Intimidate|Intimidate]] / [[SRD-Flash Fire|Flash Fire]] ([[SRD-Justified|Justified]])
**Base HP**:: 3

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 2)/(MaxDexterity::5) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::5)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::4)     |

**Height**: 2'3" / 0.7m
**Weight**: 41.9lbs / 19.0kg
**Good Starter**:: Yes
**Recommended Rank**:: Beginner

| Evolves   | Pokemon          | Kind   | Item       |
|:----------|:-----------------|:-------|:-----------|
| To        | [[SRD-Arcanine]] | Stone  | Fire Stone |

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "/Users/bill/Code/Pokerole SRD/Pokerole SRD/SRD v2.0/SRD-Pokedex/SRD-Growlithe.md"
flatten moves as T
where file.path = this.file.path
```
