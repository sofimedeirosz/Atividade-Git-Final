# Atividade-Git-Final
# Atividade Avaliativa - Git Colaborativo com Portugol

## Integrantes do grupo
- Fulano da Silva
- Ciclana Souza  
- Beltrano Gomes

## Objetivo
Desenvolver colaborativamente um algoritmo em Portugol de…..

## Etapas realizadas por cada membro

### Fulano da Silva 
- Como criou?
- Como Configurou o Git? não deixe exposto sua chave.
- Criou o arquivo `algoritmo.pg` com a estrutura inicial:
- fez o que? depois?...

### Maria Eduarda
- Como Configurou o Git? não deixe exposto sua chave.
- Fez `git pull` após o commit de Fulano.
- Adicionou lógica de ... 
 

### Beltrano Gomes 
- Como Configurou o Git? não deixe exposto sua chave.
- Fez `git pull` após o commit de Ciclana.
- Finalizou o algoritmo com lógica . . .


## Comandos utilizados
Todos os comandos foram executados via terminal utilizando chave SSH:
### Comandos de Fulano

### Comandos de Maria Eduarda
compuni@Lab6m34 MINGW64 ~
$ git config --global user.name

compuni@Lab6m34 MINGW64 ~
$ git config --global user.email

compuni@Lab6m34 MINGW64 ~
$ git config --global --unset user.name

compuni@Lab6m34 MINGW64 ~
$ git config --global --unset user.email

compuni@Lab6m34 MINGW64 ~
$ rm -f ~/.ssh/id_rsa*

compuni@Lab6m34 MINGW64 ~
$ git config --global user.name "Duda Silveira"

compuni@Lab6m34 MINGW64 ~
$ git config --global user.email "dudasouzas007@gmail.com"

