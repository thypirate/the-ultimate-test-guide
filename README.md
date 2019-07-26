# the-ultimate-test-guide
> Este repositório foi feito com a intenção de ajudar no planeamento e na execução de testes de aplicações web.

Conteúdos
---
+ [Abordagem para planeamento de testes](#)
+ [Test cases](#)
+ [Manual vs automático](#)
+ [Bug backlog](#)
+ [Material de leitura](#)


### Abordagem para planeamento de testes
---
Podemos resumir o processo de desenvolvimento clássico de um produto com: **idea -> feature -> development -> testing -> release**.
Antes da execução de qualquer teste, o tester deve criar um plano de teste juntamente com o gestor do projeto ou com a equipa de desenvolvimento. Mas antes isso é preciso saber o critério de aceitação ou *acceptance criteria*. 
Critério de aceitação trata-se de um conjunto de regras formais de como uma funcionalidade deve comportar e normalmente são definidas pelo dono de projeto.
O plano de teste tem os seguintes tópicos:
* Escopo do teste (objetivos);
* Tempo de execução (tempo estimado para execução do teste);
* Entregas (relatórios e datas geradas pelo teste);
* Critérios para passagem de produção (condição para passagem de produção);
* Riscos e contigência (medição de incertezas de teste);
* Test cases;

### Test cases
---
Os test cases podem ser organizados da seguinte forma:
* Nome do teste - ex. Cliente - Criar/Registar;
* Pré-requisitos - ex. O utilizador deve estar com a sessão iniciada e estar na página de registo de cliente;
* Passos -> numero; Passo (descrição do passo) ex. Click na caixa de texto “Título”. Escolher a opção  “Sra.”. Resultado Esperado ex. “Sra.” encontra-se escrito na caixa de texto.
* Desmantelar - ex. Eliminar o cliente com o nome “Isabela Souza Costa”.

Test cases por ser visto de duas formas :
*Happy paths* -> o tester testa com o fim de atingir o resultado desejado/esperado;
*Edgy cases* -> o tester testa com o fim de explorar a aplicação encontrando ou não falhas.

### Manual e automático
---
Um **teste manual** é quando o teste de um software ou aplicação web é feito manualmente pelo tester com objetivo de encontrar bugs no software ou aplicação web a ser desenvolvido. O tester verifica todas as funcionalidades essenciais do sujeito software ou aplicação web executando todos os *test cases* e gerando relatórios sem ajuda de ferramentos de automatização.
Um **teste automático ou automatizado** é quando os testers escrevem código/scripts para automatizar a execução de um teste. O objectivo e completar a execução do teste em menor tempo possível.

### Bug backlog
---


### Material de leitura
---
+ [Usability Testing Tutorial: Need, Process, Best Practice](https://www.guru99.com/usability-testing-tutorial.html)
+ [Automation Testing Vs. Manual Testing: What’s the Difference?](https://www.guru99.com/difference-automated-vs-manual-testing.html)
+ [Automation Testing Tutorial: Process, Planning & Tools](https://www.guru99.com/automation-testing.html)
+ [What is Regression Testing? Test Cases, Tools & Examples](https://www.guru99.com/regression-testing.html)
+ [Integration Testing Tutorial: Big Bang, Top Down & Bottom Up](https://www.guru99.com/integration-testing.html)
+ [GUI Testing: Complete Guide](https://www.guru99.com/gui-testing.html)
+ [Functional Testing](https://test.io/functional-testing/)
