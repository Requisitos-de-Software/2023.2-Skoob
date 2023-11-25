# Brainstorming

## Introdução

O brainstorming desempenha um papel fundamental no processo de elicitação de requisitos, ajudando a equipe a identificar, explorar e capturar as necessidades e expectativas dos stakeholders. Durante as sessões de elicitação, o brainstorming permite que os participantes gerem ideias e insights valiosos relacionados aos requisitos do projeto. A abordagem colaborativa promove a criatividade, o diálogo e a compreensão compartilhada, resultando na definição mais precisa e abrangente dos requisitos. Neste contexto, o brainstorming é uma ferramenta essencial para promover a comunicação eficaz e a coleta de informações necessárias para o sucesso do projeto.

## Metodologia

Utilizando a técnica de brainstorming, o mediador conduziu uma série de perguntas cuidadosamente elaboradas para extrair ideias valiosas do usuário. Embora idealmente essa técnica envolva um grupo de 8 a 12 participantes,como diz o livro Interação Humano-Computador (Barbosa e Silva)<a id="a" href="#aa">[3]</a> devido a restrições de tempo e dificuldades na coordenação de horários, não foi possível contar com mais pessoas. No entanto, as respostas fornecidas pelo usuário foram extremamente satisfatórias.

Uma gravação completa do brainstorming foi realizada, e também elaboramos um [termo de autorização de uso de imagem](../img/termo_de_uso.pdf), o qual foi assinado pelo usuário, permitindo-nos utilizar a gravação.

## Cronograma

Na tabela 1, temos o cronograma detalhado do dia e do horário em que a reunião será realizada e também dos participantes e suas respectivas funções na utilização da técnica.

| Participantes        |    Data    | Hora  |
| -------------------- | :--------: | :---: |
| Mediador: Ana        |
| Desenvolvedor:  Yago | 03/10/2023 |  16h  |
| Usuário:  Evilly     |

<div style="text-align: center">
<p> Tabela 1: Cronograma para execução da técnica. (Fonte: Jefferson França, 2023).</p>
</div>

### Perguntas e Respostas

Quais são as funcionalidades que você considera essenciais em um aplicativo voltado para leitores, como o Skoob?

- Tags de opção para classificação de livros e possibilidade de conseguir definir metas para anos diferentes, além da tbr, que possibilita sortear os livros das suas metas para definir a próxima leitura (ver infos dos livros e resenhas).

Quando se trata de eventos literários, que tipo de informações você gostaria de ver sobre eles no aplicativo do Skoob?

- Gostaria de ter mais visibilidade dentro do app, aba de news de literatura.
  
Como o aplicativo do Skoob pode oferecer suporte aos usuários em caso de dúvidas ou problemas relacionados a eventos literários?

- Nunca precisou usar o suporte, mas algumas abas que entra tem o ícone de
interrogação onde é encontrada informações sobre a página.

Que sugestões você tem para tornar o aplicativo do Skoob mais amigável, com um design intuitivo e uma navegação simplificada, garantindo uma experiência agradável para os amantes da leitura?

- O que incomoda um pouco é para ser uma rede social, mas não vê muita interação
entre os usuários, queria melhorar isso, ex.: stories.
- A interface é fácil de mexer mas acha que poderia ser mais moderno o design.
  
Quais recursos de recomendação de livros poderíamos adicionar para ajudar os usuários a descobrir novas leituras?

- Fazer ranking semanal ou mensal dos livros mais lidos na plataforma, quanto mais
ela vê um livro, mais ela quer ler.

Quais recursos de conectividade social podemos implementar para que os usuários possam interagir uns com os outros de maneira mais eficaz?

- Stories.

Quais são as principais reclamações ou desafios que os usuários enfrentam atualmente
com o Skoob, e como podemos resolvê-los?

- Tem um bug específico, onde colocamos a porcentagem de leitura ao registrar um
histórico.

Quais recursos de gamificação poderíamos implementar para tornar o uso do Skoob mais
envolvente e divertido?

- Já tem um ranking, mas é pouco incentivado.
- Tem muita informação legal mas pouco divulgada.
- Sugestões: deixar o ranking visível no perfil da pessoa, medalhas, personalização do passarinho (icone do skoob), criar um avatar como no instagram.

### Gravação da Reunião

<iframe width="1000vw" height="650vh" src="https://www.youtube.com/embed/mLnZGidTMkw" title="Entrevista" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe>

### Legenda das tabelas:
    - n: Número do Requisito;
    - RF:  Requisito Funcional;
    - RNF: Requisito Não Funcional;
    - BSn: Requisito elicitado por meio de Brainstorming;

Na tabela 2, temos os requisitos já priorizados de acordo com a técnica Three-Level Scale. <a id="Tabela2"></a>

