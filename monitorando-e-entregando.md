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





