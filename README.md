## _Exercícios da Aula (27/09/2021) de Hardskills na AlphaEdTech._

### _1._ Após criado a sua conta no GitHub, crie um repositório remoto público chamado “my_first_steps” e cole o link aqui;

* <https://github.com/ayoline/my_first_steps.git>

### _2._ Crie um diretório em sua máquina e o vincule ao seu repositório remoto “my_first_steps” utilizando os comandos git necessários para a realização desta tarefa. 

### Cole aqui a cadeia de comandos que você utilizou para a realização desta tarefa.

* Com o git bash dentro do diretório criado, executar os seguintes comandos:
* $ git init
* $ git checkout -B main
* $ git remote add origin https://github.com/ayoline/my_first_steps.git
* $ git push -u origin main


### _3._ Dentro do diretório em sua máquina, crie um arquivo chamado “ola_mundo.txt”, adicione algum texto da sua preferência e adicione-o ao seu repositório remoto utilizando os comandos git necessários para a realização desta tarefa. 
### Cole aqui a cadeia de comandos que você utilizou para a realização desta tarefa.

* Com o git bash dentro do diretório criado, executar os seguintes comandos:
* $ git add ola_mundo.txt
* $ git commit -m "first commit"
* $ git push -u origin main 


### _4._ Se não existir em seu diretório, adicione ao seu diretório um arquivo com o nome de “.gitignore”. Em seguida, crie um arquivo chamado “serei_ignorado.txt” e adicione algum texto dentro dele. Adicione a instrução ao arquivo “.gitignore” para que as alterações realizadas no arquivo “serei_ignorado.txt” não seja controlado pelo git. 

### Cole aqui o conteúdo que você utilizou no “.gitignore” para realizar esta tarefa.

* serei_ignorado.txt


### _5._ Dentro do seu diretório local, crie um arquivo chamado “README.md” e edite-o contendo todas as respostas aos enunciados das questões anteriores. Adicione-o ao seu repositório remoto utilizando os comandos git necessários para a realização desta tarefa.

### Cole aqui a cadeia de comandos que você utilizou para a realização desta tarefa.

* Com o git bash dentro do diretório criado, executar os seguintes comandos:
* $ git add *
* $ git commit -m "Configura modificações nos arquivos descritas no arquivo README"
* $ git push -u origin main 