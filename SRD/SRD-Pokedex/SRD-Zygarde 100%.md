---
Ability1: Aura Break
Ability2: ''
BaseHP: 11
BoxSprite: SRD-BoxSprite-zygarde-10.png
DexID: 0718F3
Dexterity: 5
EventAbilities: ''
GenderType: N
GoodStarter: 'No'
HasAForm?: ''
HiddenAbility: ''
HomeSprite: SRD-HomeSprite-zygarde-10.png
Insight: 6
Legendary: 'Yes'
MaxDexterity: 5
MaxInsight: 6
MaxSpecial: 5
MaxStrength: 6
MaxVitality: 7
Name: Zygarde 100%
Number: 718
RecommendedRank: Master
Special: 5
Sprite: zygarde-10.png
Strength: 6
Type1: Dragon
Type2: Ground
Unevolved: 'No'
Vitality: 7
---

#PokeroleSRD/Pokedex

# `= this.name`

![[SRD-HomeSprite-zygarde-10.png|right]]

**DexID:** `= this.DexID`
**Type::** `= choice(length(this.Type2)=0, this.Type1,this.Type1+"/"+this.Type2)`
**Abilities::** `= choice(length(this.Ability2)=0, "[[SRD-"+this.Ability1+"|"+this.Ability1+"]]","[[SRD-"+this.Ability1+"|"+this.Ability1+"]]"+" / "+"[[SRD-"+this.Ability2+"|"+this.Ability2+"]]")` `= choice(length(this.HiddenAbility)=0,"","("+"[[SRD-"+this.HiddenAbility+"|"+this.HiddenAbility+"]]"+")")` `= choice(length(this.EventAbilities)=0,"","\<"+"[[SRD-"+this.EventAbilities+"|"+this.EventAbilities+"]]"+"\>")`
**Base HP:** `= this.BaseHP`

![[SRD-BoxSprite-zygarde-10.png|right]]

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

![[SRD-Zygarde 100%-Learnset]]