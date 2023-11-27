# Verificação do artefato "[Three-Level Scale](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/three_level_scale/)"

## Introdução

A análise de artefatos desempenha um papel fundamental na avaliação de documentos, projetos e produtos em diversas áreas, incluindo a Engenharia de Requisitos de Software. A abordagem de verificação de artefatos tem por objetivo realizar uma análise minuciosa do conteúdo, estrutura e atributos específicos de um artefato, com o propósito de avaliar sua qualidade, aderência aos requisitos e congruência com os objetivos previamente definidos.

Nesse contexto, o escopo de nossa pesquisa visa à aplicação da técnica de verificação de artefatos ao artefato de [Three-Level Scale](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/three_level_scale/), desenvolvido pela nossa equipe, [Grupo 6](https://requisitos-de-software.github.io/2023.2-Skoob/), em seu projeto no contexto do Skoob <a id="a" href="#aa">[3]</a>. Ressalta-se que a realização da verificação está estritamente alinhada com as diretrizes e datas estipuladas no [plano de ensino](https://aprender3.unb.br/pluginfile.php/2692699/mod_resource/content/34/Plano_de_Ensino%20RE%20022023%20Turma%202.pdf) <a id="a" href="#aa">[1]</a>.

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
| 3  | Possui links para os outros artefatos, caso necessário? | Não | Pode melhorar  | Poderia ser linkado ao artefato de [requisitos elicitados](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/requisitos/) |
| 4  | O artefato possui bibliografia/referências bibliográficas? | Sim | Bom | Poderia ter mais referências. |
| 5  | As referências são citadas no texto?             | Não | Pode melhorar  | A introdução traz elementos da bibliografia mas não possui citação.  |
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
| 1  | O artefato explica como é feito a técnica de Three-Level Scaling? | Sim | Ótima  |  |
| 2  | É explicado como a equipe aplicou a técnica? | Sim | Ótimo  |  | 
| 3  | Há na metodologia data, hora e participantes que estiverem presentes na priorização? | Sim  | Bom  | Tiveram participantes que não estão listados. |
| 4  | Há gravação da técnica? | Sim | Bom  | As câmeras estão desligadas |
| 5  | Os resultados da técnica estão bem explicitados? | Sim  | Ótima  |  |
| 6  | Os três níveis de prioridade são claramente definidos e diferenciados? | SIm | Ótimo | | 
| 7  | Há envolvimento de usuário para a priorização? | Sim | Ótimo | | 

<div style="text-align: center;">
    Tabela 2: Perguntas selecionadas: Conteúdo do artefato. (Fonte: Plano de ensino da disciplina <a id="a" href="#aa">[1]</a> e Yago Passos, 2023)
</div>

## Correções e ajustes sugeridos

O artefato foi analisado com atenção aos checklists apresentados, atendendo a maioria dos critérios. No entanto, recomenda-se realizar ajustes de acordo com as observações detalhadas nas tabelas específicas abaixo.

Referentes à [Tabela 1](#Tabela1):

- Pode-se linkar o artefato com os de [Requisitos Elicitados](../../elicitacao/requisitos.md).
- Sempre utilizar as referências no texto, mostrando que a bibliografia foi usada.
- Procurar e utilizar outra(s) referência(s) bibliográfica(s) 
- Padronizar o histórico de versionamento de acordo com [revisoes](../revisoes.md).

Referentes à [Tabela 2](#Tabela2):

-  Incluir no Cronograma: todos os participantes da técnica.
- Ligar as câmeras na gravação da técnica

## Gravação da Verificação
Abaixo, o vídeo 1, da gravação da Verificação.

<iframe width="1000vw" height="650vh" src="https://youtube.com/embed/yuzum8OihKQ" title="Verificação" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe>

<div style="text-align: center">
<p> Vídeo 1: Verificação do Artefato. (Fonte: Yago Passos. 2023).</p>
</div>

## Bibliografia

> <a id="a" href="#aa">[1]</a> SALES, André Barros. Plano de ensino da disciplina. Disponível em: <https://aprender3.unb.br/pluginfile.php/2692699/mod_resource/content/34/Plano_de_Ensino%20RE%20022023%20Turma%202.pdf>. Acesso em 8 de novembro de 2023.

> <a id="b" href="#bb">[2]</a> Slides da aula “Requisitos – Aula 23” dos professores Milene Serrano e Maurício Serrano. Disponível em: <https://aprender3.unb.br/pluginfile.php/2692856/mod_resource/content/2/Requisitos%20-%20Aula%20023.pdf>. Acessado em: 12 de novembro de 2023.

> <a id="c" href="#cc">[3]</a> Three-Level Scale do Grupo 6 da Disciplina de Requisitos. Disponível em: <https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/three_level_scale/>. Acesso em 26 novembro de 2023.

> <a id="d" href="#dd">[4]</a> linhadecódigo, Técnicas de VV&T - Validação, Verificação e Teste. Dipsonível em: <http://www.linhadecodigo.com.br/artigo/492/tecnicas-de-vvampt-validacao-verificacao-e-teste.aspx/>. Acesso em 8 de novembro de 2023.

## Histórico de Versão

| Versão | Data de execução | Data prevista de revisão |             Descrição             |                      Autor(es)                       |                     Revisado                      |
| :----: | :--------------: | :-------------: | :-------------------------------: | :--------------------------------------------------: | :--------------------------------------------------: |
| `1.0`  |    26/11/2023    |   26/11/2023    | Elaboração do artefato |   [Yago Passos](https://github.com/yagompassos)   | <input type="checkbox" enabled checked /> |


### Revisão (V&V)

| Data de Revisão | Cobertura de Versões  |          Técnica         |                  Revisor(es)                  |
| :------------: | :-------------: | :--------------------------: |  :----------------------------------------: |
|   dd/mm/aaaa   |  `1.0`  |    [Revisão estática](../verificacao/revisoes.md)   |  [Jefferson França](https://github.com/Frans6) |
