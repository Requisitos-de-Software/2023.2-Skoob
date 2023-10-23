# Especificação Suplementar

## Introdução

A especificação suplementar exerce a identificação de requisitos do sistema que não foram diretamente abordados na modelagem de casos de uso, de forma que ao integrar ambas as perspectivas, seja possível definir de maneira abrangente todos os requisitos do sistema.

Esse método fundamenta-se nos seguintes critérios:

- Funcionalidade
- Usabilidade
- Confiabilidade
- Desempenho
- Suportabilidade

## Metodologia

Com base no tópico anterior, o modelo adotado para este artefato é o FURPS+, uma metodologia que estabelece requisitos de um sistema dentro dos cinco critérios mencionados anteriormente.

- __F - Functionality:__ Engloba os aspectos funcionais do sistema, detalhados nos casos de uso. Esses requisitos estão relacionados às funcionalidades específicas que o sistema deve oferecer para atender às necessidades dos usuários.
- __U - Usability:__ Refere-se à facilidade com que os usuários podem interagir e realizar suas tarefas por meio do software. Isso inclui a interface do usuário, a navegabilidade e a experiência geral de uso.
- __R - Reliability:__ Avalia o quão confiável o software foi projetado para ser, ou seja, sua capacidade de operar sem falhas ou interrupções inesperadas. Isso envolve questões de robustez e tolerância a falhas.
- __P - Performance:__ Considera o desempenho do software em termos de velocidade, eficiência e capacidade de resposta. Isso pode incluir métricas como tempo de resposta, taxa de transferência e uso de recursos.
- __S - Supportability:__ Engloba requisitos relacionados à manutenibilidade, adaptabilidade, internacionalização, portabilidade e outros aspectos relevantes para a manutenção e escalabilidade do sistema.
- __+:__ Este símbolo representa requisitos não funcionais adicionais que não se enquadram nos pilares listados. Estes podem incluir aspectos de design, implementação, interface e considerações físicas. 

### Functionality (Funcionalidades)

Os requisitos funcionais são explicitados de forma detalhada nos casos de uso, oferecendo uma visão concreta das operações e interações do sistema com seus usuários e outros elementos do ambiente.

### Usability (Usabilidade)

Engloba a capacidade do sistema de ser facilmente compreendido e utilizado pelos usuários, independentemente de sua familiaridade prévia com a plataforma, além de se estender à eficácia, eficiência e satisfação geral dos mesmos.

#### Facilidade de Uso

O Skoob é intuitivo e de fácil navegação. Suas operações são simples e diretas, proporcionando uma experiência de uso sem complicações. Para realizar ações principais, como adicionar um livro à estante, geralmente são necessários cinco cliques.

#### Disponibilidade

O Skoob requer uma conexão com a internet para funcionar, o que pode ser um ponto de consideração para usuários em locais com acesso instável ou nenhum acesso à rede.

#### Interface

A interface do Skoob foi projetada para ser amigável e eficiente, além de promover a interação entre os usuários. Ela facilita a realização das principais atividades, como buscar livros, adicioná-los à sua estante e registrar históricos de leitura.

### Reliability (Confiabilidade)

A confiabilidade está relacionada às medidas adotadas para garantir a segurança e integridade dos dados dos usuários dentro do sistema.

#### Garantia de segurança mínima no armazenamento de dados

O Skoob prioriza a segurança dos dados dos usuários com um sistema que não mantém informações pessoais armazenadas. Elas são acessadas apenas durante a utilização do aplicativo, em total conformidade com as políticas de privacidade da plataforma. Essa prática é rigorosamente alinhada ao termo de uso do aplicativo, reforçando a segurança mínima garantida.

#### Garantia de disponibilidade

O Skoob é projetado para funcionar de maneira contínua, 24 horas por dia e sete dias por semana, desde que o usuário disponha de conexão estável à internet.

### Performance (Desempenho)

#### Armazenamento

Para instalar o aplicativo Skoob, o usuário precisará de aproximadamente 30MB de espaço disponível em seu dispositivo no caso do sistema operacional ser Android e 60MB no caso do IOS.

#### Tempo de resposta

O Skoob deve ter um tempo de comunicação ágil, com o dispositivo móvel, de no máximo 7 segundos. Isso significa uma experiência fluida e rápida ao utilizar o aplicativo.

### Supportability (Suportabilidade)

A suportabilidade engloba uma série de aspectos técnicos cruciais, tais como manutenibilidade, adaptabilidade, internacionalização, portabilidade, além de outros elementos relevantes.

#### Sistemas operacionais (OS)

O aplicativo Skoob é compatível com os seguintes sistemas operacionais:

- Para dispositivos iOS: Requer iOS 11.0 ou posterior (App Store)<a id="a" href="#bb">[2]</a>.
- Para dispositivos Android: Requer Android 6.0 ou superior (Google Play)<a id="a" href="#cc">[3]</a>.

O aplicativo Skoob pode ser instalado em uma ampla variedade de dispositivos, incluindo:

- iPhone
- iPad
- iPod touch
- Apple TV
- Celulares Android, entre outros.

#### Idiomas

O Skoob oferece suporte aos idiomas:

- Português (Brasil)
- Inglês

### +

Esta categoria abrange uma variedade de requisitos, incluindo design, implementação e considerações físicas.

#### Design

O aplicativo Skoob segue uma paleta de cores composta predominantemente de azul e branco. Os usuários têm a opção de escolher entre diversos temas, incluindo o tema padrão claro, que faz uso do azul e do branco definido na paleta de cores. Além disso, o Skoob oferece opções de temas escuros, como Dark, Dark Blue, Dark Pink e Dark Gray, para atender às preferências individuais dos usuários. Para os que buscam uma estética mais nostálgica, o tema Old Paper também está disponível. Essa variedade de temas permite uma personalização flexível, proporcionando uma experiência única a cada usuário.

## Bibliografia

<a id="aa" href="#a">[1]</a> SALES, André. Modelagem de Requisitos. Disponível em: [Aprender 3](https://aprender3.unb.br/pluginfile.php/2692803/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf). Acesso em 23 de outubro de 2023.<br>
<a id="bb" href="#a">[2]</a> SKOOB IOS. Disponível em: [App Store](https://apps.apple.com/br/app/skoob-organize-suas-leituras/id904670263). Acesso em: 23 de Outubro de 2023.<br>
<a id="cc" href="#a">[3]</a> SKOOB ANDROID. Disponível em: [Google Play](https://play.google.com/store/apps/details?id=com.gaudium.skoob). Acesso em: 23 de Outubro de 2023.<br>

## Histórico de Versão

| Versão | Data de execução | Data de revisão |             Descrição             |                      Autor(es)                       |                     Revisor(es)                      |
| :----: | :--------------: | :-------------: | :-------------------------------: | :--------------------------------------------------: | :--------------------------------------------------: |
| `1.0`  |    23/10/2023    |   24/10/2023    | Criação do artefato |   [Ana Rocha](https://github.com/anaaroch)    | [Rafael Amancio](https://github.com/Rafael-gc) |