|  Id         |                                                     Descrição                                                    | Tipo  |
| :---------: | :--------------------------------------------------------------------------------------------------------------: | :---: |
|     BS01    |                                Deve ser possível Criar uma meta de leitura para o ano                            |  RF   |
|     BS02    |            Deve ser possível sortear um livro cadastrado nas metas para o ano para a próxima leitura             |  RF   |
|     BS03    |  Deve ser possível sortear um livro dentre os livros marcados como Quero ler para a próxima leitura do usuário   |  RF   |
|     BS04    | Deve ser possível ver informações gerais de um livro cadastrado, como sinopse, autor, quantidade de páginas, etc |  RF   |
|     BS05    |                                  Deve existir uma aba de lançamentos de livros                                   |  RF   |
|     BS06    |                            Deve existir uma aba de notícias sobre editoras e autores                             |  RF   |
|     BS07    |                          Deve existir um FAQ para guiar os usuários nas funcionalidades                          |  RF   |
|     BS08    |                            Deve ser possível alterar o tema (escuro/claro/variantes)                             |  RF   |
|     BS09    |             Deve ser possível visualizar um ranking semanal/mensal de livros mais bem classificados              |  RF   |
|     BS10    |                 Deve ser possível visualizar um ranking semanal/mensal de livros mais lidos                      |  RF   |
|     BS11    |                         Deve ser possível postar fotos e/ou vídeos em formato "stories"                          |  RF   |
|     BS12    |                                     Deve ser possível compartilhar estantes                                      |  RF   |
|     BS13    |                            Deve ser possível realizar desafios dentro da plataforma                              |  RF   |
|     BS14    |                                  Deve ser possível criar desafios entre amigos                                   |  RF   |
|     BS15    |                          Deve ser possível mandar mensagens diretas entre usuários                               |  RF   |
|     BS16    |                         Deve ser possível conquistar prêmios e recompensas a partir de Desafios                  |  RF   |
|     BS17    |                            Deve ser possível expor prêmios nos perfis e na TimeLine                              |  RF   |
|     BS18    |   Deve ser possível receber recomendações de livros com base nas preferências literárias dos usuários            |  RF   |
|     BS19      |   O Skoob deve ser capaz de interoperar com outras plataformas de redes sociais, permitindo aos usuários compartilhar conteúdo.          |   RNF   |


<div style="text-align: center">
<p> Tabela 2: Requisitos elicitados através do brainstorming. (Fonte: Jefferson França, 2023).</p>
</div>

### Conclusão

A aplicação do brainstorming no processo de elicitação de requisitos para o Skoob foi extremamente eficaz, as respostas fornecidas pelo usuário foram valiosas e abrangentes, as ideias geradas durante a sessão forneceram uma base sólida para a definição dos [requisitos funcionais e não funcionais](requisitos.md) do aplicativo, abrangendo desde funcionalidades essenciais até recursos de conectividade social e gamificação.

## Bibliografia

[1] SERRANO, Milene; SERRANO, Maurício. Requisitos - Elicitação, Modelagem e Análise. Apresentação Power Point. Disponível em: https://aprender3.unb.br/pluginfile.php/2692779/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 04 de outubro de 2023.

[2] Brainstorming em Bilheteria Digital. Disponível em: https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/tecnicas/brainstorming/. Acesso em 04 de Outubro de 2023.

<a id="aa" href="#a">[3]</a> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

## Histórico de Versão

| Versão | Data de execução | Data de revisão |      Descrição      |                                           Autor(es)                                            |                                                                  Revisor(es)                                                                   |
| :----: | :--------------: | :-------------: | :-----------------: | :--------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------: |
| `1.0`  |    04/10/2023    |   04/10/2023    | Criação do artefato | [Jefferson França](https://github.com/Frans6) e [Rafael Amancio](https://github.com/Rafael-gc) | <input type="checkbox" enabled checked /> |
| `1.1`  |    04/10/2023    |   04/10/2023    | Adicionando a gravação | [Yago Passos](https://github.com/yagompassos) | <input type="checkbox" enabled checked /> |
| `1.2`  |    24/10/2023    |   25/10/2023    | Alterações na tabela | [Rafael Amancio](https://github.com/Rafael-gc) | <input type="checkbox" enabled checked />   |
| `1.3`  |    02/11/2023    |   04/11/2023    | Adicionando Conclusão | [Ana Rocha](https://github.com/anaaroch) | <input type="checkbox" enabled checked /> |


### Revisão (V&V)

| Data de Revisão | Cobertura de Versões  |   Técnica  |    Revisor(es)    |
| :-------------: | :-------------------: | :--------: |  :--------------: |
|   04/10/2023   |    `1.0`    |   [Revisão estática](../verificacao/revisoes.md)    |  [Yago Passos](https://github.com/yagompassos) |
|   04/10/2023   |    `1.1`    |   [Revisão estática](../verificacao/revisoes.md)    |  [Rafael Amancio](https://github.com/Rafael-gc) |
|   04/11/2023   |    `1.3`    |   [Revisão estática](../verificacao/revisoes.md)    |  [Yago Passos](https://github.com/yagompassos) |
|   25/11/2023   |    `1.3`    |   [Revisão por inspeção](../verificacao/revisoes.md)    |  [Ana Rocha](https://github.com/anaaroch) |