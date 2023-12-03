# Verificação do artefato "[Backward-From](https://requisitos-de-software.github.io/2023.2-Skoob/pos_rastreabilidade/backward/)"

## Introdução

A análise de artefatos desempenha um papel fundamental na avaliação de documentos, projetos e produtos em diversas áreas, incluindo a Engenharia de Requisitos de Software. A abordagem de verificação de artefatos tem por objetivo realizar uma análise minuciosa do conteúdo, estrutura e atributos específicos de um artefato, com o propósito de avaliar sua qualidade, aderência aos requisitos e congruência com os objetivos previamente definidos.

Nesse contexto, o escopo de nossa pesquisa visa à aplicação da técnica de verificação de artefatos ao artefato de [Backward-From](https://requisitos-de-software.github.io/2023.2-Skoob/pos_rastreabilidade/backward/), em seu projeto no contexto do Skoob <a id="a" href="#aa">[3]</a>. Ressalta-se que a realização da verificação está estritamente alinhada com as diretrizes e datas estipuladas no [plano de ensino](https://aprender3.unb.br/pluginfile.php/2692699/mod_resource/content/34/Plano_de_Ensino%20RE%20022023%20Turma%202.pdf) <a id="a" href="#aa">[1]</a>.

Para melhor compreensão, é relevante salientar que a técnica de verificação, inspirada no processo de Fagan, abarca uma análise sistemática e rigorosa do artefato em busca de possíveis erros, inconsistências, omissões e desvios em relação aos requisitos. Essa etapa desempenha um papel crucial na garantia da qualidade e na precisão do artefato, assegurando sua conformidade com os objetivos estabelecidos no contexto do projeto ou documento em análise <a id="d" href="#dd">[4]</a>.

## Metodologia

A verificação, segundo o método de inspeção de Fagan, representa uma abordagem formal e estruturada para a revisão de documentos, cujo propósito é a identificação de falhas, erros e problemas nos artefatos, incluindo documentos, código-fonte, especificações e outros elementos correlacionados a projetos de desenvolvimento de software. O processo compreende etapas que envolvem planejamento, revisão geral, preparação, execução da inspeção, correções e acompanhamento <a id="b" href="#bb">[2]</a>. Além disso, a avaliação do artefato em questão também se baseará nos critérios de avaliação especificados no [plano de ensino](https://aprender3.unb.br/pluginfile.php/2692699/mod_resource/content/34/Plano_de_Ensino%20RE%20022023%20Turma%202.pdf). Para dar maior clareza à análise, implementamos um "conteúdo esperado", que compreende um checklist fundamentado nas questões previamente definidas no plano de ensino <a id="a" href="#aa">[1]</a>.

A inspeção de Fagan é ilustrada na Figura 1 apresentada abaixo, demonstrando as etapas envolvidas no processo.

<div style="text-align: center;">
    <img src="../../Fagan.png" alt="image" width="900"/>
</div>

<div style="text-align: center;">
    Figura 1: Método de Fagan: Inspeção. (Fonte: Slide “Requisitos – Aula 23” <a id="b" href="#bb">[2]</a>, 2023)
</div>

## Conteúdo esperado

Espera-se que o artefato apresente tabelas com os cronogramas planejados e executados ao longo do projeto, além de seguir a estrutura padrão básica exigida para todos os artefatos.

## Verificação

Com base nisso, foram criadas as Tabela 1 e 2 a seguir, que relaciona as especificações ideais do artefato, indica se o requisito é atendido ou não e avalia a qualidade de acordo com a classificação a seguir:

**Possui/Atende**

- Sim
- Não
- Incompleto

**Qualidade**

- Ótimo (Atende todos os requisitos do conteúdo esperado)
- Bom (Atende parcialmente os requisitos do conteúdo esperado)
- Pode melhorar (Não atende os requisitos do conteúdo esperado)

A Tabela 1 contém perguntas no que diz respeito à formatação do artefato. <a id="Tabela1"></a>

|    | Descrição do Critério | Possui | Qualidade | Observação |
|----|----------------------|---------------------------------|------------------------|----------|
| 1  | O artefato possui introdução?    | Sim | Ótimo  |  |
| 2  | Todas as tabelas e imagens do artefato possuem legendas, fontes e são introduzidas no texto? | Sim | Ótimo  |   |
| 3  | Possui links para os outros artefatos, caso necessário?                  | Sim | Ótimo  |  |
| 4  | O artefato possui bibliografia/referências bibliográficas?       | Sim | Ótimo  |  |
| 5  | As referências são citadas no texto?             | Sim | Ótimo  |  |
| 6  | O artefato possui um histórico de versões?        | Sim | Ótimo  |   |
| 7  | O artefato possui autor?     |Sim | Ótimo  |   |
| 8  | O artefato possui revisor?   |Sim | Ótimo  |   |
| 9  | O Histórico de versão está padronizado de acordo com as mudanças do artefato de [revisoes](../revisoes.md)? | Sim | Ótimo  |   |

<div style="text-align: center;">
    Tabela 1: Perguntas selecionadas: Formatação do artefato. (Fonte: Plano de ensino da disciplina <a id="a" href="#aa">[1]</a> e Yago Passos, 2023)
</div>

A Tabela 2 contém perguntas no que diz respeito ao conteúdo do artefato. <a id="Tabela2"></a>

|     | Descrição do Critério | Possui | Qualidade | Observação |
|-----|----------------------|---------------------------------|------------------------|----------|
| 1   | A metodologia de rastreabilidade "backward-from" está detalhada e compreensível?                      |  Sim | Ótimo  |   |
| 2   | Os quatro níveis e seis elos de rastreabilidade estão claramente apresentados?                       |  Sim | Ótimo  |   |
| 3   | Os elos entre os requisitos funcionais e não-funcionais estão corretamente identificados na Tabela 3? |  Sim | Ótimo  |  |
| 4   | Os tipos de elos (Satisfação, Recurso, Agregação) estão aplicados de acordo com a metodologia?        |  Sim | Ótimo  |   |

<div style="text-align: center;">
    Tabela 2: Perguntas selecionadas: Conteúdo do artefato. (Fonte: Plano de ensino da disciplina <a id="a" href="#aa">[1]</a> e Yago Passos, 2023)
</div>

## Correções e ajustes sugeridos

O artefato foi analisado com atenção aos checklists apresentados, atendendo todos critérios. Portanto, não há sugestões de ajuste ou melhora.

## Bibliografia

> <a id="a" href="#aa">[1]</a> SALES, André Barros. Plano de ensino da disciplina. Disponível em: <https://aprender3.unb.br/pluginfile.php/2692699/mod_resource/content/34/Plano_de_Ensino%20RE%20022023%20Turma%202.pdf>. Acesso em 8 de novembro de 2023.

> <a id="b" href="#bb">[2]</a> Slides da aula “Requisitos – Aula 23” dos professores Milene Serrano e Maurício Serrano. Disponível em: <https://aprender3.unb.br/pluginfile.php/2692856/mod_resource/content/2/Requisitos%20-%20Aula%20023.pdf>. Acessado em: 12 de novembro de 2023.

> <a id="c" href="#cc">[3]</a> Backward From do Grupo 6 da Disciplina de Requisitos. Disponível em: <https://requisitos-de-software.github.io/2023.2-Skoob/pos_rastreabilidade/backward/>. Acesso em 26 novembro de 2023.

> <a id="d" href="#dd">[4]</a> linhadecódigo, Técnicas de VV&T - Validação, Verificação e Teste. Dipsonível em: <http://www.linhadecodigo.com.br/artigo/492/tecnicas-de-vvampt-validacao-verificacao-e-teste.aspx/>. Acesso em 8 de novembro de 2023.

## Histórico de Versão

| Versão | Data de execução | Data prevista de revisão |             Descrição             |                      Autor(es)                       |                     Revisado                      |
| :----: | :--------------: | :-------------: | :-------------------------------: | :--------------------------------------------------: | :--------------------------------------------------: |
| `1.0`  |    26/11/2023    |   26/11/2023    | Elaboração do artefato |   [Yago Passos](https://github.com/yagompassos)   | <input type="checkbox" enabled checked /> |


### Revisão (V&V)

| Data de Revisão | Cobertura de Versões  |          Técnica         |                  Revisor(es)                  |
| :------------: | :-------------: | :--------------------------: |  :----------------------------------------: |
|   28/11/2023   |  `1.0`  |    [Revisão estática](https://requisitos-de-software.github.io/2023.2-Skoob/verificacao/revisoes/)   |  [Shaíne Oliveira](https://github.com/ShaineOliveira_) |
