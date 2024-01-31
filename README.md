<img src="https://capsule-render.vercel.app/api?type=waving&color=0:db813b,50:d76f32,100:e0945e&height=150&section=header" width="100%">

<html>
  <img align="left" src="https://github.com/Delgado-tech/dnc-landing-page-challenge/assets/60985347/01280482-629f-4956-93a1-f7bab2b52400" width="100px"/>
  <h1>FORMAÇÃO EM TECNOLOGIA - DESAFIO 7 <br>
  Refatoração de uma API com Typescript e Jest<br><br></h1>
</html>

### 🚀 Descrição do desafio:
> O Desafio 7 consiste em refatorar uma API simples desenvolvida em Express, originalmente escrita em JavaScript, para utilizar Typescript. Além disso, a tarefa inclui a implementação de testes de integração utilizando a biblioteca Jest.

#

### 🎯 Resolução:
O código da API foi completamente refatorado para incorporar o Typescript, proporcionando melhor tipagem e organização ao projeto. Os testes de integração foram implementados usando o Jest, garantindo a robustez e confiabilidade do sistema. Você pode ver a versão antes de ser refatorada na pasta `__old`.

#

### 👁️‍🗨️ Utilização
Passo a passo para testar o código em sua máquina

```diff
+ Passo 1: Clone o repositório
# > git clone https://github.com/Delgado-tech/dnc-jest-challenge.git

+ Passo 2: Crie a pasta node_modules com npm install
# > npm install

+ Passo 3: Conecte o seu banco de dados
# Para testar o código será necessário ter uma conexão MySQL ativa em sua máquina;
# Crie um banco de dados para testar o código (não será necessário criar nenhuma tabela);
# Dentro do projeto vá em:
! src > config > knex.ts
# Dentro do arquivo knex.ts altere os campos "host, port, user, password e database";
# Coloque os dados referentes ao seu banco de dados nos campos informados.

+ Passo 4: Carregue a migração do projeto em seu banco de dados;
# Para o projeto funcionar será necessário carregar a migração do knex;
# Rode o comando a seguir em seu terminal:
# > npx knex migrate:latest
# Pronto! A tabela "Aluno" foi adicionada ao seu banco de dados.

+ Passo 5: Configure o seu arquivo .env
# Variáveis:
# ROOT_URL="http://localhost:8080"
# PORT="8080"

+ Passo 6: Inicie o projeto
# > npm run start

+ Passo 7: Rode os testes:
# Só será possivel rodar os testes se a aplicação tiver sido iniciada;
# > npm run test
```

<br>

<html>
  <br>
  <table>
    <tr>
      <th></th>
      <th>NOME</th>
      <th>DESCRIÇÃO</th>
    </tr>
    <!--Linha 1-->
    <tr>
      <td> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" width="20px"/></td>
      <td><strong>Express<strong/></td>
      <td>Framework utilizado para o desenvolvimento da API</td>
    </tr>
    <!--Linha 2-->
    <tr>
      <td> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="20px"/></td>
      <td><strong>Typescript<strong/></td>
      <td>Linguagem de programação para maior tipagem e organização</td>
    </tr>
    <!--Linha 3-->
    <tr>
      <td> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jest/jest-plain.svg" width="20px"/></td>
      <td><strong>Jest<strong/></td>
      <td>Framework de teste utilizado para testes de integração</td>
    </tr>
  </table>
  <br>
</html>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:30363d&height=150&section=footer" width="100%">
