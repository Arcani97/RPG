---
cssclasses:
  - center-h
banner: "![[Banner.webp]]"
banner_x: 0.5
banner_y: 0.7
---


```meta-bind-button
label: Novo NPC
hidden: true
class: "botaolargura botaobold botaogreen"
tooltip: ""
id: npc
style: primary
actions:
  - type: templaterCreateNote
    templateFile: 1 Modelos/NPC.md
    folderPath: Npcs
    fileName: Novo NPC
    openNote: true
  - type: command
    command: workspace:edit-file-title

```

```meta-bind-button
label: Novo Item
hidden: true
class: "botaolargura botaobold botaogreen"
tooltip: ""
id: item
style: primary
actions:
  - type: templaterCreateNote
    templateFile: 1 Modelos/Item.md
    folderPath: Itens
    fileName: Novo Item
    openNote: true
  - type: command
    command: workspace:edit-file-title

```

```meta-bind-button
label: Nova Erva
hidden: true
class: "botaolargura botaobold botaogreen"
tooltip: ""
id: erva
style: primary
actions:
  - type: templaterCreateNote
    templateFile: 1 Modelos/Erva.md
    folderPath: Herbário
    fileName: Nova Erva
    openNote: true
  - type: command
    command: workspace:edit-file-title

```

```meta-bind-button
label: Novo Veículo
hidden: true
class: "botaolargura botaobold botaogreen"
tooltip: ""
id: veiculo
style: primary
actions:
  - type: templaterCreateNote
    templateFile: 1 Modelos/Veículo.md
    folderPath: Veículos
    fileName: Novo Veículo
    openNote: true
  - type: command
    command: workspace:edit-file-title

```

```meta-bind-button
label: Nova Classe
hidden: true
class: "botaolargura botaobold botaogreen"
tooltip: ""
id: classe
style: primary
actions:
  - type: templaterCreateNote
    templateFile: 1 Modelos/Classe.md
    folderPath: Classes
    fileName: Nova Classe
    openNote: true
  - type: command
    command: workspace:edit-file-title

```

```meta-bind-button
label: Itens
hidden: true
class: "botaolargura botaobold botaoblue"
tooltip: ""
id: moc-itens
style: primary
actions:
  - type: open
    link: "[[Itens]]"

```

```meta-bind-button
label: Veículos
hidden: true
class: "botaolargura botaobold botaoblue"
tooltip: ""
id: moc-veiculos
style: primary
actions:
  - type: open
    link: "[[Veículos]]"

```

```meta-bind-button
label: Herbário
hidden: true
class: "botaolargura botaobold botaoblue"
tooltip: ""
id: moc-ervas
style: primary
actions:
  - type: open
    link: "[[Herbário]]"

```

```meta-bind-button
label: Regras da Casa
hidden: true
class: "botaolargura botaobold botaoblue"
tooltip: ""
id: moc-regrascasa
style: primary
actions:
  - type: open
    link: "[[Regras da Casa]]"

```

```meta-bind-button
label: Classes
hidden: true
class: "botaolargura botaobold botaoblue"
tooltip: ""
id: moc-classes
style: primary
actions:
  - type: open
    link: "[[Classes]]"

```

## Comandos

`BUTTON[npc]`  `BUTTON[item]`  `BUTTON[erva]`  `BUTTON[veiculo]`  `BUTTON[classe]`

**⠀**

# Menu

`BUTTON[moc-regrascasa]`  `BUTTON[moc-itens]`  `BUTTON[moc-ervas]`  `BUTTON[moc-veiculos]`  `BUTTON[moc-classes]`


