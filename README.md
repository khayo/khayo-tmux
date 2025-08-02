# Referências
https://quickref.me/tmux.html

# Quick start
Clone o repositorio:
```bash
git clone https://github.com/khayo/khayo-tmux.git ~/.config/tmux
```

Rode o instalador:
```
~/.config/tmux/./install.sh
```

# Instalação TPM
Para que tudo funcione corretamente é necessário instalar o gerenciador de plugins TPM
```bash
git clone https://github.com/tmux-plugins/tpm ~/.config/tmux/plugins/tpm
```

# Ctrl + a + ?
mostra teclas de atalho do sistema

# Ctrl + a + I(capital i)
instala plugins

# Comandos comuns
## Ctrl + a + z
Full screen do panel selecionado

## Ctrl + a + d 
Detach da sessao

## Ctrl + (h,j,k,l)
Movimento entre panels

## Ctrl + a + (h,j,k,l)
Resize do panel

## Ctrl + a + t
Modo relogio

# Volta para uma sessão fechada
## Mostra sessoes existentes 
```bash
tmux ls
```
## Conecta na sessão escolhida
```bash
tmux attach -t n 
```
Onde 'n' é o numero da sessão   

