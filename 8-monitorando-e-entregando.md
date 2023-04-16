# Monitorando e Entregando

## Gráfico de Burndow

O gráfico de Born Down é uma das ferramentas mais utilizadas no monitoramento do progresso do projeto.

![image](https://user-images.githubusercontent.com/52088444/232313375-b84bc8c1-c9c7-4cb6-83e8-b0efe7039ef1.png)


Veja que a partir desse gráfico podemos extrair informações tais como:
- quão bom é o time no planejamento;
- o time é realmente alto-organizado e está trabalhando como uma equipe?
- Quais melhorias esse time pode fazer?
- O quão bem o time está executando as histórias planejadas na frente?

Normalmente existem dois tipos de burndown em um projeto ágil ou scrum.
- Burndown do produto: registra a soma dos esforços restantes do backlog do produto ao longo do tempo. O esforço estimado pode estar em qualquer unidade de medida que o time entenda, mas geralmente para o burndown do produto, a unidade de medida são "sprints".
- Burndown da sprint: representa a quantidade restante de trabalho do backlog da Sprint ao longo dos dias de duração dessa frente.O esforço estimado pode estar em qualquer unidade de medida que o time entenda, mas geralmente para o bordão da sprint, a unidade de medida são horas ou dias.
![image](https://user-images.githubusercontent.com/52088444/232314019-65122252-91c5-4e79-abc7-aa0822a574d9.png)

- Como montar um gráfico de Burndown?

![image](https://user-images.githubusercontent.com/52088444/232314176-cccc61d5-a4b7-4cf0-9af9-f085278a58d6.png)

    - O gráfico representa a quantidade de trabalho que falta ser feito no eixo vertical ou y versus o tempo no eixo horizontal ou x.
    - A unidade de tempo do eixo x pode ser em dias, horas, semanas ou até mesmo sprints, mas neste último caso, somente se estivermos usando um gráfico de burndown da release.
    - A unidade da quantidade do eixo Y pode ser em horas de trabalho ou pontos de história. É importante mencionar que a unidade escolhida deve ser a mais adequada com a realidade de cada projeto ou empresa, visto que cada unidade de medida possui objetivos diferentes.
    - O burndown por pontos de história indica o valor que foi entregue ao cliente.Já o burndown por horas mostra o acompanhamento do ritmo diário do time.

Qual deles é o correto? Os dois, pois os dois tipos são importantes.

![image](https://user-images.githubusercontent.com/52088444/232314287-3521f235-426b-4324-bc2b-988f326e810e.png)

- Burndown da sprint, como já vimos, este é o gráfico que representa a quantidade restante de trabalho do backlog da Sprint ao longo dos dias de duração dessa frente.
- Deve se traçar uma linha ligando o eixo Y com o X. Essa reta vai nos indicar o progresso padrão da Sprint e se tudo corresse como esperado é a medida de velocidade do time. Mas veja que dificilmente o progresso da Sprint vai casar exatamente com essa linha. Se isso acontecer, acredite, é porque alguma coisa está errada.

- Por este gráfico, vemos que no primeiro dia da Sprint, 1 de agosto, a equipe estimou que havia aproximadamente 70 pontos de história de trabalho a serem feitos. Isso foi, na verdade, a velocidade estimada de toda a sprint.
- Em 16 de agosto, a equipe estimou que havia ainda aproximadamente 15 pontos de trabalho a serem feitos. A linha de tendência tracejada mostra que eles estão aproximadamente dentro do prazo, isto é, neste ritmo, eles completarão tudo até o final da Sprint.

## Incendios Descontrolados (Você sabe interpretar o Burndown?)

O gráfico de Burn Down é uma ferramenta de simples aplicação, mas se algo der errado, será que você saber identificar?

![image](https://user-images.githubusercontent.com/52088444/232314483-3f3a5154-7b6f-4679-9650-526fed193fe7.png)

Uma equipe deve tentar ficar o mais próximo possível da reta ideal, com pequenos picos ou vales ocorrendo naturalmente como parte da variação comum.

- Esta reta(vermelha) significa que a equipe completou o trabalho requerido pela experiente a tempo. Suas estimativas de capacidade foram sólidas e eles não se comprometeram demais. É claro que pequenos desvios vão acontecer, mas nada que indique que as coisas estão saindo do controle.

Mas nem sempre é assim que acontece. E o Scrum Master é o responsável por garantir que a equipe aja quando surgirem sinais de alarme, tais como estes que veremos a seguir:
![image](https://user-images.githubusercontent.com/52088444/232314660-3393c117-5082-4c28-bfb8-c0b29c461412.png)

- Neste gráfico podemos ver que o time-box da Sprint se esgotou, mas o time não conseguiu entregar o previsto e isso pode acontecer por diversos motivos , impedimentos não solucionados, estimativas erradas e itens mais complexos do que se imaginava.

Isso é ruim? Não. Se acontecer de vez em quando, no início do projeto, é muito comum errarmos as estimativas ou descobrirmos que os itens eram bem mais complexos do que estávamos imaginando. Mas, à medida que o tempo for passando, as estimativas se tornam mais precisas. O que não pode é isso virar uma constante.

![image](https://user-images.githubusercontent.com/52088444/232314755-a24c2a18-d355-421a-b58f-a35e341ecdff.png)

Já neste gráfico acontece justamente o contrário. O time encerrou todo o trabalho antes do final do time box da frente. Isso é bom, mas veja que você não pode mandar o time para casa descansar até que o time box se encerre. O dono do produto deve, então, selecionar mais algum item do backlog do produto, ou então o time pode usar o tempo restante para reduzir a dívida técnica.

![image](https://user-images.githubusercontent.com/52088444/232314821-5c863960-fb14-4b78-989d-2f7eeaf0b07f.png)

Agora neste gráfico vemos o terror de todo o time scrum. Mais trabalho foi adicionado ou descoberto no meio da frente? E por que esse trabalho adicional está sendo considerado aqui e não foi parar no backlog do produto para posterior verificação?E porque, provavelmente para se entregar um item já comprometido, esse trabalho adicional deve ser finalizado antes. Essa é a tal maldição das dependências e este "vale"
![image](https://user-images.githubusercontent.com/52088444/232314883-1bc82017-5612-4c13-ae01-5b79c627d5bf.png)
pode significar uma das seguintes opções.
- O time milagrosamente conseguiu ser super máster produtivo e encerrou as atividades.
- O time errou feio na estimativa do trabalho adicional ou o dono do produto retirou itens do backlog da Sprint
Como vemos aqui, o burndown não é muito bom para indicar as variações de escopo que podem ocorrer durante o Sprint

Algumas dicas muito importantes:

- adicionando indicações nos impedimentos.
![image](https://user-images.githubusercontent.com/52088444/232314968-b8fbf742-0577-4a03-ae08-6046b19bea7e.png)
Impedimentos e desvios normalmente atrapalham um bom andamento da frente e se você não documentá-los, provavelmente vai se esquecer, porque determinado Sprint terminou com o trabalho não entregue. Por isso, é recomendável que você indique os desvios, como mostramos aqui.

- Tarefas maiores que 08h00. Evite isso, apenas recapitulando as histórias de usuário são normalmente estimadas em pontos de história. Já as tarefas, ou seja, a decomposição das histórias em partes menores, é feita em horas e de preferência. Essas tarefas devem ser decompostas de forma a que caibam em um dia de trabalho.
Se as tarefas previstas forem muito grandes, o gráfico de Burn Down não vai refletir corretamente o andamento.
![image](https://user-images.githubusercontent.com/52088444/232315073-3450e0b1-7c40-408a-b829-ba78e3c87e87.png)

- E por quê? Porque todos os dias indicamos no gráfico quais as tarefas que foram finalizadas. É uma tarefa prevista em 12h00, por exemplo. Não será plotada no gráfico, mesmo que já tenha sido 98% completada. E aí vai parecer que nada foi feito nesse dia.

- E quando devemos agir.
 ![image](https://user-images.githubusercontent.com/52088444/232315156-895ccb64-c65e-4fe7-9065-6d93c18f7f58.png)

Existe uma linha tênue entre o momento em que descobrimos um problema na Sprint e o momento em que devemos tomar alguma ação.
- Agir cedo demais causa pânico desnecessário e pode introduzir problemas além do que a equipe já está trabalhando.
- Agir tarde demais, no entanto, pode impedir que a equipe seja capaz de completar a meta da frente

- Quando agir e qual ação corretiva tomar. É um exercício de observação e controle. Depois de umas seis Sprints, você já vai estar bem mais confortável em tomar as medidas necessárias.

E veja que se uma tendência perdurar por mais de duas Sprints, não deixe que isso continue. Uma ação corretiva deve ser tomada antes que essa tendência se propague para os mais Sprints.

## BurnDown do Produto( ou Release)

O BurnDown do produto ou release BurnDown chart é o gráfico que registra a soma dos esforços restantes do backlog do produto ao longo do tempo.

![image](https://user-images.githubusercontent.com/52088444/232315320-3fc51a25-5a8f-47cc-87c1-b4dbbf933bd5.png)

Em um projeto scrum otime acompanha seu progresso atualizando o gráfico de bordão do produto ao final de cada Sprint.

- O eixo horizontal desse gráfico mostra as Sprints.
- O eixo vertical mostra a quantidade de trabalho restante no início de cada expoente.

O trabalho restante pode ser representado em qualquer unidade da preferência do time por pontos de história, dias ideais, etc.

Neste gráfico, o time iniciou um projeto que foi planejado em 11 Sprints de duas semanas, com o total de 200 pontos de história.
![image](https://user-images.githubusercontent.com/52088444/232315399-376c5db1-6099-4cc5-a805-9ab4356d8350.png)

- A primeira sprint correu bem e a partir do gráfico podemos ver que eles finalizaram 20 pontos, ficando então cerca de 180 pontos de história remanescentes após a primeira Sprint
- durante a segunda sprint, podemos ver que houve um aumento do trabalho.Isso pode ter sido causado por atividades adicionadas ao projeto ou porque o time alterou algumas estimativas do trabalho restante.
![image](https://user-images.githubusercontent.com/52088444/232315506-21acc95c-1341-4128-9fe7-deee08a0cdeb.png)

- A partir desse sprint, o projeto prosseguiu bem, chegando até a Sprint sete, que podemos ver uma diminuição do progresso, mas que depois foi rapidamente recuperado.
![image](https://user-images.githubusercontent.com/52088444/232315534-b1cfb522-f2b5-45d4-aad0-603235b9971c.png)

Como podemos ver, o uso desse gráfico é bem simples e ele funciona muito bem em várias situações e em vários times. Entretanto, em projetos com muitas mudanças de requisitos, talvez seja interessante utilizar o gráfico de Burndown alternativo.

**Gráfico de BurnDown do produto alternativo.
![image](https://user-images.githubusercontent.com/52088444/232315604-5a5210fd-0583-4ca2-96f7-4ce35113adc7.png)

O gráfico de bBurndown do produto ou release típico do scrum, mostra um único valor a mudança na quantidade de trabalho restante. Em alguns casos, sua simplicidade é maravilhosa. Entretanto, ela também pode mascarar o que pode estar acontecendo em um projeto.

- Por exemplo, suponha que um time esperasse avançar 40 horas, pontos ou o que for, mas o último gráfico de Burndown da Sprint mostra apenas o progresso de dez.

O time foi mais lento do que o esperado ou mais trabalho foi acrescentado ao incremento? Como saber isso?

**Neste gráfico de burndown, a altura de cada barra representa a quantidade de trabalho restante no release.
![image](https://user-images.githubusercontent.com/52088444/232315701-23bfc42c-e2c0-400c-ad8f-085a1cd8ec5f.png)

Eu prefiro, particularmente, estimar os itens do backlog do produto em pontos de história, porque eles indicam o valor de negócio que estamos adicionando ao projeto. Se fossem apenas horas, não teríamos certeza se essas horas têm algo de útil entregue nelas.
- Começamos o projeto, então, com 175 pontos de história ao final da Sprint um.
![image](https://user-images.githubusercontent.com/52088444/232315768-d6d350d5-d156-44b3-972e-8df3ddb0860d.png)
- 25 pontos foram entregues, restando 150 a serem concluídos 
![image](https://user-images.githubusercontent.com/52088444/232315781-aeb3a5d2-835a-4692-b0e4-9af27f758f5a.png)
- no final da Sprint Três Temos 120 pontos ainda a serem entregues e é aí que começa a bagunça.
![image](https://user-images.githubusercontent.com/52088444/232315810-c22b1246-db1c-4cfb-8667-c62ba02dbfac.png)
- Antes do inicio da Sprint quatro, o dono do produto acrescentou trabalho ao projeto.
![image](https://user-images.githubusercontent.com/52088444/232315838-0d0f7a31-4ecd-4931-908d-b60891730da5.png)
- Este trabalho adicional é mostrado na parte inferior do gráfico, logo abaixo do eixo X.
- Você pode ver que a altura vertical da Sprint quatro vai aproximadamente de -40 a 95 ou 135 pontos de trabalho remanescentes.
![image](https://user-images.githubusercontent.com/52088444/232315894-d236c63e-d8f5-4a5a-a36a-c187671dd11a.png)
- 40 desse 135 pontos são de trabalho novo 
- antes do início da Sprint Seis algum trabalho foi removido pelo dono do produto, Veja que a barra da Sprint seis abaixo do eixo X diminuiu uns 30 pontos.Já a parte superior dessa barra também diminuiu.as isso é por conta do trabalho dos desenvolvedores, que entregaram uns 25 pontos de história.
![image](https://user-images.githubusercontent.com/52088444/232315930-b8438c54-0796-4517-9eee-c1871b83d844.png)
- O mesmo aconteceu com a Sprint sete.Os desenvolvedores entregaram 25 pontos de história e o dono do produto não acrescentou mais nada,nem tampouco removeu 
![image](https://user-images.githubusercontent.com/52088444/232315997-f2b3ec86-5f2f-4037-86f3-0db5a405288a.png)

**para prever quando o projeto encerrará, devemos levar em conta as tendências atuais. Assim, você desenha as linhas em vermelho, de acordo com as tendências das barras e vai ter uma noção aproximada de quando o projeto irá terminar.

![image](https://user-images.githubusercontent.com/52088444/232316073-01580caa-b47b-44ee-9981-27574b6bab55.png)

## Gráfico de Burnup

Já vimos o Gráfico de Burndown do produto que nos permite acompanhar o andamento do projeto.

Veremos agora o gráfico de Burnup, com o qual também é possível realizar o acompanhamento do projeto.

Tanto Burndown como Burnup representam um progresso na entrega do trabalho. Basicamente, a diferença é na forma como os dados são apresentados.

O Burn Down mostra o quanto falta para atingir a meta.
![image](https://user-images.githubusercontent.com/52088444/232316387-6ac27c15-8e96-4f97-b94d-98e5c550550c.png)

Enquanto o burnup mostra o que já foi feito até o momento.
![image](https://user-images.githubusercontent.com/52088444/232316420-2e644b48-2c33-48f6-882d-c2386db30f77.png)

Esse gráfico é construído sobre dois eixos, no eixo horizontal e medido o fator tempo e no eixo vertical temos o fator que representa o montante de trabalho.
![image](https://user-images.githubusercontent.com/52088444/232316540-f19a3bea-d225-41f2-9661-c270d987af98.png)

Este montante de trabalho pode ser representado em pontos de história, horas, etc. De acordo com o que é utilizado no dia a dia de trabalho pela equipe. Nesse gráfico vemos duas linhas. Azul representa o montante de trabalho entregue ao cliente, ou seja, representa o total de histórias ou itens do backlog entregues ao longo do projeto. A Linha Vermelha representa o montante de trabalho que está sendo pedido pelo cliente, ou seja, representa
o total de histórias ou itens de back log criadas para o projeto.
![image](https://user-images.githubusercontent.com/52088444/232316624-75838d43-02ac-4bc4-8212-1c5a4beddd54.png)
A distância entre estas duas linhas representa a cada dia, ou outra unidade de tempo utilizada, o montante de trabalho que falta ser entregue para que se atinja o objetivo do projeto naquele momento.

**Escopo versus entregas.

![image](https://user-images.githubusercontent.com/52088444/232316717-3e3ba72d-46a1-41ce-a884-e57dd4deab57.png)

A análise mais imediata que podemos fazer sobre este gráfico é a comparação do quanto o escopo do projeto evoluiu com quanto de trabalho foi entregue ao longo do tempo.

Se o escopo do projeto começa a crescer muito mais do que a quantidade de trabalho entregue, então podemos ter um problema, pois o projeto está crescendo em demandas, mas a velocidade de entregas da equipe não está acompanhando o ritmo de crescimento dessas demandas.

E o que fazer nesse caso?
![image](https://user-images.githubusercontent.com/52088444/232316859-92d11930-92c3-4f65-b8be-25ca7af6359d.png)

Temos algumas alternativas:
- checar quais impedimentos podem estar impactando a velocidade das entregas.
- Checar qual a razão pela qual as demandas estão crescendo tão rapidamente. E alertar o cliente que, do jeito que as coisas vão, o projeto não vai terminar nunca.
- Estudar um possível aumento na equipe a fim de aumentar a velocidade das entregas. Sempre lembrando que um aumento ou modificação no time resultará em uma queda de produtividade inicial até que o novo membro esteja habilitado para o trabalho.

**Regularidade das entregas.

![image](https://user-images.githubusercontent.com/52088444/232317243-09897f05-6191-4fd3-a1b4-1969eb46ade6.png)

Outra análise interessante é sobre a regularidade das entregas do projeto frente ao objetivo. 
Para esta análise, traçamos uma linha desde a origem do gráfico até o ponto que representa o total de demandas no último dia representado no gráfico.
conforme a linha verde que apresentamos.
- Se a linha azul está sempre próxima da linha verde, mais equilibrado está o andamento do projeto. Além disso, com essa linha é possível avaliar se estamos adiantados ou atrasados com as entregas.
        - Caso a linha azul esteja acima da linha verde, estamos adiantados.
        - Caso a linha azul esteja abaixo da Linha Verde, estamos atrasados.

## Cumulative Flow Diagram(CFD)

Há diversas formas de medir e exibir o progresso do seu projeto, mas uma das formas mais comuns, principalmente entre os praticantes do Kanban, é a utilização do cumulativo flow, um diagrama ou CFD.

O CFD é um gráfico que exibe o progresso de um processo em que há diversos estágios pelos quais um item deve passar até estar pronto.

![image](https://user-images.githubusercontent.com/52088444/232318532-3163d59c-dcf3-40e2-8ff3-c12599ed0841.png)

Equipes de Scrum utilizam um gráfico similar, o burndown em que se exibem as quantidades de itens a serem completados na iteração e que vão sendo queimados conforme são entregues.
![image](https://user-images.githubusercontent.com/52088444/232318749-9900fb1b-a1e5-4fbd-96c3-e028f0314603.png)

O que acontece com o burndown e que uma grande quantidade de informações sobre o que está acontecendo com os itens não fica visível, 

Com o CFD por outro lado, são exibidos também o estado dos itens, mesmo antes de estarem prontos. A inclusão das fases torna o gráfico mais complexo de ser montado do que um burndown.

**Como o cfd é montado?

Vamos supor que você desistiu dessa vida louca de projetos e decidiu abrir uma confeitaria de bolos. Vamos imaginar que os passos do seu processo de produção sejam os seguintes:
- preparar a massa, 
- assar a massa, 
- preparar recheio e coberturas, 
- rechear confeitar.

Imagine que você conseguiu ajuda da sua família. Duas tias e sua mãe entram nessa empreitada.

Aí ficou combinado que você executará os passos um e dois.

Sua tia mais velha, a Joana, prepara os recheios e coberturas.

A sua tia mais nova recheia os bolos e a sua mãe os confeita.

Se a cada 30 minutos você tirasse uma fotografia do momento e olhasse quantos itens estão em cada fase.

Você teria algo parecido com que segue nessa tabela?

![image](https://user-images.githubusercontent.com/52088444/232318963-807cfda5-acb0-429b-be70-443840aae681.png)

- Agora veja como montamos o gráfico.

![image](https://user-images.githubusercontent.com/52088444/232318992-651c1186-5363-44c1-bf06-959d752dbaf4.png)

- Comece da direita para a esquerda. Primeiro, marque um ponto com a quantidade de itens já prontos.
![image](https://user-images.githubusercontent.com/52088444/232319053-1173659c-f88b-4bf9-b19c-25c52f94de70.png)
- Trace uma reta do ponto anterior até o atual. Neste caso, o ponto anterior é o zero e preenche a parte interna. Escolha uma cor diferente para cada item.
- A partir do ponto de pronto, some a quantidade de itens que está no quinto passo do processo, ou seja, confeitar.
![image](https://user-images.githubusercontent.com/52088444/232319117-b4b5dfd3-247a-43db-90f1-6728ee0bb20c.png)
- Trace uma reta do ponto anterior até o atual e preencha a sua parte interna. Escolha uma cor diferente do item anterior.
![image](https://user-images.githubusercontent.com/52088444/232319229-164f85cc-f8df-42fa-ac58-5311ddd11593.png)
- Vá colocando os pontos relativos aos demais passos do processo.
- Veja este ponto.
![image](https://user-images.githubusercontent.com/52088444/232319261-d738ecd1-e9c3-48a7-85cf-fc4631728409.png)
Ele representa a fase Preparar recheio e cobertura. Nesta fase, a tabela indica que existem três itens em produção e é por isso que ele é plotado aqui.

A ideia de ser cumulativo é que sempre quando se fala que há 18 itens prontos como indicado no momento, cinco, quer dizer que esses itens já passaram por todas as fases anteriores, ou seja, já são bolos, batidos, assados, recheados e enfeitados.
![image](https://user-images.githubusercontent.com/52088444/232319310-51338d7e-04fd-4003-a54f-b814faec9290.png)


**Veja a seguir um exemplo de um gráfico pronto que mostra possíveis fases no desenvolvimento de um software.

Agora vamos ver como interpretar esse gráfico:
![image](https://user-images.githubusercontent.com/52088444/232319343-41992dec-3b2c-40bb-ab1d-38c13d8228c9.png)


Traçando uma linha horizontal entre determinados estados, é possível extrair o tempo médio aproximado que os itens levam para serem processados e entregues.
- O tempo entre assumirmos o compromisso com a entrega e a entrega, de fato é chamada de lead time.
- Já o cycle time ou tempo de ciclo é o tempo que se leva para construir um item.
- Uma linha vertical mostra a quantidade exata de itens em trabalho na linha do tempo.
- Outro ponto interessante a se notar é a relação entre as taxas de entrada e de saída em um fluxo contínuo. Quanto mais paralelas estiverem, melhor. Ou seja, se estivermos controlando uma linha de produção, como a fábrica de bolos, esse é um bom indicativo.

Já em um projeto, deve haver uma convergência em algum ponto do tempo indicando a finalização do projeto. Logo, é importante que a taxa de saída seja maior que a de entrada para que todos os itens, em algum momento do tempo, sejam completamente processados.


##  Revisão da Sprint

O propósito da revisão da Sprint é inspecionar o resultado da Sprint e determinar as adaptações futuras.

O Time Scrum apresenta os resultados de seu trabalho para as principais partes interessadas e o progresso em direção a meta do produto, é discutido na revisão da Sprint.
- Essa reunião tem a duração de 04horas para uma Sprint de um mês.
- Se a Sprint tiver menor duração, a reunião deve ser proporcionalmente reduzida.

Qualquer pessoa pode participar e seu principal objetivo é entregar mais um incremento, mostrando àspartes interessadas o que foi produzido na Sprint. Mesmo que possamos ir liberando incrementos ao longo da Sprint, como indicado no guia do Scrum.A revisão da Sprint ainda deve ser realizada, pois nela mostraremos todos os itens já liberados e como eles estão interagindo entre si.

Além disso, as partes interessadas poderão ter uma visão integrada do que mudou em seu ambiente, de acordo com o feedback recebido. Os participantes dessa reunião colaboram e decidem sobre o que fazer a seguir, ou seja, o cliente, a partir do que viu, pode solicitar alterações, inclusão de novas funcionalidades ou ainda pedir que itens previstos para as próximas Sprint sejam retirados. Dessa forma, o backlog do produto será ajustado para refletir essas solicitações.

O Time Scrum só deve apresentar os itens que estão 100% finalizados de acordo com os critérios de pronto, e claro nesta reunião devemos apresentar o produto em funcionamento e não um ppt com a lista das funcionalidades entregues.

**Qual é o grande objetivo desta reunião?

A revisão da Sprint atrai feedback vital das principais partes interessadas.

Essas reuniões são, ou pelo menos deveriam ser, um evento social, onde equipes diferentes podem interagir umas com as outras e discutir seu trabalho, fazer uma apresentação, força equipe a realmente terminar as coisas e liberá-las, sem elas a tendência de liberar pilhas de coisas 99% prontas. Com apresentações, somos obrigados a ter menos itens prontos, mas esses itens estarão realmente prontos, e isso é muito melhor do que entregar coisas feitas pela metade e que com certeza irão poluir a próxima Sprint.

Uma apresentação de sprints bem feita tem um efeito profundo. A equipe ganha crédito por suas realizações e eles se sentem bem. Além disso, pessoas que estão de fora do dia a dia do projeto podem ver o que a equipe está fazendo.

**o papel de cada um.

- Segundo o guia do scrum, ninguém lidera ou controla essa reunião. Todos os integrantes do time scrum em comum acordo, vão acertando o que precisa ser apresentado.
Veja que, como todos os eventos previstos no Scrum, esta é uma reunião informal, o que incentiva a colaboração.
- Todos os integrantes do time Scrum devem participar e o dono do produto pode e deve convidar as principais partes interessadas para participar também.
- Itens que não atenderem à definição de pronto serão rejeitados e retornarão ao backlog do produto.
- Itens rejeitados não têm a obrigatoriedade de serem desenvolvidos na Sprite subsequente. Isso vai depender do julgamento do dono do produto de acordo com os critérios de entrega de valor. 
- É muito comum que o dono do produto comande esta reunião, já que o cliente estará presente. Embora o guia do scrum não recomende ninguém, mas veja, o dono do produto apenas comanda a agenda da reunião.
- Quem comanda a apresentação do que está sendo entregue são os desenvolvedores.
- O Scrum Master deve garantir que a reunião vai ocorrer e explicar qual é o seu objetivo para os novatos no framework. Ele também explica que a reunião deve se manter dentro do time box apropriado.

## Retrospectiva da Sprint

A  Sprint se encerra em uma reunião chamada Retrospectiva da Sprint.

Uma das regras do Scrum é que sempre existem formas de se melhorar, não importa o quão pequena seja essa melhoria.

Assim, uma reunião de lições aprendidas deve ser realizada logo após a reunião de revisão. A chamada retrospectiva da Sprint a duração da retrospectiva da Sprint é normalmente de 03horas para uma Sprint de um mês. Se a Sprint for menor, esta reunião deverá ter sua duração reduzida proporcionalmente.

À principal finalidade dessa reunião é agregar lições aprendidas, e falar de lições aprendidas é falar de qualidade e melhoria contínua.

As lições aprendidas são a base para alcançarmos o nível de excelência desejado, ou seja, são alicerce para o aperfeiçoamento contínuo. Afinal, só podemos ser melhores se aprendermos com nossos erros e nossos acertos.

Assim, na reunião de retrospectiva da Sprint, devemos inspecionar como:

- a última Sprint foi em relação às pessoas, 
- relações, 
- processos, 
- ferramentas 
- definição de pronto.

O time scrum deve refletir sobre o que aconteceu na Sprint:
- Todos da equipe estão comprometidos?
- Faltou participação de alguém? do dono do produto, do scrum master?
-  As ferramentas são adequadas? 
-  as reuniões foram adequadas? 
-  O processo Scrum está andando bem? 
-  Nossa definição de pronto está adequada? 
-  Erros no produto aconteceram por conta de uma definição de pronto fraca?

Esses são exemplos de perguntas que o time pode fazer durante a retrospectiva.
Identificar e ordenar os principais itens que foram bem e as potenciais melhorias. É importante observar que se deve identificar tantos pontos que a equipe achou ruim quanto os pontos em que a decisão foi acertada. Uma maneira de realizar essa parte da reunião é usando post-its coloridos, em que cada membro escreve suas observações, sendo uma cor para pontos positivos e outra para os pontos negativos.

- Criar um plano de implementação de melhorias. O importante desta reunião não é apenas explicitar os erros e acertos das experientes, mas sim elaborar um plano a ser colocado em ação para que os erros levantados não sejam repetidos, mas que os acertos, sim. Portanto, não basta a equipe dizer que algo não está bom. Deve também propor soluções para evitar a recorrência desse erro e se comprometer a seguir esse plano na próxima Sprint.

A adaptação é essencial para o scrum. Portanto, é preciso que o processo mude para o seu desenvolvimento estar sempre melhorando em qualidade.

**O papel de cada um.

Segundo o guia do scrum, ninguém lidera ou controla essa reunião. Todos os integrantes do time scrum devem indicar o que deu certo e o que deu errado na frente, de forma a que todo o processo possa melhorar. Veja que, como todos os eventos previstos no Scrum, esta é uma reunião informal, o que incentiva a colaboração.Todos os integrantes devem obrigatoriamente participar e, neste caso, todos exercem o mesmo papel de membros do time scrum. Ou seja, aqui não há distinção entre o papel de scrum master ou o dono do produto, ou ainda desenvolvedor.

## Speed Boat

A ferramenta Speed Boat é uma forma lúdica de realizar a retrospectiva da Sprint .

O objetivo de uma cerimônia de retrospectiva é identificar as práticas e atitudes que deram certo ou que deram errado, visando melhorar a próxima iteração.Portanto, para o sucesso dessa retrospectiva, os participantes devem ter a liberdade de expressar suas opiniões, sejam elas boas ou ruins.Entretanto, é natural que alguns participantes não se sintam à vontade para expressarem suas frustrações verbalmente. Principalmente se há uma equipe recém formada, com receio de ferir alguém. Para buscar contornar essa situação, uma boa saída é utilizar o jogo Speed Boat. Esse jogo visa dar aos participantes uma oportunidade de escreverem suas frustrações, refletindo no que é verdadeiramente importante. Essa prática gera uma oportunidade em cada participante de refletir antes de escrever, pois apenas expressando verbalmente faz com que a maioria das pessoas não reflita no que estão falando. No que pode ser algo trivial. Além disso, esse jogo é muito bom para aquelas pessoas que se queixam de tudo, pois escrevendo suas frustrações, as pessoas se acostumam a quantificar o impacto do que está escrevendo, contribuindo assim muito mais para a cerimônia de retrospectiva. A utilização da prática Speed Boat também é muito simples. 

**iNICIANDO A DINÂMICA

A história do nosso time está em um barco em direção à ilha paradisíaca do sucesso.
De dentro do barco, analisaremos alguns aspectos dessa viagem, inicialmente de forma individual e mais tarde em conjunto.

- A Ilha. Como seu time, vê a ilha paradisíaca do sucesso?
![image](https://user-images.githubusercontent.com/52088444/232321167-c913fd46-9ba6-473d-8f38-7bca84fa95f5.png)

- Comece a atividade pedindo para que cada um anote em post-its a onde querem chegar juntos. Pode ser ao final do projeto ou na próxima Release, na próxima iteração.  Se esta dinâmica já foi feita anteriormente relembre com o time se os objetivos continuam os mesmos?

- O vento, essa força que nos leva para a frente. Agora peça ao time que escrevam quais são as forças que impulsionam o time a chegar na Ilha.
![image](https://user-images.githubusercontent.com/52088444/232321244-27ee0b9c-86d8-4c10-bb03-d1a3665f085d.png)

- A ideia é não só identificar pontos fortes, mas também os motivadores.  Seu foco maior será em obter as forças do time âncora ou o que nos impede? 
- Esta terceira fase da dinâmica, onde vamos começar a analisar o lado negro da força?
![image](https://user-images.githubusercontent.com/52088444/232321285-cf1684f2-a15d-4acb-a488-950d5b67b190.png)
 Aqui, você facilitador deverá estimular o time a escrever nos post-its todo o tipo de impedimento que acontece com frequência, a infra demora a atender requisições? e existe muita burocracia? O cliente não está engajado? o dono do produto sumiu? As histórias estão mal escritas? Essa é a hora de falar desses assuntos que impedem que o time tem uma viagem tranquila.

- Rocha Ou os riscos que corremos na jornada?
![image](https://user-images.githubusercontent.com/52088444/232321364-35495ff5-4284-4013-acac-e0a504e35b3a.png)
É a vez de se perguntar e se quais são os riscos que podem ser controlados pelo time?  E se o fulano continuar chegando tarde todos os dias?  E se não conseguirmos aprender essa nova tecnologia a tempo? E se beltrano sair de férias sendo o cara que mais conhece do sistema?

- Analisando a viagem: agora que o time avaliou todos esses aspectos da sua jornada de forma individual. Vamos olhar de longe o panorama e eleger alguns itens para discussão. Dependendo da quantidade de post-its e do time box, você pode usar algum tipo de votação para identificar quais assuntos o time quer aprofundar.
Cabe ao facilitador resumir a história da viagem começando pelo destino, ressaltando os pontos fortes e o que o time aprecia.

-Mas existem algumas coisas que estão atrapalhando a viagem quando falarem sobre riscos. Sempre pergunte o que podemos fazer para que isso não aconteça ou para minimizar o seu impacto na viagem. Ao falar das âncoras, pergunte nós poderíamos ter feito alguma coisa diferente para que isto não nos impactasse?

Esta é uma atividade divertida e bem assertiva, pois além de avaliar pontos fortes e fracos, também permite trazer uma análise de riscos, uma sutil análise de comportamento, identificando motivadores e identificando se os objetivos das pessoas envolvidas estão alinhados com os da empresa.
