---
sidebar_position: 3
---

# Guia de Estilo

## Introdução

### Objetivo do guia de estilo

O Guia de Estilo tem como objetivo assegurar a consistência, a qualidade e a usabilidade no design. Ele serve como um documento centralizado, reunindo as principais decisões de design, diretrizes e recomendações que orientam a criação e o desenvolvimento da interface. Este guia proporciona uma base para todos os membros da equipe de design e desenvolvimento, garantindo que as decisões tomadas sejam implementadas de forma coerente e eficaz ao longo do ciclo de vida do projeto.

### Organização e conteúdo do guia de estilo

O guia está estruturado para ser uma ferramenta prática e acessível, a qual pode ser consultada a qualquer momento durante o desenvolvimento e também para futuras atualizações ou melhorias no sistema. Seu conteúdo inclui diretrizes sobre layout, tipografia, cores, símbolos, interação, vocabulário e muito mais, fornecendo os fundamentos necessários para criar uma experiência de usuário intuitiva, eficiente e agradável.

### Público-alvo do guia de estilos

O público-alvo deste guia inclui os membros da equipe de design, desenvolvedores, gerentes de projeto e qualquer outro profissional envolvido no processo de criação e manutenção do site. Ao seguir as recomendações deste guia, o time de desenvolvimento estará apto a entregar um produto consistente, que atenda às necessidades dos usuários e que seja fácil de manter e expandir.

### Como utilizar o guia

Este guia deve ser consultado continuamente durante o desenvolvimento do site e utilizado como referência nas fases de design, implementação e manutenção. As diretrizes e recomendações podem ser aplicadas de maneira flexível, ajustando-se conforme as necessidades específicas do projeto, mas sempre mantendo a coerência com os princípios estabelecidos.

### Manutenção do guia

A manutenção do guia de estilo deve ser uma prática contínua. O documento precisa ser atualizado sempre que novas diretrizes ou alterações no design forem feitas, garantindo que todos os membros da equipe tenham acesso à versão mais atualizada. Isso assegura que futuras melhorias ou ajustes no site sigam as mesmas diretrizes, mantendo a consistência e qualidade ao longo do tempo.

## Resultados de Análise
<!--
Descrição do ambiente de trabalho do usuário: Relatar as condições de uso do site, levando em consideração os tipos de dispositivos utilizados pelos usuários (computadores, celulares, tablets), e o contexto em que o site será acessado (em casa, no trabalho, em locais públicos, etc.).
-->

## Elementos de Interface

### Disposição espacial e grid
<!-- Definir a estrutura de layout e a utilização de grids para garantir que o design seja organizado e responsivo. --> 

### Janelas
<!-- Descrever o uso de janelas ou painéis, como elas devem ser estruturadas e quando devem ser usadas. --> 
 
### Tipografia

A tipografia utilizada no site da Prefeitura Municipal de Nova Iorque segue uma lógica de fallbacks, priorizando fontes nativas dos sistemas operacionais dos usuários. Isso assegura que o design mantenha a legibilidade e a consistência, independentemente do dispositivo utilizado.

**Fonte principal:** `system-ui`  
Representa a fonte padrão do sistema operacional do usuário, garantindo alta compatibilidade e desempenho. Quando não disponível, a fonte de fallback segue uma lista que cobre a maioria dos sistemas operacionais, garantindo a continuidade da experiência de leitura.

**Fontes de Fallback:** 
Caso a fonte principal não esteja disponível, o sistema recorrerá às fontes seguintes, que são amplamente suportadas em diferentes dispositivos: `-apple-system`, `Segoe UI`, `Roboto`, `Helvetica Neue`, `Arial` e `sans-serif`.

A seguir, apresentamos os estilos tipográficos utilizados no site, com exemplos de cada tipo de texto, incluindo seu tamanho e peso.


<p style={{ textAlign: 'center', fontSize: '17px' }}><b>Figura x</b> - Estilos Tipográficos</p>
<center>
    ![tipografia](../analise-de-requisitosII/assets/tipografia.jfif)
