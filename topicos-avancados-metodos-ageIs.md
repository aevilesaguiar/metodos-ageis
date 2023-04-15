# Tópicos avançados , outros métodos ageis

## eXtreme Programming
![image](https://user-images.githubusercontent.com/52088444/232250188-8e673614-42db-4386-93db-d9b23b60c44a.png)


A XP ou XP é uma metodologia ágil de desenvolvimento de software, focada na agilidade de equipes e na qualidade dos projetos, e tem como valores a simplicidade, o feedback, a comunicação, a coragem e o respeito. 
A Extreme Programming foi criada por Kent Beck quando trabalhava na Chrysler, no projeto da folha de pagamento, quando Beck tornou se líder do projeto em março de 1996. Ele começou a refinar o método de  desenvolvimento usado e logo em seguida escreveu um livro, e em outubro de 1999, a Extreme Programming foi publicada. Os valores é que XP é uma metodologia ágil para equipes pequenas e médias que desenvolvem software baseado em requisitos vagos e que se modificam rapidamente. Entre as principais diferenças da XP em relação às metodologias clássicas estão o feedback constante, a abordagem incremental e o encorajamento da comunicação entre as pessoas. A maioria das regras da XP causa surpresa no primeiro contato, e muitas não fazem sentido se aplicadas isoladamente.  E a força de seu conjunto que sustenta o seu sucesso, trazendo uma verdadeira revolução no desenvolvimento de software.  O principal objetivo da XP é dar agilidade ao desenvolvimento do projeto e busca garantir a satisfação do cliente.

E seus cinco valores são:
![image](https://user-images.githubusercontent.com/52088444/232250225-24a5556b-7da0-4362-8f4a-242d31912eb5.png)


- Comunicação busca manter o melhor relacionamento possível entre clientes e desenvolvedores, preferindo conversas pessoais a outros meios de comunicação.
- Simplicidade Entende-se como simplicidade a busca do objetivo de implementar o software com o menor número possível de classes e métodos. Outra ideia importante deste princípio é procurar implementar apenas requisitos atuais, evitando assim adicionar funcionalidades que podem ser importantes apenas no futuro. A aposta da XP  é que é melhor fazer algo simples hoje do que implementar algo complicado que talvez não venha a ser usado.
- Feedback A prática do feedback constante significa que o desenvolvedor terá informações constantes do código e do cliente. A informação do código é dada pelos testes constantes que indicam os erros tanto individuais quanto do software integrado.
- Coragem. Este princípio também dá suporte a simplicidade, pois assim que a oportunidade de simplificar o software é percebida, a equipe pode experimentar e buscar novas soluções. Além disso, é preciso coragem para obter e cobrar constantemente um feedback do cliente.
- Respeito:respeita o valor que dá sustentação a todos os demais membros de uma equipe só irão se preocupar em comunicar-se melhor, por exemplo, se se importarem uns com os outros. Respeito é o mais básico de todos os valores. Se ele não existir em um projeto, não há nada que possa salvá-lo. Saber ouvir, saber compreender e respeitar o ponto de vista do outro é essencial para que um projeto de software seja bem sucedido.


As práticas Segundo Kent Beck, as práticas primordiais para a aplicação da XP são as seguintes:
![image](https://user-images.githubusercontent.com/52088444/232250314-51e6f1f7-debd-403d-91dc-ab7bea0aaa3b.png)

- Jogos de planejamento ou planning games. O desenvolvimento é feito em iterações semanais. No início da semana, desenvolvedores e o cliente reúnem se para priorizar as funcionalidades. Essa reunião recebe o nome de Jogo do Planejamento. Nela, o cliente identifica prioridades e os desenvolvedores as estimam. O cliente é essencial neste processo e assim ele fica sabendo o que está acontecendo e o que vai acontecer no projeto. Como o escopo é reavaliado semanalmente, o projeto é regido por um contrato de escopo negociável, que difere significativamente das formas tradicionais de contratação de projetos de software. Ao final de cada semana, o cliente recebe novas funcionalidades, completamente testadas e prontas para serem postas em produção. 
- Pequenas versões Soul Small Releases. A liberação de pequenas versões funcionais do projeto auxilia muito no processo de aceitação por parte do cliente, que já pode testar uma parte do sistema que está comprando. As versões chegam a ser ainda menores que as produzidas por outras metodologias incrementais.
- Metáforas o conceito de rápido para um cliente de um sistema jurídico é diferente do que para um programador experiente em controlar comunicação e sistemas em tempo real, como controle de tráfego aéreo, é preciso traduzir as palavras do cliente para o significado que ele espera dentro do projeto.
- Projetos simples ou simple design. Simplicidade é um princípio da XP. Projeto simples significa dizer que, caso o cliente tenha pedido que na primeira versão. Apenas o usuário teste possa entrar no sistema com a senha um, dois, três e assim ter acesso a todo o sistema. Você vai fazer o código exato para que esta funcionalidade seja implementada sem se preocupar com sistemas de autenticação e restrições de acesso. Um erro comum ao adotar essa prática é a confusão por parte dos programadores de códigos simples e o código fácil. Nem sempre o código mais fácil de ser desenvolvido levará a solução mais simples por parte de projeto. Esse entendimento é fundamental para o bom andamento da XP código fácil deve ser identificado e substituído por código simples, 
- time coeso: A equipe de desenvolvimento é formada pelo cliente e pela equipe de desenvolvimento.
- Testes de aceitação ou customer tests são testes construídos pelo cliente e em conjunto com analistas e testadores. Para aceitar um determinado requisito do sistema.
- Ritmo sustentável ou sustainable space: Trabalhar com qualidade, buscando ter ritmo de trabalho saudável, ou seja, 40 horas por semana ou 08h00 por dia, sem horas extras. Horas extras são permitidas quando trouxerem produtividade para a execução do projeto. Outra prática que se verifica neste processo é a prática do trabalho energizado, onde se busca trabalho motivado sempre. Para isto, o ambiente de trabalho e a motivação da equipe devem estar sempre em harmonia.
- Posses coletivas ou collective ownership: O código fonte não tem dono e ninguém precisa solicitar permissão para poder modificar o mesmo. O objetivo com isto é fazer a equipe conhecer todas as partes do sistema 
- programação em ParEs ou Per programming é a programação em par o em duplas em um único computador. Geralmente, a dupla é formada por um iniciante na linguagem e outra pessoa funcionando como um instrutor. omo é apenas um computador, o novato é que fica à frente fazendo a codificação e o instrutor acompanha, ajudando a desenvolver suas habilidades. Desta forma, o programa sempre é revisto por duas pessoas. Com isto, busca se sempre a evolução da equipe, melhorando a qualidade do código, fonte gerado,

- codificação padrão ou coding standard : A equipe de desenvolvimento precisa estabelecer regras para programar e todos devem seguir essas regras. Desta forma, parecerá que todo o código fonte foi editado pela mesma pessoa, mesmo quando a equipe possui dez ou até mesmo 100 membros.

- Desenvolvimento orientado a testes ou Test Driver Development: primeiro cria os testes unitários e depois cria o código para que os testes funcionem. Esta abordagem é complexa no início, pois vai contra o processo de desenvolvimento de software que adotamos há muitos anos. Só que os testes unitários são essenciais para que a qualidade do projeto seja mantida.
- Refatoração ou factoring:  é um processo que permite a melhoria contínua da programação, com o mínimo de introdução de erros e mantendo a compatibilidade com o código já existente.Refabricar melhor a clareza e a leitura do código, dividindo o em módulos mais coesos e de maior reaproveitamento, evitando a duplicação de código fonte.
- Integração contínua sempre que produzir uma nova funcionalidade, nunca espere uma semana para integrar a versão atual do sistema. Isto só aumenta a possibilidade de conflitos e a possibilidade de erros no código fonte. Integrar de forma contínua permite saber o status real da programação.

Muitos dos componentes da XP também são encontrados no Scrum, já que ambos surgiram a partir do manifesto ágil. Mas veja que o scrum é uma forma de gestão ampla para projetos que não depende da área de conhecimento,Ou seja, não há necessidade do projeto ser de desenvolvimento de software.

Já o XP tem sua aplicação mais restrita, focada no mundo, justamente no desenvolvimento de sistemas de software.

## Crystal

Crystal ou cristal é uma família de metodologias de desenvolvimento de software, e como os cristais, possui diferentes cores e rigidez, referindo se ao tamanho e ao nível crítico do projeto.

A Cristall foi criada por Alistair Cockburn e Jim Highsmith, e tais métodos são focados nos talentos e nas habilidades das pessoas, permitindo que o processo de desenvolvimento seja moldado conforme as características específicas da equipe, mesclando a sua cultura de trabalho com a proposta de desenvolvimento ágil.

A metodologia cristal utiliza dois parâmetros para adequar ao projeto de software: 
- a primeira métrica o número de pessoas envolvidas 
- segunda o nível crítico.

Cada método Cristal é caracterizado por uma cor de acordo com o número de envolvidos.
![image](https://user-images.githubusercontent.com/52088444/232252055-0e90ec7c-3ee9-42f4-8582-f21b8622edea.png)

Crystal Clear é uma metodologia leve para equipes:
- de 1 a 8 pessoas, podendo chegar até 12 em casos especiais e 
- YELLOW para equipes por volta de 10 a 20 membros.
- Orange e a variante Orange Web são apropriados para equipes de 20 a 50 participantes 
- Red para equipes de 50 a 100 membros.

Existem mais cores, mas as mais usuais são essas. 

![image](https://user-images.githubusercontent.com/52088444/232252155-50921ca6-87ad-4063-bfdf-b726c4551fae.png)

Como vemos no gráfico, se o seu projeto tiver uma equipe de seis pessoas. O método Crystal que devemos usar é o Crystal Clear.

Além das cores, o cristal utiliza- se de algumas letras para representar a criticidade, ou seja, potenciais perdas causados por uma falha no sistema de desenvolvimento de software :

- C de comfort ou conforto. Casos em que a falha do sistema ocasiona a perda de credibilidade do usuário, devido a ele não atender este conforto ou facilidade.

Como exemplo, temos o serviço de um aparelho celular. Caso este falhe, o usuário deverá utilizar se de um outro ou até mesmo utilizar se de outros meios para realizar a comunicação desejada.

- D de Discretionary money ou dinheiro disponível para uso conforme necessário, cujo uso depende de decisão de alguém com poder para isso.
São os casos em que a falha do sistema ocasiona na perda de dinheiro, mas de valor inexpressivo, tendo como exemplo o sistema de um caixa de um supermercado.
Tal falha pode impactar em não cobrar determinados produtos ou cobrar produtos com valor superior, que logo seria descoberto por clientes, gerando a perda de valores, mas que não levará o mercado à falência 
- E de essencial Money  ou dinheiro indispensável, absolutamente necessário. São os casos em que a falha do sistema ocasiona a perda de uma quantia indispensável em grandes valores. Como exemplo, temos o sistema de reserva de uma companhia aérea. Esta não funcionando, ocasionará a perda de valores significativos devido aos gastos que a mesma acarretaria e assim na qual pode culminar até mesmo na falência da empresa.
- L de Life ou Vida, são os casos em que a falha do sistema ocasiona a perda de vidas, tendo como referência um software de piloto automático onde a sua falha poderia derrubar um avião e matar os tripulantes e todos os passageiros.

Assim, de acordo com o tamanho do projeto, tamanho da equipe e a sua criticidade, devemos escolher o método que melhor se adeque a ele.

Características da Metodologia Crystal:

![image](https://user-images.githubusercontent.com/52088444/232252506-d41fcd46-2064-4e40-8abe-98ab7ac84301.png)


Independentemente de qual implementação CRYSTAL você escolhe.

Você encontrará sete princípios chave em cada um: 

- Entrega frequente: Os proprietários de projetos cliente podem esperar resultados da equipe a cada dois meses, quando são considerados mais projetos. As entregas podem não entrar em produção diretamente, pois dependem de integrações, mas os interessados irão ver as versões intermediárias e assim serem capazes de fornecer feedback.
- Feedback contínuo: Toda equipe de projeto se reúne regularmente para discutir as atividades do projeto. A equipe também se reúne regularmente com as partes interessadas para garantir que o projeto está caminhando na direção esperada e comunicar quaisquer novas descobertas que possam afetar o projeto.
- Comunicação constante Espera se que para projetos menores, a equipe esteja toda localizada na mesma sala. Já para projetos maiores, é esperado que possam estar localizados no mesmo edifício ou andar. Todos os projetos esperam ter acesso frequente às pessoas que definam os requisitos.
- Segurança: Cristal é algo único em seu foco no aspecto da segurança de desenvolvimento de software. Isto vem em dois aspectos, sendo que um deles é a zona segura para que os membros da equipe sejam eficazes na comunicação da verdade durante o projeto, sem medo de represálias. O outro aspecto relativo à segurança que só o cristall reconhece, é que a finalidade de cada projeto de software varia e que alguns projetos afetam a segurança de seus usuários finais, enquanto outros não.
Por exemplo, um sistema de ônibus espacial é muito mais crítico do que o software de uma batedeira de bolo.
- foco:  Os membros da equipe devem trabalhar em no máximo dois ou três itens prioritários cada um, e também devem trabalhar sem interrupções.
- Acesso aos usuários finais Como a maioria dos métodos ágeis, Cristal espera que a equipe do projeto tenha acesso a um ou mais usuários do sistema a ser construído.
- Testes automatizados e de integração O Crystal tem várias formas para verificação da funcionalidade desenvolvida. Controles devem ser postos em prática para apoiar a versão, tais como testes automatizados e frequente integração dos componentes desenvolvidos.



## MSDM (Método de Desenvolvimento de Sistemas Dinâmicos)

A Dynamic Sistemas Development Method de MSDM em inglês foca na criação de protótipos que evoluem para o sistema, utilizando para isso a colaboração muito próxima do cliente.

As ideias principais desse framework podem ser observadas no conjunto dos seguintes princípios norteadores:

- O envolvimento ativo do usuário é imperativo.
- O time deve ter o poder para tomar decisões.
- O foco é a entrega frequente de produtos.
- O encaixe ao propósito do negócio é o critério essencial para aceitação das entregas.
- O desenvolvimento iterativo e incremental é necessário para convergir com precisão as soluções do negócio.
- Todas as mudanças durante o desenvolvimento são reversíveis.
- Requisitos são alinhados em um alto nível.
- O teste é integrado por todo o ciclo de vida.
- Uma abordagem colaborativa e cooperativa entre as partes envolvidas é essencial.

É possível notar com esses princípios, que o cliente e o negócio são os pontos essenciais do método, enquanto que os aspectos técnicos, como a programação, são pouco abordados, o que fica ainda mais evidente na descrição do processo.
![image](https://user-images.githubusercontent.com/52088444/232252632-7fef957d-7ec3-4076-92c8-becab3a39746.png)

Além disso, é possível combinar o MSDM a outros métodos, tal como e XP, e mesmo assim ainda manter os seus princípios. Além desses princípios, existem algumas técnicas que são usadas durante a execução de um projeto:

- Time boxes, definição de um período fixo para execução do projeto, colocando até datas de entrega.
- Moscow técnica para priorização de requisitos durante o período de desenvolvimento. A ideia fundamental é priorizar e implementar os requisitos que sejam considerados principais, deixando os menos importantes para depois.
- Modelagem não deve ser uma atividade burocrática, sendo usada para prover um melhor entendimento do problema e da solução.
- Prototipação forma de verificar a adequação dos requisitos e facilitar as discussões com o cliente.O protótipo criado deve evoluir juntamente com o projeto
- Teste essa atividade deve ser executada sistematicamente e de forma contínua durante o projeto 
- Gerência de Configuração Essencial, visto que os produtos são entregues com uma grande frequência.

## TDD(Test Driven Development)

Test Drive and Development ou, em português, desenvolvimento guiado por testes é definido como umatécnica de desenvolvimento de software ligado ao conceito de verificação e validação em curtos períodos de tempo.


No TDD você desenvolve os testes do software antes mesmo de desenvolver o software para cada peça da aplicação que deverá ser construída.
Os testes são escritos antes com base nas entradas e saídas dos métodos ou funcionalidades do sistema. A prática é simples escreva um teste que falha, faça o passar da maneira mais simples possível e, por fim, refatore código.

Esse ciclo é conhecido como ciclo vermelho verde Refatore.
![image](https://user-images.githubusercontent.com/52088444/232252769-4739896e-0359-4957-b2ad-dcfdecafc301.png)

**Pricncipios

Os princípios fundamentais que devemos levar em conta ao adotar o TDD são:
- escrever o teste da implementação antes de escrever o código a ser implementado inteiro; 
- escrever apenas o código suficiente para o teste e se contentar com isso. 
- Escrever testes pequenos, testando a menor quantidade possível de código de cada vez. 
- Escrever testes rápidos não é programar rápido, e sim testes que executem rápido.

O ciclo de vida do TDD.

![image](https://user-images.githubusercontent.com/52088444/232252861-3db5fb7b-473a-48d7-8d26-7f45a1c37251.png)


- Crie o teste
- execute todos os possíveis testes 
- verifique se ocorre alguma falha na aplicação.
- Escreva a aplicação a ser testada 
- execute os testes para ver se todos passarão relatórios
- execute os testes novamente e garanta que eles continuem passando.
- Refatore 
- teste-os novamente e garanta que eles continuem passando

Vantagens do uso do TDD:
![image](https://user-images.githubusercontent.com/52088444/232252943-4fbecb74-daf4-41ef-bc76-e79983eab2b9.png)


- Feedback rápido sobre a nova funcionalidade e sobre as outras funcionalidades existentes no sistema.
- Código mais limpo já que escrevemos códigos simples para o teste passar.
- Segurança na refatoração, pois podemos ver o que estamos ou não afetando no sistema.
- Segurança na correção de bugs.
- Maior produtividade, já que o desenvolvedor encontra menos bugs e não desperdiça tempo em depuração.
- Código da aplicação mais flexível, já que para escrever testes temos que separar em pequenos pedaços do nosso código para que sejam testáveis, ou seja, nosso código estará menos acoplado.


## FDD (Feature Driven Development)

O Featured Driven Development é um processo de software centrado no cliente, centrado na arquitetura e pragmático.
Para o FDD, os recursos são um aspecto muito importante.Um recurso é uma pequena função de valor para o cliente e é expressa na forma, ação, resultado e objeto.
![image](https://user-images.githubusercontent.com/52088444/232253029-b3a29260-7474-4e83-9a54-c39181ddd90c.png)

Por exemplo, calcular o total de uma venda, validar a senha de um usuário e autorizar a transação de venda de um cliente.

Os recursos são para o FDD. O que as histórias de usuários são para o Scrum. Eles são a principal fonte de requisitos e a principal entrada em seus esforços de planejamento.

Há seis funções principais em um projeto de FDD :
![image](https://user-images.githubusercontent.com/52088444/232253056-023e351a-e0a5-4590-ba50-df9732da83f9.png)


- o gerente do projeto;
- o arquiteto chefe;
- o gerente de desenvolvimento;
- o programador chefe
- o proprietário de classe 
o especialista em Dominion.

O indivíduo assumirá uma ou mais funções em um projeto como você esperaria. O conceito de proprietário de uma classe é onde o FDD difere do XP. No XP, por exemplo, possui uma prática chamada propriedade coletiva, cuja ideia é que qualquer desenvolvedor possa atualizar qualquer artefato, incluindo o código fonte, conforme necessário. Já o FDD adota uma abordagem diferente ao designar classes a desenvolvedores individuais. Portanto, se o recurso exigir alterações em várias classes, os proprietários dessas classes deverão trabalhar juntos como uma equipe de recursos para implementá lo.

O FDD também define uma coleção de funções de suporte incluindo:
- o gerente de domínio
- o gerente de releases
- o guru da linguagem
- engenheiro de builds
- especialista em ferramentas
- administrador do sistema
- testador de player 
- escritor técnico.

Em relação às práticas definidas no FDD, elas não são extremamente rígidas, pregando adaptação ao ambiente de desenvolvimento. No entanto, existe um conjunto de práticas que são fundamentais e que são:

- modelagem em objetos de domínio.Construir um diagrama de classes básico com os objetos de domínio e suas relações, definindo assim uma arquitetura básica para o modelo do sistema.
- Desenvolvimento por características, a implementação deve ser orientada pelas características.
- Autoria individual. O código é de autoria de um dono da classe, o que permite uma maior rapidez na implementação das tarefas associadas.
- Times da característica. Para a implementação de uma determinada característica, o chefe programador recruta os donos das classes que serão usadas. Esse grupo de pessoas é o time da característica.
- Inspeções. A forma de verificação de qualidade do código e do projeto 
- integração ou build regular em um determinado período de tempo fixo devem ser integradas às características já terminadas, permitindo a verificação de erros e também criando uma versão atual que pode ser demonstrada ao cliente.
- Gerência de configuração. Manter versões de todos os artefatos criados.
- Reportar visibilidade dos resultados permite que se conheça o progresso do projeto 

**Processo

![image](https://user-images.githubusercontent.com/52088444/232253273-f6953863-98e1-4e7a-aae4-364957df7416.png)


o FDD é classicamente descrita por cinco processos:

- Desenvolver um modelo abrangente pode envolver o desenvolvimento de requisitos, análise orientada por objetos, modelagem, lógica de dados e outras técnicas para entendimento do domínio de negócio em questão. O resultado é um modelo de objetos e ou de dados de alto nível que guiará a equipe durante os ciclos de construção.

- Construir uma lista de funcionalidades e a decomposição funcional do modelo do domínio em três camadas típicas:
    - área de negócio, 
    - atividades de negócio 
    - e passos automatizados das atividades ou funcionalidades.

O resultado é uma hierarquia de funcionalidades que representa o produto a ser construído. Também chamado de backlog do produto. Planejar por funcionalidade abrange a estimativa de complexidade e dependência das funcionalidades, também levando em consideração a prioridade de valor para o negócio ou cliente.

O resultado é um plano de desenvolvimento com os pacotes de trabalho na sequência apropriada para sua construção.

Detalhar por funcionalidade, Já dentro de uma iteração de construção, a equipe detalha os requisitos e outros artefatos para codificação de cada funcionalidade, incluindo os testes.

O projeto para as funcionalidades é inspecionado. O resultado é o modelo de domínio mais detalhado e os esqueletos de código prontos para serem preenchidos.

Construir por funcionalidade. Cada esqueleto de código é preenchido, testado e inspecionado. O resultado é um incremento do produto integrado ao repositório principal de código, com qualidade e potencial para ser usado pelo cliente ou usuário.

##  Kanban

Kanban é um método baseado no Pensamento Lean e no Pensamento Ágil, voltado a melhorar a execução dos serviços, entregar valor de maneira contínua e evoluir continuamente o sistema de produção, através da resolução sistemática de problemas.

Kanban procura identificar oportunidades de melhoria, criando uma cultura de melhoria contínua na equipe.Kanban é uma ferramenta criada inicialmente para ser utilizada no controle de produção da Toyota e que hoje pode ser utilizada em diversas áreas, como por exemplo: desenvolvimento de software, gestão de TI, novos negócios, design, finanças, marketing, operações, entre outras.

O uso adequado dessa ferramenta pode trazer agilidade e organização. Agilidade em responder às mudanças que surgem ao longo da execução de tarefas e projetos e organização, formando um time que trabalha de forma mais eficiente, sem gerar muito ruído nas comunicações.

O Kanban organiza um determinado processo com base em um quadro visual. Esse quadro é dividido entre os estágios do processo e cada estágio possuirá cartões afixados com tarefas a serem realizadas nesse passo do processo. Esses cartões passam de um estágio do processo para outro, à medida que as tarefas indicadas nesses cartões vão sendo finalizadas. Dessa forma, um sistema Kanban é composto por um fluxo de valor onde unidades de trabalho trafegam da esquerda para a direita. Cada etapa do processo adiciona mais valor ao item que está sendo trabalhado, sendo que quando ele chega ao final do processo, ele está concluído ou Done. Esse fluxo de valor pode ser o desenvolvimento de um software, a prestação de um serviço como atendimento ao cliente ou até mesmo a criação de um produto físico.

Vamos supor que fazemos parte de um time de desenvolvimento de um aplicativo. O nosso processo atual tem algumas etapas que vamos mapear na forma de colunas e que são backlog, design e desenvolvimento, testes deploy e pronto.
![image](https://user-images.githubusercontent.com/52088444/232253578-dd21ff60-d832-4cff-8054-4eae6233a6c7.png)

Neste quadro, as unidades de trabalho representam itens que geram algum benefício ao cliente ou usuário final. São novas funcionalidades, correção de defeitos ou melhorias na interface do produto. O valor é gerado somente quando um item alcança a última etapa. Apesar de conter etapas sequenciais e cartões, isso é quase, mas ainda não é um sistema Kanban. Vamos fazer mais duas mudanças para tornar o fluxo puxado. Dividir as colunas intermediárias em dois estágios "fazendo e pronto" e adicionar limite de trabalho em progresso(WIP), Ou seja, cada coluna vai ter um limite de tarefas a serem trabalhadas ao mesmo tempo.

Feitas essas mudanças, o nosso quadro ficaria assim:

![image](https://user-images.githubusercontent.com/52088444/232253641-e57fdd60-4822-495c-acfa-2cc237d57083.png)


Vamos analisar como isso funciona na prática. Vamos supor que você é o especialista em design e que você está trabalhando em uma funcionalidade. Após concluir a sua atividade, você movimenta o cartão para a etapa pronto da coluna Design. Se um desenvolvedor que atua na etapa de desenvolvimento está livre, ele pode perceber que você sinalizou a conclusão da sua parte e então puxar o cartão para etapa, fazendo da coluna Desenvolvimento. Repare que o Limite um da coluna Design é válido tanto para fazendo quanto pronto. No caso, temos um item que foi concluído pelo designer, mas ainda não foi puxado. O que o designer faz nesse caso? Nada.
Ele apenas aguarda alguém puxar o item para o desenvolvimento. Nesse caso, o slot seria então liberado e ele poderia trabalhar em outro item. 
Claro que, se na prática não houver um slot disponível, o membro do time não vai ficar simplesmente parado em um sistema Kanban estimulamos as pessoas a olharem para o fluxo como um todo e buscarem formas de aumentar a vazão. Pode ser que o designer possa ajudar alguém no desenvolvimento. Pode ser que ele usa esse tempo para pensar em melhorias e etc. 
Veja que a divisão de fazendo e pronto em cada um dos passos é importante quando várias funções que não são compartilhadas atuam no mesmo fluxo. 

Por exemplo, a pessoa responsável pelo design não será a mesma que irá efetuar o desenvolvimento. Se não tivéssemos essas colunas, como é que o desenvolvedor saberia que o designer encerrou sua tarefa? Assim como os itens são puxados apenas quando a capacidade disponível, raramente existe sobrecarga. Isso é o que chamamos de sistema puxado. Esse é um contraste, a forma tradicional de trabalhar, que chamamos de sistema empurrado. Vamos entender a diferença entre os dois para compreender melhor um sistema Kanban.

Sistema empurrado, um sistema empurrado e aquele em que a produção é baseada na demanda sem respeito à capacidade do sistema. Em geral, no paradigma empurrado, tenta se produzir o máximo possível e em grandes lotes, sem considerar a real necessidade dos clientes. Neste tipo de abordagem, a estratégia de marketing e vendas também é focada em vender e empurrar os produtos para o cliente. No nosso exemplo, não teríamos as colunas Fazenda e Pronto e tampouco o limite de tarefas. E assim que o designer terminasse sua tarefa, ele mesmo moveria o seu cartão para a coluna Desenvolvimento. E qual é o mal disso? É que, em um determinado momento, a coluna Desenvolvimento vai ficar tão cheia de coisas para fazer que o fluxo vai travar. Aí é o que o designer vai fazer, vai continuar fazendo seu trabalho e gerando mais trabalho para o desenvolvedor.É como se empurrasse a batata quente para o próximo e ele que se vire com ela. Os principais efeitos colaterais de um sistema empurrado são a sobrecarga, demora nas entregas em grandes lotes e burnout das pessoas.

Sistema puxado por um sistema puxado e aquele em que os participantes puxam o trabalho quando a capacidade disponível para executá lo. Isso é possível quando atribuímos limites para as unidades de trabalho em progresso.  Um sistema puxado nunca irá sofrer com sobrecarga se os limites forem estabelecidos corretamente.
Nesse paradigma, busca se atingir um passo sustentável, ou seja, um equilíbrio entre a capacidade do time e o que é demandado dele.


