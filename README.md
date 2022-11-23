# Node.js: testes de unidade e de integração

<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"><img src="/logos/JavaScript.png" alt="Logo JavaScript" widht="80" height="80"></a> <img src="/logos/VS Code.png" alt="Logo do VS Code" widht="80" height="80"> <a href="https://jestjs.io/pt-BR/docs/configuration" target="_blank"><img src="/logos/jest.png" alt="Logo Jest" widht="80" height="80"></a>

-----
## Objetivos deste treinamento:
+ Aprender os conceitos de testes e como utilizá-los;
+ Entender a importância e os benefícios de testar o código;
+ Fazer testes unitários com Jest; e
+ Fazer testes de integração com Supertest.

*****

Este treinamento faz parte da **Formação em Node.js com Express: Criando APIs REST em Node com Express**, tópicos abordados:
1. Conceituando testes
2. Asserções e Jest
3. Implementando testes
4. Testando uma API
5. Testando rotas

## Introduction
Concepts and fundamentals of testing in applications and software, what is a testing culture and how can we implement it. What are static tests and unit tests and practice with exercises. Know the statements, their meaning and importance. Implement tests in frameworks such as Jest and SuperTest.

## 1. Conceituando testes
**Habilidades desenvolvidas neste tópico:**
+ Aumentar a confiabilidade e qualidade do código;
+ Tipos de testes que podemos implementar, como: os estáticos, unitários, de integração e E2E:
  - **Testes estáticos:** analisa o código sem necessariamente executá-lo, verificando se as boas práticas e formatação padronizada foram adotadas na implementação;
  - **Testes unitários:** utilizados para verificar o comportamento das menores unidades de código da aplicação;
  - **Testes de integração:** os módulos do software são combinados e testados como um conjunto;
  - **Teste E2E (End-to-End):** método utilizado para testar um fluxo da aplicação desde o começo até o fim.
+ Ter uma cultura de testes e alguns de seus benefícios, como a padronização e estabelecimento de processos para o nosso projeto;
+ Utilizar o ESLint para fazer testes estáticos em JS estabelecendo um padrão de escrita para o código, verificando se há divergências entre o código escrito e o padrão adotado e também analisando a estrutura do projeto em busca de problemas como módulos inexistentes, falta de clareza nas declarações etc; e
+ Implementar os primeiros testes de unidade utilizando um código implementado do zero.

## 2. Asserções e Jest
**Habilidades desenvolvidas neste tópico:**
+ Utilizar métodos nativos de asserções para fins de comparação de igualdade;
+ Instalar e executar o **Jest** com a *flag --experimental*;
+ Criar arquivos de testes com o **Jest** e analisar erros;
+ Usar a função *describe* um método do **Jest** usado para conjunto de testes relacionados. O describe possui a sintaxe de dois argumentos:
  - Uma *string* para descrever;
  - Uma *função callback* para executar o teste.
+ Gerar relatório com o *coverage*, uma ferramenta integrada do *jest* para cobertura de testes, que possibilita identificar caminhos não testados no código.
