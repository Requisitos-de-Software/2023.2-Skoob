# Verificação do artefato ["NFR"](https://requisitos-de-software.github.io/2023.2-DETRAN/entrega_4/NFR/)

## Introdução

A análise de artefatos desempenha um papel fundamental na avaliação de documentos, projetos e produtos em diversas áreas, incluindo a Engenharia de Requisitos de Software. A abordagem de verificação de artefatos tem por objetivo realizar uma análise minuciosa do conteúdo, estrutura e atributos específicos de um artefato, com o propósito de avaliar sua qualidade, aderência aos requisitos e congruência com os objetivos previamente definidos.

Nesse contexto, o escopo de nossa pesquisa visa à aplicação da técnica de verificação de artefatos ao artefato do [NFR](https://requisitos-de-software.github.io/2023.2-DETRAN/Entrega_1/Rich_picture/), desenvolvido pelo [Grupo 7](https://requisitos-de-software.github.io/2023.2-DETRAN/) em seu projeto no contexto do Detran <a id="a" href="#aa">[3]</a>. Ressalta-se que a realização da verificação está estritamente alinhada com as diretrizes e datas estipuladas no [plano de ensino](https://aprender3.unb.br/pluginfile.php/2692699/mod_resource/content/34/Plano_de_Ensino%20RE%20022023%20Turma%202.pdf) <a id="a" href="#aa">[1]</a>.

Para melhor compreensão, é relevante salientar que a técnica de verificação, inspirada no processo de Fagan, abarca uma análise sistemática e rigorosa do artefato em busca de possíveis erros, inconsistências, omissões e desvios em relação aos requisitos. Essa etapa desempenha um papel crucial na garantia da qualidade e na precisão do artefato, assegurando sua conformidade com os objetivos estabelecidos no contexto do projeto ou documento em análise <a id="d" href="#dd">[4]</a>.

## Metodologia

A verificação, segundo o método de inspeção de Fagan, representa uma abordagem formal e estruturada para a revisão de documentos, cujo propósito é a identificação de falhas, erros e problemas nos artefatos, incluindo documentos, código-fonte, especificações e outros elementos correlacionados a projetos de desenvolvimento de software. O processo compreende etapas que envolvem planejamento, revisão geral, preparação, execução da inspeção, correções e acompanhamento <a id="b" href="#bb">[2]</a>. Além disso, a avaliação do artefato em questão também se baseará nos critérios de avaliação especificados no [plano de ensino](https://aprender3.unb.br/pluginfile.php/2692699/mod_resource/content/34/Plano_de_Ensino%20RE%20022023%20Turma%202.pdf). Para dar maior clareza à análise, implementamos um "conteúdo esperado", que compreende um checklist fundamentado nas questões previamente definidas no plano de ensino <a id="a" href="#aa">[1]</a>.

A inspeção de Fagan é ilustrada na Figura 1 apresentada abaixo, demonstrando as etapas envolvidas no processo.

<div style="text-align: center;">
    <img src="../../Fagan.png" alt="image" width="900"/>
</div>s

<div style="text-align: center;">
    Figura 1: Método de Fagan: Inspeção. (Fonte: Slide “Requisitos – Aula 23” <a id="b" href="#bb">[2]</a>, 2023)
</div>

## Conteúdo esperado

Espera-se que no artefato estejam presentes as padronizações esperadas, metodologia explicada e conteúdo relevante sobre o tema da entrevista.

### Verificação

Sendo assim, foi elaborada a tabela 1 abaixo relacionando as especificações ideais do artefato, se ele possui ou não o requisito apresentado nas perguntas e quanto a qualidade, baseada na seguinte classificação:

**Possui/Atende**

- Sim
- Não
- Incompleto

**Qualidade**

- Ótimo (Apresenta todos os requisitos do conteúdo esperado)
- Bom (Apresenta parcialmente os requisitos do conteúdo esperado)
- Pode melhorar (Não apresenta os requisitos do conteúdo esperado)

<br>

| ID  | Conteúdo                                                                      | Possui/Atende     | Qualidade     | Observação            |
| --- | ----------------------------------------------------------------------------- | ---------- | ------------- | -------------------------------------------------- |
| 1   | Há histórico de versão padronizado?                                           | Sim        | Ótimo         |  -                                                 |
| 2   | Há autor e revisor no artefato?                                               | Incompleto | Pode Melhorar | Não há revisores.             |
| 3   | Existem referências bibliográficas?                                           | Sim        | Ótimo | -           |
| 4   | Possui hiperlinks para outros artefatos caso necessário?                      | Não        | Pode Melhorar        | O artefato é dependente dos requisitos elicitados, mas não há ligação com outros artefatos.   |
| 5   | As tabelas e imagens possuem legenda, fonte e são introduzidas no texto?      | Incompleto | Pode melhorar      | A maioria das imagens não são introduzidas no texto    |
| 6   | As referências bibliográficas estão citadas no texto?                         | Não        | Pode melhorar        | Não há nenhuma citação ou referência, no corpo do artefato, que remete ao que está listado na sua própria bibliografia. |
| 6   | Todas informações que o texto trás, citam e são referenciadas com alguma bibliografia?  | Sim  |  Ótimo  | O texto não trás novas informações que necessitariam de referência bibliográfica.|
| 7   | Existe uma metodologia definida no artefato?                 | Sim       | Bom | A metodologia poderia abrangir mais *como* um nfr é feito|
| 8   | Esá descrita a definição do RNF?                             | Sim        | Ótimo          |- |
| 9   | Existe o cartão de especificação do RNF?                     | Não        | Pode melhorar  | - |
| 10  | Os softgoals condizem com o contexto?                        | Sim        | Ótimo          |-|
| 11  | Softgoals representam metas bem definidas?                   | Sim        | Ótimo          |-|
| 12  | Os impactos foram corretamente propagados?                   | Sim        | Ótimo          |-|

<div style="text-align: center">
<p> Tabela 1: Checklist pro artefato do NFR Framework. (Fonte: Yago Passos, 2023).</p>
</div>

## Correções e ajustes sugeridos

No geral, o artefato está condizente com o conteudo, mas precisa de pequenos ajustes. O que o Grupo Skoob sugere:

- Sempre citar a referência bibliográfica no texto do corpo do artefato.
- Sempre introduzir tabelas, vídeos e outras estruturas gráficas no texto, antes do conteúdo.
- Ser mais detalhado e específico na metodologia, não resuma essa parte.
- Sempre buscar possíveis ligações que seu artefato tem com o outro, para manter o projeto *conversando* (Nesse caso: requisitos elicitados, especificação suplementar...).
- Apresentar os cartões de especialização.

## Bibliografia

> <a id="a" href="#aa">[1]</a> SALES, André Barros. Plano de ensino da disciplina. Disponível em: <https://aprender3.unb.br/pluginfile.php/2692699/mod_resource/content/34/Plano_de_Ensino%20RE%20022023%20Turma%202.pdf>. Acesso em 8 de novembro de 2023.

> <a id="b" href="#bb">[2]</a> Slides da aula “Requisitos – Aula 23” dos professores Milene Serrano e Maurício Serrano. Disponível em: <https://aprender3.unb.br/pluginfile.php/2692856/mod_resource/content/2/Requisitos%20-%20Aula%20023.pdf>. Acessado em: 12 de novembro de 2023.

> <a id="c" href="#cc">[3]</a> NFR Framework do Grupo 7 da Disciplina de Requisitos. Disponível em: <https://requisitos-de-software.github.io/2023.2-DETRAN/entrega_4/NFR/>. Acesso em 12 novembro de 2023.

> <a id="d" href="#dd">[4]</a> linhadecódigo, Técnicas de VV&T - Validação, Verificação e Teste. Dipsonível em: <http://www.linhadecodigo.com.br/artigo/492/tecnicas-de-vvampt-validacao-verificacao-e-teste.aspx/>. Acesso em 8 de novembro de 2023.

## Histórico de Versão

| Versão | Data de execução | Data prevista de revisão |      Descrição     |          Autor(es)            |          Revisado            |
| :----: | :--------------: | :-------------: | :------------------------: | :------------------------: | :------------------: |
| `1.0`  |    12/11/2023    |   10/11/2023    | Criação do artefato |   [Yago Passos](https://github.com/yagompassos)    |  |

### Revisão (V&V)

| Data de Revisão | Cobertura de Versões  |          Técnica         |                  Revisor(es)                  |
| :------------: | :-------------: | :--------------------------: |  :----------------------------------------: |
|   xx/xx/xxxx   |    `1.0`    |    -    | [Ana Rocha](https://github.com/anaaroch_) |