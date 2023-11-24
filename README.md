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
- Para gerar o relatório de teste de cobertura, clique com o botão esquerdo sobre o projeto no Netbeans, vá até Code Coverage e Show Reports, conforme a imagem a seguir:

<img src="https://github.com/GQS-2023/BancoJunitSuiteMetricsCoverage/assets/45953979/71c0e31c-710a-4fbe-a423-619ccacaeb64" alt="jacoco" />

- A seguinte tela aparecerá mostrando uma tabela com os nomes das classes do projeto, na coluna "Coverage", a porcentagem de teste de cobertura realizado em cada classe. Na coluna "Total", mostra o número de linhas passíveis de teste e na coluna "Not Executed" exibe quantas das linhas não foram testadas. 

<img src="https://github.com/GQS-2023/BancoJunitSuiteMetricsCoverage/assets/45953979/370287c6-df92-4442-9c39-5e3a1e36fefa" alt="jacoco" />

Além da tela apresentada, na pasta do projeto, tem-se esse relatório mais detalhado em target -> site -> jacoco -> index.html

- [x] Inspeção pelo Metrics 


# ✨ Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Java](https://www.oracle.com/br/java/technologies/downloads/), [Apache Netbeans] (https://netbeans.apache.org/) 
1. Esse projeto usa Maven, para isso siga as orientações a seguir:
   - Adicionar as dependências (maven-surefire-plugin, junit-jupiter-api, junit-jupiter-engine, org.hamcrest, junit-platform-suite-api, junit-platform-suite-engine,metrics-core) no arquivo pom.xml do projeto. Consulte a dependência em https://mvnrepository.com/
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



