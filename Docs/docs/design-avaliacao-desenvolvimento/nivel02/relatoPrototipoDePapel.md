---
sidebar_position: 4
---

# Relato dos Resultados da Avaliação dos Protótipos de Papel

## Introdução

O presente documento tem como objetivo relatar os resultados obtidos durante a avaliação dos Protótipos de Papel, realizada com o intuito de identificar possíveis problemas e oportunidades de melhoria no sistema proposto. A análise foi conduzida com base no [Planejamento da Avaliação do Protótipo de Papel](./planejamentoAvaliacaoPrototipoDePapel.md) e a organização dos dados foi feita com base no [Planejamento do Relato dos Resultados da Avaliação do Protótipo de Papel](./planejamentoRelatoPrototipoDePapel.md).

## Cronograma Executado

<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Tabela 1</b> - Cronograma Executado</p>

| Entrevistador(es) | Entrevistado(s)| Horário de Início | Horário de Fim | Data Planejada | Tarefa  | Local |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| [Weverton Rodrigues](https://github.com/vevetin) | Arthur Sousa | 16:50 | 16:57 | 09/01/2025 | [Protótipo de Papel 2 - Agendamento de Consulta Médica](./prototipoDePapel.md#protótipo-de-papel-2---agendamento-de-consulta-médica) | Sala I2, UAC, Campus UnB Gama |
| [Paulo Henrique](https://github.com/paulomh) | João Artur | 10:20 | 10:30 | 13/01/2025 | [Protótipo de Papel 1 - Realizar Pedido no e-SIC](./prototipoDePapel.md#protótipo-de-papel-1---fazer-um-pedido-no-e-sic) | Sala I4, UAC, Campus UnB Gama |
| [Rodrigo Wendrel](https://github.com/rodwendrel)  | Guilherme Oliveira | 16:00 | 16:30 | 14/01/2025 | [Protótipo de Papel 4 - Busca por Licitação Fracassada](./prototipoDePapel.md#protótipo-de-papel-4---busca-por-licitação-fracassada) | Conteiner EJ, Campus UNB Gama |
| [Necivaldo Amaral](https://github.com/junioramaral22) | Ana Claudia | 19:00 | 19:10 | 14/01/2025 | [Protótipo de Papel 5 - Envio de Nota Fiscal de Serviço](./prototipoDePapel.md#protótipo-de-papel-5---envio-de-nota-fiscal-de-serviço) | Casa da entrevistada |


<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Weverton Rodrigues](https://github.com/vevetin)</p>

</center>

## Entrevista - Fazer um pedido no e-SIC

### Objetivo e âmbito da avaliação

A avaliação teve como objetivo analisar o [Protótipo de Papel 1 - Fazer um pedido no e-SIC](./prototipoDePapel.md#protótipo-de-papel-1---fazer-um-pedido-no-e-sic), visando identificar pontos de melhoria na interação e na interface, buscando aspectos relacionados à alternativas de design e problemas na interação e na interface.

### Método de avaliação

O método de avaliação utilizado foi a entrevista semiestruturada com base no [Planejamento da Avaliação do Protótipo de Papel](./planejamentoAvaliacaoPrototipoDePapel.md).
<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Tabela 2</b> - Roteiro de perguntas para Avaliação do Protótipo de Papel</p>

| Objetivo | Pergunta | Resposta |
|---|---|---|
| Ideias e Alternativas de Design | 1. Qual das alternativas de design do protótipo de papel é mais eficiente e fácil de aprender? | O entrevistado optou por seguir o fluxo de acessar o e-SIC através do ícone que encontrava-se no carrosel no centro da página inicial do protótipo ([figura 03](./prototipoDePapel.md#figura03)), visto que a opção de buscar pelo "mapa do site" exigia um esforço maior. | 
| Ideias e Alternativas de Design | 2. Qual alternativa de design os usuários preferem? Por quê? | Como mencionado anteriormente, ele preferiu acessar a página do e-sic pelo ícone presente no carrosel por ser uma opção mais rápida e eficiente.|
| Ideias e Alternativas de Design | 3. Qual alternativa de design se espera que tenha um impacto negativo menor ao ser adotada? | Durante a avaliação, o usuário não percebeu que o ícone estava presente em um carrosel no protótipo. Portanto, substituir o carrosel por um componente estático com as funcionalidades mais acessadas do site na página principal, deixando claro e evidente os botões de acesso.|
| Problemas na Interação e Interface | 4. Os usuários conseguem operar o protótipo de papel? Eles atingem seus objetivos de maneira eficiente? Com que frequência cometem erros?| Sim, o usuário conseguiu operar o protótipo de papel com certa maestria, atingindo seu objetivo de realizar um pedido no e-sic com demasiada eficiência sem cometer erros.| 
| Problemas na Interação e Interface | 5. Que parte da interface do protótipo de papel deixa os usuários insatisfeitos ou causa confusão? | Não tiveram partes que o deixaram insatisfeito. |
| Problemas na Interação e Interface  | 6. Os usuários entendem claramente o que cada elemento do protótipo de papel significa e o que devem fazer em seguida? | Sim, o usuário entendeu claramente os elementos do protótipo de papel| 

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Paulo Henrique](https://github.com/paulomh)</p>

</center>

### Avaliação Heurística

**Objetivo e método**  

Após a entrevista, foi realizada uma avaliação heurística baseada nas 10 heurísticas de Nielsen<sup>[1](./relatoPrototipoDePapel.md#referências-bibliográficas)</sup>, selecionado por sua relevância no contexto de protótipos de papel. As heurísticas analisadas foram:

- Visibilidade do status do sistema: verificar se o sistema fornece feedback adequado sobre o status das ações realizadas.
- Flexibilidade e eficiência de uso: avaliar se o sistema permite que os usuários realizem tarefas de maneira rápida e eficiente.
- Design estético e minimalista: examinar se o protótipo evita informações desnecessárias e mantém o foco nos elementos essenciais.
- Correspondência entre o sistema e o mundo real: analisar se os fluxos propostos no protótipo são familiares aos usuários.

**Resultados**

Das heurísticas analisadas, o fluxo de acessar a página do e-sic pelo "mapa do site" violou a heurística de correspondência entre o sistema e o mundo real, visto que esse fluxo não é claro e intuitivo para o usuário. Por outro lado, as demais heurísticas avaliadas foram satisfeitas, uma vez que o protótipo permite que os usuários realizem tarefas de maneira rápida e eficiente e evita informações desnecessárias, além de sempre retornar um feedback adequado para as ações executadas no protótipo, mantendo o foco nos elementos essenciais.

### Seleção dos participantes

Por motivos pessoais, o participante selecionado no [planejamento da avaliação](./planejamentoAvaliacaoPrototipoDePapel.md#cronogramaEntrevista) não pôde participar, sendo o seu substituto o entrevistado João Arthur. O participante selecionado foi o João Artur, de 21 anos, que se enquadra no grupo de [Cidadãos em Geral (faixa etária predominante: 18 a 60 anos)](../../analise-de-requisitos/perfilDeUsuario.md#conclusão). João possui experiência uma boa experiência com tecnologia, representando um usuário dessa faixa etária com familiaridade intermediária a avançada em usar interfaces digitais.

### Sugestões de melhorias

Da entrevista não houve sugestões de melhoria por parte do entrevistado. Porém, identificando a forma como o protótipo era utilizado, o entrevistado não notou a presença do carrosel na página inicial do protótipo, não interferindo na sua experiência de uso, mas evidenciando que usar esse tipo de recurso pode ofuscar demais funcionalidades. A sugestão de melhoria identificada durante a avaliação foi a substituição do carrosel por um componente estático com as funcionalidades mais acessadas do site na página principal, deixando claro e evidente os botões de acesso. Essa mudança visa facilitar o acesso do usuário às funcionalidades mais utilizadas do site, tornando a navegação mais intuitiva e eficiente. Além disso, outra sugestão de mudança por parte do avaliador seria a inclusão de um cabeçalho fixo com as funcionalidades separadas por categorias, facilitando a navegação do usuário.

### Registro da avaliação

<center>

<iframe width="560" height="315" src="https://www.youtube.com/embed/9v6sCGDIONY?si=RGC_9xD4Rg1U4Q9C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

</center>

## Entrevista - Agendamento de Consulta Médica

### Objetivo e âmbito da avaliação

A avaliação teve como objetivo analisar o [Protótipo de Papel 2 - Agendamento de Consulta Médica](./prototipoDePapel.md#protótipo-de-papel-2---agendamento-de-consulta-médica), visando identificar pontos de melhoria na interação e na interface. O âmbito da avaliação abrangeu aspectos relacionados à alternativas de design e problemas na interação e na interface.

### Método de avaliação

O método de avaliação utilizado foi a entrevista semiestruturada, acordado com o [Planejamento da Avaliação do Protótipo de Papel](./planejamentoAvaliacaoPrototipoDePapel.md).

<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Tabela 3</b> - Roteiro de perguntas para Avaliação do Protótipo de Papel</p>

| Objetivo | Pergunta | Resposta |
|---|---|:---|
| Ideias e Alternativas de Design | 1. Qual das alternativas de design do protótipo de papel é mais eficiente e fácil de aprender? | O entrevistado optou por iniciar o fluxo pela barra de pesquisa, considerando-a mais eficiente e fácil de aprender em relação ao menu horizontal. | 
| Ideias e Alternativas de Design | 2. Qual alternativa de design os usuários preferem? Por quê? |O entrevistado preferiu a barra de pesquisa em relação ao menu horizontal, pois acredita que a pesquisa direta facilita o processo e permite encontrar o que precisa de maneira mais rápida. |
| Ideias e Alternativas de Design | 3. Qual alternativa de design se espera que tenha um impacto negativo menor ao ser adotada? | Além da barra de pesquisa, outras alternativas que poderiam ter um impacto negativo menor incluem o uso de um menu simplificado com ícones, botões grandes e visíveis para ações principais. |
| Problemas na Interação e Interface | 4. Os usuários conseguem operar o protótipo de papel? Eles atingem seus objetivos de maneira eficiente? Com que frequência cometem erros?| Sim, o entrevistado conseguiu operar o protótipo com relativa facilidade, atingindo seus objetivos de maneira eficiente.| 
| Problemas na Interação e Interface | 5. Que parte da interface do protótipo de papel deixa os usuários insatisfeitos ou causa confusão? | O entrevistado não identificou partes da interface que causassem insatisfação ou confusão. Ele destacou que o protótipo estava bem claro e que qualquer pessoa, independentemente de sua experiência com tecnologia, conseguiria utilizá-lo sem dificuldades. |
| Problemas na Interação e Interface  | 6. Os usuários entendem claramente o que cada elemento do protótipo de papel significa e o que devem fazer em seguida? |O entrevistado indicou que compreendeu claramente o que cada elemento do protótipo de papel representava e as ações que deveria realizar em seguida. Ele não teve dificuldades em identificar o próximo passo durante a interação, e destacou que a navegação estava intuitiva, sem causar incertezas sobre o que fazer em cada etapa. | 

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Weverton Rodrigues](https://github.com/vevetin)</p>

</center>

### Avaliação Heurística

**Objetivo e método**  
Além da entrevista, foi realizada uma avaliação heurística baseada nas 10 heurísticas de Nielsen<sup>[1](./relatoPrototipoDePapel.md#referências-bibliográficas)</sup>, selecionado por sua relevância no contexto de protótipos de papel. As heurísticas analisadas foram:
- Correspondência entre o sistema e o mundo real: verificar se a terminologia e os fluxos apresentados no protótipo são familiares aos usuários.
- Design estético e minimalista: examinar se o protótipo evita informações desnecessárias e mantém o foco nos elementos essenciais.
- Reconhecimento em vez de memorização: confirmar se as informações necessárias estão visíveis e facilmente acessíveis no protótipo.

**Resultados**    
A avaliação heurística não identificou violações em nenhuma das heurísticas analisadas. Este resultado indica que o protótipo está em conformidade com os princípios de usabilidade estabelecidos. A ausência de problemas nesta etapa reforça que o design atual atende aos padrões de interação esperados.

### Seleção dos participantes

O participante selecionado foi Arthur Sousa, de 20 anos, que se enquadra no grupo de [Cidadãos em Geral (faixa etária predominante: 18 a 60 anos)](../../analise-de-requisitos/perfilDeUsuario.md#conclusão). Arthur possui experiência avançada com tecnologia, representando um usuário típico dessa faixa etária com familiaridade intermediária a avançada em interfaces digitais. Sua seleção foi estratégica para explorar a interação com o protótipo de papel sob a perspectiva de um usuário que, embora confortável com tecnologia, pode identificar pontos de melhoria relacionados à usabilidade e acessibilidade. Essa abordagem visa garantir que o protótipo atenda tanto às necessidades gerais quanto aos requisitos de usabilidade do público-alvo.

### Sugestões de melhorias

Nenhuma sugestão de melhoria foi identificada durante a avaliação. O protótipo de papel foi considerado claro e intuitivo pelo entrevistado, que não apontou problemas de compreensão ou dificuldades nas interações. O fluxo proposto está bem alinhado com as necessidades do usuário, e todas as informações necessárias para a execução das tarefas foram facilmente compreendidas.

### Registro da avaliação

<center>

<iframe width="560" height="315" src="https://www.youtube.com/embed/qxcZxsH1Dxg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

</center>

## Entrevista - Busca por licitação fracassada

### Objetivo e âmbito da avaliação

### Método de avaliação

<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Tabela 4</b> - Roteiro de perguntas para Avaliação do Protótipo de Papel</p>

| Objetivo | Pergunta | Resposta |
|---|---|---|

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Rodrigo Wendrel](https://github.com/rodwendrel)</p>

</center>

### Avaliação Heurística

**Objetivo e método**  

**Resultados**

<!-- incluir avaliacao heuristica, se aplicavel -->

### Seleção dos participantes

### Sugestões de melhorias

### Registro da avaliação

<center>

<iframe width="560" height="315" src="https://www.youtube.com/embed/BPNICWKYZbI?si=4eyn0pnsIgLlF9F7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

</center>

## Entrevista - Envio de Nota Fiscal de Serviço

### Objetivo e âmbito da avaliação

A avaliação teve como objetivo analisar o [Protótipo de Papel 5 - Envio de Nota Fiscal](https://interacao-humano-computador.github.io/2024.2-Prefeitura-Municipal-de-Nova-Iorque/docs/design-avaliacao-desenvolvimento/nivel02/prototipoDePapel#protótipo-de-papel-5---envio-de-nota-fiscal-de-serviço), visando identificar pontos de melhoria na interação e na interface. O âmbito da avaliação abrangeu aspectos relacionados à alternativas de design e problemas na interação e na interface.
### Método de avaliação

O método de avaliação utilizado foi a entrevista semiestruturada, acordado com o [Planejamento da Avaliação do Protótipo de Papel](./planejamentoAvaliacaoPrototipoDePapel.md).
<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Tabela 5</b> - Roteiro de perguntas para Avaliação do Protótipo de Papel</p>

| Objetivo | Pergunta | Resposta |
|---|---|:---|
| Ideias e Alternativas de Design | 1. Qual das alternativas de design do protótipo de papel é mais eficiente e fácil de aprender? | A entrevistada optou pelo menu superior | 
| Ideias e Alternativas de Design | 2. Qual alternativa de design os usuários preferem? Por quê? |A entrevistada preferiu o menu superior pela fácil identificação |
| Ideias e Alternativas de Design | 3. Qual alternativa de design se espera que tenha um impacto negativo menor ao ser adotada? | do menu superior|
| Problemas na Interação e Interface | 4. Os usuários conseguem operar o protótipo de papel? Eles atingem seus objetivos de maneira eficiente? Com que frequência cometem erros?| Sim, a entrevistada conseguiu operar o protótipo com facilidade, atingindo seus objetivos de maneira eficiente.| 
| Problemas na Interação e Interface | 5. Que parte da interface do protótipo de papel deixa os usuários insatisfeitos ou causa confusão? | Nenhuma, ficou bem claro para a entrevistada |
| Problemas na Interação e Interface  | 6. Os usuários entendem claramente o que cada elemento do protótipo de papel significa e o que devem fazer em seguida? | Sim, bem claro. | 

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Necivaldo Amaral](https://github.com/junioramaral22)</p>

</center>

### Avaliação Heurística

**Objetivo e método**  
Além da entrevista, foi realizada uma avaliação heurística baseada nas 10 heurísticas de Nielsen<sup>[1](./relatoPrototipoDePapel.md#referências-bibliográficas)</sup>, selecionado por sua relevância no contexto de protótipos de papel. As heurísticas analisadas foram:
- Correspondência entre o sistema e o mundo real: verificar se a terminologia e os fluxos apresentados no protótipo são familiares aos usuários.
- Design estético e minimalista: examinar se o protótipo evita informações desnecessárias e mantém o foco nos elementos essenciais.
- Reconhecimento em vez de memorização: confirmar se as informações necessárias estão visíveis e facilmente acessíveis no protótipo.

**Resultados**    
A avaliação heurística não identificou violações em nenhuma das heurísticas analisadas. Este resultado indica que o protótipo está em conformidade com os princípios de usabilidade estabelecidos. A ausência de problemas nesta etapa reforça que o design atual atende aos padrões de interação esperados.

<!-- incluir avaliacao heuristica, se aplicavel -->

### Seleção dos participantes
A participante selecionada foi Ana, de 51 anos, que se enquadra no grupo de [Cidadãos em Geral (faixa etária predominante: 18 a 60 anos)](../../analise-de-requisitos/perfilDeUsuario.md#conclusão). Que possui bom conhecimento com tecnologia e familiaridade com as tarefas designadas. Teve fácil entendimento do fluxo da tarefa e completou sem dificuldades.

### Sugestões de melhorias
Nenhuma sugestão de melhoria foi descrita. A entrevistada teve claro entendimento da tarefa e como realiza-la no protótipo de papel.

### Registro da avaliação

<center>

<iframe width="560" height="315" src="https://www.youtube.com/embed/_SLnLHSkmKY?si=ruSV-x5XdHcv2Py3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

</center>

## Planejamento de reprojeto

<center>
<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Tabela 6</b> - Cronograma do Reprojeto.</p>

| Executador | Horário de Início | Horário de fim | Data |
|:---:|:---:|---|---|
</center>

## Referências Bibliográficas

> 1. BARBOSA, Simone Diniz Junqueira et al. Interação humano-computador e experiência do usuário. 1. ed. Rio de Janeiro: Simone Diniz Junqueira Barbosa, 2021. Capítulo 12: Métodos de Avaliação de IHC. Páginas 281-286. Autopublicação. ISBN: 978-65-00-19677-1.

## Histórico de Versão

| Versão | Data | Autor(es) | Descrição | Data de Revisão | Revisor(es) |
|:---:|:---:|---|---|:---:|---|
| 1.0 | 12/01/2025 | [Weverton Rodrigues](https://github.com/vevetin) | Criação do documento | 12/01/2025 | [Paulo Henrique](https://github.com/paulomh) |
| 1.1 | 14/01/2025 | [Necivaldo Amaral](https://github.com/junioramaral22) | Adição de relato prototipo envio nota fiscal | 12/01/2025 | [Weverton Rodrigues](https://github.com/vevetin) |
| 1.2 | 14/01/2025 | [Paulo Henrique](https://github.com/paulomh) | Adição de relato prototipo fazer um pedido no e-sic | 12/01/2025 | [Necivaldo Amaral](https://github.com/junioramaral22) |