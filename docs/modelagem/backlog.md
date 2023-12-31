# Backlog do Produto

## Introdução

&emsp;&emsp; O Backlog do Produto é uma lista priorizada de itens sobre os quais o time de desenvolvimento trabalhará no decorrer do projeto. Trata-se da lista de funcionalidades e requisitos que deverão ser entregues ao cliente ao longo das Sprints. Ele é atualizado, reordenado e refinado de acordo com o nível de detalhes que é possível de se ter em cada momento do projeto.<br>
&emsp;&emsp; Os itens do Backlog do Produto são organizados pelo Product Owner de acordo com a ordem em que serão desenvolvidos, de forma a maximizar o retorno ao clientes. Assim, os itens do topo do Backlog são colocados em desenvolvimento primeiro [1].


## Metodologia

&emsp;&emsp; Para a metodologia foi utilizado o Microsoft Excel e o [Miro](https://miro.com/pt/) para organizar o agrupamento dos requisitos por temas. Uma reunião na plataforma Teams foi realizada no dia 03/11/2023, em que participaram os integrantes: [Rafael Amancio](https://github.com/Rafael-gc), [Yago Passos](https://github.com/yagompassos) e [Jefferson França](https://github.com/Frans6). A reunião que deu origem a esse artefato foi gravada (Vídeo 1) e pode ser acessada a seguir: 
<iframe width="1000vw" height="650vh" src="https://www.youtube.com/embed/zCLlcU7lMGU" title="Tematização dos Requisitos" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe>

<div style="text-align: center">
<p> Vídeo 1: Elaboração inicial do Backlog. (Fonte: Rafael Amancio, 2023).</p>
</div>     

### Temas

<div style="text-align:justify">
    <p>&emsp;&emsp; Ao analisar os requisitos, foi observado que eles poderiam ser organizados em três grandes temas:</p>
    <ul>
        <li> Login
        <li> Livro
        <li> Usuário
    </ul>
    <p>&emsp;&emsp; Os temas compõem o maior nível de abstração do backlog, sendo necessário especificar ainda mais através da criação dos Épicos.</p>
</div>

### Épicos

<div style="text-align:justify">
    <p>&emsp;&emsp; Ao analisar os temas, foram criados os seguintes Épicos:</p>
    <ul>
        <li> Acessibilidade
        <li> Livro
        <li> Usuário
        <li> Acompanhamento
        <li> Entretenimento
    </ul>
    <p>&emsp;&emsp; Os Épicos melhoram a especificidade da classificação dos requisitos. Com os Épicos definidos, o próximo passo é realizar a classificação.</p>
</div>

### Épico 1 - Acessibilidade


&emsp;&emsp; Esse Épico irá classificar todos os requisitos voltados ao acesso do usuário ao Skoob, abrangendo funções de login, cadastro de usuário, ajuda, entre outras. Esses requisitos podem ser visualizados na Tabela 1:

| ID  | Requisito                                                                            | Rastreabilidade                           |
| --- | ------------------------------------------------------------------------------------ | ----------------------------------------- |
| OB01 | Deve ser possível realizar login                                                    | [OB](../elicitacao/observacao.md)         |
| IN01 | Deve ser possível realizar cadastro                                                 | [IN](../elicitacao/introspeccao.md)       |
| IN02 | Deve ser possível recuperar a senha                                                 | [IN](../elicitacao/introspeccao.md)       |
| IN16 | A senha deve conter no mínimo um número uma letra maiúscula e um caracter especial  | [IN](../elicitacao/introspeccao.md)       |
| IN17 | Deve ser possível fazer cadastro/login com as credenciais do facebook               | [IN](../elicitacao/introspeccao.md)       |
| IN18 | Deve ser possível obter o aplicativo em sistemas IOS e Android                | [IN](../elicitacao/introspeccao.md)       |
| BS07 | Deve existir um FAQ para guiar os usuários nas funcionalidades                | [BS](../elicitacao/brainstorming.md)      |
| BS08 | Deve ser possível alterar o tema (escuro/claro/variantes)               | [BS](../elicitacao/brainstorming.md)      |


<div align="center">
<p> <b>Tabela 1</b>: Requisitos do Épico 1 (Fonte: Rafael Amancio, 2023). </p>
</div>


### Épico 2 - Livro

&emsp;&emsp; Esse Épico irá classificar todos os requisitos voltados aos livros, abrangendo funções de busca, cadastro, visualização, ranking, entre outras. Esses requisitos podem ser visualizados na Tabela 2:

|      ID     | Requisito                                                                                                        | Rastreabilidade                         |
| ----------- | ---------------------------------------------------------------------------------------------------------------- | --------------------------------------- |
|     OB02    |                                        Deve ser possível pesquisar livros                                        |   [OB](../elicitacao/observacao.md)     |
|     IN03    |                                       Deve ser possível cadastrar um livro                                       |   [IN](../elicitacao/introspeccao.md)   |
|     IN04    |                        Deve ser possível escrever resenhas dos livros marcados como lidos                        |   [IN](../elicitacao/introspeccao.md)   |
|     IN05    |                                 Deve ser possível dar notas aos livros lidos                                     |   [IN](../elicitacao/introspeccao.md)   |
|     IN14    |                                    Deve ser possível filtrar livros por nota                                     |   [IN](../elicitacao/introspeccao.md)   |
|     IN15    |                                     Deve ser possível filtrar livros por categoria                               |   [IN](../elicitacao/introspeccao.md)   |
|     BS02    |            Deve ser possível sortear um livro cadastrado nas metas para o ano para a próxima leitura             |   [BS](../elicitacao/brainstorming.md)  |
|     BS03    |  Deve ser possível sortear um livro dentre os livros marcados como Quero ler para a próxima leitura do usuário   |   [BS](../elicitacao/brainstorming.md)  |
|     BS04    | Deve ser possível ver informações gerais de um livro cadastrado, como sinopse, autor, quantidade de páginas, etc |   [BS](../elicitacao/brainstorming.md)  |
|     BS05    |                                  Deve existir uma aba de lançamentos de livros                                   |   [BS](../elicitacao/brainstorming.md)  |
|     BS09    |             Deve ser possível visualizar um ranking semanal/mensal de livros mais bem classificados              |   [BS](../elicitacao/brainstorming.md)  |
|     BS10    |                 Deve ser possível visualizar um ranking semanal/mensal de livros mais lidos                      |   [BS](../elicitacao/brainstorming.md)  |
|     BS18    |   Deve ser possível receber recomendações de livros com base nas preferências literárias dos usuários            |   [BS](../elicitacao/brainstorming.md)  |

<div align="center">
<p> <b>Tabela 2</b>: Requisitos do Épico 2 (Fonte: Rafael Amancio, 2023). </p>
</div>


### Épico 3 - Usuário

&emsp;&emsp; Esse Épico irá classificar todos os requisitos voltados aos usuários e suas interações, abrangendo funções de busca, compartilhamento, mensagens diretas, perfil, entre outras. Esses requisitos podem ser visualizados na Tabela 3:

|      ID     | Requisito                                                                                                        | Rastreabilidade                        |
| ----------- | ---------------------------------------------------------------------------------------------------------------- | -------------------------------------- |
|     OB04    |             Deve existir uma timeline onde é possível ver atualizações literárias de outros usuários.            |   [OB](../elicitacao/observacao.md)    |
|     OB05    |                                Deve ser possível adicionar comentários nos posts                                 |   [OB](../elicitacao/observacao.md)    |
|     OB06    |                                    Deve ser possível curtir posts da timeline                                    |   [OB](../elicitacao/observacao.md)    |
|     IN07    |                               Deve ser possível registrar o histórico de leitura                                 |   [IN](../elicitacao/introspeccao.md)  |
|     IN10    |                            Deve ser possível compartilhar a lista de livros desejados                            |   [IN](../elicitacao/introspeccao.md)  |
|     IN11    |                                   Deve ser possível pesquisar outros usuários                                    |   [IN](../elicitacao/introspeccao.md)  |
|     IN12    |                          Deve ser possível abrir e analisar o perfil de outros usuários                          |   [IN](../elicitacao/introspeccao.md)  |
|     IN13    |                              Deve ser possível adicionar outros usuários como amigo                              |   [IN](../elicitacao/introspeccao.md)  |
|     BS12    |                                     Deve ser possível compartilhar estantes                                      |   [BS](../elicitacao/brainstorming.md) |
|     BS15    |                          Deve ser possível mandar mensagens diretas entre usuários                               |   [BS](../elicitacao/brainstorming.md) |
|     BS17    |                            Deve ser possível expor prêmios nos perfis e na TimeLine                              |   [BS](../elicitacao/brainstorming.md) |

<div align="center">
<p> <b>Tabela 3</b>: Requisitos do Épico 3 (Fonte: Rafael Amancio, 2023). </p>
</div>

### Épico 4 - Acompanhamento


&emsp;&emsp; Esse Épico irá classificar todos os requisitos voltados ao acompanhamento de leitura, abrangendo funções de tags de livros, estantes, contagem de leitura, entre outras. Esses requisitos podem ser visualizados na Tabela 4:

|      ID     | Requisito                                                                                                        | Rastreabilidade                        |
| ----------- | ---------------------------------------------------------------------------------------------------------------- | -------------------------------------- |
|     OB03    |             Deve ser possível marcar os livros como: Lido / Lendo / Quero ler / Abandonei / Relendo              |   [OB](../elicitacao/observacao.md)    |
|     IN06    |                 Deve ser possível contabilizar os dias lendo livros quando o status for relendo                  |   [IN](../elicitacao/introspeccao.md)   |
|     IN08    |                                   Deve ser possível adicionar livro a estante                                    |   [IN](../elicitacao/introspeccao.md)  |
|     IN09    |                                Deve ser possível criar lista de livros desejados                                 |   [IN](../elicitacao/introspeccao.md)  |
|     BS01    |                                Deve ser possível Criar uma meta de leitura para o ano                            |   [BS](../elicitacao/brainstorming.md) |
|     BS06    |                            Deve existir uma aba de notícias sobre editoras e autores                             |   [BS](../elicitacao/brainstorming.md) |


<div align="center">
<p> <b>Tabela 4</b>: Requisitos do Épico 4 (Fonte: Rafael Amancio, 2023). </p>
</div>

### Épico 5 - Entretenimento

&emsp;&emsp; Esse Épico irá classificar todos os requisitos voltados ao entretenimento do usuário, abrangendo funções de stories, desafios e conquistas. Esses requisitos podem ser visualizados na Tabela 4:

|      ID     | Requisito                                                                                                        | Rastreabilidade                        |
| ----------- | ---------------------------------------------------------------------------------------------------------------- | -------------------------------------- |
|     BS11    |                         Deve ser possível postar fotos e/ou vídeos em formato "stories"                          |   [BS](../elicitacao/brainstorming.md) |
|     BS13    |                            Deve ser possível realizar desafios dentro da plataforma                              |   [BS](../elicitacao/brainstorming.md) |
|     BS14    |                                  Deve ser possível criar desafios entre amigos                                   |   [BS](../elicitacao/brainstorming.md) |
|     BS16    |                         Deve ser possível conquistar prêmios e recompensas a partir de Desafios                  |   [BS](../elicitacao/brainstorming.md) |


<div align="center">
<p> <b>Tabela 4</b>: Requisitos do Épico 5 (Fonte: Rafael Amancio, 2023). </p>
</div>

## Priorização

A Tabela 5 a seguir relaciona os épicos definidos, as histórias de usuário e suas prioridades [2]. 

| História de Usuário   | Épico                  | Prioridade |
|-----------------------|------------------------|---------------|
| [US01](user_story.md) | Épico 1: Acessibilidade  | Should       |
| [US02](user_story.md) | Épico 1: Acessibilidade  | Must       |
| [US03](user_story.md) | Épico 4: Acompanhamento  | Must       |
| [US04](user_story.md) | Épico 4: Acompanhamento  | Should       |
| [US05](user_story.md) | Épico 2: Livro           | Could  |
| [US06](user_story.md) | Épico 3: Usuário         | Should      |
| [US07](user_story.md) | Épico 3: Usuário         | Should      |
| [US08](user_story.md) | Épico 4: Acompanhamento  | Should      |
| [US09](user_story.md) | Épico 4: Acompanhamento  | Could |
| [US10](user_story.md) | Épico 3: Usuário         | Would      |
| [US11](user_story.md) | Épico 3: Usuário         | Could      |
| [US12](user_story.md) | Épico 3: Usuário         | Could      |
| [US13](user_story.md) | Épico 3: Usuário         | Could      |
| [US14](user_story.md) | Épico 2: Livro           | Could      |
| [US15](user_story.md) | Épico 2: Livro           | Could      |
| [US16](user_story.md) | Épico 5: Entretenimento  | Could      |
| [US17](user_story.md) | Épico 5: Entretenimento  | Could      |
| [US18](user_story.md) | Épico 2: Livro           | Could      |
| [US19](user_story.md) | Épico 2: Livro           | Should      |
| [US20](user_story.md) | Épico 1: Acessibilidade  | Could      |

<div align="center">
<p> <b>Tabela 5</b>: Relação Histórias de Usuário com os Épicos (Fonte: Rafael Amancio, 2023). </p>
</div>

## Conclusão

<div style="text-align: justify">

&emsp;&emsp; O Backlog do Produto consegue deixar claro o que precisa ser feito e em qual ordem de prioridade, servindo como um guia para os desenvolvedores no decorrer do projeto. Sua flexibilidade somada com a simplicidade agrega valor ao cliente e facilita a vida dos desenvolvedores, o que o torna um artefato de extrema importância.

</div>

## Bibliografia

<a id="aa" href="#a">[1]</a> SALES, André. Modelagem de Requisitos. Disponível em: [Aprender 3](https://aprender3.unb.br/pluginfile.php/2692826/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf). Acesso em 04 de novembro de 2023.<br>
<a id="aa" href="#a">[2]</a> Equipe 2023.1-VLC . Disponível em: [Github](https://github.com/Requisitos-de-Software/2023.1-VLC). Acesso em 04 de novembro de 2023.<br>

## Histórico de versão

| Versão | Data | Data prevista de revisão | Descrição| Autor(es) | Revisado
|--|--|--|--|--|--|
| `1.0`  |    04/11/2023    |   04/11/2023    | Criação do artefato |   [Rafael Amancio](https://github.com/Rafael-gc)    | <input type="checkbox" enabled checked /> |
| `1.1`  |    06/11/2023    |   06/11/2023    | Correções e adição do vídeo |   [Rafael Amancio](https://github.com/Rafael-gc)    |  <input type="checkbox" enabled checked />   |
| `1.2`  |    06/11/2023    |   06/11/2023    | Adicionada tabela 5 |   [Rafael Amancio](https://github.com/Rafael-gc)    |  <input type="checkbox" enabled checked />   |
| `1.3`  |    03/12/2023    |        04/12/2023        | Adicionando tabela de revisão | [Ana Rocha](https://github.com/anaaroch) |    <input type="checkbox" disabled checked />      |

### Revisão
| Data de Revisão | Cobertura de Versões  |          Técnica         |                  Revisor(es)                  |
| :------------: | :-------------: | :--------------------------: |  :----------------------------------------: |
|   06/11/2023   |    `1.1`    |    [Revisão estática](../verificacao/revisoes.md)   |  [Yago Passos](https://github.com/yagompassos) e [Jefferson França](https://github.com/Frans6) |
|   22/11/2023   |    `1.2`    |    [Revisão por inspeção](../verificacao/revisoes.md)   |  [Shaíne](https://github.com/ShaineOliveira) |