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

## MSDM
## TDD
## FDD
##  KanBan