compuni@Lab6m34 MINGW64 ~
$ ssh-keygen -t rsa -b 4096 -C "dudasouzas007@gmail.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/compuni/.ssh/id_rsa):
Created directory '/c/Users/compuni/.ssh'.
Enter passphrase for "/c/Users/compuni/.ssh/id_rsa" (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/compuni/.ssh/id_rsa
Your public key has been saved in /c/Users/compuni/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:7lA4JFiY89vjvX/mJVdTelXiZTV2bqZMZjtC6HSI0No dudasouzas007@gmail.com
The key's randomart image is:
+---[RSA 4096]----+
|   o. ..      .oB|
|  +o   ... o ..=+|
|  .o. .o. + o = *|
|    .o..Eo o = *o|
|     oo S . . *.o|
|    . o+     . +.|
|     ..o.   . o  |
|      .o.   o+   |
|        oo.+.    |
+----[SHA256]-----+

compuni@Lab6m34 MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 1294

compuni@Lab6m34 MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/compuni/.ssh/id_rsa (dudasouzas007@gmail.com)

compuni@Lab6m34 MINGW64 ~
$ clip < ~/.ssh/id_rsa.pub

compuni@Lab6m34 MINGW64 ~
$ ssh -T git@github.com
The authenticity of host 'github.com (20.201.28.151)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
Hi dudas00937! You've successfully authenticated, but GitHub does not provide shell access.

compuni@Lab6m34 MINGW64 ~
$ git clone git@github.com:sofimedeirosz/Atividade-Git-Final
Cloning into 'Atividade-Git-Final'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

compuni@Lab6m34 MINGW64 ~
$ cd Atividade-Final-Git
bash: cd: Atividade-Final-Git: No such file or directory

compuni@Lab6m34 MINGW64 ~
$ cd Atividade-Git-Final

compuni@Lab6m34 MINGW64 ~/Atividade-Git-Final (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

compuni@Lab6m34 MINGW64 ~/Atividade-Git-Final (main)
$ git add .

compuni@Lab6m34 MINGW64 ~/Atividade-Git-Final (main)
$ git commit -m "Soma"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

compuni@Lab6m34 MINGW64 ~/Atividade-Git-Final (main)
$ git push
Everything up-to-date

compuni@Lab6m34 MINGW64 ~/Atividade-Git-Final (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

compuni@Lab6m34 MINGW64 ~/Atividade-Git-Final (main)
$ code .

compuni@Lab6m34 MINGW64 ~/Atividade-Git-Final (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   atv final git.por

no changes added to commit (use "git add" and/or "git commit -a")

compuni@Lab6m34 MINGW64 ~/Atividade-Git-Final (main)
$ git add .

compuni@Lab6m34 MINGW64 ~/Atividade-Git-Final (main)
$ git commit -m "soma"
[main b8d8e59] soma
 1 file changed, 7 insertions(+), 1 deletion(-)

compuni@Lab6m34 MINGW64 ~/Atividade-Git-Final (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 407 bytes | 407.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To github.com:sofimedeirosz/Atividade-Git-Final
   f19761d..b8d8e59  main -> main



### Comandos de Monique
ASUS@LAPTOP-PQ88A7LP MINGW64 ~
$ git config --global user.name

ASUS@LAPTOP-PQ88A7LP MINGW64 ~
$ git config --global user.email
castromonique807@gmail.com

ASUS@LAPTOP-PQ88A7LP MINGW64 ~
$ git config --global --unset user.name

ASUS@LAPTOP-PQ88A7LP MINGW64 ~
$ git config --global --unset user.email

ASUS@LAPTOP-PQ88A7LP MINGW64 ~
$ ls -al ~/.ssh
total 12
drwxr-xr-x 1 ASUS 197121 0 Mar 28 20:23 ./
drwxr-xr-x 1 ASUS 197121 0 Apr 11 19:16 ../

ASUS@LAPTOP-PQ88A7LP MINGW64 ~
$ rm -f ~/.ssh/id_rsa*

ASUS@LAPTOP-PQ88A7LP MINGW64 ~
$ git config --global user.name monique

ASUS@LAPTOP-PQ88A7LP MINGW64 ~
$ git config --global user.email castromonique807@gmail.com

ASUS@LAPTOP-PQ88A7LP MINGW64 ~
$ ssh-keygen -t rsa -b 4096 -C castromonique807@gmail.com
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/ASUS/.ssh/id_rsa):
Enter passphrase for "/c/Users/ASUS/.ssh/id_rsa" (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /c/Users/ASUS/.ssh/id_rsa
Your public key has been saved in /c/Users/ASUS/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:8xuFOxKggBvkTWj3/BvIS7nM7oo7SxYPoApNooBkbek castromonique807@gmail.com
The key's randomart image is:
+---[RSA 4096]----+
| +o..            |
|*+o=             |
|O.*.o .          |
|=* E + .   .     |
|=o. o + S . .    |
|o +  = o + o     |
|.o .+ o + =      |
|o..  = . . +     |
| ++.+o    .      |
+----[SHA256]-----+

ASUS@LAPTOP-PQ88A7LP MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 1394

ASUS@LAPTOP-PQ88A7LP MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/ASUS/.ssh/id_rsa (castromonique807@gmail.com)

ASUS@LAPTOP-PQ88A7LP MINGW64 ~
$ clip < ~/.ssh/id_rsa.pub

ASUS@LAPTOP-PQ88A7LP MINGW64 ~
$  clip < ~/.ssh/id_rsa.pub

ASUS@LAPTOP-PQ88A7LP MINGW64 ~
$ ssh -T git@github.com
The authenticity of host 'github.com (20.201.28.151)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
Hi mopsychosz! You've successfully authenticated, but GitHub does not provide shell access.

ASUS@LAPTOP-PQ88A7LP MINGW64 ~
$ git clone git@github.com:sofimedeirosz/Atividade-Git-Final
Cloning into 'Atividade-Git-Final'...
remote: Enumerating objects: 6, done.

Aborting commit due to empty commit message.

ASUS@LAPTOP-PQ88A7LP MINGW64 ~/Atividade-Git-Final (main)
$ git commit -m "subtração"
[main d5456f7] subtração
 1 file changed, 5 insertions(+), 1 deletion(-)

ASUS@LAPTOP-PQ88A7LP MINGW64 ~/Atividade-Git-Final (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 364 bytes | 364.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:sofimedeirosz/Atividade-Git-Final
   32a82ed..d5456f7  main -> main

ASUS@LAPTOP-PQ88A7LP MINGW64 ~/Atividade-Git-Final (main)
$

ASUS@LAPTOP-PQ88A7LP MINGW64 ~/Atividade-Git-Final (main)
$ clip <~/.ssh/id_rsa.pub


## Observações
Cada etapa foi realizada por apenas um integrante por vez, respeitando a ordem de commits e a integridade do código.
