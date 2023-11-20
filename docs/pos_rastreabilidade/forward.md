# Forward-From

## Introdução

A gestão eficiente e estratégica de projetos é fundamental para o sucesso de organizações contemporâneas. No âmbito do desenvolvimento de software, a rastreabilidade emerge como um elemento crucial, permitindo a compreensão e o controle dos artefatos produzidos ao longo do ciclo de vida do projeto. Entre as diversas abordagens de rastreabilidade, destaca-se o conceito de "forward-from," um artefato que desempenha um papel essencial na manutenção da coerência e na facilitação da comunicação entre as diversas fases do desenvolvimento.

O artefato de rastreabilidade forward-from direciona sua atenção para o futuro, estabelecendo uma conexão direta e sistemática entre os requisitos iniciais e as etapas subsequentes do desenvolvimento <a id="a" href="#aa">[1]</a>. Este mecanismo busca garantir que cada componente do sistema, desde os requisitos até a implementação final, seja claramente relacionado aos seus predecessores, oferecendo uma visão abrangente e contínua da evolução do projeto.

## Metodologia
A estratégia adotada para estabelecer a rastreabilidade entre requisitos e artefatos centrou-se no método "forward-from", uma abordagem de pós-rastreabilidade que implica na criação de vínculos entre os requisitos e os artefatos gerados nas fases subsequentes do desenvolvimento. No âmbito da rastreabilidade entre requisitos, a aplicação do "forward-from" envolve a identificação das dependências entre os requisitos, como refinamentos, generalizações ou substituições entre eles. Por exemplo, um requisito pode evoluir a partir de outro, incorporando novas funcionalidades ou modificando as existentes. Essa análise de dependência é crucial para compreender as inter-relações dos requisitos e garantir sua adequada consideração durante o desenvolvimento do software.

Além disso, a abordagem "forward-from" inclui a rastreabilidade entre requisitos e artefatos de implementação, como código-fonte, documentação técnica e testes. Esta prática permite a identificação dos requisitos implementados em cada componente do sistema, os casos de teste associados e as áreas específicas da arquitetura relacionadas a cada requisito. Essas informações desempenham um papel crucial na preservação da integridade do sistema e na facilitação de futuras atividades de manutenção. Em resumo, a adoção do "forward-from" na rastreabilidade é essencial para estabelecer relações transparentes e consistentes entre os elementos do sistema, promovendo uma compreensão mais clara, manutenção eficaz e evolução contínua do software ao longo de seu ciclo de vida.

## Mapeamento

Na Tabela 1, apresentamos uma legenda para facilitar a compreensão dos artefatos que serão discutidos.

| Legenda | Artefato                  |
| ------- | ------------------------- |
| US      | História de Usuário       |
| UC      | Casos de Uso              |
| C       | Cenários                  |
| L       | Léxico                    |
| INT     | Introspecção              |
| BS      | Brainstorming             |
| OB      | Observação                |
| RF      | Requisitos Funcionais     |
| RNF     | Requisitos não Funcionais |

<div style="text-align: center">
<p>Tabela 1 - Legenda. (Fonte: Jefferson França. 2023)</p>
</div>

Na tabela 2, apresentaremos a vinculação dos artefatos a cada requisito, delineando as conexões estabelecidas. Essa análise proporcionará uma visão detalhada das relações entre requisitos específicos e os respectivos artefatos, evidenciando a consistência e integração no âmbito do processo de rastreabilidade forward.

|     ID do requisito     |        Descrição do requisito        |
| :---------------------: | :----------------------------------: |
|          Épico          |         Épico de referência          |
|          Tema           |           Tema do Backlog            |
|   História de Usuário   |         História de usuário          |
|         Léxico          |          Léxico relacionado          |
|      Casos de uso       |       Caso de uso relacionado        |
|        Cenários         |         Cenário relacionado          |
| Artefatos de elicitação | Artefatos que elicitaram o requisito |
|      Implementado       |              Sim ou Não              |

