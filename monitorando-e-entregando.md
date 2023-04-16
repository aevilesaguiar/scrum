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


Esse gráfico é construído sobre dois eixos no eixo horizontal e medindo o fator tempo e no eixo vertical

temos o fator que representa o montante de trabalho.

Este montante de trabalho pode ser representado em pontos de história, horas, etc.

De acordo com o que é utilizado no dia a dia de trabalho pela equipe.

Nesse gráfico vemos duas linhas.

Azul representa o montante de trabalho entregue ao cliente, ou seja, representa o total de histórias

ou itens do backlog entregues ao longo do projeto.

A Linha Vermelha representa o montante de trabalho que está sendo pedido pelo cliente, ou seja, representa

o total de histórias ou itens de back log criadas para o projeto.

A distância entre estas duas linhas representa, a cada dia ou outra unidade de tempo utilizada, o

montante de trabalho que falta ser entregue para que se atinja o objetivo do projeto naquele momento.

Escopo versus entregas.

A análise mais imediata que podemos fazer sobre este gráfico é a comparação do quanto o escopo do projeto

evoluiu com quanto de trabalho foi entregue ao longo do tempo.

Se o escopo do projeto começa a crescer muito mais do que a quantidade de trabalho entregue, então

podemos ter um problema, pois o projeto está crescendo em demandas, mas a velocidade de entregas da

equipe não está acompanhando o ritmo de crescimento dessas demandas.

E o que fazer nesse caso.

Temos algumas alternativas checar quais impedimentos podem estar impactando a velocidade das entregas.

Checar qual a razão pela qual as demandas estão crescendo tão rapidamente.

E alertar o cliente que, do jeito que as coisas vão, o projeto não vai terminar nunca.

Estudar um possível aumento na equipe a fim de aumentar a velocidade das entregas.

Sempre lembrando que um aumento ou modificação no time resultará em uma queda de produtividade inicial

até que o novo membro esteja habilitado para o trabalho.

Regularidade das entregas.

Outra análise interessante é sobre a regularidade das entregas do projeto frente ao objetivo.

Para esta análise, traçamos uma linha desde a origem do gráfico até o ponto que representa o total

de demandas no último dia representado no gráfico, conforme a linha verde que apresentamos.

Se a linha azul está sempre próxima da linha verde, mais equilibrado está o andamento do projeto.

Além disso, com essa linha é possível avaliar se estamos adiantados ou atrasados com as entregas.

Caso a linha azul esteja acima da linha verde, estamos adiantados.

Caso a linha azul esteja abaixo da Linha Verde, estamos atrasados.





