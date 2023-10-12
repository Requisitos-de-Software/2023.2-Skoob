# Cenários

## Introdução
Cenários são como histórias em evolução que descrevem o que acontece em um ambiente específico, destacando as interações entre as pessoas envolvidas. Geralmente, essas interações envolvem o sistema em desenvolvimento e os participantes externos, como usuários ou outros sistemas. A característica mais importante de um cenário é que ele fornece uma representação concreta de uma atividade que os usuários executam ao realizar uma tarefa específica.

Esses cenários desempenham um papel crucial na fase de levantamento de requisitos de sistemas de software. Eles são usados para descrever como os usuários irão utilizar o sistema e como o sistema se conecta com outros sistemas externos. Isso ajuda a entender e identificar novos requisitos de forma eficaz.[¹]

## Metodologia

A metodologia para criar cenários envolve a identificação de partes interessadas, coleta de informações, definição do escopo, identificação de cenários, descrição detalhada, validação, documentação e uso. Essa abordagem flexível adapta-se às necessidades do projeto, com a participação ativa das partes interessadas.
Dessa forma, os cenários serão representados conforme a tabela 1.


| Elemento    | Descrição                                        |
|-------------|--------------------------------------------------|
| Título      | O nome ou assunto central do cenário.           |
| Objetivo    | A razão ou propósito para a existência do cenário. |
| Contexto    | As condições iniciais, o ambiente físico e a cronologia do cenário. |
| Recursos    | Itens inanimados com os quais os participantes interagem. |
| Ator        | Indivíduos ou entidades organizacionais envolvidos no cenário. |
| Episódios   | Ações realizadas pelos atores, muitas vezes com a participação de outros, usando os recursos. |
| Restrições  | Regras ou limitações que afetam a execução dos episódios. |
| Exceção     | Planos ou procedimentos para lidar com situações extraordinárias ou erros inesperados durante o cenário. |

<div style="text-align: center">
<p> Tabela 1: Modelo dos cenários. (Fonte: Shaíne Oliveira, 2023).</p>
</div>

## Cenários encontrados
As tabelas-xx a xx representam os cenários que foram identificados para o aplicativo Skoob. 



#### **C01: Adicionando um Livro à Estante Pessoal**

| Elemento    | Descrição                                        |
|-------------|--------------------------------------------------|
| Título      | Adicionar Livro à Estante                        |
| Objetivo    | Permitir que os usuários organizem e gerenciem seus livros pessoais. |
| Contexto    | O usuário está logado em sua conta no aplicativo. Ele está em casa, com acesso à internet. |
| Recursos    | Smartphone ou computador, conexão com a internet. |
| Ator        | Usuário do Skoob.                               |
| Episódios   |  1. O usuário pesquisa um livro. <br>           2. O usuário encontra o livro desejado.<br> 3. O usuário clica no botão "Adicionar à Estante". |
| Restrições  | O livro deve estar disponível na base de dados do Skoob. |
| Exceção     | Se o livro não for encontrado, o sistema exibe uma mensagem de erro. |

<div style="text-align: center">
<p> Tabela 2: Cenário 01. (Fonte: Shaíne Oliveira, 2023).</p>
</div>

#### **C02: Avaliando um Livro Lido**

| Elemento    | Descrição                                        |
|-------------|--------------------------------------------------|
| Título      | Avaliar Livro Lido                               |
| Objetivo    | Permitir que os usuários avaliem e compartilhem suas opiniões sobre livros lidos. |
| Contexto    | O usuário está logado em sua conta e deseja avaliar um livro recentemente lido. |
| Recursos    | Smartphone ou computador, conexão com a internet. |
| Ator        | Usuário do Skoob.                               |
| Episódios   | 1. O usuário acessa sua estante pessoal. <br>     2. O usuário seleciona o livro que deseja avaliar. <br>   3. O usuário atribui uma classificação e escreve uma resenha.   <br> 4. O usuário confirma a avaliação.              |
| Restrições  | O livro deve estar na estante do usuário.       |
| Exceção     | Se o usuário tentar avaliar um livro que não está em sua estante, o sistema exibe uma mensagem de erro. |

