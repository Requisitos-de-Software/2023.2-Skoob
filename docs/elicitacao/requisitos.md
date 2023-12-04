# Requisitos Elicitados
Na tabela 1 é possível identificar todos os requisitos elicitados e na legenda pode-se verificar a rastreabilidade:

### Legenda da tabela:
- RF - Requisito Funcional
- RNF - Requisito Não Funcional
- OB - [Observação](observacao.md)
- IN - [Introspecção](introspeccao.md)
- BS - [Brainstorming](brainstorming.md)
- ** - Requisito não implementado no Skoob

| Identificação |                                                     Descrição                                                  |  Tipo  |
| :-----------: | :------------------------------------------------------------------------------------------------------------: | :----: |
|     OB01    |                                         Deve ser possível realizar login                                         |   RF   |
|     OB02    |                                        Deve ser possível pesquisar livros                                        |   RF   |
|     OB03    |             Deve ser possível marcar os livros como: Lido / Lendo / Quero ler / Abandonei / Relendo              |   RF   |
|     OB04    |             Deve existir uma timeline onde é possível ver atualizações literárias de outros usuários.            |   RF   |
|     OB05    |                                Deve ser possível adicionar comentários nos posts                                 |   RF   |
|     OB06    |                                    Deve ser possível curtir posts da timeline                                    |   RF   |
|     IN01    |                                       Deve ser possível realizar cadastro                                        |   RF   |
|     IN02    |                                       Deve ser possível recuperar a senha                                        |   RF   |
|     IN03    |                                       Deve ser possível cadastrar um livro                                       |   RF   |
|     IN04    |                        Deve ser possível escrever resenhas dos livros marcados como lidos                        |   RF   |
|     IN05    |                                 Deve ser possível dar notas aos livros lidos                                     |   RF   |
|    * IN06 *   |                 Deve ser possível contabilizar os dias lendo livros quando o status for relendo                |   RF   |
|     IN07    |                               Deve ser possível registrar o histórico de leitura                                 |   RF   |
|     IN08    |                                   Deve ser possível adicionar livro a estante                                    |   RF   |
|     IN09    |                                Deve ser possível criar lista de livros desejados                                 |   RF   |
|     IN10    |                            Deve ser possível compartilhar a lista de livros desejados                            |   RF   |
|     IN11    |                                   Deve ser possível pesquisar outros usuários                                    |   RF   |
|     IN12    |                          Deve ser possível abrir e analisar o perfil de outros usuários                          |   RF   |
|     IN13    |                              Deve ser possível adicionar outros usuários como amigo                              |   RF   |
|    * IN14 *   |                                    Deve ser possível filtrar livros por nota                                   |   RF   |
|    * IN15 *   |                                     Deve ser possível filtrar livros por categoria                             |   RF   |
|    * IN16 *  |                A senha deve conter no mínimo um número uma letra maiúscula e um caracter especial               |   RNF  |
|     IN17    |                      Deve ser possível fazer cadastro/login com as credenciais do facebook                       |   RNF  |
|     IN18    |                       Deve ser possível obter o aplicativo em qualquer sistema operacional                       |   RNF  |
|     IN19    |                       Os dados do usuário devem ser guardados de forma eficaz, impendindo o vazamento dos mesmos  |   RNF  |
|     IN20    |              O Skoob deve ser capaz de se adaptar a diferentes tamanhos de tela e resoluções                       |   RNF  |
|     BS01    |                                Deve ser possível Criar uma meta de leitura para o ano                            |   RF   |
|     BS02    |            Deve ser possível sortear um livro cadastrado nas metas para o ano para a próxima leitura             |   RF   |
|    * BS03 *   |  Deve ser possível sortear um livro dentre os livros marcados como Quero ler para a próxima leitura do usuário |   RF   |
|     BS04    | Deve ser possível ver informações gerais de um livro cadastrado, como sinopse, autor, quantidade de páginas, etc |   RF   |
|     BS05    |                                  Deve existir uma aba de lançamentos de livros                                   |   RF   |
|    * BS06 *   |                            Deve existir uma aba de notícias sobre editoras e autores                           |   RF   |
|    * BS07 *   |                          Deve existir um FAQ para guiar os usuários nas funcionalidades                        |   RF   |
|     BS08    |                            Deve ser possível alterar o tema (escuro/claro/variantes)                             |   RF   |
|    * BS09 *   |             Deve ser possível visualizar um ranking semanal/mensal de livros mais bem classificados            |   RF   |
|    * BS10*   |                 Deve ser possível visualizar um ranking semanal/mensal de livros mais lidos                     |   RF   |
|    * BS11 *   |                         Deve ser possível postar fotos e/ou vídeos em formato "stories"                        |   RF   |
|    * BS12 *   |                                     Deve ser possível compartilhar estantes                                    |   RF   |
|     BS13    |                            Deve ser possível realizar desafios dentro da plataforma                              |   RF   |
|    * BS14 *   |                                  Deve ser possível criar desafios entre amigos                                 |   RF   |
|     BS15    |                          Deve ser possível mandar mensagens diretas entre usuários                               |   RF   |
|    * BS16 *   |                         Deve ser possível conquistar prêmios e recompensas a partir de Desafios                |   RF   |
|    * BS17 *   |                            Deve ser possível expor prêmios nos perfis e na TimeLine                            |   RF   |
|    * BS18 *   |   Deve ser possível receber recomendações de livros com base nas preferências literárias dos usuários          |   RF   |
|     BS19      |   O Skoob deve ser capaz de interoperar com outras plataformas de redes sociais, permitindo aos usuários compartilhar conteúdo.          |   RNF   |


<div style="text-align: center">
    <p> Tabela 1: Elicitação de Requisitos. (Fonte: Rafael e Shaíne, 2023).</p>
</div>

## Histórico de Versão

| Versão | Data de execução | Data prevista de revisão |      Descrição      |                   Autor(es)                   | Revisado |
| :----: | :--------------: | :----------------------: | :-----------------: | :-------------------------------------------: | :------: |
| `1.0`  |    18/10/2023    |   20/10/2023    | Criação do artefato | [Shaíne Oliveira](https://github.com/ShaineOliveira) e [Rafael Amancio](https://github.com/Rafael-gc) |    <input type="checkbox" enabled checked />      |
| `1.1`  |    20/10/2023    |   20/10/2023    | Adição de hiperlinks e nova classificação | [Shaíne Oliveira](https://github.com/ShaineOliveira) e [Rafael Amancio](https://github.com/Rafael-gc) |    <input type="checkbox" enabled checked />      |
| `1.2`  |    24/10/2023    |   25/10/2023    | Alterações na tabela | [Rafael Amancio](https://github.com/Rafael-gc) |    <input type="checkbox" enabled checked />      |
| `1.3`  |    03/12/2023    |        04/12/2023        | Adicionando tabela de revisão | [Ana Caroline](https://github.com/anaaroch) |    <input type="checkbox" disabled checked />      |

### Revisão

| Data de Revisão | Cobertura de Versões | Técnica |                 Revisor(es)                 |
| :-------------: | :------------------: | :-----: | :-----------------------------------------: |
|   20/10/2023    |        `1.0` e `1.1`         |    [Revisão estática](https://requisitos-de-software.github.io/2023.2-Skoob/verificacao/revisoes/)    | [Ana Rocha](https://github.com/anaaroch),  e [Yago Passos](https://github.com/yagompassos) |
|   22/11/2023    |        `1.2`         |    [Revisão por inspeção](https://requisitos-de-software.github.io/2023.2-Skoob/verificacao/revisoes/)    | [Shaíne Oliveira](https://github.com/ShaineOliveira) |