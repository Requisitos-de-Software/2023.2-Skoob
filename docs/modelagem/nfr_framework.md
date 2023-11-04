# NFR framework

## Introdução

NFR é um framework conceitual que se baseia no Softgoal Interdependency Graph (SIG) como modelo principal. Seu principal enfoque está nos requisitos Não-Funcionais do aplicativo. No Framework, softgoals são empregados como metas de caráter vago, desprovidas de critérios de satisfação claramente definidos. Estes softgoals são usados para representar os Requisitos Não-Funcionais e podem se interconectar, demonstrando como um softgoal influencia outro. <a href="#aa">[1]</a>

### Requisitos Não Funcionais Elicitados

Abaixo, na tabela 1, estão os [requisitos não funcionais](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/requisitos/) elicitados pela equipe.

| ID | Requisito | Fonte |
|----|-----------|-------|
|RNF01| A senha deve conter no mínimo um número uma letra maiúscula e um caracter especial| [Introspecção](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/introspeccao/)|
|RNF02| Deve ser possível fazer cadastro/login com as credenciais do facebook	|  [Introspecção](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/introspeccao/)|
|RNF03| Deve ser possível obter o aplicativo em qualquer sistema operacional| [Introspecção](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/introspeccao/)|
|RNF04| Os dados do usuário devem ser guardados de forma eficaz, impendindo o vazamento dos mesmos| [Introspecção](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/introspeccao/)|
|RNF05| Os dados do usuário devem ser guardados de forma eficaz, impendindo o vazamento dos mesmos| [Brainstorming](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/brainstorming/)|
|RNF06|  O Skoob deve ser capaz de se adaptar a diferentes tamanhos de tela e resoluções | [Introspecção](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/introspeccao/)|

<div style="text-align: center;">
    Tabela 1: Requisitos Não Funcionais Elicitados, Autor(a): Shaíne e Ana, 2023
</div>

### Softgoals

Os softgoals são separados em 3 tipos: <a href="#aa">[1]</a>

- NFR Softgoal: Um requisito não-funcional que é avaliado durante a análise para determinar sua inclusão ou exclusão no projeto. Esses requisitos são considerados como critérios de qualidade e são avaliados para assegurar que o produto final atenda aos padrões desejados, servindo como indicadores de qualidade.

- Softgoal de Operacionalização: São funcionalidades que têm o papel de tornar concretas as características abstratas. Em outras palavras, elas são responsáveis por converter os requisitos não-funcionais em funcionalidades tangíveis que podem ser implementadas no sistema, representando a materialização das características abstratas em elementos mensuráveis.

- Claim Softgoal (Arfimação): É uma notação que pode ser incorporada ao modelo para argumentar pontos específicos da modelagem em linguagem natural. Essa notação permite expressar ideias ou justificativas relacionadas ao modelo, auxiliando na explicação do raciocínio por trás de determinadas escolhas de design.

Além disso, cada um desses softgoals pode ser detalhado ou subdividido em sub-requisitos, utilizando as seguintes técnicas:

- Decomposição de Softgoal NFR: Essa técnica permite uma melhor organização e compreensão dos softgoals NFR, desdobrindo-os em componentes mais específicos.

- Decomposição de Operacionalização: Essa técnica viabiliza a definição de uma solução geral, desagregando-a em casos mais específicos para uma compreensão mais detalhada.

- Decomposição de Afirmação (Claims): Essa técnica possibilita a reafirmação ou negação de justificativas específicas do projeto, oferecendo uma abordagem mais detalhada da argumentação.

- Priorização: Esta técnica envolve a subdivisão de um softgoal em outro softgoal do mesmo tipo e tópico, mas com uma prioridade associada, permitindo uma hierarquia de importância entre os requisitos. <a href="#aa">[1]</a>

| Contribuição       | Descrição  | Notação    |  
| ------------------ | ---------- | ---------- |
| *MAKE*  | FILHO com contribuição tão positiva a ponto de satisfazer o PAI sob a perspectiva dos envolvidos. | ++     | 
| *HELP*  | FILHO com contribuição positiva parcial, que sozinho não chega a satisfazer o PAI sob a perspectiva dos envolvidos. | +     |  
| *UNKNOWN*  | FILHO não afeta o PAI. | ?    |
| *HURT*   | FILHO com contribuição negativa parcial, que sozinho não chega a negar o PAI sob a perspectiva dos envolvidos. | -| 
| *BREAK*    | FILHO com contribuição tão negativa a ponto de negar o PAI sob a perspectiva dos envolvidos| --| 
| *SOME +*   | FILHO com contribuição positiva, cuja intensidade não se pode determinar. | SOME + | 
| *SOME -*   | FILHO com contribuição negativa, cuja intensidade não se pode determinar | SOME - | 
| *AND*    | “Pai” é satisfeito se somente todos os “filhos” forem satisfeitos sob a perspectiva dos envolvidos| AND|
| *OR* | “Pai” é satisfeito se somente um dos “filhos” é satisfeito sob a perspectiva dos envolvidos |OR|    
| *EQUAL* | Ambos compartilham o mesmo label| =| 