<div style="text-align: center">
<p>Tabela 2 - Vínculo requisito e artefatos. (Fonte: Jefferson França. 2023)</p>
</div>

### Requisitos Funcionais

|          OB01           |                                            Deve ser possível realizar login                                            |
| :---------------------: | :--------------------------------------------------------------------------------------------------------------------: |
|          Épico          |  [Épico 1 - Autenticação](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)  |
|          Tema           |       [Autenticação](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)       |
|   História de Usuário   |                                                           --                                                           |
|         Léxico          |                                               Léxico relacionado (Yago)                                                |
|      Casos de uso       |                                                           --                                                           |
|        Cenários         | [C03: Realizando o Login](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/cenarios.md) |
| Artefatos de elicitação |      [Observação](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/observacao.md)      |
|      Implementado       |                                                          Sim                                                           |

<div style="text-align: center">
<p>Tabela 3 - Rastreabilidade do OB01. (Fonte: Jefferson França. 2023)</p>
</div>

|          OB02           |                                           Deve ser possível pesquisar livros                                           |
| :---------------------: | :--------------------------------------------------------------------------------------------------------------------: |
|          Épico          |     [Épico 2 - Livro](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)      |
|          Tema           |          [Livro](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)           |
|   História de Usuário   |                                                           --                                                           |
|         Léxico          |                                               Léxico relacionado (Yago)                                                |
|      Casos de uso       |        [UC01](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/casos_de_uso.md)         |
|        Cenários         | [C04: Pesquisando Livros](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/cenarios.md) |
| Artefatos de elicitação |      [Observação](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/observacao.md)      |
|      Implementado       |                                                          Sim                                                           |

<div style="text-align: center">
<p>Tabela 4 - Rastreabilidade do OB02. (Fonte: Jefferson França. 2023)</p>
</div>

|          OB03           |                Deve ser possível marcar os livros como: Lido / Lendo / Quero ler / Abandonei / Relendo                 |
| :---------------------: | :--------------------------------------------------------------------------------------------------------------------: |
|          Épico          | [Épico 4 - Acompanhamento](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md) |
|          Tema           |      [Acompanhamento](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)      |
|   História de Usuário   |         [US03](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/user_story.md)          |
|         Léxico          |                                               Léxico relacionado (Yago)                                                |
|      Casos de uso       |        [UC01](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/casos_de_uso.md)         |
|        Cenários         |           [C01](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/cenarios.md)           |
| Artefatos de elicitação |      [Observação](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/observacao.md)      |
|      Implementado       |                                                          Sim                                                           |

<div style="text-align: center">
<p>Tabela 5 - Rastreabilidade do OB03. (Fonte: Jefferson França. 2023)</p>
</div>

|          OB04           |            Deve existir uma timeline onde é possível ver atualizações literárias de outros usuários.            |
| :---------------------: | :-------------------------------------------------------------------------------------------------------------: |
|          Épico          | [Épico 3 - Usuário](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md) |
|          Tema           |      [Usuário](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)      |
|   História de Usuário   |      [US12](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/user_story.md)      |
|         Léxico          |                                            Léxico relacionado (Yago)                                            |
|      Casos de uso       |                                                       --                                                        |
|        Cenários         |                                                       --                                                        |
| Artefatos de elicitação |  [Observação](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/observacao.md)   |
|      Implementado       |                                                       Sim                                                       |

<div style="text-align: center">
<p>Tabela 6 - Rastreabilidade do OB04. (Fonte: Jefferson França. 2023)</p>
</div>

|          OB05           |                                Deve ser possível adicionar comentários nos posts                                |
| :---------------------: | :-------------------------------------------------------------------------------------------------------------: |
|          Épico          | [Épico 3 - Usuário](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md) |
|          Tema           |      [Usuário](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)      |
|   História de Usuário   |                                                       --                                                        |
|         Léxico          |                                            Léxico relacionado (Yago)                                            |
|      Casos de uso       |     [UC05](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/casos_de_uso.md)     |
|        Cenários         |                                                       --                                                        |
| Artefatos de elicitação |  [Observação](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/observacao.md)   |
|      Implementado       |                                                       Sim                                                       |

