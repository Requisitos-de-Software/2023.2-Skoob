# Backward-From

## Introdução

A rastreabilidade "backward-from" é um conceito fundamental na engenharia de software e gerenciamento de requisitos, que se refere à capacidade de seguir o caminho inverso de um artefato ou item de software para identificar suas origens ou relacionamentos. Essa abordagem de rastreabilidade é especialmente valiosa em projetos de desenvolvimento de software, onde a compreensão da origem e do contexto de requisitos, componentes de software ou mudanças é crucial para garantir a qualidade, a manutenção eficiente e a conformidade com os objetivos do projeto. <a id="c" href="#cc">[3]</a>

Para a realização da técnica de backward-from, foi utilizado o modelo de Toranzo, onde as informações a serem rastreadas são classificadas em quatro níveis e seis elos de rastreabilidade. <a id="b" href="#bb">[2]</a>

## Metodologia

A metodologia de rastreabilidade "backward-from" compreende uma série de passos sistemáticos projetados para seguir o caminho inverso de um artefato específico no desenvolvimento de software.
Os níveis são: <a id="b" href="#bb">[2]</a>

- **Ambiental**: informações oriundas do contexto no qual a organização está inserida;
- **Organizacional**: informações pertecentes à organização;
- **Gerencial**: informações que auxiliam na gerencia do projeto;
- **Desenvolvimento**: informações associadas aos diversos artefatos gerados ao longo do processo de desenvolvimento.

Os principais elos de rastreabilidade são: <a id="b" href="#bb">[2]</a>

- **Satisfação**: classe origem tem dependência de satisfação com a classe destino;
- **Recurso**: classe origem tem dependência de recurso com a classe destino;
- **Responsabilidade**: registra a participação, responsabilidade e ação de pessoas sobre artefatos;
- **Representação**: captura a representação ou modelagem dos requisitos em outras linguagens;
- **Alocado**: classe origem está relacionada à classe destino, que representa um subsistema;
- **Agregação**: indica “composição” de elementos.

### Legendas:

- **RF** - [Requisito Funcional](./../elicitacao/requisitos.md)
- **RNF** - [Requisito Não-Funcional](./../elicitacao/requisitos.md)
- **OB** - [Observação](./../elicitacao/observacao.md)
- **IN** - [Introspecção](./../elicitacao/introspeccao.md)
- **BS** - [Brainstorming](./../elicitacao/brainstorming.md)

## Tabelas de requisitos funcionais

A Tabela 1 engloba todos os [Requisitos Funcionais Elicitados](./../elicitacao/requisitos.md): <a id="Tabela1"></a>

