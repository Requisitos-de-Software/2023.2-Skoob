# Léxicos

## Introdução
LAL é o termo usado para descrição de termos de forma ampliada da Linguagem <a id="a" href="#aa">[1]</a>. E é assim que a técnica de léxicos visa estabelecer uma linguagem comum entre os envolvidos no desenvolvimento do software, eliminando ambiguidades e garantindo uma compreensão unificada dos requisitos. Ela faz isso descrevendo símbolos de uma linguagem: o principal objetivo a ser perseguido pelos Engenheiros de Requisitos é identificar palavras ou frases específicas do meio social da aplicação que está sendo estudada <a id="a" href="#aa">[1]</a>.

## Metodologia
A técnica envolve a criação de um glossário que define os termos específicos relacionados ao domínio do problema. Esse glossário é formado por léxicos e dividido entre os tipos: **Verbo**, **Objeto** e **Estado**. Além disso, os Léxicos também serão compostos por: **Noção(ões)**, **Impacto(s)** e zero ou vários **Sinônimos**. A tabela 1 exemplifica como os léxicos serão descritos.

|      Nome       |         Noção         |              Impacto            |   Sinônimo(s)   | Classificação | Léxicos Relacionados | Principais Requisitos Relacionados |  Elaborado por: |
| :-------: | :-----: | :-----: | :-------: | :---------: | :---------: | :---------: | :---------: |
| Nome do Léxico 1 |   Símbolos  |    Descrição do efeito    |   Sinônimo(s)   | Verbo/Objeto/Estado | Códigos dos Léxicos | Códigos dos Requisitos | Nome do Autor |
| Nome do Léxico 2 |   Símbolos  |    Descrição do efeito    |   Sinônimo(s)   | Verbo/Objeto/Estado | Códigos dos Léxicos | Códigos dos Requisitos |Nome do Autor |
| Nome do Léxico 3 |   Símbolos  |    Descrição do efeito    |   Sinônimo(s)   | Verbo/Objeto/Estado |  Códigos dos Léxicos | Códigos dos Requisitos | Nome do Autor |

<div style="text-align: center">
<p> Tabela 1: Exemplo de Léxico. (Fonte: Yago Passos, 2023).</p>
</div>

