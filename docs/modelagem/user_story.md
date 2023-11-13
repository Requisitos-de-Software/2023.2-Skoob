# Histórias de Usuário

## Introdução

As histórias de usuário desempenham um papel fundamental na metodologia ágil de desenvolvimento de software, oferecendo uma maneira eficaz de capturar requisitos funcionais e prioridades do ponto de vista do usuário.

Essas histórias proporcionam uma abordagem centrada no usuário, permitindo que equipes multidisciplinares compreendam e atendam às necessidades dos usuários. Ao definir casos de uso específicos e critérios de aceitação claros, as histórias de usuário fornecem uma base sólida para a criação de produtos e sistemas que atendam às expectativas dos usuários finais.

## Metodologia
As histórias de usuário foram desenvolvidas tendo em vista a elaboração do [backlog](./backlog.md), onde os avaliadores Jefferson, Rafael e Yago discutiram e tematizaram os requisitos para encontrar seus respectivos Épicos e, assim, seguir modelagem ágil. A gravação desta reunião está presente [aqui](./backlog.md).

Na elaboração de cada história de usuário, mantemos sua estrutura objetiva, curta e detalhada, exemplificada da seguinte forma:

- ### Nome da História
  - **ID:** Identificação da história (USXX)
  - **Origem:** Requisito(s) que originaram a históra
  - **Descrição:** Eu, como ***papel***, desejo ***descrição da funcionalidade desejada***
  - **Motivo:** O porque dessa história
  - **Critérios de aceitação**:
    - Lista dos critérios de aceitação
  - **Validez:** O usuário validou a história

Após a especificação de cada história, o avaliador Yago se reuniu com o usuário Thales Vieira, que consentiu com sua participação no projeto, para validar as histórias elaboradas. Dessa forma, a tabela 1 demonstra os papéis de cada avaliador, bem como do entrevistado, na elaboração do Backlog e das histórias de usuário.

|    Função     |   Participante   |
| :-----------: | :--------------: |
| Scrum Master  | Jefferson França |
| Desenvolvedor | Rafael Fernandes |
| Desenvolvedor |  Yago Milagres   |
| Product Owner |  Thales Vieira   |

<div style="text-align: center">
<p> Tabela 1: Relação dos papéis do Scrum. (Fonte: Yago Passos, 2023).</p>
</div>

## Especificação das histórias de usuário

