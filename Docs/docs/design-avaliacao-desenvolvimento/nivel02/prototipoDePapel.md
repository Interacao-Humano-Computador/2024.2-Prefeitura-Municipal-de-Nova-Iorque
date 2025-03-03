---
sidebar_position: 1
---

# Protótipos de Papel

## Introdução

Protótipo é uma representação limitada de um design que permite aos usuários interagir com ele e explorar a sua conveniência<sup>[1](./prototipoDePapel.md#referências-bibliográficas)</sup>. Protótipos respondem a questões e fornecem suporte aos designers para a escolha de uma dentre as várias opções. Portanto, servem para vários fins: por exemplo, testar a viabilidade técnica de uma ideia, esclarecer requisitos vagos, realizar testes com usuários e avaliações, ou verificar se um design é compatível com o resto do desenvolvimento do sistema<sup>[2](./prototipoDePapel.md#referências-bibliográficas)</sup>.

Um protótipo de baixa-fidelidade é aquele que não se assemelha muito ao produto final, utilizando materiais muito diferentes da versão final pretendida, como papel e cartolina, ao invés de telas eletrônicas, por exemplo. Eles são úteis devido a sua simplicidade, baixo custo e velocidade na produção. Isso significa que protótipos de baixa-fidelidade podem ser rapidamente modificados, possibilitando a exploração de ideias alternativas e novos tipos de design<sup>[3](./prototipoDePapel.md#referências-bibliográficas)</sup>. 

O protótipo de papel é uma técnica de prototipação de baixa-fidelidade que consiste em desenhar a interface de um sistema em folhas de papel, simulando a interação do usuário com o sistema. O protótipo de papel é uma técnica de baixo custo e de fácil aplicação, que permite testar a usabilidade de um sistema de forma rápida e eficiente.

## Objetivo

Com base no nível 02 de design, avaliação e desenvolvimento do processo de design da [Engenharia de Usabilidade de Mayhew](../../planejamento/processosDeDesign.md#engenharia-de-usabilidade-de-mayhew), o objetivo deste documento é apresentar os protótipos de baixa-fidelidade desenvolvidos utilizando a técnica de protótipo de papel das tarefas selecionadas, por cada membro, do site da Prefeitura Municipal de Nova Iorque.

## Metodologia

Utilizando os [storyboards](../nivel01/Storyboard/storyboards.md) e [diagramas das análises de tarefas](../../analise-de-requisitos/analiseTarefas.md) como base, seguindo a técnica de prototipação em papel, cada membro se responsabilizou em desenvolver seu respectivo protótipo seguindo a tarefa específica selecionada do site.

## Protótipos

### Protótipo de Papel 1 - Fazer um pedido no e-SIC

Baseado no [diagrama HTA - Realizar Pedido no e-SIC](../../analise-de-requisitos/analiseTarefas.md#tarefa-01---realizar-pedido-no-e-sic) e tendo como base o objetivo do [storyboard - Fazer um pedido no e-SIC](../nivel01/Storyboard/storyboards.md#storyboard-1---fazer-um-pedido-no-e-sic), foi desenvolvido o protótipo de papel para a tarefa de fazer um pedido no e-SIC. Começando pela tela inicial do site.

<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Figura 1</b> - Tela inicial do protótipo</p>

![](./assets/prototipoTelaInicialPaulo.jpg)

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Paulo Henrique](https://github.com/paulomh)</p>

</center>

Na tela inicial, há duas formas de se acessar o e-SIC: por meio do "Mapa do Site" no canto superior direito ou pelo carrosel no qual se localiza a opção "Cidadão / e-SIC". Ao clicar na opção "Mapa do Site", uma pequena janela se abre com as opções de acesso ao e-SIC. 

<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Figura 2</b> - Tela inicial do protótipo com o mapa do site aberto</p>

![](./assets/prototipoTelaInicialMapaPaulo.jpg)

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Paulo Henrique](https://github.com/paulomh)</p>

</center>
<a id="figura03"></a>
Ao passar o mouse sobre a opção "Cidadão / e-SIC" no carrosel, surgirá uma extensão com as opções de acesso ao e-SIC. 

<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Figura 3</b> - Tela inicial do protótipo com extensão de acesso ao e-SIC</p>

![](./assets/prototipoTelaInicialPopUpPaulo.jpg)

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Paulo Henrique](https://github.com/paulomh)</p>

</center>

Ambas opções levam para a página do e-SIC. Nesta página, há a possibilidade de fazer um pedido ou consultar um pedido já realizado através de um protocolo. Além disso, há também informações úteis sobre onde fazer um pedido presencialmente, explicação da lei de acesso à informação, prazo de resposta por parte da prefeitura e uma tabela mostrando o os pedidos e eventuais respostas.

<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Figura 4</b> - Tela do e-SIC no protótipo</p>

![](./assets/prototipoTelaESicPaulo.jpg)

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Paulo Henrique](https://github.com/paulomh)</p>

</center>

Ao passar o mouse sobre a opção "Pedido de Informação", surgirá uma extensão com três opções: "Entrar", "Cadastrar" e "Pedido Anônimo". Ao clicar em "Cadastrar", o usuário será redirecionado para a página de cadastro. Ao clicar em "Pedido Anônimo", o usuário será redirecionado para o formulário de pedido de forma anônima.

<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Figura 5</b> - Tela do e-SIC no protótipo com extensão do pedido de informação</p>

![](./assets/prototipoPedidoInfoPaulo.jpg)

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Paulo Henrique](https://github.com/paulomh)</p>

</center>

#### Fluxo Alternativo - "Entrar"

Ao clicar em "Entrar", o usuário será redirecionado para a página de login. Nela o usuárrio inserirá seu email e senha e clicará em "Login". Caso o usuário não tenha cadastro, ele poderá clicar em "Cadastrar" para ser redirecionado para a página de cadastro.

<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Figura 6</b> - Tela de login do protótipo</p>

![](./assets/prototipoTelaLoginPaulo.jpg)

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Paulo Henrique](https://github.com/paulomh)</p>

</center>

Feito o login, o usuário será redirecionado para a página com o formulário de pedido. Na página do formulário de pedido, o usuário preencherá os campos de "Resumo" e "Detalhamento da Solicitação", obrigatórios, e selecionar a "Unidade Desejada" que é opcional.

<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Figura 7</b> - Tela de solicitação de pedido do protótipo</p>

![](./assets/prototipoTelaSolicitacaoPaulo.jpg)

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Paulo Henrique](https://github.com/paulomh)</p>

</center>

#### Fluxo Alternativo - "Cadastrar"

Caso o usuário clique em "Cadastrar", ele será redirecionado para a página de cadastro. Nela, o usuário preencherá os campos de "CPF ou CNPJ", "Nome Completo", "Data de Nascimento", "Sexo", "Escolaridade", "Telefone", "Email" e "Senha" e clicará em "Cadastrar". Caso o usuário já tenha cadastro, ele poderá clicar em "Entrar" para ser redirecionado para a página de login.

<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Figura 8</b> - Tela de cadastro do protótipo</p>

![](./assets/prototipoTelaCadastroPaulo.jpg)

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Paulo Henrique](https://github.com/paulomh)</p>

</center>

Após clicar em "Cadastrar", o usuário receberá uma confirmação de cadastro e logo em seguida será redirecionado para a página do e-SIC. Após o cadastro, o [fluxo alternativo - "Entrar"](#fluxo-alternativo---entrar) será seguido.

#### Fluxo Alternativo - "Pedido Anônimo"

Ao clicar em "Pedido Anônimo", o usuário será redirecionado para o formulário de pedido de forma anônima. Neste formulário, o usuário preencherá os campos de "Reside no Muncípio", "Sexo", "Escolaridade", "Faixa Etária", opcionais, "Resumo", "Detalhamento da Solicitação", obrigatórios e a "Unidade Desejada" que é opcional. Após preencher os campos, o usuário clicará em "Enviar".

<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Figura 9</b> - Tela de solicitação de pedido anônimo do protótipo</p>

![](./assets/prototipoTelaSolicitacaoAnomPaulo.jpg)

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Paulo Henrique](https://github.com/paulomh)</p>

</center>

Após clicar em "Enviar", o pedido será registrado e aparecerá uma janela de confirmação da realização do pedido na qual há um botão "Continuar" que redirecionará o usuário para a página do e-SIC com o pedido registrado.

<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Figura 10</b> - Tela de solicitação de pedido realizado</p>

![](./assets/prototipoPedidoRealizadoPaulo.jpg)

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Paulo Henrique](https://github.com/paulomh)</p>

</center>

<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Figura 11</b> - Tela do e-SIC no protótipo com o pedido realizado</p>

![](./assets/prototipoTelaESicPedidoFeitoPaulo.jpg)

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Paulo Henrique](https://github.com/paulomh)</p>

</center>

### Protótipo de Papel 2 - Agendamento de Consulta Médica

Baseando-se na  [análise CMN-GOMS detalhada - Agendar consulta médica no site da prefeitura](../../analise-de-requisitos/analiseTarefas.md#análise-cmn-goms-detalhado) e no [Storyboard 2 - Agendamento de Consulta Médica para Dona Lúcia](../nivel01/Storyboard/storyboards.md#storyboard-2---agendamento-de-consulta-médica-para-dona-lúcia), o protótipo de papel foi desenvolvido para representar de forma visual e interativa o fluxo de agendamento de consultas médicas no site da prefeitura.
O protótipo de papel consiste em duas telas principais, detalhadas a seguir:  

**Tela Inicial:**
 - Um menu suspenso localizado no menu horizontal, onde o usuário pode selecionar a opção "Saúde" para acessar a funcionalidade de agendamento.
 - Uma barra de pesquisa, permitindo buscar diretamente pelo termo "agendamento de consultas".

**Tela de Formulário:**   
- Dados Pessoais: Nome completo, CPF, e número do CNS, com preenchimento automático para usuários logados.
- Endereço: CEP, cidade, UF e logradouro.
- Detalhes do Agendamento: Menu suspenso para especialidade, data, horário e um mapa interativo para escolha da UBS.

Além disso, a interação do usuário é simplificada pelos botões "Cancelar" e "Salvar" inicialmente. Após salvar, novos botões (como "Baixar", "Imprimir", "Editar" e "Excluir") são adicionados para oferecer mais opções de gerenciamento.

#### Fluxos Alternativos e Modais
- Se o usuário optar por cancelar o preenchimento, ele será redirecionado à tela inicial.
- Ao salvar o agendamento, um modal é exibido com resumo do agendamento e opções para baixar, imprimir ou fechar.
- Caso o usuário exclua um agendamento, um modal de confirmação aparece com a opção de cancelar ou confirmar a exclusão.

<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Figura 12</b> - Protótipo de Papel: Agendamento de Consulta Médica</p>

![protótipo de papel: agendamento de consulta médica para dona Lúcia](./assets/prototipo-de-papel-Weverton.jfif)

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Weverton Rodrigues](https://github.com/vevetin)</p>

</center>

### Protótipo de Papel 3 - Registro de reclamação na ouvidoria

Baseado na análise de tarefas GOMS para "[Abrir uma nova solicitação no canal de ouvidoria virtual](https://marvelapp.com/prototype/71404f5)", foi desenvolvido o protótipo de papel que representa as etapas do processo.

#### Tela Inicial
Na tela inicial, o usuário tem três métodos principais para acessar o canal de ouvidoria:

Navegando pelo carrossel de ícones:
O usuário identifica o carrossel na página principal e localiza o ícone da ouvidoria visualmente.
<p style={{ textAlign: 'center', fontSize: '17px' }}><b>Figura 13</b> - Página principal </p>
    <center>
        ![pp4](./assets//pp4.jpg)
    </center>
<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Pedro Luiz](https://github.com/pedroluizfo)</p>

Posicionando o mouse diretamente sobre o ícone da ouvidoria:
Quando o usuário encontra o ícone da ouvidoria diretamente, uma descrição é exibida ao passar o mouse, indicando a funcionalidade antes de clicar.
<p style={{ textAlign: 'center', fontSize: '17px' }}><b>Figura 14</b> - Menu suspenso </p>
    <center>
        ![PP004](./assets//PP004.jpg)
    </center>
<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Pedro Luiz](https://github.com/pedroluizfo)</p>

Selecionando o link direto para o canal eletrônico de acesso:
O usuário, já familiarizado com o site, localiza rapidamente o link "Canal Eletrônico de Acesso" na página inicial e clica para acessar a ouvidoria.


#### Página da Ouvidoria Virtual
Ao acessar a seção da ouvidoria virtual, o usuário tem a opção de preencher uma nova solicitação ou acompanhar uma solicitação existente.
<p style={{ textAlign: 'center', fontSize: '17px' }}><b>Figura 15</b> - Página da ouvidoria </p>
    <center>
        ![pp04](./assets//pp04.jpg)
    </center>
<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Pedro Luiz](https://github.com/pedroluizfo) </p>
Nova solicitação:
O usuário clica em "Nova Solicitação" e é redirecionado para o formulário de manifestação.


Acompanhamento de solicitação existente:
O usuário pode inserir o código de acompanhamento na seção dedicada e visualizar o status de sua solicitação.


Formulário de Manifestação
Ao acessar o formulário, o usuário segue as etapas abaixo:

Preenchimento de informações pessoais:
O formulário exibe os campos obrigatórios: Nome, E-mail, Telefone, Endereço, Bairro, Cidade e UF. O usuário insere as informações manualmente.


Seleção do tipo de manifestação:
O usuário seleciona a natureza da manifestação (Elogio, Reclamação, Solicitação, Sugestão ou Denúncia) em um menu suspenso.

Descrição da manifestação:
O usuário localiza o campo de texto, insere os detalhes da solicitação e escolhe se deseja que a manifestação seja pública ou anônima.

Confirmação e Código de Acompanhamento
Após revisar todos os dados preenchidos:

O usuário clica no botão "Enviar".
Uma mensagem de confirmação é exibida com o código de acompanhamento gerado automaticamente.
O código pode ser anotado para acompanhamento futuro.
<p style={{ textAlign: 'center', fontSize: '17px' }}><b>Figura 16</b> - Página da ouvidoria </p>
    <center>
        ![PP0004](./assets//PP0004.jpg)
    </center>
<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Pedro Luiz](https://github.com/pedroluizfo) </p>

#### Fluxo Alternativo - Acompanhamento de Solicitações
Caso o usuário já tenha um código de acompanhamento, ele pode seguir o fluxo abaixo:

Acessa a página de "Acompanhamento de Solicitações".
Insere o código no campo apropriado e clica em "Buscar".
Visualiza o status da solicitação.
(Imagem: Página de acompanhamento com campo preenchido e status exibido)
Esse protótipo em papel visa facilitar a validação do design e a experiência do usuário em cada etapa do processo.

### Protótipo de Papel 4 - Busca por licitação fracassada

Baseado no [diagrama HTA - Licitações desertas ou fracassadas](../../analise-de-requisitos/analiseTarefas.md#tarefa-03---acessar-informações-de-licitações-desertas-ou-fracassadas) e tendo como base o objetivo do [Storyboard - Busca por licitações fracassadas  ](../nivel01/Storyboard/storyboards.md#storyboard-5-busca-por-licitação-fracassada).

<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Figura 17</b> - Tela inicial do protótipo</p>

![](./assets/prototipoRodrigo1.jpeg)

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Rodrigo Wendrel](https://github.com/rodwendrel)</p>

</center>

Na tela inicial, é possível visualizar o carrossel onde o usuário pode buscar pela opção de licitações. Ao selecionar esta opção, um menu de buscas aparece
várias categorias de licitações aparecem. No caso, buscamos as fracassadas

<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Figura 18</b> - Tela de licitações </p>

![](./assets/prototipoRodrigo2.jpeg)

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Rodrigo Wendrel](https://github.com/rodwendrel)</p>

</center>

Nesta tela, temos os filtros de ano, modalidade, status e unidade sendo que, estes possuem um menu com mais opções. Também temos uma busca pelo número da licitação. Ao adicionar os filtros, as licitações correspondentes aparecem e é possível clicar em detalhes para ver tudo sobre a licitação escolhida.
<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Figura 19</b> - Tela de detalhes </p>

![](./assets/prototipoRodrigo3.jpeg)

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Rodrigo Wendrel](https://github.com/rodwendrel)</p>

</center>

Então, os detalhes são exibidos, é possível visualizar os documentos da licitação e fazer o download no formato desejado. Então, um pop-up de sucesso é exibido.

### Protótipo de Papel 5 - Envio de Nota Fiscal de Serviço
Baseado no [diagrama HTA - Envio de Nota Fiscal de Serviço](https://interacao-humano-computador.github.io/2024.2-Prefeitura-Municipal-de-Nova-Iorque/docs/analise-de-requisitos/analiseTarefas#tarefa-04---consulta-e-envio-de-nota-fiscal-eletr%C3%B4nica-no-site-da-prefeitura) e tendo como base o objetivo do [Storyboard - Envio de Nota Fiscal de Serviço  ](https://interacao-humano-computador.github.io/2024.2-Prefeitura-Municipal-de-Nova-Iorque/docs/design-avaliacao-desenvolvimento/nivel01/Storyboard/storyboards#storyboard-3-envio-de-nota-fiscal-de-servi%C3%A7o)

<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Figura 20</b> - Tela inicial do protótipo</p>

![](./assets/prototipoInicialNecivaldo.jpg)

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Necivaldo Amaral](https://github.com/junioramaral22)</p>

</center>
Na tela inicial, há duas formas de acessar as notas fiscais de serviço: por meio do menu superior na opção NFS-E e pelas listadas em empresas no canto inferior esquerdo.

<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Figura 21</b> - Tela inicial do protótipo com menu dropdown</p>

![](./assets/prototipoInicial2Necivaldo.jpg)

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Necivaldo Amaral](https://github.com/junioramaral22)</p>

</center>

Ao passar o mouse por cima da opção NFS-E o usuario pode escolher entre as opções: 1. Emitir nota fiscal, 2. Consultar nota fiscal.

<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Figura 22</b> - Tela de Login</p>

![](./assets/prototipoNecivaldoLogin.jpg)

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Necivaldo Amaral](https://github.com/junioramaral22)</p>

</center>

Para realizar uma das funções da nota fiscal de serviço o usuario deve logar no sistema ou cadastrar-se. Logo após será redirecionado.

<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Figura 23</b> - Tela de formulário</p>

![](./assets/prototipoNecivaldoForm.jpg)

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Necivaldo Amaral](https://github.com/junioramaral22)</p>

</center>

Nessa tela o usuário poderá preencher as informações do formulário para a emissão da nota fiscal de serviço.

<center>

<p style={{ textAlign: 'center', fontSize: '18px' }}><b>Figura 24</b> - Tela de confirmação de Formulário enviado</p>

![](./assets/prototipoNecivaldoForm2.jpg)

<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Necivaldo Amaral](https://github.com/junioramaral22)</p>

</center>

Após o envio do formulário é notificado ao usuário a emissão com possibilidade de impressão / salvar e dado a opção de retorno a tela inicial.

## Bibliografia

> \- BRASIL. Prefeitura Municipal de Nova Iorque. Prefeitura Municipal de Nova Iorque. Disponível em: https://www.novaiorque.ma.gov.br/. Acesso em: 02 jan. 2025.   

## Referências Bibliográficas

> 1. PREECE, Jenny; ROGERS, Yvonne; SHARP, Helen. Interaction design: beyond human-computer interaction. 1. ed. New York: J. Wiley & Sons, 2002. Capítulo 08: Design, Prototipação e Construção. Página 261. Disponível em: [libgen.li/file.php?md5=02236874c9b62b7d9aed9ec21639968a](https://libgen.li/file.php?md5=02236874c9b62b7d9aed9ec21639968a). Acesso em: 02 jan. 2025.

> 2. PREECE, Jenny; ROGERS, Yvonne; SHARP, Helen. Interaction design: beyond human-computer interaction. 1. ed. New York: J. Wiley & Sons, 2002. Capítulo 08: Design, Prototipação e Construção. Página 261. Disponível em: [libgen.li/file.php?md5=02236874c9b62b7d9aed9ec21639968a](https://libgen.li/file.php?md5=02236874c9b62b7d9aed9ec21639968a). Acesso em: 02 jan. 2025.

> 3. PREECE, Jenny; ROGERS, Yvonne; SHARP, Helen. Interaction design: beyond human-computer interaction. 1. ed. New York: J. Wiley & Sons, 2002. Capítulo 08: Design, Prototipação e Construção. Página 262-263. Disponível em: [libgen.li/file.php?md5=02236874c9b62b7d9aed9ec21639968a](https://libgen.li/file.php?md5=02236874c9b62b7d9aed9ec21639968a). Acesso em: 02 jan. 2025.

## Histórico de Versão

| Versão | Data | Autor(es) | Descrição | Data de Revisão | Revisor(es) |
|:---:|:---:|---|---|:---:|---|
| 1.0 | 02/01/2025 | [Paulo Henrique](https://github.com/paulomh) | Criação do documento | 02/01/2025 | [Weverton Rodrigues](https://github.com/vevetin)  |
| 1.1 | 05/01/2025 | [Paulo Henrique](https://github.com/paulomh) | Protótipo - Realizar pedido no e-SIC | 05/01/2025 | [Rodrigo Wendrel](https://github.com/junioramaral22)  |
| 1.2 | 05/01/2025 | [Pedro Luiz](https://github.com/pedroluizfo) | Protótipo - Registrar chamado na ouvidoria | 05/01/2025 | [Rodrigo Wendrel](https://github.com/junioramaral22)  |
| 1.3 | 05/01/2025 | [Paulo Henrique](https://github.com/paulomh) | Imagens do protótipo - Realizar pedido no e-SIC | 05/01/2025 | [Pedro Luiz](https://github.com/pedroluizfo)  |
| 1.4 | 05/01/2025 | [Weverton Rodrigues](https://github.com/vevetin) | Protótipo - Agendamento de Consulta Médica | 05/01/2025 | [Paulo Henrique](https://github.com/paulomh) |
| 1.5 | 05/01/2025 | [Rodrigo Wendrel](https://github.com/rodwendrel) | Imagens do protótipo - Buscar por licitação fracassada | 05/01/2025 | [Paulo Henrique](https://github.com/paulomh)  |
| 1.6 | 14/01/2025 | [Necivaldo Amaral](https://github.com/junioramaral) | Imagens do protótipo - Envio de Nota Fiscal de Serviço | 05/01/2025 | [Rodrigo Wendrel](https://github.com/rodwendrel)  |


