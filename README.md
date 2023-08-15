# Notas de Liderança para pessoas em Tech

Esse markdown foi desenhado como um compilado do meu processo de desenvolvimento de liderança de pessoas. Diferente de um artigo, ele é um documento evolutivo e iterativo. O objetivo é compartilhar os princípios e ferramentas principais em uma liderança técnica que possam ajudar a mais pessoas terem essa experiência.

Agradeço a ideia vinda do [Kamil Sindi](https://github.com/ksindi/managers-playbook) e incrementada como todo apoio e Material da [a.karta](https://akarta.com.br/) e outras referências que serão mantidas como link.

# Sumário
- [Anotações de Liderança para pessoas em Tech](#anotações-de-liderança-para-pessoas-em-tech)
- [Sumário](#sumário)
- [Time](#time)
- [O papel e características do líder neste time](#o-papel-e-características-do-líder-neste-time)
- [Cerimônias e reuniões](#cerimônias-e-reuniões)
  * [One on Ones](#one-on-ones)
    + [Primeiras 1:1s com líderes de líderes](#primeiras-1-1s-com-l-deres-de-l-deres)
    + [Stay Interviews](#stay-interviews)
    + [Técnicas de feedbacks](#técnicas-de-feedbacks)
  * [Alinhamento de Objetivos](#alinhamento-de-objetivos)
    + [Tour of Duty](#tour-of-duty)
  * [Comemorações e Entrega](#comemorações-e-entrega)
- [Auto-conhecimento](#auto-conhecimento)
  * [RAIN](#rain)
- [Gerenciamento Lean de Software](#gerenciamento-lean-de-software)
  * [Complexidade: A raiz da maioria dos problemas em Software](#complexidade--a-raiz-da-maioria-dos-problemas-em-software)
  * [Princípio do baixo acoplamento](#princípio-do-baixo-acoplamento)
  * [Principio da alta iteração e pequenas entregas](#princípio-da-alta-itera--o-e-pequenas-entregas)
  * [Princípio da automação](#princípio-da-automação)
  * [Princípio da visibilidade](#princípio-da-visibilidade)
  * [Princípio da diversidade](#princípio-da-diversidade)

<!-- <small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small> -->

# Time

Características:
* Célula auto-suficiente, geralmente cross-functional e com o mínimo de interfaces 
* Composta por diversos papéis e que respeite a regra do [Two Pizzas Team](https://buffer.com/resources/small-teams-why-startups-often-win-against-google-and-facebook-the-science-behind-why-smaller-teams-get-more-done/) (o tamanho do time no deve superar o que duas pizzas são capazes de alimentar em uma noite escura de inverno) 
* Times **não** devem ser pensados em aumentar output da sua fase da cadeia de valor, mas maximizar o valor do que entrega ao cliente (mesmo que seja uma parte pequena do processo)
* Times tem fases de maturação e dinâmica de relacionamento interno e externo. Aos poucos, times vão criando sua própria cultura e regras que geram conflito e/ou aumentam a produtividade. Um bom modelo é o [Modelo de Tuckman](http://www.communicationcache.com/uploads/1/0/8/8/10887248/developmental_sequence_in_small_groups_-_reprint.pdf)

> “In teams which scored highly on architectural capabilities, little communication is required between delivery teams to get their work done.
[...] Architecture and teams are loosely coupled. To enable this, we must also ensure delivery teams are cross-functional, with all the skills necessary to design, develop, test, deploy, and operate the system on the same team.”
>> [*Jez Humble; Nicole Forsgren; Gene Kim - Accelerate*](https://www.amazon.com.br/-/pt/dp/B07B9F83WM/)


> “This is what the original “two-pizza” team was intended to do. Not merely to execute independently, but to deliver customer value independently. The core idea behind autonomy is not arranging teams to maximize outputs of steps in the value chain, but defining value chains in such a way that a single, tight-knit team can be unleashed upon it. Every team has to define its output in terms of customer success because that’s how the organizational boundary is drawn.”
>> [*Kislay Verma - Independence, autonomy, and too many small teams*](https://kislayverma.com/organizations/independence-autonomy-and-too-many-small-teams)

> Ralph Waldo Emerson disse: “Todo homem que encontro é superior a mim de algum modo. E, nesse particular, aprendo com ele.”
>> [*Dale Carnegie - Como fazer amigos e influenciar pessoas*](https://www.amazon.com.br/Como-Fazer-Amigos-Influenciar-Pessoas/dp/8504018024)


# Papel 

Premissa: As pessoas gostam de ver a conexão do seu trabalho em impactos positivos para os clientes e, consequentemente, alinhando-se ao propósito da empresa. O lider de pessoas é a figura que representa a empresa para o time. (["Pessoas pedem demissão por causa do líder, não da empresa"](https://g1.globo.com/economia/concursos-e-emprego/noticia/2019/11/22/8-em-cada-10-profissionais-pedem-demissao-por-causa-do-chefe-veja-os-motivos.ghtml))

Apesar de variar de empresa para empresa, no cenário de Desenvolvimento de Software, o líder é aquele que tem a responsabilidade de:
* Respeitar a individualidade de cada pessoa, praticando frequentemente escuta ativa
* Encontrar aprendizado das falhas ao invés de culpados
* Comunicar um forte senso de propósito e elevar a barra do time, investindo no desenvolvimento das pessoas dando tempo, espaço e recurso para experimentar e aprender
* Ser um facilitador, um meio de campo, entre as diferentes forças que interagem em um time

> "Minha popularidade, minha felicidade e meu senso de valor dependem, em grande medida, da minha habilidade no trato com as pessoas."
>> [*Dale Carnegie - Como fazer amigos e influenciar pessoas*](https://www.amazon.com.br/Como-Fazer-Amigos-Influenciar-Pessoas/dp/8504018024)

Atenção ao viés congnitivo: O inconsciente é quem direciona boa parte do nosso comportamento e decisões. Reconhecer isso permite promover um ambiente que evita preconceito (juízo de valor baseado em esterótipo) e discriminação negativa (situações de tratamento diferenciado para certos grupos que reforçam ou reprimem tal grupo já reprimido) 
> “Não somos nós que tomamos muitas das decisões do nosso dia a dia” 
>> [*Don Ariely*](https://www.blend-edu.com/vies-inconsciente-nas-empresas-entenda-o-conceito-e-dicas-para-minimiza-los-na-organizacao/). 

# Cerimônias e reuniões

Algumas cerimônias são bem comuns no mundo de Software. Aqui traremos algumas dicas

## One on Ones

**Objetivo:** Esta é a cerimônia mais importante na construção de um relacionamento líder-liderado. É aqui que acompanhamos:
- O passado: Feedback sobre comportamentos e entregas
- O presente: Performance, clima e relacionamento com a equipe
- O futuro: Tour of duty e alinhamento de expectativas

Este é o momento que deve ser individualizado: o que funciona para uma pessoa pode não funcionar para outra (ou até mesmo para a mesma pessoa em um tempo diferente). 

No entanto, não há nada para se preocupar. Entender que você está falando com um outro ser humano e que todo confronto deve ter direitos universais como respeito, competencia, status social e autonomia ([High-Performing Teams Need Psychological Safety. Here’s How to Create It](https://hbr-org.cdn.ampproject.org/c/s/hbr.org/amp/2017/08/high-performing-teams-need-psychological-safety-heres-how-to-create-it))
* Esta pessoa tem crenças, perspectivas e opiniões, assim como eu
* Esta pessoa tem expectativas, ansiedades e vulnerabilidade, assim como eu
* Essa pessoa tem amigos, famílias e, talvez, filhos que os amam, assim como eu.
* Esta pessoa quer se sentir respeitada, apreciada e competente, assim como eu
* Esta pessoa deseja paz, felicidade e curtição, assim como eu.

**Premissa:** Este momento tem como premissa as [4 fases do aprendizado](https://focuslife.com.br/4-fases-do-aprendizado-pnl/). Nela é possível navegar nas competências que faz sentido para a pessoa e nos desejos que ela tem de vida e de carreira. A consciência é algo poderoso pois só podemos mudar algo quando a gente se conscientiza.  

![Fases do Aprendizado](./images/fases-do-aprendizado.png)

**Duração:** Ela pode variar de pessoa para pessoa mas geralmente é uma reunião de 25 a 40 minutos. Onde segue-se geralmente esta estrutura:
1. Abrir espaço para deixar o liderado trazer o tópico principal (Começar sempre com: E aí, como está sendo a semana?)
2. Trazer um dos tópicos abaixo, se tiver tempo.
3. Finalizar a 1:1 com algo "O que podemos fazer para evoluirmos no que falamos hoje? Vamos chegar a uma solução em conjunto?"

**Perguntas poderosas:** 
* 1:1s de futuro profissional
  * Como você vê o seu futuro profissional? O que você acredita que a empresa já conseguiu te ajudar neste sentido? Como a empresa consegue ajudar nas conquistas que você almeja? Como posso ajudar?
  * Você sente que está progredindo nos seus grandes objetivos aqui?
  * Seu trabalho é o que você esperava quando aceitou? Como você descreveria o ambiente de trabalho no time?
  * Quais oportunidades você gostaria de querer estar no futuro? No espectro de 6 meses a 1 ano, onde voce quer estar?
* 1:1s para falar sobre o time
  * Hoje você tem um ponto focal no time? Alguém que você admira? Com quem você tem mais dificuldade em trabalhar? Por quê?
  * Dos valores da empresa, você acredita que estamos falhando em algum?
* 1:1s de acompanhamento de projeto
  * Como esse projeto está indo? O que podemos fazer para fazermos melhor? Algo te travando? Algo não está claro? Posso ajudar em algo
  * Dentro deste projeto, qual seria o resultado ideal? E como podemos alcançá-lo na sua opinião?
* 1:1s sobre feedback sobre o trabalho como lider
  * Como lider, o que não estou fazendo para ajudar o seu dia-a-dia?
  * Como lider, o que estou fazendo para ajudar o seu dia-a-dia?
  * O que não deveria estar fazendo e estou?
* [1:1s na entrada de pessoas no time (onboarding)](https://www.shrm.org/ResourcesAndTools/hr-topics/talent-acquisition/Pages/Effective-Onboarding-Should-Last-for-Months.aspx)
* Primeira 1:1s com as pessoas de um time que já está em execução (entrada de um novo líder)
  * Conhecendo um ao outro - Nome, histórico de empresa, algum fator relavante
  * O que você gosta do seu trabalho no dia-a-dia? O que mais sente vontade de acordar e trabalhar?
  * Como você enxerga meu papel aqui? Como posso te ajudar no dia-a-dia?
  * O que está indo bem dentro do time hoje? O que ainda acha que tem espaço de melhoria no time hoje?

### Primeiras 1:1s com líderes de líderes

Assim como os liderados, líderes também precisam ter clareza sobre o seu trabalho e as expectativas sobre eles. Aqui são algumas perguntas poderosas

* O que você espera do time no final do quarter? Quais são os critérios de sucesso (padrão de desempenho, entregas, métricas, iniciativas) que devem avaliar minha performance?
* Qual é o seu maior medo sobre nossa temática?
* Quais desafios da área meu time é diretamente responsável?
* Como vemos minha contribuição para esse momento do time/área/negócio?

Referências: [[1](https://larahogan.me/blog/first-one-on-one-questions/)]

### Stay Interviews

**Objetivo:** Uma 1:1 um pouco diferente é a Stay Interview. Esta cerimônia permite habilitar uma conversa sincera do momento atual da pessoa, como ela está se sentindo em relação à empresa e a seus objetivos ali dentro. 

Segundo o Projeto Aristóteles, existem fatores de sucesso dos times relacionado a 5 características que podem ser observadas através das Stay Interviews 
> * Psychological safety - “If I make a mistake on our team, it is not held against me.”
> * Dependability - “When my teammates say they’ll do something, they follow through with it.”
> * Structure and Clarity - “Our team has an effective decision-making process.”
> * Meaning - “The work I do for our team is meaningful to me.”
> * Impact - “I understand how our team’s work contributes to the organization's goals.”
>> [Link para o Projeto Aristóteles](https://rework.withgoogle.com/guides/understanding-team-effectiveness/steps/identify-dynamics-of-effective-teams/)

Para a cerimônia ser efetiva, é necessário o entrevistador não tentar interromper ou se justificar, apenas perguntando e explicando a pergunta. Idealmente, uma stay interview é feita por uma pessoa que não seja líder direto, pois a ideia é ser uma conversa super sincera.

Inicia-se explicando a dinâmica, a motivação/importância de ouvir a pessoa e compartilhando que você irá fazer algumas anotações. Ao final, (1) agradecer por ter compartilhado e ser franco, (2) levantar os principais pontos anotados e (3) fazer um plano em conjunto levando em consideração o código de cultura da empresa.

**Duração:** De 20 a 1 hora. 

**Perguntas:**[[1](https://builtin.com/recruiting/stay-interview)] [[2](https://www.insperity.com/blog/stay-interview-questions/)]
1. (Meaning) O que você busca quando vem trabalhar todo dia?
2. (Meaning) Se você pudesse mudar uma coisa sobre o dia-a-dia, time ou empresa. O que seria?
3. (Impact) No último ano, quando que você saiu dizendo "este foi um ótimo dia de trabalho"?
4. (Impact) Qual a sua maior realização aqui? Você entende que seu trabalho está te fazendo evoluir como profissional?
5. (Psychological Safety) No ultimo ano, quando que algo te gerou ansiedade ou frustração? / O que te causa apreensão ou medo no seu dia-a-dia de trabalho?
6. (Psychological Safety) Em que situações você não se sentiu seguro de apresentar opiniões divergentes para uma pessoa ou time?
7. (Work-life balance) Como você avalia relação vida pessoal e trabalho? Como ela poderia ser melhorada?
8. (Dependability) Você concorda com o caminho que o nosso time está trilhando?
9. (Dependability) No último ano, quais os momentos que você sentiu ausência de ownership de tarefas ou problemas no nosso contexto? Você acredita que deveria ser endereçado por alguém? Se sim, quem?
10. (Structure and clarity) Quais de seus talentos não estão sendo usados no seu trabalho atualmente? / O que você gostava no seu último emprego/cargo que você não tem mais aqui?
11. (Leadership Dependability) Que tipo de feedback ou reconhecimento você gostaria sobre sua performance que você não está recebendo?
12. (Leadership Dependability) O que eu posso fazer para tornar o seu dia-a-dia melhor aqui com a gente?

### Exit Interviews

**Objetivo:** Uma 1:1 de fechamento focado em buscar aprender com a saída do membro do seu time

**Duração:** De 20 a 1 hora. 

**Perguntas:**[[1](https://www.indeed.com/career-advice/starting-new-job/exit-interview-questions)]
1. Quais motivações te fizeram deixar sua posição atual?
2. Como você se sente sobre sua liderança? Algum exemplo de situação ou sugestão para melhoria?
3. No último ano, quando que você saiu dizendo "este foi um ótimo dia de trabalho"?
4. Onde o time atual não conseguiu dar o suporte necessário para seus objetivos de carreira?
5. Você recomendaria esta empresa para outros procurando emprego? Sob quais aspectos?
6. Qual foi o critério que você adotou para o novo empregador?

### Técnicas de feedbacks

Essa palavra "feedback" pode ter uma conotação ruim para algumas pessoas, porém é de extremo valor quando bem aplicada. Como dito anteriormente, feedbacks devem ter como objetivo levar a situação para a consciência de uma pessoa e evitar situações onde a pessoa entra no modo de [luta-ou-fuga](https://www.buildthestage.com/giving-constructive-feedback-to-employees-in-spades/)

Existem algumas técnicas discutidas [aqui](https://veduca.sfo2.cdn.digitaloceanspaces.com/uploads/a15179eb372717b5d3e24064e5b41933.pdf). Aqui vamos explorar algumas delas. Mas o mais importante é tratar esta conversa com respeito e foco em um acionável, tratando a outra pessoa como um ser humano.

#### SCI

 Uma que vejo bastante uso é o que chamo SCI estendido (sempre focado em futuro) [[1](https://www.ccl.org/articles/leading-effectively-articles/closing-the-gap-between-intent-vs-impact-sbii/)]:

1. (Situação) Sabe quando...
2. (Comportamento) Percebi que o comportamento foi...
3. (Impacto) Naquele momento, me gerou...
4. Quando acontecer algo parecido, 
5. O que acha de ... 
6. Para que o impacto seja....

#### Compreender, Validar e convergir

1. Compreenda o ponto de vista da outra pessoa

2. Valide suas percepções.

3. Ofereça opções que acomodem as duas partes, encontrando formas justas de resolver as diferenças.
* Explique o que não te satisfaz na proposta do outro e o que te satisfaria;
* Peça uma posição de consenso e justa para as duas partes.

4. Ao final, pergunte quais critérios de consenso estão claros para vocês.

Utiliza perguntas poderosas para ententender o ponto de vista da outra pessoa:

* Como é que vê esta situação? Pode me dar um exemplo concreto? 
* Qual a importância que isto tem para você?
* O que o leva a dizer isso? Que informação adicional você tem? No que se baseia esse ponto de vista?
* Como é que isso funcionaria? Como podemos testar um caminho? 
* Como essa situação afeta outras pessoas importantes para você? 
* Que ideias, princípios e valores estão em jogo para você?
* Que impacto minha atitude teve sobre você? Como acha que contribui para o que está sentindo?
* Se isso acontecesse, o que significaria para você?


#### Citações


* [*Dale Carnegie - Como fazer amigos e influenciar pessoas*](https://www.amazon.com.br/Como-Fazer-Amigos-Influenciar-Pessoas/dp/8504018024)
  > Não adianta criticar, porque isso coloca a pessoa na defensiva e em geral faz com que ela tente se justificar. A crítica é perigosa porque fere o precioso orgulho do indivíduo, atinge seu senso de importância e desperta ressentimento. [...] Nosso desejo de aprovação é tão intenso quanto o medo da condenação. [...] Ao lidar com pessoas, devemos lembrar que não estamos tratando com criaturas lógicas, mas com seres emotivos, suscetíveis a preconceitos e motivados pelo orgulho e pela vaidade. 
  > [Por isso,] Em vez de condenar as pessoas, vamos tentar compreendê-las. Vamos tentar descobrir o que as leva a fazer o que fazem. Essa atitude é bem mais útil e interessante do que as críticas, além de cultivar a compaixão, a tolerância e a bondade. Saber tudo é perdoar tudo.

  > William James disse: “O mais profundo princípio da natureza humana é a ânsia de obter reconhecimento.” Veja bem: ele não falou “desejo”, “vontade” ou “aspiração”. Usou a palavra “ânsia”, que designa um tipo insaciável de fome humana, e os raros indivíduos que satisfazem essa carência de maneira honesta têm todas as pessoas na palma da mão, e “até o coveiro lamentará sua morte”.[...] Portanto, a única forma de influenciar as pessoas é falar sobre o que elas querem e mostrar como alcançar o que desejam.

  > “Se existe um segredo para o sucesso, ele consiste na capacidade de entender o ponto de vista do outro e enxergar não só com seus olhos, mas também com os olhos dele”, disse Henry Ford.[...] Enxergar o ponto de vista da outra pessoa e despertar nela um desejo ardente não deve ser encarado como manipulação para tirar proveito dela ou prejudicá-la. Todos os envolvidos devem ganhar com a negociação.

  > É possível fazer mais amigos em dois meses, demonstrando interesse por eles, do que em dois anos, tentando fazer com que os outros se interessem por você. [...] Demonstrar interesse genuíno pelos outros não só conquista amigos para você, como também pode fazer com que a clientela desenvolva um sentimento de lealdade à sua empresa.

  > Se você espera que as pessoas se sintam bem ao estar com você, você também precisa se sentir bem ao estar com as pessoas. [...Para isso, por exemplo.] Fale sobre assuntos que interessam ao outro.
  > Se obedecermos [a essa lei], raramente teremos problemas na vida. Na verdade, se obedecermos a essa lei, teremos inúmeros amigos e uma felicidade constante. Mas, no exato momento que a violamos, arranjamos problemas. A lei é a seguinte: Sempre faça com que o outro se sinta importante.

  > “Não existe nada intrinsecamente bom ou mau; tudo depende do que pensamos”, disse Shakespeare.

  > Se somos tão egoístas a ponto de não podermos irradiar um pouco de felicidade e fazer um pequeno elogio sem querer nada em troca, então merecemos o fracasso.

  > Convencido contra a vontade, Um homem ainda acredita na sua verdade. [...] Você pode estar coberto de razão enquanto defende seus argumentos, mas seu esforço para mudar o modo de pensar do outro provavelmente será tão inútil quanto se estivesse errado.

  > Nove entre dez vezes, uma discussão termina com cada parte ainda mais convencida de que está absolutamente certa. Não é possível ganhar uma discussão. Não é possível porque, se perdê-la, você perde. E se ganhar, você perde. Por quê? Bem, imagine que você venceu seu adversário, demonstrou a fragilidade dos argumentos dele e provou que ele está non compos mentis. E aí? Você se sentirá bem. E ele? Você fez com que ele se sentisse inferior. Feriu seu orgulho. Ele vai se ressentir do seu triunfo.  

  > Acolha a divergência. Lembre-se do ditado: “Quando dois sócios concordam o tempo todo, um dos dois não é necessário.” Se existe algum ponto sobre o qual você não havia pensado, agradeça a quem chamou sua atenção. Talvez essa discordância seja a oportunidade de se corrigir antes de cometer um erro grave. Desconfie da sua primeira impressão instintiva. Numa situação desagradável, nossa primeira reação natural é assumir uma postura defensiva. Cuidado.

  > Dê a seus oponentes uma oportunidade de falar. Deixem terminar o que têm a dizer. Não resista, não se defenda nem inicie uma discussão. [...] Procure pontos em comum: Depois de ouvir seus oponentes, trate primeiro dos pontos e das áreas em que vocês concordam. Seja sincero. Procure admitir e assumir seus erros. Peça desculpa por eles.
 
  > Prometa que vai refletir sobre as ideias de seus oponentes e estudá-las com cuidado. E fale com sinceridade. Seus adversários podem ter razão. É muito mais fácil concordar em avaliar seus próprios pensamentos agora do que tomar uma decisão apressada e, no futuro, se encontrar numa posição em que eles podem dizer: “Tentamos avisá-lo, mas você não quis escutar...” Agradeça sinceramente a seus oponentes pelo interesse demonstrado. Qualquer um que devota tempo a discordar de você está interessado nas mesmas coisas que você. Pense neles como pessoas que desejam ajudá-lo. Assim, será possível transformar oponentes em amigos. Adie a ação para permitir que os dois lados tenham tempo de refletir sobre o problema. Sugira uma nova reunião para o fim do dia ou o dia seguinte, quando todos os fatos poderão ser checados.


## Alinhamento de Objetivos

> "Uma vida com propósito é aquela em que eu entenda as razões pelas quais faço o que faço e pelas quais claramente deixo de fazer o que não faço." 

> "Até algum tempo atrás, a vida era muito menos complexa e a intenção principal era sobreviver. Isto é, obter recursos para montar uma família e ter um patrimônio que se pudesse deixar de herança. Como a sociedade hoje é mais focada no indivíduo, a ideia de propósito está marcada por um conceito que já existiu e voltou com força: o da realização."

*["Por que fazemos o que fazemos?" - Mario Sergio Cortella](https://www.amazon.com/Por-que-fazemos-Portuguese-ebook/dp/B01JT2I3DA/)*

Alinhar objetivos é essencial para uma boa comunicação líder-liderado. A importância de chegar a objetivos comuns do time e pessoais é que eles deixam clara a sua relação com as pessoas do time.

Abstraindo, uma pessoa líder trabalha com um liderado 2 tipos de Goals para um determinado tempo (Semestre/Trimestre):
1. Objetivo de entrega ou do time: Como um time, precisamos estar alinhados com os objetivos da empresa. Neste sentido, os objetivos aqui explorados são alinhados para que consigamos atingir um marco dentro da Organizaço e conseguir novos investimentos. 
2. Objetivo pessoal ou de desenvolvimento: Toda pessoa que está no grupo tem o interesse de se desenvolver

Os objetivos de time alinham somente que iremos passar de um ponto A para um ponto B.

```
A ...----|-----|-----|---- > B(performance)
```

Para uma organização continuar inovando. Esta passagem de fase muitas vezes não é suficiente. Fazer do mesmo jeito do que fazíamos ontem pode ser o primeiro passo para o fracasso. No entanto, alinhar as goals pessoais conseguem transformar a visão das pessoas, propondo e explorando novas soluções, transformando o tour de uma pessoa:

```

                    /-- > C,D(desenvolvimento)     ^
                   /                               | proximos 
                  /                                |
A----|-----|-----|---- > B(performance)            | tours
```

Para o desenvolvimento pessoal, existe um framework: 70/20/10 
* 70% do tempo na prática
* 20% do tempo com pessoas/mentores
* 10% do tempo em um estudo formal como livros ou cursos

### Tour of Duty

Uma das formas de entender melhor o desenvolvimento de uma pessoa é o Tour of Duty. Neste ponto alguns materiais que indico:
* [Curso introdutório de Tour of Duty no Linkedin](https://www.linkedin.com/learning/reid-hoffman-and-chris-yeh-on-creating-an-alliance-with-employees/welcome)
* [Artigo com template da RD Station](https://medium.com/rd-shipit/voc%C3%AA-sabe-o-seu-tour-of-duty-618c175be955)

## Comemorações e Entrega

> "Rotina não é monotonia, [...] a rotina consiste em uma série de procedimentos-padrão com os quais um processo completa. E esse nível de repetibilidade é o que torna a rotina mais adequada. [...] A monotonia é a morte da motivação. As pessoas [...] tentam alterar a situação quando veem o risco de monotonia”

*["Por que fazemos o que fazemos?" - Mario Sergio Cortella](https://www.amazon.com/Por-que-fazemos-Portuguese-ebook/dp/B01JT2I3DA/)*

> The most important characteristic of high-performing teams is that they are never satisfied: they always strive to get better.

[*Jez Humble; Nicole Forsgren; Gene Kim - Accelerate*](https://www.amazon.com.br/-/pt/dp/B07B9F83WM/)

> "A coisa mais incrível de vencer não é a vitória em si. É poder contar, ensinar outras pessoas sobre como você fez, por que fez, de que maneira fez, com que considerações fez e o que levou em conta. São os valores que você pratica que contam."

*["Seja foda! - Caio Carneiro"](https://www.amazon.com.br/Seja-foda-Portuguese-Caio-Carneiro-ebook/dp/B079GZM3P5)*

> Vamos parar de pensar em nossas realizações, nossos desejos, e tentar descobrir os pontos fortes da outra pessoa. Esqueça a bajulação. Ofereça um reconhecimento honesto e verdadeiro.
>> [*Dale Carnegie - Como fazer amigos e influenciar pessoas*](https://www.amazon.com.br/Como-Fazer-Amigos-Influenciar-Pessoas/dp/8504018024)

# Auto-conhecimento

> Qualquer tolo pode criticar, condenar e reclamar – e a maioria dos tolos assim o faz. Mas é preciso ter caráter e autocontrole para compreender e perdoar.

> Controle seu gênio. Lembre-se de que é possível medir a grandeza de uma pessoa avaliando aquilo que a deixa zangada. Ouça antes. Dê a seus oponentes uma oportunidade de falar. Deixem terminar o que têm a dizer. Não resista, não se defenda nem inicie uma discussão.

>>  [*Dale Carnegie - Como fazer amigos e influenciar pessoas*](https://www.amazon.com.br/Como-Fazer-Amigos-Influenciar-Pessoas/dp/8504018024)

Esta é provavelmente a primeira lição que se pratica no dia a dia. Nós, seres humanos, temos respostas quase que instintivas: reações “pré-programadas” ou premissas que não aprendemos a falar ou lidar. E com isso auto-conhecimento, na minha opinião, é essencial para lidar com as situações. Aqui alguns materiais:

* [Seis passos para melhorar a sua inteligência emocional - Ramona Hacker (TED Talk)](https://www.ted.com/talks/ramona_hacker_6_steps_to_improve_your_emotional_intelligence?language=pt-br)
* [Understanding Leadership (Harvard Business Review)](https://hbr.org/2004/01/understanding-leadership)
* [Radical Candor — The Surprising Secret to Being a Good Boss - Kim Scott (Video)](https://www.youtube.com/watch?v=MIh_992Nfes)

## RAIN

O framework RAIN, explorado no livro [10% mais feliz](https://www.amazon.com/10-Mais-Feliz-Portugues-Brasil/dp/8543102359), pode ajudar:

* Reconheça: Faça uma pausa e perceba o momento, tente entender o gatilho daquela situação. Exemplo do livro: “É como fazer uma pausa diante do que está acontecendo e simplesmente admitir que aquilo é real, que existe.”.
* Aceite: Você deve estar em um momento diferente, sinta ele e perceba as sensações que estar neste momento te gera. Muitas vezes depois da negação pode vir o insight de como resolver.
* Investigue: Esta é provavelmente a parte mais prática. A partir dos sentidos, entenda o que ele causa, suas reações e respostas no seu corpo. Por exemplo: Como está sua respiração? Você chega a ficar agitado? Tremer a perna?
* Não se identifique: Todo aquele mar de emoções não é você, não é o seu estado natural e sim como você está naquele momento. Neste ponto, da próxima vez que você reconhecer algo parecido, você pode engatilhar outra reação ou cultivar outros sentimentos. Aqui vale o caso citado acima: eu não sou uma pessoa constantemente irritada, porém nas situações de ser contrariado sem motivo eu passo para um estado de irritação. A partir do momento que eu entendo que “estou” e não “sou”, o meu objetivo é voltar a normalidade.

# Gerenciamento Lean de Software

O que o processo tem a ver com liderança? Gosto muito deste tópico:
> O seu método de trabalho não como algo dissociado da própria empresa, mas como resultado de um longo processo de envolvimento com os problemas e de adaptação à realidade que você vive.
> > [Zen e a Arte da Gestão de Software (ou da Manutenção de Motocicletas?](https://medium.com/software-zen/zen-e-a-arte-da-gest%C3%A3o-de-software-ou-da-manuten%C3%A7%C3%A3o-de-motocicletas-42f9be67f9e4)

O desenvolvimento de software é algo que evolui muito rapidamente no tempo. Garantir que o time esteja sendo o mais produtivo possível não é uma tarefa fácil no dia-a-dia onde o ambiente de incertezas e agilidade caminham juntos. Abaixo tentarei resumir alguns princípios capazes de nortear esta caminhada com base em algumas pesquisas (e muito influenciado pelo Accelerate)

## Complexidade: A raiz da maioria dos problemas em Software

Complexidade é o grande tema discutido em Engenharia de Software e sua redução é vital para a performance de um time.

No Artigo [No Silver Bullet - Essence and Accident in Software Engineering](http://worrydream.com/refs/Brooks-NoSilverBullet.pdf), Brooks traz a discussão que complexidade é algo inerente do software e isso gera diversos problemas:

> The complexity of software is an essential property, not an accidental one. [...] Many of the classic problems of developing software products derive from this essential complexity and its nonlinear increases with size. From the complexity comes the difficulty of communication among team members, which leads to product flaws, cost overruns, schedule delays. From the complexity comes the difficulty of enumerating, much less understanding, all the possible states of the program, and from that comes the unreliability. From complexity of function comes the difficulty of invoking function, which makes programs hard to use. From complexity of structure comes the difficulty of extending programs to new functions without creating side effects. From complexity of structure come the unvisualized states that constitute security trapdoors.

Em [Out of Tar Pit](http://curtclifton.net/papers/MoseleyMarks06a.pdf), Ben Moseley e Peter Marks concordam e categorizam complexidade como algo central dos problemas em Engenharia de Software:

> Complexity is the root cause of the vast majority of problems with software today. Unreliability, late delivery, lack of security — often even poor performance in large-scale systems can all be seen as deriving ultimately from unmanageable complexity.

Porém, para os autores desenvolve este conceito dividido sob duas óticas: 
* Complexidade Essencial: inerente ao problema (através da visão do usuário)
* Complexidade Acidental: todo o resto. É tudo relativo ao processo de desenvolvimento, testes, deploy, infra-estrutura escolha de linguagens, algoritmos ou toda abstração que construímos com o objetivo de processar o problema no computador.

> When it comes to accidental and essential complexity we firmly believe that the former exists and that the goal of software engineering must be both to eliminate as much of it as possible, and to assist with the latter.

E daí vem a diferença dos projetos de Software para os Projetos clássicos de engenharia. Estamos lidando a todo momento com complexidade e com a dúvida de que o que estamos construindo é algo essencial ao problema ou a interpretação de uma pessoa engenheira da realidade. O desafio da gestão de software, portanto, é entender estas variáveis e conseguir executar algo que entregue valor para o cliente.

Todos os princípios abaixo terão a premissa da redução da Complexidade Acidental ou de validarmos se estamos indo na essência dos problemas.

* Destaques de alguns autores:
  * [Frederick P. Brooks, Jr - No Silver Bullet: Essence and Accidents of Software Engineering](http://worrydream.com/refs/Brooks-NoSilverBullet.pdf)
    > The familiar software project, at least as seen by the nontechnical manager, has something of this character; it is usually innocent and straightforward, but is capable of becoming a monster of missed schedules, blown budgets, and flawed products. So we hear desperate cries for a silver bullet--something to make software costs drop as rapidly as computer hardware costs do.

    > The essence of a software entity is a construct of interlocking concepts: data sets, relationships among data items, algorithms, and invocations of functions. This essence is abstract in that such a conceptual construct is the same under many different representations. It is nonetheless highly precise and richly detailed.

    > Digital computers are themselves more complex than most things people build: They have very large numbers of states. This makes conceiving, describing, and testing them hard. Software systems have orders-of-magnitude more states than computers do


  * [Ben Moseley e Peter Marks - Out of Tar Pit](http://curtclifton.net/papers/MoseleyMarks06a.pdf)
    > Simplicity is Hard
     
    > The key problem with testing is that a test (of any kind) that uses one particular set of inputs tells you nothing at all about the behaviour of the system or component when it is given a different set of inputs.  The huge number of different possible inputs usually rules out the possibility of testing them all, hence the unavoidable concern with testing will always be — have you performed the right tests?

    >  The key problem is that a test (of any kind) on a system or component that is in one particular state tells you nothing at all about the behaviour of that system or component when it happens to be in another state.[... This problem] is a direct parallel to one of the fundamental problems with testing discussed above — namely that testing for one set of inputs tells you nothing at all about the behaviour with a different set of inputs. In fact the problem caused by state is typically worse — particularly
when testing large chunks of a system — simply because even though the number of possible inputs may be very large, the number of possible states the system can be in is often even larger.

    > Our recommendations for dealing with complexity (as exemplified by both state and control) can be summed up as: (1) Avoid and (2) Separate

  * [Charles Hoare - The Emperor's Old Clothes](cs.fsu.edu/~engelen/courses/COP4610/hoare.pdf)
    > I conclude that there are two ways of constructing a software design: One way is to make it so simple that there are obviously no deficiencies and the other way is to make it so complicated that there are no obvious deficiencies

  * [Dijkstra - The Humble Programmer](https://www.cs.utexas.edu/users/EWD/transcriptions/EWD03xx/EWD340.html)
    > Those who want really reliable software will discover that they must find means of avoiding the majority of bugs to start with, and as a result the programming process will become cheaper. If you want more effective programmers, you will discover that they should not waste their time debugging, they should not introduce the bugs to start with.
    
    > We all know that the only mental tool by means of which a very finite piece of reasoning can cover a myriad cases is called “abstraction”; as a result the effective exploitation of his powers of abstraction must be regarded as one of the most vital activities of a competent programmer.

## Princípio do baixo acoplamento

* Comunicação é uma das maiores dificuldades em times ágeis de software, sendo assim: pouca comunicação é algo que facilita a agilidade.
* Em empresas com mais de um time, a arquitetura do software deve ser desenhado para permitir do desenho ao deploy (passando por fases como desenvolvimento, testes, etc) sem dependências de outros times.
* Comunicação tem um aspecto não linear como é possível ilustrar na imagem abaixo:

![Manda de produtividade. 3 pessoas geram 3 linhas de comunicação, 6 pessoas geram 15.](https://i.dell.com/sites/imagecontent/consumer/merchandizing/pt/PublishingImages/Novas-imagens-OC/Learn%20Pages/Endeavour/graficos-artigo-dell-produtividade-mandalas.png)
> > [Dell & Endeavor: Eficiência para times de alto crescimento](https://endeavor.org.br/pessoas/eficiencia-para-times-de-alto-crescimento-como-combater-os-ladroes-de-tempo/)*

* Para isso funcionar, pela [Lei de Conway](https://en.wikipedia.org/wiki/Conway%27s_law), não só a empresa deve reduzir comunicação mas a arquitetura do sistema deve ser orientada a desacoplamento de domínios, contextos bem delimitados (bounded countexts) e testes capazes de prover isolamento de componentes. Do contrário, caímos na [Lei de brooks](https://en.wikipedia.org/wiki/Brooks%27s_law): "Adicionar pessoas a um projeto de software atrasado só o deixa mais atrasado".

* O que algumas empresas tem feito? Um caminho bem interssante que estou vendo no mercado é não existir mais aqueles times de "Operação", "Design", "Arquitetura", etc. No final, o time tem que ser autônomo, não é? Sendo assim, criar um time como todas estes papéis dentro do próprio time pode ser uma abordagem para incrementar a agilidade (["Specialized roles create efficiencies within each segment while potentially creating inefficiencies across the entire life cycle."](https://netflixtechblog.com/full-cycle-developers-at-netflix-a08c31f83249))


* Destaque de Livros e artigos:
  * [*Jez Humble; Nicole Forsgren; Gene Kim - Accelerate*](https://www.amazon.com.br/-/pt/dp/B07B9F83WM/)
    > In teams which scored highly on architectural capabilities, little communication is required between delivery teams to get their work done. 

    > The architecture of the system is designed to enable teams to test, deploy, and change their systems without dependencies on other teams.
    
    > high-performing group [...] can do most of our testing without requiring an integrated environment. We can and do deploy or release our application independently of other applications/ services it depends on.
    
    > Use of bounded contexts and APIs as a way to decouple large domains into smaller, more loosely coupled units, and the use of test doubles and virtualization as a way to test services or components in isolation.

    > ensure delivery teams are cross-functional, with all the skills necessary to design, develop, test, deploy, and operate the system on the same team.

* [*Eric S. Raymond - A Catedral e o Bazar*](https://pt.wikipedia.org/wiki/A_Catedral_e_o_Bazar)

    > Fred Brooks observou que o tempo de um programador não é acumulativo; adicionar desenvolvedores em um projeto atrasado de software faz com que ele se torne mais atrasado. Ele expôs que a complexidade e custos de comunicação de um projeto crescem com o quadrado do número de desenvolvedores, enquanto o trabalho feito cresce somente linearmente. Esta afirmação é desde então conhecida como "A Lei de Brooks"

* [*Gregor Hohpe - The Architect Elevator — Visiting the upper floors*](https://martinfowler.com/articles/architect-elevator.html)

    > A well-known architecture department anti-pattern is the “ivory tower”: architects sit in the penthouse to define how developers should design and build software, without developing any software themselves. Such a setup has one cardinal flaw: it doesn't provide feedback to the architects as to the effectiveness nor the cost of their decisions. Worse yet: some architects quite enjoy themselves not having to deal with those consequences.

## Princípio da alta iteração e pequenas entregas 
**(para mais interação com clientes)** 

* Provocação: o seu time já fez entrega em produção hoje?

* Objetivo: Trabalhar em batches pequenos permitindo Lead Time baixo e maior iteração em feedback loops. 

* Uma crítica clássica ao [modelo cascata](https://pt.wikipedia.org/wiki/Modelo_em_cascata) é justamente ele não permitir pequenos batches de entrega com o intuito de o cliente sentir progresso e conseguir ajudar no incremento do produto. 

* Quando a busca por inputs de clientes é feita em (1) estágios iniciais e (2) recorrente, mais fácil a validação (ou reprovação) de um usuário final e mais claro o sentimento de dever cumprido dentro do time (valendo aqui até sugestões durante o processo de desenho e desenvolvimento).

* "Frequentemente, as soluções mais impressionantes e inovadoras surgem ao se perceber que o seu conceito do problema estava errado" [*Eric S. Raymond - A Catedral e o Bazar*](https://pt.wikipedia.org/wiki/A_Catedral_e_o_Bazar). Portanto, para isso ter a interação com o usuário é vital para não priorizar o que poderia ser importante para o conceito inicial do problema, mas não é. 

* Apesar de trabalhar em pequenos batches adicionar algum overhead, permite "errar rápido" e evita entregas com nenhum valor ou valor negativo para organizações.

* O dia-a-dia do desenvolvimento é lidar com variáveis complexas e abstratas. Sendo assim, reduzir a chance do erro através de pequenas e constantes melhorias fazem com que a busca pela solução fique mais próxima da ideal.

* Agora: quão grande ou quão pequena deve ser a entrega? Na prática, alterar os valores de [WIP Limit e manter consistência no throughput](https://medium.com/rd-shipit/m%C3%A9tricas-em-times-%C3%A1geis-as-3-m%C3%A9tricas-fundamentais-que-voc%C3%AA-precisa-saber-e-dominar-816ffb6a53c5) para que eles sejam saudáveis para o time é uma fórmula que varia de time para a time mas uma boa prática a ser seguida.

* Pessoas técnicas também podem interagir com clientes, alterar especificações ou sugerir novas prioridades: Durante o processo de desenvolvimento de software, limitações técnicas podem surgir e ninguém melhor que o time técnico para encontrar soluções, sendo eles parte muito importante da entrega de valor para o cliente final.

* Destaque de Livros:
  * [*Jez Humble; Nicole Forsgren; Gene Kim - Accelerate*](https://www.amazon.com.br/-/pt/dp/B07B9F83WM/)
    > We found that external approvals were negatively correlated with lead time, deployment frequency, and restore time, and had no correlation with change fail rate.

    > [Product] actively and regularly seek customer feedback and incorporate this feedback into the design of their products. [...] Our key hypothesis in asking these questions was that teams implementing continuous delivery practices and taking an experimental approach to product development will build better products, and will also feel more connected to the rest of their organization. This, in turn, creates a virtuous cycle: by creating higher levels of software delivery performance, we increase the rate at which teams can validate their ideas, creating higher levels of job satisfaction and organizational performance.
    
    > Even though working in small chunks adds some overhead, it reaps enormous rewards by allowing us to avoid work that delivers zero or negative value for our organizations.
    
    > Development teams have the authority to create and change specifications as part of the development process without requiring approval.

  * [*Eric S. Raymond - A Catedral e o Bazar*](https://pt.wikipedia.org/wiki/A_Catedral_e_o_Bazar)
    > O estilo de Linus Torvalds de desenvolvimento -- libere cedo e freqüentemente, delegue tudo que você possa, esteja aberto ao ponto da promiscuidade -- veio como uma surpresa. Nenhuma catedral calma e respeitosa aqui -- ao invés, a comunidade Linux pareceu assemelhar-se a um grande e barulhento bazar de diferentes agendas e aproximações

    > Uma importante característica dos grandes [programadpres] é a preguiça construtiva. Eles sabem que você ganha um 'A' não por esforço, mas por resultados, e é quase sempre mais fácil partir de uma boa solução parcial do que do nada.
 
    > Planeje jogar algo fora; você irá, de qualquer maneira. [...] você freqüentemente não entende realmente o problema até depois da primeira vez que você implementa uma solução. Na segunda vez, talvez você saiba o suficiente para fazer corretamente. Então se você quer fazer algo certo, esteja preparado para começar tudo novamente pelo menos uma vez.

    > Com um pouco de estímulo, seus usuários irão diagnosticar problemas, sugerir correções e ajudar


## Princípio da automação
 
* Investimento em automação e cultura de DevOps _ao invés de_ processos burocráticos, aprovação e documentos.

* Testes devem rodar contra todo commit em um CI

* Todos os testes podem ser rodados na máquina local

* Alterações em produção devem ser feitas por processo totalmente autoamtizados (passando por todo o processo de qualidade como testes de forma automatizada)

* Além de qualidade, o deploy deve ser algo simples, não um evento que gera calafrios ou necessitam ser feitos em horários extras. Isso reduz inclusive o burnout do time!

* O objetivo é que qualquer processo ou burocracia repetitiva dentro de uma organização (como deploy, documentação, etc) possa ser visualizado como uma oportunidade de automação. Isso torna o trabalho mais sustentável e produtivo para as próprias pessoas

* Destaque de Livros:
  * [*Jez Humble; Nicole Forsgren; Gene Kim - Accelerate*](https://www.amazon.com.br/-/pt/dp/B07B9F83WM/)

    > Automated unit and acceptance tests should be run against every commit to version control to give developers fast feedback on their changes. [...] Developers should be able to run all automated tests on their workstations [...and] no one should be saying they are “done” with any work until all relevant automated tests have been written and are passing.
    
    > changes should only be applied to production using a fully automated process that forms part of a deployment pipeline. That is, no changes should be able to be made to production unless they have been committed to version control, validated by the standard build and test process, and then deployed through an automated process triggered through a deployment pipeline.

    > when teams practice CD, deployment to production is not an enormous, big-bang event— it’s something that can be done during normal business hours as a part of regular daily work. [...Also,] they help to decrease deployment pain and team burnout.

    > Investments in technology are also investments in people, and these investments will make our technology process more sustainable

  * [*Eric S. Raymond - A Catedral e o Bazar*](https://pt.wikipedia.org/wiki/A_Catedral_e_o_Bazar)
    > Os programadores bons sabem o que escrever. O grandes sabem o que re-escrever (e reusar).

## Princípio da visibilidade 

* Provocação: Seu serviço está de pé? Quantos requests ele está recebendo? Qual throughput do seu time no último mês? Estas são perguntas muito comuns que managers recebem. 

* Qualquer pessoa do time deveria ser capaz de entender e responder o estado e qualidade do serviço do seu time.

* Este princípio ajuda o próprio time a se regular e verificar os resultados das suas alterações. 

* Destaque de Livros:
  * [*Jez Humble; Nicole Forsgren; Gene Kim - Accelerate*](https://www.amazon.com.br/-/pt/dp/B07B9F83WM/)

    > Managers should make performance metrics visible and take pains to align these with organizational goals, and should delegate more authority to their employees.

## Princípio da diversidade

> Kintsugi ("emenda de ouro") é uma antiga arte japonesa que consiste em reparar cerâmica quebrada com pó de ouro ou algum material com brilho, tornando-a uma peça única pois suas rachadoras beiram o impossível de se reproduzir. Como resultado, a peça restaurada se torna muito mais valiosa.
>> [Kintsugi (Wikipedia)](https://en.wikipedia.org/wiki/Kintsugi)

* Como metáfora (e até filosofia!), cada pessoa traz consigo uma história e diversas "rachaduras de ouro" que as fazem únicas e acrescentam uma visão diferente dentro do time. 

* Alguns conceitos:
  * Grupos Minoritários: Grupos que possuem pouca experessão em termos numéricos. Em consequência, possuem com pouca representativdade em espaços de poder, privilégios e mercado de trabalho em cargos seniores/decisores. Ex: LGBTQIA+
  * Grupos Minorizados: Grupos numericamente expressivos mas com pouca ou nenhuma representativdade nos espaços de poder, privilégio e mercado de trabalho em cargos seniores/decisores. Ex: Pessoas Negras
  * Grupos Subrepresentados: Grupos que em algum espaço não reflete a realidade estatística da sociedade. Ex: Pessoas com deficiência em cargos de mídia
  * Grupos Subutilizados: Grupos que tenham formação necessária para ocupar certos cargos (ex: decisores ou especialistas) em empresas ou orgãos mas não estão representadas em cargos compatíveis com sua função. 

* ["A diversidade não se limita às pessoas, mas ao que existe dentro delas, incluindo a diversidade das emoções."](https://www.ted.com/talks/susan_david_the_gift_and_power_of_emotional_courage/transcript?language=pt-br#t-865476). Sendo assim, o cuidado a [interseccionalidade](https://www.ted.com/talks/kimberle_crenshaw_the_urgency_of_intersectionality) durante o processo de liderança é importante. A percepção de que cada pessoa é múltipla e que suas características (raça, gênero, sexualidade, condição social) cria experiências diferentes na sociedade. Ações que promovam Diversidade e Inclusão devem levar não um sub-grupo de razões mas a interseccionalidade delas como estrutura que a sociedade gerou opressão.

* Não basta somente ter diversidade no time mas, como líder, prover mecanismos onde estas pessoas possam (1) Expressar, (2) Interagir, (3) Aprender e (4) Pertencer dentro do time e da organização (["Creating connections among followers is one of the most important tasks for leaders"](https://management30.com/energize-people/individuals-interactions/))

* Empresas e times são subconjuntos de uma sociedade. A realidade brasileira é diversa e desigual. O líder portanto deve provocar ativamente um ambiente de trabalho que represente a diversidade da sociedade (diferenças físicas,culturais, tradições, religião, costumes, a política, etc) com o intuito de promover a [equidade](https://duvidas.dicio.com.br/equidade-ou-igualdade/) e justiça social (práticas através de ações afirmativas que combatem a desigualdade).

* Destaque de Livros:
  * [*Jez Humble; Nicole Forsgren; Gene Kim - Accelerate*](https://www.amazon.com.br/-/pt/dp/B07B9F83WM/)

    > Diversity matters. Research shows that teams with more diversity with regard to gender or underrepresented minorities are smarter (Rock and Grant 2016), achieve better team performance (Deloitte 2013), and achieve better business outcomes [...] It is also important to note that diversity is not enough. Teams and organizations must also be inclusive.

  * [*Eric S. Raymond - A Catedral e o Bazar*](https://pt.wikipedia.org/wiki/A_Catedral_e_o_Bazar)

    > "Dados olhos suficientes, todos os erros são triviais." Eu chamo isso de: "Lei de Linus".


# Outros pontos

* Segurança

> We found that the biggest predictor of an organization’s application-development security practices was cultural, not technical: high-trust, low-blame cultures focused on performance were 1.6x more likely to have above average adoption of emerging security practices than low trust, high-blame cultures focused on power or rules. We also found early evidence suggesting that pre-deployment security scanning is effective at finding vulnerable dependencies, resulting in fewer vulnerabilities in production code.
>> 2022 Accelerate