<div style="text-align: center;">
    Tabela 2: Contribuições, Autor(a): Shaíne 
</div>
 
## Legendas

### Softgoals

<div style="text-align: center;">
    <img src="../img/legenda_framework.png" alt="image" width="500"/>
</div>

<div style="text-align: center;">
    Figura 1: Legenda Softgoals,  Fonte: Shaíne
</div>

### Rótulos

<div style="text-align: center;">
    <img src="../img/rotulos.png" alt="image" width="900"/>
</div>

<div style="text-align: center;">
    Figura 2: Rótulos, Fonte: NFR4ES - Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. <a href="#aa">[1]</a>
</div>

Descrição: <a href="#aa">[1]</a>

- Satisfeito: Reflete que um requisito não funcional tem um impacto positivo na realização de outro requisito, resultando em contentamento.
- Fracamente satisfeito: Indica uma relação de impacto positivo, porém menos pronunciada do que a condição de "satisfeito".
- Negado: Demonstra que um requisito não funcional prejudica adversamente outro requisito, invalidando ou contradizendo sua realização.
- Fracamente negado: Similar à notação "negado", mas com uma relação de negação mais suave.
- Conflitante: Indica uma relação de conflito entre requisitos não funcionais, sugerindo que esses requisitos possuem aspectos tanto positivos quanto negativos que entram em choque.
- Indeterminado: Refere-se a uma relação incerta ou desconhecida entre requisitos não funcionais, geralmente quando há informações insuficientes para determinar o impacto de um requisito sobre o outro.

## NFR
 Foram feitos 3 tipos de NFR: Portabilidade, Interoperabilidade e Segurança.

## NFR-1 Portabilidade

### Requisito de Portabilidade

| ID  | Requisito |
|-----|-----------|
|RNF01| Deve ser possível obter o aplicativo em qualquer sistema operacional|
|RNF06|  O Skoob deve ser capaz de se adaptar a diferentes tamanhos de tela e resoluções |

<div style="text-align: center;">
    Tabela 3: Requisito de Portabilidade, Autor(a): Shaíne e Ana, 2023
</div>

### Sem Propagação

<div style="text-align: center;">
    <img src="../img/portabilidade_semPropagacao.png" alt="image" width="500"/>
</div>

<div style="text-align: center;">
    Figura 3: NFR-1 Portabilidade, Autor(a): Shaíne e Ana, 2023
</div>

### Com Propagação

<div style="text-align: center;">
    <img src="../img/portabilidade_propagacao.png" alt="image" width="500"/>
</div>
 
<div style="text-align: center;">
    Figura 4: NFR-1 Portabilidade com Propagação, Autor(a): Shaíne  e Ana, 2023
</div>

### Cartões de Especificação

| Classificação         | Multiplataforma / Portabilidade | 
| ----------------------|--|
| Descrição             | O aplicativo deve ser acessível em diversos sistemas operacionais. |
| Justificativa         | O aplicativo deve estar disponível em várias plataformas, como iOS e Android, para garantir que os usuários possam acessar suas notas em qualquer dispositivo. |
| Origem do requisito   | RNF01 |
| Critério de aceitação | Recurso financeiro disponivel. |
| Prioridade            | Alta prioridade.  Fonte: [TLS](./../elicitacao/three_level_scale.md) |
| Conflito              | Custo elevado. |
| Historia              | 01 de nov. 2023 |

<div style="text-align: center;">
Tabela 4: Cartão de Especificação - Sistema Operacional, Autor(a): Shaíne, 2023
</div>

| Classificação         | Multiplataforma / Portabilidade | 
| ----------------------|--|
| Descrição             | O Skoob deve ser capaz de se adaptar a diferentes tamanhos de tela e resoluções, proporcionando uma experiência de uso consistente e de alta qualidade em dispositivos de diferentes modelos e fabricantes. |
| Justificativa         | A adaptação a diferentes tamanhos de tela e resoluções é essencial para garantir uma experiência de usuário satisfatória, desde smartphones até tablets. Isso permite que os usuários desfrutem do Skoob em seus dispositivos preferidos, sem comprometer a usabilidade. |
| Origem do requisito   | RNF06 |
| Critério de aceitação | O aplicativo deve ser testado em uma variedade de dispositivos com diferentes tamanhos de tela e resoluções, e não deve apresentar problemas de usabilidade ou layout em nenhum deles. |
| Prioridade            | Média prioridade.  Fonte: [TLS](./../elicitacao/three_level_scale.md) |
| Conflito              | Pode haver desafios técnicos na implementação da adaptação a diferentes tamanhos de tela, especialmente em dispositivos muito pequenos ou com resoluções muito baixas. No entanto, a prioridade é garantir uma experiência consistente em todas as plataformas. |
| Historia              | 04 de nov. 2023 |

