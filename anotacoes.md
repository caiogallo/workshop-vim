## Teclas de movimentação
h - esquerda
j - baixo
k - cima
l - direita

## expressões regulares
:g  

### find and replace (s/)
:g/^$/s/^$/-----           " troca espacos por -----

### separar regex (,/)
:g/s$/,/ro$/d              " apaga tudo terminado em 's' e 'ro'

## usar comandos vim no terminal
set -o vi

## Split de tela

### configurar e fazer os splits
:set splitright      " pode colocar no .vimrc
:e <arquivo>         " abre arquivo janela atual
:sp <arquivo>        " abre arquivo abaixo
:vs <arquivo>        " abre arquivo a direita

### navegar entre as janelas
ctrl+w <tecla movimentacao>
ctrl+w =             " normaliza as janelas

## abas

### abrir nova tab
:tabnew <arquivo>

### navegação entre tabs
:gt                  " próxima tab
:gT                  " anterior

## Sessões (atalhos mapeados no .vimrc)
ms                   " criar
rs                   " restaurar

## Correção Ortográfica (atalhos mapeados no .vimrc)
spon                 " ligar
spof                 " desligar

### navegar nas palavras erradas
]s                   " vai para a próxima
[s                   " vai para anterior

### sugestões
modo normal: z=
modo inserção: ctrl+x s

