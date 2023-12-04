# Moscow

## Introdução

A técnica de priorização MoSCoW é uma abordagem que categoriza requisitos ou tarefas em quatro grupos principais: Must-have (Deve Ter), Should-have (Deveria Ter), Could-have (Poderia Ter) e Won't-have (Não Deve Ter). Ela ajuda as equipes a identificar e priorizar o que é essencial, importante, opcional e o que não será incluído em um projeto, garantindo uma alocação eficiente de recursos e a entrega de resultados alinhados com as expectativas dos stakeholders.

## Metodologia

### Must-have

São os requisitos prioritários/críticos para o negócio, como: normativas da bolsa de valores, informações que afetam a credibilidade da empresa, entre outros. Dessa forma, se um desses itens não for concluído, o projeto não pode ser considerado como finalizado com sucesso.

### Should-have

Importantes, mas não são necessários (do ponto de vista estratégico) para entrega neste momento. Pode-se ter outro meio de se atender a necessidade classificada como SHOULD, ou pode-se esperar um pouco para ser trabalhado(ex: a conclusão de outro projeto em andamento reduzirá ou eliminará a necessidade do projeto demandado).

### Could-have

São os itens desejáveis, mas não são necessário (do ponto de vista estratégico) e podem melhorar a satisfação do cliente com algum esforço de desenvolvimento.

### Would/ Want/ Won't - have

Menos críticos, com menor retorno sobre o investimento ou não adequados para serem realizados. Decisões que devem ter a concordância dos clientes. Pode ser usado "Would Like (Gostaria)" para conferir melhor entendimento.

## Requisitos
Na tabela 1 contém a priorização dos requisitos seguindo a técnica de Moscow.

### Legenda da tabela:

- OB - [Observação](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/observacao/)
- IN - [Introspecção](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/introspeccao/)
- BS - [Brainstorming](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/brainstorming/)

| Identificação |                                                    Descrição                                                     | Prioridade |
| :-----------: | :--------------------------------------------------------------------------------------------------------------: | :--------: |
|     [OB01](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/observacao/)      |                                         Deve ser possível realizar login                                         |   Must     |
|     [OB02](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/observacao/)      |                                        Deve ser possível pesquisar livros                                        |   Must     |
|     [OB03](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/observacao/)      |             Deve ser possível marcar os livros como: Lido / Lendo / Quero ler / Abandonei / Relendo              |   Must     |
|     [OB04](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/observacao/)      |             Deve existir uma timeline onde é possível ver atualizações literárias de outros usuários.            |   Could    |
|     [OB05](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/observacao/)      |                                Deve ser possível adicionar comentários nos posts                                 |   Could    |
|     [OB06](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/observacao/)      |                                    Deve ser possível curtir posts da timeline                                    |   Could    |
|     [IN01](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/introspeccao/)      |                                       Deve ser possível realizar cadastro                                        |   Must     |
|     [IN02](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/introspeccao/)      |                                       Deve ser possível recuperar a senha                                        |   Must     |
|     [IN03](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/introspeccao/)      |                                       Deve ser possível cadastrar um livro                                       |   Must     |
|     [IN04](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/introspeccao/)      |                        Deve ser possível escrever resenhas dos livros marcados como lidos                        |   Should   |
|     [IN05](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/introspeccao/)      |                                 Deve ser possível dar notas aos livros lidos                                     |   Should   |
|     [IN06](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/introspeccao/)      |                 Deve ser possível contabilizar os dias lendo livros quando o status for relendo                  |   Should   |
|     [IN07](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/introspeccao/)      |                               Deve ser possível registrar o histórico de leitura                                 |   Should   |
|     [IN08](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/introspeccao/)      |                                   Deve ser possível adicionar livro a estante                                    |   Must     |
|     [IN09](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/introspeccao/)      |                                Deve ser possível criar lista de livros desejados                                 |   Could    |
|     [IN10](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/introspeccao/)      |                            Deve ser possível compartilhar a lista de livros desejados                            |   Would    |
|     [IN11](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/introspeccao/)      |                                   Deve ser possível pesquisar outros usuários                                    |   Could    |
|     [IN12](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/introspeccao/)      |                          Deve ser possível abrir e analisar o perfil de outros usuários                          |   Could    |
|     [IN13](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/introspeccao/)      |                              Deve ser possível adicionar outros usuários como amigo                              |   Could    |
|     [IN14](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/introspeccao/)     |                                    Deve ser possível filtrar livros por nota                                     |   Could    |
|     [IN15](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/introspeccao/)      |                                     Deve ser possível filtrar livros por categoria                                      |   Could    |
|     [IN16](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/introspeccao/)      |                A senha deve conter no mínimo um número uma letra maiúscula e um caracter especial                |   Should   |
|     [IN17](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/introspeccao/)      |                      Deve ser possível fazer cadastro/login com as credenciais do facebook                       |   Should   |
|     [IN18](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/introspeccao/)      |                       Deve ser possível obter o aplicativo em qualquer sistema operacional                       |   Must     |
|     [BS01](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/brainstorming/)      |                                Deve ser possível Criar uma meta de leitura para o ano                            |   Should   |
|     [BS02](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/brainstorming/)      |            Deve ser possível sortear um livro cadastrado nas metas para o ano para a próxima leitura             |   Should   |
|     [BS03](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/brainstorming/)      |  Deve ser possível sortear um livro dentre os livros marcados como Quero ler para a próxima leitura do usuário   |   Should   |
|     [BS04](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/brainstorming/)      | Deve ser possível ver informações gerais de um livro cadastrado, como sinopse, autor, quantidade de páginas, etc |   Must     |
|     [BS05](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/brainstorming/)      |                                  Deve existir uma aba de lançamentos de livros                                   |   Should   |
|     [BS06](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/brainstorming/)      |                            Deve existir uma aba de notícias sobre editoras e autores                             |   Should   |
|     [BS07](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/brainstorming/)      |                          Deve existir um FAQ para guiar os usuários nas funcionalidades                          |   Should   |
|     [BS08](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/brainstorming/)      |                            Deve ser possível alterar o tema (escuro/claro/variantes)                             |   Could    |
|     [BS09](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/brainstorming/)      |             Deve ser possível visualizar um ranking semanal/mensal de livros mais bem classificados              |   Could    |
|     [BS10](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/brainstorming/)      |                 Deve ser possível visualizar um ranking semanal/mensal de livros mais lidos                      |   Could    |
|     [BS11](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/brainstorming/)      |                         Deve ser possível postar fotos e/ou vídeos em formato "stories"                          |   Could    |
|     [BS12](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/brainstorming/)      |                                     Deve ser possível compartilhar estantes                                      |   Could    |
|     [BS13](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/brainstorming/)      |                            Deve ser possível realizar desafios dentro da plataforma                              |   Could    |
|     [BS14](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/brainstorming/)      |                                  Deve ser possível criar desafios entre amigos                                   |   Could    |
|     [BS15](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/brainstorming/)      |                          Deve ser possível mandar mensagens diretas entre usuários                               |   Could    |
|     [BS16](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/brainstorming/)      |                         Deve ser possível conquistar prêmios e recompensas a partir de Desafios                  |   Would    |
|     [BS17](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/brainstorming/)      |                            Deve ser possível expor prêmios nos perfis e na TimeLine                              |   Would    |
|     [BS18](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/brainstorming/)      |   Deve ser possível receber recomendações de livros com base nas preferências literárias dos usuários            |   Could    |


