---
Ability1: Pressure
Ability2: ''
BaseHP: 4
BoxSprite: SRD-BoxSprite-deoxys-speed.png
DexID: 0386F3
Dexterity: 10
EventAbilities: ''
GenderType: N
GoodStarter: 'No'
HasAForm?: 'Yes'
HiddenAbility: ''
HomeSprite: SRD-HomeSprite-deoxys-speed.png
Insight: 5
Legendary: 'Yes'
MaxDexterity: 10
MaxInsight: 5
MaxSpecial: 6
MaxStrength: 6
MaxVitality: 5
Name: Speed Deoxys
Number: 386
RecommendedRank: Master
Special: 6
Sprite: deoxys-speed.png
Strength: 6
Type1: Psychic
Type2: ''
Unevolved: 'No'
Vitality: 5
---

#PokeroleSRD/Pokedex

# `= this.name`

![[SRD-HomeSprite-deoxys-speed.png|right]]

**DexID:** `= this.DexID`
**Type::** `= choice(length(this.Type2)=0, this.Type1,this.Type1+"/"+this.Type2)`
**Abilities::** `= choice(length(this.Ability2)=0, "[[SRD-"+this.Ability1+"|"+this.Ability1+"]]","[[SRD-"+this.Ability1+"|"+this.Ability1+"]]"+" / "+"[[SRD-"+this.Ability2+"|"+this.Ability2+"]]")` `= choice(length(this.HiddenAbility)=0,"","("+"[[SRD-"+this.HiddenAbility+"|"+this.HiddenAbility+"]]"+")")` `= choice(length(this.EventAbilities)=0,"","\<"+"[[SRD-"+this.EventAbilities+"|"+this.EventAbilities+"]]"+"\>")`
**Base HP:** `= this.BaseHP`

![[SRD-BoxSprite-deoxys-speed.png|right]]

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

![[SRD-Speed Deoxys-Learnset]]