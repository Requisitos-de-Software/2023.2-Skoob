# Cenários

## Introdução
Cenários são como histórias em evolução que descrevem o que acontece em um ambiente específico, destacando as interações entre as pessoas envolvidas. Geralmente, essas interações envolvem o sistema em desenvolvimento e os participantes externos, como usuários ou outros sistemas. A característica mais importante de um cenário é que ele fornece uma representação concreta de uma atividade que os usuários executam ao realizar uma tarefa específica.

Esses cenários desempenham um papel crucial na fase de levantamento de requisitos de sistemas de software. Eles são usados para descrever como os usuários irão utilizar o sistema e como o sistema se conecta com outros sistemas externos. Isso ajuda a entender e identificar novos requisitos de forma eficaz.<a id="a" href="#aa">[1]</a>.

## Metodologia

A metodologia para criar cenários envolve a identificação de partes interessadas, coleta de informações, definição do escopo, identificação de cenários, descrição detalhada, validação, documentação e uso. Essa abordagem flexível adapta-se às necessidades do projeto, com a participação ativa das partes interessadas.

Os cenários do aplicativo Skoob foram criados com base no texto estruturado, onde emprega uma linguagem natural, baseada na realidade, com a suposição de que o uso da linguagem usada pelos usuários da aplicação, em vez da linguagem técnica do software, torna mais fácil para os clientes compreenderem e confirmarem os requisitos <a id="a" href="#aa">[1]</a>. Dessa forma, os mesmos foram desenvolvidos a partir dos requisitos priorizados nas técnicas de Moscow, Three-Level Scale e First Things First.
Assim, os cenários serão representados conforme a tabela 1.


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
As tabelas 2 a 13 representam os cenários que foram identificados para o aplicativo Skoob. 

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
| Contexto    | O usuário, em sua residência, conectado à internet, está logado em sua conta e deseja avaliar um livro recentemente lido. |
| Recursos    | Smartphone ou computador, conexão com a internet. |
| Ator        | Usuário do Skoob.                               |
| Episódios   | 1. O usuário acessa sua estante pessoal. <br>     2. O usuário seleciona o livro que deseja avaliar. <br>   3. O usuário atribui uma classificação e escreve uma resenha.   <br> 4. O usuário confirma a avaliação.              |
| Restrições  | O livro deve estar na estante do usuário e marcado como "lido".       |
| Exceção     | Se o usuário tentar avaliar um livro que não esteja marcado como "lido" ou não está em sua estante, o sistema exibe uma mensagem de erro. |

<div style="text-align: center">
<p> Tabela 3: Cenário 02. (Fonte: Shaíne Oliveira, 2023).</p>
</div>

#### **C03: Realizando o Login**

| Elemento    | Descrição                                        |
|-------------|--------------------------------------------------|
| Título      | Realizar Login                                   |
| Objetivo    | Permitir que os usuários acessem suas contas no aplicativo. |
| Contexto    | O usuário, em sua residência, conectado à internet, iniciou o aplicativo Skoob e deseja acessar sua conta. |
| Recursos    | Smartphone ou computador, conexão com a internet. |
| Ator        | Usuário do Skoob.                               |
| Episódios   | 1. O usuário abre o aplicativo Skoob. <br>        2. O usuário clica na opção "Login".   <br>     3. O usuário insere seu email e senha.  <br> 4. O usuário clica no botão "Entrar".            |
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
| Contexto    | O usuário, em sua residência, conectado à internet, está logado em sua conta e deseja encontrar um livro específico. |
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
| Contexto    | O usuário, em sua residência, conectado à internet, está logado em sua conta e deseja interagir com uma postagem. |
| Recursos    | Smartphone ou computador, conexão com a internet. |
| Ator        | Usuário do Skoob.                               |
| Episódios   | 1. O usuário navega pelo feed de postagens. <br> 2. O usuário seleciona uma postagem específica. <br> 3. O usuário escreve seu comentário na caixa de texto.<br> 4. O usuário clica no botão "Comentar".          |
| Restrições  | O comentário deve atender aos critérios de moderação e políticas do aplicativo. |
| Exceção     | Se o comentário violar as políticas do aplicativo, ele não será publicado, e o sistema exibirá uma mensagem informando a violação. |

<div style="text-align: center">
<p> Tabela 6: Cenário 05. (Fonte: Shaíne Oliveira, 2023).</p>
</div>

#### **C06: Recuperando a Senha**

