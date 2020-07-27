# AKA

## Description
```
Cows are following me everywhere I go. Help, I'm trapped!

nc chall.csivit.com 30611
```

## Preview
The mad-cow appears when you enter a command.
```
user @ csictf: $
ls
 ________________________________________
/ Don't look at me, I'm just here to say \
\ moo.                                   /
 ----------------------------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
user @ csictf: $
pwd
 ________________________________________
/ Don't look at me, I'm just here to say \
\ moo.                                   /
 ----------------------------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
user @ csictf: $
```

## Checkpoint
```
user @ csictf: $
alias
alias awk='cowsay Don\'\''t look at me, I\'\''m just here to say moo.'
alias cat='cowsay Don\'\''t look at me, I\'\''m just here to say moo.'
alias cd='cowsay Don\'\''t look at me, I\'\''m just here to say moo.'
alias find='cowsay Don\'\''t look at me, I\'\''m just here to say moo.'
alias grep='cowsay Don\'\''t look at me, I\'\''m just here to say moo.'
alias head='cowsay Don\'\''t look at me, I\'\''m just here to say moo.'
alias less='cowsay Don\'\''t look at me, I\'\''m just here to say moo.'
alias ls='cowsay Don\'\''t look at me, I\'\''m just here to say moo.'
alias more='cowsay Don\'\''t look at me, I\'\''m just here to say moo.'
alias pwd='cowsay Don\'\''t look at me, I\'\''m just here to say moo.'
alias sed='cowsay Don\'\''t look at me, I\'\''m just here to say moo.'
alias tail='cowsay Don\'\''t look at me, I\'\''m just here to say moo.'

user @ csictf: $
alias ls='ls'

user @ csictf: $
alias cat='cat'

user @ csictf: $
ls
flag.txt
script.sh
start.sh

user @ csictf: $
cat flag.txt
```

## Flag
csictf{1_4m_cl4rk3_k3nt}
