```dataview
TABLE 
E.Pokemon as "Evolves To"
from #PokeroleSRD/Pokedex 
flatten 
filter(Evolutions, (x) => x.Speed = "Slow" and x.Evolves = "To") as E
```