| Elemento    | Descrição                                        |
|-------------|--------------------------------------------------|
| Título      | Recuperar a Senha                                |
| Objetivo    | Permitir que os usuários recuperem sua senha em caso de esquecimento. |
| Contexto    | O usuário, em sua casa com acesso à internet, iniciou o aplicativo Skoob e deseja acessar sua conta, mas esqueceu sua senha de login. |
| Recursos    | Smartphone ou computador, conexão com a internet. |
| Ator        | Usuário do Skoob.                               |
| Episódios   | 1. O usuário acessa a tela de login do aplicativo. <br> 2. O usuário clica no link "Esqueci minha senha". <br> 3. O sistema solicita ao usuário seu endereço de e-mail registrado.    <br>  4. O usuário insere seu endereço de e-mail e clica em "Enviar".<br> 5. O sistema envia um e-mail com instruções para redefinir a senha.<br> 6. O usuário acessa sua caixa de entrada de e-mail, segue as instruções e redefine a senha. <br>   7. O sistema confirma a alteração bem-sucedida da senha. |
| Restrições  | O endereço de e-mail fornecido deve estar associado à conta do usuário. |
| Exceção     | Se o endereço de e-mail não estiver associado a nenhuma conta, o sistema informa que a recuperação de senha não é possível. |

<div style="text-align: center">
<p> Tabela 7: Cenário 06. (Fonte: Shaíne Oliveira, 2023).</p>
</div>

#### **C07: Obtendo o Aplicativo em Qualquer Sistema Operacional**

| Elemento    | Descrição                                        |
|-------------|--------------------------------------------------|
| Título      | Obtendo o Aplicativo em Qualquer Sistema Operacional |
| Objetivo    | Permitir que os usuários acessem o aplicativo Skoob em qualquer sistema operacional compatível. |
| Contexto    | O usuário deseja baixar o aplicativo Skoob em um dispositivo com qualquer sistema operacional compatível (por exemplo, Android, iOS), e possui acesso à internet na sua casa. |
| Recursos    | Dispositivo com sistema operacional compatível, conexão com a internet. |
| Ator        | Usuário do Skoob.                               |
| Episódios   | 1. O usuário acessa a loja de aplicativos apropriada para o seu sistema operacional (App Store, Google Play Store). <br> 2. O usuário pesquisa por "Skoob" na loja de aplicativos. <br> 3. O usuário localiza o aplicativo Skoob na lista de resultados. <br> 4. O usuário clica no botão "Baixar" ou "Instalar". <br>   5. O sistema inicia o download e instalação do aplicativo no dispositivo do usuário.<br>  6. O aplicativo Skoob é instalado com sucesso no dispositivo do usuário. |
| Restrições  | O dispositivo do usuário deve ser compatível com o sistema operacional e atender aos requisitos de hardware e software do aplicativo. |
| Exceção     | Se o dispositivo não for compatível ou não atender aos requisitos mínimos, o usuário não conseguirá baixar e instalar o aplicativo. |

<div style="text-align: center">
<p> Tabela 8: Cenário 07. (Fonte: Shaíne Oliveira, 2023).</p>
</div>

#### **C08: Criando uma Meta de Leitura para o Ano**

| Elemento    | Descrição                                        |
|-------------|--------------------------------------------------|
| Título      | Criar uma Meta de Leitura para o Ano             |
| Objetivo    | Permitir que os usuários estabeleçam uma meta de leitura pessoal para o ano. |
| Contexto    | O usuário, em casa ou em qualquer local com acesso à internet, está logado em sua conta no aplicativo Skoob. |
| Recursos    | Smartphone, tablet ou computador, conexão com a internet. |
| Ator        | Usuário do Skoob.                               |
| Episódios   | 1. O usuário pesquisa um livro. <br> 2. O usuário encontra o livro desejado.<br> 3. O usuário define o ano em que deseja ler aquele livro. <br> 5. O sistema confirma a adição do livro à meta do ano selecionado.          |
| Restrições  | O ano deve ser atual ou posterior ao que o usuário se encontra. O livro deve estar disponível na base de dados do Skoob. |
| Exceção     | Se o usuário tentar criar uma meta para anos anteriores ou se o livro não for encontrado, o sistema exibe uma mensagem de erro. |

<div style="text-align: center">
<p> Tabela 9: Cenário 08. (Fonte: Shaíne Oliveira, 2023).</p>
</div>

#### **C09: Cadastro/Login com Credenciais do Facebook**

