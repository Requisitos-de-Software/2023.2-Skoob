# Verificação do artefato ["Forward-From"](https://requisitos-de-software.github.io/2023.2-Skoob/pos_rastreabilidade/forward/)

## Introdução

A verificação de artefatos desempenha um papel crucial na avaliação de documentos, projetos ou produtos em diversas áreas, incluindo os Requisitos de Software. Essa técnica visa a análise minuciosa do conteúdo, estrutura e características específicas de um artefato, com o propósito de avaliar sua qualidade, conformidade com requisitos e adequação aos objetivos estabelecidos. 
Neste contexto, este documento tem como objetivo executar esse procedimento no artefato [Forward-From](https://requisitos-de-software.github.io/2023.2-Skoob/pos_rastreabilidade/forward/) <a id="c" href="#cc">[3]</a> , desenvolvido pelo [Grupo 6](https://requisitos-de-software.github.io/2023.2-Skoob/).

Em termos práticos, a técnica de verificação, inspirada no processo de Fagan, implica na análise rigorosa e sistemática do artefato em busca de erros, inconsistências, lacunas e desvios em relação aos requisitos. Essa etapa é fundamental para assegurar a qualidade e precisão do artefato, garantindo que este esteja alinhado com os objetivos do projeto ou documento em questão.

## Metodologia

A metodologia adotada para a verificação dos artefatos é composta por duas abordagens distintas, cada uma contribuindo para assegurar a qualidade e integridade do material analisado.

A primeira é fundamentada nos critérios de avaliação presentes no [plano de ensino](https://aprender3.unb.br/pluginfile.php/2692699/mod_resource/content/34/Plano_de_Ensino%20RE%20022023%20Turma%202.pdf) <a id="a" href="#aa">[1]</a> e [Software Requirements, Third Edition](https://aprender3.unb.br/pluginfile.php/2692775/mod_resource/content/1/Elicitacao%20de%20Req.pdf) <a id="d" href="#dd">[4]</a>, fornecendo um direcionamento preciso para a avaliação do conteúdo esperado nos artefatos. Essa etapa se baseia em um checklist elaborado a partir da leitura do plano e do livro, abrangendo questionamentos específicos sobre a construção de [Forward-From](https://requisitos-de-software.github.io/2023.2-Skoob/pos_rastreabilidade/forward/) <a id="c" href="#cc">[3]</a>.

A segunda abordagem se apoia na técnica formal de inspeção de Fagan, um processo estruturado que visa identificar e corrigir possíveis erros, falhas e problemas nos artefatos analisados, abrangendo documentos, código-fonte, especificações, entre outros itens relacionados a projetos de desenvolvimento de software. Essa técnica proporciona uma revisão criteriosa e sistemática, contribuindo para a melhoria da qualidade e precisão dos artefatos <a id="b" href="#bb">[2]</a>. A inspeção de Fagan é ilustrada na Figura 1 apresentada abaixo, demonstrando as etapas envolvidas no processo.

![Inspeção Fagan](../Fagan.png)

<div style="text-align: center;">
    Figura 1: Método de Fagan: Inspeção. (Fonte: Slide “Requisitos – Aula 23” <a id="b" href="#bb">[2]</a>, 2023)
</div>

## Conteúdo esperado

É esperado que o artefato inclua a lista de requisitos elicitados com suas devidas identificações e descrições, juntamente com uma análise de pós-rastreabilidade, além de seguir a estrutura padrão básica exigida para todos os artefatos.

## Gravação da verificação

No vídeo 1, destacado abaixo, é realizada a verificação do artefato [forward-from](https://requisitos-de-software.github.io/2023.2-Skoob/pos_rastreabilidade/forward/) conforme o checklist elaborado para tal.

<iframe width="1000vw" height="650vh" src="https://youtube.com/embed/IXHU9X-dSQA" title="V&V - Forward-from" frameborder="0" allow="accelerometer; autoplay; clipboard-write; 
encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe>
<div style="text-align: center">
<p> Vídeo 1: Gravação da verificação do Forward-From. (Fonte: Ana Rocha e Shaíne Oliveira, 2023).</p>
</div>

## Verificação

Com base nisso, foram criadas as Tabela 1 e 2 a seguir, que relaciona as especificações ideais do artefato, indica se o requisito é atendido ou não e avalia a qualidade de acordo com a classificação a seguir:

**Possui**

- Sim
- Não
- Incompleto

**Qualidade**

- Ótimo (Atende todos os requisitos do conteúdo esperado)
- Bom (Atende parcialmente os requisitos do conteúdo esperado)
- Pode melhorar (Não atende os requisitos do conteúdo esperado)

A Tabela 1 contém perguntas no que diz respeito à formatação do artefato. <a id="Tabela1"></a>

| ID  | Descrição do Critério                                                                        | Possui | Qualidade     | Observação                                      |
| --- | -------------------------------------------------------------------------------------------- | ------ | ------------- | ----------------------------------------------- |
| 1   | O artefato possui introdução?  | Sim    | Ótimo |  |
| 2   | Todas as tabelas e imagens do artefato possuem legendas, fontes e são introduzidas no texto? |  Sim  |    Ótimo     |    |
| 3   | Possui links para os outros artefatos, caso necessário? | Incompleto  | Bom | Colocar o link para o gitpages e não para o github |
| 4   | O artefato possui bibliografia/referências bibliográficas?    | Sim  |  Bom   | Poderia ter colocado o link de acesso das referências  |
| 5   | O artefato possui histórico de versões? |  Sim   |    Ótimo  |   |
| 6   | O artefato possui autor? | Sim   |    Ótimo     |     |                                            |
| 7   | O artefato possui revisor?  |  Sim  |  Bom  | Até a data em que a verificação foi feita a última versão do artefato não havia sido revisada   |

<div style="text-align: center;">
    Tabela 1: Perguntas selecionadas: Formatação do artefato. (Fonte: Ana Caroline e Shaíne Oliveira, 2023)
</div>

A Tabela 2 contém perguntas no que diz respeito ao conteúdo do artefato. <a id="Tabela2"></a>

| ID  | Descrição do Critério                                                            | Possui | Qualidade | Observação                                                                                               |
|----|-------------------------------------------------------------------------------------|--------|-----------|-----------------------------------------------------------------------------------------------------------|
| 1  |   Os requisitos estão devidamente identificados no artefato?  | Sim  |  Ótimo   |  |
| 2  |  Cada requisito no artefato possui uma descrição clara e concisa?  |  Sim   |     Ótimo      |   |
| 3  | No artefato, são citados quais requisitos estão implementados e quais não estão?  |  Sim  |   Ótimo |  |
| 4  | A rastreabilidade abrange todas as fases do ciclo de vida do projeto, desde a elicitação dos requisitos até a validação e a verificação?  |  Incompleto |  Bom   | Faltou alguns artefatos como: Backlog, NFR Framework e as técnicas de priorização |
| 5  | A rastreabilidade permite identificar os impactos de mudanças nos requisitos em outros componentes ou funcionalidades do sistema?   | Não   |  Pode melhorar   | Não foi feito o protótipo |

<div style="text-align: center;">
    Tabela 2: Perguntas selecionadas: Conteúdo do artefato. (Fonte: Ana Caroline e Shaíne Oliveira, 2023)
</div>

## Correções e ajustes sugeridos

O artefato foi analisado com atenção aos checklists apresentados, atendendo parte dos critérios. No entanto, recomenda-se realizar ajustes de acordo com as observações detalhadas nas tabelas específicas de cada ID abaixo.

#### Referentes a tabela 1:
- [ID3 - Possui links para os outros artefatos, caso necessário?](#Tabela1)
- [ID4 - O artefato possui bibliografia/referências bibliográficas? ](#Tabela1)
- [ID7 - O artefato possui revisor?](#Tabela1)

#### Referentes a tabela 2:
- [ID4 - A rastreabilidade abrange todas as fases do ciclo de vida do projeto, desde a elicitação dos requisitos até a validação e a verificação?](#Tabela2)
- [ID5 - A rastreabilidade permite identificar os impactos de mudanças nos requisitos em outros componentes ou funcionalidades do sistema?](#Tabela2)

## Bibliografia

> <a id="a" href="#aa">[1]</a> SALES, André Barros. Plano de ensino da disciplina. Disponível em: [Aprender 3](https://aprender3.unb.br/pluginfile.php/2692699/mod_resource/content/34/Plano_de_Ensino%20RE%20022023%20Turma%202.pdf). Acesso em 23 de novembro de 2023.

> <a id="b" href="#bb">[2]</a> Slides da aula “Requisitos – Aula 23” dos professores Milene Serrano e Maurício Serrano. Disponível em: [Aprender 3](https://aprender3.unb.br/pluginfile.php/2692856/mod_resource/content/2/Requisitos%20-%20Aula%20023.pdf). Acessado em: 23 de novembro de 2023.

> <a id="c" href="#cc">[3]</a> Forward-From do Grupo 6 da Disciplina de Requisitos. Disponível em: [Git Page](https://requisitos-de-software.github.io/2023.2-Skoob/pos_rastreabilidade/forward/). Acesso em 23 novembro de 2023.

## Histórico de Versão

| Versão | Data de execução | Data prevista de revisão |      Descrição     |          Autor(es)            |          Revisado            |
| :----: | :--------------: | :-------------: | :------------------------: | :------------------------: | :------------------: |
| `1.0`  |    23/11/2023    |   25/11/2023    | Criação do artefato |   [Ana Rocha](https://github.com/anaaroch) e [Shaíne Oliveira](https://github.com/ShaineOliveira_)    | <input type="checkbox" disabled checked /> |
| `1.1`  |    23/11/2023    |   25/11/2023    | Preenchimento do checklist |   [Ana Rocha](https://github.com/anaaroch) e [Shaíne Oliveira](https://github.com/ShaineOliveira_)    | <input type="checkbox" disabled checked /> |
| `1.2`  |    24/11/2023    |   25/11/2023    | Adicionando vídeo da inspeção |   [Ana Rocha](https://github.com/anaaroch) | <input type="checkbox" disabled checked /> |

### Revisão

| Data de Revisão | Cobertura de Versões  |          Técnica         |                  Revisor(es)                  |
| :------------: | :-------------: | :--------------------------: |  :----------------------------------------: |
|  xx/xx/xxxx   |    `1.0`    |    --   | [Rafael](https://github.com/Rafael-gc) |