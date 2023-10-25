# Casos de Uso

## Introdução

Diagramas de casos de uso descrevem o que o sistema faz do ponto de vista do usuário, destacando suas principais funcionalidades e como os usuários interagem com ele. Ele não entra em detalhes técnicos, concentrando-se nas ações do usuário. Esse artefato é frequentemente derivado da especificação de requisitos e pode servir como base para o documento de requisitos do sistema.

## Componentes e Símbolos

Utilizando o software de diagramação LucidChart, elaboramos os diagramas de casos de uso. Para uma melhor compreensão dos diagramas apresentados neste artefato, foi desenvolvida uma legenda, Figura 1, que esclarece o significado de cada elemento presente nos diagramas.

<p align="center">
  <img src="../img/legenda.jpeg" alt="Legenda">
</p>
<div style="text-align: center">
<p>Figura 1 - Legenda diagramas. (Fonte: Jefferson França. 2023)</p>
</div>



### Atores

Em um diagrama de casos de uso, "atores" são entidades externas (como usuários ou sistemas) que interagem com o sistema para realizar ações específicas. Eles ajudam a identificar as interações essenciais entre o sistema e seu ambiente.

### Cenário

Em um diagrama de casos de uso, um "cenário" descreve uma sequência de eventos que ilustra como um ou mais casos de uso específicos são executados. Os cenários fornecem detalhes sobre como os atores interagem com o sistema e o que acontece em diferentes etapas de uma funcionalidade, ajudando a compreender o comportamento do sistema a partir da perspectiva do usuário.

No contexto de um diagrama de casos de uso, é essencial que todos os casos de uso descritos estejam incluídos nos cenários. Caso contrário, esses casos de uso serão considerados fora do escopo do sistema

### Comunicação

Em um diagrama de casos de uso, "comunicação" se refere à forma como os casos de uso interagem.

- "Extend" (estender) descreve cenários opcionais que ampliam um caso de uso base em circunstâncias específicas.
- "Include" (incluir) representa funcionalidades compartilhadas por vários casos de uso, evitando duplicação.
  
Essas relações ajudam a organizar e tornar os diagramas mais eficientes.

### Caso de Uso

Em um diagrama de casos de uso, um "caso de uso" representa uma funcionalidade ou interação específica que o sistema oferece aos usuários ou atores externos. Ele descreve o que o sistema faz, sem entrar em detalhes técnicos, e foca nas ações e interações que os atores têm com o sistema. Os casos de uso ajudam a definir os requisitos funcionais do sistema e a documentar as principais funcionalidades que o sistema deve suportar.

## Casos de Uso

Na Figura 2, é possível analisar o diagrama de casos de uso, no qual estão representadas as atividades mais relevantes e essenciais do aplicativo. As especificações detalhadas dos casos de uso podem ser encontradas nas tabelas de 1 a 5, apresentadas logo abaixo.

<p align="center">
  <img src="../img/casos_de_uso.jpeg" alt="Casos de Uso">
</p>
<div style="text-align: center">
<p>Figura 2 - Diagrama de casos de uso. (Fonte: Jefferson França. 2023)</p>
</div>

### UC01. Adicionar livro à estante

| UC01 | Adicionar Livro à Estante |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Alta |
| **Descrição** | Este caso de uso representa a ação de um usuário adicionar um livro à sua estante pessoal no aplicativo Skoob. A estante é onde o usuário pode acompanhar seus livros lidos, em leitura e desejados. |
| **Requisitos** |  Pesquisar um livro. <br> Selecionar um livro <br> Etiquetar livro  |
| **Condição de entrada** | Pesquisar o livro desejado. |
| **Fluxo principal** | <b>Fluxo 1 - FEP1 </b> <ol> <li> O usuário pesquisa um livro no aplicativo. <li> O usuário seleciona o livro desejado na lista de resultados de pesquisa. <li> O usuário define qual etiqueta ele vai atribuir ao livro. <li> O usuário escolhe uma etiqueta (por exemplo, "Lido", "Lendo", "Desejo Ler", etc.). <li> Dependendo da etiqueta escolhida, o sistema pode solicitar informações adicionais relacionadas a essa etiqueta. Por exemplo, se a etiqueta for "Lido", o sistema pode pedir uma avaliação ou uma resenha do livro. <li> O usuário fecha a aba de etiquetagem e o livro é adicionado à estante. </ol> |
| **Fluxos alternativos** | <b>Fluxo 1 - FEA1 </b><ol> <li> O usuário pesquisa um livro no aplicativo. <li> O usuário seleciona o livro desejado na lista de resultados de pesquisa. <li> O usuário visualiza os detalhes do livros desejado. <li> O usuário define qual etiqueta ele vai atribuir ao livro. <li> O usuário escolhe uma etiqueta (por exemplo, "Lido", "Lendo", "Desejo Ler", etc.). <li> Dependendo da etiqueta escolhida, o sistema pode solicitar informações adicionais relacionadas a essa etiqueta. Por exemplo, se a etiqueta for "Desejo Ler", o sistema pergunta quando ele quer ler. <li> O usuário fecha a aba de etiquetagem e o livro é adicionado à estante. </ol> |
| **Fluxos de exceção** | <b>Fluxo 1 - FE01 </b> <ol> <li> O usuário pesquisa um livro no aplicativo. <li> O livro não é encontrado pelo sistema </ol>
| **Pós condições** | O usuário tem o livro adicionado a sua estante. |
| **Data da criação** | 22/10/2023 |
| **Rastreabilidade** | OB02, OB03 e IN08 |