<div style="text-align: center">
<p>Tabela 7 - Rastreabilidade do OB05. (Fonte: Jefferson França. 2023)</p>
</div>

|          OB06           |                                   Deve ser possível curtir posts da timeline                                    |
| :---------------------: | :-------------------------------------------------------------------------------------------------------------: |
|          Épico          | [Épico 3 - Usuário](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md) |
|          Tema           |      [Usuário](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)      |
|   História de Usuário   |                                                       --                                                        |
|         Léxico          |                                            Léxico relacionado (Yago)                                            |
|      Casos de uso       |                                                       --                                                        |
|        Cenários         |                                                       --                                                        |
| Artefatos de elicitação |  [Observação](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/observacao.md)   |
|      Implementado       |                                                       Sim                                                       |

<div style="text-align: center">
<p>Tabela 8 - Rastreabilidade do OB06. (Fonte: Jefferson França. 2023)</p>
</div>

|          IN01           |                                         Deve ser possível realizar cadastro                                          |
| :---------------------: | :------------------------------------------------------------------------------------------------------------------: |
|          Épico          | [Épico 1 - Autenticação](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md) |
|          Tema           |      [Autenticação](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)      |
|   História de Usuário   |                                                          --                                                          |
|         Léxico          |                                              Léxico relacionado (Yago)                                               |
|      Casos de uso       |                                                          --                                                          |
|        Cenários         |                                                          --                                                          |
| Artefatos de elicitação |   [Introspecção](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/introspeccao.md)   |
|      Implementado       |                                                         Sim                                                          |

<div style="text-align: center">
<p>Tabela 9 - Rastreabilidade do IN01. (Fonte: Jefferson França. 2023)</p>
</div>

|          IN02           |                                         Deve ser possível recuperar a senha                                          |
| :---------------------: | :------------------------------------------------------------------------------------------------------------------: |
|          Épico          | [Épico 1 - Autenticação](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md) |
|          Tema           |      [Autenticação](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)      |
|   História de Usuário   |        [US02](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/user_story.md)         |
|         Léxico          |                                              Léxico relacionado (Yago)                                               |
|      Casos de uso       |                                                          --                                                          |
|        Cenários         |          [C01](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/cenarios.md)          |
| Artefatos de elicitação |   [Introspecção](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/introspeccao.md)   |
|      Implementado       |                                                         Sim                                                          |

<div style="text-align: center">
<p>Tabela 10 - Rastreabilidade do IN02. (Fonte: Jefferson França. 2023)</p>
</div>

|          IN03           |                                       Deve ser possível cadastrar um livro                                       |
| :---------------------: | :--------------------------------------------------------------------------------------------------------------: |
|          Épico          |  [Épico 2 - Livro](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)   |
|          Tema           |       [Livro](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)        |
|   História de Usuário   |                                                        --                                                        |
|         Léxico          |                                            Léxico relacionado (Yago)                                             |
|      Casos de uso       |                                                        --                                                        |
|        Cenários         |                                                        --                                                        |
| Artefatos de elicitação | [Introspecção](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/introspeccao.md) |
|      Implementado       |                                                       Sim                                                        |

<div style="text-align: center">
<p>Tabela 11 - Rastreabilidade do IN03. (Fonte: Jefferson França. 2023)</p>
</div>

|          IN04           |                        Deve ser possível escrever resenhas dos livros marcados como lidos                        |
| :---------------------: | :--------------------------------------------------------------------------------------------------------------: |
|          Épico          |  [Épico 2 - Livro](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)   |
|          Tema           |       [Livro](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)        |
|   História de Usuário   |      [US06](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/user_story.md)       |
|         Léxico          |                                            Léxico relacionado (Yago)                                             |
|      Casos de uso       |     [UC02](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/casos_de_uso.md)      |
|        Cenários         |                                                        --                                                        |
| Artefatos de elicitação | [Introspecção](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/introspeccao.md) |
|      Implementado       |                                                       Sim                                                        |