<div style="text-align: center">
<p> Tabela 3: Cenário 02. (Fonte: Shaíne Oliveira, 2023).</p>
</div>


#### **C03: Realizando o Login**

| Elemento    | Descrição                                        |
|-------------|--------------------------------------------------|
| Título      | Realizar Login                                   |
| Objetivo    | Permitir que os usuários acessem suas contas no aplicativo. |
| Contexto    | O usuário iniciou o aplicativo Skoob e deseja acessar sua conta. |
| Recursos    | Smartphone ou computador, conexão com a internet. |
| Ator        | Usuário do Skoob.                               |
| Episódios   | 1. O usuário abre o aplicativo Skoob. <br>        2. O usuário clica na opção "Login".   <br>     3. O usuário insere seu nome de usuário e senha.  <br> 4. O usuário clica no botão "Entrar".            |
| Restrições  | As credenciais de login devem ser válidas.       |
| Exceção     | Se as credenciais forem inválidas, o sistema exibe uma mensagem de erro. |

<div style="text-align: center">
<p> Tabela 4: Cenário 03. (Fonte: Shaíne Oliveira, 2023).</p>
</div>



#### **C04: Pesquisando Livros**

| Elemento    | Descrição                                        |
|-------------|--------------------------------------------------|
| Título      | Pesquisar Livros                                 |
| Objetivo    | Permitir que os usuários encontrem livros de seu interesse no aplicativo. |
| Contexto    | O usuário está logado em sua conta e deseja encontrar um livro específico. |
| Recursos    | Smartphone ou computador, conexão com a internet. |
| Ator        | Usuário do Skoob.                               |
| Episódios   | 1. O usuário acessa a função de pesquisa no aplicativo.<br> 2. O usuário insere o título ou autor do livro desejado na barra de pesquisa. <br> 3. O usuário clica no botão "Pesquisar".   <br>       4. O sistema exibe os resultados da pesquisa.    |
| Restrições  | A pesquisa deve retornar resultados válidos com base no título ou autor fornecidos. |
| Exceção     | Se nenhum resultado for encontrado, o sistema exibe uma mensagem indicando que nenhum livro corresponde à pesquisa. |

<div style="text-align: center">
<p> Tabela 5: Cenário 04. (Fonte: Shaíne Oliveira, 2023).</p>
</div>

#### **C05: Adicionando Comentários em Posts**

| Elemento    | Descrição                                        |
|-------------|--------------------------------------------------|
| Título      | Adicionar Comentários em Posts                  |
| Objetivo    | Permitir que os usuários interajam com as postagens, adicionando comentários. |
| Contexto    | O usuário está logado em sua conta e deseja interagir com uma postagem. |
| Recursos    | Smartphone ou computador, conexão com a internet. |
| Ator        | Usuário do Skoob.                               |
| Episódios   | 1. O usuário navega pelo feed de postagens. <br> 2. O usuário seleciona uma postagem específica. <br> 3. O usuário escreve seu comentário na caixa de texto.<br> 4. O usuário clica no botão "Comentar".          |
| Restrições  | O comentário deve atender aos critérios de moderação e políticas do aplicativo. |
| Exceção     | Se o comentário violar as políticas do aplicativo, ele não será publicado, e o sistema exibirá uma mensagem informando a violação. |

<div style="text-align: center">
<p> Tabela 6: Cenário 05. (Fonte: Shaíne Oliveira, 2023).</p>
</div>



## Bibliografia

[1] CENÁRIOS: Rastreamento de Cenários. [S. l.]. Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf>.

## Histórico de Versão

| Versão | Data       | Descrição                  | Autor(es)     | Revisor(es)     |
| ------ | ---------- | --------------------       | ------------- | -------------   |
| `1.0`  | 11/10/2023 | Criação do documento       | Shaíne  | Ana Caroline        |
| `1.1`  | 11/10/2023 | Adição de dois cenários       | Shaíne  | Ana Caroline        |
| `1.2`  | 12/10/2023 | Adição dos cenários 04 e 05      | Shaíne  | Ana Caroline        |