<div style="text-align: center">
<p> Tabela 1: Especificação do caso de uso: Adicionar Livro à Estante. (Fonte: Jefferson França. 2023).</p>
</div>

### UC02. Escrever Resenha

| UC02 | Escrever Resenha |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Média |
| **Descrição** | Este caso de uso representa a ação de um usuário escrever uma resenha de um livro já lido. A resenha é publicada em seu perfil onde outros usuários podem ter acesso. |
| **Requisitos** | Etiqueta do Livro como "Lido". |
| **Condição de entrada** | Selecionar livro na estante. |
| **Fluxo principal** | <b>Fluxo 1 - FEP1 </b> <ol> <li> O usuário navega até seu perfil. <li> O usuário acessa sua estante. <li> O usuário seleciona um livro que possui a etiqueta marcada como "Lido". <li> O usuário clica "Resenha". <li> O usuário clica em "Comente sua leitura". <li> O usuário define um título da resenha e escreve sua resenha.  <li> O usuário publica sua resenha. </ol> |
| **Fluxos alternativos** | <b>Fluxo 1 - FEP1 </b> <ol> <li> O usuário pesquisa um livro no aplicativo. <li> O usuário seleciona o livro desejado na lista de resultados de pesquisa. <li> O usuário define qual etiqueta ele vai atribuir ao livro. <li> O usuário define a etiqueta como "Lido". <li> O usuário avalia o livro por meio das estrelas. <li> O usuário clica em "Resenha". <li> O usuário clica em "Comente sua leitura". <li> O usuário publica sua resenha</ol> |
| **Fluxos de exceção** | <b>Fluxo 1 - FE01 </b> <ol> <li> O usuário navega até seu perfil. <li> O usuário acessa sua estante. <li> O usuário seleciona um livro que possui a etiqueta marcada como "Lendo". </ol>
| **Pós condições** | O usuário tem a resenha do livro publicada em seu perfil |
| **Data da criação** | 22/10/2023 |
| **Rastreabilidade** | IN04, IN05, IN01, OB01 |

<div style="text-align: center">
<p> Tabela 2: Especificação do caso de uso: Escrever Resenha. (Fonte: Jefferson França. 2023).</p>
</div>

### UC03. Adicionar Amigo

| UC03 | Adicionar Amigo |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Alta |
| **Descrição** | Este caso de uso representa a ação de um usuário adicionar um amigo a sua lista de amigos. |
| **Requisitos** | Ter perfil cadastrado. |
| **Condição de entrada** | Encontrar amigo. |
| **Fluxo principal** | <b>Fluxo 1 - FEP1 </b> <ol> <li> O usuário pesquisa o perfil do amigo. <li> O usuário visita o perfil do amigo. <li> O usuário clica nos três pontos presentes no perfil do amigo. <li> O usuário clica em "Amigos?". <li> O usuário confirma que deseja enviar uma solicitação de amizade </ol> |
| **Fluxos alternativos** | <b>Fluxo 1 - FEP1 </b> <ol> <li> O usuário encontra o perfil de um amigo na página inicial. <li> O usuário acessa o perfil do amigo. <li> O usuário clica nos três pontos presentes no perfil do amigo. <li> O usuário clica em "Amigos?". <li> O usuário confirma que deseja enviar uma solicitação de amizade</ol> |
| **Fluxos de exceção** | <b>Fluxo 1 - FE01 </b> <ol> <li> O usuário pesquisa o perfil do amigo. <li> O usuário digita o nome do amigo errado. <li> O usuário não encontra o amigo. </ol>
| **Pós condições** | O usuário tem seu amigo adicionado a sua lista de amigos |
| **Data da criação** | 22/10/2023 |
| **Rastreabilidade** | IN01, IN11, IN13 |

