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

![image](https://user-images.githubusercontent.com/52088444/232252077-36616bf9-78fa-415c-aabb-23a94320a87c.png)

Como vemos no gráfico, se o seu projeto tiver uma equipe de seis pessoas. O método Crystal que devemos usar é o Crystal Clear.
![image](https://user-images.githubusercontent.com/52088444/232252101-7ef570f1-95f6-4b7b-a0f2-91f189cd85b7.png)

Além das cores, o cristal utiliza- se de algumas letras para representar a criticidade, ou seja, potenciais perdas causados por uma falha no sistema de desenvolvimento de software C de comfort ou conforto. Casos em que a falha do sistema ocasiona a perda de credibilidade do usuário, devido a ele não atender este conforto ou facilidade.

Como exemplo, temos o serviço de um aparelho celular.

Caso este falhe, o usuário deverá utilizar se de um outro ou até mesmo utilizar se de outros meios

para realizar a comunicação desejada.

Desde descrição, ferry, money ou dinheiro disponível para uso conforme necessário, cujo uso depende

de decisão de alguém com poder para isso.

São os casos em que a falha do sistema ocasiona na perda de dinheiro, mas de valor inexpressivo, tendo

como exemplo o sistema de um caixa de um supermercado.

Tal falha pode impactar em não cobrar determinados produtos ou cobrar produtos com valor superior,

que logo seria descoberto por clientes, gerando a perda de valores, mas que não levará o mercado à

falência e de essencial, nem dinheiro essencial ou dinheiro indispensável, absolutamente necessário.

São os casos em que a falha do sistema ocasiona a perda de uma quantia indispensável em grandes valores.

Como exemplo, temos o sistema de reserva de uma companhia aérea.

Esta não funcionando, ocasionará a perda de valores significativos devido aos gastos que a mesma acarretaria

e assim na qual pode culminar até mesmo na falência da empresa.

L.

De Life ou Vida são os casos em que a falha do sistema ocasiona a perda de vidas, tendo como referência

um software de piloto automático onde a sua falha poderia derrubar um avião e matar os tripulantes e

todos os passageiros.

Assim, de acordo com o tamanho do projeto, tamanho da equipe e a sua criticidade, devemos escolher

o método que melhor se adeque a ele.

Características da Metodologia Crystal Independentemente de qual implementação CRYSTAL você escolhe.

Você encontrará sete princípios chave em cada um.

Entrega frequente Os proprietários de projetos cliente podem esperar resultados da equipe a cada dois

meses, quando são considerados mais projetos.

As entregas podem não entrar em produção diretamente, pois dependem de integrações, mas os interessados

irão ver as versões intermediárias e assim serem capazes de fornecer feedback.

Feedback contínuo Toda equipe de projeto se reúne regularmente para discutir as atividades do projeto.

A equipe também se reúne regularmente com as partes interessadas para garantir que o projeto está caminhando

na direção esperada e comunicar quaisquer novas descobertas que possam afetar o projeto.

Comunicação constante Espera se que para projetos menores, a equipe esteja toda localizada na mesma

sala.

Já para projetos maiores, é esperado que possam estar localizados no mesmo edifício ou andar.

Todos os projetos esperam ter acesso frequente às pessoas que definam os requisitos de segurança.

Cristal é algo único em seu foco no aspecto da segurança de desenvolvimento de software.

Isto vem em dois aspectos, sendo que um deles é a zona segura para que os membros da equipe sejam eficazes

na comunicação da verdade durante o projeto, sem medo de represálias.

O outro aspecto relativo à segurança que só o cristão reconhece, é que a finalidade de cada projeto

de software varia e que alguns projetos afetam a segurança de seus usuários finais, enquanto outros

não.

Por exemplo, um sistema de ônibus espacial é muito mais crítico do que o software de uma batedeira

de bolo foco.

Os membros da equipe devem trabalhar em no máximo dois ou três itens prioritários cada um, e também

devem trabalhar sem interrupções.

Acesso aos usuários finais Como a maioria dos métodos ágeis, Kristol espera que a equipe do projeto

tenha acesso a um ou mais usuários do sistema a ser construído.

Testes automatizados e de integração O Crystal tem várias formas para verificação da funcionalidade

desenvolvida.

Controles devem ser postos em prática para apoiar a versão, tais como testes automatizados e frequente

integração dos componentes desenvolvidos.












## MSDM
## TDD
## FDD
##  KanBan