<div style="text-align: center;">
Tabela 5: Cartão de Especificação - Portabilidade, Autor(a): Ana, 2023 
</div>

## NFR-2 Interoperabilidade

### Requisito de Interoperabilidade

| ID  | Requisito |
|-----|-----------|
|RNF02| Deve ser possível fazer cadastro/login com as credenciais do Facebook|
|RNF05| O Skoob deve ser capaz de interoperar com outras plataformas de redes sociais, permitindo aos usuários compartilhar conteúdo.|

<div style="text-align: center;">
Tabela 6: Requisito de Interoperabilidade, Autor(a): Shaíne e Ana, 2023
</div>

### Sem Propagação

<div style="text-align: center;">
    <img src="../img/interoperabilidade_semPropagacao.png" alt="image" width="500"/>
</div>

<div style="text-align: center;">
    Figura 5: NFR-2 Interoperabilidade, Autor(a): Shaíne e Ana, 2023
</div>

### Com Propagação

<div style="text-align: center;">
    <img src="../img/interoperabilidade_comPropagacao.png" alt="image" width="500"/>
</div>
 
 <div style="text-align: center;">
    Figura 6: NFR-2 Interoperabilidade com Propagação, Autor(a): Shaíne e Ana, 2023
</div>

### Cartões de Especificação

| Classificação         | Interoperabilidade | 
| ----------------------|--|
| Descrição             | As senhas dos usuários devem atender aos seguintes critérios: conter no mínimo um número, pelo menos uma letra maiúscula e pelo menos um caractere especial. |
| Justificativa         | Esses critérios de senha são necessários para aumentar a segurança das contas de usuário, tornando mais difícil para os invasores adivinharem ou quebrarem senhas. Garantir que esse requisito seja atendido é essencial para proteger a privacidade e os dados dos usuários. |
| Origem do requisito   | RNF03|
| Critério de aceitação | O sistema deve validar todas as senhas inseridas pelos usuários para garantir que elas atendam aos critérios de pelo menos um número, uma letra maiúscula e um caractere especial. |
| Prioridade            | Alta prioridade.  Fonte: [TLS](./../elicitacao/three_level_scale.md) |
| Conflito              |Pode haver resistência dos usuários que não estão acostumados a criar senhas mais complexas. No entanto, a segurança é uma prioridade.|
| Historia              | 01 de nov. 2023 |

<div style="text-align: center;">
    Tabela 7: Cartão de Especificação - Interoperabilidade, Autor(a): Shaíne, 2023
</div>

| Classificação         | Interoperabilidade | 
| ----------------------|--|
| Descrição             | O Skoob deve ser capaz de interoperar com outras plataformas de redes sociais, permitindo aos usuários compartilhar conteúdo, de forma integrada e sem problemas. |
| Justificativa         | Esse requisito visa melhorar a experiência do usuário, permitindo que eles compartilhem informações sobre livros e interajam com outras plataformas sociais. Isso aumentará a visibilidade do Skoob e promoverá a interação dos usuários. |
| Origem do requisito   | RNF05|
| Critério de aceitação | O sistema deve permitir que os usuários compartilhem conteúdo do Skoob em outras plataformas de redes sociais, como Facebook, Twitter, Instagram, entre outras. |
| Prioridade            | Média prioridade.  Fonte: [TLS](./../elicitacao/three_level_scale.md) |
| Conflito              |Pode haver desafios técnicos na integração com diferentes plataformas de redes sociais, mas os benefícios de interoperabilidade são significativos.|
| Historia              | 04 de nov. 2023 |

<div style="text-align: center;">
    Tabela 8: Cartão de Especificação - Interoperabilidade, Autor(a): Ana, 2023
</div>

## NFR-3 Segurança

### Requisito de Segurança

| ID  | Requisito |
|-----|-----------|
|RNF03| A senha deve conter no mínimo um número uma letra maiúscula e um caracter especial|
|RNF04| Os dados do usuário devem ser guardados de forma eficaz, impendindo o vazamento dos mesmos|

<div style="text-align: center;">
    Tabela 9: Requisito de Segurança, Autor(a): Shaíne e Ana, 2023
</div>

### Sem Propagação

<div style="text-align: center;">
    <img src="../img/seguranca_semPropagacao.png" alt="image" width="500"/>
</div>

<div style="text-align: center;">
    Figura 7: NFR-3 Segurança, Autor(a): Shaíne e Ana, 2023
</div>

### Com Propagação

