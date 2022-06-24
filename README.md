# Inteli - Instituto de Tecnologia e Liderança 

<p align="center">
<a href= "https://www.inteli.edu.br/"><img src="https://www.inteli.edu.br/wp-content/uploads/2021/08/20172028/marca_1-2.png" alt="Inteli - Instituto de Tecnologia e Liderança" border="0"></a>
</p>

# EduCons

## <b><Fal><Cons></b>

## Integrantes: 
- <a href="https://www.linkedin.com/in/daniel-barzilai-061036234">Daniel Barzilai</a>
- <a href="https://www.linkedin.com/in/gabriela-rodrigues-matias/">Gabriela Rodrigues Matias</a>
- <a href="https://www.linkedin.com/in/henriqueschilderlima/">Henrique Agostinho Schilder Lima</a> 
- <a href="https://www.linkedin.com/in/mateus-rafael-miranda">Mateus Rafael Miranda da Silva</a>
- <a href="https://www.linkedin.com/in/patriciahonorato/">Patricia Honorato Moreira</a>
- <a href="https://www.linkedin.com/in/sophia-de-oliveira-tosar-aba7ab23b/">Sophia de Oliveira Tosar</a> 

## 📝 Descrição
<p> Desenvolver uma aplicação para gerar um diagnóstico robusto de maturidade gerencial das redes de ensino considerando 3 pontos:</p>

Agenda Educacional, sob 7 eixos;
Agenda de Gestão, sob 2 eixos e
Indicadores Educacionais.

<p> Atuar com uma ferramenta completa de diagnóstico inicial para avaliação da maturidade gerencial das redes de ensino, facilitando assim as análises e tomadas de decisões das redes de ensino quanto às políticas e investimentos em recursos. Desse modo, iremos desenvolver uma plataforma Web, responsável por garantir a entrega em relação ao preenchimento e armazenamento das informações captadas em relação às respostas para as agendas educacional e de gestão. Assim como os diagnósticos de orientação de acordo com os resultados de cada agenda. Desenvolvida por meio de:</p>

<p> Front-end:
HTML, CSS, Bootstrap e JavaScript.
  
<p> Back-end:
Node.js com Express.js

<p> Infraestrutura (Banco de Dados):
SQL
<br>
<img src="../frontend/imgs/FalCons_Logo.png" alt="FalCons" border="0" style="max-width: 100%"><br>
  
## 📁 Estrutura de pastas
 - Raiz<br>
|<br>
|--> .git (pasta oculta)<br>
|--> .vscode<br>
|--> backend<br>
   --> node_modules<br>
   &emsp;| app.js<br>
   &emsp;| dbFalconi.db<br>
   &emsp;| dbFalconi.sqbpro<br>
|--> Documentos<br>
   --> antigos<br>
     &emsp;| T5_G3_V8.0_Web_application_document.pdf<br>
     &emsp;| T5_G3_V8.0_Web_application_document.docx<br>
|--> frontend<br>
   &emsp;| index.html<br>
|--> imagens<br>
|--> src<br>
| .DS_Store<br>
| .gitignore<br>
| README.md<br>
| estado.txt<br>
| package-lock.json<br>

Dentre os arquivos presentes na raiz do projeto, definem-se:

- <b>readme.md</b>: arquivo que serve como guia e explicação geral sobre o projeto (o mesmo que você está lendo agora).

- <b>documentos</b>: aqui estarão todos os documentos do projeto.
- <b>backend</b>: aqui estão os arquivos pertinentes ao servidor e banco de dados.
- <b>frontend</b>: aqui estão os arquivos responsáveis pelas telas vistas pelo usuário no site e as ferramentas de funcionamento por trás de cada uma delas.

## 💻 Configuração para desenvolvimento

Aqui encontram-se todas as instruções necessárias para a instalação de todos os programas, bibliotecas e ferramentas imprescindíveis para a configuração do ambiente de desenvolvimento.

1.  Baixar e instalar o node.js:  [https://nodejs.org/pt-br/](https://nodejs.org/pt-br/) (versão 16.15.1 LTS)
2. Clone o repositório em questão.
3.  No modo administrador, abra o "prompt de comando" ou o "terminal" e, após,  abra a pasta "src/backend" no diretório raiz do repositório clonado e digite o segundo comando:

```sh
npm install
```

Isso instalará todas as dependências definidas no arquivo <b>package.json</b> que são necessárias para rodar o projeto. Agora o projeto já está pronto para ser modificado. Caso ainda deseje iniciar a aplicação, digite o comando abaixo no terminal:

```sh
npm start
```
5. Agora você pode acessar a aplicação através do link http://localhost:1234/
6. O servidor está online.


```
Alunos inteli (remover essa observação do readme.md após leitura e execução):

1. Certifique-se que há um arquivo "package.json" na pasta backend do projeto.

2. Dentro deste arquivo, encontre a propriedade "scripts", e adicione um atributo de nome "start"
com o valor "node <CAMINHO_DO_ARQUIVO_DO_SERVIDOR>." Atenção: "<CAMINHO_DO_ARQUIVO_DO_SERVIDOR>" 
deve ser substituído pelo caminho para o arquivo principal da aplicação, utilizado para subir o
servidor. Por exemplo, se o arquivo utilizado para subir o servidor é "app.js", o atributo start
deve possuir o valor "node app.js".

3. No arquivo utilizado para subir a aplicação, defina a porta padrão de execução para "1234".
````

## 🗃 Histórico de lançamentos

* 0.2.1 - 25/01/2022
    * Atualização de documentos (código do módulo permanece inalterado).
* 0.2.0 - 15/01/2022
    * Remove `setDefaultXYZ()`
    * Adiciona `init()`
* 0.1.1 - 11/01/2022
    * Crash quando chama `baz()`
* 0.1.0 - 10/01/2022
    * O primeiro lançamento adequado
    * Renomeia `foo()` para `bar()`
* 0.0.1 - 01/01/2022
    * Trabalho em andamento

## 📋 Licença/License
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Licença Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />Este obra está licenciado com uma Licença <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Atribuição 4.0 Internacional</a>.
<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/Spidus/Teste_Final_1">MODELO GIT INTELI</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://www.yggbrasil.com.br/vr">Inteli, Daniel Barzilai, Gabriela Rodrigues Matias, Henrique Agostinho Schilder Lima, Mateus Rafael Miranda da Silva, Patricia Honorato Moreira, Sophia de Oliveira Tosar, </a> is licensed under <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>

## 🎓 Referências

Aqui estão as referências usadas no projeto:
1. <https://creativecommons.org/share-your-work/>
