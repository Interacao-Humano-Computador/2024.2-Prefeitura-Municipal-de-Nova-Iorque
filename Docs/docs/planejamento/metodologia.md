---
sidebar_position: 8
---

# Metodologia

## Introdução
Neste projeto, a equipe de desenvolvimento decidiu adotar e se basear em algumas metodologias específicas, com o intuito de organizar e otimizar o processo de desenvolvimento, buscando alcançar o máximo de eficiência dentro das condições e recursos disponíveis do grupo. É importante destacar que este documento tem como objetivo principal detalhar as metodologias nas quais nos inspiramos ao longo das diferentes fases do desenvolvimento. Além disso, pretende esclarecer quais elementos dessas metodologias foram aplicados e quais foram adaptados ou simplificados para atender melhor às necessidades e limitações do projeto.

## Metodologia de desenvolvimento
As metodologias escolhidas foram baseadas nas abordagens ágeis SCRUM e XP, adaptadas para atender às limitações de disponibilidade e horários dos membros do grupo. A adoção de práticas ágeis visa promover uma colaboração mais eficiente e uma entrega contínua de valor ao longo do desenvolvimento. As adaptações específicas foram feitas para garantir que todos os integrantes possam participar ativamente nas reuniões e atividades, ajustando a cadência das sprints e flexibilizando algumas práticas para alinhar com a realidade e os compromissos de cada membro do grupo.

### SCRUM
O SCRUM é uma metodologia ágil que organiza o trabalho em ciclos chamados sprints, com o objetivo de entregar incrementos de produto em intervalos regulares. No contexto deste projeto, a metodologia foi adaptada para se adequar ao cronograma e à disponibilidade dos participantes, dividindo o trabalho em 7 sprints de duração variável, definidos conforme a complexidade das tarefas e os prazos.

Ao final de cada sprint, é realizada uma sprint review, onde o time avalia o progresso, demonstra o que foi desenvolvido e discute ajustes necessários para as próximas etapas. Embora o SCRUM normalmente inclua dailys — reuniões diárias para alinhamento — essa prática foi omitida neste projeto, sendo substituída por atualizações semanais ou conforme a necessidade. Essa adaptação mantém o foco nas entregas e garante flexibilidade, sem comprometer o ritmo de colaboração e o alinhamento do grupo.

### XP

O XP (Extreme Programming) é uma metodologia ágil focada em melhorar a qualidade do software e a capacidade de resposta às mudanças através de práticas intensivas, como desenvolvimento orientado a testes, programação em pares, integração contínua e feedback constante. No contexto deste projeto, a metodologia XP foi adaptada para equilibrar a qualidade do código e a colaboração entre os membros, mesmo com as limitações de disponibilidade.

Com 7 sprints de duração variável, as práticas de XP foram aplicadas de forma flexível: o desenvolvimento orientado a testes (TDD) e a integração contínua são mantidos para garantir que cada incremento seja funcional e estável. A prática de programação em pares é utilizada apenas quando possível, priorizando momentos em que decisões críticas são tomadas. Sem dailys, o time utiliza checkpoints semanais ou conforme a necessidade para monitorar o progresso e manter o alinhamento. Essas adaptações permitem que o XP contribua para a qualidade do software e a satisfação do time, mesmo em um ambiente de disponibilidade reduzida.

## Comunicação

Para evitar problemas de alinhamento e garantir uma comunicação eficaz, a equipe definiu uma estratégia de comunicação clara, utilizando ferramentas como Microsoft Teams, WhatsApp e GitHub. Essas plataformas permitem uma comunicação rápida e acessível para o grupo, possibilitando suporte imediato quando necessário.

Em caso de imprevistos ou dificuldades, os membros avisam o grupo por meio dessas ferramentas, assegurando que todos estejam informados sobre o andamento do projeto e possam colaborar conforme necessário.

## Políticas

### Política de commits

Para manter um padrão nas mensagens de commit, adotamos o modelo *Conventional Commits*. Esse padrão facilita a rastreabilidade e a compreensão das mudanças no histórico do projeto. A estrutura básica de um commit é:  
`git commit -m "tipoDeMudança(): descrição significativa da alteração"`

Exemplo: O commit para a criação do arquivo metodologias.md pode ser:  
`docs: criação do documento de padrões e metodologias`

### Política de branches
As branches são criadas seguindo um padrão que facilita o entendimento e o vínculo com entregas específicas, os integrantes irão trabalhar juntos em uma mesma branch e depois será feita uma revisão para o merge na branch principal.


## Conclusão
Nossa equipe busca constantemente otimizar e padronizar o projeto para minimizar erros e melhorar a clareza do processo de desenvolvimento. A metodologia escolhida é uma combinação de SCRUM e XP, adaptada à realidade e disponibilidade dos integrantes, promovendo entregas frequentes e de qualidade.

A proposta de comunicação rápida e os encontros semanais garantem que todos estejam informados e alinhados. As políticas de commits e branches proporcionam um padrão de entregas, permitindo que o projeto seja compreensível e gerenciável. Com isso, mantemos o foco na eficiência e na qualidade, utilizando as metodologias como guias e ajustando-as conforme necessário para atender ao projeto da melhor maneira possível.

## Bibliografia

> \- BOURQUE, Pierre; FAIRLEY, Richard E. (eds.). SWEBOK: Guide to the Software Engineering Body of Knowledge, Versão 3.0, IEEE Computer Society, 2014. Disponível em: https://www.computer.org/education/bodies-of-knowledge/software-engineering. Acesso em: 8 nov. 2024. 

> \- Conventional Commits 1.0.0. Conventional Commits, [2012?]. Disponível em: https://www.conventionalcommits.org/en/v1.0.0/. Acesso em: 6 nov. 2024.

> \-  Universidade de Brasília (UnB), Campus UnB Gama: Faculdade de Ciências e Tecnologias em Engenharia. Documentação do projeto de Interação Humano-Computador: Banco Central. Semestre 2023.1, Universidade de Brasília, Gama, 2023. Disponível em: https://interacao-humano-computador.github.io/2023.1-BancoCentral/#/. Acesso em: 6 nov. 2024.  


## Histórico de Versão
---
| Versão | Data | Autor(es) | Descrição | Data de Revisão | Revisor(es) |
|:---:|:---:|---|---|:---:|---|
| 1.0 | 08/11/2024 | [Pedro Luiz Fonseca Da Silva](https://github.com/pedroluizfo) | Criação do documento | 09/11/2024 | [Weverton Rodrigues](https://github.com/vevetin) |