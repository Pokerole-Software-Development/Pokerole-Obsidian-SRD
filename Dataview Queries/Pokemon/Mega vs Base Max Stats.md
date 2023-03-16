```dataview
TABLE 
embed(link(BookSprite)),
sum(Evolutions.Pokemon.Strength+
Evolutions.Pokemon.Dexterity+
Evolutions.Pokemon.Vitality+
Evolutions.Pokemon.Special+
Evolutions.Pokemon.Insight) AS Bases,
Strength+Dexterity+Vitality+Special+Insight AS Mega_Bases,
Evolutions.Pokemon.MaxStrength+
Evolutions.Pokemon.MaxDexterity+
Evolutions.Pokemon.MaxVitality+
Evolutions.Pokemon.MaxSpecial+
Evolutions.Pokemon.MaxVitality AS Mega_Maxes,
MaxStrength+MaxDexterity+MaxVitality+MaxSpecial+MaxInsight AS Mega_Maxes
from #PokeroleSRD/Pokedex 
flatten filter(Evolutions, (x) => x.Kind = "Mega")
Where contains(Name, "Mega")
```