# First Things First

## Introdução

Após a elicitação dos requisitos essenciais, precisamos empregar métodos eficazes para a priorização de tais requisitos. Esta etapa é crucial para definir e diferenciar a relevância e a urgência de cada requisito individualmente. Uma das técnicas adotadas para tal, é a técnica conhecida como "First Things First".

## Metodologia

A técnica de priorização "First Things First" representa uma ferramenta importante na gestão de requisitos, ao considerar cuidadosamente os benefícios, custos e riscos  de cada requisito, onde os mesmo são classificados em diferentes níveis de importância, tendo como resultado uma lista clara e organizada de prioridades para a implementação. São feitas avaliações para determinar os respectivos índices (1-9) para cada indicativo acima descrito, que deve considerar a visão do cliente e do desenvolvedor de forma equilibrada. A partir disso, é possível calcular o valor total, avaliar o custo relativo e determinar o nível de risco associado a cada um. Assim, o cálculo da prioridade para cada requisito permite a construção de uma lista ordenada em ordem decrescente de importância, fornecendo um guia claro para a fase de implementação. Esta abordagem meticulosa e bem estruturada assegura que os recursos sejam alocados de maneira eficiente e direcionados aos elementos cruciais para o sucesso do projeto.

## Cronograma

Na tabela 1, temos o cronograma detalhado do dia e do horário em que a reunião será realizada e também dos participantes e suas respectivas funções na utilização da técnica.

| Participantes        |    Data    | Hora  |
| -------------------- | :--------: | :---: |
| Mediador: Ana |
| Desenvolvedor: Shaíne   | 04/10/2023 |  17h  |
| Usuário: Vitória Monteiro      |
<div style="text-align: center">
<p> Tabela 1: Cronograma para execução da técnica. (Fonte: Ana Rocha, 2023).</p>
</div>

## Requisitos
Na tabela 2 são listados os requisitos funcionais elicitados pelo grupo, através dos métodos de [Observaçao](../elicitacao/observacao.md), [Introspecção](../elicitacao/introspeccao.md) e [Brainstoming](../elicitacao/brainstorming.md).

Legenda:

- BS - Brainstorming
- IN - Introspecção
- OB - Observação

| Identificação |                                                    Descrição                                                     |
| :-----------: | :--------------------------------------------------------------------------------------------------------------: |
|     OB01      |                                         Deve ser possível realizar login                                         |
|     OB02      |                                        Deve ser possível pesquisar livros                                        |
|     OB03      |             Deve ser possível marcar os livros como: Lido / Lendo / Quero ler / Abandonei / Relendo              |
|     OB04      |             Deve existir uma timeline onde é possível ver atualizações literárias de outros usuários.            |
|     OB05      |                                Deve ser possível adicionar comentários nos posts                                 |
|     OB06      |                                    Deve ser possível curtir posts da timeline                                    |
|     IN01      |                                       Deve ser possível realizar cadastro                                        |
|     IN02      |                                       Deve ser possível recuperar a senha                                        |
|     IN03      |                                       Deve ser possível cadastrar um livro                                       |
|     IN04      |                        Deve ser possível escrever resenhas dos livros marcados como lidos                        |
|     IN05      |                                 Deve ser possível dar notas aos livros lidos                                     |
|     IN06      |                 Deve ser possível contabilizar os dias lendo livros quando o status for relendo                  |
|     IN07      |                               Deve ser possível registrar o histórico de leitura                                 |
|     IN08      |                                   Deve ser possível adicionar livro a estante                                    |
|     IN09      |                                Deve ser possível criar lista de livros desejados                                 |
|     IN10      |                            Deve ser possível compartilhar a lista de livros desejados                            |
|     IN11      |                                   Deve ser possível pesquisar outros usuários                                    |
|     IN12      |                          Deve ser possível abrir e analisar o perfil de outros usuários                          |
|     IN13      |                              Deve ser possível adicionar outros usuários como amigo                              |
|     IN14      |                                    Deve ser possível filtrar livros por nota                                     |
|     IN15      |                                     Deve ser possível filtrar livros por categoria                               |
|     BS01      |                                Deve ser possível Criar uma meta de leitura para o ano                            |
|     BS02      |            Deve ser possível sortear um livro cadastrado nas metas para o ano para a próxima leitura             |
|     BS03      |  Deve ser possível sortear um livro dentre os livros marcados como Quero ler para a próxima leitura do usuário   |
|     BS04      | Deve ser possível ver informações gerais de um livro cadastrado, como sinopse, autor, quantidade de páginas, etc |
|     BS05      |                                  Deve existir uma aba de lançamentos de livros                                   |
|     BS06      |                            Deve existir uma aba de notícias sobre editoras e autores                             |
|     BS07      |                          Deve existir um FAQ para guiar os usuários nas funcionalidades                          |
|     BS08      |                            Deve ser possível alterar o tema (escuro/claro/variantes)                             |
|     BS09      |             Deve ser possível visualizar um ranking semanal/mensal de livros mais bem classificados              |
|     BS10      |                 Deve ser possível visualizar um ranking semanal/mensal de livros mais lidos                      |
|     BS11      |                         Deve ser possível postar fotos e/ou vídeos em formato "stories"                          |
|     BS12      |                                     Deve ser possível compartilhar estantes                                      |
|     BS13      |                            Deve ser possível realizar desafios dentro da plataforma                              |
|     BS14      |                                  Deve ser possível criar desafios entre amigos                                   |
|     BS15      |                          Deve ser possível mandar mensagens diretas entre usuários                               |
|     BS16      |                         Deve ser possível conquistar prêmios e recompensas a partir de Desafios                  |
|     BS17      |                            Deve ser possível expor prêmios nos perfis e na TimeLine                              |