- ### Realizar Login com Credenciais de outra Rede Social
  - **ID:** US01
  - **Origem:** [IN17](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:**  Eu, como usuário, desejo fazer login na plataforma utilizando minhas credenciais do Google ou do Facebook para acessar facilmente minha conta.
  - **Motivo:** Para simplificar o processo de login e garantir acesso rápido à minha conta.
  - **Critérios de Aceitação:**
    - Deve ser possível conectar a conta do Facebook à conta da plataforma.
    - Deve ser possível conectar a conta do Google à conta da plataforma.
    - As informações do perfil devem ser sincronizadas corretamente durante o login.
  - **Validez:** Validado pelo usuário

- ### Recuperar Senha Esquecida
  - **ID:** US02
  - **Origem:** [IN02](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:**  Eu, como usuário, desejo ter a opção de recuperar minha senha por meio de um processo de redefinição de senha seguro e eficiente.
  - **Motivo:** Para garantir o acesso contínuo à minha conta, mesmo em casos de senha esquecida ou perdida.
  - **Critérios de Aceitação:**
    - Deve haver um processo de verificação de identidade seguro para redefinir a senha.
    - O usuário deve receber instruções claras sobre como redefinir a senha com sucesso.
  - **Validez:** Validado pelo usuário

- ### Adicionar Livro à Estante
  - **ID:** US03
  - **Origem:** [IN08](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:**  Eu, como usuário, desejo adicionar um livro à minha estante e atribuir um status específico, como "Lido", "Lendo", "Quero ler", "Abandonei" ou "Relendo".
  - **Motivo:** Para organizar e compartilhar minha lista de leituras e experiências literárias.
  - **Critérios de Aceitação:**
    - Deve ser possível atribuir um dos estados especificados a cada livro adicionado à estante.
    - A atualização do status do livro na estante deve refletir corretamente na interface do usuário.
  - **Validez:** Validado pelo usuário

- ### Filtrar Livros por Nota
  - **ID:** US04
  - **Origem:** [IN06](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:**  Eu, como usuário, desejo filtrar os livros com base em sua avaliação de nota para encontrar facilmente os livros mais bem avaliados.
  - **Motivo:** Para descobrir rapidamente livros bem avaliados e de alta qualidade para leitura.
  - **Critérios de Aceitação:**
    - Deve haver uma opção clara para filtrar os livros com base na avaliação de nota.
    - Os resultados devem ser precisos e refletir as classificações correspondentes.
    - Deve ser possível agregar 2 ou mais especificações em uma só filtragem
    - Os resultados da pesquisa devem ser atualizados em tempo real a medida que o usuário ajusta o filtro
  - **Validez:** Validado pelo usuário

- ### Filtrar Livros por Categoria
  - **ID:** US05
  - **Origem:** [IN15](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:**  Eu, como usuário, desejo filtrar livros por categorias específicas, como gênero literário, para encontrar obras que correspondam aos meus interesses.
  - **Motivo:** Para explorar facilmente livros de gêneros específicos que se alinhem com meus gostos e preferências.
  - **Critérios de Aceitação:**
    - Deve ser possível selecionar diferentes categorias para filtrar os livros.
    - Os resultados da filtragem devem ser precisos e abranger as categorias escolhidas.
    - Deve ser possível agregar 2 ou mais especificações em uma só filtragem
    - Os resultados da pesquisa devem ser atualizados em tempo real a medida que o usuário ajusta o filtro
  - **Validez:** Validado pelo usuário

- ### Escrever Resenhas de Livros Lidos
  - **ID:** US06
  - **Origem:** [IN04, IN05](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:**  Eu, como usuário, desejo escrever resenhas detalhadas dos livros que já li para compartilhar minhas opiniões e experiências com outros leitores.
  - **Motivo:** Para contribuir com a comunidade de leitores e ajudar outros usuários a descobrir novos livros com base em minha avaliação e análise.
  - **Critérios de Aceitação:**
    - Deve haver uma opção clara para escrever e publicar resenhas na plataforma.
    - Os usuários devem ter a capacidade de editar ou excluir suas resenhas conforme necessário.
  - **Validez:** Validado pelo usuário

- ### Dar Notas aos Livros Lidos
  - **ID:** US07
  - **Origem:** [IN05](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:**  Eu, como usuário, desejo atribuir notas aos livros que li para expressar minha avaliação e classificação pessoal.
  - **Motivo:** Para fornecer uma avaliação quantitativa dos livros e compartilhar minhas preferências com outros usuários.
  - **Critérios de Aceitação:**
    - Deve haver um sistema de classificação clara, como o uso de estrelas, para avaliar os livros.
    - Os usuários devem ser capazes de visualizar a média de classificações dadas por outros usuários.
  - **Validez:** Validado pelo usuário

- ### Contabilizar Dias de Leitura ao Reler um Livro
  - **ID:** US08
  - **Origem:** [IN06](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:**  Eu, como usuário, desejo que os dias de leitura sejam contabilizados quando estou relendo um livro, para manter o registro preciso do meu progresso de leitura.
  - **Motivo:** Para monitorar o tempo dedicado à leitura de um livro específico, mesmo durante a re-leitura.
  - **Critérios de Aceitação:**
    - O sistema deve registrar com precisão os dias de leitura ao reler um livro específico.
    - Os usuários devem ser capazes de visualizar o histórico de leitura detalhado para cada livro.
  - **Validez:** Validado pelo usuário

- ### Criar Lista de Livros Desejados
  - **ID:** US09
  - **Origem:** [IN09](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:**  Eu, como usuário, desejo criar uma lista de livros desejados para registrar os livros que desejo ler no futuro.
  - **Motivo:** Para manter um registro organizado dos livros que despertaram meu interesse e que pretendo ler posteriormente.
  - **Critérios de Aceitação:**
    - Deve haver uma opção clara para adicionar livros à lista de desejos.
    - Os usuários devem poder acessar e gerenciar facilmente a lista de livros desejados.
  - **Validez:** Validado pelo usuário

- ### Compartilhar Lista de Livros Desejados
  - **ID:** US10
  - **Origem:** [IN10](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:** Eu, como usuário, desejo poder compartilhar minha lista de livros desejados com outros usuários para recomendar livros e descobrir novas leituras em potencial.
  - **Motivo:** Para compartilhar e explorar interesses literários com amigos e a comunidade de leitores.
  - **Critérios de Aceitação:**
    - Deve ser possível compartilhar a lista de livros desejados por meio de links ou convites específicos.
    - Os usuários devem ter opções de privacidade para controlar quem pode acessar sua lista de livros desejados.
  - **Validez:** Validado pelo usuário

- ### Pesquisar Outros Usuários
  - **ID:** US11
  - **Origem:** [IN11](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:** Eu, como usuário, desejo pesquisar outros usuários na plataforma para descobrir amigos com interesses literários semelhantes.
  - **Motivo:** Para expandir minha rede de contatos e interagir com outros leitores na comunidade.
  - **Critérios de Aceitação:**
    - Deve haver uma barra de pesquisa intuitiva para procurar outros usuários pelo nome ou nome de usuário.
    - Os resultados da pesquisa devem ser precisos e abranger os critérios de pesquisa especificados.
  - **Validez:** Validado pelo usuário

- ### Analisar o Perfil de Outros Usuários
  - **ID:** US12
  - **Origem:** [IN12](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:** Eu, como usuário, desejo visualizar e analisar o perfil de outros usuários para conhecer suas preferências literárias, estantes de livros e atividades recentes.
  - **Motivo:** Para entender melhor os interesses e atividades de leitura de outros usuários na plataforma.
  - **Critérios de Aceitação:**
    - Deve ser possível acessar o perfil de outros usuários com facilidade a partir de suas páginas de resultados de pesquisa.
    - As informações do perfil do usuário devem ser apresentadas de forma clara e organizada.
  - **Validez:** Validado pelo usuário

- ### Adicionar Outros Usuários como Amigos
  - **ID:** US13
  - **Origem:** [IN13](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:** Eu, como usuário, desejo adicionar outros usuários como amigos na plataforma para acompanhar suas atualizações e interagir com suas atividades literárias.
  - **Motivo:** Para fortalecer conexões sociais com outros leitores e compartilhar experiências literárias em uma comunidade engajada.
  - **Critérios de Aceitação:**
    - Deve haver uma opção clara para adicionar outros usuários como amigos.
    - Os usuários devem receber notificações sobre novas solicitações de amizade e confirmações de amizade.
  - **Validez:** Validado pelo usuário

- ### Visualizar Ranking Semanal/Mensal de Livros Mais Bem Classificados
  - **ID:** US14
  - **Origem:** [BS09](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:** Eu, como usuário, desejo acessar o ranking semanal/mensal de livros mais bem classificados na plataforma para descobrir novas obras populares e aclamadas.
  - **Motivo:** Para ficar atualizado com os livros mais populares e bem avaliados entre a comunidade de leitores.
  - **Critérios de Aceitação:**
    - Deve haver uma seção na plataforma dedicada a rankings de livros mais bem classificados.
    - Os rankings devem ser atualizados automaticamente em uma base semanal e mensal.
    - Os rankings devem exibir os títulos dos livros, capas, autores e a quantidade de leituras ou visualizações.
    - Os usuários devem poder clicar em um livro no ranking para obter mais informações e acessar sua página de detalhes.
    - Os livros devem ser classificados com base em critérios como classificação média dos usuários, número de avaliações ou popularidade.
    - A interface do usuário deve ser responsiva e funcionar bem em diferentes dispositivos, como computadores e dispositivos móveis.
  - **Validez:** Validado pelo usuário

- ### Visualizar Ranking Semanal/Mensal de Livros Mais Lidos
  - **ID:** US15
  - **Origem:** [BS10](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:** Eu, como usuário, desejo acessar o ranking semanal/mensal de livros mais lidos na plataforma para descobrir tendências de leitura e obras populares entre os usuários.
  - **Motivo:** Para explorar novos livros com base em sua popularidade e número de leituras registradas.
  - **Critérios de Aceitação:**
    - Deve haver uma seção na plataforma dedicada a rankings de livros mais lidos .
    - Os rankings devem ser atualizados automaticamente em uma base semanal e mensal.
    - Os rankings devem exibir os títulos dos livros, capas, autores e a quantidade de leituras ou visualizações.
    - Os usuários devem poder clicar em um livro no ranking para obter mais informações e acessar sua página de detalhes.
    - Os livros devem ser classificados com base em critérios como classificação média dos usuários, número de avaliações ou popularidade.
    - A interface do usuário deve ser responsiva e funcionar bem em diferentes dispositivos, como computadores e dispositivos móveis.
  - **Validez:** Validado pelo usuário

- ### Postar Fotos e/ou Vídeos em Formato "Stories"
  - **ID:** US16
  - **Origem:** [BS11](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:** Eu, como usuário, desejo poder postar fotos e/ou vídeos em formato de "stories" para compartilhar momentos literários e interagir com outros usuários de maneira envolvente.
  - **Motivo:** Para compartilhar experiências de leitura de forma visual e estimular a interação social na plataforma.
  - **Critérios de Aceitação:**
    - Deve haver uma opção clara para criar e publicar "stories" na plataforma.
    - Os usuários devem ter a capacidade de visualizar e interagir com as histórias publicadas por outros usuários.
    - O usuário deve poder capturar ou selecionar fotos e/ou vídeos da galeria do dispositivo para adicionar à postagem
    - As postagens no formato 'stories' devem ser visíveis apenas por um período limitado (por exemplo, 24 horas)
    - O usuário deve poder adicionar uma legenda ou descrição à postagem
    - Deve haver uma opção para o usuário compartilhar a postagem em suas histórias ou com um grupo específico de seguidores
  - **Validez:** Validado pelo usuário

- ### Criar Desafios entre Amigos
  - **ID:** US17
  - **Origem:** [BS14](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:** Eu, como usuário, desejo criar desafios de leitura personalizados e convidar meus amigos para participar, incentivando a interação e o engajamento em atividades literárias divertidas.
  - **Motivo:** Para promover interações sociais e incentivar a leitura entre amigos na plataforma.
  - **Critérios de Aceitação:**
    - Deve ser possível convidar amigos da plataforma para participar do desafio por meio de notificações ou convites
    - Deve haver uma opção para o usuário criar um desafio personalizado a partir da sua conta
    - Deve ser possível criar desafios personalizados com instruções e metas específicas.
    - Os usuários devem receber notificações sobre os convites para participar de desafios e atualizações do progresso do desafio.
  - **Validez:** Validado pelo usuário

- ### Receber Recomendações de Livros Personalizadas
  - **ID:** US18
  - **Origem:** [BS18](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:** Eu, como usuário, desejo receber recomendações de livros personalizadas com base nos meus interesses literários e atividades de leitura anteriores.
  - **Motivo:** Para descobrir novos livros que correspondam aos meus gostos e preferências pessoais.
  - **Critérios de Aceitação:**
    - O sistema deve analisar com precisão minhas preferências literárias e atividades de leitura para gerar recomendações relevantes.
    - Os usuários devem receber regularmente atualizações e notificações sobre novas recomendações de livros com base em seus perfis.
    - As recomendações de livros devem ser geradas com base nas informações coletadas e em algoritmos de recomendação
    - Os usuários devem poder visualizar informações detalhadas sobre os livros recomendados, como capa, título, autor, sinopse e avaliações de outros leitores
  - **Validez:** Validado pelo usuário

- ### Sortear livro entre livros "Quero ler"
  - **ID:** US19
  - **Origem:** [BS03](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:** Eu, como usuário, quero ter a opção de sortear um livro aleatoriamente da minha lista de livros marcados como "Quero Ler"
  - **Motivo:** Quero que o sistema me ajude a escolher qual será minha próxima leitura com base nos livros que demonstrei interesse. 
  - **Critérios de Aceitação**:
    - Deve ser possível sortear um livro dentre os livros marcados como Quero ler para a próxima leitura do usuário
    - O sistema deve verificar se o usuário tem pelo menos um livro marcado como "Quero Ler"
    - Se o usuário não tiver pelo menos um livro marcado como "Quero Ler" o sistema deve exibir uma mensagem informativa indicando que não há livro disponíveis para sorteio.
    - O sistema deve garantir que o sorteio seja verdadeiramente aleatório e imparcial
- **Validez:** Validado pelo usuário
      
- ### Alterar Tema da Interface
  - **ID:** US20
  - **Origem:** [BS08](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:** Eu, como usuário, desejo ter a opção de alterar o tema da interface do aplicativo    
  - **Motivo:** Para personalizar a experiência de uso de acordo com minhas preferências visuais e para adaptar a interface de acordo com as condições de iluminação do ambiente ou para melhorar a acessibilidade.
  - **Critérios de Aceitação:**
    - Deve haver uma seleção clara de temas disponíveis na seção de configurações da interface.
    - A mudança de tema deve ser refletida imediatamente em todos os elementos da interface, incluindo cores, fontes e layout.
    - Os temas disponíveis devem incluir opções de tema claro, tema escuro e outras variantes que possam ser visualmente agradáveis e acessíveis para os usuários.
    - Os temas selecionados devem ser aplicados consistentemente em todas as telas e páginas do aplicativo.
  - **Validez:** Validado pelo usuário

### Validação das histórias de usuário

O Vídeo 1, presente a seguir, contém o conteúdo da reunião de validação com o usuário Thales Vieira, que leu e consentiu com o [termo de consentimento e uso de imagem](./img/TERMO%20DE%20AUTORIZAÇÃO%20DE%20USO%20DE%20IMAGEM%20THALES.pdf)

<iframe width="1000vw" height="650vh" src="https://www.youtube.com/embed/bV-c_BaWt-M" title="Validação de histórias de usuário" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen=""></iframe>

<div style="text-align: center">
<p> Vídeo 1: Validação de User Stories. (Fonte: Yago Milagres Passos. 2023).</p>
</div>

## Conclusão

O desenvolvimento das histórias de usuário desempenhou um papel fundamental na definição dos requisitos essenciais para o sucesso do projeto "Skoob". Ao abordar as necessidades e expectativas dos usuários de maneira abrangente, as histórias de usuário fornecem uma estrutura sólida para o desenvolvimento de funcionalidades e recursos que promovem a interação, o engajamento e a satisfação do usuário. 

Ao implementar as histórias de usuário identificadas neste artefato, espera-se que a plataforma "Skoob" atenda às demandas dos usuários de forma eficaz, fornecendo uma experiência enriquecedora e personalizada no mundo da literatura.

## Bibliografia

[1] VLC. Hitórias de Usuário. Grupo VLC da disciplina Requisitos de Software, disponível em: https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/cenarios. Acesso em: 16 de outubro de 2023.

[2] SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 15. 1º/2019. 46 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

## Histórico de Versão

| Versão | Data de execução | Data prevista de revisão |                   Descrição                   |                   Autor(es)                   |                  Revisado                  |
| :----: | :--------------: | :----------------------: | :-------------------------------------------: | :-------------------------------------------: | :----------------------------------------: |
| `1.0`  |    03/11/2023    |        05/11/2023        |              Criação do Artefato              | [Jefferson França](https://github.com/Frans6) | <input type="checkbox" enabled checked /> |
| `1.1`  |    04/11/2023    |        04/11/2023        |            Elaboração de Histórias            | [Jefferson França](https://github.com/Frans6) | <input type="checkbox" enabled checked /> |
| `1.2`  |    05/11/2023    |        05/11/2023        | Seções de Introdução, Metodologia e Conclusão | [Yago Passos](https://github.com/yagompassos) | <input type="checkbox" enabled checked /> |
| `1.3`  |    06/11/2023    |        06/11/2023        |      Adicionando a gravação da validação      | [Yago Passos](https://github.com/yagompassos) | <input type="checkbox" enabled checked /> |

### Revisão (V&V)
| Data de Revisão | Cobertura de Versões |       Técnica        |                  Revisor(es)                  |
| :-------------: | :------------------: | :------------------: | :-------------------------------------------: |
|   04/11/2023    |        `1.0`         | Revisão por inspeção | [Yago Passos](https://github.com/yagompassos) |
|   04/11/2023    |        `1.1`         | Elaboração em pares  | [Yago Passos](https://github.com/yagompassos) |
|   04/11/2023    |        `1.2`         | Elaboração em pares  | [Jefferson França](https://github.com/Frans6) |
|   04/11/2023    |        `1.3`         | Elaboração em pares  | [Jefferson França](https://github.com/Frans6) |