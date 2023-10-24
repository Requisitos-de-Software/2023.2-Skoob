# Casos de Uso

## Introdução

Diagramas de casos de uso descrevem o que o sistema faz do ponto de vista do usuário, destacando suas principais funcionalidades e como os usuários interagem com ele. Ele não entra em detalhes técnicos, concentrando-se nas ações do usuário. Esse artefato é frequentemente derivado da especificação de requisitos e pode servir como base para o documento de requisitos do sistema.

## Componentes e Símbolos

Utilizando o software de diagramação LucidChart, elaboramos os diagramas de casos de uso. Para uma melhor compreensão dos diagramas apresentados neste artefato, foi desenvolvida uma legenda, Figura 1, que esclarece o significado de cada elemento presente nos diagramas.

<p align="center">
  <img src="img/legenda.jpeg" alt="Legenda">
</p>
<div style="text-align: center">
<p>Figura 1 - Legenda diagramas. (Fonte: Jefferson França. 2023)</p>
</div>



### Atores

Em um diagrama de casos de uso, "atores" são entidades externas (como usuários ou sistemas) que interagem com o sistema para realizar ações específicas. Eles ajudam a identificar as interações essenciais entre o sistema e seu ambiente.

### Cenário

Em um diagrama de casos de uso, um "cenário" descreve uma sequência de eventos que ilustra como um ou mais casos de uso específicos são executados. Os cenários fornecem detalhes sobre como os atores interagem com o sistema e o que acontece em diferentes etapas de uma funcionalidade, ajudando a compreender o comportamento do sistema a partir da perspectiva do usuário.

No contexto de um diagrama de casos de uso, é essencial que todos os casos de uso descritos estejam incluídos nos cenários. Caso contrário, esses casos de uso serão considerados fora do escopo do sistema

### Comunicação

Em um diagrama de casos de uso, "comunicação" se refere à forma como os casos de uso interagem.

- "Extend" (estender) descreve cenários opcionais que ampliam um caso de uso base em circunstâncias específicas.
- "Include" (incluir) representa funcionalidades compartilhadas por vários casos de uso, evitando duplicação.
  
Essas relações ajudam a organizar e tornar os diagramas mais eficientes.

### Caso de Uso

Em um diagrama de casos de uso, um "caso de uso" representa uma funcionalidade ou interação específica que o sistema oferece aos usuários ou atores externos. Ele descreve o que o sistema faz, sem entrar em detalhes técnicos, e foca nas ações e interações que os atores têm com o sistema. Os casos de uso ajudam a definir os requisitos funcionais do sistema e a documentar as principais funcionalidades que o sistema deve suportar.

## Casos de Uso

<p align="center">
  <img src="img/casos_de_uso.png" alt="Casos de Uso">
</p>
<div style="text-align: center">
<p>Figura 2 - Diagrama de casos de uso. (Fonte: Jefferson França. 2023)</p>
</div>

### UC01. Adicionar livro à estante

| UC01 | Adicionar Livro à Estante |
| -: | :- |
| **Atores** | Usuário |
| **Frequência de uso** | Alta |
| **Descrição** | Este caso de uso representa a ação de um usuário adicionar um livro à sua estante pessoal no aplicativo Skoob. A estante é onde o usuário pode acompanhar seus livros lidos, em leitura e desejados. |
| **Requisitos** | Abrir ambiente de mídias |
| **Condição de entrada** | Pesquisar o livro desejado |
| **Fluxo principal** | <ol> <li> O usuário pesquisa um livro no aplicativo. <li> O usuário seleciona o livro desejado na lista de resultados de pesquisa. <li> O usuário define qual etiqueta ele vai atribuir ao livro. <li> O usuário escolhe uma etiqueta (por exemplo, "Lido", "Lendo", "Desejo Ler", etc.). <li> Dependendo da etiqueta escolhida, o sistema pode solicitar informações adicionais relacionadas a essa etiqueta. Por exemplo, se a etiqueta for "Lido", o sistema pode pedir uma avaliação ou uma resenha do livro. <li> O usuário fecha a aba de etiquetagem e o livro é adicionado à estante. </ol> |
| **Fluxos alternativos** | Não há |
| **Fluxos de exceção** | <b>Fluxo 1: O Usuário clicka em abrir uma mídia</b> <ol> <li> O sistema abre o gerenciado de arquivos do dispositivo <li> O gerenciador de arquivos navega entre as pastas mostrando mídias disponíveis <li> O usuário escolhe uma mídia <ul> <li> A mídia selecionada abre no aplicativo pausada por padrão </ul> </ol> <b> Fluxo 2: O usuário clicka em abrir um diretorio</b> <ol> <li> O sistema abre o gerenciado de arquivos do dispositivo <li> O gerenciador de arquivos navega mostrando as pastas disponíveis </ol> <b> Fluxo 3: O usuário abre uma stream</b> <ol> <li> O Sistema abre uma janela de configurações da stream <ul> <li> O usuários pode configurar a URL de stream <li>O usuário pode configurar o arquivo <li> O usuário pode configurar a qualidade da stream </ul> <li> O usuário da play na stream </ol> <b>Fluxo 4: O usuário clicka em abrir recentes</b> <ol> <li> O sistema mostra em uma menu de cascata as mídias recentes <li> O usuário escolhe a mídia <li> O sistema inicia a mídia </ol> <b> Fluxo 5: O usuário clicka em salvar uma playlist </b> <ol> <li> O sistema abre o gerenciado de arquivos do dispositivo <li> O gerenciador de arquivos navega entre as pastas disponíveis <li> O usuário escolhe a pasta <li> O usuário salva a playlist em formato de um arquivo </ol>|
| **Pós condições** | O usuário tem acesso a eventos de playback |
| **Data da criação** | 15/05/2023 |
| **Rastreabilidade** | ST01, ST02, ST03, ST12, ST13, INT03 |

<div style="text-align: center">
<p> Tabela 1: Especificação do caso de uso: Mídia. (Fonte: SANTOS, Mizael. 2023).</p>
</div>

## Bibliografia

<a id="aa" href="#a">[1]</a> IMAGEM. Disponível em: [Imagem](https://pt.wikipedia.org/wiki/Imagem). Acesso em: 05 de Setembro de 2023.

## Histórico de Versão

| Versão | Data de execução | Data de revisão |      Descrição      |                   Autor(es)                   |                  Revisor(es)                  |
| :----: | :--------------: | :-------------: | :-----------------: | :-------------------------------------------: | :-------------------------------------------: |
| `1.0`  |    23/10/2023    |   24/10/2023    | Criação do artefato | [Jefferson França](https://github.com/Frans6) | [Yago Passos](https://github.com/yagompassos) |

