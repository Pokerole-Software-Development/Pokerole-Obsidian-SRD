---
Ability1: Shed Skin
Ability2: ''
BaseHP: 4
BoxSprite: SRD-BoxSprite-kakuna.png
DexID: '0014'
Dexterity: 1
EventAbilities: ''
GenderType: ''
GoodStarter: 'Yes'
HasAForm?: ''
HiddenAbility: ''
HomeSprite: SRD-HomeSprite-kakuna.png
Insight: 1
Legendary: 'No'
MaxDexterity: 3
MaxInsight: 3
MaxSpecial: 3
MaxStrength: 3
MaxVitality: 4
Name: Kakuna
Number: 14
RecommendedRank: Beginner
Special: 1
Sprite: kakuna.png
Strength: 1
Type1: Bug
Type2: Poison
Unevolved: 'Yes'
Vitality: 2
---

#PokeroleSRD/Pokedex

# `= this.name`

![[SRD-HomeSprite-kakuna.png|right]]

**DexID:** `= this.DexID`
**Type::** `= choice(length(this.Type2)=0, this.Type1,this.Type1+"/"+this.Type2)`
**Abilities::** `= choice(length(this.Ability2)=0, "[[SRD-"+this.Ability1+"|"+this.Ability1+"]]","[[SRD-"+this.Ability1+"|"+this.Ability1+"]]"+" / "+"[[SRD-"+this.Ability2+"|"+this.Ability2+"]]")` `= choice(length(this.HiddenAbility)=0,"","("+"[[SRD-"+this.HiddenAbility+"|"+this.HiddenAbility+"]]"+")")` `= choice(length(this.EventAbilities)=0,"","\<"+"[[SRD-"+this.EventAbilities+"|"+this.EventAbilities+"]]"+"\>")`
**Base HP:** `= this.BaseHP`

![[SRD-BoxSprite-kakuna.png|right]]

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

![[SRD-Kakuna-Learnset]]