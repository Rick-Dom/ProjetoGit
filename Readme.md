Olá, esse projeto ensina você a usar o Git :)
tudo aqui foi visto no video 
* [COMO USAR GIT E GITHUB NA PRÁTICA!](https://www.youtube.com/watch?v=UBAX-13g8OM&list=LL)
da incrivel Rafaella Ballerini 
* [link do github dela:](https://github.com/rafaballerini)


## Codigos do terminal do Git

* git --version = verificar se a sua versão está correta

* git mkdir = criar uma pasta 

* git cd = abrir pasta (ou voce pode criar uma pasta e abrir o terminal do git lá mesmo com o botao direito do mouse)

* git init = para iniciar um repositório vazio [obs:o (master) significa que voes esta dentro da sua branchprincipal]

* git add = para adicionar o arquivo em uma especio de pacote para ser "puxado" (push) para o repositório do Github. Os aquivos que sao enviados fica no estaod de stading ( Exemplo: git add nome do projeto ou git add . para adiconar tudo)

* git status = para verificar se foi adicionado, e para ver se as modificações estao sendo feitas

* git commit -m "primeiro commit" = adiciona o seu primeiro commit

* git branch -M "main" = basicamente falando, muda o nome da sua branch

* git remote add origem https://github.com/ nome do usuario /nome do projeto.git = faz a conexâo do repositorio local com o repositorio do Github

* git push -u origem main = envia os arquivos 

* git push origin main = quando a conexao ja estiver estabelecida 

* git checkout -b "nome da nova branch" = para criar uma branch nova (ramificação)

* git checkout main = para voltar para branch principal

* git merge nome da branch = para juntar as duas branch

## PUXAR UM ARQUIVO PARA SUA MAQUINA
Você deve ir ate o repositório que voce deseja clonar e clicar o botão verde "code" e sem seguida copiar o link que aparece. Depois disso basta criar uma pasta, onde vai ficar o arquivo e abrir o terminal do Git e escrever o seguinte codigo: 

* git clone link que voce copiou