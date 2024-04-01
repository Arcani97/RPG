---
cssclasses:
  - dashboard
  - tableitens
tags: MoC
---

# Armaduras

```dataview
table without id file.link as Item, Tipo,  PreçoVisivel as Preço, Espaço as Tamanho
from #Item
where contains(Tipo, "Armadura") or contains(Tipo, "Escudo")
sort file.name asc
sort Preço asc
sort Tipo asc
```

# Armas Simples

```dataview
table without id file.link as Item, Tipo,  PreçoVisivel as Preço, Espaço as Tamanho
from #Item/Arma/Simples
sort file.name asc
sort Tipo asc
```

# Armas Marciais

```dataview
table without id file.link as Item, Tipo, PreçoVisivel as Preço, Espaço as Tamanho
from #Item/Arma/Marcial
sort file.name asc
sort Tipo asc
```

# Armas de Fogo

```dataview
table without id file.link as Item, Tipo, PreçoVisivel as Preço, Espaço as Tamanho
from #Item/Arma/de-Fogo
sort file.name asc
sort Preço asc
```

# Itens Gerais

```dataview
table without id file.link as Item, Tipo, PreçoVisivel as Preço, Espaço as Tamanho
from #Item/Equipamento
sort file.name asc
sort Tipo asc
```

# Ferramentas

```dataview
table without id file.link as Item, Tipo, PreçoVisivel as Preço, Espaço as Tamanho
from #Item/Ferramenta
sort file.name asc
sort Tipo asc
```

# Bens de Comércio

```dataview
table without id file.link as Item, Tipo, PreçoVisivel as Preço, Espaço as Tamanho
from #Item/Bens-de-Comércio
sort file.name asc
sort Preço asc
```
