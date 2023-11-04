# Histórias de Usuário

## Introdução

## Metodologia

### Subtítulo - Exemplo de Tabela

|    Função     | Participante |
| :-----------: | :----------- |
| Scrum Master  | ----         |
| Desenvolvedor | ----         |
| Desenvolvedor | ----         |
| Product Owner | ----         |

<div style="text-align: center">
<p> Tabela 1: Exemplo de Tabela. (Fonte: Jefferson França, 2023).</p>
</div>

## Especificação das histórias de usuário

- ### Operações de Login
  - **ID:** US01
  - **Origem:** [OB01](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:** Eu, como usuário, desejo ingressar na plataforma com minhas credenciais (nome de usuário e senha).
  - **Motivo:** Quero poder salvar minhas preferências no aplicativo para poder acessá-las depois.
  - **Critérios de Aceitação**:
    - Deve ser possível realizar cadastro
    - Deve ser possível recuperar a senha
    - Deve ser possível fazer cadastro/login com as credenciais do facebook
    - O sistema deve verificar se as credenciais são válidas
    - Deve ser possível realizar login com sucesso em diferentes tipos de dispositivos
  - **Validez:**


- ### Filtragem de Livros
  - **ID:** US02
  - **Origem:** [IN14, IN15](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:** Eu, como usuário, desejo filtrar livros do sistema de acordo com alguma especificação, por exemplo, nota ou por categoria.
  - **Motivo:** Quero ter acesso a uma lista de pesquisa facilitada de acordo com meus gostos, sem ter que visualizar categorias que não são do meu interesse, ou livros de nota baixa.
  - **Critérios de Aceitação**: 
    - O sistema deve apresentar apenas uma lista de livros que atendam a filtragem especificada pelo usuário
    - Deve ser possível alterar a filtragem por Categoria
    - Deve ser possível alterar a filtragem por Nota 
    - Deve ser possível agregar 2 ou mais especificações em uma só filtragem
    - Os resultados da pesquisa devem ser atualizados em tempo real a medida que o usuário ajusta o filtro
  - **Validez:**

- ### Adicionar livro à estante
    - **ID:** US03
    - **Origem:** [OB03](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
    - **Descrição:** Eu, como usuário, desejo escolher um livro da lista de livvros da plataforma e adicioná-lo à minha estante, escolhendo uma etiqueta de acordo com meu desenvolvimento com o livro.
    - **Motivo:** Quero ter acesso a uma lista de livros que tenho, tive, ou quero ter contato, para salvar minhas preferências e poder interagir sobre livros lidos ou em processo de leitura.
    - **Critérios de Aceitação**: 
        - Deve ser possível marcar os livros como: Lido / Lendo / Quero ler / Abandonei / Relendo
    - **Validez:**
    
- ### Sorteio e recomendaçoes
  - **ID:** US04
  - **Origem:** [BS03](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:** Eu, como usuário, quero ter a opção de sortear um livro aleatoriamente da minha lista de livros marcados como "Quero Ler"
  - **Motivo:** Quero que o sistema me ajude a escolher qual será minha próxima leitura com base nos livros que demonstrei interesse. 
  - **Critérios de Aceitação**:
    - Deve ser possível sortear um livro dentre os livros marcados como Quero ler para a próxima leitura do usuário
    - O sistema deve verificar se o usuário tem pelo menos um livro marcado como "Quero Ler"
    - Se o usuário não tiver pelo menos um livro marcado como "Quero Ler" o sistema deve exibir uma mensagem informativa indicando que não há livro disponíveis para sorteio.
    - O sistema deve garantir que o sorteio seja verdadeiramente aleatório e imparcial
  - **Validez:**

- ### Feedback dos livros
  - **ID:** US05
  - **Origem:** [IN04, IN05](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:** Eu, como usuário, desejo poder dar notas a e comentar sobre os livros que tenho na estante como lidos.
  - **Motivo:** Quero interagir com outros leitores sobre os livros que conheço e ser capaz de ver os feedbacks já existentes sobre os mesmos.
  - **Critérios de Aceitação**:
    - O usuário deve ser capaz de adicionar um título curto para sua resenha
    - Deve ser possível adicionar classificações (por exemplo, em estrelas) à resenha indicando a avaliação do livro.
    - O usuário deve ter a opção de salvar a resenha como rascunho antes de publicá-la
    - Outros usuários devem ser capazes de interagir com resenhas (como curtir, comentar ou denunciar)
  - **Validez:**
  
- ### Ranking de Livros
  - **ID:** US06
  - **Origem:** [BS09, BS10](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:** Eu, como usuário, desejo ter acesso a um ranking semanal e mensal que categoriza livros de acordo com sua popularidade ou qualidade geral
  - **Motivo:** Quero poder ver quais livros estão em alta, para poder me inspirar ou ter ideias com base no que outros usuários estão lendo e gostando.
  - **Critérios de Aceitação**:
    - Deve haver uma seção na plataforma dedicada a rankings de livros mais lidos e mais bem classificados.
    - Os rankings devem ser atualizados automaticamente em uma base semanal e mensal.
    - Os rankings devem exibir os títulos dos livros, capas, autores e a quantidade de leituras ou visualizações.
    - Os usuários devem poder clicar em um livro no ranking para obter mais informações e acessar sua página de detalhes.
    - Os livros devem ser classificados com base em critérios como classificação média dos usuários, número de avaliações ou popularidade.
    - A interface do usuário deve ser responsiva e funcionar bem em diferentes dispositivos, como computadores e dispositivos móveis.
  - **Validez:**

- ### Desafios
  - **ID:** US07
  - **Origem:** [BS13, BS14](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:** Eu, como usuário, gostaria de participar de desafios propostos pela aplicativo.
  - **Motivo:** Quero poder me divertir e ler ao mesmo tempo, com meus amigos.
  - **Critérios de Aceitação**:
    - Deve ser possível convidar amigos da plataforma para participar do desafio por meio de notificações ou convites
    - Deve haver uma opção para o usuário criar um desafio personalizado a partir da sua conta
    - Os usuários devem receber notificações quando forem convidados para um desafio e quando um desafio for concluído
    - Os desafios podem ser concluídos individualmente ou em competições contra outros usuários, dependendo do tipo de desafio
  - **Validez:**

- ### Cadastrar livro
  - **ID:** US08
  - **Origem:** [IN03](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:** Eu, como usuário, quero poder cadastrar um livro caso ele não seja encontrado pelo sistema de busca ou que ainda não exista no sistema.
  - **Motivo:** Quero manter os livros cadastrados atualizados no sistema.
  - **Critérios de Aceitação**:
    - Deve haver uma opção visível na interface do usuário que permita ao usuário cadastrar um livro.
    - Deve haver a possibilidade de adicionar uma sinopse ou descrição do livro.
    - O sistema deve permitir que o usuário adicione a capa do livro, que pode ser enviada a partir de um arquivo ou vinculada a uma URL.
    - Deve ser possível associar o livro a categorias ou gêneros específicos.
  - **Validez:**
  
  - ### Sistemas Operacionais
  - **ID:** US09
  - **Origem:** [IN18](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:** Eu, como usuário, gostaria de ter a capacidade de baixar o aplicativo em qualquer sistema operacional móvel compatível.
  - **Motivo:** Quero conseguir acessar o aplicativo do meu dispositivo móvel.
  - **Critérios de Aceitação**:
    - O aplicativo deve estar disponível para download e instalação em sistemas operacionais móveis populares, como iOS (Apple), Android (Google).
    - Os links de download devem direcionar os usuários para a versão correta do aplicativo para o sistema operacional de seus dispositivos.
    - Os usuários devem receber suporte ou orientação para a instalação do aplicativo em seus dispositivos.
  - **Validez:**

  - ### Meta de Leitura
  - **ID:** US10
  - **Origem:** [BS01](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:** Eu, como usuário, gostaria de ter a capacidade de estabelecer uma meta de leitura para o ano.
  - **Motivo:** Quero conseguir definir um obejetivo de quantos livros desejo ler no ano e rastrear meu progresso.
  - **Critérios de Aceitação**:
    - O usuário deve poder definir um número de livros como sua meta anual
    - Deve haver uma área para inserir ou selecionar a data de início e término da meta
    - O sistema deve calcular automaticamente o número de livros a serem lidos por mês ou semana para alcançar a meta
    - O sistema deve exibir um indicador visual do progresso, mostrando quantos livros foram lidos em relação à meta
    - O sistema deve fornecer notificações ou lembretes regulares para incentivar o usuário a atingir sua meta
  - **Validez:**

  - ### Stories
  - **ID:** US11
  - **Origem:** [BS11](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:** Eu, como usuário, gostaria de ter a capacidade de criar e compartilhar fotos e/ou vídeos em formato 'stories'.
  - **Motivo:** Quero poder compartilhar momentos com meus amigos
  - **Critérios de Aceitação:**
    - O usuário deve poder capturar ou selecionar fotos e/ou vídeos da galeria do dispositivo para adicionar à postagem
    - As postagens no formato 'stories' devem ser visíveis apenas por um período limitado (por exemplo, 24 horas)
    - O usuário deve poder adicionar uma legenda ou descrição à postagem
    - Deve haver uma opção para o usuário compartilhar a postagem em suas histórias ou com um grupo específico de seguidores
  - **Validez:**

  - ### Recomendações
  - **ID:** US12
  - **Origem:** [BS18](https://github.com/Requisitos-de-Software/2023.2-Skoob/blob/main/docs/elicitacao/requisitos.md)
  - **Descrição:** Eu, como usuário, gostaria de receber recomendações de livros personalizadas com base nas minhas preferências literárias
  - **Motivo:** Quero descobrir novos livros que se encaixe em meus gostos literários
  - **Critérios de Aceitação**:
    - O sistema deve coletar e analisar informações sobre as preferências literárias do usuário, incluindo gêneros favoritos, autores preferidos e livros lidos anteriormente
    - As recomendações de livros devem ser geradas com base nas informações coletadas e em algoritmos de recomendação
    - Os usuários devem poder visualizar informações detalhadas sobre os livros recomendados, como capa, título, autor, sinopse e avaliações de outros leitores
    - Os usuários devem receber notificações ou atualizações regulares com novas recomendações de livros com base em suas preferências
  - **Validez:**

  - ### Interação entre usuários
  - **Id**
  - **Origem:**
  - **Descrição:**
  - **Motivo:**
  - **Critérios de Aceitação**:
  - **Validez:**



### Exemplo Imagem

<a id="a" href="#aa">![image](img/imagem.png)</a>

<div style="text-align: center">
<p>Figura 1 - Exemplo de Imagem. (Fonte: Jefferson França. 2023)</p>
</div>

## Bibliografia

<a id="aa" href="#a">[1]</a> IMAGEM. Disponível em: [Imagem](https://pt.wikipedia.org/wiki/Imagem). Acesso em: 05 de Setembro de 2023.

## Histórico de Versão

| Versão | Data de execução | Data de revisão |      Descrição      |                   Autor(es)                   |                  Revisor(es)                  |
| :----: | :--------------: | :-------------: | :-----------------: | :-------------------------------------------: | :-------------------------------------------: |
| `1.0`  |    03/11/2023    |   05/11/2023    | Criação do Artefato | [Jefferson França](https://github.com/Frans6) | [Yago Passos](https://github.com/yagompassos) |