A construção de cada léxico foi possível a partir da análise dos requisitos elicitados na seção de [Elicitação](../elicitacao/requisitos). O membro [Yago Passos](https://github.com/yagompassos), com auxílio da [Ana Rocha](https://github.com/anaaroch), adquiriram os léxicos feitos pelos membros da equipe na atividade proposta pelo professor para presença do dia 17/10. Então, reuniram-se e discutiram a elaboração dos glossários vistos a seguir.

## Descrição dos Léxicos
Abaixo, a Tabela 2 lista os léxicos de **estado**. Esses referem-se aos termos que descrevem as condições, estados ou propriedades do sistema ou dos elementos nele contidos.

|Código|  Nome       |        Noção         |              Impacto            |   Sinônimo(s)   | Classificação | Léxicos Relacionados | Principais Requisitos Relacionados |  Elaborado por: |
|:----:| :--------: | :-----: | :-------: | :---------: | :---------: |:----:| :---------: | :-----: |
| LE1 |  Lido     |    Indica que um livro foi lido  |    Mostra as realizações do usuário    |   Concluído   | Estado | LV2 , LO1 e LO4 | [OB03](..\elicitacao\requisitos.md) |Shaíne Oliveira |
| LE2 |  Lendo    |  Indica que um livro está sendo lido  |    Mostra as realizações do usuário    |   Em andamento   | Estado | LV2, LO1 e LO4  |[OB03](..\elicitacao\requisitos.md) |  Yago Passos |  
| LE3 |  Quero ler   |    Indica o desejo de ler um livro  |    Mostra as realizações do usuário    |   Meta   | Estado | LV2, LO1 e LO4 | [OB03](..\elicitacao\requisitos.md)| Yago Passos |
| LE4 |  Relendo    |    Indica que um livro está sendo lido novamente |    Mostra as realizações do usuário    |   Em andamento   | Estado | LV2, LO1 e LO4  | [OB03](..\elicitacao\requisitos.md) |  Yago Passos |
| LE5 |  Abandonei   |  Indica que o usuário desistiu da leitura de um livro  |    Mostra as realizações do usuário    |   Desisti   | Estado | LV2, LO1 e LO4  | [OB03](..\elicitacao\requisitos.md)| Yago Passos | 
| LE6 |  Usuário Online |   Indica que o usuário está logado em sua conta  |    Usuário tem acesso total ao aplicativo e suas funcionalidades    |   Ativo   | Estado | -  | - | Shaíne Oliveira | 

<div style="text-align: center">
<p> Tabela 2: Glossário dos léxicos de estado. (Fonte: Yago Passos, 2023).</p>
</div>

Abaixo, a Tabela 3 lista os léxicos de **objeto**. Esses englobam os termos que representam os elementos tangíveis ou virtuais do sistema com os quais os usuários interagem

|Código|  Nome     |      Noção       |   Impacto          |   Sinônimo(s)   | Classificação |  Léxicos Relacionados | Principais Requisitos Relacionados |  Elaborado por: |
|:----:|  :-----: | :-------: | :---------: | :---------: |:----:| :---------: | :-----: | :-----: |
|LO1| Livro |   Principal objeto do aplicativo  |  Centro das atividades no Skoob  |  Obra, publicação, revista, HQ, mangá, conto  | Objeto | LO4, LO5, LV1, LV2, LV4  | [OB02, BS02-BS05, IN03-IN10](..\elicitacao\requisitos.md) | Shaíne Oliveira | 
|LO2| Usuário |  Pessoa que utiliza o aplicativo. Leitores e Autores.  | Interações com funcionalidades da aplicação, interação entre usuários, possibilidade de se encontrar dentro da plataforma |  Leitor, amigo, seguidor  | Objeto | Todos | [Todos](..\elicitacao\requisitos.md)|  Yago Passos |
|LO3| Lista de desejados |   Composta de livros que o usuário deseja fazer aquisição  |  Visualização e compartilhamento da lista com o intuito de indicar quais livros o usuário deseja ter posse  |  -  | Objeto | LO1, LO2, LE3 | [IN09 E IN10](..\elicitacao\requisitos.md) | Yago Passos | 
|LO4| Estante |  Composta por livros adicionados pelo usuário  |    Controle e visualização dos livros   |  -  | Objeto | LO1, LO2, LV2 | [IN08 E BS12](..\elicitacao\requisitos.md) | Ana Rocha |
|LO5| Autor |  Autores de livros  |    Acesso à informações sobre o autor e outros livros escritos pelo mesmo    |  Escritor  | Objeto | LO1, LV1 | [BS04 E BS06](..\elicitacao\requisitos.md) | Ana Rocha |  

<div style="text-align: center">
<p> Tabela 3: Glossário dos léxicos de objeto. (Fonte: Yago Passos, 2023).</p>
</div>

Abaixo, a Tabela 4 lista os léxicos de **verbo**. Esses consistem em palavras ou frases que descrevem ações que podem ser executadas pelos usuários ou pelo sistema.

|Código|  Nome       |        Noção         |              Impacto            |   Sinônimo(s)   | Classificação | Léxicos Relacionados | Principais Requisitos Relacionados |  Elaborado por: |
|:----:| :--------: | :-----: | :-------: | :---------: | :---------: |:----:| :---------: | :-----: |
| LV1| Pesquisar |  O usuário deseja encontrar livros, autores ou usuários  |    Facilita a descoberta de conteúdo no app    |   Buscar   | Verbo | LO1, LO2, LO5 | [OB02 e IN11](..\elicitacao\requisitos.md)|  Shaíne Oliveira |
| LV2| Definir status do livro |  O usuário etiqueta um livro   |    Permite que outras ações sejam executadas dependendo do status do livro   |   Etiquetar   | Verbo | LE1, LE2, LE3, LE4, LE5 | [OB03 e BS03](..\elicitacao\requisitos.md) |  Ana Rocha | 
| LV3| Atribuir nota |   O usuário avalia um livro com o status "lido"  |    Permite que outros usuário vejam a nota do livro    |  Avaliar   | Verbo | LO1 e LE1 |[IN05 e IN14](..\elicitacao\requisitos.md)| Yago Passos | 
| LV4| Escrever resenha |   O usuário escreve uma resenha sobre um livro com o status "lido"  |    Permite que outros usuário vejam a resenha do livro    |   Resenhar   | Verbo | LO1 e LE1 | [IN04](..\elicitacao\requisitos.md) | Yago Passos |  
| LV5| Adicionar amigos |   O usuário inicia uma amizade com outro usuário  |    Permite que ambos interajam, pelo feed e chat   |   -   | Verbo | LO2 | [IN13](..\elicitacao\requisitos.md) | Yago Passos | 
| LV6| Registrar histórico de leitura |   O usuário está lendo um livro e deseja registrar em que página do livro se encontra  |    Permite acompanhar o progresso de leitura    |   -   | Verbo | LO1, LE2 e LE4| [IN06](..\elicitacao\requisitos.md)|  Ana Rocha |

<div style="text-align: center">
<p> Tabela 4: Glossário dos léxicos de verbo. (Fonte: Yago Passos, 2023).</p>
</div>

## Conclusão
O artefato apresentado destaca a importância da técnica de léxicos na engenharia de requisitos, onde a criação de um glossário com termos específicos relacionados ao domínio do problema ajuda a eliminar ambiguidades e promover uma compreensão unificada dos requisitos do sistema. A categorização dos léxicos em verbos, objetos e estados contribui para uma visão abrangente das ações, entidades e condições no contexto da aplicação, facilitando a comunicação entre os membros da equipe de desenvolvimento. Além disso, a precisão e organização na construção dos léxicos asseguram clareza e coerência no entendimento dos termos, evitando mal-entendidos e garantindo uma visão compartilhada do sistema e suas funcionalidades. Em última análise, a técnica de léxicos desempenha um papel crucial no sucesso do projeto de software, estabelecendo uma base sólida para o desenvolvimento eficaz e garantindo uma compreensão clara e unificada dos requisitos entre todos os envolvidos.

## Bibliografia

<a id="aa" href="#a">[1]</a> SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. Disponível em: [Requisitos - Aula 10](https://aprender3.unb.br/pluginfile.php/2692795/mod_resource/content/1/Aula%2010.pdf). Acesso em: 18 de outubro de 2023.

## Histórico de Versão

| Versão | Data de execução | Data de revisão |           Descrição          |                  Autor(es)                   |                Revisor(es)                  |
| :----: | :--------------: | :-------------: | :--------------------------: | :------------------------------------------: | :----------------------------------------: |
| `1.0`  |    18/10/2023    |   18/10/2023    |    Elaboração do Artefato    | [Yago Passos](https://github.com/yagompassos)| [Ana Rocha](https://github.com/anaaroch) |
| `1.1`  |    24/10/2023    |   24/10/2023    |    Criação dos Léxicos    | [Yago Passos](https://github.com/yagompassos) e [Ana Rocha](https://github.com/anaaroch) | [Shaíne Oliveira](https://github.com/ShaineOliveira) |
| `1.2`  |    24/10/2023    |   24/10/2023    |    Adicionada seção de conclusão    | [Rafael Amancio](https://github.com/yagompassos) | [Yago Passos](https://github.com/yagompassos) |
| `1.3`  |    26/10/2023    |   30/10/2023    |   Refatorando Léxicos e alterando léxico de usuários   | [Yago Passos](https://github.com/yagompassos) | [Rafael Amancio](https://github.com/yagompassos) | 