<div style="text-align: center">
    <p> Tabela 1: Levantamento de requisitos Moscow. (Fonte: Rafael e Shaíne, 2023).</p>
</div>

## Conclusão
A priorização dos requisitos com os usuários do aplicativo Skoob, para fins de documentação, conclui que esse processo é essencial para criar uma documentação clara e eficaz, refletindo as prioridades dos usuários. Essa documentação servirá como uma valiosa referência, garantindo um alinhamento constante com as necessidades dos usuários.

## Bibliografia

[1] SALES, André Barros. Técnicas de Priorização. Disponível em: https://aprender3.unb.br/pluginfile.php/2692772/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em 02 de outubro de 2023.

## Histórico de Versão

| Versão | Data de execução | Data prevista de revisão | Descrição  |   Autor(es)    |  Revisado  |
| :----: | :--------------: | :----------------------: | :--------: | :------------: | :---------:|
| `1.0`  |    02/10/2023    |   03/10/2023    | Criação do artefato | [Shaíne](https://github.com/ShaineOliveira) | <input type="checkbox" enabled checked /> |
| `1.1`  |    03/10/2023    |   04/10/2023    | Priorização de Requisitos | Todos | <input type="checkbox" enabled checked /> |
| `1.2`  |    04/10/2023    |   04/10/2023    | Requisitos de outras técnicas adicionados |  [Rafael Amancio](https://github.com/Rafael-gc) | <input type="checkbox" enabled checked /> |
| `1.3`  |    29/11/2023    |   30/11/2023    | Correções no artefato |  [Shaíne Oliveira](https://github.com/ShaineOliveira) | <input type="checkbox" disabled checked /> |

### Revisão

| Data de Revisão | Cobertura de Versões  |   Técnica  |    Revisor(es)    |
| :-------------: | :-------------------: | :--------: |  :--------------: |
|   03/10/2023   |    `1.0`    |   [Revisão estática](../verificacao/revisoes.md)    |  [Rafael Amancio](https://github.com/Rafael-gc) |
|   04/10/2023   |    `1.2`    |   [Revisão estática](../verificacao/revisoes.md)    |  [Shaíne](https://github.com/ShaineOliveira) |
|   24/11/2023   |    `1.2`    |   [Revisão por inspeção](../verificacao/revisoes.md)    |  [Ana Rocha](https://github.com/anaaroch) |
