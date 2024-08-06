<h1 align="center"> Cadastros de Ecommerce </h1>

## Status do Projeto🚧
> 👍Projeto Finalizado 👍

## 📋Descrição
O projeto desenvolvido para disciplina de Programação Web II consiste em uma aplicação de carrinho de compras para um e-commerce. Esse sistema oferece aos usuários a funcionalidade de adicionar o carrinho, visualizar seu conteúdo e gerenciar suas compras de forma eficiente. Uma aplicação simula as operações básicas de um sistema de e-commerce, proporcionando uma interface simples e intuitiva que permite aos usuários vivenciar a experiência de adicionar produtos e consultar o total de suas compras.

## Métodos PHP Utilizados 

1. **`include_once("controller/conexao.php")`**
   - **Função:** `include_once()`
   - **Descrição:** Inclui e avalia o arquivo especificado durante a execução do script. A diferença de `include_once()` para `include()` é que o primeiro garante que o arquivo será incluído apenas uma vez, evitando múltiplas inclusões que podem causar erros.
 
2. **`mysqli_query($mysqli, $resultado_categoria)`**
   - **Função:** `mysqli_query()`
   - **Descrição:** Executa uma consulta no banco de dados MySQL. Recebe a conexão (`$mysqli`) e a consulta SQL (`$resultado_categoria`), e retorna um resultado que pode ser manipulado com outras funções `mysqli`.
 
3. **`mysqli_fetch_assoc($resultcategoria)`**
   - **Função:** `mysqli_fetch_assoc()`
   - **Descrição:** Obtém uma linha de resultado de uma consulta como uma matriz associativa. Usado para iterar sobre os resultados da consulta.
 
4. **`echo`**
   - **Função:** `echo`
   - **Descrição:** Imprime uma ou mais strings. Utilizado para gerar HTML dinâmico com base nos dados recuperados do banco de dados.
 
5. **`require_once`**('controller/produtos-resumo.php')
- **Função:** `require_once`()
- **Descrição**: Inclui e avalia o arquivo especificado apenas uma vez durante a execução do script. Se o arquivo já foi incluído antes, ele não será incluído novamente. Isso é útil para evitar múltiplas inclusões de um mesmo arquivo, o que pode causar erros, especialmente ao definir funções, classes ou instâncias de objetos.
 
6. **`$_POST`**
- **Função:** `$_POST`
- **Descrição**: Superglobal que coleta dados enviados via método POST em um formulário HTML. Aqui, é usado para obter valores de campos do formulário.
 
7. **`mysqli_query`**($mysqli, $grava_produto)
- **Função**: mysqli_query()
- **Descrição**: Executa uma consulta no banco de dados MySQL. Recebe a conexão ($mysqli) e a consulta SQL ($grava_produto). Retorna um resultado que pode ser usado para verificar se a consulta foi bem-sucedida.
 
8. **`mysqli_affected_rows`**($mysqli)
- **Função**: mysqli_affected_rows()
- **Descrição**: Retorna o número de linhas afetadas pela última consulta SQL. Aqui, é usado para verificar se o comando INSERT inseriu algum registro na tabela.
Sim, o código PHP que você forneceu utiliza vários métodos e funções PHP. Vou listar e explicar cada um deles para que você possa entender como são usados no seu script.
 
9. **`mysqli_query($mysqli, $cad_categoria)`**
   - **Função:** `mysqli_query()`
   - **Descrição:** Executa uma consulta SQL no banco de dados MySQL. Recebe a conexão (`$mysqli`) e a consulta SQL (`$cad_categoria`). Retorna `true` em caso de sucesso ou `false` em caso de falha.
 
10. **`mysqli_error($mysqli)`**
   - **Função:** `mysqli_error()`
   - **Descrição:** Retorna uma descrição textual do último erro ocorrido na conexão MySQL. É útil para depuração e exibição de mensagens de erro mais detalhadas.
 
11. **`mysqli_close($mysqli)`**
   - **Função:** `mysqli_close()`
   - **Descrição:** Fecha a conexão com o banco de dados MySQL. Deve ser chamado quando a interação com o banco de dados estiver concluída para liberar recursos

## Imagem das aplicações 📸

# Tela Inicial ⬇️
   ![imagem](img/telainicial.png)

# Pedidos 🛍️
   ![imagem](img/gifcarrinho.gif)

# Cadastro de Categoria ⬇️
   ![imagem](img/gifcategoria.gif)

# Cadastro de Marcas ⬇️
   ![imagem](img/gifmarcas.gif)

## Explicação ⚠️

Inclusão de Arquivos:
*include_once*() e *require_once*() são usados para incluir e avaliar arquivos externos. A principal diferença é que *include_once*() e *require_once*() garantem que o arquivo será incluído apenas uma vez, evitando múltiplas inclusões.
 
Manipulação de Dados de Formulários:
*$_POST* é utilizado para coletar dados enviados via método POST em formulários HTML.
 
Interação com o Banco de Dados:
*mysqli_query*() executa consultas SQL.
*mysqli_fetch_assoc*() obtém resultados da consulta.
*mysqli_affected_rows*() verifica quantas linhas foram afetadas pela última consulta.
*mysqli_error*() fornece uma descrição do erro se a consulta falhar.
*mysqli_close*() fecha a conexão com o banco de dados.
 
Saída de Dados:
*echo* é utilizado para imprimir texto e variáveis na saída padrão, gerando HTML dinâmico e mensagens para o usuário.
Esses métodos e funções são essenciais para criar, manipular, e interagir com dados em uma aplicação PHP que utiliza um banco de dados MySQL.

### 🛠️ Tecnologia ultilizadas
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original-wordmark.svg" width=50  />  |<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-plain.svg" width=50 /> |  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/threedsmax/threedsmax-original.svg" width=50/> |<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original-wordmark.svg" width=50/> |
| :---: | :---: | :---: | :---: | 

## ✒️ Autores
| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/105460028?v=4" width=115><br><sub>Hanelise Naves Amorim</sub>](https://github.com/hiseamorim) | [<img loading="lazy" src="https://avatars.githubusercontent.com/u/130574133?v=4" width=115><br><sub>Quezia Kato</sub>](https://github.com/QueziaKato) |  [<img loading="lazy" src="https://avatars.githubusercontent.com/u/86802310?v=4" width=115><br><sub>Leonardo Rocha</sub>](https://github.com/LeonardoRochaMarista) |  [<img loading="lazy" src="https://avatars.githubusercontent.com/u/86796647?s=200&v=4" width=115><br><sub>Marista Escola Social Ir. Acácio</sub>](https://github.com/MaristaIrAcacio) | 
| :---: | :---: | :---: | :---: |