<div style="text-align: center">
<p>Tabela 12 - Rastreabilidade do IN04. (Fonte: Jefferson França. 2023)</p>
</div>

|          IN05           |                                   Deve ser possível dar notas aos livros lidos                                   |
| :---------------------: | :--------------------------------------------------------------------------------------------------------------: |
|          Épico          |  [Épico 2 - Livro](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)   |
|          Tema           |       [Livro](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)        |
|   História de Usuário   |      [US06](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/user_story.md)       |
|         Léxico          |                                            Léxico relacionado (Yago)                                             |
|      Casos de uso       |                                                        --                                                        |
|        Cenários         |        [C02](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/cenarios.md)        |
| Artefatos de elicitação | [Introspecção](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/introspeccao.md) |
|      Implementado       |                                                       Sim                                                        |

<div style="text-align: center">
<p>Tabela 13 - Rastreabilidade do IN05. (Fonte: Jefferson França. 2023)</p>
</div>

|          IN06           |                    Deve ser possível contabilizar os dias lendo livros quando o status for relendo                     |
| :---------------------: | :--------------------------------------------------------------------------------------------------------------------: |
|          Épico          | [Épico 4 - Acompanhamento](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md) |
|          Tema           |      [Acompanhamento](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)      |
|   História de Usuário   |         [US08](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/user_story.md)          |
|         Léxico          |                                               Léxico relacionado (Yago)                                                |
|      Casos de uso       |                                                           --                                                           |
|        Cenários         |                                                           --                                                           |
| Artefatos de elicitação |    [Introspecção](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/introspeccao.md)    |
|      Implementado       |                                                          Não                                                           |

<div style="text-align: center">
<p>Tabela 14 - Rastreabilidade do IN06. (Fonte: Jefferson França. 2023)</p>
</div>

|          IN07           |                                Deve ser possível registrar o histórico de leitura                                |
| :---------------------: | :--------------------------------------------------------------------------------------------------------------: |
|          Épico          | [Épico 3 - Usuário](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)  |
|          Tema           |      [Usuário](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)       |
|   História de Usuário   |                                                        --                                                        |
|         Léxico          |                                            Léxico relacionado (Yago)                                             |
|      Casos de uso       |     [UC04](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/casos_de_uso.md)      |
|        Cenários         |                                                        --                                                        |
| Artefatos de elicitação | [Introspecção](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/introspeccao.md) |
|      Implementado       |                                                       Sim                                                        |

<div style="text-align: center">
<p>Tabela 15 - Rastreabilidade do IN07. (Fonte: Jefferson França. 2023)</p>
</div>

|          IN08           |                                      Deve ser possível adicionar livro a estante                                       |
| :---------------------: | :--------------------------------------------------------------------------------------------------------------------: |
|          Épico          | [Épico 4 - Acompanhamento](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md) |
|          Tema           |      [Acompanhamento](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)      |
|   História de Usuário   |         [US03](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/user_story.md)          |
|         Léxico          |                                               Léxico relacionado (Yago)                                                |
|      Casos de uso       |        [UC01](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/casos_de_uso.md)         |
|        Cenários         |           [C01](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/cenarios.md)           |
| Artefatos de elicitação |    [Introspecção](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/introspeccao.md)    |
|      Implementado       |                                                          Sim                                                           |

<div style="text-align: center">
<p>Tabela 16 - Rastreabilidade do IN08. (Fonte: Jefferson França. 2023)</p>
</div>

