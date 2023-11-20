# Metodologia

## Introdução

A escolha da metodologia de desenvolvimento de software é um passo crítico. Cada metodologia tem suas próprias abordagens e práticas, e a escolha certa deve se basear nas necessidades do projeto e na equipe. Essa decisão afeta diretamente como a equipe trabalha, colabora e se adapta às mudanças durante o desenvolvimento. Portanto, a seleção da metodologia é um artefato crucial para o sucesso do projeto.

## Scrum Adaptado

Tendo tudo isso em vista, escolhemos adotar uma adaptação da metodologia Scrum. Essa metodologia se baseia em um conjunto de práticas eficazes para o desenvolvimento. Essa abordagem permite que nossa equipe conduza o projeto de forma ágil, sem a necessidade de dominar todas as etapas de uma só vez. Em vez disso, dividimos o projeto em ciclos chamados sprints. Cada sprint é composto por um conjunto de atividades que devem ser concluídas dentro de um prazo determinado. Essa estratégia nos permite ser flexíveis e ágeis nas entregas, adaptando-nos às mudanças à medida que surgem.

Ao adaptar o Scrum em nosso projeto, reconhecemos que, embora o Scrum seja uma metodologia valiosa, não há possibilidade de encaixar todas suas características com o projeto da matéria e, portanto, não o seguiremos rigidamente. Continuaremos a seguir os princípios fundamentais do Scrum, mas com a liberdade de ajustar as práticas e processos conforme necessário para atingir nossos objetivos de maneira eficaz e eficiente.

As principais características a serem seguidas viementemente são <a id="a" href="#aa">[1]</a>:

 - Divisão das entregas em Sprints;
 - Papéis de Scrum Master ([Jefferson França](https://github.com/Frans6)) e Product Owner ([Shaíne](https://github.com/ShaineOliveira));  
 - Descrição de um [Backlog]() do produto;
 - Utilização de ferramenta de quadro estilo Kanban;
 - Reuniões.

Contudo, os principais fundamentos e indicações que não serão implementadas no projeto <a id="a" href="#aa">[1]</a>:

 - Métricas de Scrum como tabela de conhecimento ou de satisfação.
 - Reuniões Diárias ou de modelo [_Stand-up_](https://blog.cronapp.io/stand-up-meeting-o-que-e-e-como-realizar-uma-daily-scrum/)

### Quadro Kanban
Do japonês, Kanban é literalmente traduzido como quadro de sinal ou sinal visual <a id="aa" href="#a">[2]</a>. Em engenharia de Software, Kanban é uma estratégia para otimizar o fluxo de valor para partes interessadas através de um processo que utiliza um sistema visual <a id="aa" href="#a">[3]</a>.

A imagem 1 contém informações do Quadro Kanban utilizado pelo grupo. A ferramenta utilizada para sua elaboração 
e o Trello, que está definida no artefato de [Ferramentas](/docs/planejamento/ferramentas.md)

![Imagem exemplo do Kanban](/docs/planejamento/img/kanban_exemplo.png)

## Políticas

### Política de _commits_
A criação deste método visa promover a padronização e rastreabilidade em nosso processo de desenvolvimento. Dessa forma, devem estar de acordo com o seguinte padrão:

```bash
git commit -m "Arquivo: Descrição inserida no histórico de versão"
```

Exemplo:
>
> O _commit_ referente a criação do arquivo `metodologias.md` pode ter a mensagem `metodologias: criação do documento`

</br>

## Conclusão 

A adaptação da metodologia Scrum para o nosso projeto é uma escolha estratégica que nos permite manter um equilíbrio entre estrutura e flexibilidade. Ao seguir os princípios fundamentais do Scrum e adaptá-los conforme necessário, nossa equipe está posicionada para alcançar os objetivos do projeto de maneira eficiente e eficaz. A implementação do quadro Kanban também nos proporciona uma visão clara do fluxo de trabalho e contribui para a organização e acompanhamento das atividades. Além disso, ao estabelecer políticas claras, como a de commits, garantimos uma padronização no registro de alterações, facilitando a rastreabilidade e o entendimento do histórico de versões. Com essas práticas e abordagens, estamos confiantes de que seremos capazes de enfrentar os desafios do projeto com agilidade, transparência e qualidade.

## Bibliografia

<a id="aa" href="#a">[1]</a> O QUE É O SCRUM E COMO COMEÇAR. Disponível em: <https://www.atlassian.com/br/agile/scrum>. Acesso em: 18 de Setembro de 2023.

<a id="aa" href="#a">[2]</a> O que é Kanban? Explicado para Iniciantes. Disponível em: <https://businessmap.io/pt/recursos-kanban/primeiros-passos/o-que-e-kanban>. Acesso em: 03 de outubro de 2023.

<a id="aa" href="#a">[3]</a> Wikipédia, Kanban. Disponível em: <https://pt.wikipedia.org/wiki/Kanban>. Acesso em: 03 de outubro de 2023.

## Histórico de Versão

| Versão | Data de execução | Data prevista de revisão |       Descrição      |         Autor(es)      |       Revisado          |
| :----: | :--------------: | :-------------: | :-----------------------: | :----------------: | :-----------: |
| `1.0`  |    18/09/2023    |   18/09/2023    | Criação do artefato | [Jefferson França](https://github.com/Frans6)  | <input type="checkbox" enabled checked /> |
| `1.1`  |    18/09/2023    |   18/09/2023    | Seção de Scrum Adaptado |  [Yago Passos](https://github.com/yagompassos) | <input type="checkbox" enabled checked /> |
| `1.2`  |    29/09/2023    |   03/10/2023    | Seção de Políticas | [Jefferson França](https://github.com/Frans6)  | <input type="checkbox" enabled checked /> |
| `1.3`  |    03/10/2023    |   04/10/2023    | Seção do Kanban |  [Yago Passos](https://github.com/yagompassos) | <input type="checkbox" enabled checked /> |
| `1.4`  |    17/10/2023    |   18/10/2023    | Seção de Conclusão |  [Yago Passos](https://github.com/yagompassos) | |

### Verificação

| Data de Revisão | Cobertura de Versões  |          Técnica         |     Revisor(es)    |
| :------------: | :-------------: | :--------------------------: |  :---------------: |
|   01/09/2023   |  `1.0` e `1.1`  |     [Revisão estática](../verificacao/revisoes.md)       | [Shaíne](https://github.com/ShaineOliveira) |
|   03/10/2023   |      `1.2`      |     [Revisão estática](../verificacao/revisoes.md)       | [Yago Passos](https://github.com/yagompassos) |
|   10/10/2023   |      `1.3`      |     [Revisão estática](../verificacao/revisoes.md)       | [Jefferson França](https://github.com/Frans6) |