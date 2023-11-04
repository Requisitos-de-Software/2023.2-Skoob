# Three-Level Scale

## Introdução

Um sistema de escala de três níveis é uma abordagem simples e eficaz para classificar requisitos em três categorias distintas. Essas categorias frequentemente são rotuladas como prioridade "alta", "média" e "baixa". A utilidade desse sistema reside na sua capacidade de simplificar a classificação e a tomada de decisões, tornando mais fácil para as pessoas avaliarem e compararem diferentes opções. Para o projeto a técnica será utilizada por um desenvolvedor, que também séra o mediador, e um usuário. A Figura 1 ilustra a divisão das categorias desta técnica.

<div style="text-align: center;">
  <img src="../img/priorizacao_tls.png" alt="image" width="800"/>
</div>
<div style="text-align: center">
    <p> Figura 1: Priorização de requisitos - Three-Level Scale. (Fonte: SALES, André Barros <a href="#aa">[1]</a>, 2023).</p>
</div>

## Metodologia

A técnica divide os requisitos em três categorias: alto, médio e baixo, com base em sua importância ou prioridade. Isso simplifica o processo de avaliação e permite que a equipe se concentre nos requisitos mais críticos, enquanto também reconhece os menos urgentes. É uma abordagem eficaz para garantir que recursos e esforços sejam direcionados para as áreas mais importantes de um projeto ou tarefa.

Todo o processo de categorização é uma atividade colaborativa que envolve a equipe, e é fundamental que haja consenso entre todos os membros sobre a categoria em que cada requisito deve ser classificado.

## Cronograma

Na tabela 1, temos o cronograma detalhado do dia e do horário em que a reunião será realizada e também dos participantes e suas respectivas funções na utilização da técnica.

| Participantes        |    Data    | Hora  |
| -------------------- | :--------: | :---: |
| Mediador: Jefferson |
| Desenvolvedor: Ana   | 04/10/2023 |  17h  |
| Usuário: Vitória Monteiro      |
<div style="text-align: center">
<p> Tabela 1: Cronograma para execução da técnica. (Fonte: Jefferson França, 2023).</p>
</div>

### Gravação da Técninca

Vídeo 1, da gravação: 

<iframe width="1000vw" height="650vh" src="https://www.youtube.com/embed/5C4R6nzaC4U" title="tecnicatls" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe>
<div style="text-align: center">
    <p> Vídeo 1: Estimativa da parte do usuário - First Things First. (Fonte: Grupo Skoob, 2023).</p>
</div>

## Requisitos Priorizados

### Legenda das tabelas:
    - n: Número do Requisito;
    - RFn:  Requisito Funcional;
    - RNFn: Requisito Não Funcional;
    - OBSn: Requisito elicitado por meio de Observação;
    - BSn: Requisito elicitado por meio de Brainstorming;
    - ISn: Requisito elicitado por meio de Introspecção.

Na tabela 2, temos os requisitos já priorizados de acordo com a técnica Three-Level Scale.

# Backlog de Funcionalidades (BS)

