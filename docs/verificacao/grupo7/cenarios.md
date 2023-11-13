# Verificação do artefato ["Cenários"](https://requisitos-de-software.github.io/2023.2-DETRAN/Entrega_3/cenarios/)

## Introdução

A técnica de verificação de artefatos é uma etapa crítica no processo de avaliação de documentos, projetos ou produtos em várias áreas, incluindo Requisitos de Software. Essa abordagem visa examinar detalhadamente o conteúdo, a estrutura e as características específicas de um artefato para avaliar sua qualidade, conformidade com requisitos e adequação aos objetivos definidos.

Neste contexto, pretendemos aplicar essa técnica ao artefato ["Cenários"](https://requisitos-de-software.github.io/2023.2-DETRAN/Entrega_3/cenarios/) desenvolvido pelo [Grupo 7](https://requisitos-de-software.github.io/2023.2-DETRAN/).<a id="a" href="#aa">[3]</a>. A verificação é baseada no plano de ensino e nas datas estabelecidas nele.

Para esclarecer, a técnica de verificação, inspirada no processo de Fagan, implica na análise rigorosa e sistemática do artefato em busca de erros, inconsistências, lacunas e não conformidades com os requisitos. É uma etapa essencial para garantir a qualidade e a precisão do artefato, assegurando que ele atenda aos objetivos estabelecidos no contexto do projeto ou documento em questão.

## Metodologia

A verificação por inspeção de Fagan é uma técnica formal e estruturada de revisão de documentos que visa identificar erros, falhas e problemas em artefatos como documentos, código-fonte, especificações e outros itens relacionados a projetos de desenvolvimento de software. O processo envolve etapas que incluem planejamento, visão geral, preparação, inspeção, correção e acompanhamento.<a id="a" href="#aa">[2]</a>. Além disso, para verificar o artefato em questão será baseado também nos critérios de avaliação do artefato, disponível como prévia no [plano de ensino](https://aprender3.unb.br/pluginfile.php/2692699/mod_resource/content/34/Plano_de_Ensino%20RE%20022023%20Turma%202.pdf).
O processo será composto pelo "conteúdo esperado" onde foi realizado um checklist baseado nas perguntas do plano de ensino.<a id="a" href="#aa">[1]</a>.

![Inspeção Fagan](../Fagan.png)

<b>Método de Fagan</b>: Inspeção. (Fonte: Slides da aula “Requisitos – Aula 23” dos professores Milene Serrano e Maurício Serrano, 2023)

## Conteúdo esperado

Espera-se que no artefato encontre todos os objetivos e necessidades atendidas com a análise dos documentos.

### Verificação

Sendo assim, foi elaborada a tabela 1 e a tabela 2 relacionando as especificações ideais do artefato, se ele possui ou não o requisito apresentado nas perguntas e quanto a qualidade, baseada na seguinte classificação:

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
| 2   | Há autor e revisor no artefato?                                               | Sim | Ótimo          |                                                                            |
| 3   | Existem referências bibliográficas?                                           | Sim        | Bom | Acredita-se que não tenha apenas uma referência, o próprio aplicativo já se torna uma referência                                                            |
| 4   | Possui hiperlinks para outros artefatos caso necessário?                      | Não        | Pode melhorar           | Os requisitos poderiam ter links para as técnicas de elicitação


<b>Tabela 1</b>: Perguntas selecionadas: Formatação do artefato. (Fonte: Rafael, 2023)


A Tabela 2 contém perguntas no que diz respeito ao conteúdo do artefato. 

| ID  | Conteúdo                                                                      | Possui     | Qualidade     | Observação                                                                                                                 |
| --- | ----------------------------------------------------------------------------- | ---------- | ------------- | -------------------------------------------------------------------------------------------------------------------------- |                 
| 1  | Os cenários possuem título, objetivo, contexto, atores, recursos, epsódios, retrição e exceção?           | Não        | Pode | Os cenários não contém restrições e exceções                       |
| 2  | Os cenários são descritos de forma clara e concisa, fornecendo informações suficientes para entender o contexto, a ação realizada e o resultado esperado?                               | Sim        | Bom | A falta de alguns itens na descrição do cenário acabou afetando o entendimento do contexto (restrições e exceções) |
| 3   | A modelagem de cenários cobre adequadamente as principais funcionalidades e interações do sistema?                                    | Sim        | Ótimo |                                                                                                            |
| 4   | Os cenários são priorizadoes com base em sua importância, impacto e frequência de ocorrência? | Sim        | Ótimo           |   |
| 5   | O cenário está associado a requisitos ou histórias de usuário específicas?                   | Sim        | Ótimo         |                                                                                                                            |


<b>Tabela 2</b>: Perguntas selecionadas: Conteúdo do artefato. (Fonte: Rafael, 2023)

## Correções e ajustes sugeridos

O artefato precisa de ajustes.
Para isso, é recomendado fazer os ajustes seguindo as observações:

#### Referentes a tabela 1:
 - [ID3 - Existem referências bibliográficas?](#verificacao)
 - [ID4 - Possui hiperlinks para outros artefatos caso necessário?](#verificacao)
#### Referentes a tabela 2:
 - [ID1 - Os cenários possuem título, objetivo, contexto, atores, recursos, epsódios, retrição e exceção?  ](#verificacao)
 - [ID2 - Os cenários são descritos de forma clara e concisa, fornecendo informações suficientes para entender o contexto, a ação realizada e o resultado esperado? ](#verificacao)

## Bibliografia

> [1] SALES, André Barros. Plano de ensino da disciplina. Disponível em: https://aprender3.unb.br/pluginfile.php/2692699/mod_resource/content/34/Plano_de_Ensino%20RE%20022023%20Turma%202.pdf. Acesso em 13 de novembro de 2023.

> [2] Slides da aula “Requisitos – Aula 23” dos professores Milene Serrano e Maurício Serrano. Disponível em: https://aprender3.unb.br/pluginfile.php/2692856/mod_resource/content/2/Requisitos%20-%20Aula%20023.pdf. Acessado em: 13 de novembro de 2023.

> [3] Cenários do Grupo 7 da Disciplina de Requisitos. Disponível em: <https://requisitos-de-software.github.io/2023.2-DETRAN/Entrega_3/cenarios/>. Acesso em 13 novembro de 2023.


## Histórico de Versão

| Versão | Data de execução | Data prevista de revisão |             Descrição             |                      Autor(es)                       |                     Revisado                      |
| :----: | :--------------: | :-------------: | :-------------------------------: | :--------------------------------------------------: | :--------------------------------------------------: |
| `1.0`  |    13/11/2023    |   13/11/2023    | Criação do artefato |    [Rafael](https://github.com/Rafael-gc)   | <input type="checkbox" enabled checked /> |



### Revisão (V&V)

| Data de Revisão | Cobertura de Versões  |          Técnica         |                  Revisor(es)                  |
| :------------: | :-------------: | :--------------------------: |  :----------------------------------------: |
|   13/11/2023   |   `1.0`     |   Revisão por inspeção    | [Shaine](https://github.com/ShaineOliveira)   |
