---
cssclasses:
  - dashboard
  - tableveiculos
tags: MoC
---

# Terrestres

```dataview
table without id file.link as Item, Velocidade, Passageiros, Tripulantes, Carga,  PreçoVisivel as Preço, Manutenção as "Manutenção (30d)"
from #Veículo
where contains(Tipo, "Terrestre")
sort file.name asc
sort Preço asc
```

# Aquáticos

```dataview
table without id file.link as Item, Velocidade, Passageiros, Tripulantes, Carga,  PreçoVisivel as Preço, Manutenção as "Manutenção (30d)"
from #Veículo
where contains(Tipo, "Aquático")
sort file.name asc
sort Preço asc
```

# Aéreos

```dataview
table without id file.link as Item, Velocidade, Passageiros, Tripulantes, Carga,  PreçoVisivel as Preço, Manutenção as "Manutenção (30d)"
from #Veículo
where contains(Tipo, "Aéreo")
sort file.name asc
sort Preço asc
```