<div style="text-align: center">
<p> Tabela 3: Especificação do caso de uso: Adicionar Amigo. (Fonte: Jefferson França. 2023).</p>
</div>

### UC04. Compartilhar Atividades de Leitura

| UC04 | Compartilhar Atividades de Leitura |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Alta |
| **Descrição** | Este caso de uso representa a ação de um usuário atualizar seu histórico de leitura. |
| **Requisitos** | Ter um livro com a etiqueta "Lendo". |
| **Condição de entrada** | Etiquetar livro como "Lendo". |
| **Fluxo principal** | <b>Fluxo 1 - FP01 </b> <ol> <li> O usuário acessa o seu perfil. <li> O usuário acessa sua estante. <li> O usuário clica na etiqueta do livro. <li> O usuário clica em "Novo". <li> O usuário informa o que está achando da leitura. <li> O usuário informa qual página ele está. <li> O usuário salva. <li> Atividade de leitura é compartilhada no perfil do usuário. </ol> |
| **Fluxos alternativos** | <b>Fluxo 1 - FA01 </b> <ol> <li> O usuário pesquisa um livro no aplicativo. <li> O usuário seleciona o livro desejado na lista de resultados de pesquisa. <li> O usuário define qual etiqueta como "Lendo". <li> O usuário clica em "Histórico". <li> O usuário clica em "Novo". <li> O usuário informa o que está achando do livro. <li> O usuário informa em qual página ele está. <li> O usuário salva. <li> A atividade de leitura é compartilhada no perfil do usuário. </ol> |
| **Fluxos de exceção** | Não há.
| **Pós condições** | O usuário tem sua atividade de leitura compartilhada |
| **Data da criação** | 22/10/2023 |
| **Rastreabilidade** | OB03, IN07 |

<div style="text-align: center">
<p> Tabela 4: Especificação do caso de uso: Compartilhar atividades de leitura. (Fonte: Jefferson França. 2023).</p>
</div>

### UC05. Comentar publicação

| UC05 | Comentar publicação |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Baixa |
| **Descrição** | Este caso de uso representa a ação de um usuário comentar a atividade de algum outro usuário. |
| **Requisitos** | Ser cadastrado. |
| **Condição de entrada** | Possuir Perfil. |
| **Fluxo principal** | <b>Fluxo 1 - FP01 </b> <ol> <li> O usuário acessa a página principal. <li> O usuário rola a página até encontrar uma publicação do seu interesse. <li> O usuário clica em comentar. <li> O usuário escreve seu comentário. <li> O usuário envia o comentário.</ol> |
| **Fluxos alternativos** | <b>Fluxo 1 - FA01 </b> <ol> <li> O usuário acessa o perfil do amigo. <li> O usuário vê uma publicação que gostou. <li> O usuário clica em comentar. <li> O usuário escreve seu comentário. <li> O usuário envia o comentário. </ol> |
| **Fluxos de exceção** | Não há.
| **Pós condições** | O usuário tem seu comentário publicado na postagem. |
| **Data da criação** | 22/10/2023 |
| **Rastreabilidade** | OB05 |

<div style="text-align: center">
<p> Tabela 5: Especificação do caso de uso: Comentar publicação. (Fonte: Jefferson França. 2023).</p>
</div>

## Bibliografia

[1] DevMedia. O que é UML e Diagramas de Caso de Uso: Introdução Prática à UML. 2012. DevMedia. Disponível em: https://www.devmedia.com.br/o-que-e-uml-e-diagramas-de-caso-de-uso-introducao-pratica-a-uml/23408. Acessado em 24 de outubro de 2023.

[2] SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 11. Disponível em: https://aprender3.unb.br/pluginfile.php/2692803/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf. Acessado em 24 de outubro de 2023.

## Histórico de Versão

| Versão | Data de execução | Data de revisão |      Descrição      |                   Autor(es)                   |                  Revisor(es)                  |
| :----: | :--------------: | :-------------: | :-----------------: | :-------------------------------------------: | :-------------------------------------------: |
| `1.0`  |    23/10/2023    |   24/10/2023    | Criação do artefato | [Jefferson França](https://github.com/Frans6) | [Yago Passos](https://github.com/yagompassos) |
| `1.1`  |    24/10/2023    |   24/10/2023    | Atualização das tabelas | [Jefferson França](https://github.com/Frans6) | [Yago Passos](https://github.com/yagompassos) |

