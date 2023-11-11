# Verificação do artefato ["Especificação Suplementar"](https://requisitos-de-software.github.io/2023.2-DETRAN/Entrega_3/especificacao_suplementar/)

## Introdução

A técnica de verificação de artefatos é uma etapa crítica no processo de avaliação de documentos, projetos ou produtos em várias áreas, incluindo Requisitos de Software. Essa abordagem visa examinar detalhadamente o conteúdo, a estrutura e as características específicas de um artefato para avaliar sua qualidade, conformidade com requisitos e adequação aos objetivos definidos.

Neste contexto, pretendemos aplicar essa técnica ao artefato ["Especificação Suplementar"](https://requisitos-de-software.github.io/2023.2-DETRAN/Entrega_3/especificacao_suplementar/) desenvolvido pelo [Grupo 7](https://requisitos-de-software.github.io/2023.2-DETRAN/).<a id="a" href="#aa">[3]</a>. A verificação é baseada no plano de ensino e nas datas estabelecidas nele.

Para esclarecer, a técnica de verificação, inspirada no processo de Fagan, implica na análise rigorosa e sistemática do artefato em busca de erros, inconsistências, lacunas e não conformidades com os requisitos. É uma etapa essencial para garantir a qualidade e a precisão do artefato, assegurando que ele atenda aos objetivos estabelecidos no contexto do projeto ou documento em questão.

## Metodologia

A verificação por inspeção de Fagan é uma técnica formal e estruturada de revisão de documentos que visa identificar erros, falhas e problemas em artefatos como documentos, código-fonte, especificações e outros itens relacionados a projetos de desenvolvimento de software. O processo envolve etapas que incluem planejamento, visão geral, preparação, inspeção, correção e acompanhamento.<a id="a" href="#aa">[2]</a>. Além disso, para verificar o artefato em questão será baseado também nos critérios de avaliação do artefato, disponível como prévia no [plano de ensino](https://aprender3.unb.br/pluginfile.php/2692699/mod_resource/content/34/Plano_de_Ensino%20RE%20022023%20Turma%202.pdf).
O processo será composto pelo "conteúdo esperado" onde foi realizado um checklist baseado nas perguntas do plano de ensino.<a id="a" href="#aa">[1]</a>.

![Inspeção Fagan](../Fagan.png)

<b>Método de Fagan</b>: Inspeção. (Fonte: Slides da aula “Requisitos – Aula 23” dos professores Milene Serrano e Maurício Serrano, 2023)

## Conteúdo esperado

Espera-se que no artefato encontre uma especificação suplementar no modelo FURPS+ com requisitos testáveis e rastreáveis.
### Verificação

Sendo assim, foi elaborada a tabela 1 abaixo relacionando as especificações ideais do artefato, se ele possui ou não o requisito apresentado nas perguntas e quanto a qualidade, baseada na seguinte classificação:

**Possui**

- Sim
- Não
- Incompleto

**Qualidade**

- Ótimo (Apresenta todos os requisitos do conteúdo esperado)
- Bom (Apresenta parcialmente os requisitos do conteúdo esperado)
- Pode melhorar (Não apresenta os requisitos do conteúdo esperado)

A Tabela 1 contém perguntas no que diz respeito à formatação do artefato. 

| ID  | Conteúdo                                                                      | Possui     | Qualidade     | Observação                                                                                                                 |
| --- | ----------------------------------------------------------------------------- | ---------- | ------------- | -------------------------------------------------------------------------------------------------------------------------- |
| 1   | Há histórico de versão padronizado?                                           | Sim        | Ótimo         |                                                                                                                            |
| 2   | Há autor e revisor no artefato?                                               | Sim | Ótimo           |                                                                                         |
| 3   | Existem referências bibliográficas?                                           | Sim        | Ótimo |                                        
| 4   | O artefato segue o modelo FURPS+?| Sim        | Ótimo           |   |
| 5   | Há uma introdução no artefato?            | Sim        | Ótimo |        |
| 6  | Existe uma metodologia definida no artefato?                                          | Sim        | Bom        |            No artefato poderia ter colocado como foi feito todo o processo de planejamento e objetivos com a especificação suplementar                                                                                                                |

<b>Tabela 1</b>: Perguntas selecionadas: Formatação do artefato. (Fonte: Shaíne Oliveira, 2023)

A Tabela 2 contém perguntas no que diz respeito ao conteúdo do artefato. 


| ID  | Conteúdo                                                                      | Possui     | Qualidade     | Observação                                                                                                                 |
| --- | ----------------------------------------------------------------------------- | ---------- | ------------- | -------------------------------------------------------------------------------------------------------------------------- | 
| 1   | Os requisitos são rastreáveis?             | Sim        | Bom         |  Foi colocado apenas referência ao diagrama de casos de uso, mas o diagrama não engloba todos os requisitos listados na especificação suplementar|
| 2   | O documento especifica o tempo de resposta no Desempenho?                   | Sim        | Bom         |   Poderia colocar dados mais precisos, pois citar apenas "rápido" não especifica de fato o desempenho. Dessa forma, seria bom colocar tempo em segundos, etc.                           |
| 3  | O documento especifica qual plataforma o aplicativo pode ser executado?                  | Sim        | Ótimo         |        |
| 4   | A modelagem de especificação suplementar cobre todas as principais características do sistema?                 | Sim        | Ótimo         |                            |
| 5   | Todos os requisitos podem ser testados (RF e RNF)?                  | Sim        | Ótimo        |      |
    


<b>Tabela 2</b>: Perguntas selecionadas: Conteúdo do artefato. (Fonte: Shaíne Oliveira, 2023)

## Correções e ajustes sugeridos

O artefato foi muito bem construído, mas não cumpriu de forma "Ótimo" três checklists apresentados na tabela.
Para isso, é recomendado fazer os ajustes seguindo as observações:

#### Referentes a tabela 1:
- [ID6 - Os requisitos são rastreáveis?](#verificacao)

#### Referentes a tabela 2:

- [ID1 - Os requisitos são rastreáveis?](#verificacao)
- [ID2 - O documento especifica o tempo de resposta no Desempenho?](#verificacao) 


## Bibliografia

> [1] SALES, André Barros. Plano de ensino da disciplina. Disponível em: https://aprender3.unb.br/pluginfile.php/2692699/mod_resource/content/34/Plano_de_Ensino%20RE%20022023%20Turma%202.pdf. Acesso em 8 de novembro de 2023.

> [2] Slides da aula “Requisitos – Aula 23” dos professores Milene Serrano e Maurício Serrano. Disponível em: https://aprender3.unb.br/pluginfile.php/2692856/mod_resource/content/2/Requisitos%20-%20Aula%20023.pdf. Acessado em: 8 de novembro de 2023.

> [3] Análise de documentos do Grupo 7 da Disciplina de Requisitos. Disponível em: <https://requisitos-de-software.github.io/2023.2-DETRAN/Entrega_3/especificacao_suplementar/>. Acesso em 8 novembro de 2023.


## Histórico de Versão

| Versão | Data de execução | Data prevista de revisão |             Descrição             |                      Autor(es)                       |                     Revisado                      |
| :----: | :--------------: | :-------------: | :-------------------------------: | :--------------------------------------------------: | :--------------------------------------------------: |
| `1.0`  |    07/11/2023    |   10/11/2023    | Criação do artefato |   [Shaíne](https://github.com/ShaineOliveira)   | |
| `1.1`  |    11/11/2023    |   13/11/2023    | Correções no artefato |   [Shaíne](https://github.com/ShaineOliveira)   | |


### Revisão (V&V)

| Data de Revisão | Cobertura de Versões  |          Técnica         |                  Revisor(es)                  |
| :------------: | :-------------: | :--------------------------: |  :----------------------------------------: |
|   xx/xx/xxxx   |    --    |   ---    |   [Yago](https://github.com/yagompassos)  |