<div style="text-align: center;">
    <img src="../img/seguranca_comPropagacao.png" alt="image" width="500"/>
</div>
 
<div style="text-align: center;">
    Figura 8: NFR-3 Segurança com Propagação, Autor(a): Shaíne  e Ana, 2023
</div>

### Cartões de Especificação

| Classificação         | Segurança | 
| ----------------------|--|
| Descrição             | As senhas dos usuários devem atender aos seguintes critérios: conter no mínimo um número, pelo menos uma letra maiúscula e pelo menos um caractere especial. |
| Justificativa         | Esses critérios de senha são essenciais para aumentar a segurança das contas de usuário. A inclusão de um número, uma letra maiúscula e um caractere especial torna as senhas mais robustas, reduzindo o risco de violações de segurança e acessos não autorizados.|
| Origem do requisito   | RNF03|
| Critério de aceitação |O sistema deve validar todas as senhas inseridas pelos usuários para garantir que elas atendam aos critérios de pelo menos um número, uma letra maiúscula e um caractere especial. |
| Prioridade            | Alta prioridade.  Fonte: [TLS](./../elicitacao/three_level_scale.md) |
| Conflito              | Alguns usuários podem achar esse requisito de senha complexo ou difícil de lembrar, mas a segurança é fundamental. |
| Historia              | 01 de nov. 2023 |

<div style="text-align: center;">
    Tabela 10: Cartão de Especificação - Segurança, Autor(a): Shaíne, 2023
</div>

| Classificação         | Segurança | 
| ----------------------|--|
| Descrição             | Os dados do usuário devem ser armazenados de forma eficaz para evitar qualquer vazamento de informações. |
| Justificativa         | Garantir a eficácia no armazenamento dos dados é crucial para proteger a privacidade e a segurança dos usuários, prevenindo vazamentos indesejados.|
| Origem do requisito   | RNF04|
| Critério de aceitação |O sistema deve implementar práticas de segurança robustas para garantir que os dados do usuário sejam protegidos contra acessos não autorizados ou vazamentos. |
| Prioridade            | Alta prioridade.  Fonte: [TLS](./../elicitacao/three_level_scale.md) |
| Conflito              | Medidas de segurança adicionais podem aumentar a complexidade do sistema, mas são essenciais para proteger a integridade dos dados. |
| Historia              | 04 de nov. 2023 |

<div style="text-align: center;">
    Tabela 11: Cartão de Especificação - Segurança, Autor(a): Ana, 2023 
</div>

### Conclusão

Com a aplicação do NFR framework ao Skoob, através da análise dos softgoals, foi estabelecida uma hierarquia de prioridades, garantindo que os aspectos como segurança, portabilidade e interoperabilidade sejam devidamente atendidos acerca dos [requisitos não funcionais](https://requisitos-de-software.github.io/2023.2-Skoob/elicitacao/requisitos/), permitindo a definição de critérios de aceitação específicos para cada requisito, assegurando que as metas de qualidade identificadas na [Especificação Suplementar](especificacao_suplementar.md) sejam alcançadas de forma eficaz, resultando em uma experiência mais segura e eficiente para os usuários.

## Referências

<a id="aa" href="#a">[1]</a> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, 2019. Disponível em: [Aprender](https://aprender3.unb.br/pluginfile.php/2692835/mod_resource/content/2/DISSERTA%C3%87%C3%83O%20Reinaldo%20Ant%C3%B4nio%20da%20Silva.pdf). Acesso em: 1 nov. 2023.</br>
<a id="bb" href="#a">[2]</a> Requisitos Não-Funcionais. [s.l.: s.n., s.d.]. Disponível em: [Requirements Engineering Introduction](https://www.cin.ufpe.br/~if716/arquivos20152/experimentoBruno/Aula2/Aula2-Parte2-NFR%20Framework.pdf). Acesso em: 1 nov. 2023.</br>

## Histórico de versão

| Versão | Data | Data prevista de revisão | Descrição| Autor(es) | Revisado
|--|--|--|--|--|--|
|`1.0` | 01/11/2023 | 02/11/2023  | Criação da documentação| [Shaíne](https://github.com/ShaineOliveira) | <input type="checkbox" disabled checked /> |
|`1.1` | 02/11/2023 | 03/11/2023  | Atualização e correção | [Ana Caroline](https://github.com/anaaroch) |     |
|`1.2` | 04/11/2023 | 05/11/2023  | Incrementando o artefato | [Ana Caroline](https://github.com/anaaroch) |     |

### Revisão (V&V)
| Data de Revisão | Cobertura de Versões  |          Técnica         |                  Revisor(es)                  |
| :------------: | :-------------: | :--------------------------: |  :----------------------------------------: |
|   02/11/2023   |    `1.0`    |    Revisão por inspeção    |  [Ana Rocha](https://github.com/anaaroch) |

