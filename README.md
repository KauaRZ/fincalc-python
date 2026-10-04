# FinCalc - Sistema de Cálculos Financeiros

Sistema desenvolvido em Python para realização de cálculos financeiros, como parte da atividade prática da disciplina de **Gestão de Configuração e DevOps**.

## 📚 Sobre o projeto

O FinCalc tem como objetivo implementar diferentes funcionalidades de cálculos financeiros, utilizando práticas de desenvolvimento colaborativo, controle de versão e integração e entrega contínuas.

Durante o desenvolvimento serão utilizados:

- Git e GitHub para controle de versão;
- Branches para desenvolvimento das funcionalidades;
- Pull Requests para integração do código;
- Code Review entre os integrantes;
- GitHub Actions para Integração Contínua (CI);
- GitHub Codespaces como ambiente de desenvolvimento;
- Self-hosted Runner para simulação de Continuous Delivery (CD);
- Flake8 para análise de qualidade do código;
- Bandit para análise de segurança.

## 🧮 Funcionalidades

O sistema contará com funcionalidades relacionadas a cálculos financeiros, incluindo:

- Juros simples;
- Juros compostos;
- Simulação de aposentadoria;
- Cálculo de IRRF;
- Financiamento pelo sistema Price;
- Depreciação linear;
- Valor futuro com aportes periódicos;
- Conversão de taxa anual para mensal;
- Lucro líquido e margem operacional;
- Retorno real ajustado pela inflação.

## 🛠️ Tecnologias utilizadas

- **Python**
- **Git**
- **GitHub**
- **GitHub Codespaces**
- **GitHub Actions**
- **Flake8**
- **Bandit**

## 🌿 Estratégia de desenvolvimento

Cada funcionalidade será desenvolvida em uma branch específica e posteriormente integrada à branch `main` por meio de Pull Requests.

Fluxo utilizado:

```text
main
 │
 ├── feature/juros-compostos
 ├── feature/simulacao-aposentadoria
 ├── feature/irrf
 ├── feature/financiamento-price
 ├── feature/depreciacao-linear
 ├── feature/valor-futuro
 ├── feature/conversao-taxa
 ├── feature/lucro-margem
 └── feature/retorno-real
