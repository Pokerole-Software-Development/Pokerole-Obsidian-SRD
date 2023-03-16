---
Ability1: Fur Coat
Ability2: ''
BookSprite: SRD-furfrou-BookSprite.png
BoxSprite: SRD-furfrou-BoxSprite.png
DexCategory: Poodle Pokemon
DexDescription: Historically, these Pokemon were the designated guardians of the kings.
  They are popular pets now and people love to trim their fur into exotic hairstyles.
  But their protective nature has never been lost.
EventAbilities: ''
Evolutions: []
GenderType: ''
Height:
  Feet: 3.9
  Meters: 1.2
HiddenAbility: ''
HomeSprite: SRD-furfrou-HomeSprite.png
Image: furfrou.png
Legendary: 'No'
Moves:
- - Starter
  - '[[SRD-Tackle|Tackle]]'
- - Starter
  - '[[SRD-Growl|Growl]]'
- - '---------------------------'
  - '---------------------------'
- - Beginner
  - '[[SRD-Sand Attack|Sand Attack]]'
- - Beginner
  - '[[SRD-Baby-Doll Eyes|Baby-Doll Eyes]]'
- - Beginner
  - '[[SRD-Take Down|Take Down]]'
- - '---------------------------'
  - '---------------------------'
- - Amateur
  - '[[SRD-Tail Whip|Tail Whip]]'
- - Amateur
  - '[[SRD-Bite|Bite]]'
- - Amateur
  - '[[SRD-Odor Sleuth|Odor Sleuth]]'
- - Amateur
  - '[[SRD-Retaliate|Retaliate]]'
- - Amateur
  - '[[SRD-Headbutt|Headbutt]]'
- - Amateur
  - '[[SRD-Charm|Charm]]'
- - '---------------------------'
  - '---------------------------'
- - Ace
  - '[[SRD-Sucker Punch|Sucker Punch]]'
- - Ace
  - '[[SRD-Cotton Guard|Cotton Guard]]'
- - '---------------------------'
  - '---------------------------'
- - Pro
  - '[[SRD-Hyper Voice|Hyper Voice]]'
- - Pro
  - '[[SRD-Last Resort|Last Resort]]'
- - Pro
  - '[[SRD-Work Up|Work Up]]'
Number: 676
ShuffleToken: SRD-furfrou-ShuffleToken.png
Type1: Normal
Type2: ''
Weight:
  Kilograms: 28.0
  Pounds: 61.7
---

#PokeroleSRD/Pokedex

# `= this.name`

> [!grid]
> ![[SRD-furfrou-BookSprite.png|wsmall]]
> ![[SRD-furfrou-HomeSprite.png]]
> ![[SRD-furfrou-BoxSprite.png|htiny]]
> ![[SRD-furfrou-ShuffleToken.png|wsmall]]


*Poodle Pokemon*
*Historically, these Pokemon were the designated guardians of the kings. They are popular pets now and people love to trim their fur into exotic hairstyles. But their protective nature has never been lost.*

**DexID**:: 0676
**Name**:: Furfrou
**Type**:: Normal
**Abilities**:: [[SRD-Fur Coat|Fur Coat]]
**Base HP**:: 4

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | (Strength::2)/(MaxStrength::5)   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | (Dexterity:: 3)/(MaxDexterity::6) |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | (Vitality::2)/(MaxVitality::4)   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | (Special::2)/(MaxSpecial::4)     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | (Insight::2)/(MaxInsight::5)     |

**Height**: 3'9" / 1.2m
**Weight**: 61.7lbs / 28.0kg
**Good Starter**:: No
**Recommended Rank**:: Amateur

## Learnset

```dataview
TABLE WITHOUT ID
    T[0] AS Learned,
    T[1].Type AS Type,
    T[1] AS Move
FROM "SRD/SRD-Pokedex/SRD-Furfrou.md"
flatten moves as T
where file.path = this.file.path
```