|          IN11           |                                   Deve ser possível pesquisar outros usuários                                    |
| :---------------------: | :--------------------------------------------------------------------------------------------------------------: |
|          Épico          | [Épico 3 - Usuário](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)  |
|          Tema           |      [Usuário](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)       |
|   História de Usuário   |      [US11](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/user_story.md)       |
|         Léxico          |                                            Léxico relacionado (Yago)                                             |
|      Casos de uso       |     [UC03](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/casos_de_uso.md)      |
|        Cenários         |                                                        --                                                        |
| Artefatos de elicitação | [Introspecção](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/introspeccao.md) |
|      Implementado       |                                                       Sim                                                        |

<div style="text-align: center">
<p>Tabela 17 - Rastreabilidade do IN11. (Fonte: Jefferson França. 2023)</p>
</div>

|          IN14           |                                    Deve ser possível filtrar livros por nota                                     |
| :---------------------: | :--------------------------------------------------------------------------------------------------------------: |
|          Épico          |  [Épico 2 - Livro](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)   |
|          Tema           |       [Livro](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)        |
|   História de Usuário   |      [US04](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/user_story.md)       |
|         Léxico          |                                            Léxico relacionado (Yago)                                             |
|      Casos de uso       |                                                        --                                                        |
|        Cenários         |                                                        --                                                        |
| Artefatos de elicitação | [Introspecção](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/introspeccao.md) |
|      Implementado       |                                                       Não                                                        |

<div style="text-align: center">
<p>Tabela 18 - Rastreabilidade do IN14. (Fonte: Jefferson França. 2023)</p>
</div>

|          IN15           |                                  Deve ser possível filtrar livros por categoria                                  |
| :---------------------: | :--------------------------------------------------------------------------------------------------------------: |
|          Épico          |  [Épico 2 - Livro](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)   |
|          Tema           |       [Livro](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)        |
|   História de Usuário   |      [US05](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/user_story.md)       |
|         Léxico          |                                            Léxico relacionado (Yago)                                             |
|      Casos de uso       |                                                        --                                                        |
|        Cenários         |                                                        --                                                        |
| Artefatos de elicitação | [Introspecção](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/introspeccao.md) |
|      Implementado       |                                                       Não                                                        |

<div style="text-align: center">
<p>Tabela 19 - Rastreabilidade do IN15. (Fonte: Jefferson França. 2023)</p>
</div>

|          IN16           |                  A senha deve conter no mínimo um número uma letra maiúscula e um caracter especial                  |
| :---------------------: | :------------------------------------------------------------------------------------------------------------------: |
|          Épico          | [Épico 1 - Autenticação](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md) |
|          Tema           |      [Autenticação](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)      |
|   História de Usuário   |                                                          --                                                          |
|         Léxico          |                                              Léxico relacionado (Yago)                                               |
|      Casos de uso       |                                                          --                                                          |
|        Cenários         |                                                          --                                                          |
| Artefatos de elicitação |   [Introspecção](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/introspeccao.md)   |
|      Implementado       |                                                         Não                                                          |

<div style="text-align: center">
<p>Tabela 19 - Rastreabilidade do IN16. (Fonte: Jefferson França. 2023)</p>
</div>

|          BS03           |   Deve ser possível sortear um livro dentre os livros marcados como Quero ler para a próxima leitura do usuário    |
| :---------------------: | :----------------------------------------------------------------------------------------------------------------: |
|          Épico          |   [Épico 2 - Livro](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)    |
|          Tema           |        [Livro](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)         |
|   História de Usuário   |       [US19](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/user_story.md)        |
|         Léxico          |                                             Léxico relacionado (Yago)                                              |
|      Casos de uso       |                                                         --                                                         |
|        Cenários         |                                                         --                                                         |
| Artefatos de elicitação | [Brainstorming](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/brainstorming.md) |
|      Implementado       |                                                        Não                                                         |

<div style="text-align: center">
<p>Tabela 20 - Rastreabilidade do BS03. (Fonte: Jefferson França. 2023)</p>
</div>

