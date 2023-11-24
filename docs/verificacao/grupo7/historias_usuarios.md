# Verificação do artefato "[Historias De Usuarios](https://requisitos-de-software.github.io/2023.2-DETRAN/entrega_4/historias_de_usuarios/)"

## Introdução

A verificação de artefatos desempenha um papel crucial na avaliação de documentos, projetos ou produtos em diversas áreas, incluindo os Requisitos de Software. Essa técnica visa a análise minuciosa do conteúdo, estrutura e características específicas de um artefato, com o propósito de avaliar sua qualidade, conformidade com requisitos e adequação aos objetivos estabelecidos. 
Neste contexto, este documento tem como objetivo executar esse procedimento no artefato [Historias De Usuarios](https://requisitos-de-software.github.io/2023.2-DETRAN/entrega_4/historias_de_usuarios/) <a id="c" href="#cc">[3]</a> , desenvolvido pelo [Grupo 7](https://requisitos-de-software.github.io/2023.2-DETRAN/).

Em termos práticos, a técnica de verificação, inspirada no processo de Fagan, implica na análise rigorosa e sistemática do artefato em busca de erros, inconsistências, lacunas e desvios em relação aos requisitos. Essa etapa é fundamental para assegurar a qualidade e precisão do artefato, garantindo que este esteja alinhado com os objetivos do projeto ou documento em questão.

## Metodologia

A metodologia adotada para a verificação dos artefatos é composta por duas abordagens distintas, cada uma contribuindo para assegurar a qualidade e integridade do material analisado.

A primeira é fundamentada nos critérios de avaliação presentes no [plano de ensino](https://aprender3.unb.br/pluginfile.php/2692699/mod_resource/content/34/Plano_de_Ensino%20RE%20022023%20Turma%202.pdf) <a id="a" href="#aa">[1]</a> e nos [slides da aula 15](https://aprender3.unb.br/pluginfile.php/2692826/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf) <a id="d" href="#dd">[4]</a>,  fornecendo um direcionamento preciso para a avaliação do conteúdo esperado nos artefatos. Essa etapa se baseia em um checklist elaborado a partir da leitura do plano e dos slides, abrangendo questionamentos específicos sobre a construção de [Historias De Usuarios](https://requisitos-de-software.github.io/2023.2-DETRAN/entrega_4/historias_de_usuarios/) <a id="c" href="#cc">[3]</a>.

A segunda abordagem se apoia na técnica formal de inspeção de Fagan, um processo estruturado que visa identificar e corrigir possíveis erros, falhas e problemas nos artefatos analisados, abrangendo documentos, código-fonte, especificações, entre outros itens relacionados a projetos de desenvolvimento de software. Essa técnica proporciona uma revisão criteriosa e sistemática, contribuindo para a melhoria da qualidade e precisão dos artefatos <a id="b" href="#bb">[2]</a>. A inspeção de Fagan é ilustrada na Figura 1 apresentada abaixo, demonstrando as etapas envolvidas no processo.

<div style="text-align: center;">
    <img src="../../Fagan.png" alt="image" width="900"/>
</div>

<div style="text-align: center;">
    Figura 1: Método de Fagan: Inspeção. (Fonte: Slide “Requisitos – Aula 23” <a id="b" href="#bb">[2]</a>, 2023)
</div>

## Conteúdo esperado

É esperado que o artefato atenda aos critérios de identificação, detalhamento, rastreabilidade, entre outros, além de seguir a estrutura padrão básica exigida para todos os artefatos.

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

| ID | Descrição do Critério | Possui | Qualidade | Observação |
|----|----------------------|---------------------------------|------------------------|----------|
| 1  | O artefato possui introdução? | Sim | Ótimo |   |
| 2  | Todas as tabelas e imagens do artefato possuem legendas, fontes e são introduzidas no texto? | Não | Ótimo | O artefato não possui tabelas e imagens. |
| 3  | Possui links para os outros artefatos, caso necessário? | Sim | Bom | Algumas histórias de usuários estão associadas aos léxicos, mas há casos em que essa relação não é estabelecida, embora seja possível. Seria interessante manter um padrão. |
| 4  | O artefato possui bibliografia/referências bibliográficas? | Sim | Bom | A referência não inclui um link funcional de acesso. |
| 5  | O artefato possui um histórico de versões? | Sim | Ótimo | |
| 6  | O artefato possui autor? | Sim | Ótimo | |
| 7  | O artefato possui revisor? | Sim | Ótimo | |

<div style="text-align: center;">
    Tabela 1: Perguntas selecionadas: Formatação do artefato. (Fonte: Plano de ensino da disciplina <a id="a" href="#aa">[1]</a>, 2023)
</div>

A Tabela 2 contém perguntas no que diz respeito ao conteúdo do artefato. <a id="Tabela2"></a>

| ID | Descrição do Critério | Possui | Qualidade | Observação |
|----|-----------------------|--------|-----------|------------|
| 1  | Os títulos das histórias de usuário são auto-explicativos? | Sim | Ótimo |  |
| 2  | O “quem”, “o que” e o “por que” estão definidos nas histórias de usuário? | Sim | Ótimo |  |
| 3  | A participação do cliente e/ou persona na validação das histórias de usuário? | Incompleto | Pode melhorar | O processo de validação com o "usuário representativo", que acredito ser o uso de personas, não está registrado.  |
| 4  | As histórias possuem critérios de aceitação? | Sim | Ótimo |  |
| 5  | Todas as histórias de usuário podem ser testadas? | Sim | Ótimo |  |
| 6  | As Histórias de Usuário seguem algum modelo ou padrão?  | Sim | Ótimo |  |
| 7  | As histórias possuem identificação, descrição e rastreabilidade?  | Sim | Bom | A história de usuário US13, que aborda a "Recolocação de placa do veículo", está associada ao requisito ADD20, relacionado ao armazenamento de informações do usuário. Recomenda-se a correção dessa associação para o requisito ADD34, que trata da recolocação de placa. |

<div style="text-align: center;">
    Tabela 2: Perguntas selecionadas: Conteúdo do artefato. (Fonte: Plano de ensino da disciplina <a id="a" href="#aa">[1]</a>, Slide “Requisitos – Aula 15” <a id="d" href="#dd">[4]</a> e Ana Rocha, 2023)
</div>

## Correções e ajustes sugeridos

O artefato foi analisado com atenção aos checklists apresentados, atendendo a maioria dos critérios. No entanto, recomenda-se realizar ajustes de acordo com as observações detalhadas nas tabelas específicas de cada ID abaixo.

Referentes à [Tabela 1](#Tabela1):

- ID3: Possui links para os outros artefatos, caso necessário?
- ID4: O artefato possui bibliografia/referências bibliográficas?

Referentes à [Tabela 2](#Tabela2):

- ID3: A participação do cliente e/ou persona na validação das histórias de usuário?
- ID7: As histórias possuem identificação, descrição e rastreabilidade?

## Bibliografia

<a id="aa" href="#a">[1]</a> SALES, André Barros. Plano de ensino da disciplina. Disponível em: [Aprender 3](https://aprender3.unb.br/pluginfile.php/2692699/mod_resource/content/34/Plano_de_Ensino%20RE%20022023%20Turma%202.pdf). Acesso em 11 de novembro de 2023.</br>
<a id="bb" href="#b">[2]</a> SERRANO, Milene e Mauricio. Slide “Requisitos – Aula 23”. Disponível em: [Aprender 3](https://aprender3.unb.br/pluginfile.php/2692856/mod_resource/content/2/Requisitos%20-%20Aula%20023.pdf). Acesso 11 de novembro de 2023. </br>
<a id="cc" href="#c">[3]</a> GRUPO 7. Documento de Historias De Usuarios do Grupo 7 da Disciplina de Requisitos de Software. Disponível em: [Git Page](https://requisitos-de-software.github.io/2023.2-DETRAN/entrega_4/historias_de_usuarios/). Acesso em 11 novembro de 2023.</br>
<a id="dd" href="#d">[4]</a> SERRANO, Milene e Mauricio. Slide “Requisitos – Aula 15”. Disponível em: [Aprender 3](https://aprender3.unb.br/pluginfile.php/2692826/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf). Acesso em 11 novembro de 2023.</br>

## Histórico de Versão

| Versão | Data de execução | Data prevista de revisão |             Descrição             |                      Autor(es)                       |                     Revisado                      |
| :----: | :--------------: | :-------------: | :-------------------------------: | :--------------------------------------------------: | :--------------------------------------------------: |
| `1.0`  |    11/11/2023    |   13/11/2023    | Criação do artefato |   [Ana Rocha](https://github.com/anaaroch)    | <input type="checkbox" disabled checked /> |

<!-- Trocar o "disabled" do checkbox para "enabled" quando realizar a revisão -->

### Revisão (V&V)

| Data de Revisão | Cobertura de Versões  |          Técnica         |                  Revisor(es)                  |
| :------------: | :-------------: | :--------------------------: |  :----------------------------------------: |
|   xx/xx/xxxx   |    `1.0`    |    -    |  [Yago Passos](https://github.com/yagompassos) |