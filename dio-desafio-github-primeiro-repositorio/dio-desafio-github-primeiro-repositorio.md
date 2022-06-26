# anotações sobre git/github :computer:

                            windows        unix
navega entre as pasta                 - cd                    - cd
listar as  pasta                               - dir                   - ls
criar pasta no dico local              - mkdir              - mkdir
apagar pastas                               - del/rmdir        - rm -rf
limpas lista                                    - cls                    - clear ou [ ctrl+l ]

criar arquivo dentro da pasta -echo hello > hello.txt

windows - remover pasta com os arquivos rmdir workspace /S /Q
linux   - rm -rf workspace/
tecla tab completa nome de pasta existe no diretorio

no git 
abrir git bash na pasta que encontra arquivo 
openssl sha1 texto.txt


criando uma chave ssh git bash 
$ ssh-keygen -t ed25519 -C seu e-mail
enter 
vai pedir para colocar uma senha 
visualizar chaves 
cd /c/Users/Danie/.ssh/
ls
car id_ed25519.pub 
copiar codigo gerado colar no github 
no git 
$ eval $(ssh-agent -s)
$ ls 
id_es25519 id_25519.pub
$ ssh-add id_ed25519
cave adiciona neste passo e chave privada 
$ git clone >> caminho chaves ssh di github 

comandos basicos do git 
$ git init 
$ git add
$ git commit
$ ls -a visualizar arquivos ocultos 

$ git config --global user.mail "******"
$ git config --global user.name

$ git config --list

Link para download do Git: https://git-scm.com/downloads
O Git Bash é um terminal extendido para otimizar o uso do Git.
