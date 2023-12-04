# Introspecção

## Introdução

A técnica de Introspecção consiste em imaginar o objetivo final do sistema, imaginando e documentando todas as funções que o sistema poderia realizar para ajudar a alcançar esse objetivo. Na prática, o engenheiro de requisitos deve imaginar quais seriam os requisitos, tanto funcionais quanto não funcionais, que o sistema deve possuir para que seja um sucesso e em seguida documentar esses requisitos. O documento de introspecção deverá servir como um guia para o desenvolvimento do software.


## Execução

O objetivo da técnica é conseguir imaginar e elicitar o máximo de requisitos referentes ao Escopo e a Profundidade da aplicação. Para isso, todos os integrantes do grupo se reuniram e conversaram sobre o que o sistema deveria fazer.

Por fim, foram atribuídos ID's únicos para cada requisito, funcional e não funcional, documentado na Tabela 1.

### Legenda da tabela:
    - INn: Requisito elicitado por meio de Introspecção;
    - n: Número do Requisito;
    - RF:  Requisito Funcional;
    - RNF: Requisito Não Funcional;

## Requisitos Elicitados


| Identificação |                                                     Descrição                                                    |      Tipo      |
| :-----------: | :--------------------------------------------------------------------------------------------------------------: | :------------: |
|     IN01      |                                       Deve ser possível realizar cadastro                                        |       RF       |
|     IN02      |                                       Deve ser possível recuperar a senha                                        |       RF       |
|     IN03      |                                       Deve ser possível cadastrar um livro                                       |       RF       |
|     IN04      |                        Deve ser possível escrever resenhas dos livros marcados como lidos                        |       RF       |
|     IN05      |                                 Deve ser possível dar notas aos livros lidos                                     |       RF       |
|     IN06      |                 Deve ser possível contabilizar os dias lendo livros quando o status for relendo                  |       RF       |
|     IN07      |                               Deve ser possível registrar o histórico de leitura                                 |       RF       |
|     IN08      |                                   Deve ser possível adicionar livro a estante                                    |       RF       |
|     IN09      |                                Deve ser possível criar lista de livros desejados                                 |       RF       |
|     IN10      |                            Deve ser possível compartilhar a lista de livros desejados                            |       RF       |
|     IN11      |                                   Deve ser possível pesquisar outros usuários                                    |       RF       |
|     IN12      |                          Deve ser possível abrir e analisar o perfil de outros usuários                          |       RF       |
|     IN13      |                              Deve ser possível adicionar outros usuários como amigo                              |       RF       |
|     IN14      |                                    Deve ser possível filtrar livros por nota                                     |       RF       |
|     IN15      |                                     Deve ser possível filtrar livros por categoria                                      |       RF       |
|     IN16      |                A senha deve conter no mínimo um número uma letra maiúscula e um caracter especial                |       RNF      |
|     IN17      |                      Deve ser possível fazer cadastro/login com as credenciais do facebook                       |       RNF      |
|     IN18      |                       Deve ser possível obter o aplicativo em qualquer sistema operacional                       |       RNF      |
|     IN19    |                       Os dados do usuário devem ser guardados de forma eficaz, impendindo o vazamento dos mesmos                       |   RNF  |
|     IN20    |           O Skoob deve ser capaz de se adaptar a diferentes tamanhos de tela e resoluções                        |     RNF  |

<div style="text-align: center">
<p> Tabela 1: Requisitos elicitados utilizando a técnica de Introspecção. (Fonte: Rafael Amancio, 2023).</p>
</div>

## Conclusão
Em resumo, essa técnica serviu de grande ajuda para o desenvolvimento inicial do projeto, gerando 15 requisitos funcionais e 3 não funcionais, totalizando 18 requisitos.

## Bibliografia

<a id="aa" href="#a">[1]</a> SALES, André Barros. Técnicas de Priorização. Disponível em: [Aprender 3](https://aprender3.unb.br/pluginfile.php/2692772/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf). Acesso em 04 de outubro de 2023.

## Histórico de Versão

| Versão | Data de execução | Data prevista de revisão |       Descrição      |         Autor(es)      |       Revisado          |
| :----: | :--------------: | :-------------: | :------------------------: | :----------------: | :-----------: |
| `1.0`  |    04/10/2023    |   04/10/2023    | Criação do artefato  | [Rafael Amancio](https://github.com/Rafael-gc) | <input type="checkbox" enabled checked />  |
| `1.1`  |    24/10/2023    |   25/10/2023    | Alterações na tabela | [Rafael Amancio](https://github.com/Rafael-gc) | <input type="checkbox" enabled checked />  |

### Revisão

| Data de Revisão | Cobertura de Versões  |          Técnica         |     Revisor(es)    |
| :------------: | :-------------: | :--------------------------: |  :---------------: |
|   27/10/2023   |    `1.1` e `1.2`   | [Revisão estática](https://requisitos-de-software.github.io/2023.2-Skoob/verificacao/revisoes/)     |  [Shaíne Oliveira](https://github.com/ShaineOliveira) |
|   26/11/2023   |  Todas até a data desta revisão  |    [Revisão por inspeção](../verificacao/grupo6/introspeccao_6.md)     | [Yago](https://github.com/yagompassos) |
