# Léxicos

## Introdução
LAL é o termo usado para descrição de termos de forma ampliada da Linguagem <a id="a" href="#aa">[1]</a>. E é assim que a técnica de léxicos visa estabelecer uma linguagem comum entre os envolvidos no desenvolvimento do software, eliminando ambiguidades e garantindo uma compreensão unificada dos requisitos. Ela faz isso descrevendo símbolos de uma linguagem: o principal objetivo a ser perseguido pelos Engenheiros de Requisitos é identificar palavras ou frases específicas do meio social da aplicação que está sendo estudada <a id="a" href="#aa">[1]</a>.

## Metodologia
A técnica envolve a criação de um glossário que define os termos específicos relacionados ao domínio do problema. Esse glossário é formado por léxicos e dividido entre os tipos: **Verbo**, **Objeto** e **Estado**. Além disso, os Léxicos também serão compostos por: **Noção(ões)**, **Impacto(s)** e zero ou vários **Sinônimos**. A tabela 1 exemplifica como os léxicos serão descritos.

|      Nome       |   Autor   |        Noção         |              Impacto            |   Sinônimo(s)   | Classificação |
| :-------: | :-----: | :-----: | :-------: | :---------: | :---------: |
| Nome do Léxico 1 |  Nome do Autor |   Símbolos  |    Descrição do efeito    |   Sinônimo(s)   | Verbo/Objeto/Estado | 
| Nome do Léxico 2 |  Nome do Autor |   Símbolos  |    Descrição do efeito    |   Sinônimo(s)   | Verbo/Objeto/Estado | 
| Nome do Léxico 3 |  Nome do Autor |   Símbolos  |    Descrição do efeito    |   Sinônimo(s)   | Verbo/Objeto/Estado | 

<div style="text-align: center">
<p> Tabela 1: Exemplo de Léxico. (Fonte: Yago Passos, 2023).</p>
</div>

A construção de cada léxico foi possível a partir da análise dos requisitos elicitados na seção de [Elicitação](../elicitacao/requisitos).

## Descrição dos Léxicos
Abaixo, a Tabela 2 lista os léxicos de **estado**. Esses referem-se aos termos que descrevem as condições, estados ou propriedades do sistema ou dos elementos nele contidos.

|      Nome       |   Autor   |        Noção         |              Impacto            |   Sinônimo(s)   | Classificação |
| :-------: | :-----: | :-----: | :-------: | :---------: | :---------: |
| Lido |  Shaíne Oliveira |   Indica que um livro foi lido  |    Mostra as realizações do usuário    |   Concluído   | Estado | 
| Lendo |  Yago Passos |   Indica que um livro está sendo lido  |    Mostra as realizações do usuário    |   Em andamento   | Estado | 
| Quero ler |  Yago Passos |   Indica o desejo de ler um livro  |    Mostra as realizações do usuário    |   Meta   | Estado | 
| Relendo |  Yago Passos |   Indica que um livro está sendo lido novamente |    Mostra as realizações do usuário    |   Em andamento   | Estado | 
| Abandonei |  Yago Passos |   Indica que o usuário desistiu da leitura de um livro  |    Mostra as realizações do usuário    |   Desisti   | Estado |
| Usuário Online |  Shaíne Oliveira |   Indica que o usuário está logado em sua conta  |    Usuário tem acesso total ao aplicativo e suas funcionalidades    |   Ativo   | Estado |

<div style="text-align: center">
<p> Tabela 2: Glossário dos léxicos de estado. (Fonte: Yago Passos, 2023).</p>
</div>

Abaixo, a Tabela 3 lista os léxicos de **objeto**. Esses englobam os termos que representam os elementos tangíveis ou virtuais do sistema com os quais os usuários interagem

|      Nome       |   Autor   |        Noção         |              Impacto            |   Sinônimo(s)   | Classificação |
| :-------: | :-----: | :-----: | :-------: | :---------: | :---------: |
| Livro |  Shaíne Oliveira |   Principal objeto do aplicativo  |    Centro das atividades no Skoob   |   Obra, publicação  | Objeto |
| Usuário | Yago Passos |   Outros usuários do sistema  |    Interação entre usuários   |   Amigo, seguidor  | Objeto |
| Lista de desejados | Yago Passos |   Composta de livros que o usuário deseja fazer aquisição  |    Visualização e compartilhamento da lista com o intuito de indicar quais livros o usuário deseja ter posse   |  -  | Objeto |
| Estante | Ana Rocha |  Composta por livros adicionados pelo usuário  |    Controle e visualização dos livros   |  -  | Objeto |
| Autor | Ana Rocha |   Autores de livros  |    Acesso à informações sobre o autor e outros livros escritos pelo mesmo    |  Escritor  | Objeto |

<div style="text-align: center">
<p> Tabela 3: Glossário dos léxicos de objeto. (Fonte: Yago Passos, 2023).</p>
</div>

Abaixo, a Tabela 4 lista os léxicos de **verbo**. Esses consistem em palavras ou frases que descrevem ações que podem ser executadas pelos usuários ou pelo sistema.

|      Nome       |   Autor   |        Noção         |              Impacto            |   Sinônimo(s)   | Classificação |
| :-------: | :-----: | :-----: | :-------: | :---------: | :---------: |
| Pesquisar |  Shaíne Oliveira |   O usuário deseja encontrar livros, autores ou usuários  |    Facilita a descoberta de conteúdo no app    |   Buscar   | Verbo | 
| Definir status do livro |  Ana Rocha |   O usuário etiqueta um livro   |    Permite que outras ações sejam executadas dependendo do status do livro   |   Etiquetar   | Verbo | 
| Atribuir nota |  Yago Passos |   O usuário avalia um livro com o status "lido"  |    Permite que outros usuário vejam a nota do livro    |  Avaliar   | Verbo | 
| Escrever resenha |  Yago Passos |   O usuário escreve uma resenha sobre um livro com o status "lido"  |    Permite que outros usuário vejam a resenha do livro    |   Resenhar   | Verbo | 
| Adicionar amigos |  Yago Passos |   O usuário inicia uma amizade com outro usuário  |    Permite que ambos interajam, pelo feed e chat   |   -   | Verbo | 
| Registrar histórico de leitura |  Ana Rocha |   O usuário está lendo um livro e deseja registrar em que página do livro se encontra  |    Permite acompanhar o progresso de leitura    |   -   | Verbo | 

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

