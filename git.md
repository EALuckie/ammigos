# Commands for git and github

- git config --global user.name "EALuckie"
- git config --global user.email "e.luckie@gmail.com"
- git init
- git status
- git log
- git log --graph
- git add .
- git commit -m "Este es mi primer commit"
- git checkout < fd > #Para regresar al último estado guardado
- git config --global alias.tree "log --graph" #Para hacer macros de comandos


## GitHub

https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

- ssh-keygen -t ed25519 -C "e.luckie@kalecon.com"
- id_rsa
- git push -u origin main
- git pull origin main   