| Elemento    | Descrição                                        |
|-------------|--------------------------------------------------|
| Título      | Cadastro/Login com Credenciais do Facebook       |
| Objetivo    | Permitir que os usuários cadastrem-se e façam login no aplicativo Skoob usando suas credenciais do Facebook. |
| Contexto    | O usuário está interessado em se cadastrar ou fazer login no aplicativo Skoob e possui uma conta válida no Facebook. O usuário está em qualquer local com acesso à internet. |
| Recursos    | Dispositivo com acesso à internet, conta válida no Facebook. |
| Ator        | Usuário do Skoob.                               |
| Episódios   | 1. O usuário acessa a tela de cadastro ou login no aplicativo Skoob. <br> 2. O usuário opta pela opção "Cadastrar/Login com o Facebook". <br>3. O sistema redireciona o usuário para a página de login do Facebook. <br>4. O usuário insere suas credenciais de login do Facebook (ID e senha). <br>5. O Facebook autentica as credenciais do usuário e autoriza o acesso ao Skoob. <br>6. O usuário é redirecionado de volta ao aplicativo Skoob, agora logado com suas credenciais do Facebook. |
| Restrições  | O usuário deve ter uma conta válida no Facebook, e as credenciais do Facebook devem ser corretas. |
| Exceção     | Se as credenciais do Facebook estiverem incorretas, o sistema exibe uma mensagem de erro. Se o usuário não tiver uma conta no Facebook, o sistema informa que a opção não está disponível para ele. |

<div style="text-align: center">
<p> Tabela 10: Cenário 09. (Fonte: Shaíne Oliveira, 2023).</p>
</div>

#### **C10: Visualizando Informações Gerais de um Livro Cadastrado**

| Elemento    | Descrição                                        |
|-------------|--------------------------------------------------|
| Título      | Visualizar Informações Gerais de um Livro Cadastrado |
| Objetivo    | Permitir que os usuários acessem e visualizem informações detalhadas sobre um livro cadastrado, como sinopse, autor, quantidade de páginas, etc. |
| Contexto    | O usuário está logado em sua conta no aplicativo Skoob, com acesso à internet, e deseja obter informações detalhadas sobre um livro específico. |
| Recursos    | Smartphone, tablet ou computador, conexão com a internet. |
| Ator        | Usuário do Skoob.                               |
| Episódios   | 1. O usuário pesquisa um livro específico no aplicativo Skoob. <br>2. O usuário encontra o livro desejado nos resultados da pesquisa. <br>3. O usuário clica no título do livro para acessar a página de detalhes do livro. <br>       4. O sistema exibe informações gerais, como sinopse, autor, quantidade de páginas e outras informações relevantes sobre o livro. |
| Restrições  | O livro deve estar cadastrado na base de dados do Skoob, e o usuário deve ter permissão para acessar suas informações. |
| Exceção     | Se o livro não estiver cadastrado na base de dados ou o usuário não tiver permissão para acessar as informações, o sistema exibe uma mensagem indicando a indisponibilidade dos detalhes. |

<div style="text-align: center">
<p> Tabela 11: Cenário 10. (Fonte: Shaíne Oliveira, 2023).</p>
</div>

#### **C11: Acessando a Aba de Lançamentos de Livros**

| Elemento    | Descrição                                        |
|-------------|--------------------------------------------------|
| Título      | Acessar a Aba de Lançamentos de Livros            |
| Objetivo    | Permitir que os usuários acessem a seção dedicada aos lançamentos de livros no aplicativo Skoob. |
| Contexto    | O usuário está logado em sua conta no aplicativo Skoob, com acesso à internet, e deseja explorar os lançamentos mais recentes de livros. |
| Recursos    | Smartphone, tablet ou computador, conexão com a internet. |
| Ator        | Usuário do Skoob.                               |
| Episódios   | 1. O usuário abre o aplicativo Skoob.     <br> 2. O usuário navega pela barra de menu ou guias na interface do aplicativo. <br> 3. O usuário seleciona a guia "Lançamentos" ou "Novos Livros". <br> 4. O sistema exibe uma lista dos livros mais recentes lançados no mercado. |
| Restrições  | A guia de "Lançamentos" deve estar disponível e ser acessível para o usuário. |
| Exceção     | Se a guia de "Lançamentos" não estiver disponível ou o usuário não tiver permissão para acessá-la, o sistema informa que a função não está disponível para ele. |

<div style="text-align: center">
<p> Tabela 12: Cenário 11. (Fonte: Shaíne Oliveira, 2023).</p>
</div>

#### **C12: Utilizando o FAQ para Guiar Usuários nas Funcionalidades**

