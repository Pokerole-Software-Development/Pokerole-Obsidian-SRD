```
TABLE 
Strength+Dexterity+Vitality+Special+Insight AS Bases,
MaxStrength+MaxDexterity+MaxVitality+MaxSpecial+MaxInsight AS Maxes
from #PokeroleSRD/Pokedex 
where MegaEvolutions
```

```
TABLE 
Strength+Dexterity+Vitality+Special+Insight AS Bases,
MaxStrength+MaxDexterity+MaxVitality+MaxSpecial+MaxInsight AS Maxes
from #PokeroleSRD/Pokedex 
where contains(Name, "Mega-")
```

```dataview
TABLE 
Strength+Dexterity+Vitality+Special+Insight AS Bases,
link(join(["SRD", MegaEvolutions.Name],"-")).Strength+
link(join(["SRD", MegaEvolutions.Name],"-")).Dexterity+
link(join(["SRD", MegaEvolutions.Name],"-")).Vitality+
link(join(["SRD", MegaEvolutions.Name],"-")).Special+
link(join(["SRD", MegaEvolutions.Name],"-")).Insight AS Mega_Bases,
MaxStrength+MaxDexterity+MaxVitality+MaxSpecial+MaxInsight AS Maxes,
link(join(["SRD", MegaEvolutions.Name],"-")).MaxStrength+
link(join(["SRD", MegaEvolutions.Name],"-")).MaxDexterity+
link(join(["SRD", MegaEvolutions.Name],"-")).MaxVitality+
link(join(["SRD", MegaEvolutions.Name],"-")).MaxSpecial+
link(join(["SRD", MegaEvolutions.Name],"-")).MaxVitality AS Mega_Maxes
from #PokeroleSRD/Pokedex 
where MegaEvolutions
```