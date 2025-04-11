# Atividade Avaliativa - Git Colaborativo com Portugol

## Integrantes do grupo
- Thiago Moreira
- José Carlos

## Objetivo
Desenvolver colaborativamente um algoritmo em Portugol de subtração e adiçao

## Etapas realizadas por cada membro

### Thiago Moreira
- Como criou? 
- Como Configurou o Git? não deixe exposto sua chave.
- Criou o arquivo `algoritmo.pg` com a estrutura inicial:
- fez o que? depois?...

### Ciclana Souza
- Thiagoce José.
- Fez `git pull` após o commit de Thiago.
- Adicionou conta de subtração
 



## Comandos utilizados
todos do tutorial
### Comandos de Fulano

### Comandos de José
Nitro@DESKTOP-BTRMKOS MINGW64 ~
$ git config --global user.name
José

Nitro@DESKTOP-BTRMKOS MINGW64 ~
$ git config --global user.email
jose.resta.resta@edu.unifil.br

Nitro@DESKTOP-BTRMKOS MINGW64 ~
$ git config --global --unset user.name
warning: user.name has multiple values

Nitro@DESKTOP-BTRMKOS MINGW64 ~
$ git config --unset user.email
fatal: not in a git directory

Nitro@DESKTOP-BTRMKOS MINGW64 ~
$ ls -al ~/.ssh
total 29
drwxr-xr-x 1 Nitro 197121    0 Apr  5 19:22 ./
drwxr-xr-x 1 Nitro 197121    0 Apr 11 19:27 ../
-rw-r--r-- 1 Nitro 197121 3401 Apr 11 19:25 id_rsa
-rw-r--r-- 1 Nitro 197121  756 Apr 11 19:25 id_rsa.pub
-rw-r--r-- 1 Nitro 197121  828 Apr  5 19:22 known_hosts
-rw-r--r-- 1 Nitro 197121   92 Apr  5 19:22 known_hosts.old

Nitro@DESKTOP-BTRMKOS MINGW64 ~
$ rm -f~/.ssh/id_rsa
rm: unknown option -- ~
Try 'rm --help' for more information.

Nitro@DESKTOP-BTRMKOS MINGW64 ~
$ rm -f ~/.ssh/id_rsa

Nitro@DESKTOP-BTRMKOS MINGW64 ~
$ git config --global user.name "José"
warning: user.name has multiple values
error: cannot overwrite multiple values with a single value
       Use a regexp, --add or --replace-all to change user.name.

Nitro@DESKTOP-BTRMKOS MINGW64 ~
$ rm -f~/.ssh/id_rsa*
rm: unknown option -- ~
Try 'rm --help' for more information.

Nitro@DESKTOP-BTRMKOS MINGW64 ~
$ rm -f ~/.ssh/id_rsa*

Nitro@DESKTOP-BTRMKOS MINGW64 ~
$ git config --global user.name "José"
warning: user.name has multiple values
error: cannot overwrite multiple values with a single value
       Use a regexp, --add or --replace-all to change user.name.

Nitro@DESKTOP-BTRMKOS MINGW64 ~
$ git config --global --unset user.email

Nitro@DESKTOP-BTRMKOS MINGW64 ~
$ git config --global user.email "jose.resta.resta@edu.unifil.br"

Nitro@DESKTOP-BTRMKOS MINGW64 ~
$ git config --global user.name "José Carlos"
warning: user.name has multiple values
error: cannot overwrite multiple values with a single value
       Use a regexp, --add or --replace-all to change user.name.

Nitro@DESKTOP-BTRMKOS MINGW64 ~
$ ssh-keygen -t rsa -b 4096 -C "jose.resta.resta@edu.unifil.br"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/Nitro/.ssh/id_rsa):
Enter passphrase for "/c/Users/Nitro/.ssh/id_rsa" (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/Nitro/.ssh/id_rsa
Your public key has been saved in /c/Users/Nitro/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:ugQiTD99sPbNEseN90HVjEKkbnikGcL442uQtSl9hLU jose.resta.resta@edu.unifil.br
The key's randomart image is:
+---[RSA 4096]----+
|           oo  +.|
|     o  .  .. o o|
| .  ..oo..o  o   |
|o . ..=.EBo .    |
|...o.Bo*S++o .   |
| . .*o*o*o. . .  |
|     o++ o   .   |
|     ..o.        |
|     .o          |
+----[SHA256]-----+

Nitro@DESKTOP-BTRMKOS MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 267

Nitro@DESKTOP-BTRMKOS MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/Nitro/.ssh/id_rsa (jose.resta.resta@edu.unifil.br)

Nitro@DESKTOP-BTRMKOS MINGW64 ~
$ clip<~/.ssh/id_rsa.pub

Nitro@DESKTOP-BTRMKOS MINGW64 ~
$ ssh -T git@github.com
Hi JoseCBBettegaFilho! You've successfully authenticated, but GitHub does not provide shell access.

Nitro@DESKTOP-BTRMKOS MINGW64 ~
$ git clone git@github.com:Thiag0123/Avalia-oGit
Cloning into 'Avalia-oGit'...
remote: Enumerating objects: 13, done.
remote: Counting objects: 100% (13/13), done.
remote: Compressing objects: 100% (11/11), done.
remote: Total 13 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (13/13), 4.70 KiB | 370.00 KiB/s, done.
Resolving deltas: 100% (1/1), done.

Nitro@DESKTOP-BTRMKOS MINGW64 ~
$ git clone git@github.com:Thiag0123/Avalia-oGit
fatal: destination path 'Avalia-oGit' already exists and is not an empty directory.

Nitro@DESKTOP-BTRMKOS MINGW64 ~
$



## Observações
Cada um do grupo fez a sua parte seguindo uma ordem, pull, commit e etc.
