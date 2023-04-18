# Tópicos Avançados Executando

## Criando o incremento

O incremento é a soma de todos os itens do backlog do produto completados durante uma Sprint em andamento, somado aos incrementos entregues em Sprints anteriores. À medida que o tempo vai passando, esse incremento vai aumentando até que, ao final do projeto, temos o produto finalizado. Se formos pensar na forma tradicional de gerenciamento de projetos, o incremento nada mais é que uma nova versão do produto, com novas funcionalidades acrescentadas. Vários incrementos podem ser criados em uma Sprint e a soma dos incrementos é apresentada na revisão Sprint.

Assim, vários incrementos podem ser entregues aos stakeholders antes do final da frente, ou seja, não devemos esperar a revisão da Sprint para só então liberarmos um incremento pronto e utilizável, que só então irá adicionar valor.

**Formato sugerido.

Veja que o incremento não é um documento, mas uma parte do produto em funcionamento. O incremento deve, obrigatoriamente estar aderente à definição de pronto. Essa definição garante que o que foi entregue está de acordo com os padrões de qualidade estabelecidos pelo time Scrum 

**o papel de cada um.

Os desenvolvedores trabalham de forma mais eficaz se eles puderem decidir como realizar seu trabalho ao invés de atuarem num ambiente onde outros determinam o que deve ser feito. Dar à equipe a capacidade e a responsabilidade de organizar seu trabalho e de determinar a melhor forma de cumprir seus compromissos motiva seus membros para fazer o melhor possível. Isso também os ajuda a colaborar para garantir que as habilidades corretas sejam aplicadas às tarefas adequadas.

O auto gerenciamento afeta muitas áreas, incluindo como o planejamento e o comprometimento acontecem. Como o trabalho é atribuído e como os membros do time enxergam o seu papel no projeto?

**Work in Progress(wip)

O termo  WIP do inglês work in progress, ou seja, trabalho em andamento, é uma métrica que indica, o que é que está em execução em um determinado ponto do processo.

Em projetos ágeis, é uma boa prática limitar o work in progress, já que os recursos humanos e o tempo são limitados.

Essa prática foi herdada do Kanban e implica em um sistema puxado, ou seja, o trabalho em cada etapa do processo é limitado, de forma que um novo trabalho somente será puxado para a próxima etapa, quando a capacidade disponível dentro do limite daquela etapa.

Limitamos o work in progress porque estudos comprovaram que quanto maior o número de tarefas em andamento em determinada parte do processo, maior é o Leade-Time.

**O que é o Lide Time?

É simplesmente o tempo em que uma tarefa fica no fluxo, isto é, o tempo decorrido desde que o cliente fez uma solicitação até a sua entrega. O lead time mostra como está o nosso fluxo, identificando gargalos e áreas problemáticas no processo, auxiliando assim o time a tomar decisões para resolvê-los. O limite de Wip, obviamente, não pode ser muito grande, tampouco muito pequeno. Não existe um número mágico e cada time deve descobrir o seu número ideal empiricamente.

**porque o limite não pode ser muito pequeno?

Vamos considerar que definimos um limite de WiP de uma tarefa por desenvolvedor.

O que fazer se uma tarefa foi bloqueada? ou tiver algum impedimento? aquele desenvolvedor vai parar? E se a solução daquele impedimento não depender dele, ele vai continuar parado.

É claro que existem empresas que trabalham com o WIP limitado de forma radical, de uma tarefa por desenvolvedor, mas essas empresas já são maduras em processos ágeis e o desenvolvedor que ficaria parado pode atuar em melhorias de código ou refactoring, ou ajudando outro desenvolvedor, ou ainda ajudando a testar etc.

Porque o limite não pode ser muito grande? porque as pessoas simplesmente são sequenciais. Não executamos mais de uma tarefa ao mesmo tempo. Temos que parar uma para começar outra.

Estudos também comprovaram que temos uma grande perda de tempo e concentração quando temos muitas tarefas a serem executadas ao mesmo tempo.

Assim, o tempo que se perde para lembrar o que a outra tarefa que estava parada é o que precisa ser feito é nocivo para o fluxo.

Então, um número ideal deve ficar entre duas e três tarefas por desenvolvedor. Mas é claro que isso vai depender do contexto e o número ideal aparecerá com a maturidade e experiência do time.

Mas o que fazer se todas as tarefas do desenvolvedor estiverem bloqueadas?

Na verdade, quando isso acontece, devemos formar uma força tarefa para desbloquear essas tarefas, de forma que o fluxo volte ao normal.

## Quadro de Tarefas ou ScrumBoard ou Scrum Taskboard

