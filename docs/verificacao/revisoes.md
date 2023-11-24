# Revisões 

## Introdução
Os processos de verificação e validação são formas disciplinadas de avaliar um produto e artefatos de software e controlar sua qualidade <a id="a" href="#aa">[1]</a>. A revisão, que foi a análise estática escolhida no planejamento do projeto, ajuda a manter os artefatos padronizados e com conteúdo relevante e correspondente com a demanda do professor. Dessa forma, há menos propagação de erros durante o projeto, que consequentemente reduz o retrabalho <a id="b" href="#bb">[2]</a>.

## Objetivo
O objetivo desse artefato é apresentar as escolhas e definições que a equipe traçou, para padronização dos artefatos e acompanhamento da V&V ao longo do desenvolvimento de todo o projeto.

## Técnicas de Revisão adotadas
Em cada artefato desse projeto de requisitos sobre o aplicativo Skoob, pode ser encontrado 3 diferentes métodos de revisão adotados. Eles estão presentes no histórico de versão adotado pela equipe na [sexta reunião](../atas/reuniao06.md). A Tabela 1 e 2, demonstram como ficou padronizado o histórico de versionamento após essa reunião.

| Versão | Data de execução | Data prevista de revisão |       Descrição      |         Autor(es)      |       Revisado          |
| :----: | :--------------: | :-------------: | :------------------------: | :----------------: | :-----------: |
| `1.0`  |    dd/mm/aaaa    |   dd/mm/aaaa    |   Descrição do que foi feito    | Nome do Autor | <input type="checkbox" enabled checked /> |
| `1.1`  |    dd/mm/aaaa    |   dd/mm/aaaa    |   Descrição do que foi feito    | Nome do Autor | <input type="checkbox" enabled checked /> |
| `1.2`  |    dd/mm/aaaa    |   dd/mm/aaaa    |   Descrição do que foi feito    | Nome do Autor | <input type="checkbox" enabled checked /> |

<div style="text-align: center">
<p> Tabela 1: Nova tabela de Versionamento. (Fonte: Yago Passos, 2023).</p>
</div>

| Data de Revisão | Cobertura de Versões  |          Técnica         |     Revisor(es)    |
| :------------: | :-------------: | :--------------------------: |  :---------------: |
|   dd/mm/aaaa   |    `1.0`   |    Nome da Técnica     |  Nome do Revisor |
|   dd/mm/aaaa   |  `1.1` e `1.2` |    Nome da Técnica     |  Nome do Revisor |

<div style="text-align: center">
<p> Tabela 2: Tabela das revisões. (Fonte: Yago Passos, 2023).</p>
</div>

Dito isso, no campo da técnica de revisão, a terceira coluna da tabela 2, pode ser preenchida com 3 valores diferentes, são eles:

- Elaboração por Pares
- Revisão estática
- Revisão por inspeção.

A primeira técnica, **elaboração por pares**, tem origem na técnica de verificação "programação por pares", apresentada na vídeoaula 05 da Univesp <a id="a" href="#aa">[1]</a>. Consiste na elaboração do artefato em dupla, onde uma pessoa, o autor, escreve o documento *markdown* acompanhado do revisor, em tempo real. Há necessáriamente interação verbal entre eles, para o desenvolvimento do artefato.

A segunda técnica (**revisão estática**) consiste na revisão padrão do artefato, procurando defeitos ou inconsistências, é a forma padrão proposta pelo professor André no início do semestre, utilizada por todos os demais grupos da matéria de Requisitos.

A terceira técnica (**revisão por inspeção**), porém, consiste na execução da [quinta entrega](#verificação), da verificação e validação. Utilizando de uma metodologia criada por Fagan, a equipe analisa os artefatos a partir de uma checklist, criada pelos próprios membros do grupo <a id="b" href="#bb">[2]</a>. As checklists estão descritas em cada artefato de verificação da etapa de [verificação](#verificação).

## Conclusão

A adoção de revisões no processo de desenvolvimento do projeto Skoob revela-se essencial para garantir a consistência e qualidade dos artefatos. A padronização do histórico de versionamento, exemplificada nas Tabelas 1 e 2, proporciona uma visão clara do progresso, reduzindo a propagação de erros e minimizando retrabalhos. As técnicas de revisão, como a elaboração por pares, revisão estática e revisão por inspeção, oferecem abordagens distintas, enriquecendo a qualidade do produto final. Este artefato delineia as escolhas da equipe para a verificação e validação, refletindo nosso comprometimento com a excelência e a transparência ao longo do ciclo de desenvolvimento.

## Bibliografia

> <a id="aa" href="#a">[1]</a> UNIVESP, Gerência e Qualidade de Software - Aula 05 - Verificação e Validação. Disponível em: <https://www.youtube.com/watch?v=1Y-1zz6rZxo>. Acesso em: 09 de Novembro de 2023.

> <a id="bb" href="#b">[2]</a> UNIVESP, Gerência e Qualidade de Software - Aula 06 - Técnica de revisão. Disponível em: <https://www.youtube.com/watch?v=nA1BVDd9GUE>. Acesso em: 09 de Novembro de 2023.

## Histórico de Versão

| Versão | Data de execução | Data prevista de revisão |       Descrição      |         Autor(es)      |       Revisado          |
| :----: | :--------------: | :-------------: | :------------------------: | :----------------: | :-----------: |
| `1.0`  |    12/11/2023    |   13/11/2023    |   Elaboração do artefato    | [Yago Passos](https://github.com/yagompassos) | <input type="checkbox" enabled checked /> |

### Verificação

| Data de Revisão | Cobertura de Versões  |          Técnica         |     Revisor(es)    |
| :------------: | :-------------: | :--------------------------: |  :---------------: |
|   24/11/2023   |    `1.0`   |   Revisão estática  |  [Ana Rocha](https://github.com/anaaroch) |