| Elemento    | Descrição                                        |
|-------------|--------------------------------------------------|
| Título      | Utilizar o FAQ para Guiar Usuários nas Funcionalidades |
| Objetivo    | Permitir que os usuários acessem o FAQ (Frequently Asked Questions - Perguntas Frequentes) no aplicativo Skoob para obter informações e orientações sobre as funcionalidades do sistema. |
| Contexto    | O usuário está logado em sua conta no aplicativo Skoob, com acesso à internet, e deseja obter informações sobre como usar as funcionalidades do aplicativo. |
| Recursos    | Smartphone, tablet ou computador, conexão com a internet. |
| Ator        | Usuário do Skoob.                               |
| Episódios   | 1. O usuário abre o aplicativo Skoob.   <br> 2. O usuário navega pela barra de menu ou guias na interface do aplicativo. <br> 3. O usuário localiza a guia "FAQ" ou "Perguntas Frequentes" e clica nela. <br> 4. O sistema exibe uma lista de perguntas frequentes e respostas relacionadas às funcionalidades do aplicativo. <br> 5. O usuário seleciona uma pergunta que corresponde à sua dúvida ou interesse. <br>6. O sistema exibe a resposta detalhada à pergunta do usuário. |
| Restrições  | A guia "FAQ" deve estar disponível e ser acessível para o usuário. As perguntas frequentes devem estar atualizadas e relevantes. |
| Exceção     | Se a guia "FAQ" não estiver disponível ou o usuário não encontrar a resposta desejada, ele pode optar por entrar em contato com o suporte ao cliente para obter ajuda adicional. |


<div style="text-align: center">
<p> Tabela 13: Cenário 12. (Fonte: Shaíne Oliveira, 2023).</p>
</div>

## Conclusão
A criação de cenários desempenha um papel fundamental na engenharia de requisitos e no desenvolvimento de software, concentrando-se nas interações entre os usuários e o sistema em cenários do mundo real. Isso assegura que os requisitos sejam capturados de forma clara e compreensível. Além disso, os cenários promovem uma compreensão compartilhada, garantindo que todas as partes envolvidas no projeto, incluindo desenvolvedores e partes interessadas, possam se comunicar de forma eficaz e compreender as funcionalidades do sistema.

Uma das principais vantagens dos cenários é a detecção antecipada de problemas. Ao elaborar cenários, é possível identificar requisitos conflitantes, ausentes ou impraticáveis antes do início do desenvolvimento, economizando tempo e recursos. Além disso, a criação de cenários fornece uma documentação clara e viva para o sistema, o que é essencial para o desenvolvimento e manutenção contínua do software.

## Bibliografia

<a id="aa" href="#a">[1]</a> CENÁRIOS: Rastreamento de Cenários. [S. l.]. Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf>. <br>
<a id="bb" href="#a">[2]</a> VLC. Cenários. Grupo VLC da disciplina Requisitos de Software, disponível em: https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/cenarios. Acesso em: 16 de outubro de 2023.

## Histórico de Versão

| Versão | Data       | Descrição                  | Autor(es)     | Revisor(es)     |
| ------ | ---------- | --------------------       | ------------- | -------------   |
| `1.0`  | 11/10/2023 | Criação do documento       | [Shaíne](https://github.com/ShaineOliveira)  | [Ana Caroline](https://github.com/anaaroch)        |
| `1.1`  | 11/10/2023 | Adição de dois cenários       | [Shaíne](https://github.com/ShaineOliveira)   | [Ana Caroline](https://github.com/anaaroch)         |
| `1.2`  | 12/10/2023 | Adição dos cenários 04 e 05      | [Shaíne](https://github.com/ShaineOliveira)   | [Ana Caroline](https://github.com/anaaroch)        |
| `1.3`  | 16/10/2023 | Atualizando "contexto" dos cenários     | [Shaíne](https://github.com/ShaineOliveira)   | [Ana Caroline](https://github.com/anaaroch)          |
| `1.4`  | 18/10/2023 | Adiciona novos cenários     | [Shaíne](https://github.com/ShaineOliveira)   | [Ana Caroline](https://github.com/anaaroch)          |
| `1.5`  | 23/10/2023 | Adiciona novos cenários     | [Shaíne](https://github.com/ShaineOliveira)   | Todos      |
| `1.6`  | 23/10/2023 | Correção de cenários     | [Ana Caroline](https://github.com/anaaroch)   |   [Shaíne](https://github.com/ShaineOliveira)    |
| `1.7`  | 24/10/2023 | Adiciona conclusão    |[Shaíne](https://github.com/ShaineOliveira)   |  Todos  |