<div style="text-align: center">
    <p> Tabela 2: Elicitação de requisitos. (Fonte: Ana Rocha e Yago Passos, 2023).</p>
</div>

## Priorização
Para a priorização adequada dos requisitos de forma condizente com o método First-Things-First, definimos os envolvidos:

- **Gerente:** O papel foi executado por [Ana Rocha](https://github.com/anaaroch)
- **Representante dos clientes:** Vitória Monteiro, uma usuária entrevistada.
- **Representante de desenvolvimento:** [Yago Passos](https://github.com/yagompassos) e [Ana Rocha](https://github.com/anaaroch)

### Entrevista 
A primeira etapa da Priorização consistiu em uma entrevista. Nessa entrevista questionamos a representante dos clientes respeito das funcionalidades elicitadas, pedindo que ela fornesesse um número de 1 a 9, estimando o benefício relativo que cada recurso fornece ao cliente. Também foi pedida a mesma métrica para a estimativa da penalidade que o negócio sofreria se o recurso não fosse implementado. <a id="b" href="#bb">[2]</a>

No vídeo 1, destacado a baixo, a entrevista com a representante dos clientes, Vitória Monteiro.
<iframe width="1000vw" height="650vh" src="https://www.youtube.com/embed/xNCw4aAP9tk" title="Reunião 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe>
<div style="text-align: center">
    <p> Vídeo 1: Estimativa da parte do usuário - First Things First. (Fonte: Ana Rocha e Yago Passos, 2023).</p>
</div>

Aqui contém o documento do [Termo de Consentimento de uso da Imagem](./img/termo_de_consentimento_vitoria.pdf), assinado pela usuária entrevistada.

### Estimativa da parte Técnica
A segunda etapa foi uma reunião entre os representantes de desenvolvimento, que ao ponderar as funcionalidades, chegaram na priorização representada na Figura 2:
<div style="text-align: center;">
  <img src="../img/priorizacao_ftf.png" alt="image" width="800"/>
</div>

<div style="text-align: center">
    <p> Figura 2: Priorização de requisitos - First Things First. (Fonte: Ana Rocha e Yago Passos, 2023).</p>
</div>

### Conclusão
Em resumo, a técnica de priorização "First Things First" se mostrou uma ferramenta importante na gestão dos requisitos que elicitamos, permitindo uma abordagem bem definida para determinar a importância de cada funcionalidade, nos proporcionando uma lista clara e organizada de prioridades para a implementação, o que permite uma alocação eficiente de recursos.

## Bibliografia

<a id="aa" href="#a">[1]</a> WIEGERS, Karl e BEATTY, Joy. Disponível em: [Software Requirements, Third Edition](https://aprender3.unb.br/pluginfile.php/2692778/mod_resource/content/2/PriorizaA%CC%83%C2%A7A%CC%83%C2%A3o%20de%20Req.pdf). Acesso em: 02 de Outubro de 2023.</br>
<a id="bb" href="#b">[2]</a> SALES, André. Técnicas de Priorização. Disponível em: [Aprender 3](https://aprender3.unb.br/pluginfile.php/2692772/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf). Acesso em 04 de outubro de 2023.

## Histórico de Versão

| Versão | Data de execução | Data prevista de revisão |             Descrição             |                      Autor(es)                       |                     Revisado                      |
| :----: | :--------------: | :-------------: | :-------------------------------: | :--------------------------------------------------: | :--------------------------------------------------: |
| `1.0`  |    02/10/2023    |   03/10/2023    | Criação do artefato |   [Ana Rocha](https://github.com/anaaroch)    | <input type="checkbox" enabled checked /> |
| `1.1`  |    04/10/2023    |   04/10/2023    | Atualização do artefato |   [Ana Rocha](https://github.com/anaaroch)  | <input type="checkbox" enabled checked /> |
| `1.2`  |    04/10/2023    |   04/10/2023    | Seção de Priorização |   [Yago Passos](https://github.com/yagompassos)    | <input type="checkbox" enabled checked /> |
| `1.3`  |    16/10/2023    |   17/10/2023    | Elaboração da Conclusão | [Ana Rocha](https://github.com/anaaroch) | <input type="checkbox" enabled checked /> |
| `1.4`  |    02/11/2023    |   04/11/2023    | Adicionando cronograma e implementando novo sistema de revisão | [Ana Rocha](https://github.com/anaaroch) | <input type="checkbox" enabled checked /> |

### Revisão
| Data de Revisão | Cobertura de Versões  |          Técnica         |                  Revisor(es)                  |
| :------------: | :-------------: | :--------------------------: |  :----------------------------------------: |
|   04/10/2023   |    `1.1`    |    [Revisão estática](https://requisitos-de-software.github.io/2023.2-Skoob/verificacao/revisoes/)    |  [Yago Passos](https://github.com/yagompassos) |
|   04/10/2023   |    `1.2`    |    [Revisão estática](https://requisitos-de-software.github.io/2023.2-Skoob/verificacao/revisoes/)    |  [Ana Rocha](https://github.com/anaaroch) |
|   18/10/2023   |    `1.3`    |    [Revisão estática](https://requisitos-de-software.github.io/2023.2-Skoob/verificacao/revisoes/)    |  [Yago Passos](https://github.com/yagompassos) |
|   24/11/2023   |    `1.4`    |    [Revisão por inspeção](https://requisitos-de-software.github.io/2023.2-Skoob/verificacao/revisoes/)    |  [Rafael Amancio](https://github.com/Rafael-gc) |