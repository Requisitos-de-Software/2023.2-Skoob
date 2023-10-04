# Título

## Introdução

O brainstorming desempenha um papel fundamental no processo de elicitação de requisitos, ajudando a equipe a identificar, explorar e capturar as necessidades e expectativas dos stakeholders. Durante as sessões de elicitação, o brainstorming permite que os participantes gerem ideias e insights valiosos relacionados aos requisitos do projeto. A abordagem colaborativa promove a criatividade, o diálogo e a compreensão compartilhada, resultando na definição mais precisa e abrangente dos requisitos. Neste contexto, o brainstorming é uma ferramenta essencial para promover a comunicação eficaz e a coleta de informações necessárias para o sucesso do projeto.

## Metodologia

Utilizando a técnica de brainstorming, o mediador conduziu uma série de perguntas cuidadosamente elaboradas para extrair ideias valiosas do usuário. Embora idealmente essa técnica envolva um grupo de 8 a 12 participantes, devido a restrições de tempo e dificuldades na coordenação de horários, não foi possível contar com mais pessoas. No entanto, as respostas fornecidas pelo usuário foram extremamente satisfatórias.

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
    - RFn:  Requisito Funcional;
    - RNFn: Requisito Não Funcional;
    - BSn: Requisito elicitado por meio de Brainstorming;

Na tabela 2, temos os requisitos já priorizados de acordo com a técnica Three-Level Scale.

|  Id   |                                                     Descrição                                                     | Tipo  | Implementado |
| :---: | :---------------------------------------------------------------------------------------------------------------: | :---: | :----------: |
| BS01  | Deve ser possível ver informações gerais de um livro cadastrado, como sinopse, autor, quantidade de páginas, etc  | RF02  |     Sim      |
| BS02  |                      Deve ser possível visualizar as minhas resenhas e as de outros usuários                      | RF03  |     Sim      |
| BS03  |              Deve existir uma timeline onde é possível ver informações sobre pessoas que você segue.              | RF04  |     Sim      |
| BS04  |                                   Deve existir uma aba de lançamentos de livros                                   | RF05  |     Sim      |
| BS05  |   Deve ser possível sortear um livro dentre os livros marcados como Quero Ler para a próxima leitura do usuário   | RF06  |     Sim      |
| BS06  |                          Deve ser possível sortear um livro cadastrado nas metas do ano                           | RF07  |     Sim      |
| BS07  |                                    Deve ser possível curtir posts da timeline                                     | RF08  |     Sim      |
| BS08  |                                 Deve ser possível adicionar comentários nos posts                                 | RF09  |     Sim      |
| BS09  |                             Deve ser possível alterar o tema (escuro/claro/variantes)                             | RF10  |     Sim      |
| BS10  |                             Deve existir uma aba de notícias sobre editoras e autores                             | RF11  |     Não      |
| BS11  |                                       Deve haver contato com a equipe Skoob                                       | RF12  |     Não      |
| BS12  |                          Deve existir um FAQ para guiar os usuários nas funcionalidades                           | RF13  |     Não      |
| BS13  |                               Deve ser possível postar algo livremente na timeline                                | RF14  |     Não      |
| BS14  |                                 Deve ser possível alterar o idioma da plataforma                                  | RF15  |     Não      |
| BS15  |                           Deve existir uma lista de sugestão de acordo com livros lidos                           | RF16  |     Não      |
| BS16  |                           Deve existir um ranking semanal/mensal de livros mais lidos.                            | RF17  |     Não      |
| BS17  |                     Deve existir um ranking semanal/mensal de livros mais bem classificados.                      | RF18  |     Não      |
| BS18  |                     Deve ser possível ver a compatibilidade de gosto literário entre usuários                     | RF19  |     Não      |
| BS19  |                                  Deve ser possível criar desafios entre amigos.                                   | RF20  |     Não      |
| BS20  |                                      Deve ser possível compartilhar estantes                                      | RF21  |     Não      |
| BS21  | Deve ser possível postar fotos e/ou vídeos em formato “stories” para compartilhar ideias e novidades sobre livros | RF22  |     Não      |
| BS22  |                               Devem ser exibidas mensagens de erro mais intuitivas                                | RF23  |     Não      |
| BS23  |                        Deve haver recompensas que são obtidas através de desafios e metas.                        | RF24  |     Não      |
| BS24  |                         Deve haver mais medalhas, que são exibidas no perfil das pessoas                          | RF25  |     Não      |
| BS25  |                                        Deve haver um ranking entre amigos.                                        | RF26  |     Não      |
| BS26  |                             Deve ser possível mandar mensagens diretas entre usuários                             | RF27  |     Não      |

<div style="text-align: center">
<p> Tabela 2: Requisitos elicitados através do brainstorming. (Fonte: Jefferson França, 2023).</p>
</div>


## Bibliografia

<a id="aa" href="#a">[1]</a> SERRANO, Milene; SERRANO, Maurício. Requisitos - Elicitação, Modelagem e Análise. Apresentação Power Point. Disponível em: https://aprender3.unb.br/pluginfile.php/2692779/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 04 de outubro de 2023.
<a id="aa" href="#a">[2]</a> Brainstorming em Bilheteria Digital. Disponível em: https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/tecnicas/brainstorming/. Acesso em 04 de Outubro de 2023.


## Histórico de Versão

| Versão | Data de execução | Data de revisão |      Descrição      |                                           Autor(es)                                            |                                                                  Revisor(es)                                                                   |
| :----: | :--------------: | :-------------: | :-----------------: | :--------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------: |
| `1.0`  |    04/10/2023    |   04/10/2023    | Criação do artefato | [Jefferson França](https://github.com/Frans6) e [Rafael Amancio](https://github.com/Rafael-gc) | [Ana Rocha](https://github.com/anaaroch), [Shaíne Oliveira](https://github.com/ShaineOliveira) e [Yago Passos](https://github.com/yagompassos) |
| `1.1`  |    04/10/2023    |   04/10/2023    | Adicionando a gravação | [Yago Passos](https://github.com/yagompassos) | [Rafael Amancio](https://github.com/Rafael-gc) |