|          BS07           |                            Deve existir um FAQ para guiar os usuários nas funcionalidades                            |
| :---------------------: | :------------------------------------------------------------------------------------------------------------------: |
|          Épico          | [Épico 1 - Autenticação](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md) |
|          Tema           |      [Autenticação](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)      |
|   História de Usuário   |                                                          --                                                          |
|         Léxico          |                                              Léxico relacionado (Yago)                                               |
|      Casos de uso       |                                                          --                                                          |
|        Cenários         |          [C12](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/cenarios.md)          |
| Artefatos de elicitação |  [Brainstorming](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/brainstorming.md)  |
|      Implementado       |                                                         Não                                                          |

<div style="text-align: center">
<p>Tabela 21 - Rastreabilidade do BS07. (Fonte: Jefferson França. 2023)</p>
</div>

|          BS10           |                    Deve ser possível visualizar um ranking semanal/mensal de livros mais lidos                     |
| :---------------------: | :----------------------------------------------------------------------------------------------------------------: |
|          Épico          |   [Épico 2 - Livro](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)    |
|          Tema           |        [Livro](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)         |
|   História de Usuário   |       [US15](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/user_story.md)        |
|         Léxico          |                                             Léxico relacionado (Yago)                                              |
|      Casos de uso       |                                                         --                                                         |
|        Cenários         |                                                         --                                                         |
| Artefatos de elicitação | [Brainstorming](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/brainstorming.md) |
|      Implementado       |                                                        Não                                                         |

<div style="text-align: center">
<p>Tabela 21 - Rastreabilidade do BS10. (Fonte: Jefferson França. 2023)</p>
</div>

|          BS11           |                            Deve ser possível postar fotos e/ou vídeos em formato "stories"                             |
| :---------------------: | :--------------------------------------------------------------------------------------------------------------------: |
|          Épico          | [Épico 5 - Entretenimento](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md) |
|          Tema           |      [Entretenimento](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)      |
|   História de Usuário   |         [US16](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/user_story.md)          |
|         Léxico          |                                               Léxico relacionado (Yago)                                                |
|      Casos de uso       |                                                           --                                                           |
|        Cenários         |                                                           --                                                           |
| Artefatos de elicitação |   [Brainstorming](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/brainstorming.md)   |
|      Implementado       |                                                          Não                                                           |

<div style="text-align: center">
<p>Tabela 22 - Rastreabilidade do BS11. (Fonte: Jefferson França. 2023)</p>
</div>

|          BS11           |                            Deve ser possível postar fotos e/ou vídeos em formato "stories"                             |
| :---------------------: | :--------------------------------------------------------------------------------------------------------------------: |
|          Épico          | [Épico 5 - Entretenimento](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md) |
|          Tema           |      [Entretenimento](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)      |
|   História de Usuário   |         [US16](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/user_story.md)          |
|         Léxico          |                                               Léxico relacionado (Yago)                                                |
|      Casos de uso       |                                                           --                                                           |
|        Cenários         |                                                           --                                                           |
| Artefatos de elicitação |   [Brainstorming](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/brainstorming.md)   |
|      Implementado       |                                                          Não                                                           |

<div style="text-align: center">
<p>Tabela 22 - Rastreabilidade do BS11. (Fonte: Jefferson França. 2023)</p>
</div>

### Requisitos Não Funcionais

|          BS19           | O Skoob deve ser capaz de interoperar com outras plataformas de redes sociais, permitindo aos usuários compartilhar conteúdo. |
| :---------------------: | :---------------------------------------------------------------------------------------------------------------------------: |
|          Épico          |                                                              --                                                               |
|          Tema           |                                                              --                                                               |
|   História de Usuário   |                                                              --                                                               |
|         Léxico          |                                                   Léxico relacionado (Yago)                                                   |
|      Casos de uso       |                                                              --                                                               |
|        Cenários         |                                                              --                                                               |
| Artefatos de elicitação |      [Brainstorming](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/brainstorming.md)       |
|      Implementado       |                                                              Não                                                              |

<div style="text-align: center">
<p>Tabela 23 - Rastreabilidade do BS19. (Fonte: Jefferson França. 2023)</p>
</div>

