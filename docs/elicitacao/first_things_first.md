# First Things First

## Introdução

Após a elicitação dos requisitos essenciais, precisamos empregar métodos eficazes para a priorização de tais requisitos. Esta etapa é crucial para definir e diferenciar a relevância e a urgência de cada requisito individualmente. Uma das técnicas adotadas para tal, é a técnica conhecida como "First Things First".

## Metodologia

A técnica de priorização "First Things First" representa uma ferramenta importante na gestão de requisitos, ao considerar cuidadosamente os benefícios, custos e riscos  de cada requisito, onde os mesmo são classificados em diferentes níveis de importância, tendo como resultado uma lista clara e organizada de prioridades para a implementação. São feitas avaliações para determinar os respectivos índices (1-9) para cada indicativo acima descrito, que deve considerar a visão do cliente e do desenvolvedor de forma equilibrada. A partir disso, é possível calcular o valor total, avaliar o custo relativo e determinar o nível de risco associado a cada um. Assim, o cálculo da prioridade para cada requisito permite a construção de uma lista ordenada em ordem decrescente de importância, fornecendo um guia claro para a fase de implementação. Esta abordagem meticulosa e bem estruturada assegura que os recursos sejam alocados de maneira eficiente e direcionados aos elementos cruciais para o sucesso do projeto.

## Requisitos
Na tabela 1 são listados os requisitos funcionais elicitados pelo grupo, através dos métodos de [Observaçao](../elicitacao/observacao.md), [Introspecção](../elicitacao/introspeccao.md) e [Brainstoming](../elicitacao/brainstorming.md).

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
|     IN15      |                                     Deve ser possível filtrar por categoria                                      |
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
    <p> Tabela 1: Elicitação de requisitos. (Fonte: Ana Rocha e Yago Passos, 2023).</p>
</div>

## Priorização

Na Figura 1 contém a priorização dos requisitos seguindo a técnica de First Things First.

<div style="text-align: center">
    <p> Figura 1: Priorização de requisitos - First Things First. (Fonte: Ana Rocha e Yago Passos, 2023).</p>
</div>

## Bibliografia

<a id="aa" href="#a">[1]</a> WIEGERS, Karl e BEATTY, Joy. Disponível em: [Software Requirements, Third Edition](https://aprender3.unb.br/pluginfile.php/2692778/mod_resource/content/2/PriorizaA%CC%83%C2%A7A%CC%83%C2%A3o%20de%20Req.pdf). Acesso em: 02 de Outubro de 2023.</br>
<a id="aa" href="#a">[2]</a> SALES, André Barros. Técnicas de Priorização. Disponível em: [Aprender 3](https://aprender3.unb.br/pluginfile.php/2692772/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf). Acesso em 04 de outubro de 2023.

## Histórico de Versão

| Versão | Data de execução | Data de revisão |             Descrição             |                      Autor(es)                       |                     Revisor(es)                      |
| :----: | :--------------: | :-------------: | :-------------------------------: | :--------------------------------------------------: | :--------------------------------------------------: |
| `1.0`  |    02/10/2023    |   03/10/2023    | Criação do artefato |   [Ana Rocha](https://github.com/anaaroch_)    | [Yago Passos](https://github.com/yagompassos) |
| `1.1`  |    04/10/2023    |   04/10/2023    | Atualização do artefato |   [Ana Rocha](https://github.com/anaaroch_) e [Yago Passos](https://github.com/yagompassos)  | [Jefferson](https://github.com/Frans6), [Shaíne](https://github.com/ShaineOliveira) e [Rafael](https://github.com/Rafael-gc) |

