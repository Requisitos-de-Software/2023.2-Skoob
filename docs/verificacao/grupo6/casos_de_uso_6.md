# Verificação do artefato "[Casos de Uso](https://requisitos-de-software.github.io/2023.2-Skoob/modelagem/casos_de_uso/)"

## Introdução

A análise de artefatos desempenha um papel fundamental na avaliação de documentos, projetos e produtos em diversas áreas, incluindo a Engenharia de Requisitos de Software. A abordagem de verificação de artefatos tem por objetivo realizar uma análise minuciosa do conteúdo, estrutura e atributos específicos de um artefato, com o propósito de avaliar sua qualidade, aderência aos requisitos e congruência com os objetivos previamente definidos.

Nesse contexto, o escopo de nossa pesquisa visa à aplicação da técnica de verificação de artefatos ao artefato de [Casos de Uso](https://requisitos-de-software.github.io/2023.2-Skoob/modelagem/casos_de_uso/), desenvolvido pela nossa equipe, [Grupo 6](https://requisitos-de-software.github.io/2023.2-Skoob/), em seu projeto no contexto do Skoob <a id="a" href="#aa">[3]</a>. Ressalta-se que a realização da verificação está estritamente alinhada com as diretrizes e datas estipuladas no [plano de ensino](https://aprender3.unb.br/pluginfile.php/2692699/mod_resource/content/34/Plano_de_Ensino%20RE%20022023%20Turma%202.pdf) <a id="a" href="#aa">[1]</a>.

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

| ID | Descrição do Critério | Possui | Qualidade | Observação |
|----|----------------------|---------------------------------|------------------------|----------|
| 1  | O artefato possui introdução? | Sim | Ótima  |  |
| 2  | Todas as tabelas e imagens do artefato possuem legendas, fontes e são introduzidas no texto? | Sim | Ótimo  |  |
| 3  | Possui links para os outros artefatos, caso necessário? | Não | Ótimo  | Não parece necessário.|
| 4  | O artefato possui bibliografia/referências bibliográficas? | Sim | Ótimo | |
| 5  | As referências são citadas no texto?             | Não | Pode melhorar  | O texto do corpo do artefato traz elementos da bibliografia mas não possui citação.  |
| 6  | O artefato possui um histórico de versões? | Sim | Bom  | Não está padronizado com as mudanças do artefato de [revisoes](../revisoes.md) |
| 7  | O artefato possui autor? | Sim |Ótimo  |  |
| 8  | O artefato possui revisor? |Sim |Ótimo  |  |
| 9  | O Histórico de versão está padronizado de acordo com as mudanças do artefato de [revisoes](../revisoes.md)? | Não | Pode Melhorar  |  |

<div style="text-align: center;">
    Tabela 1: Perguntas selecionadas: Formatação do artefato. (Fonte: Plano de ensino da disciplina <a id="a" href="#aa">[1]</a> e Yago Passos, 2023)
</div>

A Tabela 2 contém perguntas no que diz respeito ao conteúdo do artefato. <a id="Tabela2"></a>

| ID | Descrição do Critério | Possui | Qualidade | Observação |
|----|----------------------|---------------------------------|------------------------|----------|
| 1  | A modelagem de casos de uso cobre todas as principais funcionalidades e interações do sistema?   | Sim   | Bom | o nome Compartilhar atividades de leitura, do [UC04](../../modelagem/casos_de_uso.md) não parece descrever bem o que real representa o caso de uso.  |
| 2  | Existe limite do sistema?                           | Sim     | Ótimo |  |
| 3  | Os atores estão fora da fronteira do sistema?      | Sim    | Pode Melhorar | O sistema possui o limite, mas também está representado como um ator, fora do sistema. |
| 4  | O ator principal está do lado esquerdo do sistema? | Sim     | Ótimo   |   |
| 5  | Os casos de uso possuem rastreabilidade?          | Sim     | Bom   |  Só faltou colocar os links para melhor rastreabilidade |
| 6  | Os diagramas de caso de uso focam nos requisitos funcionais do sistema? | Sim  | Bom    | Comentar publicação não parece ser um requisito tão principal ou relevante para ser modelado.  |
| 7  | O artefato possui metodologia explicando como, quando, onde e quem desenvolveu os casos de uso? | Não | Pode Melhorar |  |
| 8  | O artefato explica ou linka a(s) ferramenta(s) utilizada(s) para a elaboração dos casos de uso? | Não | Pode Melhorar |  |

<div style="text-align: center;">
    Tabela 2: Perguntas selecionadas: Conteúdo do artefato. (Fonte: Plano de ensino da disciplina <a id="a" href="#aa">[1]</a> e Yago Passos, 2023)
</div>

## Correções e ajustes sugeridos

O artefato foi analisado com atenção aos checklists apresentados, atendendo a maioria dos critérios. No entanto, recomenda-se realizar ajustes de acordo com as observações detalhadas nas tabelas específicas abaixo.

Referentes à [Tabela 1](#Tabela1):

- Sempre utilizar as referências no texto, mostrando que a bibliografia foi usada.
- Padronizar o histórico de versionamento de acordo com [revisoes](../revisoes.md).

Referentes à [Tabela 2](#Tabela2):

- Rever o sistema como um ator fora do sistema em si no diagrama.
- Adicionar links dos requisitos para facilitar rastreabilidade e comunicação entre artefatos
- Modelar os requisitos mais importantes da plataforma (UC 01 a 04 são ótimos. Porém o UC05 parece irrelevante)
- Ser mais descritivo na elaboração do artefato e do seu conteúdo.
- Linkar o artefato de ferramentas, explicando o que foi utilizado para a elaboração do diagrama

## Bibliografia

> <a id="a" href="#aa">[1]</a> SALES, André Barros. Plano de ensino da disciplina. Disponível em: <https://aprender3.unb.br/pluginfile.php/2692699/mod_resource/content/34/Plano_de_Ensino%20RE%20022023%20Turma%202.pdf>. Acesso em 8 de novembro de 2023.

> <a id="b" href="#bb">[2]</a> Slides da aula “Requisitos – Aula 23” dos professores Milene Serrano e Maurício Serrano. Disponível em: <https://aprender3.unb.br/pluginfile.php/2692856/mod_resource/content/2/Requisitos%20-%20Aula%20023.pdf>. Acessado em: 12 de novembro de 2023.

> <a id="c" href="#cc">[3]</a> Casos de Uso do Grupo 6 da Disciplina de Requisitos. Disponível em: <https://requisitos-de-software.github.io/2023.2-Skoob/modelagem/casos_de_uso/>. Acesso em 26 novembro de 2023.

> <a id="d" href="#dd">[4]</a> linhadecódigo, Técnicas de VV&T - Validação, Verificação e Teste. Dipsonível em: <http://www.linhadecodigo.com.br/artigo/492/tecnicas-de-vvampt-validacao-verificacao-e-teste.aspx/>. Acesso em 8 de novembro de 2023.

## Histórico de Versão

| Versão | Data de execução | Data prevista de revisão |             Descrição             |                      Autor(es)                       |                     Revisado                      |
| :----: | :--------------: | :-------------: | :-------------------------------: | :--------------------------------------------------: | :--------------------------------------------------: |
| `1.0`  |    26/11/2023    |   26/11/2023    | Elaboração do artefato |   [Yago Passos](https://github.com/yagompassos)   | <input type="checkbox" enabled checked /> |


### Revisão (V&V)

| Data de Revisão | Cobertura de Versões  |          Técnica         |                  Revisor(es)                  |
| :------------: | :-------------: | :--------------------------: |  :----------------------------------------: |
|   dd/mm/aaaa   |  `1.0`  |    [Revisão estática](../verificacao/revisoes.md)   |  [Jefferson França](https://github.com/Frans6) |