O Scrum Board é um quadro originário do Kanban, onde o time coloca as tarefas do Backlog em post-its de uma forma organizada e ordenada. O objetivo do uso do Scrum Board é podermos visualizar e entender rápida e claramente o andamento do trabalho e ele pode ser construído da seguinte forma:

![image](https://user-images.githubusercontent.com/52088444/232789733-23d35d2d-0c5e-4920-9b52-be6148c3b97e.png)


**colunas do quadro.

As colunas do quadro Kanban são personalizáveis e podemos adicionar quantas etapas forem necessárias, tais como: projetar, desenvolver, testar e integrar.

Cada cartão seria movido da esquerda para a direita para indicar visualmente o seu estado atual. Também podemos incorporar a boa prática do Kanban e limitando o trabalho em andamento ou o work in progress(WIP), ou seja, eliminaremos o número de cartões permitidos em cada coluna. Ao aceitar essa limitação, aceitamos nos concentrar em um pequeno número de histórias em cada ponto no tempo, e realizá-las em vez de começar novas histórias.

As colunas mínimas e um quadro de tarefas são: 

- TO-DO: coisas esperando para serem iniciadas.
- DOING: coisas que estamos fazendo agora, e geralmente em um número limitado
- DONE:coisas que já foram concluídas. 


Você pode, claro, adicionar todo o tipo de coluna que quiser esperando pelo teste de integração, por exemplo, ou cancelado.

Entretanto, antes de complicar as coisas, pense profundamente, a adição de colunas é realmente necessária? 
Além dessas colunas, ainda podemos ter o gráfico de Burnndown, a meta da sprint, itens que surgiram durante a Sprint e que devem ir para o backlog do produto, pois não estavam previstos para entrar na fila de desenvolvimento dessa Sprint, backlog de impedimentos e limite de work in progress.

**Raias possíveis.

Um quadro Kanban pode ter um ou vários caminhos, também conhecidos como raias, que podem ser utilizados para isolar diferentes tipos de trabalho que podem ter fluxos de desenvolvimento diversos. Não há certos ou errados. Use de acordo com o que melhor se adeque ao time scrum. Se não deu certo, mude. Se deu certo, aprimore.
Em projetos e scrum o normal é termos raias baseadas em histórias de usuário. Uma história de usuário é colocada por Raia, todas as tarefas relativas a essa história de usuário é que trafegam pelo quadro 

![image](https://user-images.githubusercontent.com/52088444/232792079-20a8f70e-8c28-44d1-bd7a-9611612c627e.png)

**responsável alocado.

A depender do projeto, pode ser interessante montar raias de acordo com cada uma das pessoas do time ou uma pessoa por raia.

- Como funciona?
![image](https://user-images.githubusercontent.com/52088444/232792167-e39ab3c5-1f2d-4fbe-a69c-f915907dc05a.png)
Do lado esquerdo temos as histórias de usuário que compõem o backlog da Sprint, que serão trabalhadas nesse sprint ou uma por raia. Essas histórias, que são representadas pelos cartões azuis, são divididas em tarefas os post-its amarelos, que ficam inicialmente na coluna a fazer ou to-do. Assim que um membro pega uma tarefa para trabalhar, ela deve passar da coluna a fazer pára em andamento doing.

Veja que o membro que pegar a tarefa para executá-la tem a obrigação de movê-la para a coluna seguinte. Ao terminar o desenvolvimento, a tarefa é passada então para a coluna Pronto ou Done.

Quando todas as tarefas forem finalizadas e a história de usuário cumpriu todos os requisitos dos critérios de pronto e critérios de aceitação, o cartão da história é, então, movido para a coluna Pronto.

## Reuniões Diárias Scrum / Daily Scrum / Stand Up

A reunião diária ou Daily ou  Scrum Meeting é uma reunião de acompanhamento do progresso, bem como planejamento do que o time realizará nas próximas 24 horas.

A reunião diária otimiza a colaboração e a performance através da Inspeção do Trabalho, desde a última reunião diária e da previsão do próximo trabalho a ser realizado dentro da Sprint. O formato desta reunião é definido pelos desenvolvedores e pode ser conduzida de diferentes formas, desde que estas foquem no progresso em direção à meta da  Sprint e devemos levar em conta as seguintes regras:

- O time box será sempre de 15 minutos. O Scrum master deve ensinar os desenvolvedores a respeitar esse time boxed.
- Deve ser realizada sempre no mesmo horário e local. A justificativa para isso é reduzir os riscos dela não acontecer, pois todos sabemos a dificuldade que é tentar conciliar agendas de várias pessoas e reservas de salas. Se a reunião é sempre no mesmo horário e local, as pessoas já se programam com antecedência para participar.
- Alguns times utilizarão perguntas, outros se basearam em discussões, o mais comum é que sejam feitas estas três perguntas, mas não há obrigatoriedade que sejam elas, e que são: o que eu fiz no projeto desde a última reunião? o que irei fazer até a próxima reunião? E quais são os impedimentos? Embora o guia do scrum, não cite essas perguntas a serem feitas na daily scrum, elas são interessantes, pois apresentam uma oportunidade para avaliar o progresso atual, planejar as próximas ações e mostrar os potenciais riscos. 
- Esta reunião é exclusiva para os desenvolvedores. Outras pessoas poderão assisti-la se os desenvolvedores assim o permitirem, mas esses convidados não podem opinar ou fazer qualquer comentário.
- O dono do produto e o Scrum Master podem participar ativamente. Caso acumulem a função de desenvolvedores. Caso contrário, podem apenas assistir e mesmo assim, somente se os desenvolvedores assim o permitirem.
- Um ponto de atenção é que, caso haja a necessidade de um assunto ser debatido em maior profundidade, ele deve ser feito após a daily scrum. Em uma outra reunião marcada para isso, o Scrum não proíbe que outras reuniões aconteçam. Ele apenas nos alerta para utilizarmos reuniões de forma a não desperdiçar o precioso tempo do time scrum. Se um ou mais desenvolvedores não puderem participar, a reunião deve acontecer assim mesmo, embora acabe sendo prejudicada.

Os benefícios da realização da reunião diária são:

- melhorar a comunicação, 
- identificar impedimentos que devem ser removidos, 
- destacar e promover discussões e tomada de decisão de forma rápida.
- Aprimorar o nível de conhecimento entre os membros do time.
- Acompanhar o progresso da Sprint.


Os desenvolvedores frequentemente se encontram imediatamente após a reunião diária para discussões detalhadas ou para replanejar o restante do trabalho da Sprint.

Como atualizamos o andamento do projeto, conforme cada pessoa descreve o que fez ontem e o que fará hoje. Pode ir colocando post-its no quadro de tarefas quando essa pessoa descreve uma tarefa que não havia sido planejada.

Também criam post-it para este item quando atualiza uma estimativa de prazo a atualiza no respectivo post-it, escrevendo a nova e riscando estimativa antiga.

Para o guia do scrum, a atualização do progresso da Sprint não é trabalho do scrum master, já que como a presença dele não é obrigatória nesse evento, não haveria como ser dele essa função. Imediatamente após a reunião diária. Um desenvolvedor checa, o que já foi finalizado e marca um novo ponto no gráfico de Burndown da Sprint. Essa atividade precisa ser realizada diariamente para que o progresso da Sprint possa ser visível e transparente para toda a empresa.

Depois da primeira reunião diária, o quadro de tarefas pode se parecer mais ou menos como este da figura:

![image](https://user-images.githubusercontent.com/52088444/232796544-5e369282-8042-4039-8c15-bf33757d6ed4.png)

Como se pode ver três tarefas foram selecionadas e colocadas em produção doing. A equipe vai trabalhar nessas tarefas hoje, poucos dias depois o quadro de tarefas pode se parecer como algo assim:
![image](https://user-images.githubusercontent.com/52088444/232797023-b6f78287-806e-4fc4-8e2c-026a0e4b1a03.png)

Como podemos ver, completamos a história depósito, isto é, ela foi integrada ao repositório com ocódigo fonte testado, refatoradoo e etc.
A história ferramenta de migração está parcialmente completa e a login foi iniciada e a administração de usuários ainda nem começou. Tivemos itens não planejados, como podemos ver na parte inferior direita do quadro.

Guardá-los é útil para que sejam lembrados quando você for fazer a retrospectiva da Sprint, já que o fato deles não terem sido identificados antes do início da Sprint pode ser resultado de alguma falha em algum processo de desenvolvimento ou levantamento de requisitos. Além disso, se esses itens forem relativos ao produto, eles serão integrados ao backlog do produto. E o gráfico de Burndown também foi atualizado à medida que as histórias de usuário e as tarefas foram sendo completados.

## Débito (dívida) técnica

Débitos tecnicos são implementações e ou soluções não realizadas da melhor forma dentro do trabalho esperado, pode ser uma cobertura de testes não alcançada, há algum componente não implementado 100%, falta de padronização de código e etc.

Em inglês, o termo conhecido é technical debity, cuja tradução é dívida e não débito, O termo débito técnico acabou sendo mais usado que dívida técnica.

Bom, não importa se é débito ou dívida, o fato é que isso não é nada bom para o projeto. Algumas causas de se acumular o débito técnico são:

- upfront design, ou seja, a desenvolver componentes antes que sejam realmente necessários. O termo em inglês mais conhecido é Big Design Upfront, que geralmente é associado ao modelo waterfall ou cascata.
- Gambiarras.
- Sacrificar intencionalmente a qualidade para entregar na data prevista.
- Implementar funcionalidades que não haviam sido previstas.
- Falta de conhecimento técnico.
- Complexidade do projeto.
- Escolha de tecnologia.
- Ferramenta plataforma todos inadequados.
- Passar do tempo o código envelhece e apodrece. Como praticamente tudo na vida, não é mesmo?

**Quadrantes da dívida técnica:

![image](https://user-images.githubusercontent.com/52088444/232798705-9321088f-8777-4eda-855c-4c09d69f7d70.png)

Basicamente, podemos classificar a divida técnica em quatro tipos distintos:

- imprudente e intencional: Sabemos do problema, mas não vamos resolver.
- Imprudente e não intencional: Vamos trabalhar com uma nova linguagem de programação.
- consciente e intencional: dado o nosso deadline: Vamos entregar com o problema e depois corrigi-lo 
- consciente e não intencional: Agora vejo que poderíamos ter trabalhado utilizando métodos ágeis.

O que deveríamos almejar é sempre ter dívida técnica nos quadrantes verdes. Estes são os quadrantes onde temos consciência sobre assumir um risco que pode gerar um impacto no futuro. Embora os quadrantes azuis não sejam inevitáveis, eles representam e abordam fatores que nem sempre são facilmente compreendidos.

Por exemplo:
- trabalhar com uma nova tecnologia ou um novo framework que o time não possui conhecimento vai fazer com que o resultado provavelmente não seja tão aderente e benéfico quanto deveria ser.

**E quando pagar a dívida?

É igual a uma dívida financeira o quanto antes, melhor, Não se deve acumular, porém, caso a decisão do negócio seja absorver alguma dívida objetivando uma entrega mais rápida, então crie visibilidade sobre a dívida acumulada para que todos fiquem alertas e possam pagá-la o quanto antes.

Dica colhe um post-it chamativo no seu quadro de tarefas.


## Técnicas para controle das dívidas técnicas

Agora que você já sabe que as dívidas técnicas não são nada boas para um projeto ágil, vamos ver algumas técnicas para lidar com elas.
Toda vez que houver um acúmulo de dívida técnica ou que ela tenha sido identificada apenas posteriormente, Isso deve ser discutido na retrospectiva da Sprint.

Nessa discussão, tente explorar qual é a causa raiz. Ela pode estar em diferentes contextos, tais como numa falta de conhecimento, numa pressão para que o time tenha um ritmo insustentável e etc. Somente assim estaremos fazendo um esforço concreto para que a dívida técnica seja mínima em longo prazo e para isso podemos usar algumas estratégias, como veremos na sequência:

**Sprint de reforço

Sprint de reforço ou hardening Sprint = É uma sprint onde nenhuma nova funcionalidade é desenvolvida. o time trabalha apenas em melhorias técnicas no software, como por exemplo a refatoração, testes automatizados e melhorias de performance.

Eu diria que uma Sprint de reforço é como usar o 13.º salário para pagar as dívidas. Você sabe que as dívidas estão lá, mas você espera uma oportunidade e gasta uma boa parte dele para quitá-las.

A Scum org abomina essa prática já a Scrum Alliance diz que isso não é uma boa ideia, mas que às vezes pode ser necessário.

**E quanto a nós?

Bom, se a prática ágil diz que devemos sempre entregar itens de valor para o cliente, talvez seja o caso de combinar itens da Sprint com algumas dívidas técnicas.

**Tratar a dívida como um item da Sprint.

A partir das dívidas identificadas na reunião de planejamento da Sprint, o dono do produto e o time de desenvolvimento selecionam quais dívidas podem ser saldadas nesse sprint.

**Formato.

Não há nenhum formato que identifique uma dívida, já que ela pode assumir diversas formas, mas uma ideia bacana é reservar uma área do quadro de tarefas com uma quantidade ilimitada de espaços. Cada nova dívida deve ser registrada em um post-it e colocado em um desses espaços. Quando acabarem os espaços, o time não poderá fazer novas dívidas. Ele precisa resolver alguns dos itens antes de criar novas. Além disso, crie uma nova linha no quadro de tarefas. Apenas post-its de dívidas técnicas devem encaminhar por essa pista. Estimule o time a sempre ter pelo 1 item caminhando nesta linha por Sprint.Esta abordagem torna fácil de perceber visualmente se o time está trabalhando em suas dívidas técnicas.
















