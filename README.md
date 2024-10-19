# Java CI Pipeline

Este repositório contém um exemplo de configuração de um pipeline de Integração Contínua (CI) para um projeto Java utilizando GitHub Actions.

## Estrutura do Repositório

java-ci-pipeline/ ├── src/ │ ├── main/ │ │ └── java/ │ └── test/ │ └── java/ ├── .github/ │ └── workflows/ ├── .gitignore ├── README.md └── pom.xml

## Etapas do Pipeline

1. **Build**: O código é compilado usando Maven.
2. **Testes**: Testes unitários são executados para garantir a integridade do código.
3. **Análise de Código**: O código é analisado usando SonarCloud.
4. **Deploy**: O artefato é implantado em um ambiente de homologação simulado.

## Diagrama do Pipeline

![image](https://github.com/user-attachments/assets/38669230-c58d-4724-a053-8ef49ecbed1e)

## Como Executar

1. Faça um fork deste repositório.
2. Configure os segredos do GitHub (`SONAR_TOKEN`).
3. Realize um commit ou um pull request para ver o pipeline em ação.

## Ferramentas Utilizadas

- **GitHub Actions**: Para orquestração do pipeline.
- **Maven**: Para build e gerenciamento de dependências.
- **JUnit**: Para testes unitários.
- **SonarCloud**: Para análise de qualidade do código.
- **GitHub Pages**: Para deploy simulado.
