## 💻 Como fazer deploy app Angular no Github Pages

## :books: Passo a Passo
- Passo 1:  Git Push. Após enviar o comando "git push -u origin main" para armazenar o seu projeto no GitHub, siga as etapas a seguir:

- Passo 2: Terminal. Volte para o terminal do seu projeto e digite o seguinte comando:

npm install -g angular-cli-ghpages

Esse comando irá adicionar uma biblioteca chamada "angular-cli-ghpages" ao seu projeto Angular. Essa biblioteca nos permitirá fazer o deploy do projeto no GitHub Pages.

- Passo 3: Fazer o deploy. Após a instalação da biblioteca, execute o seguinte comando no terminal:

ng build --configuration=production --base-href "https://<username>.github.io/<reponame>/"

Aguarde até que o comando seja concluído. Ele irá empacotar o seu projeto Angular e fazer o deploy no GitHub Pages.

- Passo 4: Acessar a página

ngh --dir dist/<project-name>

ATENÇÃO AQUI: No passo 3 geramos um build que criou uma pasta chamada " dist " e dentro dela tem uma pasta com o nome do nosso projeto. As vezes, o nome do nosso projeto é "AngularProjeto" e ela pode gerar na pasta dist um " angular-projeto". Então, é o nome gerado na pasta dist que você irá colocar.

- Passo 5: Projeto no ar

Em seguida, vá para o repositório do seu projeto no GitHub, na pasta "Actions" e verá o build do seu projeto sendo feito e logo será disponibilizado o link para acesso ao seu projeto.

Espero que essas instruções tenham sido úteis para você. Agora você poderá compartilhar o seu projeto Angular com outras pessoas através do Github Pages.