</center>
<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Weverton Rodrigues](https://github.com/vevetin) | Fonte: Figma, 2024</p>

### Símbolos não tipográficos

Os símbolos não tipográficos, como ícones e gráficos, são essenciais para guiar os usuários, destacar informações e indicar ações no site. No entanto, a escolha atual dos ícones no site da Prefeitura de Nova Iorque apresenta limitações, prejudicando a clareza e a usabilidade.

A seguir, são apresentados os ícones atualmente utilizados no site:

<p style={{ textAlign: 'center', fontSize: '17px' }}><b>Figura x</b> - Ícones Atuais do Site da Prefeitura de Nova Iorque</p>
    <center>
        ![icones-atuais](../analise-de-requisitosII/assets/icones-atuais.jfif)
    </center>
<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Weverton Rodrigues](https://github.com/vevetin) | Fonte: Figma, 2024</p>

Para melhorar a experiência do usuário, propomos a adoção de ícones revisados, baseados nos Princípios de Gestalt, conforme descrito por Simone Barbosa (2010)<sup>[1](guiaDeEstilo.md#referências-bibliográficas)</sup>. Os ícones revisados seguem, principalmente, os princípios de simetria, similaridade e fecho, promovendo maior padronização e clareza.

[inserir imagem aqui]

A aplicação desses princípios garantirá uma interface mais intuitiva, consistente e alinhada às boas práticas de design visual.

### Cores

As cores utilizadas no design do site da Prefeitura Municipal de Nova Iorque foram escolhidas com base na harmonia e acessibilidade. A paleta de cores inclui tons principais, neutros e de status, visando garantir contraste e legibilidade em diversos dispositivos e contextos.

<p style={{ textAlign: 'center', fontSize: '17px' }}><b>Figura x</b> - Cores Utilizadas no Design do Site</p>
    <center>
        ![tipografia](../analise-de-requisitosII/assets/cores.jfif)
    </center>
<p style={{ textAlign: 'center', fontSize: '17px' }}>Autor: [Weverton Rodrigues](https://github.com/vevetin) | Fonte: Figma, 2024</p>

<!--
Animações: Quando e como as animações devem ser usadas no site, garantindo que não distraiam o usuário e sim complementem a interação.
-->


## Elementos de Interação

### Estilos de interação
<!-- Explicar os tipos de interação disponíveis no site (clique, toque, arrastar, etc.) e como eles devem ser implementados. -->

### Seleção de um estilo
<!-- Determinar qual estilo de interação será adotado para ações como navegação, preenchimento de formulários, etc. -->

### Aceleradores (teclas de atalho)
<!-- Se for pertinente, listar as teclas de atalho que podem ser usadas para otimizar a navegação no site. -->

## Elementos de Ação

### Preenchimento de campos
<!-- Instruções sobre como os campos de formulários devem ser estruturados e como o usuário deve interagir com eles. -->

### Seleção
<!-- Definir as regras para selecionar opções, como menus suspensos ou caixas de seleção. -->

### Ativação
<!-- Descrever como os botões de ação devem ser utilizados para ativar funções, como envio de formulários ou navegação entre páginas. -->


## Vocabulário e Padrões

### Terminologia 
<!-- Definir os termos técnicos que serão usados ao longo do site e garantir que sejam compreendidos pelos usuários. -->

### Tipos de tela
<!-- Descrever os tipos de tela que serão apresentados aos usuários, como telas iniciais, de erro, de confirmação, etc. -->

### Sequências de diálogos
<!-- Estabelecer as sequências de interações típicas, como fluxos de navegação e feedback ao usuário. -->


## Considerações Finais
<!--
Design Rationale: Justificar as decisões de design tomadas ao longo do projeto, alinhando-as às necessidades e expectativas dos usuários.
Implementação e Atualizações: Como o guia será implementado na prática e as atualizações serão feitas à medida que o site evolui.
-->

## Bibliografia

> \- BARBOSA, Simone, et al. Interação Humano-Computador e Experiência do Usuário. Leanpub, 2022. Disponível em: https://leanpub.com/ihc-ux. Acesso em: 18 nov. 2024.

## Referências Bibliográficas

> \- BARBOSA, Simone, et al. Interação Humano-Computador. 1. ed. Rio de Janeiro: Elsevier, p.50-51, 2010.

## Histórico de Versão
---
| Versão | Data | Autor(es) | Descrição | Data de Revisão | Revisor(es) |
|:---:|:---:|---|---|:---:|---|
| 1.0 | 28/11/2024 | [Weverton Rodrigues](https://github.com/vevetin) | criação do documento |  |  |
| 1.1 | 30/11/2024 | [Weverton Rodrigues](https://github.com/vevetin) | adição dos subtópicos tipografia, símbolos não tipográficos e cores | | | 