|  Id   |                                                    Descrição                                                     | Tipo  | Prioridade |
| :---: | :--------------------------------------------------------------------------------------------------------------: | :---: | :--------: |
| BS01  | Deve ser possível ver informações gerais de um livro cadastrado, como sinopse, autor, quantidade de páginas, etc | RF01  |    Alta    |
| BS02  |                     Deve ser possível visualizar as minhas resenhas e as de outros usuários                      | RF02  |   Média    |
| BS03  |             Deve existir uma timeline onde é possível ver informações sobre pessoas que você segue.              | RF03  |   Baixa    |
| BS04  |                                  Deve existir uma aba de lançamentos de livros                                   | RF04  |    Alta    |
| BS05  |  Deve ser possível sortear um livro dentre os livros marcados como Quero Ler para a próxima leitura do usuário   | RF05  |   Média    |
| BS06  |                          Deve ser possível sortear um livro cadastrado nas metas do ano                          | RF06  |   Baixa    |
| BS07  |                                    Deve ser possível curtir posts da timeline                                    | RF07  |   Baixa    |
| BS08  |                            Deve ser possível alterar o tema (escuro/claro/variantes)                             | RF08  |   Média    |
| BS09  |                            Deve existir uma aba de notícias sobre editoras e autores                             | RF09  |   Baixa    |
| BS10  |                                      Deve haver contato com a equipe Skoob                                       | RF10  |   Média    |
| BS11  |                          Deve existir um FAQ para guiar os usuários nas funcionalidades                          | RF11  |    Alta    |
| BS12  |                               Deve ser possível postar algo livremente na timeline                               | RF12  |   Baixa    |
| BS13  |                                 Deve ser possível alterar o idioma da plataforma                                 | RF13  |   Média    |
| BS14  |                          Deve existir uma lista de sugestão de acordo com livros lidos                           | RF14  |   Baixa    |
| BS15  |                           Deve existir um ranking semanal/mensal de livros mais lidos.                           | RF15  |   Baixa    |
| BS16  |                     Deve existir um ranking semanal/mensal de livros mais bem classificados.                     | RF16  |   Baixa    |
| BS17  |                    Deve ser possível ver a compatibilidade de gosto literário entre usuários                     | RF17  |   Baixa    |
| BS18  |                                  Deve ser possível criar desafios entre amigos.                                  | RF18  |   Média    |
| BS19  |                                     Deve ser possível compartilhar estantes                                      | RF19  |   Baixa    |
| BS20  |                         Deve ser possível postar fotos e/ou vídeos em formato “stories”                          | RF20  |   Baixa    |
| BS21  |                               Devem ser exibidas mensagens de erro mais intuitivas                               | RF21  |   Média    |
| BS22  |                       Deve haver recompensas que são obtidas através de desafios e metas.                        | RF22  |   Baixa    |
| BS23  |                         Deve haver mais medalhas, que são exibidas no perfil das pessoas                         | RF23  |   Baixa    |
| BS24  |                                       Deve haver um ranking entre amigos.                                        | RF24  |   Baixa    |
| BS25  |                            Deve ser possível mandar mensagens diretas entre usuários                             | RF25  |   Baixa    |
| BS26  | O Skoob deve ser capaz de interoperar com outras plataformas de redes sociais, permitindo aos usuários compartilhar conteúdo.  | RNF05  |   Média    |
| OB01  |                                         Deve ser possível realizar login                                         | RF01  |    Alta    |
| OB02  |                                        Deve ser possível pesquisar livros                                        | RF02  |    Alta    |
| OB03  |             Deve ser possível marcar os livros como: Lido / Lendo / Quero ler / Abandonei / Relendo              | RF03  |    Alta    |
| OB04  |            Deve existir uma timeline onde é possível ver atualizações literárias de outros usuários.             | RF04  |   Baixa    |
| OB05  |                                Deve ser possível adicionar comentários nos posts                                 | RF05  |   Média    |
| IN01  |                                       Deve ser possível realizar cadastro                                        | RF01  |    Alta    |
| IN02  |                                       Deve ser possível recuperar a senha                                        | RF02  |    Alta    |
| IN03  |                                       Deve ser possível cadastrar um livro                                       | RF03  |    Alta    |
| IN04  |                        Deve ser possível escrever resenhas dos livros marcados como lidos                        | RF04  |   Média    |
| IN05  |                                   Deve ser possível dar notas aos livros lidos                                   | RF05  |   Média    |
| IN06  |                 Deve ser possível contabilizar os dias lendo livros quando o status for relendo                  | RF06  |   Média    |
| IN07  |                                Deve ser possível registrar o histórico de leitura                                | RF07  |   Média    |
| IN08  |                                   Deve ser possível adicionar livro a estante                                    | RF08  |    Alta    |
| IN09  |                                Deve ser possível criar lista de livros desejados                                 | RF09  |   Baixa    |
| IN10  |                            Deve ser possível compartilhar a lista de livros desejados                            | RF10  |   Baixa    |
| IN11  |                                   Deve ser possível pesquisar outros usuários                                    | RF11  |   Baixa    |
| IN12  |                          Deve ser possível abrir e analisar o perfil de outros usuários                          | RF12  |   Baixa    |
| IN13  |                              Deve ser possível adicionar outros usuários como amigo                              | RF13  |   Baixa    |
| IN14  |                                    Deve ser possível filtrar livros por nota                                     | RF14  |   Baixa    |
| IN15  |                                     Deve ser possível filtrar por categoria                                      | RF15  |   Média    |
| IN16  |               A senha deve conter no mínimo um número, uma letra maiúscula e um caractere especial               | RNF01 |    Alta    |
| IN17  |                      Deve ser possível fazer cadastro/login com as credenciais do Facebook                       | RNF02 |   Média    |
| IN18  |                       Deve ser possível obter o aplicativo em qualquer sistema operacional                       | RNF03 |    Alta    |
| IN19  |      Os dados do usuário devem ser guardados de forma eficaz, impendindo o vazamento dos mesmos                  |   RNF04   |  Alta    |   
| IN20  |              O Skoob deve ser capaz de se adaptar a diferentes tamanhos de tela e resoluções                       |   RNF06  |  Média    |  



