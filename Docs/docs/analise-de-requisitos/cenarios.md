---
sidebar_position: 4
---

# Cenários

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

## Introdução

De acordo com Rosson e Carroll (2002)<sup>[1](../analise-de-requisitos/cenarios.md#referência-bibliográfica)</sup>, cenários são narrativas que descrevem pessoas realizando atividades em um determinado contexto. Eles representam histórias detalhadas sobre o uso de uma aplicação, envolvendo os usuários, seus objetivos, os processos que executam e os dados com os quais interagem. Essas narrativas podem ser textuais ou pictóricas, e têm como propósito capturar requisitos, entender a atividade do usuário, explorar soluções de design e avaliar a eficácia de um produto.

Os cenários são fundamentais em diversas fases do processo de design, pois oferecem uma maneira de descrever e entender como os usuários interagem com um sistema, permitindo que a equipe de design tome decisões informadas sobre funcionalidades e usabilidade. Além disso, os cenários são ferramentas mais acessíveis e econômicas em comparação com protótipos complexos, tornando-os um recurso valioso em projetos de Interação Humano Computador (IHC).

## Metodologia

A metodologia adotada para a construção dos cenários seguiu uma abordagem detalhada e analítica, com o objetivo de fornecer uma compreensão profunda das interações dos usuários com o sistema. A elaboração dos cenários foi fundamentada na literatura, especialmente nas diretrizes de Rosson e Carroll (2002), que destacam a importância de cenários ricos e detalhados para o processo de design de interfaces.

Para garantir a riqueza dos cenários e permitir uma análise abrangente, foram utilizadas perguntas refinadoras, adaptadas de Silveira et al. (2004) e Aureliano (2007), conforme apresentado por Simone Barbosa (2010)<sup>[2](../analise-de-requisitos/cenarios.md#referência-bibliográfica)</sup> no livro Interação Humano-Computador. Essas perguntas abordam diferentes elementos do cenário (objetivo, ambiente, ator, planejamento, ação, evento e avaliação), com o intuito de explorar as variáveis que afetam as interações e identificar as necessidades e dificuldades dos usuários.

Além disso, a metodologia foi complementada pela adaptação do modelo de cenários proposto pelo grupo do Banco Central (2023)<sup>[3](../analise-de-requisitos/cenarios.md#referência-bibliográfica)</sup>, que proporcionou uma visão mais focada nas especificidades do sistema em questão. Essa adaptação permitiu integrar uma análise mais contextualizada, que foi fundamental para a construção dos cenários no projeto.

### Modelo Utilizado

Neste projeto, foi adotada uma combinação de modelos para a construção dos cenários, com o objetivo de integrar diferentes perspectivas e oferecer uma análise mais completa das interações dos usuários. O modelo do grupo do Banco Central foi utilizado como base inicial, com seus elementos: Objetivo, Contexto, Recursos, Ator, Episódios, Restrições e Exceção. Este modelo é eficiente para estruturar os cenários de forma clara e concisa, destacando os aspectos fundamentais do processo de interação.

Para enriquecer a análise e explorar em detalhes as nuances do comportamento dos usuários, incorporamos o modelo de Simone Barbosa, que inclui Objetivo, Ambiente, Atores, Planejamento, Ação, Evento e Avaliação, com base nas perguntas refinadoras propostas pela autora. Este modelo permitiu uma exploração mais profunda das variáveis contextuais, das decisões dos usuários e dos resultados das interações.

A combinação desses dois modelos resultou em uma estrutura abrangente, que inclui elementos como Objetivo, Contexto/Ambiente, Recursos, Ator(es), Episódios/Planejamento, Ações, Eventos, Restrições, Exceção e Avaliação, proporcionando tanto uma visão geral do processo quanto uma análise detalhada das interações, desafios e necessidades dos usuários:

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Tabela 1</b> - Modelo para Construção de Cenários</p>

| Elemento | Descrição |
|:---:|---|
| Objetivo | Defina o objetivo principal do cenário, ou seja, o que o ator deseja alcançar ou realizar ao interagir com o sistema. |
| Contexto/Ambiente | Descreva o ambiente no qual a interação ocorre, incluindo o local, condições e qualquer fator externo relevante. |
| Recursos | Liste os recursos envolvidos na interação, como dispositivos, ferramentas ou apoio de outras pessoas. |
| Ator(es) | Defina quem são os usuários ou participantes envolvidos no cenário, suas características e necessidades específicas relacionadas à interação. |
| Episódios/Planejamento | Descreva as etapas ou ações que o ator realiza durante a interação, como um fluxo de atividades ou passos necessários para alcançar o objetivo. |
| Ações | Detalhe as ações específicas que o ator realiza para interagir com o sistema, incluindo como ele as executa e quaisquer dificuldades que possam surgir. |
| Eventos | Identifique os eventos que iniciam ou finalizam a interação ou que ocorrem como resultado das ações dos atores, como mudanças de estado ou mensagens do sistema.|
| Restrições | Liste as limitações ou obstáculos que podem afetar o desempenho da interação, como limitações tecnológicas ou de acesso, e dificuldades do usuário. |
| Exceção | Descreva possíveis cenários atípicos ou exceções, como erros ou condições imprevistas que podem alterar o fluxo normal da interação. |
| Avaliação | Explique como o ator percebe o sucesso da interação, como ele sabe que o objetivo foi alcançado, e quais são os resultados ou efeitos da interação. |

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Weverton Rodrigues](https://github.com/vevetin)<br/>Fonte: Adaptação do modelo de Simone Barbosa (2010) e repositório colaborativo do grupo [2023.1 - Banco Central](https://interacao-humano-computador.github.io/2023.1-BancoCentral/#/analise_requisitos/cenarios?id=modelo-de-cen%c3%a1rio)</p>

## Cenários Identificados

<Tabs>
  <TabItem value="C01" label="Cenário 01" default>
    <p style={{ textAlign: 'center', fontSize: '20px' }}><b>Tabela 2</b> - Cenário de Agendamento de Consulta Médica para Dona Lúcia</p>

        |Elemento| Descrição |                     
        |:---:|---|
        | Objetivo | Agendar uma consulta médica para Dona Lúcia em um serviço público de saúde, garantindo simplicidade e acessibilidade. Dona Lúcia precisa selecionar o tipo de consulta, horário e data disponíveis, além de obter a confirmação do agendamento.|
        | Contexto/Ambiente | Dona Lúcia, uma senhora de 68 anos, aposentada e com dificuldades para navegar em sites, precisa realizar o agendamento em casa, utilizando um computador com acesso à internet. Ela depende de ajuda de familiares devido à pouca familiaridade com tecnologia. O site deve oferecer uma interface acessível e intuitiva. |
        | Recursos | - Computador com acesso à internet;<br/>- Site da prefeitura (seção de agendamento de consultas);<br/>- Suporte de familiares (como os netos) para navegação e preenchimento de informações; |
        | Ator(es)    | 	Dona Lúcia, com 68 anos, aposentada, limitada em conhecimentos tecnológicos, mas motivada a cuidar de sua saúde. Conta com a ajuda de netos para navegar no site e concluir o agendamento.                                        |
        | Episódios/Planejamento | 1. Dona Lúcia acessa o site da prefeitura no computador com o auxílio do neto;<br/>2. Navega para a seção de saúde e escolhe a opção de "Agendamento de Consultas";<br/>3. O site apresenta um formulário simples com uma seção para dados básicos e outra para a seleção de especialidade, horário, data e UBS disponível;<br/>4. Com a ajuda do neto, preenche o formulário e seleciona as opções desejadas;<br/>5. Após enviar as informações, o sistema exibe uma confirmação na tela e gera um comprovante de agendamento;<br/>6. Dona Lúcia (ou o neto) clica no botão "Baixar comprovante", escolhe o local para salvar o arquivo e confirma o download;  |
        | Ações | - Navegar até a seção correta do site;<br/>- Preencher os campos obrigatórios no formulário de agendamento;<br/>- Confirmar as informações e enviar os dados;<br/>- Baixar e salvar o comprovante de agendamento. |
        | Eventos | - A necessidade de uma consulta médica de rotina motiva o agendamento;<br/>- A conclusão do agendamento gera uma confirmação visual na tela e a opção de baixar o comprovante;<br/>- O comprovante é armazenado no dispositivo do usuário. |
        | Restrições| - O sistema deve ser responsivo e acessível, permitindo ajustes de tamanho de fonte e alto contraste;<br/>- Dona Lúcia pode ter dificuldades em lidar com menus complexos ou termos técnicos no formulário. |
        | Exceção | - Caso Dona Lúcia não tenha internet, o agendamento precisa ser feito via telefone ou presencialmente;<br/>- Informações incorretas no formulário podem levar à rejeição do agendamento;<br/>- Caso Dona Lúcia não consiga salvar o comprovante, pode ser necessário acessar a seção de histórico no site para recuperá-lo. |
        | Avaliação | Dona Lúcia sabe que o objetivo foi alcançado ao visualizar a confirmação do agendamento na tela e salvar o comprovante no dispositivo com sucesso. |

   <p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Weverton Rodrigues](https://github.com/vevetin)</p>
  </TabItem>
</Tabs>

<Tabs>
  <TabItem value="C02" label="Cenário 02" default>
    <p style={{ textAlign: 'center', fontSize: '20px' }}><b>Tabela 3</b> - Cenário: Consulta e Download de Editais de Licitação para Leonardo Almeida</p>

        |Elemento| Descrição |                     
        |:---:|---|
        | Objetivo |Leonardo deseja acessar rapidamente editais de licitação relevantes ao setor de varejo para identificar oportunidades de fornecimento de uniformes para uma instituição pública local.|
        | Contexto/Ambiente | Leonardo está em seu escritório, usando um computador com acesso à internet. Ele acessa o site oficial da prefeitura de Nova Iorque-MA durante uma pausa entre reuniões com sua equipe. |
        | Recursos | - Computador com acesso à internet;<br/>- Site da prefeitura (seção de licitações e contratos)|
        | Ator(es)    | 		Leonardo Almeida, empresário do setor de varejo, com habilidades intermediárias em tecnologia e conhecimento básico sobre licitações.                                        |
        | Episódios/Planejamento | 1. Leonardo abre o navegador e acessa o site da prefeitura.;<br/>2. Ele procura pela seção de licitações e editais;<br/>3. Identifica os documentos relacionados a fornecimento de bens ou serviços para sua área.<br/>4. Utiliza dos filtros disponiveis para buscar o edital desejado<br/>5. Realiza o download dos arquivos selecionados para análise detalhada. <br/>  |
        | Ações | - Acessa o site oficial (https://www.novaiorque.ma.gov.br/);<br/>- Navega pelo menu principal até localizar "Licitações e Contratos";<br/>- Filtra os editais por data ou categoria. <br/>- Clica em um botão de download para salvar os arquivos em PDF no computador. |
        | Eventos | -Leonardo encontra uma lista de editais com descrições.;<br/>- Leonardo encontra um edital relevante e consegue realizar o download.;<br/>- O edital é armazenado no dispositivo de Leonardo.|
        | Restrições| - O sistema deve ser responsivo e acessível, permitindo ajustes de tamanho de fonte e alto contraste;<br/>- A conexão com o site pode prejudicar o download do edital; <br/> Editais podem estar organizados de maneira confusa ou em formatos não compatíveis com os softwares que Leonardo utiliza.|
        | Exceção | -  O site pode estar fora do ar ou apresentar erro ao acessar a seção de licitações.;<br/>- O edital pode não conter informações claras ou estar com links quebrados para download;<br/>|
        | Avaliação | Leonardo confirma o sucesso da interação ao verificar que os editais foram baixados corretamente e contêm informações claras sobre as condições e prazos da licitação. |

   <p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Necivaldo Amaral](https://github.com/junioramaral22)</p>
  </TabItem>
</Tabs>


<Tabs>
  <TabItem value="C03" label="Cenário 03" default>
    <p style={{ textAlign: 'center', fontSize: '20px' }}><b>Tabela 4</b> - Cenário de reclamação sobre coleta de lixo para João Da Silva</p>

| Elemento | Descrição |
|:---:|---|
| Objetivo | Facilitar o uso do canal eletrônico de ouvidoria pelos cidadãos para registrar elogios, reclamações, solicitações, sugestões e denúncias.                                                                         |
| Contexto/Ambiente | O site da prefeitura apresenta uma interface pouco informativa e recursos mal localizados. A [ouvidoria digital](https://www.administracaopublica.com.br/ouvidoria?token=4f1cf16edf5d73feaad4fec2a03c7c9e1cf536aa) não conta com campos informativos para orientar um usuário em como as solicitações devem ser feitas, a parte de [perguntas e respostas](https://www.administracaopublica.com.br/ouvidoria/acompanhamento?token=4f1cf16edf5d73feaad4fec2a03c7c9e1cf536aa[) e pouco abrangente e muito geral, a página ["Fale Conosco"](https://www.novaiorque.ma.gov.br/atendimento/fale-conosco-atendimento) retorna erro 404, e o único canal de atendimento está escondido no rodapé, dificultando o acesso dos usuários. |
| Recursos | - Computador ou dispositivo móvel com acesso à internet;<br/>- [Site oficial da prefeitura](https://www.novaiorque.ma.gov.br/);<br/>- Possível suporte técnico do setor de TI da prefeitura.                       |
| Ator(es) | Usuário fictício: João da Silva, 35 anos, trabalhador autônomo com pouco conhecimento técnico, tentando registrar uma reclamação sobre a coleta de lixo em sua rua.                                              |
| Episódios/Planejamento | 1. João acessa o site da prefeitura pelo celular;<br/>2. Encontra a seção de ouvidoria no menu;<br/>3. Clica em "Canal Eletrônico", mas não entende as opções por falta de explicação;<br/>4. Nota que a página "Fale Conosco" não funciona;<br/>5. Encontra o canal de dúvidas no rodapé do site, mas não obtém resposta imediata. |
| Ações | - João tenta usar o formulário de ouvidoria;<br/>- Explora as opções de contato sem sucesso;<br/>- Desiste de registrar sua reclamação devido à dificuldade.                                                     |
| Eventos | - João acessa o site para registrar sua reclamação;<br/>- Percebe a falta de campos explicativos e recursos de ajuda no canal eletrônico;<br/>- Não consegue completar sua solicitação.                            |
| Restrições | - Ausência de uma seção de FAQ abrangente;<br/>- A página "Fale Conosco" está fora do ar (erro 404);<br/>- Canal de atendimento mal posicionado (rodapé), dificultando a usabilidade.                              |
| Exceção | - João tenta acessar o site em um horário de manutenção ou enfrenta lentidão;<br/>- O canal de atendimento no rodapé também não responde.                                                                         |
| Avaliação | João considera a experiência frustrante e conclui que o site não atende às suas necessidades, deixando de registrar sua reclamação.                                                                              |

  <p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [ Pedro Luiz](https://github.com/pedroluizfo)</p>
  </TabItem>
</Tabs>


# Referência Bibliográfica
> \- BARBOSA, Simone, et al. Interação Humano-Computador. 1. ed. Rio de Janeiro: Elsevier, 2010. 

> \- Rosson, M.B. & Carroll, J.M. Scenario-Based Development of Human-Computer Interaction. San Francisco, CA: Morgan Kaufmann Publishers, 2002.

> \-  Universidade de Brasília (UnB), Campus UnB Gama: Faculdade de Ciências e Tecnologias em Engenharia. Documentação do projeto de Interação Humano-Computador: Banco Central. Semestre 2023.1, Universidade de Brasília, Gama, 2023. Disponível em: https://interacao-humano-computador.github.io/2023.1-BancoCentral/#/. Acesso em: 6 nov. 2024.  


# Bibliografia
> \- BARBOSA, Simone, et al. Interação Humano-Computador. 1. ed. Rio de Janeiro: Elsevier, 2010. 


## Histórico de Versão
---
| Versão | Data | Autor(es) | Descrição | Data de Revisão | Revisor(es) |
|:---:|:---:|---|---|:---:|---|
| 1.0 | 30/11/2024 | [Weverton Rodrigues](https://github.com/vevetin) | criação do documento | | |
| 1.1 | 30/11/2024 | [Necivaldo Amaral](https://github.com/junioramaral22) | Adição de cenário ao documento  | | |
| 1.2 | 01/12/2024 | [Pedro Luiz](https://github.com/pedroluizfo) | Adição do cenário 3 ao documento  | | |