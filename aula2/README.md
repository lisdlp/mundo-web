# Aula 2 - git
## comandos: 
- configurar credenciais do github
 `git config --global user.name "lisdlp"`
 `git config --global user.email "lisdelimapereira1@gmail.com"`

### utilizar sempre que começar um projeto
- iniciar git
 `git init`

- adicionar ligação remota com o repositório
`git remote add origin https://github.com/lisdlp/mundo-web.git`

- buscar por tudo no repositório
` git fetch --all`

- trocar para a branch que deseja mexer (colocar no lugar de main, se necessario, o nome da branch para qual deseja trocar)
`git checkout -b main`

- trazer as alterações presentes no github (fazer isso toda vez que for enviar alguma coisa para o repositório do github)

`git pull origin main `

- preparar os arquivos alterados/modificados/deletados para serem enviados
`git add .`
 
- verificar estado dos arquivos 

`git status`

- commitar os arquivos (registrar a descrição das mudanças)
` git commit -m "envio do arquivo da segunda aula`

- empurrar/enviar alterações para o github (para o repositório)
`git push origin main`