<div style="text-align: center">
<p> Tabela 2: Priorização dos requisitos utilizando a técnica. (Fonte: Jefferson França, 2023).</p>
</div>

## Conclusão

A técnica de Three-Level Scale foi instrumental para priorizar os requisitos de forma clara e eficiente, garantindo que a equipe direcionasse seus esforços para as áreas mais cruciais do projeto. Ao categorizar os requisitos em alto, médio e baixo, pudemos estabelecer uma hierarquia clara de necessidades, facilitando a tomada de decisões em relação ao desenvolvimento. A colaboração entre o mediador, o desenvolvedor e o usuário foi fundamental para assegurar que os requisitos fossem avaliados de maneira justa e imparcial. Com base na priorização estabelecida, estamos prontos para avançar com um foco renovado nas funcionalidades mais críticas e fundamentais para o sucesso do projeto.

## Bibliografia

<a id="aa" href="#a">[1]</a> SALES, André Barros. Técnicas de Priorização. Disponível em: [Aprender 3](https://aprender3.unb.br/pluginfile.php/2692778/mod_resource/content/2/PriorizaA%CC%83%C2%A7A%CC%83%C2%A3o%20de%20Req.pdf). Acesso em 04 de outubro de 2023.

## Histórico de Versão

| Versão | Data de execução | Data de revisão |      Descrição      |                                           Autor(es)                                            |                                                                  Revisor(es)                                                                   |
| :----: | :--------------: | :-------------: | :-----------------: | :--------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------: |
| `1.0`  |    03/10/2023    |   04/10/2023    | Criação do artefato | [Jefferson França](https://github.com/Frans6) e [Rafael Amancio](https://github.com/Rafael-gc) | [Ana Rocha](https://github.com/anaaroch), [Shaíne Oliveira](https://github.com/ShaineOliveira) e [Yago Passos](https://github.com/yagompassos) |
| `1.1`  |    04/10/2023    |   04/10/2023    | Adição do vídeo | [Jefferson França](https://github.com/Frans6) e [Rafael Amancio](https://github.com/Rafael-gc) | [Ana Rocha](https://github.com/anaaroch), [Shaíne Oliveira](https://github.com/ShaineOliveira) e [Yago Passos](https://github.com/yagompassos) |
| `1.2`  |    16/10/2023    |   17/10/2023    | Atualização da introdução | [Ana Rocha](https://github.com/anaaroch) | [Jefferson França](https://github.com/Frans6) |
| `1.3`  |    17/10/2023    |   18/10/2023    | Seção de Conclusão | [Yago Passos](https://github.com/yagompassos) | [Ana Rocha](https://github.com/anaaroch) |
