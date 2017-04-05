# Anotações

## Teclas de movimentação
h - esquerda  
j - baixo  
k - cima  
l - direita

## expressões regulares
```VimL
:g  
```

### find and replace (s/)

```VimL
:g/^$/s/^$/-----           " troca espacos por -----
```

### separar regex (,/)
```VimL
:g/s$/,/ro$/d              " apaga tudo terminado em 's' e 'ro'
```

## usar comandos vim no terminal
```VimL
set -o vi
```

## Split de tela

### configurar e fazer os splits

```VimL
:set splitright      " pode colocar no .vimrc  
:e <arquivo>         " abre arquivo janela atual  
:sp <arquivo>        " abre arquivo abaixo  
:vs <arquivo>        " abre arquivo a direita  
```

### navegar entre as janelas

```VimL
ctrl+w <tecla movimentacao>  
ctrl+w =             " normaliza as janelas
```

## abas

### abrir nova tab
```VimL
:tabnew <arquivo>
```

### navegação entre tabs

```VimL
:gt                  " próxima tab  
:gT                  " anterior
```

## Sessões (atalhos mapeados no .vimrc)
```VimL
ms                   " criar  
rs                   " restaurar
```

## Correção Ortográfica (atalhos mapeados no .vimrc)
```VimL
spon                 " ligar  
spof                 " desligar
```

### navegar nas palavras erradas
```VimL
]s                   " vai para a próxima  
[s                   " vai para anterior
```
### sugestões
```VimL
modo normal: z=  
modo inserção: ctrl+x s
```

## Mais Informações:

* https://vim-adventures.com/
* http://www.openvim.com/
* http://www.vimgenius.com/
