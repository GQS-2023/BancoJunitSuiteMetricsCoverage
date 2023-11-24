<p align="center">
  <a href="https://unform.dev">
    <img src="https://github.com/GQS-2023/BancoJunit/assets/45953979/5f26de80-b7fa-4f30-8946-74531d8a6da9" height="150" width="175" alt="banco" />
  </a>
</p>

<p align="center">Relatório usando Metrics e Coverage da aplicação Banco Junit Suite 🚀</p>

<div align="center" style="display: inline_block"><br>
  <img align="center" alt="Junit" height="30" width="40" src="">
  <img align="center" alt="Java" height="30" width="40" src="https://github.com/devicons/devicon/blob/master/icons/java/java-original-wordmark.svg">
  <img align="center" alt="Maven" height="30" width="40" src="https://upload.wikimedia.org/wikipedia/commons/5/52/Apache_Maven_logo.svg">
  <img align="center" alt="Jacoco" height="30" width="40" src="">
  <img align="center" alt="Metrics" height="30" width="40" src="">
</div>

# 💻 Relatório usando Metrics e Coverage da aplicação Banco Junit Suite

<p> Exemplo de Gerenciamento de Cliente e Conta Bancária usando Metrics e Coverage.</p>

<h4 align="center"> 
	🚧  Gerenciamento Concluído 🚀 🚧
</h4>

<p align="center">
 <a href="#-funcionalidades">Funcionalidades</a> •
 <a href="#-tecnologias">Tecnologias</a> • 
 <a href="#-autor">Autor</a> • 
 <a href="#user-content--licença">Licença</a>
</p>


### ⚙️ Funcionalidades

- [x] Relatório usando Code Coverage Jacoco

  As métricas de cobertura de teste são usadas para medir e monitorar sua atividade de teste.

- Para gerar o relatório de teste de cobertura, adicione o plugin "jacoco-maven-plugin" ao projeto.

<img src="https://github.com/GQS-2023/BancoJunitSuiteMetricsCoverage/assets/45953979/7ffb876a-31ed-4cc7-90b5-feb86c7245b8" height="350" width="550" alt="jacoco" />

- Depois clique com o botão esquerdo sobre o projeto no Netbeans, vá até Code Coverage e Show Reports, conforme a imagem a seguir:

<img src="https://github.com/GQS-2023/BancoJunitSuiteMetricsCoverage/assets/45953979/71c0e31c-710a-4fbe-a423-619ccacaeb64" alt="jacoco" />

- A seguinte tela aparecerá mostrando uma tabela com os nomes das classes do projeto, na coluna "Coverage", a porcentagem de teste de cobertura realizado em cada classe. Na coluna "Total", mostra o número de linhas passíveis de teste e na coluna "Not Executed" exibe quantas das linhas não foram testadas. 

<img src="https://github.com/GQS-2023/BancoJunitSuiteMetricsCoverage/assets/45953979/370287c6-df92-4442-9c39-5e3a1e36fefa" alt="jacoco" />

Além da tela apresentada, na pasta do projeto, tem-se esse relatório mais detalhado em target -> site -> jacoco -> index.html

<img src="https://github.com/GQS-2023/BancoJunitSuiteMetricsCoverage/assets/45953979/99b96442-9774-4010-a92c-b824c00a8f7f" alt="jacoco" />
<img src="https://github.com/GQS-2023/BancoJunitSuiteMetricsCoverage/assets/45953979/d90f1e11-dcae-4111-a23e-d20c1a975ee7" alt="jacoco" />

- [x] Inspeção pelo Metrics 
A ferramenta JavaMetrics calcula uma série de métricas úteis para conjuntos de código-fonte de programas Java. É um membro da família de ferramentas de métricas de código-fonte da SD.

- Recursos de métricas Java
	- Operação repetível em um conjunto especificado de arquivos
	- Métricas calculadas no nível do módulo:
	- Linhas de código fonte (SLOC)
	- Linhas de código fonte não comentadas
	- Linhas de comentários
	- Número de métodos
	- Densidade de Decisão
	- Complexidade ciclomática
	- Aninhamento máximo de loop
	- Aninhamento condicional máximo
	- Medidas Halstead (volume, dificuldade e esforço)
	- Índice de Manutenção do Instituto de Engenharia de Software (SEI)
	- Contagens de classes, pacotes e arquivos
	- Métricas de aninhamento de pior caso identificadas para arquivo/linha específico
	- Resumos por classe/arquivo/pacote
	- Relatório de texto
	- Relatório XML, reformatável da forma desejada (exemplo)

- Para inspecionar o código da aplicação criada acesse na barra de menus do Netbeans Source -> Inspect. 

<img src="https://github.com/GQS-2023/BancoJunitSuiteMetricsCoverage/assets/45953979/9d6bc90f-7355-4b16-9e93-acec2934051d" alt="metrics" />

- Defina o projeto que deseja inspecionar em "scope" e use a congiguração Default e clique em "Manage".
  
<img src="https://github.com/GQS-2023/BancoJunitSuiteMetricsCoverage/assets/45953979/7223462d-895a-4c66-b8a8-0d00d51bf3ad" alt="metrics" />

- Em Analyzer, escolha "Netbeans Java Hints" e em inspections, marque "Java Code Metrics" e clique em  "OK" e na tela anterior clique em "Inspect".

<img src="https://github.com/GQS-2023/BancoJunitSuiteMetricsCoverage/assets/45953979/5028c0f6-4abb-4c5f-b8ef-2e2b28092440" alt="metrics" />

- A aba "Inpector" será exibida e caso tenha alguma observação será mostrada nessa tela. 

<img src="https://github.com/GQS-2023/BancoJunitSuiteMetricsCoverage/assets/45953979/38ae21a9-4481-4c77-be52-a6d23fa70fdc" alt="metrics" />

- Analise as observações e melhore o código!
- Aqui será mostrado a aplicação Banco Junit Suite já com as alterações para melhorar o código.

# ✨ Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Java](https://www.oracle.com/br/java/technologies/downloads/), [Apache Netbeans] (https://netbeans.apache.org/) 
1. Esse projeto usa Maven, para isso siga as orientações a seguir:
   - Adicionar as dependências (maven-surefire-plugin, junit-jupiter-api, junit-jupiter-engine, org.hamcrest, junit-platform-suite-api, junit-platform-suite-engine, metrics-core) no arquivo pom.xml do projeto. Consulte a dependência em https://mvnrepository.com/
   - Adicionar plugin (maven-surefire-plugin, jacoco-maven-plugin) no build do arquivo pom.xml do projeto. 
   - A organização do projeto segue a seguinte estrutura:
     - Projeto
       - Source Packages(src)
         - Classes .java para entidades e lógica do projeto
       - Teste Packages(test)
         - Classes .java para os testes
           
  Obs: caso esses pacotes não apareçam ao criar o projeto, é necessário adicioná-los manualmente.  

### 🛠 Tecnologias
- [x] JAVA
- [x] Apache Netbeans 18 
- [x] Junit 5
- [x] Metrics
- [x] Jacoco Code Coverage  

## 🦸 Autor

Rafaela Priscila Cruz Moreira

## 📝 Licença

Este projeto esta sobe a licença [MIT](./LICENSE).