|   ID   | Descrição | Rastreabilidade | Implementado |
| :-----:| :-------: | :-------------: | :----------: |
|  RF01  | Deve ser possível realizar login | [OB01](./../elicitacao/observacao.md#requisitos-elicitados) | Sim |
|  RF02  | Deve ser possível pesquisar livros | [OB02](./../elicitacao/observacao.md#requisitos-elicitados) | Sim |
|  RF03  | Deve ser possível marcar os livros como: Lido / Lendo / Quero ler / Abandonei / Relendo | [OB03](./../elicitacao/observacao.md#requisitos-elicitados) | Sim |
|  RF04  | Deve existir uma timeline onde é possível ver atualizações literárias de outros usuários. | [OB04](./../elicitacao/observacao.md#requisitos-elicitados) | Sim |
|  RF05  | Deve ser possível adicionar comentários nos posts | [OB05](./../elicitacao/observacao.md#requisitos-elicitados) | Sim |
|  RF06  | Deve ser possível curtir posts da timeline | [OB06](./../elicitacao/observacao.md#requisitos-elicitados) | Sim |
|  RF07  | Deve ser possível realizar cadastro | [IN01](./../elicitacao/introspeccao.md#requisitos-elicitados) | Sim |
|  RF08  | Deve ser possível recuperar a senha | [IN02](./../elicitacao/introspeccao.md#requisitos-elicitados) | Sim |
|  RF09  | Deve ser possível cadastrar um livro | [IN03](./../elicitacao/introspeccao.md#requisitos-elicitados) | Sim |
|  RF10  | Deve ser possível escrever resenhas dos livros marcados como lidos | [IN04](./../elicitacao/introspeccao.md#requisitos-elicitados) | Sim |
|  RF11  | Deve ser possível dar notas aos livros lidos | [IN05](./../elicitacao/introspeccao.md#requisitos-elicitados) | Sim |
|  RF12  | Deve ser possível contabilizar os dias lendo livros quando o status for relendo | [IN06](./../elicitacao/introspeccao.md#requisitos-elicitados) | Não |
|  RF13  | Deve ser possível registrar o histórico de leitura | [IN07](./../elicitacao/introspeccao.md#requisitos-elicitados) | Sim |
|  RF14  | Deve ser possível adicionar livro a estante | [IN08](./../elicitacao/introspeccao.md#requisitos-elicitados) | Sim |
|  RF15  | Deve ser possível criar lista de livros desejados | [IN09](./../elicitacao/introspeccao.md#requisitos-elicitados) | Sim |
|  RF16  | Deve ser possível compartilhar a lista de livros desejados | [IN10](./../elicitacao/introspeccao.md#requisitos-elicitados) | Sim |
|  RF17  | Deve ser possível pesquisar outros usuários | [IN11](./../elicitacao/introspeccao.md#requisitos-elicitados) | Sim |
|  RF18  | Deve ser possível abrir e analisar o perfil de outros usuários | [IN12](./../elicitacao/introspeccao.md#requisitos-elicitados) | Sim |
|  RF19  | Deve ser possível adicionar outros usuários como amigo | [IN13](./../elicitacao/introspeccao.md#requisitos-elicitados) | Sim |
|  RF20  | Deve ser possível filtrar livros por nota | [IN14](./../elicitacao/introspeccao.md#requisitos-elicitados) | Não |
|  RF21  | Deve ser possível filtrar livros por categoria | [IN15](./../elicitacao/introspeccao.md#requisitos-elicitados) | Não |
|  RF22  | Deve ser possível criar uma meta de leitura para o ano | [BS01](./../elicitacao/brainstorming.md#Tabela2) | Sim |
|  RF23  | Deve ser possível sortear um livro cadastrado nas metas para o ano para a próxima leitura | [BS02](./../elicitacao/brainstorming.md#Tabela2) | Sim |
|  RF24  | Deve ser possível sortear um livro dentre os livros marcados como Quero ler para a próxima leitura do usuário | [BS03](./../elicitacao/brainstorming.md#Tabela2) | Não |
|  RF25  | Deve ser possível ver informações gerais de um livro cadastrado, como sinopse, autor, quantidade de páginas, etc | [BS04](./../elicitacao/brainstorming.md#Tabela2) | Sim |
|  RF26  | Deve existir uma aba de lançamentos de livros | [BS05](./../elicitacao/brainstorming.md#Tabela2) | Sim |
|  RF27  | Deve existir uma aba de notícias sobre editoras e autores | [BS06](./../elicitacao/brainstorming.md#Tabela2) | Não |
|  RF28  | Deve existir um FAQ para guiar os usuários nas funcionalidades | [BS07](./../elicitacao/brainstorming.md#Tabela2) | Não |
|  RF29  | Deve ser possível alterar o tema (escuro/claro/variantes) | [BS08](./../elicitacao/brainstorming.md#Tabela2) | Sim |
|  RF30  | Deve ser possível visualizar um ranking semanal/mensal de livros mais bem classificados | [BS09](./../elicitacao/brainstorming.md#Tabela2) | Não |
|  RF31  | Deve ser possível visualizar um ranking semanal/mensal de livros mais lidos | [BS10](./../elicitacao/brainstorming.md#Tabela2) | Não |
|  RF32  | Deve ser possível postar fotos e/ou vídeos em formato "stories" | [BS11](./../elicitacao/brainstorming.md#Tabela2) | Não |
|  RF33  | Deve ser possível compartilhar estantes | [BS12](./../elicitacao/brainstorming.md#Tabela2) | Não |
|  RF34  | Deve ser possível realizar desafios dentro da plataforma | [BS13](./../elicitacao/brainstorming.md#Tabela2) | Sim |
|  RF35  | Deve ser possível criar desafios entre amigos | [BS14](./../elicitacao/brainstorming.md#Tabela2) | Não |
|  RF36  | Deve ser possível mandar mensagens diretas entre usuários | [BS15](./../elicitacao/brainstorming.md#Tabela2) | Sim |
|  RF37  | Deve ser possível conquistar prêmios e recompensas a partir de desafios | [BS16](./../elicitacao/brainstorming.md#Tabela2) | Não |
|  RF38  | Deve ser possível expor prêmios nos perfis e na timeLine | [BS17](./../elicitacao/brainstorming.md#Tabela2) | Não |
|  RF39  | Deve ser possível receber recomendações de livros com base nas preferências literárias dos usuários | [BS18](./../elicitacao/brainstorming.md#Tabela2) | Não |

<div style="text-align: center;">
    Tabela 1: Requisitos Funcionais Elicitados. (Autor: Ana Rocha, 2023)
</div>

## Tabelas de requisitos não-funcionais

A Tabela 2 engloba todos os [Requisitos Não-Funcionais Elicitados](./../elicitacao/requisitos.md): <a id="Tabela2"></a>

|    ID   | Descrição | Rastreabilidade | Implementado |
| :------:| :-------: | :-------------: | :----------: |
|  RNF01  | A senha deve conter no mínimo um número uma letra maiúscula e um caracter especial | [IN16](./../elicitacao/introspeccao.md#requisitos-elicitados)  | Não |
|  RNF02  | Deve ser possível fazer cadastro/login com as credenciais do facebook | [IN17](./../elicitacao/introspeccao.md#requisitos-elicitados) | Sim |
|  RNF03  | Deve ser possível obter o aplicativo em qualquer sistema operacional | [IN18](./../elicitacao/introspeccao.md#requisitos-elicitados) | Sim |
|  RNF04  | Os dados do usuário devem ser guardados de forma eficaz, impendindo o vazamento dos mesmos | [IN19](./../elicitacao/introspeccao.md#requisitos-elicitados) | Sim |
|  RNF05  | O Skoob deve ser capaz de se adaptar a diferentes tamanhos de tela e resoluções | [IN20](./../elicitacao/introspeccao.md#requisitos-elicitados) | Sim |
|  RNF06  | O Skoob deve ser capaz de interoperar com outras plataformas de redes sociais, permitindo aos usuários compartilhar conteúdo | [BS19](./../elicitacao/brainstorming.md#Tabela2) | Sim |

<div style="text-align: center;">
    Tabela 2: Requisitos Não-Funcionais Elicitados. (Autor: Ana Rocha, 2023)
</div>

## Elos

Conforme mencionado na metodologia, a classificação dos requisitos será conduzida com base nos meios e tipos de elos. No entanto, uma análise realizada pelos responsáveis pelo artefato revelou que todos os requisitos elicitados pertencem à categoria "Desenvolvimento", sendo originados dos artefatos produzidos durante o processo de desenvolvimento do projeto, nenhum deles está associado à estrutura organizacional ou às práticas de gestão do projeto. Adicionalmente, iremos nos concentrar em três tipos específicos de elos de rastreabilidade: Satisfação, Recurso e Agregação.

Os requisitos funcionais listados na [Tabela 1](#Tabela1), com exceção de [OB01](./../elicitacao/observacao.md#requisitos-elicitados), [IN01](./../elicitacao/introspeccao.md#requisitos-elicitados) e [IN02](./../elicitacao/introspeccao.md#requisitos-elicitados), estabelecem um elo de rastreabilidade do tipo "Recurso" em relação ao requisito funcional [OB01](./../elicitacao/observacao.md#requisitos-elicitados), que diz respeito à capacidade de realizar login. Adicionalmente, os requisitos não-funcionais [IN19](./../elicitacao/introspeccao.md#requisitos-elicitados) e [BS19](./../elicitacao/brainstorming.md#Tabela2), listados na [Tabela 2](#Tabela2), também mantêm uma dependência com o requisito funcional [OB01](./../elicitacao/observacao.md#requisitos-elicitados), indicando a presença do mesmo tipo de elo entre eles.

Além disso, o requisito funcional [BS07](./../elicitacao/brainstorming.md#Tabela2), que aborda a implementação de um FAQ para orientar os usuários nas funcionalidades, estabelece um elo de Agregação com todos os requisitos funcionais da [Tabela 1](#Tabela1), exceto ele mesmo. Portanto, podemos descrever que [BS07](./../elicitacao/brainstorming.md#Tabela2) agrega [todas as demais funcionalidades](#Tabela1).

A Tabela 3 evidencia os outros elos entre os requisitos apresentados nas tabelas anteriores:

| ID | Requisito | Tipo de Elo |
| :--: | :---------: | :-----------: |
| ELO01 | RF01 / OB01 | **Recurso:** [OB01](./../elicitacao/observacao.md#requisitos-elicitados) depende de [IN01](./../elicitacao/introspeccao.md#requisitos-elicitados) |
| ELO02 | RF02 / OB02| **Satisfação:** [OB02](./../elicitacao/observacao.md#requisitos-elicitados) satisfaz [BS04](./../elicitacao/brainstorming.md#Tabela2) </br> **Recurso:** [OB02](./../elicitacao/observacao.md#requisitos-elicitados) depende de [IN03](./../elicitacao/introspeccao.md#requisitos-elicitados) |
| ELO03 | RF03 / OB03 | **Satisfação:** [OB03](./../elicitacao/observacao.md#requisitos-elicitados) satisfaz [IN08](./../elicitacao/introspeccao.md#requisitos-elicitados) |
| ELO04 | RF04 / OB04 | **Satisfação:** [OB04](./../elicitacao/observacao.md#requisitos-elicitados) satisfaz [BS04](./../elicitacao/brainstorming.md#Tabela2)  |
| ELO05 | RF05 / OB05 | **Recurso:** [OB05](./../elicitacao/observacao.md#requisitos-elicitados) depende de [OB04](./../elicitacao/observacao.md#requisitos-elicitados), </br> [OB05](./../elicitacao/observacao.md#requisitos-elicitados) depende de [IN12](./../elicitacao/introspeccao.md#requisitos-elicitados) |
| ELO06 | RF06 / OB06 | **Recurso:** [OB06](./../elicitacao/observacao.md#requisitos-elicitados) depende de [OB04](./../elicitacao/observacao.md#requisitos-elicitados), </br> [OB06](./../elicitacao/observacao.md#requisitos-elicitados) depende de [IN12](./../elicitacao/introspeccao.md#requisitos-elicitados) |
| ELO07 | RF07 / IN01 | **Recurso:** [IN01](./../elicitacao/introspeccao.md#requisitos-elicitados) depende de [IN16](./../elicitacao/introspeccao.md#requisitos-elicitados) |
| ELO08 | RF08 / IN02 | **Recurso:** [IN02](./../elicitacao/introspeccao.md#requisitos-elicitados) depende de [IN16](./../elicitacao/introspeccao.md#requisitos-elicitados) |
| ELO09 | RF10 / IN04 | **Recurso:** [IN04](./../elicitacao/introspeccao.md#requisitos-elicitados) depende de [OB03](./../elicitacao/observacao.md#requisitos-elicitados) </br> **Agregação:** [IN04](./../elicitacao/introspeccao.md#requisitos-elicitados) agrega [OB04](./../elicitacao/observacao.md#requisitos-elicitados) |
| ELO10 | RF11 / IN05 | **Recurso:** [IN05](./../elicitacao/introspeccao.md#requisitos-elicitados) depende de [OB03](./../elicitacao/observacao.md#requisitos-elicitados) </br> **Agregação:** [IN05](./../elicitacao/introspeccao.md#requisitos-elicitados) agrega [OB04](./../elicitacao/observacao.md#requisitos-elicitados), </br> [IN05](./../elicitacao/introspeccao.md#requisitos-elicitados) agrega [BS18](./../elicitacao/brainstorming.md#Tabela2)|
| ELO11 | RF12 / IN06 | **Recurso:** [IN06](./../elicitacao/introspeccao.md#requisitos-elicitados) depende de [OB03](./../elicitacao/observacao.md#requisitos-elicitados), </br> [IN06](./../elicitacao/introspeccao.md#requisitos-elicitados) depende de [IN07](./../elicitacao/introspeccao.md#requisitos-elicitados) |
| ELO12 | RF13 / IN07 | **Recurso:** [IN07](./../elicitacao/introspeccao.md#requisitos-elicitados) depende de [OB03](./../elicitacao/observacao.md#requisitos-elicitados) </br> **Agregação:** [IN07](./../elicitacao/introspeccao.md#requisitos-elicitados) agrega [OB04](./../elicitacao/observacao.md#requisitos-elicitados)|
| ELO13 | RF14 / IN08 | **Recurso:** [IN08](./../elicitacao/introspeccao.md#requisitos-elicitados) depende de [OB02](./../elicitacao/observacao.md#requisitos-elicitados) </br> **Agregação:** [IN08](./../elicitacao/introspeccao.md#requisitos-elicitados) agrega [BS18](./../elicitacao/brainstorming.md#Tabela2) |
| ELO14 | RF15 / IN09 | **Agregação:** [IN09](./../elicitacao/introspeccao.md#requisitos-elicitados) agrega [IN08](./../elicitacao/introspeccao.md#requisitos-elicitados), </br> [IN09](./../elicitacao/introspeccao.md#requisitos-elicitados) agrega [BS18](./../elicitacao/brainstorming.md#Tabela2) |
| ELO15 | RF16 / IN10 | **Recurso:** [IN10](./../elicitacao/introspeccao.md#requisitos-elicitados) depende de [IN09](./../elicitacao/introspeccao.md#requisitos-elicitados), </br> [IN10](./../elicitacao/introspeccao.md#requisitos-elicitados) depende de [BS19](./../elicitacao/brainstorming.md#Tabela2) | 
| ELO16 | RF18 / IN12 | **Recurso:** [IN12](./../elicitacao/introspeccao.md#requisitos-elicitados) depende de [IN11](./../elicitacao/introspeccao.md#requisitos-elicitados) </br> **Agregação:** [IN12](./../elicitacao/introspeccao.md#requisitos-elicitados) agrega [BS04](./../elicitacao/brainstorming.md#Tabela2) |
| ELO17 | RF19 / IN13 | **Recurso:** [IN13](./../elicitacao/introspeccao.md#requisitos-elicitados) depende de [IN12](./../elicitacao/introspeccao.md#requisitos-elicitados) |
| ELO18 | RF20 / IN14 | **Agregação:** [IN14](./../elicitacao/introspeccao.md#requisitos-elicitados) agrega [OB02](./../elicitacao/observacao.md#requisitos-elicitados) |
| ELO19 | RF21 / IN15 | **Agregação:** [IN15](./../elicitacao/introspeccao.md#requisitos-elicitados) agrega [OB02](./../elicitacao/observacao.md#requisitos-elicitados) |
| ELO20 | RNF02 / IN17 | **Satisfação:** [IN17](./../elicitacao/introspeccao.md#requisitos-elicitados) satisfaz [OB01](./../elicitacao/observacao.md#requisitos-elicitados), </br> [IN17](./../elicitacao/introspeccao.md#requisitos-elicitados) satisfaz [IN01](./../elicitacao/introspeccao.md#requisitos-elicitados) |
| ELO21 | RF22 / BS01 | **Agregação:** [BS01](./../elicitacao/brainstorming.md#Tabela2) agrega [IN08](./../elicitacao/introspeccao.md#requisitos-elicitados) |
| ELO22 | RF23 / BS02 | **Recurso:** [BS02](./../elicitacao/brainstorming.md#Tabela2) depende de [BS01](./../elicitacao/brainstorming.md#Tabela2) |
| ELO23 | RF24 / BS03 | **Recurso:** [BS03](./../elicitacao/brainstorming.md#Tabela2) depende de [OB03](./../elicitacao/observacao.md#requisitos-elicitados) |
| ELO24 | RF26 / BS05 | **Satisfação:** [BS05](./../elicitacao/brainstorming.md#Tabela2) satisfaz [BS04](./../elicitacao/brainstorming.md#Tabela2) |
| ELO25 | RF30 / BS09 | **Satisfação:** [BS09](./../elicitacao/brainstorming.md#Tabela2) satisfaz [BS04](./../elicitacao/brainstorming.md#Tabela2) |
| ELO26 | RF31 / BS10 | **Satisfação:** [BS10](./../elicitacao/brainstorming.md#Tabela2) satisfaz [BS04](./../elicitacao/brainstorming.md#Tabela2) |
| ELO27 | RF32 / BS11 | **Recurso:** [BS11](./../elicitacao/brainstorming.md#Tabela2) depende de [IN20](./../elicitacao/introspeccao.md#requisitos-elicitados) |
| ELO28 | RF33 / BS12 | **Recurso:** [BS12](./../elicitacao/brainstorming.md#Tabela2) depende de [IN08](./../elicitacao/introspeccao.md#requisitos-elicitados), </br> [BS12](./../elicitacao/brainstorming.md#Tabela2) depende de [BS19](./../elicitacao/brainstorming.md#Tabela2) |
| ELO29 | RF34 / BS13 | **Recurso:** [BS13](./../elicitacao/brainstorming.md#Tabela2) depende de [IN07](./../elicitacao/introspeccao.md#requisitos-elicitados) |
| ELO30 | RF35 / BS14 | **Recurso:** [BS14](./../elicitacao/brainstorming.md#Tabela2) depende de [IN13](./../elicitacao/introspeccao.md#requisitos-elicitados) </br> **Agregação:** [BS14](./../elicitacao/brainstorming.md#Tabela2) agrega [BS13](./../elicitacao/brainstorming.md#Tabela2) |
| ELO31 | RF36 / BS15 | **Recurso:** [BS15](./../elicitacao/brainstorming.md#Tabela2) depende de [IN12](./../elicitacao/introspeccao.md#requisitos-elicitados) |
| ELO32 | RF37 / BS16 | **Recurso:** [BS16](./../elicitacao/brainstorming.md#Tabela2) depende de [BS13](./../elicitacao/brainstorming.md#Tabela2) |
| ELO33 | RF38 / BS17 | **Recurso:** [BS17](./../elicitacao/brainstorming.md#Tabela2) depende de [BS16](./../elicitacao/brainstorming.md#Tabela2) </br> **Agregação:** [BS17](./../elicitacao/brainstorming.md#Tabela2) agrega [OB04](./../elicitacao/observacao.md#requisitos-elicitados)|

<div style="text-align: center;">
    Tabela 3: Elos de rastreabilidade. (Autor: Ana Rocha, 2023)
</div>

## Conclusão

Em síntese, a aplicação da técnica de rastreabilidade "backward-from" no Skoob, utilizando o modelo de Toranzo, permitiu compreender as complexas interações entre os requisitos funcionais e não-funcionais. A análise dos elos identificados destacou a importância de recursos específicos para operações fundamentais, como o login, bem como a necessidade de orientação clara aos usuários por meio de um FAQ. 

## Bibliografia

<a id="aa" href="#a">[1]</a> POHL, Klaus e RUPP, Chris. Requirements Engineering Fundamentals. Disponível em: [Aprender 3](https://aprender3.unb.br/pluginfile.php/2692881/mod_resource/content/2/Rastreabilidade.pdf). Acesso em 16 nov. de 2023. </br>
<a id="bb" href="#b">[2]</a> SERRANO, Milene e Mauricio. Slide “Requisitos – Aula 26”. Disponível em: [Aprender 3](https://aprender3.unb.br/pluginfile.php/2692879/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf). Acesso em 16 nov. de 2023. </br>
<a id="cc" href="#c">[3]</a> SAYÃO, Miriam e LEITE, Julio. Monografia Rastreabilidade de Requisitos. Disponível em: [Aprender 3](https://aprender3.unb.br/pluginfile.php/2692882/mod_resource/content/3/05_20_sayao.pdf). Acesso em 16 nov. de 2023. </br>

## Histórico de Versão

| Versão | Data de execução | Data prevista de revisão |             Descrição             |                      Autor(es)                       |                     Revisado                      |
| :----: | :--------------: | :-------------: | :-------------------------------: | :--------------------------------------------------: | :--------------------------------------------------: |
| `1.0`  |    16/11/2023    |   17/11/2023    | Criação do artefato |    [Shaine](https://github.com/ShaineOliveira)   | <input type="checkbox" enabled checked /> |
| `1.1`  |    16/11/2023    |   17/11/2023    | Evolução do artefato |    [Ana Caroline](https://github.com/anaaroch)   | <input type="checkbox" enabled checked />  |



### Revisão (V&V)

| Data de Revisão | Cobertura de Versões  |          Técnica         |                  Revisor(es)                  |
| :------------: | :-------------: | :--------------------------: |  :----------------------------------------: |
|   16/11/2023   |   `1.0`     |   [Revisão estática](../verificacao/revisoes.md)    | [Ana Caroline](https://github.com/anaaroch)   |
|   20/11/2023   |   `1.1`     |   [Revisão estática](../verificacao/revisoes.md)    | [Shaíne](https://github.com/ShaineOliveira)   |
|   26/11/2023   |    Todas até a data desta revisão     |   [Revisão por inspeção](../verificacao/grupo6/backward_from_6.md.md)    | [Yago Passos](https://github.com/yagompassos)  |
