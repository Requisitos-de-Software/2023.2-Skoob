# Verificação do artefato ["Especificação Suplementar"](https://requisitos-de-software.github.io/2023.2-DETRAN/Entrega_3/especificacao_suplementar/)

## Introdução

A técnica de verificação de artefatos é uma etapa crítica no processo de avaliação de documentos, projetos ou produtos em várias áreas, incluindo Requisitos de Software. Essa abordagem visa examinar detalhadamente o conteúdo, a estrutura e as características específicas de um artefato para avaliar sua qualidade, conformidade com requisitos e adequação aos objetivos definidos.

Neste contexto, pretendemos aplicar essa técnica ao artefato ["Especificação Suplementar"](https://requisitos-de-software.github.io/2023.2-DETRAN/Entrega_3/especificacao_suplementar/) desenvolvido pelo [Grupo 7](https://requisitos-de-software.github.io/2023.2-DETRAN/) <a id="c" href="#cc">[3]</a>. A verificação é baseada no plano de ensino e nas datas estabelecidas nele.

Para esclarecer, a técnica de verificação, inspirada no processo de Fagan, implica na análise rigorosa e sistemática do artefato em busca de erros, inconsistências, lacunas e não conformidades com os requisitos. É uma etapa essencial para garantir a qualidade e a precisão do artefato, assegurando que ele atenda aos objetivos estabelecidos no contexto do projeto ou documento em questão.

## Metodologia

A verificação por inspeção de Fagan é uma técnica formal e estruturada de revisão de documentos que visa identificar erros, falhas e problemas em artefatos como documentos, código-fonte, especificações e outros itens relacionados a projetos de desenvolvimento de software. O processo envolve etapas que incluem planejamento, visão geral, preparação, inspeção, correção e acompanhamento.<a id="b" href="#bb">[2]</a>. Além disso, para verificar o artefato em questão será baseado também nos critérios de avaliação do artefato, disponível como prévia no [plano de ensino](https://aprender3.unb.br/pluginfile.php/2692699/mod_resource/content/34/Plano_de_Ensino%20RE%20022023%20Turma%202.pdf).
O processo será composto pelo "conteúdo esperado" onde foi realizado um checklist baseado nas perguntas do plano de ensino.<a id="a" href="#aa">[1]</a>.

A inspeção de Fagan é ilustrada na Figura 1 apresentada abaixo, demonstrando as etapas envolvidas no processo.

<div style="text-align: center;">
    <img src="../../Fagan.png" alt="image" width="900"/>
</div>

<div style="text-align: center">
<p> Figura 1: <b>Método de Fagan</b>, Inspeção. (Fonte: Slides da aula “Requisitos – Aula 23” dos professores Milene Serrano e Maurício Serrano, 2023)</p>
</div>

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

<div style="text-align: center">
<p> Tabela 1:  Perguntas selecionadas: Formatação do artefato. (Fonte: Shaíne Oliveira, 2023)</p>
</div>

A Tabela 2 contém perguntas no que diz respeito ao conteúdo do artefato. 


| ID  | Conteúdo                                                                      | Possui     | Qualidade     | Observação                                                                                                                 |
| --- | ----------------------------------------------------------------------------- | ---------- | ------------- | -------------------------------------------------------------------------------------------------------------------------- | 
| 1   | Os requisitos são rastreáveis?             | Sim        | Bom         |  Foi colocado apenas referência ao diagrama de casos de uso, mas o diagrama não engloba todos os requisitos listados na especificação suplementar|
| 2   | O documento especifica o tempo de resposta no Desempenho?                   | Sim        | Bom         |   Poderia colocar dados mais precisos, pois citar apenas "rápido" não especifica de fato o desempenho. Dessa forma, seria bom colocar tempo em segundos, etc.                           |
| 3  | O documento especifica qual plataforma o aplicativo pode ser executado?                  | Sim        | Ótimo         |        |
| 4   | A modelagem de especificação suplementar cobre todas as principais características do sistema?                 | Sim        | Ótimo         |                            |
| 5   | Todos os requisitos podem ser testados (RF e RNF)?                  | Sim        | Ótimo        |      |
    

<div style="text-align: center">
<p> Tabela 2: Perguntas selecionadas: Conteúdo do artefato. (Fonte: Shaine Oliveira, 2023).</p>
</div>

## Correções e ajustes sugeridos

O artefato foi muito bem construído, mas não cumpriu de forma "Ótimo" três checklists apresentados na tabela.
Para isso, é recomendado fazer os ajustes seguindo as observações:

#### Referentes a tabela 1:
- [ID6 - Os requisitos são rastreáveis?](#verificacao)

#### Referentes a tabela 2:

- [ID1 - Os requisitos são rastreáveis?](#verificacao)
- [ID2 - O documento especifica o tempo de resposta no Desempenho?](#verificacao) 


## Bibliografia

> <a id="a" href="#aa">[1]</a> SALES, André Barros. Plano de ensino da disciplina. Disponível em: https://aprender3.unb.br/pluginfile.php/2692699/mod_resource/content/34/Plano_de_Ensino%20RE%20022023%20Turma%202.pdf. Acesso em 8 de novembro de 2023.

> <a id="b" href="#b">[2]</a> Slides da aula “Requisitos – Aula 23” dos professores Milene Serrano e Maurício Serrano. Disponível em: https://aprender3.unb.br/pluginfile.php/2692856/mod_resource/content/2/Requisitos%20-%20Aula%20023.pdf. Acessado em: 8 de novembro de 2023.

> <a id="c" href="#cc">[3]</a> Análise de documentos do Grupo 7 da Disciplina de Requisitos. Disponível em: <https://requisitos-de-software.github.io/2023.2-DETRAN/Entrega_3/especificacao_suplementar/>. Acesso em 8 novembro de 2023.



## Histórico de Versão

| Versão | Data de execução | Data prevista de revisão |             Descrição             |                      Autor(es)                       |                     Revisado                      |
| :----: | :--------------: | :-------------: | :-------------------------------: | :--------------------------------------------------: | :--------------------------------------------------: |
| `1.0`  |    07/11/2023    |   10/11/2023    | Criação do artefato |   [Shaíne](https://github.com/ShaineOliveira)   |<input type="checkbox" enabled checked /> |
| `1.1`  |    11/11/2023    |   13/11/2023    | Correções no artefato |   [Shaíne](https://github.com/ShaineOliveira)   | <input type="checkbox" enabled checked />|
| `1.1.1`  |    12/11/2023    |   13/11/2023    | Corrigindo padronização de legendas e referências bibliográficas | [Yago](https://github.com/yagompassos) |  | 


### Revisão

| Data de Revisão | Cobertura de Versões  |          Técnica         |                  Revisor(es)                  |
| :------------: | :-------------: | :--------------------------: |  :----------------------------------------: |
|   12/11/2023   |    `1.0` e `1.1`    |   Revisão estática   |   [Yago](https://github.com/yagompassos)  |