|          IN16           |                  A senha deve conter no mínimo um número uma letra maiúscula e um caracter especial                  |
| :---------------------: | :------------------------------------------------------------------------------------------------------------------: |
|          Épico          | [Épico 5 - Autenticação](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md) |
|          Tema           |      [Autenticação](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)      |
|   História de Usuário   |                                                          --                                                          |
|         Léxico          |                                              Léxico relacionado (Yago)                                               |
|      Casos de uso       |                                                          --                                                          |
|        Cenários         |                                                          --                                                          |
| Artefatos de elicitação |   [Introspecção](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/introspeccao.md)   |
|      Implementado       |                                                         Não                                                          |

<div style="text-align: center">
<p>Tabela 24 - Rastreabilidade do IN16. (Fonte: Jefferson França. 2023)</p>
</div>

|          IN18           |                         Deve ser possível obter o aplicativo em qualquer sistema operacional                         |
| :---------------------: | :------------------------------------------------------------------------------------------------------------------: |
|          Épico          | [Épico 5 - Autenticação](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md) |
|          Tema           |      [Autenticação](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/modelagem/backlog.md)      |
|   História de Usuário   |                                                          --                                                          |
|         Léxico          |                                              Léxico relacionado (Yago)                                               |
|      Casos de uso       |                                                          --                                                          |
|        Cenários         |                                                          --                                                          |
| Artefatos de elicitação |   [Introspecção](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/introspeccao.md)   |
|      Implementado       |                                                         Não                                                          |

<div style="text-align: center">
<p>Tabela 24 - Rastreabilidade do IN18. (Fonte: Jefferson França. 2023)</p>
</div>


## Conclusão

Em síntese, a abordagem "forward-from" de rastreabilidade desempenha um papel essencial no desenvolvimento de software, proporcionando uma conexão sistemática entre requisitos e artefatos subsequentes. Ao adotar essa metodologia, a equipe obtém uma visão clara das dependências, promovendo transparência, consistência e facilitando a manutenção do sistema ao longo do tempo <a id="bb" href="#b">[2]</a>. A apresentação detalhada dos requisitos funcionais e não funcionais, juntamente com seu mapeamento para artefatos específicos, destaca a utilidade prática dessa abordagem, fortalecendo a integridade do processo de desenvolvimento e a tomada de decisões fundamentadas.

## Bibliografia

><a id="aa" href="#a">[1]</a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC. 2005.

><a id="bb" href="#b">[2]</a> POHL, Klaus; RUPP, Chris. Requirements Engineering Fundamentals: A Study Guide for the Certified Professional for Requirements Engineering Exam - IREB compliant. O′Reilly. 26 de abril de 2011


## Histórico de Versão

| Versão | Data de execução | Data prevista de revisão |     Descrição      |                   Autor(es)                   |                 Revisado                  |
| :----: | :--------------: | :----------------------: | :----------------: | :-------------------------------------------: | :---------------------------------------: |
| `1.0`  |    19/11/2023    |        20/11/2023        | Elaboração inicial | [Yago Passos](https://github.com/yagompassos) | <input type="checkbox" enabled checked /> |
| `1.1`  |    19/11/2023    |        20/11/2023        | Atualizando artefato | [Jefferson França](https://github.com/Frans6) | <input type="checkbox" enabled checked /> |

### Verificação

| Data de Revisão | Cobertura de Versões |                                Técnica                                 |   Revisor(es)   |
| :-------------: | :------------------: | :--------------------------------------------------------------------: | :-------------: |
|   dd/mm/aaaa    |        `1.0`         |           [Elaboração em pares](../verificacao/revisoes.md)            | Nome do Revisor |
|   dd/mm/aaaa    |    `1.1` e `1.2`     |             [Revisão estática](../verificacao/revisoes.md)             | Nome do Revisor |
|   dd/mm/aaaa    |        Todas         | [Revisão por inspeção](<!-- linkar o artefato de verificação aqui -->) | Nome do Revisor |