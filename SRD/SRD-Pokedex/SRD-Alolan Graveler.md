---
Ability1: Magnet Pull
Ability2: Sturdy
BaseHP: 4
BoxSprite: SRD-BoxSprite-graveler-alola.png
DexID: 0075A
Dexterity: 1
EventAbilities: ''
GenderType: ''
GoodStarter: 'No'
HasAForm?: ''
HiddenAbility: Galvanize
HomeSprite: SRD-HomeSprite-graveler-alola.png
Insight: 2
Legendary: 'No'
MaxDexterity: 3
MaxInsight: 4
MaxSpecial: 4
MaxStrength: 6
MaxVitality: 6
Name: Alolan Graveler
Number: 75
RecommendedRank: Amateur
Special: 2
Sprite: graveler-alola.png
Strength: 3
Type1: Rock
Type2: Electric
Unevolved: 'Yes'
Vitality: 3
---

#PokeroleSRD/Pokedex

# `= this.name`

![[SRD-HomeSprite-graveler-alola.png|right]]

**DexID:** `= this.DexID`
**Type::** `= choice(length(this.Type2)=0, this.Type1,this.Type1+"/"+this.Type2)`
**Abilities::** `= choice(length(this.Ability2)=0, "[[SRD-"+this.Ability1+"|"+this.Ability1+"]]","[[SRD-"+this.Ability1+"|"+this.Ability1+"]]"+" / "+"[[SRD-"+this.Ability2+"|"+this.Ability2+"]]")` `= choice(length(this.HiddenAbility)=0,"","("+"[[SRD-"+this.HiddenAbility+"|"+this.HiddenAbility+"]]"+")")` `= choice(length(this.EventAbilities)=0,"","\<"+"[[SRD-"+this.EventAbilities+"|"+this.EventAbilities+"]]"+"\>")`
**Base HP:** `= this.BaseHP`

![[SRD-BoxSprite-graveler-alola.png|right]]

|           |                                                                                        |                                          |
| --------- | -------------------------------------------------------------------------------------- | ---------------------------------------- |
| Strength  | `= padleft(padright("",this.MaxStrength - this.Strength,"⭘"),this.MaxStrength,"⬤")`    | `= this.Strength`/`= this.MaxStrength`   |
| Dexterity | `= padleft(padright("",this.MaxDexterity - this.Dexterity,"⭘"),this.MaxDexterity,"⬤")` | `= this.Dexterity`/`= this.MaxDexterity` |
| Vitality  | `= padleft(padright("",this.MaxVitality - this.Vitality,"⭘"),this.MaxVitality,"⬤")`    | `= this.Vitality`/`= this.MaxVitality`   |
| Special   | `= padleft(padright("",this.MaxSpecial - this.Special,"⭘"),this.MaxSpecial,"⬤")`       | `= this.Special`/`= this.MaxSpecial`     |
| Insight   | `= padleft(padright("",this.MaxInsight - this.Insight,"⭘"),this.MaxInsight,"⬤")`       | `= this.Insight`/`= this.MaxInsight`     |

**Recommended Rank:** `= this.RecommendedRank`
**Good Starting Pokemon?** `= this.GoodStarter`
**Can Evolve?** `= this.Unevolved`

![[SRD-Alolan Graveler-Learnset]]